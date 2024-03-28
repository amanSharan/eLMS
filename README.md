# e-Learning Management System

A learning management and online assessment system for academic education.

## Features

- Admin adds courses, teachers, and students and assigns them courses.
- The teacher creates course content, announcements, assignments, quizzes, takes attendance, etc. A teacher can see the details and analysis of the assessments.
- Students can enroll in the courses using the access key, see the course content of the enrolled courses, participate in assessments and see their results in detail.
- Discussion section for both teacher and student.

## Relational Schema

![schema](https://user-images.githubusercontent.com/87283264/187967219-55bea00e-3151-488a-a4be-d2a95b9d8a5c.png)

## Tech Stack

1. Django 4.0.4
2. Bootstrap 5.0.2
3. jQuery 3.6.0
4. Chart.js v3.9.1
5. Animate.css 4.1.1
Clone the project
git clone https://github.com/nz-m/eLMS-SWE.git
Go to the project directory
cd eLMS-SWE
Create a virtual environment and activate it (Windows)
python -m venv env
env\Scripts\activate
Install dependencies
pip install -r requirements.txt
Note: If you're using newer versions of python(3.10+), you may need to add the --use-deprecated=legacy-resolver option when installing dependencies with pip to avoid errors :

pip install -r requirements.txt --use-deprecated=legacy-resolver
Make migrations and migrate
python manage.py makemigrations
python manage.py migrate
Create admin/superuser
python manage.py createsuperuser
Finally run the project
python manage.py runserver
Now the project should be running on http://127.0.0.1:8000/

## UI

![Screenshot (65)](https://user-images.githubusercontent.com/87283264/194387627-47bc4506-5acb-46da-8ae0-70ea1e7e4eb8.png)
![Screenshot (63)](https://user-images.githubusercontent.com/87283264/194389617-1d1118a5-e0a1-41a2-94b6-ef636e6a8d5e.png)
![Screenshot (71)](https://user-images.githubusercontent.com/87283264/194389301-da1f2cd5-11fd-469d-9137-380c4916e169.png)

