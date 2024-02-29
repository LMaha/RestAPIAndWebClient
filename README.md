# Restaurant Reviews API to demonstate to write and consume API

This project demonstrate to write API for Restaurant reviews and to consume it. Tech stack used is C#.
## Objective of this Project
To demonstrate how to build API and consume it. There are two folders in this project which demonstrate actual API declarations and other one how to use it.
- RestaurantreviewAPI, in this folders all the controllers are defined.
  - Restaurant, Review and User Controller(controller class which will map the routes for Http Get, Post..)
  - DatabaseScript, to create database with schema and insert records.
  - RestaurantRepository, ReviewRespositiry. Repository folders in this classes with linq commands to query database to fetch records  
- Webclient
  - Program, main method of the program
  - Entities classes, Restautant, ResaturantReview, and Review
  - API calls classes for RestaurantAPI, ReviewAPI. These classes will call method of user defined Http class.

