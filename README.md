# Job-Recommend-Webapp

This is an interactive web page provides company and position informations retrieved from GitHub API for users to search and apply jobs.

You can click http://18.220.109.151/jupiter/ to visit this site.

Note: This website provides jobs information based on your geographical location. Therefore, you might not get job items because the Github API does not have items related to your geographical location.

## Introduction
Front End:

Developed an interactive web page for users to search and apply positions (HTML, CSS, JavaScript, AJAX)  

- Used favorite records to provide personalized position recommendation 

Back End:

- Created three Java servlets with RESTful APIs to handle HTTP requests and responses

- Used MySQL database on Amazon RDS to store position data fetched from Github API

- Used MonkeyLearn API to extract keywords from description of positions

- Designed algorithms (e.g., content-based recommendation) to implement job recommendation

- Implemented acontent-based recommendation algorithm to recommend jobs based on favorite records

- Deployed the whole project to Amazon EC2
