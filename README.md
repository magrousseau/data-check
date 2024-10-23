Welcome to Kitt! The teacher will now demonstrate how to work on an exercise.

## Update Python Packages on DataStudio

Before we start our first challenge, it's important to install and update the python packages that we are going to use during the course to ensure a smooth experience 😊

Open a terminal session on DataStudio:
![](https://wagon-public-datasets.s3.amazonaws.com/b2b_python_analytics/Air_Liquide_Variant/Lectures/Setup/pip1.png)

Copy the following commands, one line at a time, paste it onto the terminal session and hit `Enter`.

```bash
pip install --upgrade pip
```
```bash
pip install -r https://wagon-public-datasets.s3.amazonaws.com/b2b_python_analytics/Air_Liquide_Variant/datastudio_pipsetup.txt
```
The installation should take approximately 10-15 minutes depending on internet connections. You should see a similar output like the screenshot below when it finished:

![](https://wagon-public-datasets.s3.amazonaws.com/b2b_python_analytics/Air_Liquide_Variant/Lectures/Setup/pip3.png)

Please raise a ticket with a TA if you are unsure.

## What's this challenge about?

The goal is to implement a function called `circle_area`, which takes **one** parameter,
`radius`, and returns the area of the circle of the given radius. As a reminder,
here is the formula:

![](https://raw.githubusercontent.com/lewagon/fullstack-images/master/ruby/area-circle.png)

Open the `demo.py` file and implement it!

There are **3 tests** that you can run with the `make` command from the terminal. Make sure the tests are all green before moving to the next challenge!

## Pushing to Kitt

When `make` is 'happy' and all green, do not forget to push to GitHub!

Add the changed files to the staging area on Git tab:

![stage](https://wagon-public-datasets.s3.amazonaws.com/b2b_python_analytics/Air_Liquide_Variant/Lectures/Setup/12_git_add.png)

Commit your files with a message:

![commit](https://wagon-public-datasets.s3.amazonaws.com/b2b_python_analytics/Air_Liquide_Variant/Lectures/Setup/13_commit.png)

And push to your GitHub account!

![push](https://wagon-public-datasets.s3.amazonaws.com/b2b_python_analytics/Air_Liquide_Variant/Lectures/Setup/14_git_push.png)

Shortly after your push is completed, [GitHub will tell Kitt](https://sebastien.saunier.me/blog/2014/04/21/practical-example-of-using-git-in-a-school.html) about this push thanks to a [webhook](https://developer.github.com/webhooks/).

Kitt will then pull your code, run `make` and update your challenge status (completion + style score). You should also see how your buddy of the day is doing!
