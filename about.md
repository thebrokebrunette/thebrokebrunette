---
layout: default
title: Howdy, I'm The Broke Brunette!
---

<html>
  	<head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1">
            <title>Example Site</title>
            <link rel="stylesheet" href="site.css">
      <style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 10px 10px;
  overflow: hidden;
  background-color: #294733;
}

li {
  float: left;
}

li a, .dropbtn {
  display: inline-block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
  background-color: #627D62;
}

li.dropdown {
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: white;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  color: #294733;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {background-color: #627D62;}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>
    </head>
  <body>    
 
     <div class="topnav">
         <right>   
  <input type="text" placeholder="Search..">
  </right>
    </div>
  </right>
    

    
<ul>
  <center>
  <li><a href="/about.html">About</a></li>
  <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">High School</a>
    <div class="dropdown-content">
      <a href="#">Jobs</a>
      <a href="#">Saving</a>
      <a href="#">College Prep</a>
        <li class="dropdown">   
      <a href="javascript:void(0)" class="dropbtn">College</a>
    <div class="dropdown-content">
      <a href="#">Budgeting</a>
      <a href="#">Saving</a>
      <a href="#">College Life</a>
        <li class="dropdown">  
      <a href="javascript:void(0)" class="dropbtn">Career</a>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
      </center>
    </div>
  </li>
</ul>
      
    <div class="posts">
          {% for post in site.posts %}
            <article class="post">
              <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
            </article>
          {% endfor %}
        </div>
  </body>
  </html>

Welcome to my blog! This is my space to discuss all things personal finance!

My name is Brooke Johnson. I am a Texas A&M Former Student (Class of 2020 – WHOOP!), a (soon-to-be) wife, and a strong believer that everyone should be in control of their money, especially women.

I started The Broke Brunette when I wanted to learn more about finance during my junior year of college. I wanted a space to discuss the topics I love to learn about, like budgeting and investing. I write about topics that I have already learned about such as high school jobs and how to pay for college, as well as topics I do not know enough about like how much should I save every month. I write to spread what I have learned in hopes that it will help someone else, but also to learn more about my own finances.

In addition to the blog, The Broke Brunette also is a podcast and a YouTube channel!

Follow us on all social media accounts!
Facebook
Instagram
Twitter
TikTok
