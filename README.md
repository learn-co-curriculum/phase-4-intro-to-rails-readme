# Intro to Rails

## Learning Goals

- Understand the purpose of Rails
- Learn where to get help with Rails

## Welcome to Rails

Ruby on Rails was created by David Heinemeier Hansson in 2004. The idea arose
because he noticed that, as he was making web applications with Ruby, he was
copy pasting common parts from previous apps into his new work. As a developer,
he (and all of us) loved solving hard problems. The only way to get to solving
the hard problems that are unique to the domain you are working in is to go up a
**layer of abstraction**. The nitty-gritty of basic web apps should be removed
from your head. That was the idea behind Rails: it handles the repetitive code
that is common across apps and enables you to focus on the hard bits.

Have a ton of fun. Rails changed the way web apps are developed; enjoy the
spoils of many open source contributors' hard work. With over a decade of open
source contributions, Rails has evolved into one of the most powerful web
application frameworks available. Before we can start building applications, it
is important to first understand what the Ruby on Rails framework is... and what
it's not.

## Why Use a Framework?

If you wanted to put surround sound in your house, would you go and spend years
researching how to best fabricate speakers, learn how to transfer sound through
wires, weld your own sound board, and create from scratch every other component
that would be required to have a surround sound system in your home? Most likely
not. Instead it would be much smarter and more efficient to purchase a surround
sound system from an organization that already put in all of the research and
development work to create a professional system.

In the same way, when it comes to building a web application it would
technically be possible to build out all of the functionality yourself, but it's
typically a better idea to leverage a system that has already spent over a
decade developing the tools necessary for getting applications built.

## What is Ruby on Rails?

- **A web framework**: A web framework provides developers the tools they need
  in order to build applications. While every application is unique there are
  certain components that can be found in almost every application, such as:
  routing, asset management, database connections, and the list goes on. A good
  web framework gives developers these baseline tools so that they don't have to
  create the base application functionality for each new project.
- **A Ruby Gem**: At its core, Ruby on Rails is simply a set of Ruby code
  libraries, and since the entire codebase is open source you have the ability to
  review the framework to better understand how it works.
- **An MVC framework**: MVC stands for Model-View-Controller. MVC is a popular
  application architecture that helps developers naturally separate concerns and
  organize their applications properly. This setup encourages a specific set of
  conventions, such as placing the logic for the application in the model files,
  managing the code flow in the controllers, and displaying content to the user
  in the views.
- **An opinionated framework**: one way Rails speeds up developer productivity
  is by enforcing strong opinions about how your code should be organized, from
  folder structure to file and variable naming. This has a few benefits: it
  frees developers up from having to make decisions about these things, and it
  also allows for some powerful abstractions to help with our code. By following
  **convention over configuration**, we get the benefits of this abstraction
  without having to write nearly as much code as in some other frameworks.

_On a side, but very important, note: don't worry if some or all of what we just
reviewed seems foreign. We'll be covering everything in detail in future
lessons, so don't worry if it all feels a little overwhelming._

## How We Will Be Using Rails

When Rails was first developed, it was meant to build **full-stack MVC**
applications, where developers could write code for both the frontend and the
backend in one place. Rails can **also** be used to create APIs, so we can serve
data to a separate frontend web application, such as a Single Page Application
built with React.

In this phase, we'll be focusing primarily on **Rails as an API** to serve JSON
data. By the end of the phase, you'll be able to build out a full-stack
application with Rails as a backend, and React as a frontend.

## How to Get Help with Rails

As you're learning about Rails, make sure to bookmark the
[Ruby on Rails Guides][rails-guides] and refer back to it often! Rails is a very
mature framework with a lot of great features. While we'll be covering a good
amount of those features in this phase, there's a whole lot more to explore.

The Rails guides are full of great examples and are always kept up to date with
the latest version of Rails, so they should be your go-to source any time
you're curious about what Rails can do.

[rails-guides]: https://guides.rubyonrails.org/

## Check For Understanding

Before you move on, make sure you can answer the following questions:

1. What do we mean when we say that Rails is a _framework_?
2. What do we mean when we say that Rails is _opinionated_? What are the
   advantages and disadvantages of this characteristic of Rails?
