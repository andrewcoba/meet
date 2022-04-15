# meet

This is an app that will show events happening in a select number of cities. 

Feature 2: As a user, I should be able to show and hide an event’s details.
•	Scenario 1: An event element is collapsed by default
o	Given a user is on the home screen
o	When nothing is targeted
o	Then the event details will be collapsed
•	Scenario 2: User can expand an event to see its details
o	Given a user would like more details about an event
o	When the user clicks on an event
o	Then details about the event expand
•	Scenario 3: User can collapse an event to hide its details
o	Given a user has learned details of an event and wants to exit pop-up
o	When the user clicks minimize or out of modal
o	Then details of an event collapse

Feature 3: As a user, I should be able to specify the number of events that I want to browse through
•	Scenario 1: When user hasn’t specified a number, 32 is the default number
o	Given the user hasn’t specified number limit of events
o	When the user is on the homepage
o	Then the default number of events shown is 32
•	Scenario 2: User can change the number of events they want to see
o	Given the user want to see a certain number of events
o	When the user clicks a dropdown menu
o	Then they will be able to specify the number of events that appear on the page

Feature 4: As a user, I should be able to use the app, even when offline
•	Scenario 1: Show cached data when there’s no internet connection
o	Given the user is an area with no internet access
o	When the user opens the app and has previously stored data
o	Then that data will still be available to them
•	Scenario 2: Show error when user changes the settings (city, time range)
o	Given the user is without internet access
o	When the user tries to change the settings such as city and time range
o	Then an error message will display

Feature 5: As a user, I should be able to view charts with the number of upcoming events in each city
•	Scenario 1: Show a chart with the number of upcoming events in each city
o	Given the user wants to see a few events in each city
o	When they toggle the chart the displays events
o	Then they will be able to view them
