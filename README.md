# Exercise 1

Submitted by YOUR_NAME.

This assignment is due by 11:59PM ET 9/7.

## Send a photo and bio

- [ ] You will be added to the [list of IBRAiN students](https://birc.uconn.edu/ibrain-team/). Please send a photo and short description of your research interests to me by email.

## Create accounts

- [ ] Create an account on [GitHub](http://github.com)
- [ ] Neuroimaging analysis takes lots of computing time. You’ll want to run some of your analysis on the UConn Storrs HPC cluster, for which you’ll need to [request an account](http://hpc.uconn.edu/storrs/account-application). You can find your advisor’s NetID at [http://phonebook.uconn.edu](http://phonebook.uconn.edu).
- [ ] Once you get your account, make sure you can SSH to the cluster as described [here](https://wiki.hpc.uconn.edu/index.php/HPC_Getting_Started)
- [ ] On the cluster, create your own scratch directory `/scratch/netid`, where `netid` should be replaced by your own netid.

## Learn Bash
- [ ] Work through the 4 free modules of [Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line) on Codeacademy. Don't just copy and paste commands in the lessons—type them out.

## Learn Git
- [ ] Work through the 4 free modules of [Learn Git](https://www.codecademy.com/learn/learn-git) on Codeacademy.

Once you have completed the course, 

1. [Fork](https://help.github.com/articles/fork-a-repo/) the [HW 1 repository](https://github.com/bircibrain/f19-hw1) from the GitHub page.
2. Clone the repository to your computer using `git` so that you have your own copy to edit and submit.

## Install required software

Please download and install the following *required* software:

- [ ] For MRI analysis: [FSL](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslInstallation) (big download!). Make sure that you can successfully run the commands `fsl` and `fsleyes` from the command line.
- [ ] Running containers: [Docker](https://hub.docker.com/editions/community/docker-ce-desktop-mac)


## Install optional software

You are also encouraged to download and install the following *optional* software or have an alternative that you are comfortable with.

- [ ] A code editor with syntax highlighting for shell and python is required. **Do not write code in a word processing application** as these applications tend to insert special characters and markup that will cause errors in your code. Any code editor is fine, but some good options are
	-  [Sublime Text](https://www.sublimetext.com)
	-  [Visual Studio Code](https://code.visualstudio.com) (part of the UConn software image) 
- [ ] Your homework assignments will be submitted using git. A graphical git client such as [GitKraken](https://www.gitkraken.com/download) can make this easier.
- [ ] A [Slack](https://slack.com) client. You are required to check Slack on a regular basis while in the IBRAiN program, but you can use the web version if you like.
- [ ] Your homework assignments will often be submitted as [Markdown](https://www.markdownguide.org) documents. A dedicated Markdown editor such as [MacDown](https://macdown.uranusjr.com) can make this easier by showing you how the document will be formatted as you write it. 


FYI only, many of my slide decks are written in Markdown and presented using the $29 [Deckset](https://www.deckset.com) app. I find this to be a really easy way to make a basic slide deck, especially when I need to include code or equations.

## Edit this file

1. [Fork](https://help.github.com/articles/fork-a-repo/) the [HW 1 repository](https://github.com/bircibrain/f19-hw1) from the GitHub page.
2. Clone the repository to your computer using `git` so that you have your own copy to edit and submit.

### Add your name

Replace the string `YOUR_NAME` at the beginning of this document with your first and last name. Since you're an IBRAIN student and Bash expert, we'll do this the easy way:

- [ ] Use `cat` piped through `sed` to change `YOUR_NAME` to your name. Note that you should redirect the output of `sed` to a temporary file (such as that given by `mktemp`) and then replace `README.md` with the temporary file using `mv`.
- [ ] Add the command(s) you used as a code block below. Make sure you use ```` ``` ```` to display your code in the Markdown file.


### Check off the steps you completed

This file (`README.md`) is written in [Markdown](https://www.markdownguide.org). GitHub will automatically show any file named `README.md` as a webpage when viewed on Github.com using [Github-flavored Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

When you see this online, you should see that the steps you need to complete have empty checkboxes like this:

- [ ]

In Markdown, a checkbox is a special list element written as:

```markdown
- [ ] Todo Item 1
- [ ] Todo Item 2

```

To tick the checkbox, write an `x` between the brackets, like this:

```markdown
- [x] Todo Item 1
- [x] Todo Item 2

```

which appears like so:

- [x] Todo Item 1
- [x] Todo Item 2

Tick the boxes for all the steps you have completed.

### Describe any installation issues

Sometimes installation instructions can be a bit vague. Use Markdown to add a bulleted list of any problems you encountered and how you solved them here:


## Submit the assignment

1. Using git, `commit` your changes to this file (remember to `git add` your files first). 
1. Using git, `push` your code to your forked repository.
1. On GitHub, [create a pull request](https://help.github.com/articles/creating-a-pull-request/) to submit your work.
