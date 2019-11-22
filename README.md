![ga_cog_large_red_rgb](https://cloud.githubusercontent.com/assets/40461/8183776/469f976e-1432-11e5-8199-6ac91363302b.png)

# TechMeet


## Intro
A specialised events-finder for Tech professionals looking to find programming-based events.

TechMeet is a group project created whilst studying at General Assembly in the Software Engineering Immersive. This is a MERN stack application using React for the front-end, Express and Node.js for the back-end and serving my data via a Mongo database.


#
## Motivation
As new developers, we wanted to re-create the [Meet-up](https://www.meetup.com/) website but specialise it to other Tech professionals like us.

During the planning stage of our project, the group agreed we wanted to use an external API within our application and use it as a key feature. We chose [Mapbox](https://www.mapbox.com/).


#
## Table of Contents
- [Tech Used](##tech-used)
- [Deployment](##deployment)
- [Getting Started](##getting-started)
- [Game Architecture](##game-architecture)
- [Challenges & Future Improvements](##challenges-&-future-improvements)
- [Creator](##creator)


#
## Tech used
* MongoDB
* Express
* Node.js
* JavaScript
    * React
    * Axios
* SAAS
* HTML5


#
## Deployment
This web app is deployed on Heroku and it can be found here: HEROKU LINK


## Getting Started
Use the clone button to download the source code. In the terminal enter the following commands:

```
<!-- To install all the packages listed in the package.json: -->
$ yarn
<!-- Run the app in your localhost: -->
$ yarn start
<!-- Check the console for any issues and if there are check the package.json for any dependancies missing  -->
```

#
## Game Architecture

### Homepage
This page highlights the core aspects of this website, like the newest content available or upcoming content like the Collections section. As this application is based on animals, animal classification links are present at the bottom of the home page.

### Login & Register


MIA-When the user lands on the website they can login using the form, if they don't have an account they can click on the 'register here' link which redirects them to the register page.

### Profile
MIA-After logging in, the user lands on their profile. Here they can see who follows them, the gems they posted and the ones they liked. From here they can also access the gems homepage and the chats homepage.

### MapBox & Events Index
This page obtains the API data for habitats and displays it through two pages:
* Index page - displays all the habitats
* Show page - shows each habitat with relevant information, and links to the animals living in the specific habitat

### Event Show & Edit
This page obtains the API data for animals and displays it through two pages:
* Index page - displays all the animals and can be filtered via alphabet buttons, which refer to the initial of the animal name
* Show page - shows each animal with relevant information, and links to the animals's habitat

### Profile

### Database
A large aspect of this application is the creation of all the data, instead of using an external API. There are many models used in the backend and each model is conencted to the other models in various ways.

#
## My contributions 👩🏻‍💻
### Project Management
MIA-I was in charge of setting tasks and deadlines in the group. I used Trello to do this, which was very effective and meant that everyone could see what other people were working on to avoid merge conflicts. Here is a screenshot of a sample day:

### 

#
## Planning
### Back-end
Initally, the group used Trello as a way to plan our project. However, as we got through the basic setup of our application we used daily stand-up meetings to organise work delegation and to discuss the status of each web page of our application. At the beginning of our project, we created hand-drawn wireframes:
[HAND-DRAWN WIREFRAMES]

### Front-end
At the beginning of our project, we created hand-drawn wireframes to highlight the user experience of our application:
[HAND-DRAWN WIREFRAMES]

#
## Testing
As we began to build our back-end, the whole group contributed in creating automated tests for a RESTful resource on the back-end, events.

#
## Challenges & Future Improvements
This was my first time working with Django and it was quite a learning curve for me as a lot of the functionality is covered by Django. As I started to understand the relationships between the models, the serializers, the views and the urls, Django became more and more simpler to use as I created my application. Also, this is my first project in which I have used Python as a key programming language and I really enjoyed the challenge of coding in a new language after using JavaScript in my previous projects and throughout my studying at General Assembly. 

In the future, I hope to add a working search-bar on the homepage and on the navigation bar. Also, I'd like to add the additional models in my back-end like collections and the Red List scale for endangered animals, as well as creating web pages for these models.


#
## Creators
- Reema Patel
- Tom Good: [GITHUB LINK]
- Sophie Turnell: [GITHUB LINK]
- Vikram Bageja: https://github.com/vikram1510






## Necessary Deliverables
​
* A **working app** hosted on the internet
* A **link to your hosted working app** in the URL section of your Github repo
* A **git repository hosted on Github**, with a link to your hosted project, and frequent commits dating back to the _very beginning_ of the project
* **A `readme.md` file** with:
    * An embedded screenshot of the app
    * Explanations of the **technologies** used
    * A couple paragraphs about the **general approach you took**
    * **Installation instructions** for any dependencies
    * Link to your **user stories/wireframes** – sketches of major views / interfaces in your application
    * Link to your **pitch deck/presentation** – documentation of your wireframes, user stories, and proposed architecture
    * Descriptions of any **unsolved problems** or **major hurdles** you had to overcome
​
---
​
## Project Feedback + Evaluation
​
* __Project Workflow__: Did you complete the user stories, wireframes, task tracking, and/or ERDs, as specified above? Did you use source control as expected for the phase of the program you’re in (detailed above)?
​
* __Technical Requirements__: Did you deliver a project that met all the technical requirements? Given what the class has covered so far, did you build something that was reasonably complex?
​
* __Creativity__: Did you added a personal spin or creative element into your project submission? Did you deliver something of value to the end user (not just a login button and an index page)?
​
* __Code Quality__: Did you follow code style guidance and best practices covered in class, such as spacing, modularity, and semantic naming? Did you comment your code as your instructors as we have in class?
​
* __Problem Solving__: Are you able to defend why you implemented your solution in a certain way? Can you demonstrated that you thought through alternative implementations? _(Note this is a likely question to be asked by a prospective employer when reviewing your portfolio projects)_


