# Code-Refactoring

## Homework 1 
    Refactoring to make a codebase that follows accessibility standards

## Motivation
The task was to take existing code and refactor it to make more accessible. The client is a marketing agency who wanted their site to be optimized for search engines.

## Tech Used
Built with 
* [VS Code](https://code.visualstudio.com/)

## Features
When viewing the source code, you will find semantic HTML elements. Those elements follow a logical structure independent of styling and positioning. All images have alt attributes, the heading attributes fall in sequential order, and there is a **NEW** concise, descriptive title.

The css file was also altered to be less redundant and classes were deleted that were unnecessary. THe HTML code reflects these changes.


## Code Examples

1. To make more accessible, this website needed to include an *alt* attribute on each image. This specifies an alternate text for an image, if the image cannot be displayed. This is useful if the user uses a screen reader.

2. By having nav instead of div, a screen reader will tell them it's a navigation point. A div won't elaborate this.

3. Before starting this project, the initial website had a broken link, where the site optimization link in the header led to nowhere. 
Now, when Site Optimization is clicked by the user, it responds correctly.

4. The CSS and HTML were cleaned up by removing redundant classes and consolidating any of the same material into one. 
    The class below used to be separated into three **DIFFERENT** classes; Search Engine Optimization, Online Reputation management, and Social Media Marketing. Now all properties and values are under a single class:


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

    The same goes with combining images. Instead of listing out the css code for each individual image in the content section of your html file, this **new** code combines classes into *.content img*:
        
            .content img {
                max-height: 200px;
            }   


This should make the website and html flow nicely and by cleaning up the css, the file is now more organized as well as being more accessible.


*Towards the end of this project, I moved this repository from the class homework file into a new file. See previous commits before this change*
[here](https://github.com/linneagear/Code-Refactoring/commits/master)