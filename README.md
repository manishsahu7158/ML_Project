## Machine Learning Project(Test)

### Software and Account Requirements

1. Github Account
2. Heroku Account
3. VS Code IDE
4. GIT Cli


Creating Conda Environment
```
conda create -p venv pyhon==3.7 -y
```

```
conda activate venv/
```
OR


```
conda activate venv
```

```
pip install -r requirements.txt
```

To Add Files to git
```
git add .
```
OR

```
git add <file_name>
```
> NOTE: To ignore file or folder from git we can write name of file or folder in .gitignore file

To check git status
```
git status
```

To check all version maintained by git 
```
git log
```

To create verion/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url
```
git remote -v
```

To setup CI/CD pipeline in HEROKU, we need 3 information
1. HEROKU_EMAIL = manishsahu7158@gmail.com
2. HEROKU_API_KEY = 02112656-135b-4851-92c8-ae2c07b7fe79
3. HEROKU_APP_NAME = ml-test1234

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tag_name> .
```

> Note: Image name for docker must be lowercase

To list docker image
```
docker images
```

Run Docker Image
```
docker run -p 5000:5000 -e PORT=5000 <image_id>
```

To check running container in docker
```
docker ps
```

To stop docker container
```
docker stop <container_id>
``` 