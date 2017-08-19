---
layout: post
title:  "A fun solution to the Rubik's cube"
---

The Rubik's cube is a though logical puzzle that's been around since the early
1980s. As some you have probably seen, it is easy to find solutions to the
puzzle on the web these days.

Most of these methods are either for speed cubists who already master the cube,
or for beginners just to follow along so that their cube gets back in shape.

One thing I found a bit harder to find is a method that is aimed just to be fun and/or easy
 to remember and execute. Many methods have too many algorithms to remember
 just for the fun of impressing your friends once in a while. Some algorithmically simple methods
 also contain awkward moves like turning the back face or the bottom face
  counter-clockwise, which I found very confusing and kept messing up.

So here's my simple solution, which is mostly [Ruwix's beginners method](https://ruwix.com/the-rubiks-cube/how-to-solve-the-rubiks-cube-beginners-method/), with
the last step adapted for easy manipulation.

*It won't be fast, but should be good enough to impress your friends for minimal effort ;-)*

All steps involve the movement of only four faces of the cube (**U**p, **R**ight, **L**eft or **F**ront) clockwise, or counter-clockwise when followed by an apostrophe (e.g. F`)

I'm assuming you're solving beginning with the white face at the top.

**1.** First step is to do the white cross.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/Rubik%27s_Cube_Beginner%27s_Method_-_after_step_1.svg/180px-Rubik%27s_Cube_Beginner%27s_Method_-_after_step_1.svg.png">

<small>By Thomas 003 (Own work) [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons</small>

**2.** Then place the white corners correctly to finish the first layer of the cube.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cc/Rubik%27s_Cube_Beginner%27s_Method_-_after_step_2.svg/180px-Rubik%27s_Cube_Beginner%27s_Method_-_after_step_2.svg.png">

<small>
By Thomas 003 (Own work)  [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons</small>

These steps should be done intuitively and most sites don't offer a specific methodology to solve them.

 **3.** The next step is to turn the cube upside down (putting the completed white face on the bottom) and insert the edges of the middle layer using one of these two algorithms.

To insert the edge piece to the right :
**U R U' R' U' F' U F**

<img src = "https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Rubiks_25.svg/180px-Rubiks_25.svg.png">

<small>By RTCNCA, Karoma (Rubiks 1.svg) [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons</small>

To insert the edge piece to the left :
**U' L' U L U F U' F'**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Rubiks_26.svg/180px-Rubiks_26.svg.png">

<small>By RTCNCA, Karoma (Rubiks 1.svg) [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons
</small>

Here's what the cube should look like now : <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Rubiks_7.svg/180px-Rubiks_7.svg.png">

<small>
By RTCNCA, Karoma (Rubiks 1.svg)  [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons</small>


NB. This is the only place in the solution where you need to make a choice between different algorithms.

NB2. some authors pretend that this middle layer can also be completed intuitively, something I have tried without success for 20 years (!)

**4.** The next step is to orient the yellow edges from the top face of the cube so that, viewed from the top, they make a yellow cross

<img src = "https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Rubik%27s_Cube_Beginner%27s_Method_-_after_step_5.svg/180px-Rubik%27s_Cube_Beginner%27s_Method_-_after_step_5.svg.png">

<small>By Thomas 003 (Own work)  [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons</small>


Here's the algorithm we'll use :
**F R U R' U' F'**

And here's how it works :

<img src = "/images/posts/cross.png" width=300>

**a)** if the cross is already there, don't apply the algorithm

**b)** if you have a yellow line (3 pieces together), turn the cube so that the line goes from left to right and apply the algorithm once and you're done

**c)** if you have a yellow L, orient it as pictured above, apply the algorithm and then go back to step **b**

**d)** if you don't have any of these configurations, apply the algorithm once and start back from **a**

Only 3 more steps left

**5.** Now that the edges are oriented correctly, you need to place them. The following algorithm :

**R U R' U R U U R' U**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/33/Rubik%27s_Cube_Beginner%27s_Method_-_step_4_solution_1b_-_2D.svg/180px-Rubik%27s_Cube_Beginner%27s_Method_-_step_4_solution_1b_-_2D.svg.png">

<small>By Thomas 003 (Own work)  [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons</small>

switches the front and left edges together. Apply it as many times as needed to switch edges until all four are correctly positioned.

**6.** Contrary to steps **4** and **5**, the final placement of the corners begins by positioning them correctly, and then twisting them (instead of twisting first and placing second)

This algorithm :

**U R U' L' U R' U' L**

cycles 3 of the 4 corners (the one at up-right is preserved).

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Rubik%27s_Cube_LL_-_PLL_A-perm_2.svg/180px-Rubik%27s_Cube_LL_-_PLL_A-perm_2.svg.png" style = "-ms-transform: rotate(-90deg); /* IE 9 */
    -webkit-transform: rotate(-90deg); /* Chrome, Safari, Opera */
    transform: rotate(-90deg);">

<small>By Thomas 003 (Own work)  [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons</small>

Apply it as many time as needed to position all corners correctly. If you don't have any corners correctly positioned, apply the algorithm arbitrarily once and then turn the cube so that one good corner is at top right.

**7.** This is the final step. Be sure to read and understand all explanations before beginning this step, as stopping and restarting the sequence again can be difficult and you often need to start back to step one when it happens.

First, orient the cube so that a corner that needs to be twisted is a the up-right position. Apply the following algorithm as many times as needed (either 2 or 4 times) to twist the corner correctly.

**R F' R' F**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Rubiks_36.svg/180px-Rubiks_26.svg.png">

<small>By RTCNCA, Karoma, Beax (Rubiks 1.svg)  [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), via Wikimedia Commons</small>

Now, your cube will probably look quite a bit shuffled, don't panic and keep going.

Turn the top face of the cube (ONLY, NOT the entire cube) so that another corner to be twisted is at the top right and apply the algorithm 2 or 4 times until it is correctly twisted.

Repeat this process until all corners are correctly twisted and finally turn the upper layer to it's correct position.

**YOU'RE DONE**

Here's a quick recap of the the steps involved for easy reference

1. do the white cross
2. use either **U R U' R' U' F' U F** or **U' L' U L U F U' F'** to insert middle edges right or left
3. use **F R U R' U' F'** to organize the yellow cross at the top
4. switch front and left edges with **R U R' U R U U R' U** (repeat if necessary)
5. cycle all corners except top right with **U R U' L' U R' U' L**
6. Twist top right corner with **R F' R' F**, turning the top face only to get the next corner in position

If you're the kind of person who prefers to understand things on his own instead of applying pre-built solutions, please take a look at the [Petrus](http://lar5.com/cube/) or the [Heise method](http://www.ryanheise.com/cube/), which are more appropriate for this kind of approach.
