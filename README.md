Running the application using, python3 -m flask run

To test that the application is working, open a new browser and navigate to http://localhost:5000.

Directory structure for project,
Flask-docker

|____ app.py

|____ requirements.txt

|____ Dockerfile


To start the application and to confirm that it is running properly, run the following command:
docker compose -f compose.yml up --build

To test the API endpoint, run the following command:
curl http://localhost:8000/initdb
curl http://localhost:8000/widgets

Using Github runner for CI/CD:
> Setup SSH key in the Gitlab account.
> Add .gitlab-ci.yml file, add jobs to the file which can be added to different stages

