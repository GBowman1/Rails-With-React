## Project Description
  The point of this project is to create a functioning site for users to leverage while playing the new Elden Ring DLC. The site will allow users to use a calculator feature to find min/maxed stats for a weapon they want to build. The site will leverage the Elden Ring API for its source of game data. The site will allow users to create builds that can include a build guide for other users to check out and try for themselves. The goal is to leverage to API to get data on equipment, how and where that equipment can be obtained. For the calculator the API will provide the stat type scaling for weapons to enable our calculator to do the math to hopefully generate optimal stats for the weapon damage, The user should input there desired Health and Stamina stats as well as a level so the calculator has something to work off of.
  
## Initial Project Goals
- Use Rails, React, Elden Ring API, Bootstrap

- A page that acts as a calculator where a user can select a weapon and the calculator will return min/maxed stat spread, as well as recommended equipment

- Next we want to implement CRUD to allow users to create builds and publish them to an index for other users to view
  - a Show page for a build should leverage the API to provide information on where that equipment can be acquired
  - A create form should allow user to use selects to find items, (prefered a visual feedback of value where user can see image of that piece of equipment next to the select), create        for should not require but also allow user to write a guide for the build.

# Refactor & New Features
- Implement the ability to store users in rails db.
  - Create a login feature
  - create users
  - create admins
  - Admin should be the only ones able to delete all builds
  - users can delete their builds from db
  - create a seperate profile for users to have a users/builds where that user can see their builds
  - maybe figure out how a user can save a build from all builds index to there builds

## DB SCHEMA

## Project Resources
  Link to API Docs:
  Heroku Deployment:

## Project Learning Goals
  - Building a project splitting frontend and backend between rails and react
  - Consuming an API
  - Learn how to store user and admin logins and profiles in rails DB
  
