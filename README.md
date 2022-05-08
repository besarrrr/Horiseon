# Horiseon Project

The task is to take existing code used by Horiseon Marketing Agency and make it more accessible. Accessibility is important and has increasingly become an important consideration for businesses. This is because when a web page is accessible it ensures that all potential users, including people with disabilities, are provided with a good user experience and that everyone is able to easily access all necessary information.  Thus, the specific aim is to make the webpage more accessible for people with disabilities, ensure that people with socio-economic restrictions have equitable access, and optimize code for search engines by refactoring the HTML and CSS. Additionally, when working with the existing code I will also clean up and leave the code better than I found it and fix any errors that may exist. 

## Acceptance Criteria

GIVEN a webpage that meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## Deployed Site

https://besarrrr.github.io/Horiseon/Develop/index.html

##  Work Done

* Refactored the HTML doc to have semantic HTML elements instead of Div elements. This helps the organization of the code and makes it easier to read and understand. Additionally, added clearly labeled areas such as: : "< !-- hero/jumbotron -->"

* Included an Alt tag to all images to meet accessibility standards. For example instead of img src="./assets/images/search-engine-optimization.jpg" class="float-left". It looks like this: img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="computer and notebook with search engine words".  The reason for this is because if a blind person is on the webpage they would still know what is being shown in the pictures. 

* Ensured all links in the webpage led to the correct location. Originally when opening the web page the “Search Engine Optimization” link in the header did not work. When clicked an user would just stay in the same spot instead of being moved down to that section of the site. When looking at the HTML, I noticed that the article element that contained that search engine optimization content was missing an ID. I added the ID as: id="search-engine-optimization" so that the href reference  href="#search-engine-optimization" Search Engine Optimization- would then work. Without the ID the href was not sending users anywhere because it had nowhere to send them. 

* Ordered CSS code to match the flow of the corresponding HTML code. To do this I had the HTML and CSS code side by side and made sure they both flowed the same. Also added clearly labeled areas, similar to the HTML doc, such as: /* Section Content Styles */

## What, Why, How

### What:
The goal was to refactor the existing code and leave it better than when I got it.

### Why:
I was motivated to apply the  HTML and CSS concepts that I have learned thus far in a setting in which I could critically think to solve problems within the code, meet accessibility standards, and to leave the code better and easier to read than how I found it. 

### How:
To complete this task II relied on a few different sources of information. I used example code from a similar project called: Run-Buddy to compare and contrast, notes from my UT Austin Coding Bootcamp classes, and coding web pages online that hold a wealth of information about HTML and CSS. Combined this provided a framework from which I could work from and could find answers to any areas that may have caused some difficulties. 
