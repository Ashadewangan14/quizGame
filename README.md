# Simple Quiz Game with HTML, CSS, and JavaScript

This is a basic quiz game built using HTML, CSS, and JavaScript. It allows users to test their knowledge on a variety of topics with different difficulty levels.

## Features

- **Multiple Topics:** Choose from General Knowledge, Science and Technology, and Culture.
- **Three Difficulty Levels:** Easy, Medium, and Hard questions for each topic.
- **Interactive Interface:**  User-friendly interface to navigate through questions, select answers, and view results.
- **Score Tracking:** The game keeps track of the player's score, displaying it at the end.
- **Try Again Option:**  Allows the player to retake the quiz after viewing their results.

## Technologies Used

- **HTML:** Used to structure the basic layout and content of the quiz game.
- **CSS:** Used to style the appearance of the quiz game, making it visually appealing.
- **JavaScript:** Provides the logic and interactivity of the game, including:
    - Displaying questions and answer options.
    - Checking answers and providing feedback.
    - Keeping track of the score.
    - Navigating between different pages of the quiz (Welcome, Topics, Quiz, Results).

## Functionality

1. **Welcome Page:**
   - Displays the title of the quiz and a start button.
   - Clicking "Start Quiz" takes the user to the topic selection page.

2. **Topics and Levels Page:**
   - Allows users to select a topic (General Knowledge, Science and Technology, Culture).
   - Provides options for difficulty levels (Easy, Medium, Hard).
   - The "Start Quiz" button initiates the quiz based on the selected topic and difficulty.

3. **Quiz Page:**
   - Displays the current question along with four multiple-choice answer options.
   - Users can click on the buttons to choose an answer.
   - The selected answer is validated, and appropriate feedback (correct/incorrect) is provided.
   - The score is updated based on correct answers.
   - Navigation buttons:
      - **Back:** Returns to the Topics and Levels page.
      - **Next:** Proceeds to the next question (becomes active after answering a question).

4. **Results Page:**
   - Displays the final score and a summary of the user's performance.
   - Shows the percentage of correctly answered questions.
   - Provides buttons for:
      - **Try Again:** Restarts the quiz with the same topic and difficulty.
      - **Go to Home:** Returns to the welcome page.

## How to Run the Quiz

1. Download or clone the repository to your local machine.
2. Open the `index.html` file in your web browser. 

## Future Enhancements

- **Timer:** Add a timer for each question to make the quiz more challenging.
- **More Questions:**  Expand the question bank for each topic and difficulty level.
- **Local Storage:** Store high scores locally so users can track their progress.
- **More Dynamic UI:** Use more advanced CSS or a JavaScript framework (like React, Vue, or Angular) to create a more visually appealing and dynamic user interface. 
