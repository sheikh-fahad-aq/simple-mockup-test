# TUNE Coding Challenge

## The Task

TUNE is planning to develop a new Users Dashboard. You are tasked with prototyping the dashboard based on the attached mockup and the mock data:

* `Code-Challenge-Mockup.png`
* `users.json`
* `logs.json`

You may use any programming languages you wish. You may also use any frameworks or libraries that are appropriate, and we encourage you to do so.

## User Interface
The provided mockup is just a guide. Feel free to improve the design within the requirements:

* Each card should have the user's avatar, name, and occupation. For users with no image avatar, display the first letter of their first name in place of an image.

* Each card should display the sum of all impressions, conversions, and revenue.

* Each card should display a simple chart of of conversions per day.

## Data

Two sets of mock data are attached that represent 30 days of impressions, conversions, and revenue, as well as the user accounts associated with the activity.

`users.json`: An array of user objects. Each user may have an id, name, avatar, and occupation.

`logs.json`: Event information about the traffic. Each item has a type (either 'impression' or 'conversion'), date and time of the event, user ID of the account the event is related to, and any revenue associated.

## Application Design

The team plans to have a database as the source of information for users and logs in the future, though it is not currently implemented, so please take that into account in the design of your solution.

The team plans to build additional views of users and event stats in the future, so please consider how the API for retrieving the data could be used for other views in the future.

## Bonus Items

* Implement the ability for the user to sort the cards by name and by total impressions, conversions, or revenue
* Write unit tests for testable portions of your code
