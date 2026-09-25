# Sentiment + Emotion Story Generator

## Overview

The Sentiment + Emotion Story Generator<img width="1281" height="344" alt="Screenshot 2026-09-25 152635" src="https://github.com/user-attachments/assets/42ca6846-b454-409d-abcb-e4039cabc76d" />
 is a Natural Language Processing (NLP) application that analyzes user input to identify both sentiment and emotion, then generates a short story that reflects the detected emotional state.

This project combines transformer-based deep learning models with an interactive Gradio interface to provide an engaging text analysis experience.

---

## Features

* Sentiment Analysis using DistilBERT
* Emotion Detection using DistilRoBERTa
* Story Generation based on sentiment-emotion combinations
* Interactive Gradio Web Interface
* Real-time text processing

---

## Technologies Used

* Python
* Hugging Face Transformers
* DistilBERT
* DistilRoBERTa
* Gradio

---

## Project Workflow

1. User enters a sentence or text.
2. The sentiment analysis model predicts whether the text is Positive or Negative.
3. The emotion detection model identifies the dominant emotion.
4. The application matches the detected sentiment and emotion with predefined story templates.
5. A relevant story is displayed to the user.

---

## Installation

Install the required libraries:

```bash
pip install transformers gradio
```

---

## Running the Application

Run the Python file:

```bash
python app.py
```

After execution, Gradio will generate a local web link where the application can be accessed through a browser.

---

## Example

### Input

```text
I am very happy today because I achieved my goal.
```

### Output

```text
Sentiment: Positive

Emotion: Joy

Story:
The sun broke through the clouds just as he got the news. It felt like the universe was smiling with him.
```

---

## Learning Outcomes

* Applied transformer-based NLP models for text classification.
* Worked with sentiment analysis and emotion detection techniques.
* Built an interactive machine learning application using Gradio.
* Gained experience integrating multiple NLP models into a single workflow.


