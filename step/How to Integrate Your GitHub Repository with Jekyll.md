---
layout: default
title: How to Integrate Your GitHub Repository with Jekyll
---

<!-- # How to Integrate Your GitHub Repository with Jekyll -->
----
### Step 1
Firstly, you need to clone your GitHub repository to your local system.

Copy the following URL:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-1.JPG)


### Step 2
In the command prompt, change to the local directory where you want to clone your GitHub repository and write the following:

```
git clone REPO-NAME
```

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-2.JPG)

This is what the folder will look like:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-3.JPG)

### Step 3
Afterwards, on a different directory, create a new Jekyll site using:

```
jekyll new NAME-OF-SITE
```

* The name doesn't have to be the same as the repository's name, but it is the same in this example.

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-16a.JPG)

```
cd NAME-OF-SITE
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-17.JPG)

### Step 4
Then, copy all of the folders and files inside of this Jekyll directory to our GitHub repository. In this example, the name of the GitHub repository is also called 'test-jekyll'.

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-4.JPG)


### Step 5
Then, we want to commit these changes to our repository. Open command prompt in this directory. Then, run these commands:

```
git status
```

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-5.JPG)

This will show you the changes that have been made since you last pulled from the GitHub repository. Afterwards, we add the changes we've made by running:
```
git add .
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-6.JPG)


Then, we need to commit these changes by running:
```
git commit -m "WRITE-YOUR-MESSAGE"
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-7.JPG)


Before we git push our changes, we always need to git pull first to make sure that we are pushing to the most updated version of the repo via:
```
git pull
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-8.JPG)

Then, we push the changes to GitHub:
```
git push -u origin master
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-9.JPG)


### Step 6
If you want to change the contents of the webpage, you need to edit the index.md file in the directory. If you want to change the settings of the website, you have to modify the 'config.yml' file.

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/gitcommand-10.JPG)

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/exampleofindexmd.JPG)

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/exampleofconfig.JPG)


Whenever you modify the config.yml file, the 'Gemfile', or the 'Gemfile.lock', you will always have to run these on command prompt in the root of your repository before running any other commands:

##### 1.
```
bundle install
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/bundleinstall-1.JPG)

##### 2.
```
bundle update
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/bundleupdate.JPG)


### Step 7
To run the website (the GitHub repo has now been integrated with Jekyll), open the command prompt in this directory and run:
```
bundle exec jekyll serve
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/bundleexecjekyllserve-2.JPG)
