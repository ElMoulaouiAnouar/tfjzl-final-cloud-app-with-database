# Final project for the course "Django Application Development with SQL and Databases" provided by `FutureSkills4All` and  `IBM Developer Skills Network`. It is an onlinecourse web application.


## DB Diagram 

<img src="https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/raw/master/static/media/course_images/onlinecourse_app_er.png">

## Installation

To set up and run this project locally, follow these steps:

1.**Clone the repository**

  ```bash
  git clone https://github.com/ElMoulaouiAnouar/tfjzl-final-cloud-app-with-database
  ```
2.**Navigate into the project directory**
  ```bash
  cd tfjzl-final-cloud-app-with-database
  ```

3.**Let us set up a virtual environment to contain all the packages we need.**

```bash
pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
```

4.**Install dependencies**

```bash
pip install -U -r requirements.txt
```

5.**Create the initial migrations and generate the database schema:**

```bash
python3 manage.py makemigrations
python3 manage.py migrate
```

6.**Run application**

```bash
python3 manage.py runserver

```