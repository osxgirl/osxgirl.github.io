---
layout: post
title:      "Code a Ruby Rainbow 🌈🤖"
date:       2018-02-06 18:08:40 +0000
permalink:  code_a_ruby_rainbow
---


in·ter·po·la·tion #

inˌtərpəˈlāSH(ə)n/

noun : the insertion of something of a different nature into something else.


**Let’s program a rainbow! **🌈 🤖 

So… we need to talk to the machine by using the Ruby Programming Language. We have that already installed and setup and now we can open Mac Terminal and Xcode to get going. But first, let’s ask ourselves some questions. We need step by step understanding on how to produce a coded rainbow.        

What colors are in the rainbow?
In what format do we provide the color listing to the computer? 
What method do we need to tell the machine to process (think)? 🤔 
How can the color listing interpolate in to the machines method (thought process)?
How can we tell the machine to show us what it’s thinking? 


**Let’s answer them in Xcode!** 🌈 🤖 


The colors are:
red, orange, yellow, green, blue, indigo, and violet


The color listing format is an array set to equal a variable of “colors”:
colors = ["red", "orange", "yellow" "green", "blue", "indigo", "violet"]


The defined method has an argument of the variable “colors”:
def display_rainbow(colors)
end

What we are doing is saying: hey computer, the colors are equal to these and what your thinking about and going to process for us is called method display_rainbow. But how can it take the colors and interpolate them into the method and print out our “colors”?

puts "R: #{colors[0]}, O: #{colors[1]}, Y: #{colors[2]}, G: #{colors[3]}, B: #{colors[4]}, I: #{colors[5]}, V: #{colors[6]}"


Woah right? The hash (“#”) means to take the data from the “colors” array and interpolate them into a hash. The numbers in a hash always begin with “0”. 
Now we have our ruby code in Xcode.

​​

**Let’s Play! Let’s program a rainbow! **🌈 🤖 

On a Mac, open terminal & type:

irb



Press Enter



Copy & Paste this code:

colors = ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet']




Press Enter




Copy & Paste this code:
def display_rainbow(colors)
puts "R: #{colors[0]}, O: #{colors[1]}, Y: #{colors[2]}, G: #{colors[3]}, B: #{colors[4]}, I: #{colors[5]}, V: #{colors[6]}"
end



Press Enter



Now, Copy & Paste this code:
display_rainbow(colors)




Press Enter​​
The ruby rainbow: R: red, O: orange, Y: yellow, G: green, B: blue, I: indigo, V: violet


There are no colors showing up but the program believes it’s displaying a rainbow the same way you believe you see one. 🌈

**ty**

//♥️
