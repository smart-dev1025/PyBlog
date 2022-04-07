# PyBlog
A free, open-source Blog CMS based on the "Django".

------------
### Features
- "graphene_django" section to test graphql
- "Blog" section to create and edit a blog Category
- "Videocast" section to create and edit a videocast Category
- "Skill" section to create and edit a skill
- "Podcast" section to create and edit a podcast Category
- Used "Django Admin" to manage all models
- Used "Sqlite" to create DB
- Translation ready
- Auth system (login & logout and forget a password)
- Front-end forms to create new object
------------

### How to install and run (GNU/Linux and Mac)
                
1. Install `git`,`python3`, `pip3`, `virtualenv` in your operating system
2. Create a development environment ready by using these commands
```
git clone https://github.com/smart-dev318/PyBlog.git		# clone the project
cd PyBlog		                                        # go to the project DIR
virtualenv -p python3 .venv		                        # Create virtualenv named .venv
source .venv/bin/activate		                        # Active virtualenv named .venv
pip install -r requirements.txt		                        # Install project requirements in .venv
python manage.py makemigrations		                        # Create migrations files
python manage.py migrate		                        # Create database tables
python manage.py collectstatic		                        # Create statics files
python manage.py runserver		                        # Run the project
```
3. Go to  `http://127.0.0.1:8000/` to use project
------------
------------
### Run with Docker

1. Install Docker on your operating system
2. Install docker-compose on your operating system
3. Run the following command to create and run the project
```
docker-compose up [-d]
```
3. Go to  `http://127.0.0.1:8000/` to use project
------------

### Notes
The Editorial template is released under license "Creative Commons Attribution 3.0 Unported".

------------
### TODO list

- [x] Create search section
- [x] Create user Login/Logout forms in front-end
- [x] Create dynamic forms to add contents in front-end
