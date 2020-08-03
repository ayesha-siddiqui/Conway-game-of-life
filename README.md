# Conway-game-of-life
## PROJECT MEMBERS
- #### 63652 | Ayesha Siddiqui
# APPROACH
We have use these following approches in this project :
- Malloc
- Threads
- Processes
- Text file
- Libraries(time,pthread,ctype,string,stdlib,stdio)
# PROBLEM FACES:
### Problem 1:
First problem was undefine reference we were not calling barrier class variables properly in conway file.

### Problem 2:
Second problem we faced in our project was segmentation fault.

# DESCRIPTION:
This program runs Conway's Game Of Life utilizing pthreads to split the task of processing. The game board is divided up between threads by rows, and when there are more threads than rows, individual rows are divided up between threads as well.Explanation of all files is mentioned below:

# CONWAY FILE:
First technique read_split is perusing contribution from document input.txt.Char contention went here is pointing input document it will spare its address.Exit disappointment work is use to show disappointment if client enter wrong document rather than input.txt it will come out of program.Split and barrier are two header records which are included this principle document conway.We have proclaim rows,coloums,size factors for taking contribution here size variable will take size of board(splitter varable is taken for board) or screen.In this strategy malloc is use for memory assignment to store size of integer.Malloc is fundamentally use to make a dynamic 2D array,then in do while circle it will print the character were star is for 1 and speck is for 0.Here cursor is accomplishing same work as i++ do in for circle highlighting the next,then to ensure we intialize our board appropriately we have utilize this condition until cursor is equivalent to measure of board this do while won't stop.Print_splitter technique is printing the board,if board position is equivalent to zero it will print zero or one.Game_generation technique is making generations,it will check its neighbors first it will check past column for neighbors where it has utilize three conditions that on the off chance that line isn't equivalent to zero, at that point it will include nieghbours all these three conditions will run infinitely.Then it will check current line for neighbors this work is accomplished for making neighbours.Last two conditions will check the fundamental rules that on the off chance that it has more, at that point three or less then 2 neighbors it will kick the bucket of lonlinesses or pack and duplicate zero however on the off chance that it has three neighbors it will duplicate 1.Thread_race strategy is for running the string it will store contentions of lines and coloumn in actual,this barrier_wait work is called from hindrance class.In synchrinize_splitter it will duplicate information board size in memory for which we have use memcopy variable.In principle its taking cmmand line contention first contention is text file,argc and argv these factors are go to primary capacity when it begins executing.
# REFERENCES:
https://www.geeksforgeeks.org/program-for-conways-game-of-life/
https://www.mathworks.com/matlabcentral/fileexchange/26805-conway-s-game-of-life
https://rosettacode.org/wiki/Conway%27s_Game_of_Life
