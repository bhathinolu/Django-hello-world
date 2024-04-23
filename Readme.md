# Hello World Django App

This is a simple Django app that returns a "Hello World!" message in JSON format or renders a basic HTML page with the message.

## How to Run/Start the Web App

1. Make sure you have Python and Django installed on your system. If not, you can install Django using pip:
    
    pip install django
    

2. Clone this repository to your local machine:
    
    git clone `https://github.com/bhathinolu/Django-hello-world.git`
    

3. Navigate to the project directory:
    
    cd helloworld_project
    

4. Run the Django development server:
    
    python manage.py runserver
    

5. Open your web browser and visit `http://127.0.0.1:8000/` to see the Hello World message.

## Accessing the Hello World JSON Response

To access the JSON response directly, visit `http://127.0.0.1:8000/`.

## Repository Structure

- `helloworld_project`: Django project directory.
- `helloworld`: Django app directory.
  - `views.py`: Contains the view functions.
  - `urls.py`: Defines URL patterns for the app.
- `README.md`: This file providing instructions on how to run/start the web app and access the Hello World JSON response in a browser.

