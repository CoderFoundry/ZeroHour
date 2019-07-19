# ZeroHour
ZeroHour - A Coding Challenge
You are given an R by C matrix consisting of booleans that represents a board. Each True boolean represents a wall. Each False boolean represents a tile you can walk on. Given this matrix, a start coordinate, and an end coordinate, return the minimum number of steps required to reach the end coordinate from the start. If there is no possible path, then return null. You can move up, left, down, and right. You cannot move through walls. You cannot wrap around the edges of the board.
<h6>For example, given the following board:</h6>
                           
                                [[f, f, f, f],<br>
                                [t, t, f, t],<br>
                                [f, f, f, f],<br>
                                [f, f, f, f]]
                          
and start = (0, 0)(bottom left) and end = (3, 0)(top left), the minimum number of steps required to reach the end is 7, since we would need to go through (1, 2) because there is a wall everywhere else on the second row. 
                            
