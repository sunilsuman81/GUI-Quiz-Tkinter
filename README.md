# GUI-Quiz-Tkinter
GUI Quiz Application using Tkinter and Open Trivia DB
Here's how to create a GUI quiz app in Python using Tkinter:
Set up the project:
Import the tkinter module.
Create a main window using tk.Tk().
Create questions:
Store quiz questions and answers in a data structure like a list of dictionaries. Each dictionary can contain the question, answer choices, and the correct answer. 
Design the GUI:
Use Tkinter widgets to create the user interface.
Display the question using a Label widget.
Create Radiobutton widgets for multiple-choice answers.
Add a "Next" button to proceed to the next question and a "Submit" button to finish the quiz.
Use StringVar to track the selected answer.
Implement quiz logic:
Create functions to handle quiz flow.
A function to display questions and answer choices.
A function to check the answer and update the score.
A function to move to the next question.
A function to calculate and display the final score.
Run the application:
Start the Tkinter event loop using window.mainloop().
