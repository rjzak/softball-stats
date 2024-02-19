# softball-stats v 2.0

# Updates
v2.0 - Pared down application to make it simpler. To start the application will start very basic. 

## Purpose

To learn Go and track team stats for the softball season

## Plan

A web application for managing a softball/baseball team and keep stats for the season. 

The application will start with very basic functionality to get something up.

1. A dynamoDB database to hold players and their batting average
2. A basic CLI using flags to update players in the database
3. A basic html website generated by a template with a table from dynamoDB

## Way in the future

A team is signed up and then can add players

Plan for a team page that has coaches and contact information. Updates can be posted for cancellations and other communication. 

Plan for a calendar page to show schedule with game times and location 

A stats page that shows season stats

Players can be on multiple teams 

## Notes 
Very early stages, the thought process is to start by building out a structured program and learn structs, input, basic math a string formatting, building go-modules, etc.

Then evolve to use the SDK for Go to store data in dynamodb or another database solution.

Then possibly evolve to have a front end where team members could go see the team stats.

Look into htmx or a server side rendering to save time and effort writing front end javascript

## Release

### v 1.0 - Create a basic application for a single team to track stats for the season
### v 2.0 - Realistically scope project to get something hosted
### v 2.1 = Incorperate some of the v 1.0 code. Got the create table command working


