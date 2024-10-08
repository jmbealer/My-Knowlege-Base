---
title: Python-best-practices
author: Justin Bealer
date_created: 2023-11-16, 04-00-39
date_modified: 2024-09-17, 11-01-03
reference: 
description: 
aliases: 
tags: 
---
# Python-best-practices
== Python Best Practices – The only guide to become Python Expert

Important Python Best Practices

So, here come some important Python best practices which you should always keep in mind.
1. Create a Code Repository and Implement Version Control

If you have ever been on GitHub, you must have noticed that a regular project’s structure looks like this:

docs/conf.py
docs/index.rst
module/__init__.py
module/core.py
tests/core.py
LICENSE
README.rst
requirements.txt
setup.py

Python coding practices

Python coding best practices

When you start a new python project, you can create a code repository and implement version control. GitHub is one provider of this, but you can use any other. Let’s talk about the structure of a project, but before that, I recommend you to check DataFlair’s latest python project on Speech Emotion Recognition.

Structure of the Python Project:
License

This is in the root directory and is where you should add a license for your project. Some licenses are:

GNU AGPLv3
GNU GPLv3
GNU LGPLv3
Mozilla Public License 2.0
Apache License 2.0
MIT License
The Unlicense
README

This is in the root directory too and is where you describe your project and what it does. You can write this in Markdown, reStructuredText, or plain text.
Module Code

This holds your actual code that may be inside a subdirectory or inside root.
requirements.txt

This is not mandatory, but if you use this, you put it in the root directory. Here, you mention the modules and dependencies of the project- the things it will not run without.
setup.py

This script in the root lets distutils build and distribute modules needed by the project.
Documentation

Readable documentation is essential. This is placed in the docs directory.
Tests

Most projects have tests- keep these in the tests directory.

2. Create Readable Documentation

So, next in python best practices is readable documentation. Like we just said, readable documentation is important. You may find it burdensome, but it creates clean code. For this, you can use Markdown, reStructuredText, Sphinx, or docstrings. Markdown and reStructuredText are markup languages with plain text formatting syntax to make it easier to mark up text and convert it to a format like HTML or PDF. reStructuredText lets you create in-line documentation. And Sphinx is a tool to easily create intelligent and beautiful documentation. It lets you generate Python documentation from existing reStructuredText. It also lets you export documentation in formats like HTML. Docstrings are documentation strings at the beginning of each module, class, or method.
3. Follow Style Guidelines

The PEP8 holds some great community-generated proposals. PEP stands for Python Enhancement Proposals- these are guidelines and standards for development. There are other PEPs like the PEP20, but PEP8 is the Python community bible for you if you want to properly style your code. This is to make sure all Python code looks and feels the same. One such guideline is to name classes with the CapWords convention.

    Use proper naming conventions for variables, functions, methods, and more.
    Variables, functions, methods, packages, modules: this_is_a_variable
    Classes and exceptions: CapWords
    Protected methods and internal functions: _single_leading_underscore
    Private methods: __double_leading_underscore
    Constants: CAPS_WITH_UNDERSCORES

Use 4 spaces for indentation. For more conventions, refer to PEP8.

For revising any python concept, refer to this free Python Tutorials Library.
4. Correct Broken Code Immediately

Like with the broken code theory, correct your broken code immediately. If you let it be while you work on something else, it can lead to worse problems later. This is what Microsoft does. It once had a terrible production cycle with MS Word’s first version. So now, it follows a ‘zero defects methodology’, and always corrects bugs and defects before proceeding.
5. Use the PyPI Instead of Doing it Yourself

One of the reasons behind Python’s popularity is the PyPI- this is the Python Package Index; it has more than 198,190 projects at the time of writing. This is a repository of software for Python and has thousands of Python projects. You should use code from this instead of writing it yourself- this saves time and lets you focus on the more important things. The PyPI has projects about everything, and you can install these using pip. You can also create and upload your own package here. Follow this best practice in Python, this will help you a lot.
6. The Zen of Python

Tim Peters wrote this short poem to express what values you should follow while coding in Python. You can get this by running “import this” in the IDLE:
>>> import this

The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren’t special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one– and preferably only one –obvious way to do it.
Although that way may not be obvious at first unless you’re Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it’s a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea — let’s do more of those!
7. Use the Right Data Structures

Know the benefits and limitations of different data structures, and choose the right one for your code.
8. Write Readable Code

You should use line breaks and indent your code. Use naming conventions for identifiers- this makes it easier to understand the code. Use comments, and whitespaces around operators and assignments. Keep the maximum line length 79 characters. You should stay consistent and write readable code.

Explore amazing python projects at DataFlair and start coding now.
9. Use Virtual Environments

You should create a virtual environment for each project you create. This will avoid any library clashes, since different projects may need different versions of a certain library.
10. Write Object-Oriented Code

Python is an object-oriented language, and everything in Python is an object. You should use the object-oriented paradigm if writing code for Python. This has the advantages of data hiding and modularity. It allows reusability, modularity, polymorphism, data encapsulation, and inheritance. Also, you should write modular and non-repetitive code. Use classes and functions in your code.
11. What Not to Do

Avoid importing everything from a package- this pollutes the global namespace and can cause clashes. Don’t implement best practices from other languages. Don’t turn off error reporting during development- turn it off after it. Don’t alter sys.path, use distutils for that.



== Python Coding Style: WIP

    Use 4 spaces per indentation and no tabs.
    Do not mix tabs and spaces. Tabs create confusion and it is recommended to use only spaces.
    Maximum line length : 79 characters which help users with a small display.
    Use blank lines to separate top-level function and class definitions and single blank line to separate methods definitions inside a class and larger blocks of code inside functions.
    When possible, put inline comments (should be complete sentences).
    Use spaces around expressions and statements.


