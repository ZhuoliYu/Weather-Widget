# Weather-Widget
SD105-Assignment-1
Set-up & Instructions
Build and deploy a weather widget that uses the navigator geolocation API to determine the users location and uses that location to obtain the current weather and a 5 day forecast for their region.

Submissions & Deadline
Submit only the URL of your PRIVATE Github repository. Be sure that your instructor has been added as a collaborator according to the instructions below.

Your submission is due no later than 11:59 PM on Sunday, December 12, 2021.

Late submissions will no be accepted. This includes commits made to your Github repository after the deadline.

To get started:
Sign-up for a free API account at OpenWeatherMap
Download starter HTML and CSS files
Process
In addition to your grade in SD105, this project will also include a grade for your SD130 - Tools & Automation course according to the following requirements:

Use version control: Create a PRIVATE repository for your work on this project. Add cmacmitt as a collaborator on your Github repository.
Include a README file with a brief description of your project.
Make sensible commits along the way. A project like this should have at least 10 commits. More is probably better for managing your work.
Make sure your commit messages are following the guideline we've been using in class: If I apply this commit, it will...
Do your work in a src folder and create a build process using gulp that minifies your js and css files and creates a production version of your code in a dist folder.
Your default gulp task should run all other tasks in series.
Your node_modules and dist folder should not be included in your repository.
Implementation Notes:
To complete this project you will need to utilize at least 2 different endpoints of the Open Weather Map API, Current Weather Data as well as 5 Day / 3 Hour Forecast.
NOTE: The oneCall endpoint SHOULD NOT be used for this assignment.
The forecast is provided in 3 hour blocks, which means you will receive 8 different temperature forecasts per day. The high that is displayed is the highest temperature forecasted for that day, while the low is the lowest temperature forecasted for that day.
Given we cannot average the condition description and image (it may not be cloudy all day), choose a single time everyday that will be used as the condition for the day.
Your output should indicate the 'Current Conditions' as today, and the forecast as the next 5 days.
You will need to use the weather icons provided by the API; you can read more about it here
All temperatures are provided in Kelvin by default. You will need to pass a parameter to the endpoint to request a different temperature unit.
