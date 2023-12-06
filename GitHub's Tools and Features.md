# Getting familiar with Tools and Features <br />

To best use GitHub, you'll need to set up Git. Git is responsible for everything GitHub-related that happens locally on your computer. To effectively collaborate on GitHub, you'll install and set up Git. <br />

## Using Git
To use Git on the command line, you'll need to download, install, and configure Git on your computer. If you do not need to work with files locally, GitHub lets you complete many Git-related actions directly in the browser, including: <br />

* Creating a repository
* Forking a repository
* Managing Files
* Being social <br />

## Setting up Git 

1. [Download and install Git](https://git-scm.com/downloads) <br />
<br />**NOTE**: Most Chrome OS devices from 2020 onwards now have a built-in Linux environment, which includes Git. To enable it, go to the Launcher, search Linuex, and click **Turn On**. <br />
If you are using an older Chrome OS device, another method is reuqired: <br />
  a. Install a terminal emulator such as Termux from the Google Play Store on your Chrome OS device.
  b. From the ternminal emulator that you installed, install Git. For example, in Termux, enter `apt install git` and then type `y` when prompted.  <br />

  2. Setting up your Git username for **every** repository on your computer <br />
  Open Git Bash. <br />
  <br />Set a Git username: <br />
  `git config -- global user.name "Angel Sun"`<br />
 <br /> Confirm that you have set the Git username correctly: <br />
  `$ git config -- global user.name` <br />
    `> Angel Sun`
<br />
<br />
## Authenicating with GitHub and Git <br />
When you connect to a GitHub repository Git, you will need to authenticate with GitHub using either HTTPS or SSH. You can authenticate to GitHub using GitHub CLI, for either HTTP or SSH. <br />

## Learn about `gh auth login`

<br /> 
Authenicate with a GitHub host. <br />
The default authentication model is a web-based browser flow. After completetion, an authentication toke nwill be stored securely in the system credential store. If a credntial store is not found or there is an issue using it gh will fallback to writing the token to a plain text file. You can use `gh auth status` for its stored location. 

<br />

Next Steps
