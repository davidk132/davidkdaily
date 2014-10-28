---
layout: post
title:  "MVC Means What's Old is New Again"
date:   2014-10-27
category: MVC
image: ""
image-title: ""
image-style: bottom
active: blog
---

I recently talked about bridging the gap between cutting edge technology and industries or professions who are not quite there yet. It happens all the time and is a cause for celebration, not distress. In the past year I have been digging deeper into the [Model - View - Controller](http://blog.codinghorror.com/understanding-model-view-controller) scheme for developing web apps.

My first foray into MVC was with [Ruby on Rails](http://rubyonrails.org). I was excited about the Ajax-y goodness of [Basecamp](https://basecamp.com) (and remember Backpack?) and I wanted to know more. I had been deeply submerged into productivity hacks and wanted more of that too. I bought [Getting Things Done](http://gettingthingsdone.com) an devoured it in a weekend. I had to be careful not to fall into the easy trap of spending so much time on my productivity apps and system that I would never actually do anything. Still, for a certain kind of mind it is a great thing. In fact, I even lent my GTD book to a former colleague. Unfortunately, he was disorganized enough that I never got it back.

MVC is excellently described elsewhere, so I will just say that it is a way to separate functions. The database and the tools to describe the information in the database go over here; the views that are shown on your browser all go over there, and the controllers that direct the flow of things goes in a neat pile *here*. A place for everything and everything in its place.

This practice works because you can easily document it all, you will remember it better when you have to add on new features in six months, and you can break your code into smaller and smaller pieces for easier refactoring.

Some time after Rails I stumbled across [Laravel](http://laravel.com). Written in PHP, Laravel has been billed as the savior to PHP's sloppy coding and poor readability. Bouncing back and forth between Rails (written in Ruby) and Laravel (written in PHP), the finer points of MVC become clearer. I learn more. I add another tool to the box; after all, some of my projects are in Wordpress, others in Jekyll, and others elsewhere. 

Moving on, MVC is work a look on the client side. [TodoMVC](http://todomvc.com) is a great web projects that charges you to create a simple ToDo app using any version of Javascript and frontend libraries. There are already amazing results and a clear sign that MVC is here to stay.

*Postscript*: Yes I know that there are other MVC systems written in Ruby, and especially PHP, and other languages like Python. I see you, PHP fans hovering around [CakePHP](http://www.cakephp.org), [CodeIgniter](https://ellislab.com/codeigniter), [Phalcon](http://phalconphp.com), [Symfony](http://www.symfony.com). There's room for everyone. Check out [bento.io](http://www.bento.io) and learn up.