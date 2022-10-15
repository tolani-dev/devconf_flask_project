# devconf_flask_project
This project helps developers register online  to attend  developers conference. The application is powered by python flask on the server-side.
Collaborated with Cohort22 of maot academy on this project
Steps TAken in setting up the project

1. CREATED A FOLDER CALLED DEVCONF
2. CD INTO DEVCONF 
3. CREATED A VIRTUAL ENVRIOMENT USING THE TERMINAL; "python3 -m venv vdevconf". note that the name of the virtual enviroment could be anything
4. ACTIVATED THE VIRTUAL ENVIROMENT USING THE TERMINAL: "source vdevconf/bin/activate"
5. INSTALLED flask using; "pip install flask"
6. INSTALLED mqsql.connector using; "pip install mysql-connector"
7. INSTALLED SQLALCHEMY using. "pip install sql_alchemy"
8. CREATED AN INSTANCE FOLDER WITH config.py file within, CREATED  A starter.py file inside of the devconf folder, CREATED pack folder with contents as follows: 1.routes folder, 2. an __init__py file, 3. a static folder for static files, 4. a templates folder for html files, 5. a mymodels.py
9. WE CONFIGURED THE APP INSIDE config.py
10. ON THE PYTHON SHELL WE RAN THE COMMAND BELOWS TO CREATE A TABLE WITH ITS PROPERTIES:
        >>>from pack import db
        >>> from pack import app
        >>> app.app_context().push()
        >>> db.create_all()
11. READ MORE DETAILS WITHIN THE FILES