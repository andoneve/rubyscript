# Writing a ruby program

## Goals
- write a ruby program
- escape special characters
- learn about "usage"
- Use loops
- Give your program arguments
- Use ruby documentation

## Tips
- Look at Ruby documentation: https://ruby-doc.org/core-2.2.0/String.html
- Inspired by this tutorial: https://learnrubythehardway.org/book/ex1.html

## Steps

1. Write a ruby program with exactly the following output (including separate lines and dots):

  I want a dyke for president
  
  ...
  
  I want a Black woman for president
  
  I want someone with bad teeth...
  
  Zoe Leonard
  
  1992

2. Put quotes around the poem:

"I want a dyke for president
...
I want a Black woman for president
I want someone with bad teeth..."
Zoe Leonard
1992

3. Write a comment above the script to tell me generally what the program does and how to use it. You can also add your authorship name and a cc license (https://creativecommons.org/) if you want to! (not necessary). Here is a simple example: http://pastebin.com/EGUmkHQ6. I DO NOT mean writing comments after each method. How can you write your code in a way that people can easily understand what your program does? Try naming variables and methods after the things they are/do.

4. Allow the user to add a line to the poem after the first line. How would we do this? Using arguments - there are a few different ways to do this, here is one way: http://stackoverflow.com/questions/4244611/pass-variables-to-ruby-script-via-command-line. Here is another way, using user input with gets: http://rubylearning.com/satishtalim/getting_input.html. Pick one, it doesn't matter!

5. Make it so that a user can write as many arguments as they want with each argument displaying as a line in the poem. hint: loop over the arguments.

6. Allow the user to input their name as author to the piece, e.g. "Zoe Leonard & [insert user's name here].

7. Tell the user how many lines they added, e.g., "Your new version of the poem added 3 lines"

8. How can we improve our program? Could we name our variables smarter so people know what we are talking about? Could we "extract variables"[http://www.refactoring.com/catalog/extractVariable.html] where we write in explicit things?
