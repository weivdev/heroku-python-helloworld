# heroku-python-helloworld
This a simple Hello World Example showing how to create a simple python web app with Flask and deploy it to Heroku. 🙈

### Create from empty new project
- Create new python project, choose `New environment` create or use existing Miniconda Interpreter, choose python3
- `$ conda activate pyweb`
- `$ conda env list`
- `$ pip install flask` 
- `$ pip freeze > requirements.txt` to create the requirements.txt with the version 
- Mark root folder as source.


### Create from Clone
- Clone the repo and create or use existing Miniconda Interpreter, choose python3
- `$ conda activate pyweb`
- `$ pip install -r requirements.txt`
- mark root folder as source.

### Deploy to Heroku
- Make sure you set `master` branch as the default branch in GitHub
- `$ heroku login`
- `$ heroku create weivdev-pythonhelloworld` You can change the website name here 
- `$ git push heroku master`

You can now see your Website on https://weivdev-pythonhelloworld.herokuapp.com/ 🙋
 