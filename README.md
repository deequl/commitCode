# How to push code to GitHub
Quick guide about commit code to a Github repository from command line.


### ...push a new repository
Open the directory where are files you want upload to a github repository.
If you didn't inicialize git, now it's the moment
```
git init
```

```
git add .
```

```
git status
```
If It's all ok, we can commit it:
```
git commit -m "first commit"
```
Change url, to the url repository you want upload your code
```
git remote add origin https://github.com/deequl/commitCode
```
Time to push your code.
```
git push -u origin master
```

### ...push an existing repository
first you shoud download the content of the repository
```
git pull .
```
```
git remote add origin https://github.com/deequl/commitCode
```
```
git push -u origin master
```

### ...do you have any error?
Try to do this If this is your first push 
>error: failed to push some refs to '...'
```
git push -f origin master
```
