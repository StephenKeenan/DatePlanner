# 05 Third-Party APIs: Work Day Scheduler

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Description
Allows users to save events for each hour of the day, and indicates both the current hour and future time blocks. The app runs in the browser and uses dynamically updated HTML and CSS powered by jQuery, as well as the Moment.js library to work with date and time. 

## Live Page

[Work Day Scheduler](https://stephenkeenan.github.io/DatePlanner/)

## Visual Representation
![Work Day Scheduler](https://github.com/StephenKeenan/DatePlanner/blob/master/assets/Work%20Day%20Scheduler.JPG)

## Acceptance Criteria

```
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

- - -
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
