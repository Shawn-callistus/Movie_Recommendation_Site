# Movie_Recommendation_Site
Implementation of Movie Recommendation System Using Flask, HTML, CSS and SQL

## Files
The repository includes the following files:

* content.py: A Python script that contains the Movie Recommendation Model which is loaded on to a pickle file.
* model.pkl: A pickle file that contains the Recommendation Model.
* app.py: The main Flask application that redirects all the html pages and connects to the sql database to store and check the records during login.
### Templates:
It contain all the html files.
* index.html: A HTML file that serves as the first page i.e the register page.
* success.html: A HTML file that serves as the login page. If they already have an account, this page is opened.
* pred.html: A HTML file which is the home page and predicts a few suggestions based on the input provided by the user.
### Static:
It contains all the css files and background image.
   * css.css and pred.css : CSS files that contains the styles for the HTML pages in the application. It is used to format and style the HTML elements present in             index.html, success.html, and pred.html.


## How to run the application
* Clone the repository to your local machine
* Ensure that Python, Flask, and all necessary dependencies are installed.
* Open the terminal/command prompt and navigate to the cloned directory.
* Run python app.py to start the application.
* Open a web browser and go to http://localhost:5000 to access the page.
* Enter the username and password to access the homepage page.
* In that page, enter any popular movie of your choice in the text field.
* Then you'll get a few suggestions listed below.
