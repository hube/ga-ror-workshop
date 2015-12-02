![GeneralAssemb.ly](assets/ga.png "GeneralAssemb.ly")

##Building Delightful Apps with Ruby on Rails
###Hubert Lee

---

##Introductions!

* Your name
* What you do
* What you hope to get out of this workshop

---

##Agenda

* What is Web Development?
* Ruby on Rails
* Developer Basics
  * The File System
  * The Command Line
* Our First Rails App

* Please feel free to ask questions at any time!

---

##Web Development
###Basic Concepts

Let's define a few terms:

* _Web Development_ <span class="fragment" data-fragment-index="1"> - building applications available on the web</span>
* _Website_ <span class="fragment" data-fragment-index="2"> - a website provides **_static_** content on the web</span>
* _Webapp_ <span class="fragment" data-fragment-index="3"> - a webapp provides **_dynamic_** content on the web</span>
* _Front-End Development_ <span class="fragment" data-fragment-index="4"> - client / browser code (HTML, CSS, JavaScript)</span>
* _Back-End Development_ <span class="fragment" data-fragment-index="5"> - server-side code (Ruby, C#.NET, Java)</span>

---

##Web Development
###How the internet works

* To understand Ruby on Rails we need to understand the internet
  * What happens when you hit enter on your address bar?
  * Where does a website live?
  * What does a webserver need to do in order to respond to your request?

---

##Web Development
###How the Internet Works

![](assets/server-side.jpg)

---

##Ruby on Rails
###Background

* Ruby on Rails is an open source web framework written in the Ruby programming
  language.
* Allows you to create interactive web applications that query a database
* Created by David Heinemer Hansson (@dhh) to simplify the task of building web
  applications, emphasizing _convention over configuration_

<div style="text-align:center;">
  ![](assets/rails.png)
</div>

---

##Ruby on Rails
###Framework

Ruby on Rails provides solutions to the most common problems faced when building
websites.

* Routing
* Templating
* Database abstraction
* And more!

---

##Ruby on Rails
###Websites built on Rails

* Twitter
* Airbnb
* Groupon
* Shopify
* Beecrazy
* General Assembly

See more [here](http://www.developerdrive.com/2011/09/20-best-sites-built-with-ruby-on-rails/)

---

##Ruby on Rails
###Architecture: MVC

![](assets/mvc_diagram.png)

---

##Developer Basics
###The File System: What is it?

The file system is how your computer stores and organizes data. Operating
systems commonly use a hierarchical structure to organize data with
**directories** (or **folders**) and **files**.

<span class="fragment" data-fragment-index="1">
**Windows Explorer** and the Mac **Finder** are both applications that let you
explore your computer's file system visually.
</span>

---

##Developer Basics
###The File System: What is it?

Files within a file system may be uniquely identified by their file path
(location within the file system). E.g.:

* `C:\Users\Hube\Desktop\hello.txt` (Windows)
* `/Users/hube/Desktop/hello.txt` (Mac)
* `/home/hube/hello.txt` (Linux)

---

##Developer Basics
###The Command Line: What is it?

The command line is a terminal giving you direct access to your operating
system. You can enter simple commands to perform a variety of functions.

Many of the tasks we need to carry out (such as running the Rails server) can
only be performed on the command line.

---

##Developer Basics
###The Command Line: Where do I start?

For Windows:

* Open the "Command Prompt" application
* For a better experience, try [Console2](http://sourceforge.net/projects/console/)

For Macs:

* Open the "Terminal" app
* For a better experience, try [iTerm 2](https://www.iterm2.com/)

---

##Developer Basics
###The Command Line: Basic commands

* `dir <path>` (Windows)/`ls <path>` (Mac/Linux) - **L**i**s**t directory contents
* `cd` (Windows)/`pwd` (Mac/Linux) - Show path to **c**urrent **d**irectory
* `mkdir <name>` (Windows/Mac/Linux) - **M**ake a **dir**ectory

Basic reference also available in the
[workshop wiki](https://github.com/hube/ga-ror-workshop-1/wiki/CLI-Reference)

---

##Developer Basics
###The Command Line: Shortcuts

When specifying paths as part of a command, we have two shortcut placeholders
we can use:

* `.` - represents the current directory
* `..` - represents the parent directory
* `%USERPROFILE%` (Windows) or `~` (Mac/Linux) - represents the home directory
* `\` (Windows) or `/` (Mac/Linux) - represents the root directory (the top of the file system)

---

##Developer Basics
###The Command Line: Pop Quiz

1. What do the following commands do?
  * `cd ~`
  * `mkdir ~/code`
  * `ls ..`
2. What command would you enter to do the following:
  * Navigate to the root directory
  * Navigate up two directories
  * Create a directory called "work" in the root directory

---

##Our First Rails App

Instructions at https://github.com/hube/ga-ror-workshop-1

---

##Recap
###Create a New App

```bash
$ rails new my_app_name
$ cd my_app_name
```

---

##Recap
###Create the database tables

```bash
$ rake db:migrate
```

---

##Recap
###Start the server

```bash
$ rails s
```

* Go to [http://localhost:3000](http://localhost:3000) in a browser

---

##Recap
###Scaffolds

```bash
$ rails generate scaffold Book author:string title:string abstract:text
$ rails generate scaffold Shelf category:string
```

* Scaffolds generate the necessary files for adding a model to your Rails app

---

##Recap

* Web Development
  * Website vs Webapp
  * Frontend vs Backend
  * How the Internet Works: Request/response Cycle
* Ruby on Rails
* The Command Line
* Our First Rails App

---

##The Road Goes Ever On
###Additional Topics

* Collaboration tools
  * Version control systems (e.g. Git, Mercurial)
  * GitHub
* Testing
  * RSpec
* Deployment
  * Heroku
  * AWS

---

##The Road Goes Ever On
###Learning Resources

* [Rails Guides](http://guides.rubyonrails.org/)
* [Codecademy RoR](http://www.codecademy.com/learn/learn-rails)
* [Codecademy Ruby](http://www.codecademy.com/tracks/ruby)
* [Coursera](https://www.coursera.org/)

---

##Working Like a Developer

* Leverage the online community's vast libraries and documentation (Google is your best friend)
* Share the knowledge you gain and give back to the community when you can
* Take pride and joy in what you work on
* Be efficient:
  * Use the keyboard and shortcut keys as much as possible
  * If you find yourself doing the same thing repeatedly, automate it
