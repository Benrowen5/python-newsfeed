# Python Newsfeed

  ![License](https://img.shields.io/badge/license-MIT-blue)
  
  ## Description
  This application is a refactor of an existing application which was built using Node.js and Express.js for the backend, Handlebars.js as the template engine, and Sequelize as the ORM. The application now uses Python and Flask for the backend, Jinja2 as the template engine, and Sqlalchemy as the ORM. This application is a tech news blog, where logged in users can create new posts, edit posts, and upvote and comment on posts. Any user not logged in will have the ability to view posts and comments.

  Deployed Application: https://python-tech-news-2022.herokuapp.com

  

  ***************************************************************
  ## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)
***************************************************************
## Installation
Clone this repository to your local machine, activate virtual environment and run python -m pip install -r requirements.txt at the project root.

## Usage
Create a .env file at the project root and paste the following into the file: 

DB_URL=mysql+pymysql://root:"your-localhost-password"@localhost/python_news_db

Make sure the MySQL service is running in your local environment. Using the MySQL shell, ensure the python_news_db database is being used. Populate the database using the seed files by running 'python seeds.py'. With all prior steps completed, in the command line enter 'python -m flask run' to start the app. The application can be accessed at the host port.

For other usage, visit the [deployed application](https://python-tech-news-2022.herokuapp.com)
  
## License
  This project is covered under the MIT license. 
      For details, visit: https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt
  
## Contributing
  Please contact me if you would like to contribute to this project.

## Tests
  There are not currently any tests for this project.

## Questions
  For any questions regarding this project, please contact me via email (Benrowentv@gmail.com).
  
  Check out my other project repositories on Github at: Benrowen5


