# Instructions
Copy the below repo into your personal repo
Repo Link: https://github.com/promiseuche/aplicar-un-agente

=======<br>
Step 1:<br> 
=======
Hello GitHub Copilot agent mode

[Step 1 - Activity 1]<br>
Let's ask Copilot agent mode to help us remember the command and create the branch build-octofit-app and publishing it.<br>

[STEP 1 - PROMPT 1] <br>
Hey copilot, how can I create and publish a new Git branch called build-octofit-app? <br>

======= <br>
Step 2:<br> 
=======
The initial application setup: Directory structure, Python requirements, and MongoDB

[Step 2 - Activity 2] 
Prompt for GitHub Copilot in agent mode to start the creation of our application

[STEP 2 - PROMPT 1] 
Let's take the following step by step and generate instructions in this order and execute the commands.
Use docs/mona-high-school-fitness-tracker.md as a guide for the project structure and requirements.

1. Understand the story of creating the fitness application from the docs/octofit_story.md file.
2. Create the initial directory structure for the octofit-tracker application octofit-tracker/backend, octofit-tracker/frontend.
3. Setup the backend python virtual environment, octofit-tracker/backend/requirements.txt based on docs/mona-high-school-fitness-tracker.md, and install required packages.

Don't proceed with the next activity until all of these steps are completed.

[Step 2 - Activity 2] 
Let's install MongoDB

[STEP 2 - PROMPT 2] 
Based on the example monafit tracker app in the docs/mona-high-school-fitness-tracker.md file and use octofit as the name for mergington's high schools app. > Let's install MongoDB.

1. Install MongoDB and make sure the command is complete.

Don't proceed with the next activity until all of these steps are completed.


[Step 2 - Activity 3] 
Let's start and verify MongoDB is running

[STEP 2 - PROMPT 3] 
Based on the example monafit tracker app in the docs/mona-high-school-fitness-tracker.md file and use octofit as the name for mergington's high schools app. > Let's start and verify MongoDB is running.

1. Start the MongoDB service.
2. Verify the MongoDB service running.

Don't proceed with the next activity until all of these steps are completed.



=======
Step 3: 
=======
Initialize and create the octofit_db MongoDB database, Django project/app, update Django project/app files, and populate the MongoDB database  
[Step 3 - Activity 1]
Setup the Python Django project/app

[STEP 3 - PROMPT 1] 
Based on the example monafit tracker app in the docs/mona-high-school-fitness-tracker.md file and use octofit as the name for mergington's high schools app,  > let's setup the Python Django project/app and run the server.
1. The octofit-tracker/backend directory will store the django project and app with the name octofit-tracker.
2. Setup the additional configuration for the django project/app with the name octofit-tracker.
Don't proceed with the next activity until all of these steps are completed. 

[Step 3 - Activity 2] 
Initialize and create the octofit_db MongoDB database 

[STEP 3 - PROMPT 2] 
Based on the example monafit tracker app in the docs/mona-high-school-fitness-tracker.md file and use octofit as the name for Merington's high school's app. Let's initialize the octofit_db database.

1. Initialize the mongo octofit_db database.
2. Create a correct table structure for users, teams, activity, leaderboard, and workouts collections.
3. Make sure there is a unique ID for the primary key for the user collection.
  ex. db.users.createIndex({ "email": 1 }, { unique: true })
4. Execute the command for me to create the database.
5. List the collections in the octofit_db database.

Don't proceed with the next activity until all of these steps are completed. 


[Step 3 - Activity 3] 
Update the Python Django project/app files 

[STEP 3 - PROMPT 3] 
Based on the example monafit tracker app in the docs/mona-high-school-fitness-tracker.md file and use octofit as the name for Merington's high school's app. Let's update the octofit-tracker/backend/octofit_tracker app files.

1. Update the octofit-tracker/backend/octofit_tracker/settings.py file to include the MongoDB database connection.
2. Update the octofit-tracker/backend/octofit_tracker/models.py file to include the models for users, teams, activity, leaderboard, and workouts collections.
3. Update the octofit-tracker/backend/octofit_tracker/serializers.py file to include the serializers for users, teams, activity, leaderboard, and workouts collections.
4. Update the octofit-tracker/backend/octofit_tracker/urls.py file to include the URLs for users, teams, activity, leaderboard, and workouts collections.
5. Update the octofit-tracker/backend/octofit_tracker/views.py file to include the views for users, teams, activity, leaderboard, and workouts collections.
6. Update the octofit-tracker/backend/octofit_tracker/tests.py file to include the tests for users, teams, activity, leaderboard, and workouts collections.
7. Update the octofit-tracker/backend/octofit_tracker/admin.py file to include the admin for users, teams, activity, leaderboard, and workouts collections.
8. Make sure api_root is in octofit-tracker/backend/octofit_tracker/urls.py
9. Enable CORS in the octofit-tracker/backend/octofit_tracker/settings.py file to allow cross-origin requests from the frontend React app and allow all origins, methods, and headers.
10. Allow all hosts in the settings.py file.
11. Install CORS middleware components.

Don't proceed with the next activity until all of these steps are completed.



[Step 3 - Activity 4] 
Populate the octofit_db database with test data from Django project/app files 

[Step 3 - PROMPT 4] 
Based on the example monafit tracker app in the docs/mona-high-school-fitness-tracker.md file and use octofit as the name for Merington's high school's app. Let's populate the octofit_db database with test data. Use the same data from docs/mona-high-school-fitness-tracker.md file.

1. Create a test data file in the octofit-tracker/backend/octofit_tracker directory.
2. Run makemigrations and migrate the database in a Python virtual environment.
3. Populate the octofit_db database with test data for users, teams, activities, leaderboard, and workouts collections based on test data in docs/mona-high-school-fitness-tracker.md octofit-tracker/backend/octofit_tracker/management/commands/populate_db.py.
4. Verify the test data is populated in the octofit_db database.

Don't proceed with the next activity until all of these steps are completed. 

====
END
====