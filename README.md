# Software-Dev-Project (Web-App) Alumni Portal

### Features:
- Authentication with email verification, change password, forgot password, update profile, delete user.
- Updating user profile by getting data from linkedin on regular basis using cron-job.
- Alumni can contact other alumni through message box integrated in our site.
- Anyone can contact the alumni office easily and alumni can mail them through our website (There is a limit for a user in a day).
- Alumni can post the jobs/internships present in their company through our jobs page.
- Events and gallery info.
- Blog to share their expereinces with the community.
- Donations and giving back page to help the students/institute.
- Additional:
	- Secured with google recaptcha service. 
	- Works on both mobile, desktop and all ratio devices.

	
### Project and environment setup
```bash
# Setup environment
mkdir Alumni-portal
cd Alumni-portal
python3 -m venv env
# Activate the environment
source ./env/bin/activate

# Clone repository
git clone https://github.com/yabhi0807/Software-Dev-Project.git

# Install the requirement of the project in the virtual environment created 
pip install -r requirements.txt

# go to project folder
cd software-dev-project/
```

```
# you need two terminals to run our project one for running the django server and other for running the chat server
python manage.py runserver

# in another terminal work on the virtual environment created
python manage.py run_chat_server
```

### Techstack

| GUI (front-end)  |  Backend Server |
|------------------|-----------------|
|  HTML5	   |  Python3 v3.8|
| CSS3		   |  Django2 v2.2|
| Javascript	   |  Cron	|
| Bootstrap4 v4.4  |  Sqlite3(database)	|
| JQuery	   |  		|
| AJAX		   |  		|
