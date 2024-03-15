# Educational project on the theme of a restaurant menu. Implemented CRUD in python (FastAPI) + PostgreSQL.

### Installation instructions for Ubuntu 22.04:

Copy the project from the repository to the local machine using the command:
* git clone https://github.com/Sana451/fast_api_project.git


Go to the project folder with the command:
* cd ./fast_api_project/


If necessary, create a virtual environment using the command:
* python3 -m venv api
* source api/bin/activate


Install python dependencies with the command:
* pip install -r requirements.txt


Open models.py file and configure parameters for connecting to the PostgreSQL database
(DB_USER, DB_PASSWD, DB_HOST, DB_PORT, DB_NAME).


Start the server with the command:
* uvicorn main:app --host localhost --port 8000 --reload
