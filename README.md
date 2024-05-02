# Smart Healthcare System
This is a web application that predicts the disease of the patient based on the symptoms entered by the user along with many other functionalities mentioned below. The complete application is developed using django framework.

# Steps to run the app
1. Clone the project.
2. Create a virtual environment and install dependencies using "mkvirtualenv new_project pip install -r requirements.txt"
3. Create a new superuser for the admin using "python ./manage.py createsuperuser".
4. Run the development server to verify everything is working using "python ./manage.py runserver".

# Features
1. Predict disease based on the symptoms entered by the user.
2. Generate proper report in pdf format.
3. Print and share report.
4. Display symptoms and precautions for a particular disease.
5. Interective frontend.
6. Fuzzy logic implemented in disease search funtionality.
7. Login and signup, both by google and manually registeration.

# Dependencies
1. Django Framework.
2. Naive byes algorithm for predicting disease.
3. Gmail api for login.
