# Combination Mini Project

### HTML, CSS and Bootstrap

- A website with linked pages 
- The user can search for and enter books to the online database
- CSS can be used for style, colour and font
- Bootstrap was the favoured tool here, as it was more efficient for the constraints of the project

### Python and SQL

- Two files were created, The first is running the HTML files through a local development environment using 'Flask'
- The second is an sqlite database file, which stores user input and saves the searches
- Originally, A combination of Flask and sqlalchemy were to be used. Again, due to the constraints of the project, sqlite was used
- It is possible to use PYODBC, although that has already been used for pevious project dealing with a different topic

### Running:

- Very simple, you need pycharm or another compiler compatible with Python to begin
- Once ready/installed, run the python file with the flask code
- You should now be able to run the website from your local development environment via a suitable browser, on port 3000

### Use

- Simply type in a book name and author in the search bar and click 'search'. If the result(s) are there, you will be given a full list.
- If the title is not there, you have the choice to add it to the existing database
