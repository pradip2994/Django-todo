# Django-todo
A simple todo app built with django
<img width="1440" alt="todoApp" src="https://github.com/pradip2994/Django-todo/assets/124191442/1a9d61bf-f4fd-43ae-8d8b-903d0dc949a7">
### Setup
To get this repository, run the following command inside your git enabled terminal

```bash
$ git clone https://github.com/pradip2994/Django-todo.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)


# Created a Docker-integrated Jenkins declarative pipeline.

1) Go to jenkins UI
2) Click on “ New items ”
3) Add name, click on “pipeline”
4) In ‘ General Section’ add Description
5) Tick ‘ Github project’ , add URL of github Repository.
6) In Pipeline section, Select ‘ Pipeline Script’
7) Write Script and Save
8) Now click on “ Build” , see the Stage View.


![image](https://github.com/pradip2994/jenkins-CICD-main/assets/124191442/ece0a902-5958-442b-8abe-87dc77d10c19)
![image](https://github.com/pradip2994/jenkins-CICD-main/assets/124191442/35539d07-8d2a-4bc7-817b-9675cae34067)
![image](https://github.com/pradip2994/jenkins-CICD-main/assets/124191442/5eeb498f-a4a5-426d-8363-836a4c6b503a)
![image](https://github.com/pradip2994/jenkins-CICD-main/assets/124191442/635a8e8a-258b-4689-b666-c140a9666d67)
![image](https://github.com/pradip2994/jenkins-CICD-main/assets/124191442/d53c6624-1b5d-45ca-b4b8-338782ec5d73)

