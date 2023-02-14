# machine_learning

### Software and account requirement.

1. [Github] (https://github.com/)
2. [Heroku_Account] (https://www.heroku.com/)
3. [Vs_Code_IDE] (https://code.visualstudio.com/download)
4. [GIT_cli] (https://git-scm.com/download)


creating conda virtual environment
.....
conda create -p venv python==3.7 -y
...

use conda virtual env
```
 conda activate venv/
 or
 conda activate venv


To install all requirement files we need to run
```
pip install -r requirements.txt


To  Add all files to git
```
git add .

TO add single file 
git add <file_name>

To ignore file or folder from git we can write name of file/folder in  .gitignore file

To check the git status
```
git status

To check all version maintained by git 
```
git log
```

To create version/commit all changes by git 
``` git commit -m "message"


To send version/changes to github
````
git push origin main
```

To check remote url
```
git remote -v


To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = muralikrishna
2. HEROKU_API_KEY = af15f770-7ad2-439c-9c85-123c87cfe524
3. HEROKU_APP_NAME =
