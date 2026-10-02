# Day05-Assignment-1

## Qwen 0.5B Local Chatbot

This project is a simple local chatbot built with Python using the Qwen 0.5B language model, Hugging Face Transformers, and PyTorch.

The chatbot runs locally on Windows and accepts questions from the user through the terminal.

## Features

* Runs the Qwen model locally
* Uses Python
* Uses Hugging Face Transformers
* Uses PyTorch
* Supports interactive conversations
* Type `exit` or `quit` to close the chatbot

## Project Structure

```text
Day05-Assignment/
│
├── main.py
├── README.md
├── .gitignore
│
└── models/
    └── qwen-0.5b/
```

## Requirements

* Python 3.x
* PyTorch
* Transformers
* Qwen 0.5B model

## Installation

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment on Windows:

```bash
venv\Scripts\activate
```

Install the required packages:

```bash
pip install torch transformers
```

## Run the Program

Run:

```bash
python main.py
```

Example:

```text
Loading tokenizer...
Loading model...
Model loaded successfully!
Type 'exit' or 'quit' to stop.

You: Hello

Assistant: Hello! How can I help you?
```

## Exit the Program

Type:

```text
exit
```

or:

```text
quit
```

## Model Location

The Qwen model should be placed inside:

# Day05-Assignment-2

## Prompt

Sort these numbers in ascending order and return only the sorted numbers:

47, 3, 91, 12, 6, 58, 24, 1, 73, 15

## Verification

I independently sorted the numbers and compared my result with Qwen's output. All 10 numbers were present exactly once and were in the correct ascending order.

I ran the same prompt twice. Both runs produced the same correct answer.

## Model and performance

Model: Qwen 2.5 3B

Model size: [copy the size shown by ollama list]

Approximate response time: [your observed time]

The 3B model was small enough to run locally on my Windows machine. The trade-off is that a smaller model uses fewer resources but may be less reliable on more difficult tasks.

```text
models/qwen-0.5b
```

The model files are excluded from the GitHub repository using `.gitignore`.
