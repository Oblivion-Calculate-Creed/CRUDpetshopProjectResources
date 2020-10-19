# Cloud Native - Fundamental Project Specification README

The purpose of this README is to outline the Fundamental project specification that I will be working on during training.
It contains a complete set of the expectations and requirements for the project and well as documented progress and a final result.

# CRUD  Application - Scott's Petshop

## Contents
* [Extra Resources](#extra-resources)
* [Brief](#brief)
* [My Approach](#my-approach)
* [Project Progress](#project-progress)
* [Risk Assessment](#risk-assessment)
* [Testing](#testing)
* [Front-End Design](#front-end-design)
* [Known Issues](#known-issues)
* [Future Improvements](#future-improvements)
* [Mentions](#mentions)
* [Authors](#authors)

### Extra Resources:
* All of my extra resources can be found in: https://github.com/Scottynic112/CRUDpetshopProjectResources
 - Presentation
 - Testing Screenshots
 - Risk Assessment Screenshots
 - Risk Assessment File
 - Jira Board Screenshots

## Brief
The project will involve concepts from all core training modules; more specifically, this will involve:

-Project Management - I have been asked to use Jira. 
-Databases - h2
-Java SE
-Spring Boot
-Front-End Development - HTML, CSS, JavaScript
-Automated Testing
-Continuous Integration
-Cloud Fundamentals

To summarise, my task is to create a CRUD application with the utilisation of supporting tools and methodologies. 
Do to the short time scale of our project some of the requirements were edited.

### My Approach
To achieve my goal, I have decided to create a Petshop application. The user will be able to fill out the form on my designed FrontEnd that creates a card. This card will display all of the information on the pet they wish to advertise. The card will be displayed in a tidy row at the bottom of the page where an update and delete option is found neatly on each card.. Here the user can choose to update the pet through a pop-up window for ease. The delete button will completely remove the animal from the page and database. 

Create Function: A form on FrontEnd with instructions and an obvious submit button. (CREATE)
   * *Creates an animal with:
   * *Name + Common Name(Breed)*
   * *Type*
   * *Price*
   * *Sex*
   * *Colour*
   * *Date*
Update function will show a pop-up window which allows you to change the details listed below. (UPDATE)
   * *Name*
   * *Price*
   * *Colour*
   * *Date*
...This is due to the fact breed, type and sec are unlikely to change.
* View and updating their animal is done through a card system for simplcity. (READ and UPDATE)
* Delete button on each card allowing the user to remove their animal (DELETE)

If I were to do the project again or with a little extra time I would like to have made a select feature (checkbox or filter system). 

## Project Progress
I have attached images of my Jiira Board on: https://github.com/Scottynic112/CRUDpetshopProjectResources. This was one of  the requirements of my project. I used Jira to track my requirements and progress. 

The board has been designed to be simple. Considering I want my plans to be clear I didn't want a cluttered board.
* *To Do*
   A list of requirements and tasks set out in the brief that I need to complete in order for this to be a successful project.
* *In Progress*
   Once the element has had any code written or a design created for it... Basically exists in any way, it is placed in the 'In progress' list.
* *Future Improvements*
   Any ideas or changes I would make if I were to do the project again.
* *Done*
   Once the task is finished then I place it into 'Done'.

## Risk Assessment
The risk assessment for this project can be found in full here: https://github.com/Scottynic112/CRUDpetshopProjectResources

A screenshot can also be found on: https://github.com/Scottynic112/CRUDpetshopProjectResources

## Testing
For the testing I used three variants: JUnit, SpringBoot and Mockito. Using these methods tested: Application, Unit and Integration. In total I ran 10 tests, all returning successful with 92.4% coverage. 
Unit tests run each accessible function in isolation. This means that logic checks can take place to highlight any additions to the code as it would then cause an error. Mockito replicates results for functions that require external data. Whereas Integration tests are tests run on an isolated and pre-determined database (version of) and allows all requests to the database can be tested. 

After downloading a coverage plugin on Spring, I was able to check the coverage to meet my testing requirements. This shows how much of the app is being successfully tested. I have taken three seperate screenshots to show my coverage results and attached them into my GitHub - CRUDpetshopProjectREADME.

## Front-End Design
The front-end of the app is finished and fully functioning. I have attached images of the front page and a picture of some example cards onto: https://github.com/Scottynic112/CRUDpetshopProjectResources

## Known Issues
There are no known bugs thus far. I have tried numerous tests to see if there were any problems however they have all been fixed up to my known knowledge. 

## Future Improvements
There are a number of improvements I would like to implement (outside of current bugs):

- As stated before I would like to have create a select feature that allowed the user to select more than one animal (to update or delete). 

- Potentially a filter option for viewing. This will have been important if the website was to grow in size and there were many pets. However, during this project there were not enough animals for this to be implemented. 

- I would like an option where the user can add a picture of the animal. This would be a nice addition especially as seeing the animal would be a must for most buyers. 
 - Adding to this a contact feature for the owner of that pet would also be a nice addition but thoughts on security/ logins would be necessary. 
 
 - Aesthetically I am happy with the current design there are obviously small changes and improvements that could be made but for the most part it looks good and is functioning as intended. I would like to create a new page for all of the cards in the future. 

## Mentions
I would like to make special mentions to my course leaders (so far): Alan and Jordan. Jordan in particular for all the help and support with my first full stack application!

## Authors
Scott Nicolson
