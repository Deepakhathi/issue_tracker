# issue_tracker
    nodejs + ejs  application to track issues/bugs for a project.
  
# Hosted URL
    https://issue-tracker-app.onrender.com
      
## Features :

### 1. Build a neat UI
### 2. Home Page
    2.1. Show a list of projects.
    2.2. Give a button to create a new Project (On creating a new project it should appear in the list)
### 3. Create Project Page
    3.1. Accept the following fields to create a project
        -Name
        -Description
        -Author
### 4. Project Detail Page
    4.1. When the user clicks on a project (in home page) redirect the user to this page which will show bugs related to this project
    4.2. User should be able to perform following actions on this page
        -Filter by multiple labels i.e. I should be able to filter by 2 or more labels at the same time
        -Filter by author
        -Search by title and description
    4.3. A button to create an issue
### 5. Create issue page
    5.1. User should be able to create an issue for a project
    5.2. Accept the following fields
        -Title
        -Description
        -Labels (multiple labels can be added to a project, IF a project has a label already show it (in dropdown) as the user types the label in)
        -Author
