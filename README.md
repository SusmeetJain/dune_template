# Dune App Template

This is a template for quickly spinning applications with the new [Dune API](https://dune.com/docs/api/). It uses the [Flask](https://flask.palletsprojects.com/en/2.0.x/) web framework. Check out the tutorial or follow the instructions below to get set up.

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/)

2. Clone this repository

3. Navigate into the project directory

4. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

5. Install the requirements

   ```bash
   $ pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file

   ```bash
   $ cp .env.example .env
   ```

7. Add your Dune API key to the newly created `.env` file

8. Run the app

   ```bash
   $ flask run
   ```

You should now be able to access the app at [http://localhost:5000](http://localhost:5000)!

## Add Your Query
Go to `app.py` and add an ID for the query you would like to run with this app. Add this to the `QUERY_ID` variable.
And then restart the app with your new query.

Please note that currently this template is in Beta. And might not scale well to all queries.