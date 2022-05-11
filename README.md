<!-- TABLE OF CONTENTS -->

# Ask Mate - Simple Forum

<summary><h2 style="display: inline-block">Table of Contents</h2></summary>
<ol>
<li>
    <a href="#about-the-project">About The Project</a>
    <ul>
    <li><a href="#tech-used">Tech Used</a></li>
    </ul>
</li>
<li>
    <a href="#future-roadmap">Future Roadmap</a>
</li>
<li>
    <a href="#getting-started">Getting Started</a>
    
</li>


</ol>

<!-- ABOUT THE PROJECT -->

## About The Project

Ask Mate is a forum-like website where users can ask and answer questions, comment on and upvote/downvote the questions and answers. 
The uploaded content can be edited or deleted by the user that posted the content.
Other users can validate the answers by upvoting (or downvoting) them.

Current features include:

- Main page where users can register or log in and see the current list of questions. A registered user can also access a dashboard to check the questions they have posted. <br/><br/>
  ![main](https://user-images.githubusercontent.com/79319253/167782936-f1338237-0724-488a-a087-69fd6e8d2942.png)

  <br/>
  <br/>
  <br/>

- Add a new question form, enabling users to post their own questions (similar template for answers and comments). <br/><br/>
 ![addquestion](https://user-images.githubusercontent.com/79319253/167783149-a30284cf-8714-4a8a-a6f9-2e4f23698f3c.png)

  <br/><br/><br/>

- Question page, with information regarding the user who made the post and timestamp, number of views and number of edits. Here, users can comment on the question, post answers, or comment on answers.  <br/><br/>

 
![entry](https://user-images.githubusercontent.com/79319253/167796931-c86f2a0d-9e92-44b6-9c1f-1ea2abc53b57.png)


  <br/><br/><br/>


## Future roadmap

- Update visual elements
- Sort questions 
- User reputation ranking system


### Tech Used

- Python
- Python Flask
- HTML
- CSS
- Bootstrap
- Postgresql

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.


1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Create these environmental variables for the connection to the database: 
   ```
    PSQL_USER_NAME = yourUsername
    PSQL_PASSWORD = yourPassword
    PSQL_HOST = databaseURL
    PSQL_DB_NAME = databaseName
   ```
   
3. Run the SQL script found in the sample_data folder in your database

4. Create a new virtual environment and install the requirements by running the next commands in the project's root folder:

    ```
   virtualenv -p python3 venv
   source venv/bin/activate
   venv/bin/pip3 install -r requirements.txt
   ```
   
5. Open a new browser page at the next address: http://127.0.0.1:5000

6. Make sure your device can run all the technologies in the build section

