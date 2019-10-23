# Practice-With-REST
Small server for learning how to use RESTful web services.

## Get started
#### Install python
##### You can install python from https://www.python.org/downloads/windows/ (Be sure to add it to PATH.)
#### Clone the repo
##### git clone https://github.com/aream-provalus/api-training-server.git
#### Change directories
##### cd api-training-server
#### Create python virtual enviorment
##### python -m venv env
#### Activate environment
##### env\Scripts\activate
#### Install flask
##### pip install flask
#### Start the server
##### flask run

### This API supports
##### GET /tasks
##### GET /tasks/<int:task_id>
##### POST /tasks
##### PUT /tasks/<int:task_id>
##### DELETE /tasks/<int:task_id>

Try sending a GET request to /tasks to get started!
