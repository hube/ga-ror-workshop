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

---

![GeneralAssemb.ly](assets/Exercise_icon_md.png)
##Draw The Internet

Time: 7 minutes

1. Grab a whiteboard marker
2. Draw a diagram that represents your understanding of how the Internet works.
  Here are some questions to consider as you draw:
  * What happens when you hit enter on your address bar?
  * Where does a website live?
  * What does a webserver need to do in order to respond to your request?
3. Share with the rest of the class and let's discuss

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

##The Command Line
###What is it?

The command line is a terminal giving you direct access to your operating
system. You can enter simple commands to perform a variety of functions.

Many of the tasks we need to carry out (such as running the Rails server) are
best performed in the command line.

---

##The Command Line
###Where do I start?

For Macs:

* Open the "Terminal" app
* For a better experience, try [iTerm 2](https://www.iterm2.com/)

For Windows:

* Open the "Command Prompt" application
* For a better experience, try [Console2](http://sourceforge.net/projects/console/)

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
###Generators

```bash
$ rails generate model Book author:string title:string abstract:text
$ rails generate model Shelf category:string
$ rails generate controller books
```

* Generators provide the bare necessities for adding a resource or model to your Rails app

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
