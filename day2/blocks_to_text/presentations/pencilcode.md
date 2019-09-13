footer: [UoN CS4S Introduction 2019 Workshop](http://cs4s.github.io/intro-2019)

# Drawing Art

# with Coding and Mathematics

## Coding & STEM 4 Schools

### An Introduction to Coding and Computational Thinking

#### Presented by Mr Daniel Hickmott

###### October 11th 2019

---

# Activity

- In this activity you will:
	- code in [Pencil Code](http://pencilcode.net/) (*A Hybrid Coding Environment*)
	- use Coding and Mathematics to draw art
	- apply concepts that you learned about in previous sessions, such as *Sequences* and *Loops*
	- learn about another **Computational Concept** called *Operators*

---

# Coding and Mathematics

- *(In Coding) "...the purpose of math is not to get a good score on a test. The purpose of the math is to get your program to work. It is a self-teaching lesson."* [David Bau](http://davidbau.com/archives/2013/12/16/teaching_math_through_pencil_code.html) (Creator of Pencil Code)
- Coding and the teaching of Mathematics have been intertwined since the first educational Coding languages (for example, LOGO)
- What are some ways that you could (or do) teach Coding alongside Mathematics?

---

![inline](images/logo_turtle.jpg)![inline](images/mindstorms_turtle.jpg)

---

![inline](images/logo_writer.png)![inline](images/boxer_drawing_pattern.gif)


---

![inline](images/pencilcode_example.png)

---

# Pencil Code

- A free, online *Hybrid Coding Environment*
- Uses a *General-Purpose Programming Language* called [CoffeeScript](https://coffeescript.org/), which can be used for web development
- You can also change the language to [JavaScript](https://developer.mozilla.org/bm/docs/Web/JavaScript), which is more commonly used by professional coders
- You can switch between *Blocks* and *Text* views
- 3 themed interactive tutorials: *Draw*, *Jam* and *Imagine*

---

# Drawing a Sky Full of Stars

![inline](images/starry_night.png)


---

# Drawing a Dot

![inline 100%](images/draw_dot_green_50.png)![inline 100%](images/draw_dot_green_100.png)
![inline 100%](images/draw_dot_orange_100.png)![inline 100%](images/draw_two_dots_100.png)

---

# Change the Background Colour

![inline](images/drawing_black_background.png)

---

# Pencil Code Colour Reference

![inline](images/pencilcode_colour_reference.png)

---

# Different Background Colours

![inline](images/drawing_custom_colours_background.png)

---

# Moving the Turtle

- We can also move the Turtle on the Canvas:
	- *fd:* it moves forward a number of steps
	- *bk:* it moves backwards a number of steps
	- *lt:* it turns by a number of degrees to the left
	- *rt:* it turns by number of degrees to the right
- We will start by moving the Turtle forward

---

# Drawing a Snow Kid in a Sequence

- Use the blocks below a starter and add *fd* and *dot* blocks to draw a Snow Kid

![inline 100%](images/snowkid_starter.png)

---

# Loops in Pencil Code

- Do you remember what *Loops* are?
- We use *Loops* to repeat steps multiple times
- For example, the *repeat* block in Scratch
- Pencil Code has a command called *for*, in the *Control* section, which is similar to repeat

![inline](images/for_block_in_pencil_code.png)

---

# Drawing a Line of Dots

![inline](images/draw_line_of_dots.png)

---

# Speeding the Turtle Up

![inline](images/draw_line_dots_speed.png)

---

# Operators

- All of the blocks in the *Operators* section
- Variety of different functions and purposes 
- E.g. addition, subtraction, multiplication & division
- We will focus on the *random* block in today's session

![inline 100%](images/random_operator.png)

---

# Random Sized Dots

![inline](images/drawing_different_size_dots.png)

---

# Random Coloured Dots

![inline](images/drawing_different_coloured_dots.png)

---

# Moving the Turtle Around

![inline](images/moving_turtle.png)

---

# Drawing Three Lines

![inline](images/three_lines_of_dots.png)

- Use the *moveto* command with the *for* loop to draw a picture similar to the one above
- Hint: by switching to the *Text* mode, you can copy and paste commands

---

# Drawing a Starry Night

![inline](images/starry_night_missing.png)

---

# Creating Dot Paintings

![inline](images/blue_painting_dots.png)

---

# Drawing a Circle of Dots

![inline](images/three_dots.png)

- What should we change to make it draw this pattern?

![inline](images/circular_pattern_of_dots.png)

---

# Forward and Backwards

![inline](images/fd_and_bk_pattern.png)

---

# Background and Colour Change

![inline](images/outmost_circle.png)

---

# Drawing the Other Circles

Pattern  |  Degrees in Each Turn  |  Times Repeated  |  Steps Forwards & Backwards
---------|------------------------|------------------|------------------------------
1        |  10                    |  36              |  175
2        |  12                    |  30              |  145
3        |  15                    |  24              |  115
4        |  20                    |  18              |  85
5        |  30                    |  12              |  55


---

# An Extra 2 Dots

- In the next steps we will draw patterns that overlap with each other, so we will also add a *big dot*
- Put the command at the top of your script (before all the *for* blocks): *dot 380, mediumturquoise*
- We also want a *dot in the middle* at the end
- After you have drawn all of the other patterns, add this command (to draw the last dot in the middle): *dot 30, white*

---

# Creating a Function

- A *Function* is a way of "encapsulating" common instructions
- We can take a set of instructions (such as drawing the dot patterns) and put them into one instruction
- If you have used *Custom Blocks* (through the *Make a block* button) in *Scratch*, you have created a *Function*
- *fd*, *speed* and other blocks are examples of in-built *Functions* in *Pencil Code*, but you can also create your own *Functions* as well

---

# Creating a Function to Draw the Pattern

- Say that we wanted to draw our pattern of circles on other spots on the Canvas more than once
- How could we do that?
- We could copy/paste the instructions a few times **but** there is a way that is neater

![inline 120%](images/draw_pattern_2_blocks.png)

---

# Functions in Pencil Code

![inline](images/function_labelled.png)

---

# Function Example

![inline](images/draw_pattern_example.png)

---

# Drawing the Pattern in Different Spots

- How can you combine the *draw_pattern* and *moveto* blocks to make a picture like below?

![inline](images/drawing_multiple_patterns_example.png)

---

# Extensions 

- If you finish all of the previous steps, you could:
	- change the colours of the different patterns
	- add more patterns on the Stage 
	- put all of the instructions that draw a pattern into one *Function* called *draw_circle* with inputs: *repeat*, *steps* and *degrees*
	- make it so that the colour of the dots are *random*
