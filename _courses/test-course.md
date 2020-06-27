---
layout: course
title: Test course
tags: tag
track: track
description: a summary
hide: false
author:
  - Ashley
lessons:
  - lessonlayout: learn
    title: Variables
    content: >+
      
      ## Introduction to Variables<a name="lesson">

      Okay, so we've learned that programming is really just giving your computer instructions in a way that it can understand.


      In order to do this, it's helpful to store information that we can reference over and over. This way we can keep telling the computer, "Hey, look at this!", and it will know what we're talking about.


      To store information, we use _variables_. Variables are found in every single programming language - they are a fundamental part of helping your computer know what the f*ck you want it to do.


      You can think of variables as a bucket of information to which you give a name. Romeo had it right when he said "What's in a name - a rose by any other name would smell as sweet." The name you give your variable, from the computer's perspective doesn't matter. From a human perspective, it matters a lot. But we'll get into that in a second. 


      There are lots of different things we can store in variables. In Python, we call these things _objects_. Object is a term you'll hear a lot in programming. You might also hear things like "everything in Python is an object." That's true, and the specifics of what that really means will be coming later in this course. 


      For right now, try to frame your thinking around the idea that the _stuff_ of Python are objects. This includes words and typed characters (these are called _strings_), integers and other numerical forms, groups of data called _lists_, _dictionaries_, _tuples_, and _sets_, and other objects that you can create and define yourself. Any of these things can be stored inside of a variable for referencing at any point in your code (with some limitations, ::wink::).


      ## Code Example<a name = "codeexample"></a>


      Here is a line of Python code that declares a variable and assigns a value to it:


      ```python

      my_name = 'Ashley'

      ```


      Let's break this down into it's different parts:


      > We have a variable name: `my_name`


      I came up with the name `my_name`. Variable names can, generally speaking, be whatever you like. Here are some guidelines:

      <div class = "note" markdown="1">

      ### Variable Name Guidelines

      - Variable names cannot start with numbers. For example, `1var` is not a valid variable name.

      - Variable names cannot be one of Python's reserved keywords. 

      - Variables names should be descriptive and short.

      - Variable names that have more than one word should be written in "snake cake". Snake case is when you replace all the spaces with underscores. For example, `this_is_snake_case`. This is common throughout all of Python.


      </div>

      > Then we have an equals sign: `=`


      The equals sign indicates assignment. We are assigning the value on the right hand side of the equals sign to the variable we declared on left side of the equals sign.


      > Then we have the value that's being assigned to the variable: `'Ashley'`.


      `'Ashley'` is wrapped in quotes because it is a string. If it was not wrapped in quotes, the Python interpreter would think I was referencing another variable, and it would get confused, and throw an error. Remember - programming is about being super explicit so the computer knows wtf we're talking about. This is one of those instances.


      ## TLDR


      - Variables are a way to store data and reference it later.

      - Variables can be named whatever you like but cannot start with a number. 

      - Variable names should be descriptive and short.

      - Variable names should be written in `snake_case`.

      - The syntax for creating a variable is:


      ```python

      variable_name = 'variable_value' # this could be a string, or any other Python object/value

      ```


      ## Activity


      Now you try! 


      1. Open up your terminal, and start the Python interpreter. <a href = "#solution1">See Solution</a>


      2. Create a variable called `favorite_color` and assign to it your favorite color. <a href = "#solution2">See Solution</a>




      ## Solutions


      ### Activity 1<a name = "solution1"></a>

      Open up your terminal, and start the Python interpreter. 


      ```terminal

      $ python3

      ```


      ### Activity 2<a name = "solution2"></a>

      Create a variable called `favorite_color` and assign to it your favorite color.


      ```terminal

      $ favorite_color = 'grapes'

      ```








  - lessonlayout: lesson
    title: Output
    content: >-
      ## Introducing Output


      So, I won't lie, I broke a cardinal rule of programming education by teaching you about variables as a first lesson.


      Tradition dictates that the very line of code you ever write should be printing out the words "Hello, world". That once action, in and of itself, is a small program, and its earliest origins seem to be from old coding tutorials from the 70s.


      So, my apologies for having robbed you of this transcendental experience. 


      To make up for my trangression, we'll cover writing your very own "Hello, world!" program in this lesson. But to do that, we need to cover _how_ to output things in Python.


      The most basic form of output is "printing". And that's not like printing a document on a physical piece of paper, it's printing from your code to some display. Most of the time, that display will be your terminal, or maybe a log, or a web browser. 



      ## Code Example<a name = "codeexample"></a>


      To print something in Python, you write the word `print` followed by a set of parentheses, `()`.


      Inside the parentheses, you include the contents of what you want printed. This could be a string literal like `'Ashley'`, or another literal like a number, for example, or it could be a variable. 


      As you learned in the previous lesson, variables are a way to store data. When you use a variable in your code, you're telling the Python interpretor to go grab the information stored in that variable's bucket.


      Let's look at this example:


      ```python

      # This code creates a variable called my_name that references the value 'Ashley'

      my_name = 'Ashley'


      # This code prints the value of my_name

      print(my_name)

      ```


      The following code is equivalent in outcome, but not in processing, to the code above:


      ```python

      print('Ashley')

      ```



      ## TLDR


      - Printing in Python is a way to output something from your code to a display, like your terminal or a web browser.

      - You can print literals or variables.

      - To print, use the following syntax:


      ```python

      print('Your Content Here')

      ```



      ## Activities


      Aright, back to the previously promised `Hello, world!` program. Are you ready for your true entry to the world of programming??


      1. Open up your terminal and start the Python interpreter. <a href = "#solution1">See Solution</a>


      2. After the interpreter is running, print out the string literal `'Hello, world!'`. Don't forget: hit the enter key after typing the code in order for it to execute. <a href = "#solution2">See Solution</a>



      ## Solutions


      ### Activity 1<a name = "solution1"></a>

      Open up your terminal, and start the Python interpreter. 


      ```terminal

      $ python3

      ```


      ### Activity 2<a name = "solution2"></a>

      After the interpreter is running, print out the string literal `'Hello, world!'`.


      ```python

      print('Hello, world!')

      ```
---
