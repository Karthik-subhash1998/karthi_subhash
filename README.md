# Google Python Exercises

Welcome to the Google Python Exercises repository! This collection of Python exercises is designed to help you improve your Python skills. These exercises are inspired by the Python class developed by Google for their own engineers.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Exercises](#exercises)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository contains a series of Python coding exercises that will help you practice different aspects of Python programming, including:

- Basic syntax
- Data structures
- String manipulation
- File I/O
- Regular expressions
- Functions and modules
- Object-oriented programming

## Prerequisites

Before you start working on these exercises, you should have:

- Basic knowledge of Python programming
- Python installed on your system (version 3.x recommended)

If you are new to Python, you can start by reading the [Python Tutorial](https://docs.python.org/3/tutorial/).

## Setup

To get started with these exercises, follow these steps:

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/google-python-exercises.git
    cd google-python-exercises
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install any necessary dependencies:
    ```bash
    pip install -r requirements.txt  # If there is a requirements file
    ```

## Exercises

The exercises are divided into different folders, each focusing on a specific topic. Each folder contains:

- A `README.md` file explaining the exercise
- Starter code
- Tests to verify your solution

### List of Exercises

1. **Basic Exercises**
   - `hello.py`: Print "Hello, World!" to the console.
   - `string1.py`: Functions for string manipulation.
   - `list1.py`: Functions for list operations.

2. **Word Count**
   - `wordcount.py`: Read a file and count the occurrences of each word.

3. **Baby Names**
   - `babynames.py`: Parse baby names from a given HTML file.

4. **Log Puzzle**
   - `logpuzzle.py`: Extract and sort puzzle URLs from a web server log file.

### Running Tests

To run tests for an exercise, navigate to the exercise folder and execute the test script. For example:

```bash
cd basic
python string1_test.py
