# mlproject1
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

* -p is used so that venv will be created in the current working directory. Recommened!
* use conda activate venv/ to activate. if we use conda activate env it will throw an error

```
pip install Flask
```

> To add git files
```
git add .
```
> To check git status
```
git status
```
> To check versions
```
git log
```
> To commit
```
git commit -m "message"
```
> To push changes form local to remote
```
git push origin main
```
> To check remote URL
```
git remote -v
```