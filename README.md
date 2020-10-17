# Homework01 - Code Refactor

## Objectives
The objective of this homework is to practice on the most common task of entry level web developer which is "**Code Refactor**".

> Always leave the campground cleaner than you found it 
> - Robert Baden-Powell

The same philosophy of the scout rules has been applied to coding practice. 
Meaning that every time that we make a change in our code base, make an improvement in the code without changing what it does.
This is the goal that we try to achieve on this assignment.

## Application 

### Application URL
https://thammaraku.github.io/homework_01_html_css_code_refactor/

## Github Repository URL
https://github.com/thammaraku/homework_01_html_css_code_refactor.git

### Screenshot
![Horiseon web page](./assets/images/01-html-css-git-homework-demo.png)


## Problems Found and Solutions

1.  **Problem:**  Majority of code is not in acessibility standard.
    **Solution:** Put the code under HTML semantic elements by replacing div tag by semantic tags (header, footer, nav, main, section, aside). Rearranged HTML and CSS file to be indenpendent of positioning and styleing.

2.  **Problem:**  CSS structure is not well organized. Many classes/IDs share the same properties which could be consolidated.
    **Solution:** Consolidated classes/IDs which share the same properties by using the right CSS selectors.

3.  **Problem:**  One of Navigation Pane links is not working.
    **Solution:** Corrected classed/IDs assignment on that partucular link.

4.  **Problem:**  Images are missing accessible alt attributes.
    **Solution:** Added alt attribute on all the image tags, including the hero image.

5.  **Problem:**  Web page title is not informative.
    **Solution:** Added more information about the company under title tag.

6.  **Problem:**  Comments are missing on both HTML and CSS files.
    **Solution:** Added comments on both HTML and CSS file by grouping into each element.


## Things learned from this homework
1. How to use Semantic HTML elements and how to organize to follow semantic structure
2. How to use CSS selectors and properties
3. How to write markdown README file


## License
No license required on this public web page.
