---
layout: post
title:      "Sinatra Project : yellow 💛"
date:       2018-09-03 13:35:38 -0400
permalink:  sinatra_project_-_yellow
---

A CRUD App : (Create Read Update Delete apps)

This is a MVC Sinatra application project that utilizes Active Record in creating a database that holds data for multiple Models. Our models are Users and Comments. The relationships between the two models are has_many & belongs_to. The user accounts can be created and users can only edit their comment entries. Just to be sure we obtain the users data, input validations are used.
I really enjoyed setting up this kind of application and working with databases!


<br>
Say hello to *yellow*!

The yellow app will nurture those who are in need of support with their Apple lifestyles. The application will greet you with a Log in & Sign Up screen, ask you create an account and save your support comments to a feed everyone can see until you delete your entries. That allows for others to see the issues and it may spark an idea for your technological growth. Along with the comments, Yellow will allow you to simply make a Video, Phone or Text to a service agent.
 

How did I build it?
I created the file project folder and subfolder based on my model selection and the necessary files for making them run. I then ran bundle init in my terminal to create a Gemile. I then created a config folder with an environment file to connect the database & app folder to the rest of the files. In order to function property the gems that I added were sinatra, ActiveRecord, sqlite3, rake_all, & shotgun. After adding them to the gem file, I ran bundle install. In order to load the environment and mount the application controllers, a config.ru file was created. Then, the application controller was created to configure the sessions, password secret, and get request.

Download the app here: <a href="https://github.com/osxgirl/Sinatra-Application">yellow</a>

Run the app in your terminal by using shotgun.

<p><a href="https://imgur.com/JAqOBU2"><img src="https://i.imgur.com/JAqOBU2.png" title="imgur.com" /></a></p>

<p><a href="https://imgur.com/cxAKUSr"><img src="https://i.imgur.com/cxAKUSr.png" title="imgur.com" /></a></p>

<p><a href="https://imgur.com/OqMNUG3"><img src="https://i.imgur.com/OqMNUG3.png" title="imgur.com" /></a></p>
￼
￼
￼
"yellow, I need help" ™

Bonus Features:
A super cool bonus feature would be to utilize the thumb print password entry when filling out the user profile form. A map to show where all the available techs are located. Also, the ability to upload a photo to the comment section & use a bot for the text 
(just for an immediate hello!).
