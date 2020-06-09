# ABOUT
- Awwards

This python/django web-app was created as a clone of the website 'Awwwards'. 
By: ANDASON OKINYI

## Description
This web-app allows a user to create a Profile,Category,Technology and Projects that are all under his username allowing other users to vote for them and visit the particular projects site.

## Setup/Installation Requirements
* Live site can be accessed from the following link https://andersawards.herokuapp.com/



### Behaviour Driven Development
* The program should return all projects on the directories page<br>
Given:All projects<br>
When: Url is changed to directory page<br>
Then: All projects are displayed<br>

* Program should show the project with the highest number of votes on the caraousel on the home page<br>
Given:A Project with the highest votes<br>
When: Home page is accessed <br>
Then: Project with highest votes is displayed.<br>

* Admin site should be displayed when "admin/" url is chosen<br>
Given: An admin url<br>
When: User enters admin url in browser<br>
Then: Admin Login is displayed<br>

* User authentication occurs when Admin tries to Login<br>
Given:Admin page is accessed<br>
When: User tries to login<br>
Then: User details are authenticated to confirm if user is an admin<br>

* User session should end when logout url is chosen<br>
Given:Logout option is given<br>
When: User chooses logout option<br>
Then: User session is ended<br>


### Technologies Used
* VScode was the source code editor of choice.
* Git and Github were used as my local and online repositories respectively.
* Django was used as the framework of choice
* Heroku was used in deploying the live site
* Postman was used in testing the API
 
 ## Credits
- google
### Support and contact details
* Contact me through my email: andersoking77@gmail.com
* The source code is also contained within the folder containing this ReadMe with comments on the code thus third-party support can be offered.

### License
MIT
Copyright (c)2020 ANDASON OKINYI 