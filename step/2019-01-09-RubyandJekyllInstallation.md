---
layout: default
---

# Ruby and Jekyll Installation Step-by-step
----

### Step 1
To install Jekyll, we first have to install the RubyInstaller:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/installjekyll.JPG)

[https://jekyllrb.com/docs/installation/windows/](https://jekyllrb.com/docs/installation/windows/)

### Step 2
Then, click the link in the first step to download the package (RubyInstaller Downloads)

### Step 3
Choose one of the first two links, depending on your computer's Windows system type (32-bit or 64-bit). If your system is 64-bit, then choose the first link. If your system is 32-bit, then choose the second link.

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/rubyinstaller.png)

### Step 4
Click the icon below in the 'Downloads' folder to start installation process:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/rubyinstallericon.JPG)

### Step 5
Accept the license and click 'next':

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-00.jpg)

### Step 6
Choose the following set-up options and install:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-01.jpg)

### Step 7
Choose the following set-up options:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-02.jpg)

### Step 8
Wait for the loading to finish:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-03.jpg)

### Step 9
Afterwards, choose the following set-up option and click 'finish' to continue:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-04.jpg)

### Step 10
The command prompt would then appear. (If you had not chosen the 'run ridk install' option in the previous step, you can manually input 'ridk install' as a command in the command prompt.)

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-05.jpg)

### Step 11
Press 'Enter' and wait for all the packages to be installed:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-06.jpg)

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-07.jpg)

If any error occurs as shown below, then go to Step 12. If not, skip to Step 13.

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-08.jpg)

### Step 12
Depending on your anti-virus software, the following steps may differ. For this tutorial, we'll use Kasperskey Internet Security as an example:

1. ![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-09.jpg)


2. Go to the 'Threats and Exclusions' option in the software.

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-10.jpg)

3. Choose the 'manage exclusions' option and add the following path to the list:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-11.jpg)

4. Then, choose the 'specify trusteed applications' option and add the following path to the file in the list:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-12.jpg)

### Step 13
If there was an error previously, we need to perform the 'ridk install' command again on the command prompt. Press 'Enter' to start the installation.

If not, just continue waiting on the installation process. Make sure that the 'succeeded' notice appears, as shown below:

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-13.jpg)

### Step 14
After the installation is done, we have to install Jekyll and Bundler using the command:

```
gem install jekyll bundler
```

![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-14.jpg)

### Step 15
Then, we run the following command:

```
gem update
```
![img](https://raw.githubusercontent.com/UI-FASILKOM-OS/extra182/master/SandBox/nardienapratama/img/ruby-jekyll-15.jpg)



And there you go, Ruby and Jekyll has been installed on your PC! :]
