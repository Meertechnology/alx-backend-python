# Python - Async Comprehension

## Description
This project focuses on Python asynchronous programming using asynchronous comprehensions and generators. By the end of this project, you will be able to write an asynchronous generator, use async comprehensions, and type-annotate generators.

## Learning Objectives
By completing this project, you will be able to:
- Write an asynchronous generator.
- Use async comprehensions.
- Type-annotate generators.

## Resources
- [PEP 530 – Asynchronous Comprehensions](https://www.python.org/dev/peps/pep-0530/)
- [What’s New in Python: Asynchronous Comprehensions / Generators](https://docs.python.org/3/whatsnew/3.6.html#whatsnew36-pep530)
- [Type-hints for generators](https://docs.python.org/3/library/typing.html#typing.Generator)

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted/compiled on Ubuntu 18.04 LTS using `python3` (version 3.7)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/env python3`
- Your code should use the `pycodestyle` style (version 2.5.x)
- All your modules should have documentation
- All your functions and coroutines must be type-annotated

## Project Structure


## Tasks

### 0. Async Generator
Write a coroutine called `async_generator` that loops 10 times, each time asynchronously waiting 1 second, then yielding a random number between 0 and 10.

#### Example:
```bash
./0-main.py
[4.40, 6.90, 6.29, 4.54, 4.13, 9.99, 6.72, 9.84, 1.00, 1.37]

./1-main.py
[9.86, 8.57, 1.74, 4.07, 0.55, 8.08, 8.38, 1.54, 7.71, 7.67]

./2-main.py
10.021936893463135

python3 0-main.py
python3 1-main.py
python3 2-main.py


This `README.md` file explains the project, provides clear instructions for each task, and includes examples for expected output.
