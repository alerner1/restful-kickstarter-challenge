# RESTFUL challenge

### Kickstarter
Welcome to Kickstarter. Assume we have a model called `Project` that inherits from `ActiveRecord::Base`, a corresponding table called `projects`, and a controller called `ProjectsController` that inherits from `ApplicationController`

For each of the following descriptions, write out the corresponding:

1. The HTTP Verb and URL (ie 'GET '/dogs'')
2. The rails controller action (ie 'dogs#index')
3. The corresponding CRUD action (ie 'READ)
4. The corresponding ActiveRecord method (ie 'all')


### Actions

1. Displays all of the projects
  a. HTTP verb and URL: GET '/projects'
  b. rails controller action: projects#index
  c. CRUD action: READ
  d. AR method: all

2. Displays information about one project
  a. HTTP verb and URL: GET '/projects/:id'
  b. rails controller action: projects#show
  c. CRUD action: READ
  d. AR method: find

3. Displays a form to create a new project
  a. HTTP verb and URL: GET '/projects/new'
  b. rails controller action: projects#new
  c. CRUD action: READ
  d. AR method: new

4. Creates a new project based on given parameters
  a. HTTP verb and URL: POST '/projects'
  b. rails controller action: projects#create
  c. CRUD action: CREATE
  d. AR method: create

5. Displays a form to update an existing project
  a. HTTP verb and URL: GET '/projects/:id/edit'
  b. rails controller action: projects#edit
  c. CRUD action: READ
  d. AR method: find

6. Updates an existing project with given parameters
  a. HTTP verb and URL: PATCH '/projects/:id'
  b. rails controller action: projects#update
  c. CRUD action: UPDATE
  d. AR method: update

7. Deletes an existing project
  a. HTTP verb and URL: DELETE '/projects/:id'
  b. rails controller action: projects#destroy
  c. CRUD action: DELETE
  d. AR method: destroy
