🎯QuizApp
QuizApp is a simple and interactive React-based multiple-choice quiz application. Users can navigate through questions, select answers, and view their final score upon completion. The app is built with React state management to ensure a smooth and engaging experience.

✨Features
Interactive Quiz: Users can solve MCQS one question at a time.
Dynamic Question Navigation: Users can move through questions one at a time with a "Next" button.
Answer Selection: Clickable options with real-time visual feedback on the selected answer.
Scoring System: Tracks correct answers and calculates the score dynamically.
Final Score Display: A dedicated results screen showing the user's total score and the number of questions.
Progress Tracker: Displays the current question number and total questions.
Validation for Answer Submission: The "Next" button is disabled until an option is selected, preventing incomplete submissions.
Clean User Interface: Styled with CSS for a visually appealing layout.
Responsive Design: Compatible with various screen sizes for seamless usage across devices.


🚀How It Works
Start the Quiz:

The quiz begins with the first question displayed on the screen.
Option Selection:

Users must select an option to enable the "Next" button.
If no option is selected, the user cannot proceed to the next question.
Score Calculation:

The score is updated dynamically based on the correctness of the selected options.
Final Score:

Once the user completes all questions, the application displays the final score out of the total number of questions.


🛠️Technologies Used
ReactJS: Frontend framework for building the user interface.
State Management: Managed using React's useState and useEffect hooks.
CSS: For styling the application.
