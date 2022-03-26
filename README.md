# Work Day Scheduler Starter Code
# Challenge-005 : Third-Party APIs Challenge: Work Day Scheduler
## By Sultan Siddiqi
## Email: sultan.siddiqi@gmail.com
## GitLab Profile: sultansiddiqi

## Link to Challenge 
https://sultansiddiqi.github.io/Challenge-005-Third-Party-APIs-Challenge-Work-Day-Scheduler/

## Project Description
Your Task
Create a simple calendar application that allows a user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

The starter code uses the Moment.js (Links to an external site.) library to work with date and time, but feel free to use a different JavaScript solution to handle this functionality since Moment.js is considered a "legacy" project. Learn more about some alternative solutions in the Moment.js project status page.

```
User Story
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively

Acceptance Criteria
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with time blocks for standard business hours
WHEN I view the time blocks for that day
THEN each time block is color-coded to indicate whether it is in the past, present, or future
WHEN I click into a time block
THEN I can enter an event
WHEN I click the save button for that time block
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

## Overview  
* Added 12 slots related to the 12 hours desired. 7am-7pm
* Added a date function that refreshed to have a live clock on the top of the page
* Created a text input slot to enter the desired task
* Added a save button per slot to allow the user to save that task in that hour
* Added a window alert to let them know the button was clicked and the item was saved
* Added a console log as well to allow the user to see if the buttons are responding
* Colour coded (as required) to show current hour time-slot, greyed out passed hours, and green is upcoming hours



## Code was to resemble the following Image

![alt text](https://courses.bootcampspot.com/courses/1181/files/1447835/preview)

### Acceptance Criteria
The following information is the grading/acceptance criteria for this assignment.

```
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
```
​
## Grading Criteria From Course Page
# https://courses.bootcampspot.com/courses/1181/assignments/23346?module_item_id=458708
​
### Technical: 40%
- Application's links all function correctly.
- Application's CSS selectors and properties are consolidated and organized to follow semantic structure.
- Application's CSS file is properly commented.
​
### Deployment: 32%
- Application deployed at live URL.
- Application loads with no errors.
- Application GitHub URL submitted.
- GitHub repository that contains application code.
​
### Application Quality: 15%
- Application resembles (at least 90%) screenshots provided in challenge instructions.
​
### Repository Quality: 13%
- Repository has a unique name.
- Repository follows best practices for file structure and naming conventions.
- Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
- Repository contains multiple descriptive commit messages.
- Repository contains quality README file with description, screenshot, and link to deployed application.

## Contribution
Code provided by "Horiseon" <br />
Code Refactored by Sultan Siddiqi