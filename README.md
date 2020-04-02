# Code-Refactoring

## Homework 1 
    Refactoring to make a codebase that follows accessibility standards

## Motivation
The task was to take existing code and refactor it to make more accessible. The client is a marketing agency who wanted their site to be optimized for search engines.

must contain at minimum a description of what the project is,
screenshots of essential code

## Tech Used
Built with 
* [VS Code](https://code.visualstudio.com/)

## Features
When viewing the source code, you will find semantic HTML elements. Those elements follow a logical structure independent of styling and positioning. All images have alt attributes, the heading attributes fall in sequential order, and there is a **NEW** concise, descriptive title.

The css file was altered to be less redundant and classes were deleted that were unnecessary. THe HTML code reflects these changes.

## Code Examples
Describe and show how to run the tests with code examples.

1. Before starting this project, the initial website had a broken link, where the site optimization link in the header led to nowhere. 

Now, when Site Optimization is clicked by the user, it responds correctly:
    **HAVE GIF HERE of working application**

            gif walkthroughs of the application functioning.

![Alt text](/relative/path/to/img.jpg?raw=true "Optional Title")
Add screenshots inside the repo

It needed a separate class that could link down to the appropriate section of the page.

2. The CSS and HTML were cleaned up by removing redundant classes and consolidating any of the same material into one class. The benefits class used to be separated into three **DIFFERENT** classes.


        .benefits {
            margin-right: 20px;
            margin-bottom: 32px;
            padding: 20px;
            clear: both;
            float: right;
            width: 20%;
            height: 100%;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            background-color: #2a607c;
            color: #ffffff;

The same with combining images. Instead of listing out the css for each individual image in the content section of your html file, you can combine classes into *.content img* or *.benefits img*



This should make the website and html flow more nicely and by cleaning up the css, the file is now more organized as well as being more accessible.