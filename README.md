# JavaScript Console Quiz --- README

## Project Overview

This project is a **JavaScript-based Console Quiz Application** that
quizzes the user with a series of general knowledge questions. It
demonstrates essential JavaScript concepts such as arrays, loops,
functions, objects, user input handling, and conditional logic.

The quiz runs in a browser environment using `prompt()`, `alert()`, and
`console.log()`.

------------------------------------------------------------------------

## Features

### ✔ Interactive Quiz

Users answer questions one by one using popup prompts.

### ✔ Score Tracking

Tracks correct answers and updates the user after each question.

### ✔ Proper Input Handling

-   Trims whitespace\
-   Converts input to lowercase for flexible matching\
-   Handles quiz cancellation gracefully

### ✔ Final Results

Displays total score and percentage at the end.

------------------------------------------------------------------------

## How It Works

1.  The quiz stores all questions and answers inside an array of
    objects.
2.  `runQuiz()` loops through each question and prompts the user.
3.  The input is normalized and compared with the correct answer.
4.  Score increases on correct responses.
5.  The user receives correctness feedback instantly.
6.  Final results are shown using an alert box.

------------------------------------------------------------------------

## File Included

    1.js   # Main JavaScript Quiz Program

------------------------------------------------------------------------

## Running the Quiz

1.  Create a new HTML file.
2.  Add this script tag:

``` html
<script src="1.js"></script>
```

3.  Open the HTML file in your browser.
4.  The quiz begins automatically.

------------------------------------------------------------------------

## Learning Outcomes

Students will practice: - JavaScript basics\
- Conditionals\
- Functions\
- Arrays and objects\
- User interaction through browser dialogs

------------------------------------------------------------------------

## Possible Enhancements

-   Convert it into a GUI-based quiz\
-   Add multiple-choice questions\
-   Add a timer\
-   Randomize questions\
-   Store high scores in LocalStorage
