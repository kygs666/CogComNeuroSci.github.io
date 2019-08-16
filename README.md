
# Verguts lab - website

[![online](https://img.shields.io/website/https/cogcomneurosci.github.io?down_color=red&down_message=offline&up_color=green&up_message=online)](https://img.shields.io/website/https/cogcomneurosci.github.io?down_color=red&down_message=offline&up_color=green&up_message=online)
[![commits](https://img.shields.io/github/last-commit/CogComNeuroSci/CogComNeuroSci.github.io)](https://img.shields.io/github/last-commit/CogComNeuroSci/CogComNeuroSci.github.io)
[![issues](https://img.shields.io/github/issues/CogComNeuroSci/CogComNeuroSci.github.io)](https://img.shields.io/github/issues/CogComNeuroSci/CogComNeuroSci.github.io)

## What is this GitHub page about?   

This GitHub page represents the code to keep the [Verguts lab website](https://cogcomneurosci.github.io/) online.
Mind that _everyone_ (in the CCNS organization) is able to contribute to this page.   

How?   
This is explained immediately below.

## Contributing to our website

Sometimes you want to help out, but you don't know where to start.   
Therefore, I wrote this small tutorial to make sure that you are able to suggest edits while at the same time preventing the site from breaking/crashing.

### Working on your own copy of the website

--- 

**Disclaimer   
We encourage you to edit the website through your own personal fork, as this reduces the chances that something weird happens to the website. Committing changes from forks protects the master branch by checking compatibility first, while at the same time blocking force pushes (i.e. edits that are not reviewed and immediately alter the master branch).**

---

#### Click and play

This guide is for people who prefer working on the GitHub main page.   
You don't have to download GitHub Desktop or Git to follow this guide.

- Go to the [master branch](https://github.com/CogComNeuroSci/CogComNeuroSci.github.io) of our website
- Click on **Fork** in the upper right corner
- Select your own profile (in my case, that would be _phuycke_)
- Go to your newly made fork of the root directory on your own profile
    - i.e. go to your own GitHub page and open "CogComNeuroSci.github.io"
- Alter your "Who's who"-section (see below for specific guide)
    - On your personal copy (i.e. the fork) of the master page, go the the /about folder
    - Click on __index.md__
    - Click on the __pencil__ symbol
    - Scroll towards your part
    - Make changes to your description
        - For aid on how to do this, look at already filled in examples (Tom, Kate, Pieter H and Fabrice)
    - Refer to your photo by writing 'profile_pic_(your name).jpg' in the ```HTML``` code snippet
- Press **commit** on the bottom of the page to confirm the changes
    - Give a descriptive name to your changes, comments are optional
- Upload your profice picture
    - Go the /images folder
    - Upload your photo (press __upload__)
    - __Make sure that it is named profile_pic_(your name).jpg__
        - Examples can again be found in the /images folder
    - Refresh your /images folder to see that the upload worked
- Press **pull request** in the main page of your personal fork
- Press **create new pull request**
- Press **create new pull request**
- Write a message and comments to clarify what you changed
- Assign a **reviewer** to your pull request (right column)
- **Create pull request**
- You did it! :heart_eyes:

---
#### GitHub Desktop

No information available.

- No information available.
    - See [this issue](https://github.com/CogComNeuroSci/CogComNeuroSci.github.io/issues/10) if you are interested in helping us out!
---

#### Git for the first time

This tutorial is for users that aim to use [Git Bash](https://git-scm.com/).
Note that this tutorial allows you to work:
- On the master branch
- On your own personal fork

Actual tutorial:
- Install Git and [make sure that it works properly](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
- Go to a folder on your local computer where you want to store the code from the GitHub repository
- Open Git Bash in this directory
    - Right mouse click > open Git Bash
    - A command window will appear
- Type ```git clone git@github.com:CogComNeuroSci/CogComNeuroSci.github.io.git``` in the command window
    - A folder called 'CogComNeuroSci.github.io' will appear in your local folder
- Go inside this new directory
- Make some changes
- When all changes are done, type ```git add --all``` in the Git Bash console
- Type ```git commit -m "your message"``` in the Git Bash console
- type ```git push origin master``` in the Git Bash console
- You did it! :heart_eyes:

#### Note

If you suspect that changes have occured in the root folder since you started editing your local folder, do the following **before pushing your changes to the root directory**. **Pushing your edits from a branch that was not updated before will lead to data loss, or worse: conflict**.

- Go to the folder where the website code is stored and open Git Bash over there
- Type ```git fetch```
- Type ```git pull```
    - This makes sure that 'upstream' edits are synchronized with your local folder first
    - By doing so, you start from the most updated code
- ```git add --all```
- ```git commit -m "your message"```
- ```git push origin master```


```python

```
