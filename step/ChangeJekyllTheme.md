# How to Change the Jekyll Theme with a GitHub-Pages Supported Theme
-----
By default, your GitHub Pages site would have a minima theme. This is a step-by-step tutorial on how to change the theme of your GitHub Pages site with a GitHub-Pages supported theme,  which can be found in this [link](https://pages.github.com/themes/).

### Step 1

Firstly, choose the theme of your liking from the link given [here](https://pages.github.com/themes/).

### Step 2

You will then be redirected to the theme's corresponding GitHub repository on github.com.

1. To use the chosen theme (e.g. the Architect theme), add the following to your site's 'config.yml' file:

```
theme: jekyll-theme-architect
```

2. If you'd like to see a preview of your site on your computer's localhost, then add the following to your site's 'Gemfile':

```
gem "github-pages", group: :jekyll_plugins
```

### Step 3

If you'd like to further customize your website, there would be additional instructions in the theme repository's README.md file, just as shown below.

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/themereposettings.JPG)
