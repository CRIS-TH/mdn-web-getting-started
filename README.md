# MDN Getting Started with the Web Tutorial

We will create the files for a working website in this repository.

## Instructions

### Read
Study the documents in the "Getting Started with the Web" series.
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web

### Implement

#### Begin

Create a `dev` branch which we will use during development.

	# creates and checks out local `dev` branch
    git checkout -b dev

	# creates a remote `dev` branch and sets up remote tracking so that it may be pulled from later
	git push --set-upstream origin dev

#### Steps

Follow the tutorials to create your website files.
Commit your changes after each new feature or significant change.
* Add the files to git:  `git add <file>`
* Commit a snapshot  `git commit -m 'decription of change'`
* Routinely push for changes to GitHub: `git push`

1. Dealing with Files:
   https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files

2. HTML Basics:
   https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics

3. CSS Basics:
   https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics

4. JavaScript Basics:
   https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics

#### End

Merge your `dev` branch to `master` and push `master` to the origin repository.

    git checkout master
	git merge dev
	git push

## Turn In

There needs to be at least one commit for each step 1-4.

When step 4 is complete, your website should look and behave exactly like
[their live example](https://mdn.github.io/beginner-html-site-scripted/).
