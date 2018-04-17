# Assignment Retrospective: CheckerBoard
This is the reflect on the first challenge we did at the begin of this semester. It compares my previous work to the provided solution.

## Reflect on the work you did for the challenge.
In this challenge, I created a CheckerBoard class accroding to the requirements. 
- Declear board as the container of AnchorPane and selection bar.
- Allow users change grid size, color scheme and rectangle size by clicking menu items or dragging window.
- Rectangles are generated as children of AnchorPane. 
- Use index of array element to decide color of each rectangle.
- Remove the old AnchorPane and generate a new one when the settings are updated. 
 
## How well did you understand the programming concepts and foundational knowledge needed to complete the challenge?
To complete this challenge, I need to understand how to build a class to generate a JavaFX UI and use this controller to generate the checkerboard with varied settings. Although in this challenge, the UI is not complicated, but it allows me get familier with JavaFX UI hierarchies.

## How well did you meet the requirements as set out in the challenge? What requirements did you not meet correctly (if any)?
Overall I think I meet all the requirements. 

## How well does your solution match the posted solution? What is different?
Comparing the CheckerBoard class in the posted solution with mine, there are almost the same, despite some details about newing a rectangle.
In the controller class, the main differences comes to the handler functions of grid size and coloe scheme. In the posted solution, switch-case are used to decide the parameters to update AnchorPane. In my code, I use seperate functions for each items in menu.
The readability and changeability of my solution is not as good as posted solution.

## How could you improve going forward? What don't you still understand that was required for the challenge?
Optimize the JavaFX UI controller to make it more readable and easier to modify, by changing the approach to update settings of checkerboard. Also, when setting the event listener, extracting the code block to form a new function and invoke this function in the lambda expression would improve readability.

