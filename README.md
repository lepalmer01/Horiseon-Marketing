# Code Refactor 

## Description

This challenge involved refactoring a small static marketing website fir Horiseon that had non semantic html tags and repeated code in CSS.
My task was to make the website more accessible by using semantic html tags and having DRY code in CSS.

## Getting Started

## 1

Here is an example of how the code of the content looked in html.

Here are the changes I made to the header content. As you can see, the first action was to replace all div tags were replaced with semtanic HTML tags - that being, one header tag and then subsequent nav tags. I also removed redundant list item tags. 

CSS was also updated to respond to the removed header class.  

<img src="/Users/lepalmer/bootcamp/Homework/Horiseon-Marketing/assets/images/Semantic HTML changes:CSS.png"/>

## 2 

HTML --
Here are the changes I made to the main content. I removed the div tag and class hero with a figure tag. Then I replaced the class content with main. Then I replaced div tags with section tags. Alt tags were added for web accessiblity. I also renamed the img class to service to consolidate CSS. 

Changes:
<img src="/Users/lepalmer/bootcamp/Homework/Horiseon-Marketing/assets/images/After html changes.png"/>

CSS --
Figure and main are no longer classes. By renaming the img class to service I was able to delete replication and consolidate the code. 

Changes:
<img src="/Users/lepalmer/bootcamp/Homework/Horiseon-Marketing/assets/images/#2 After CSS changes.png">

