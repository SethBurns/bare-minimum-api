# Bare-Minimum API
## [View The Deployed API Here](https://bare-minimum-api-53c62eb03bf8.herokuapp.com)
## [View Front-End Repo for this API](https://github.com/SethBurns/bare-minimum)
## Overview

This is an API which serves data for miniscule tasks to complete based on a category. Each task has an id, task, seen, category, saved, and completed property. Constructed using PostgreSQL, Knex, and Express.js, deployed to Heroku. 

## Set Up


## Endpoints

`https://bare-minimum-api-53c62eb03bf8.herokuapp.com/` + `endpoint`

  |             Endpoint              |              Use             |   Method   |  Required Properties for Request |
  |-----------------------------------|:----------------------------:|:----------:|:--------------------------------:|
  |       `/api/v1/tasks`         |      get all task data      |    GET     |               none               |
  | `/api/v1/results/`              |  get all results data  |    GET     |               none               |
  |       `/api/v1/savedtasks`        |      get all saved tasks      |    GET     |               none               |
  |       `/api/v1/tasks/:category`        |  get tasks per category |    GET    |            none                   |
|       `/api/v1/savedtasks`        |      post to saved tasks      |    POST     |               none               |
|       `/api/v1/savedtasks:id`        |      patch saved task      |    PATCH     |               none               |
|       `/api/v1/savedtasks:id`        |      delete saved task      |    DELETE     |               none               |

## Future Extensions
 - [ ] Add search feature within saved tasks
 - [ ] Add a suggestions form for the user to suggest a task for a category
 
## Tools & Technologies
 - SQL
 - Postgresql
 - Knex
 - Express
 - Heroku

## Contributors
<table>
     <tr>
        <td> Calli Herrmann <a href="https://github.com/CaliHam">GH</td>
        <td> Hollis Vohr <a href="https://github.com/hvohr">GH</td>
        <td> Seth Burns <a href="https://github.com/SethBurns">GH</td>
        <td> Taranveer Singh <a href="https://github.com/taranveersingh93">GH</td>
    </tr>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/u/126219151?v=4" alt="Calli GH img"
    width="150" height="auto" /></td>
        <td><img src="https://avatars.githubusercontent.com/u/123392693?v=4" alt="Hollis GH img"
    width="150" height="auto" /></td>
        <td><img src="https://avatars.githubusercontent.com/u/123792434?v=4" alt="Seth GH img"
    width="150" height="auto" /></td>
        <td><img src="https://avatars.githubusercontent.com/u/122247155?v=4" alt="Taranveer GH img"
    width="150" height="auto" /></td>
    </tr>
</table>
