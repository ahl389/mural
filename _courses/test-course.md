---
layout: post
title: Test course
tags: tag
track: track
description: a summary
hide: false
author:
  - Ashley
lessons:
  - lessonlayout: learn
    title: I am a lesson
    content: >+
      # Variables


      - [Lesson](#lesson)

      - [Code Example](#codeexample)

      - [TLDR](#tldr)

      - [Activity](#activity)

      - [Solutions](#solutions)


      ## Lesson

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


      - Variable names cannot start with numbers. For example, `1var` is not a valid variable name.

      - Variable names cannot be one of Python's reserved keywords. 

      - Variables names should be descriptive and short.

      - Variable names that have more than one word should be written in "snake cake". Snake case is when you replace all the spaces with underscores. For example, `this_is_snake_case`. This is common throughout all of Python.


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
---
