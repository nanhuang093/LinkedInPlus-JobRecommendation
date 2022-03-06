# LinkedInPlus-JobRecommendation
A website application for users to search, save and apply job positions based on their own requirement 

# Main Features

User registration, login and authentication
<img width="1431" alt="job main" src="https://user-images.githubusercontent.com/97426238/148728240-5e338051-a2fe-4cc3-83fc-443dd7949bf3.png">

User job search based on user's geo_location, favorite jobs and recommend jobs
![Job Recommendation](https://user-images.githubusercontent.com/97426238/148728284-da59b3e8-cad4-4449-9130-aeab096696f6.png)

## External APIs
GitHub Job API [https://jobs.github.com/api]

Monkey Learn: for keyward extraction [https://monkeylearn.com/keyword-extraction/]

## Flowchart of Back-end Logics
Simplified Back-end Structure
<img width="671" alt="Job Recommendation back-end" src="https://user-images.githubusercontent.com/97426238/156944715-5e4d6a4d-a43d-40ad-9b45-af53eaf49c78.png">

## Major Impacts
Built web application for users to search, save and apply job positions using **JavaScript, HTML, CSS, and AJAX**.

Implemented **RESTful APIs** on **Java Servlets** to retrieve job descriptions and interreact with database using **MySQL** on **Amazon RDS**, and extracted job keywords with **TF-IDF** algorithm using **Monkey Learn API**.

Recommended jobs using **Content-based Recommendation** algorithm based on user search history and favorites.

Deployed the service to **AWS EC2** with **Docker** container to handle 150+ queries per second.
