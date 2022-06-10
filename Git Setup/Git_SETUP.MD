
## Introduction
Git is a very popular version control system. You’ll become very familiar with this piece of software throughout TOP, so don’t worry too much about understanding it at this point. There are many lessons focused on Git later in the curriculum.

GitHub is a service that allows you to upload your code using Git and to manage your code with a nice web interface. GitHub and Git are not the same thing or even the same company.

<hr>

## SetUp Git

For Git to work properly, we need to let it know who we are so that it can link a local Git user (you) to GitHub. When working on a team, this allows people to see what you have committed and who committed each line of code.

The commands below will configure Git. Be sure to enter your own information inside the quotes (but include the quotation marks)!

```
1. git config --global user.name "Your Name"
2. git config --global user.email "yourname@example.com"
```
GitHub recently changed the default branch on new repositories from master to main. Change the default branch for Git using this command:

```
git config --global init.defaultBranch main
```

To enable colorful output with git, type

```
git config --global color.ui auto
```

To verify that things are working properly, enter these commands and verify whether the output matches your name and email address.

```
1. git config --get user.name
2. git config --get user.email
```

<hr>

