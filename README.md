# Quiz App

A quiz application that allows users to test their knowledge on various topics. The application presents multiple-choice questions and provides a report of the user's performance at the end. The quiz progress is stored using `localStorage` to prevent data loss on page refresh.

## Features

1. Displays a list of topics based on the dataset provided.
2. Allows users to select a topic to start the quiz.
3. Presents multiple-choice questions with up to 4 choices.
4. Allows navigation between questions using the "Next" and "Back" buttons.
5. Prevents modification of answers once a question has been attempted.
6. Displays a report at the end with the score, number of correct answers, and incorrect answers.
7. Tracks completed quizzes and restricts re-attempts for the same topic.
8. Utilizes `localStorage` to store quiz progress and prevent data loss on page refresh.

## Customization

To customize the topics and questions, you can modify the provided dataset. Update the data in the JSON file (dataset.json) to reflect the desired topics and their associated questions.
