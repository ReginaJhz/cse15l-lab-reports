# LAB REPORT 1
this page will describe how to log into a course-specific account on ieng6 for CSE 15L

## Installing VScode
  First install java onto your computer if it is not installed yet. 
    Click on this [Link](https://www.oracle.com/java/technologies/downloads/#jdk18-mac) to redirect to java downloard website
  Then go to VScode's [Link](https://code.visualstudio.com/) to downloard the application.
  Click download on the blue download button on the top right corner of the webpage
  ![Image](StepOne.png)

 ## Remotely Connecting
  Once installed Java and VSCode on your computer you are all set to get connected the remote
  servers
  1. open a terminal in VSCode (Control or Command(depending on which operating system you arte using) or use the new terminal menu option)
  2. type in `ssh cs15lsp23zz@ieng6.ucsd.edu` (replace `zz` with the letters by the letters in your course specific account)
  3. then type in your password to connect to the remote server 
  4. if it is your first time connecting to the server thers' going to be the following code occuring on your sceen. If it is you operating type in `yes` and press enter
  ```
  #code
  The authenticity of host 'ieng6.ucsd.edu (128.54.70.238)' can't be established.
  RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
  This key is not known by any other names
  Are you sure you want to continue connecting (yes/no/[fingerprint])?
  ```
  5. after you press enter, retype your password and return enter again
  6. Connected!
  ![Image](StepTwo.png)
## Try Some Commands
  You could try out the following commands
  1. `cd ~`
  2. `ls`
  3. `ls <directory>`
  4. `mkdir`
  5. `pwd`
  6. `..`
  7. `exit` (to log out the remote serve or you could use Command/Ctrl-D)
  ![Image]()

//should include all steps you took along with screenshots of what eachstep look like
//have at least 3 screenshots, one for each of the steps below
// for each step write at least 2-3 sentences of bullet point desciring what you did

You will upload your submission by publishing the page on Github Pages, then printing the page to PDF and uploading to the Lab Report 1 assignment on Gradescope.

