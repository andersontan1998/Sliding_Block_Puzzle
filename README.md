# *Sliding Block Puzzle*

The objective is to slide the blocks around so that the large square can slide through the hole at the bottom of the box, which is just wide enough for the large square.

Implemented by **Anderson Tan**

**Representation of the pieces:**

![alt text](https://github.com/andersontan1998/Sliding_Block_Puzzle/blob/master/pieces.PNG)

**The starting configuration of the pieces:** 

![alt text](https://github.com/andersontan1998/Sliding_Block_Puzzle/blob/master/starting.PNG)

The purpose of this project is to compute a solution (if one exists) from any given starting position of the pieces. 

**Testing:**

* [x] You can drag the blocks around with the mouse, and if they are close to a grid corner, they will "snap" into place. 

* [x] If you right click a rectangle, it will toggle the orientation (horizontal vs vertical).

* [x] Give the puzzle an initial state, compile the project, and run the solver.

* [x] Press q or escape to quit the program (or just close it via your window manager.)

**Simulation:**

![](solution_gif.gif)

**Notes:**

"Terminate called after throwing an instance of std::bad_alloc'"

Error message happens when the operating system runs out of memory and could not dedicate any more RAM to the program. This can happen if you are running on a virtual machine that is dedicated low amounts of RAM.
