# Sudoku Solver Game in Python

This is my personal version of Sudoku solving game using python, it also come with Backtracking algorithm.

![20220105000935](https://user-images.githubusercontent.com/47311671/148163684-78994e14-b45b-4f85-b1f2-61c80fa841ef.png)


Sodoku is logic-based, combinatorial number-placement puzzle game. The objective of Sudoku is to fill a 9 × 9 grid with digits so that each column, each row, and each of the nine 3 × 3 subgrids that compose the grid (also called "boxes", "blocks", or "regions") contain all of the digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution.

![20220105001542](https://user-images.githubusercontent.com/47311671/148164163-e721ba2b-0718-4319-9ae4-274138caef35.png) A typical Sudoku puzzle

![20220105001553](https://user-images.githubusercontent.com/47311671/148164205-19d11b6c-7b78-4252-9a99-3dcd398e0c01.png) The solution to the puzzle above


I'm building this Sudoku solving game with Blacktracking alorithm. Backtracking is simply reverting back to the previous step or solution as soon as I determine that my current solution cannot be continued into a complete one. I will use this principle of backtracking to implement the following algorithm:<br>
<ul>
  <li>Find some empty spaces. </li>
  <li>Attempt to place the digits 1-9 in that space.</li>
  <li>Check if that digit is valid in the current spot based on the current board.</li>
  <li>A. If the digit is valid, recursively attempt to fill the board using steps 1-3.
      B. If it is not valid, reset the square you just filled and go back to the previous step.</li>
  <li>Once the board is full by the definition of this algorithm we have found a solution.</li>
</ul>

<b>Dependencies</b>
<ul>
  <li>Python 3.x</li>
  <li>Pygame > 1.4</li>
</ul>
To <b>play</b>, run GUI.py and use numberpad to type the number then press Enter.
<br>
Developed in collaboration with <a href="https://github.com/maxwell1997lzx">maxwell1997lzx</a>
