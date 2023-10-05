# Code Refactor 

## Project Description

This challenge involved refactoring a small static marketing website for Horiseon that had non semantic html tags and repeated code in CSS.
My task was to make the website more accessible by using semantic html tags and having DRY code in CSS.

## Getting Started

I split up the code into sections according to the content on the page. Below you will see each section as well as before and after commentary and images. 

## 1. 

---
    * HTML 
---
Before Changes --

Here is an example of how the code of the content looked in html.

<img src="assets/images/1 Before html section changes.png">

After Changes --

Here are the changes I made to the header content. As you can see, the first action was to replace all div tags were replaced with semtanic HTML tags - that being, one header tag and then subsequent nav tags. I also removed redundant list item tags. 

<img src="assets/images/1 After html changes.png"/>

---
    * CSS
---   
Before Changes --

Here is an example of how the code looked in CSS.

<img src="assets/images/1 Before CSS Changes.png">

After Changes -- 

CSS was also updated to respond to the removed header class. Additionally, div tags were replaced with nav under the header tag. Comments added.

<img src="assets/images/1 After CSS Changes.png">


## 2. 
---
    * HTML
---    

Before Changes -- 

Here is an example of how the code of the content looked in html.

<img src="assets/images/2 Before html changes .png">

After Changes -- 

Here are the changes I made to the main content. I removed the div tag and class hero with a figure tag. Then I replaced the class content with main. Then I replaced div tags with section tags. Alt tags were added for web accessiblity. I also renamed the img class to service to consolidate CSS. 

<img src="assets/images/2 After html changes.png"/>


---
    * CSS
---

Before Changes --

Here is an example of how the code looked in css.

<img src="assets/images/2 Before CSS Changes_1.png">
<img src="assets/images/2 Before CSS Changes_2.png">


After Changes -- 

Here is an image of my changes. Figure and main are no longer classes. By renaming the img class to service I was able to delete replication and consolidate the CSS code. I also moved the service section so CSS was read in order of HTML outline. Comments added. 

<img src="assets/images/2 After CSS changes.png">


## 3.

---
    * HTML
---
Before Changes --

Here is an example of how the code looked in html.

<img src="assets/images/3 Before Html Changes.png">

After Changes -- 

Here are the changes I made to HTML. Divs were replaced by aside and section tags. Classes named benefit-lead, benefit-brand, benefit-cost were deleted and categorized under a section class "benefit". Alt tags were added to images.

<img src="assets/images/3 After HTML Changes.png">

---
    * CSS 
---
Before Changes -- 

Here is an example of how the code looked in css

<img src= "assets/images/3 Before CSS Changes.png">


After Changes -- 
Here I made CSS changes to the aside portion of the webpage. Comments added. 

<img src= "assets/images/3 After HTML Changes.png">


## 4.
---
    * HTML
---

Before Changes --

Here is an example of how the code looked in html.

<img src="assets/images/4 Before HTML Changes.png">

After Changes -- 

Deleted class=footer and replaced div with footer tag.

<img src="assets/images/4 After HTML Changes.png">

---
    * CSS
___

Before Changes --

Here is an example of how the code looked in css

<img src="assets/images/4 Before CSS Changes.png">

After Changes --

Removed footer as a class in CSS to reflect html. Added comments. 

<img src="assets/images/4 After CSS Changes.png">
