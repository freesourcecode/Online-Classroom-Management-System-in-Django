# Online Classroom Management System in Django with Source Code

The **Online Classroom Management System in Django created based on Python, Django, and SQLITE3 Database**.

Teachers frequently utilize a Classroom Management System to guarantee that classroom lessons go well. 

Users can upload documents in Word, Excel, or PowerPoint format, as well as photos, to this online system.

Teachers can also create quizzes that students can take if they are already registered with the system.

An **Online Classroom Management System in Django** is an easy project for beginners to learn how to build a web-based **Python Django** project.

We will provide you with the complete source code and database for the python project so that you can easily install it on your machine and learn how to program in **Python Django**.

>[!NOTE]
>To start creating an **Online Classroom Management System Project in Python Django**, makes sure that you have PyCharm Professional IDE Installed in your computer.

##  Online Classroom Management System in Django: Teacher Features

* **Dashboard**

In this page, the teacher can see all the features of the system.

* **Login Page**

The page where the teacher enters their system credentials in order to gain access to the system’s administrative side.

*  **Manage Assignments**

This is the page where the teacher can add new assignment.

*  **Manage Submissions**

This is the page where the teacher can view all the students who submit their assignment through online.

* **Add Resources**

This is the page where the teacher can add new resources or lesson for their student.

* **Notify Students**

This is the page where the teacher can can notify their students they submit or not.

* **User Features**

## Online Classroom Management System in Django: User Features

*  **Dashboard**

In this page, user can view details of their courses or subject.

* **Register Page**

The page where new user created their login credentials for the website.

* **Login Page**

The page where the system administrator enters their system credentials in order to gain access to the system’s administrative side.

* **Assignment Page**

In this page, Students can download the assignment that the teacher gives and they can upload their assignments upon the deadline of their assignments.

* **Notification Page**

In this page, students can view their notification if there is a new assignment uploaded.

## How to Create an Online Classroom Management System in Django?

Here are the steps on how to create an **Online Classroom Management System in Django** with Source Code.

1. **Open file**.

Open "pycharm professional" after that click "file" and click "new project".

2. **Choose Django**.

Next, after click "new project", choose "Django" and click.

3. **Select file location**.

Then, select a file location wherever you want.

4. **Create application name**.

After that, name your application.

5. **Click create**.

Lastly, finish creating project by clicking “create” button.

6. **Start Coding**.

Finally, we will now start adding functionality to our Django Framework by adding some functional codes.

## Functionality and Codes of the Online Classroom Management System in Django with Source Code

*   **Create template for the instructor homepage in Online Classroom Management System in Django**.

In this section, we will learn on how create a templates for the instructor homepage. 

To start with, add the following code in your instructor_basic_page.html under the folder of instructor/templates/instructor.

```<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>{% block title %}Online CLassroom Management System{% endblock %}</title>
        {% load staticfiles %}
        <link rel="shortcut icon" type="image/png" href="{%  static 'favicon.ico' %}"/>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
        <link href='https://fonts.googleapis.com/css?family=Satisfy' rel='stylesheet' type='text/css'>
        <link href='https://fonts.googleapis.com/css?family=Abhaya Libre' rel='stylesheet'>
        <link href='https://fonts.googleapis.com/css?family=Raleway' rel='stylesheet'>
        <link href='https://fonts.googleapis.com/css?family=Alfa Slab One' rel='stylesheet'>
        <link href='https://fonts.googleapis.com/css?family=Lobster' rel='stylesheet'>
        <link href='https://fonts.googleapis.com/css?family=Ledger' rel='stylesheet'>
        <link href='https://fonts.googleapis.com/css?family=Volkhov' rel='stylesheet'>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
        <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
        <style>
            a{
                color: yellow;
            }
            #id_content
            {
                width: 600px;
                height: 40px;
            }

            body
            {
                background: url('https://i.pinimg.com/originals/5d/5d/79/5d5d79ab40f17440b11dfdf9cd0f1f08.jpg') no-repeat center center fixed;
                background-size: cover;
                font-family: Ledger;font-size: 20px;
            }
        </style>
    </head>
    <body background=""style="font-family: Ledger;font-size: 20px;">
    <nav class="navbar-fixed-top bg-primary">
        <div class="container-fluid">

            <!-- Header -->
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#topNavBar">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                         <a class="navbar-brand" style="font-family:'Lobster',cursive;font-size:30px;" href="{% url 'instructor:instructor_index' %}">Online CLassroom Management System</a>

            </div>

            <!-- Items -->
            <div class="collapse navbar-collapse" id="topNavBar">
                <ul class="nav navbar-nav navbar-right">
                    <li>
                        <a href="{% url 'logout_user' %}">
                            <span class="glyphicon glyphicon-off" aria-hidden="true"></span>&nbsp; Logout
                        </a>
                    </li>
                </ul>
            </div>

        </div>
    </nav><br><br>
    {% block body %}
    {% endblock %}
    </body>
 
    </html>
 ```


### 📌 Here's the full documentation for the [Online Classroom Management System in Django](https://itsourcecode.com/free-projects/python-projects/online-classroom-management-system-in-django-with-source-code/)



