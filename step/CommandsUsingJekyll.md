---
layout: default
---

# How to Integrate Your GitHub Repository with Jekyll
----
### Step 1
Afterwards, on the same directory, create a new Jekyll site using:
```
jekyll new NAME-OF-SITE
```
```
cd NAME-OF-SITE
```
### Step 2
Then, copy all of the folders and files inside of this directory to our GitHub repository. In this example, the name of the GitHub repository is called 'test'.

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/pathddrive.JPG)


### Step 3
Then, we want to commit these changes to our repository. Open command prompt in this directory. Then, run these commands:

```
git status
```

This will show you the changes that have been made since you last pulled from the GitHub repository. Afterwards, we add the changes we've made by running:
```
git add .
```

Then, we need to commit these changes by running:
```
git commit -m "WRITE-YOUR-MESSAGE"
```

Before we git push our changes, we always need to git pull first to make sure that we are pushing to the most updated version of the repo via:
```
git pull
```

Then, we push the changes to GitHub:
```
git push -u origin master
```

### Step 4
If you want to change the contents of the webpage, you need to create an 'index.html' file and use Markdown when modifying it. If you want to change the settings of the website, you have to modify the config.yml file.

If you modify the config.yml file at all, you will always have to run these on command prompt in the root of your repository before running any other commands:

##### 1.
```
bundle install
```
##### 2.
```
bundle update
```


### Step 5
To run the website (the GitHub repo has now been integrated with Jekyll), open the command prompt in this directory and run:
```
bundle exec jekyll serve
```
