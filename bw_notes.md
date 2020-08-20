### Python GUI pygame
### Can use whatever library I want. 
### Due date: Thursday August 27th
### UPER 
- Understand 
- Plan 
- Execute
- Reflect

# To Do: 
-	Research 'Conways Game of Life'
-	The notion of 'Turing Completeness'
-	?? Main entry point????? What does this mean?

# Readme notes
### Objectives
- Student should be able to create a unique, high-quality project that can be added to a professional portfolio

- Student should be able to describe the rules of Conway’s “Game of Life”

- Student should be able to explain what cellular automata are and describe how they are useful in real life

- Student should be able to correctly analyze the ‘Turing Completeness’ of Conway’s “Game of Life”

- Student should be able to implement a visualization of Conway’s “Game of Life” using technologies related to their specific track.

- Student should be able to utilize "double buffering" to implement the game

# Design Specs
- Grid of cells
	- Grid at least 25x25. Go as big as wanted. 

	- Cell 'Properties'
	1. State of cell: Alive or Dead
	2. current state
	3. Clickable/Tappable

		a. Clicked for users to set up intial cell configuration.
		
		b. Not clickable when simulation is running.  
	4. Begaviors: Toggle state functionality. 
		a. Manual toggle alive or dead before sim running. 
		b. Sim running and rules of life caused cell to change state. (alive or dead)
	5. Appropriate data structure
	6. Display the current generation in number format. 
	7. Use a timeout function to control the generations of cells and update the generation. 
	8. Start and stop buttons. 
	9. Button to clear the grid. 

# Write an algorithm that:
### Implements the following basic steps:
	1. For each cell in the current generation's grid:
		a. Examine state of all eight neighbors (it's up to you whether you want cells to wrap around the grid and consider cells on the other side or not)
		b. Apply rules of life to determine if this cell will change states
		c. When main loop completes:
			1. Swap current and next grids
			2. Repeat until simulation stopped
### Breaks down above steps into appropriate sub-tasks implemented with helper functions to improve readability

### Uses double buffering to update grid with next generation.

### Does something well-documented with the edge of the grid. (e.g. wrap around to the far side--most fun!--or assumes all edge cells are permanently dead.)