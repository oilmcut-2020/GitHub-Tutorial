# GitHub-Tutorial
 
**Managed by- Shivani Baldwa

Email: baldwashivani@gmail.com**

This is for beginner to know what is Git, GitHub, and how to use GitHub.

## Setting Up GitHub Account
Setting your GitHub account is easy and very simple. To set the account visit GitHub’s official website.
The login form will appear on the same page. Fill out the form with your details to create an account on GitHub.
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/git1.png">
</p>

**Note** :GitHub will warn you if there are any duplicate entries i.e. if that username is already taken by some other individual
or not etc. Along with the error, GitHub will suggest you the available attributes also. For example, your username could be duplicate because whatever you are thinking as your username, might have been
already taken by someone else. 
In GitHub, you will be known by your username. So, it has to be unique. 

Once you press Sign up for GitHub button, you will be prompted to verify that you are not a robot.
Verify Account: "mail which is sent by github to your mail-id".

### Sign in again to check :
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/git2.png">
</p>

### Choosing a GitHub Account Plan
Once you have verified your identity, you can choose the GitHub plan you want to subscribe for.
For this tutorial and in general as a beginner, GitHub Free plan is more than enough.
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/git3.png">
</p>

### GitHub Account Dashboard
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/dashboard.png">
</p>

- GitHub Repositories
- GitHub Feed
- GitHub Discover Repositories

These are briefed in the below section but these will be discussed in detail in the upcoming tutorials.
- GitHub Repositories:
GitHub repositories section will contain all the repositories on which the user is working. For the ease, one can just toggle between these repositories and start working on them again.
- GitHub Feed:
GitHub feed contains an individual’s feed like other social networks. You can see the recent activities on your repositories and the activities of the people you follow. This feed will contain all private and public repositories activities. Private repositories may include the repositories on which the organization is working or created by the user himself.
- GitHub Discover Repositories:
This section is newly introduced by GitHub on the dashboard. In this section, a person will be able to see some repositories which match his interests. If you are not working on any repository, you can always explore the repositories through this section and build your reputation on GitHub.

## Introduction to GitHub

GitHub is a file or code sharing service to collaborate with different people.GitHub is a highly used software which is typically used for version control. It is helpful when more than just one person is working on a project. Github helps them to build a centralized repository where everyone can upload, edit and manage the code files.
GitHub is a central repository and Git is a tool which allows you to create a local repository. Now people usually get confused between git and GitHub but its actually very different. Git is a version control tool that will allow you to perform all kinds of operations to fetch data from the central server or push data to it whereas GitHub is a core hosting platform for version control collaboration. GitHub is a company that allows you to host a central repository in a remote server. 
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/git.png">
</p>

## STEP 1: Creating a GitHub Repository
A repository is a storage space where your project lives. It can be local to a folder on your computer, or it can be a storage space on GitHub  or another online host. You can keep code files, text files, images or any kind of a file in a repository. You need a GitHub repository when you have done some changes and are ready to be uploaded. This GitHub repository acts as your remote repository. So let me make your task easy, just follow these simple steps to create a GitHub repository: 

- Go to the link: https://github.com/ . Fill the sign up form and click on “Sign up for Github” 
- Click on “Start a new project”.

Refer to the below screenshot to get a better understanding.
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/git5.png">
</p>

Enter any repository name and click on “Create Repository”. You can also give a description to your repository (optional).
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/newrepo.png">
</p>
Now, if you noticed by default a GitHub repository is public which means that anyone can view the contents of this repository whereas in a private repository, you can choose who can view the content. Also, private repository is a paid version. Also, if you refer the above screenshot, initialize the repository with a README file. This file contains the description of the file and once you check this box, this will be the first file inside your repository.
Congratulations, your repository is successfully created! It will look like the below screenshot:
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/git6.png">
</p>

## STEP 2:Create Branches

**Branching:** Branches help you to work on different versions of a repository at one time. If you want to add a new feature nd you are afraid at the same time whether to make changes to your main project or not. This is where git branching comes to rescue. Branches allow you to move back and forth between the different states/versions of a project. 
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/readme-changes/images/masterbranch.png">
</p>

As depicted in the above image, there is a master/ production branch which has a new branch for testing. Under this branch, two set of changes are done and once it completed, it is merged back to the master branch.

To create a branch in GitHub, follow the below steps:

- Click on the dropdown “Branch: master”
- As soon as you click on the branch, you can find an existing branch or you can create a new one. In my case, I am creating a new branch with a name “readme-changes”. Refer to the below screenshot for better understanding.
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/readme-changes/images/newbranch.png">
</p>

Once you have created a new branch, you have two branches in your repository now i.e. read-me (master branch) and readme- changes. The new branch is just the copy of master branch. So let’s perform some changes in our new branch and make it look different from the master branch.

### How to use GitHub: Operations

#### Commit Command:

This operation helps you to save the changes in your file. When you commit a file, you should always provide the message.
These commit messages maintain the history of changes which in turn help other contributors to understand the file better. Now let’s make our first commit, follow the below steps:

- Click on “readme- changes” file which we have just created.
- Click on the “edit” or a pencil icon in the righmost corner of the file.
- Once you click on that, an editor will open where you can type in the changes or anything.  
- Write a commit message which identifies your changes.
- Click commit changes in the end. 
Refer to the below screenshot for better understanding:   
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/readme-changes/images/readme%20edit.png">
</p>  
  
 We have successfully made our first commit. Now this “readme- changes” file is different from the master branch. 
 
 #### Pull Command
 
Pull command is the most important command in GitHub. It tell the changes done in the file and request other contributors to view it as well as merge it with the master branch. Once the commit is done, anyone can pull the file and can start a discussion over it. Once its all done, you can merge the file. Pull command compares the changes which are done in the file and if there are any conflicts, you can manually resolve it.
Different steps involved to pull request in GitHub.

- Click the ‘Pull requests’ tab.
- Click ‘New pull request’.
- Once you click on pull request, select the branch and click ‘readme- changes’ file to view changes between the two files present in our repository.
- Click “Create pull request”.
- Enter any title, description to your changes and click on “Create pull request”. Refer to the below screenshots.
 <p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/pull-request.png">
</p>  

Next, let us move forward and see how can you merge your pull request.

#### Merge Command

Here comes the last command which merge the changes into the main master branch. We saw the changes in pink and green color, now let’s merge the “readme- changes” file with the master branch/ read-me. Go through the below steps to merge pull request.

- Click on “Merge pull request” to merge the changes into master branch.
- Click “Confirm merge”.
- You can delete the branch once all the changes have been incorporated and if there are no conflicts. Refer to the below screenshot.
 <p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/merge-pull.png">
</p>  

## STEP 3:Cloning and Forking GitHub Repository 
**Cloning:** Suppose you want to use some code which is present in a public repository, you can directly copy the contents by cloning or downloading.
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/clone.png">
</p>

Cloning is really simple!

**Forking:** Suppose, you need some code which is present in a public repository, under your repository and GitHub account. For this, we need to fork a repository. 
Before we get started with forking, there are some important points which you should always keep in mind.
- Changes done to the original repository will be reflected back to the forked repository.
- If you make a change in forked repository, it will not b reflected to the original repository until and unless you have made a pull request.

Now let’s see how can you want to fork a repository. For that, follow the below steps:
Go to Explore and search for public repositories.
Click “fork”. Note that this “librealsense-odometry” repository is already forked 2 times.
<p align="center">
  <img src="https://github.com/oilmcut-2020/GitHub-Tutorial/blob/master/images/fork.png">
</p>

As soon as you click on “Fork”, it will take some time to fork the repository. Once done you will notice that the repository name is under your account.

##### That's all for this tutorial, I hope you enjoyed it and got to understand "HOW TO USE GITHUB".
