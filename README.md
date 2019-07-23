# Introduction to IRB

## Objectives

1. Describe IRB and why it's useful when programming.
2. Distinguish IRB from your terminal and other files.
3. Access and exit IRB via your terminal.
4. Execute commands in IRB.

<iframe width="960" height="720" src="https://www.youtube.com/embed/WWh1uxqQI48?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

[MP4](http://learn-co-videos.s3.amazonaws.com/ruby/intro-to-irb.mp4)

## What is IRB?

IRB stands for "Interactive Ruby." It's a Ruby shell or REPL. REPL stands for
read–eval–print loop. It is a simple, interactive computer programming
environment that takes user inputs (such as, in our case, snippets of Ruby
code), evaluates them, and returns the result to the user. IRB is run by your
computer's terminal. 

> **Reminder**: The term 'terminal' refers to the program we use to
> communicate with our computer via text input. We can type commands one
> by one into the terminal and it will return responses, similar to the 
> way people used computers before graphical user interfaces.

You can think of it as your Ruby playground or execution
environment. You can open it up, insert code and execute it to see that code's
return value.

## What _isn't_ IRB?

IRB is not a file where you save your work. Any coding you do in the IRB console
in your terminal will not get saved anywhere. It only exists temporarily. IRB is
for testing, playing, manipulating your code so that you understand it better
and solve problems with it.

## How do you use it?

IRB allows you to execute ruby in the terminal and you're going to get
comfortable using it to test and better understand your Ruby code. To access
IRB, just type `irb` in the terminal. 

IRB allows you to do anything you can do
in a Ruby file. For instance, you can do math, get the time by typing
`Time.now`, or print text to the screen.

## Instructions

1. Open up your terminal.

   - If Sandbox is enabled, on this lesson's Learn page, you should see a 'Sandbox'
   button that will open Learn's in-browser IDE. The terminal is the at the bottom 
   of the IDE ([check this page out for more information][help])
   - If you do not have Sandbox, or are not sure how to access the terminal on 
   your computer, you can also go to [repl.it][repl] and create a Ruby based Repl 
   to follow along. Repl.it, just like Sandbox, provides a simulated terminal in 
   the browser that is ready to receive Ruby commands.

[help]: https://help.learn.co/en/articles/1862105-ide-in-browser-sandbox

2. In the terminal, type `irb` and hit `return` (if you're using Repl.it, 
you can skip this as the terminal is already set to read Ruby).

3. Now that you've started IRB, type the commands below to see how it works!
   Type each of the following lines into the IRB shell and press enter.

- `Time.now`
- `255 / 5`
- `9 ** 2`
- `puts "hello world"`

4. To leave IRB, type the `exit` command - this will get you back to your
   command line.

[repl]: https://repl.it/

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/irb-readme' title='Introduction to IRB'>Introduction to IRB</a> on Learn.co and start learning to code for free.</p>
