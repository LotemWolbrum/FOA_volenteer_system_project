# FOA Volenteer System

This repository contains Full Stack system for the final project for my Industrial Engineering Management degree, developed in collaboration with a team of 3 members, including myself, to the FOA NGO. The project utilizes a combination of mySQL, C#, HTML, CSS, JS, and jQuery to achieve its objectives.

# About the NGO

Fighting Online Antisemitism (FOA) is an Israeli-based NGO dedicated to combating antisemitism through volunteer training, reporting antisemitic content on social media, and raising awareness of the phenomena of cyberhate.

# Project Description

Our system tackles the challenge of consolidating crucial data in one place and provides valuable statistics. It goes a step further by offering recommendations to identify and report viral antisemitic posts.

And I'll give you the details:
The projects contain control of reports, control of volunteers' hour reports and optimize the storage of all the information in one place.
The volunteers of the FOA report anti-Semitic posts they find on social networks with the addition of a screenshot of the post. After uploading the post to the system, a system administrator should go over the post and confirm whether it matches the criteria for an anti-Semitic post and in addition enter the status of the post on the network and therefore it will be possible to be updated and know whether the post has been removed from that social network or not.
The FOA has volunteers who need to enter their volunteer hours and receive approval from their team leader for each report they entered. We made that easy to use for both volunteers and team leaders. 

We have added additional value to this project by making a recommendation system for the volunteers. According to a calculation with different weights for the parameters: likes, comments and shares, the recommendation system presents the social network with the greatest influence, as well as the most common language and hashtag/keywords. The system also has a Dashboard BI page that can recommend to the volunteer where else to look for anti-Semitic posts in the network.

# Technologies Used

 * **mySQL**: We've made a full database using Tables and their connections, also we used Stored Procedure to access the DB from the server side.
 * **C#**: All server side (Backend) is written in C#. It's It is divided into 3 sections, namely Controllers, Models, and DAL (Data Access Layer).
 * **HTML, CSS, JS, jQuery**: The client side (Frontend) is using HTML for creating the pages, CSS for enhancing the visual appeal, and JS for making the data dynamic from the server.

Namespace used: System.Net.Mail

# Main screens from the system

Login:

![תמונה](https://github.com/LotemWolbrum/FOA_volenteer_system_project/assets/105001516/0f5d93fd-0c2e-402c-9f29-fb7f65dc4fac)

Homepage- the result of the recommendation system and total posts uploaded:

![תמונה](https://github.com/LotemWolbrum/FOA_volenteer_system_project/assets/105001516/39f2d2fb-391a-4886-8302-95e029e34d69)

Dashboard BI:

![תמונה](https://github.com/LotemWolbrum/FOA_volenteer_system_project/assets/105001516/fff015c2-aa7a-43a2-bf20-e5f6badb9410)

Edid & view post details:

![תמונה](https://github.com/LotemWolbrum/FOA_volenteer_system_project/assets/105001516/47c7c2e7-a180-47cd-9eb1-a7f0ba4ba003)


Total hour reports:

![תמונה](https://github.com/LotemWolbrum/FOA_volenteer_system_project/assets/105001516/73a731ed-1bd6-4262-ad7d-a322472df721)

Add new hour report:

![תמונה](https://github.com/LotemWolbrum/FOA_volenteer_system_project/assets/105001516/ad24da5a-df45-4bca-8d94-2c384a57421d)

Main team page:

![תמונה](https://github.com/LotemWolbrum/FOA_volenteer_system_project/assets/105001516/a431d416-6d1b-4dc1-b0df-1262fe332bf8)




