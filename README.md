# This is the Mlops project , I will update this readme file as i will grop in this project

## To make this project below accounts required 
1. Git 
2. Heroku 


### conda evviroment required . for each project seperate enviroment required . 

Create conda enviroment 
```
conda create -p venv python==3.7 -y

```

activate the conda 

```
conda active venv/

```
or 

```
conda active venv

```
To add the file to git 

```
git add .
```
or 
```
git add <file_name>

```
>Note : To ignore file or folder from git we can write name of file / folder in .gitignore

To commit the file ---> add the file in staging area
```
git commit -m "message"
```

To send  the file in centerlized git repo 

```
git push origin master
```
To check the status 

```
git status
```
To check the log of git 

```
git log
```
To get the git url in the terminal 

```
git remote -v

```
For more git commnad [please click on](https://git-scm.com/docs/git)

To setup CI/CD pipeline in heroku we need 3 information 
1. HEROKU_EMAIL =prashant.singh2012p@gmail.com
2. HEROKU_API_KEY = <> this is sensitive information , which I have not disclosed here.
3. HEROKU_APP_NAME= ml-regression-model

BUILD DOCKER IMAGE

```
docker build -t <image_name>:<tagname>.

```

> Note: Image name for docker must be lower case 

To list docker image

```
docker images

```
To run the docker image 
```
docker run -p 5000:5000 -e PORT=5000 <DOCKER IMAGE TAG> # 8b5ba5c30794
docker run -p 5000:5000 -e PORT=5000 8b5ba5c30794

```
To check running container in docker 
```
docker ps
```
To stop the docker container 
```
docker stop <container_id>

```


