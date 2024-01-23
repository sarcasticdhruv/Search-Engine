# Search Engine 

A Django project for a search engine. This project includes a simple search functionality that allows users to search for content in a database.

## Getting Started

### Clone the repository:

```bash
git clone https://github.com/sarcasticdhruv/Search-Engine.git
```

### Create a virtual environment and activate it:

```bash
python -m venv env
source env/bin/activate   # For Linux/macOS
env\Scripts\activate     # For Windows
```

### Install the dependencies:

```bash
pip install -r requirements.txt
```

### Create a new database and update the DATABASES setting in settings.py with the appropriate credentials.

### Run the migrations:

```bash
python manage.py migrate
```

### Start the development server:

```bash
python manage.py runserver
```

### Open your web browser and navigate to [http://localhost:8000/home/](http://localhost:8000/home/) to see the search functionality in action.

## Files

Here's a brief overview of the files included in this project:

- **search_engine/:** This is the main Django app for the search engine.
- **search_engine/urls.py:** Contains the URL patterns for the search engine app.
- **search_engine/views.py:** Contains the view functions for the search engine app.
- **search_engine/templates/search_engine/home.html:** HTML template for the search engine home page.
- **search_engine/templates/search_engine/search_results.html:** HTML template for the search results page.
- **search_engine/models.py:** Contains the database model for the search engine app.
- **search_engine/forms.py:** Contains the form classes for the search engine app.
- **search_engine/signals.py:** Contains the signal handlers for the search engine app.
- **search_engine/tests.py:** Contains the unit tests for the search engine app.
- **search_engine/migrations/:** Directory containing the database migration scripts for the search engine app.
- **requirements.txt:** List of required dependencies for the project.

## Contributing

If you'd like to contribute to this project, please submit a pull request with your changes. Before submitting a pull request, make sure to run the tests and ensure that they pass.
