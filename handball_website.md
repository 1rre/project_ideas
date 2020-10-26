# Handball Website

## General Idea
* A website for the university handball club  
* Allows players to sign up for sessions during the COVID era using an SQL database 
* Automatically closes signups after it becomes full 
* Allow players to cancel their signup, re-opening the signups if this means the session is no longer full 
* Identifies players from their CID 
* Automatically emails the member running the session with the attendance list 

## How to make it
* Use union hosting (if they respond to the email) 
* Use an Elixir/Phoenix backend to close signups & contact the SQL database 
* Possibly add an admin page to create sessions? Otherwise just manually add them to the SQL database 

## Restrictions
* Getting approval from the union 
* Waiting for the webpage & database to be set up by the union SYSADMIN 
* Fitting creation around uni work 