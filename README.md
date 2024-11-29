# Django Hello World Lab

This Django application returns a JSON response with the message: `{"Message": "Hello World!"}`.

## Requirements

- Python 3.10 or higher installed.
- A virtual environment properly set up on your system.
- Django installed inside the virtual environment.

## Instructions to Set Up and Run the Application

1. Clone the repository to your local machine:
   `git clone https://github.com/Jayavic/Django-Hello-world-lab.git && cd Django-Hello-world-lab`

2. Activate the virtual environment:
   `source /tmp/app/bin/activate`

3. Install the required dependencies:
   `pip install django`

4. Apply the database migrations:
   `python manage.py migrate`

5. Run the Django development server:
   `python manage.py runserver`

6. Open your web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/). You should see the following JSON response:
   `{"Message": "Hello World!"}`

## Notes

- Always ensure the virtual environment is activated before running the server or installing dependencies.
- If you encounter any issues, check your Python and Django versions using the following commands:
   `python --version && pip show django`

