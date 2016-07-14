# Lab 1: What is Git?
Introduction to Git and exploration of browsers

In this lab you will do the following:
 - Create a GitHub Account
 - Learn to use the LXTerminal on your Virtual Machine
 - Use Git to clone a repository
 - Commit and push changes to your repository to submit your homework

## Create a GitHub Account
You should have received a link that will create a repository for this lab assignment to your account. Click on this link: if you already have a GitHub account you can sign in here, or if you don't have one you can create one now.


## Learn to use the LXTerminal on your Virtual Machine
For this first lab you will need to open your Virtual Machine and use the Terminal for the first time. You can reach the terminal by pressing on the Windows like button on the bottom left hand corner of the screen and go to System Tools -> LXTerminal.

You will see the infamous black screen with white letters. You are now officially a hacker :)

The black screen should display something like this:

```
student@student-VirtualBox:~$
```

That prompt is saying that your username is "student" and you are logged into the "student-VirtualBox" computer (the name of the virtual machine). You are now currently in the folder "~", which means your home folder which is:

```
/home/student/
```


Now we want to change directories to the Documents folder by doing the following:

```
cd Documents
```

And now we are in the location where we want to clone the repository we created by clicking on that invite link.

**Please note:** You can also go to the same location using the graphical user interface by going back to the Windows like button on the bottom left hand corner of the screen and going to Accessories -> File Manager PCManFM. Then click on the Documents folder on the left hand side.


## Use Git to clone a repository
Now we want to use git to clone the repository we created earlier and finish this lab. We can do so by first telling git who we are:

```
git config --global user.email "[your email]"
git config --global user.name "[kayashaolu]"
```

Next lets clone this repository. You need to log into your GitHub account, click on the INFO253-FL2016/lab-1-[your username] repository, and then find the green "Clone and Download" button. Copy that url that it shows you.

Now you can run the command:

```
git clone [url]
```

Where [url] is the url that you copied from the GitHub webpage. It should ask you for your username and password, and then it should download the repository!

## Commit and push changes to your repository to submit your homework

Now that you have your repository set, you can now: 
 - make changes to these files
 - ```git add [files]``` them to the staging location
 - ```git commit``` them to your repository
  - Note: Sublime Text will open a text dialog. You can enter the text you would like for the commit there and then close the tab. That will complete the commit.
 - ```git push origin master``` those changes to your remote repository


## Homework Assignment
For the homework assignment, I would like you to create a file in this repository called "browsers.txt" right next to the "readme.md" file and in the text file answer the following questions:

 - What is your experience with web architecture. Have you written HTML before? Written Javascript? etc.
 - What are your favorite features from at least 2 browsers?

You can use Sublime Text to edit files, which can be found by going to the Windows like button and going to Programming -> Sublime Text. You can also type "subl" on the command line. 

Be sure to push your changes to the remote repository. You'll know that you've done it if you can see your changes on the GitHub page.
