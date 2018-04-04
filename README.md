# A Website for Tokimon Trainer

- Trainer can sign up and edit their tokimons
- Enter trainer's profile page to edit or delete a tokimon


## Sort Function:
- Clicking on the table header can sort the table base on that attribute

## Using Nested Routes:
- Can't edit and destroy Tokimons in the Tokimon index page
- Write a matching route on the top of a nested route which overwrites the /tokimons/, so that there are two URL routes to tokimons#index
- All routes for tokimons are nested routes and I can pass two id(id and trainer_id) into the url to call the routes
