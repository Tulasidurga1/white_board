# white_board
#Hosted Link:-https://github.com/Tulasidurga1/white_board



# Whiteboard with Delete and Undo Buttons
This is a simple HTML-based whiteboard application with delete and undo functionality. It allows users to draw on a canvas, delete the drawn objects, and undo the last drawn object. The canvas supports freehand drawing using a mouse.
# Demo
Freehand drawing on a canvas.
Delete button: Clear the canvas of all drawings.
Undo button: Remove the last drawn object.
# usage
Clone the repository or copy the HTML code to an HTML file.
Open the HTML file in a web browser.
Use the mouse to draw on the canvas.
Click the "Delete" button to clear the canvas.
Click the "Undo" button to remove the last drawn object.
# html
Canvas element (#whiteboard): The drawing area.
Delete button (#deleteButton): Clears the canvas.
Undo button (#undoButton): Removes the last drawn objec
# js
startDrawing(e): Initiates drawing when the mouse is clicked.
draw(e): Continues drawing as the mouse moves.
stopDrawing(): Finalizes the drawing process.
clearWhiteboard(): Clears all drawings from the canvas.
handleUndo(): Removes the last drawn object.
redrawCanvas(): Redraws all objects on the canvas.
# css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    background-color: white;
 
  }

#whiteboard {
    margin-top: 20px;
    border: 2px solid black;
    cursor: crosshair;
  }

#control{
    margin-top: 20px;
    display: flex;
    gap: 20px;
  }
