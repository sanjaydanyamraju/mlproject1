# MLPROJECT1 branchname
### First end to end ML project with flask, CI/CD and Heroku 

Software requirements
1. [GITHUB ACCOUNT](https://github.com/)
2. [HEROKU ACCOUNT](https://dashboard.heroku.com/apps)
3. [VS CODE](https://dashboard.heroku.com/apps)

Creating Conda Environment
```
conda create -p venv python=3.7 -y
```
```
conda activate env/
```
> -p is used so that venv will be created in the current working directory. Recommened!

> use conda activate venv/ to activate. if we use conda activate env it will throw an error
```
pip install Flask
```
To add git files
```
git add .
```
To check git status
```
git status
```
To check versions
```
git log
```
To commit
```
git commit -m "message"
```
To push changes form local to remote
```
git push origin main
```
To check remote URL
```
git remote -v
```

> Note: Use integration branch for staging the changes

To setup CI/CD pipelines in HEROKU we need
1. HEROKU EMAIL - <>
2. API KEY - <>
3. HEROKU APP NAME - mlproject1
 


Add Dockerfile
Add unicorn library
Install Docker locally

1. Build Docker Image - must be small case
> docker build -t imagename:tagename .
2. To list docker images
> docker images
3. To delete docker images
> docker image rm imagename
4. To run docker image
> docker run -p 5000:5000 -e PORT=5000 <imageid>
> docker run -p 6000:6000 -e PORT=6000 c1d3004a162f
5. To check running containers
>docker ps
6. To stop the container
>docker stop <container_id>
7. To check processes on port
> lsof -i:5000
8. To kill the processes on port
> sudo kill -9 pid