# Lab 1: What is Git?
Introduction to Git and exploration of browsers

## Use Git to clone a repository
Please follow the [instructions here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) to install git on your operating system.

For the following instructions, for mac/linux users please open a terminal window and for windows users please use the Git Bash application that you have installed.

Now we want to use git to clone the repository we created earlier and finish this lab. We can do so by first telling git who we are:

```
git config --global user.email "[your email]"
git config --global user.name "[your github username]"
```

And then lets take the time to set other time saving configurations:
```
git config --global core.editor pico 
git config --global credential.helper "cache --timeout=3600"
```

The first line sets the editor that you'll be editing git commits to pico, a much simpler terminal text editor than the default vim. The second line will save your credentials for a limited time so that you will not have to enter it over and over again.

You should have gotten an email with a link to create your own repository dedicated to this lab. It should be from "GitHub Classroom". Please click on that link and have your repository for this lab created.

Next lets clone this repository. You need to log into your GitHub account, navigate to the repository that , and then find the green "Clone and Download" button. Copy that url that it shows you.

Now you can run the command:

```
git clone [url]
```

Where [url] is the url that you copied from the GitHub web page. It may ask you for your username and password, and then it should download the repository!

## Commit and push changes to your repository to submit your homework

Now that you have your repository set, you can now: 
 - make changes to these files
 - ```git add [files]``` them to the staging location
 - ```git commit``` them to your repository
 - ```git push origin master``` those changes to your remote repository


## Homework Assignment
For the homework assignment, I would like for you to create a file in this repository called "browsers.txt" right next to the "README.MD" file and in the text file answer the following questions:

 - What is your experience with web architecture. Have you written HTML before? Written JavaScript? etc.
 - What are your favorite features from at least 2 browsers?

You can use Sublime Text to edit files, which can be found by going to the Windows like button and going to Programming -> Sublime Text. You can also type "subl" on the command line. 

Be sure to push your changes to the remote repository. You'll know that you've done it if you can see your changes on the GitHub page.

Once you push those files to your repository you are done!
