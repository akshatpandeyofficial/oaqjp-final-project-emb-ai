# Emotion Detector

## Project Overview

Emotion Detector is a Python application that analyzes text and
identifies the emotions expressed in it using the IBM Watson Natural
Language Processing (NLP) library/API. The project exposes the
emotion-detection functionality through a Flask web application.

## Features

-   Detects emotions from text input using Watson NLP.
-   Formats the detection result into a clear, structured response.
-   Provides a Flask-based web interface.
-   Handles blank input and error responses.
-   Includes unit tests for the emotion-detection function.
-   Supports static code analysis.

## Technologies Used

-   Python
-   IBM Watson NLP / Watson NLP emotion detection service
-   Flask
-   unittest
-   Static analysis tools (as configured in the project)

## Project Structure

The project should include the files required by the course assignment,
such as:

``` text
emotion-detector/
├── emotion_detection.py
├── server.py
├── test_emotion_detection.py
├── emotion_detector/
│   └── __init__.py
├── templates/
│   └── index.html
├── static/
│   └── ...
└── README.md
```

> Adjust this structure to match the actual files in your repository. Do
> not add files that are not part of your implementation.

## Setup

1.  Clone the repository:

    ``` bash
    git clone https://github.com/YOUR-USERNAME/emotion-detector.git
    cd emotion-detector
    ```

2.  Create and activate a virtual environment (recommended).

3.  Install the dependencies listed in your project's requirements file.
    If the project does not yet have one, add the dependencies actually
    used by your code.

4.  Configure any Watson NLP service credentials or endpoint settings
    required by your implementation. Do not commit API keys, passwords,
    or other secrets to GitHub.

## Run the Application

Start the Flask server using the command appropriate for your project,
for example:

``` bash
python server.py
```

Then open the local address printed by Flask in your browser.

## Run Tests

Run the unit tests with:

``` bash
python -m unittest test_emotion_detection.py
```

Use the exact test command specified by your course instructions if it
differs.

## Assignment Tasks

-   [ ] Task 1: Clone and document the project repository.
-   [ ] Task 2: Implement emotion detection using the Watson NLP
    library/service.
-   [ ] Task 3: Format the emotion-detection output.
-   [ ] Task 4: Package the application as a valid Python package.
-   [ ] Task 5: Run unit tests.
-   [ ] Task 6: Deploy the application using Flask.
-   [ ] Task 7: Handle errors, including blank input and appropriate
    status codes.
-   [ ] Task 8: Run static code analysis and address reported issues.

## Repository

GitHub URL: `https://github.com/YOUR-USERNAME/emotion-detector`

Replace `YOUR-USERNAME` with your GitHub username and update this README
to reflect the implementation and deployment you actually completed.
