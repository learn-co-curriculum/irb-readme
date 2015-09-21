# Introduction to IRB

## Objectives

1. Understand what IRB is
2. Get comfortable using IRB to execute Ruby code

<video controls width="100%">
  <source src="http://learn-co-videos.s3.amazonaws.com/ruby/intro-to-irb.mp4" type="video/mp4" >
    The video accompanying this lab is best enjoyed on Learn.co
</video>

[MP4](http://learn-co-videos.s3.amazonaws.com/ruby/intro-to-irb.mp4)



## What is IRB?

IRB stands for "interactive ruby", it's a ruby shell or REPL. REPL stands for read–eval–print loop. It is a simple, interactive computer programming environment that takes user inputs (such as, in our case, snippets of Ruby code), evaluates them, and returns the result to the user. IRB is run by your computer's terminal. You can think of it as your Ruby playground or execution environment. You can open it up, insert code and execute it to see that code's return value. 

## How do you use it?

IRB allows you to execute ruby in the terminal and you're going to get comfortable using it to test and better understand your Ruby code. To access IRB, just type `irb` in the terminal. IRB allows you to do anything you can do in a Ruby file. For instance, you can do math, get the time by typing `Time.now`, or print text to the screen.

## Instructions

1. Open up your terminal.
2. Type `irb` and hit `return`
3. Now that you've started IRB, type the commands below to see how it works! Type each of the following lines into the irb shell and press enter.
  
  * `Time.now`
  * `255 / 5`
  * `9 ** 2`
  * `puts "hello world"`
4. To leave irb, type the `exit` command - this will get you back to your command line.
