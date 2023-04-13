# CAREER PATH SITE

### INSTALLATION 
The packages needed to run this app is in the requirements.txt file. You can install them using the command bellow but first, make sure you have python installed on your system since the appliucation is a flask app

```
pip install -r requirements.txt
```

### DESCRIPTION
this site is design to help students particularly at AAMUSTED who offer IT with guidance on a career path in tech to follow during their stay on canpus. It has two sections. The user section and the admin section. The user has the eligibility view the available career paths on the site and also have the choice of applying for a mentor. 
The admin section on the other hand offers a the previlage to add more careers to the site, delete existing careers or edit them as well. 
The data base is built using sqlalchemy since the the site is built with flask framework.
The admin USERNAME namd PASSWORD are set in the database. there is no register pages for the admin. The default username and password is "Admin" and "admin@pass"
The database is created as soon as the app is lunched. Use the following commands if you are not familiar with sqlalchemy to setup the admin username and passwrod.
First, lucnch python from terminal.
```
>>> from main import models 
>>> from main.models import db
>>> admin = AdminUser(username="USERNAME", password="PASSWORD")
>>> db.session.add(admin)
>>> db.session.commit()
>>> exit()
```

After this, you ca start the app by running the following command:
```
python main.py
```

### CONTRIBUTIONS
to add your contributions to this project, fork the oriject to your repo, after making the necessary changes, use a new feature branch to push your contibuions.
