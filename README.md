ICS 325-01 Spring 2019 - Assignment 4
=================

Purpose
-------
* Learn how to use github.com and GitKraken.

Collaboration
-------------
You can talk about the assignment with your peers in the class.  However, you should perform the work yourself and turn in a copy of your own work.

Prerequisites
-------------
You need to [sign up for a github.com account](https://github.com/join) if you don't already have one.  Your github.com account doesn't need to use your @metrostate.edu e-mail address.

You need to install [GitKraken](https://www.gitkraken.com/download), and log into it with your github.com account.

Use git to clone your private assignment 4 repo to your computer.  Then in PhpStorm, use `File->Open Directory` and select your local repo.

As before, you will be using the web server built into PHP.  See the instructions below for how to set that up.

Resources and Examples
----------------------
See the D2L assignment for a link to the notes explaining how the code given to you in this repository works.

Instructions
------------
#### Instructions to set up the code to run
First you need to clone your git repository to your computer.  Open GitKraken and make sure you are logged into your github.com account.  Next go to `File->Clone Repo`.  Select the `GitHub.com` icon.  A list of your repositories in github.com should pop up.  Select the one for assignment 4.  If you want, change `Where to clone to` by clicking browser and selecting a folder for your git repo to be cloned into.  Finally, hit the `Clone the repo!` button.  Your repo should now clone to your computer.

Next you need to set up PhpStorm.  We will be using the built-in PHP CGI server for this assignment.  To do so, first make sure you have the git repo open in PhpStorm by using the Open Directory menu item under File in PhpStorm (`File->Open Directory`).  Next go to `Run->Edit Configurations...` Click the green `+` to create a new configuration.  Select `PHP Built-in Web Server`.  Change the name to `Assignment 4`.  Leave host as `localhost`.  Set the port to `8080`.  Set the `Document root` to your git repo directory by clicking the `...` button next to the field and using the file chooser to select it.  If there is a red ! icon near the bottom right of the window, click the `Fix` button and specify your PHP interpreter.  Once done, click `Ok` to exit the Edit Configurations window.  Next hit the green run button to start the PHP CGI web server.  Then go to your web browser and enter this url [http://localhost:8080/hello.php](http://localhost:8080/hello.php).  You should see the text "Hello world!".

#### Assignment Instructions
1. Modify hello.php and add the text "Goodbye world!" below "Hello world!".  Stage your change, commit your change, and push your commit to master.  Remember, you MUST push your commit in order for the changes you make to show up on github.com.  You should check your repository on github.com as you work through these instructions.

2. Add a new file test.php.  Have it output the text: "Hello again!".  Stage the file, commit it, and push your commit to master.

3. Create and checkout a new branch named feature-Test-1.  Create a new file named feature-test-1.txt.  Have it output "This is feature test 1.".  Stage your change, commit your change, and push your commit to the branch feature-Test-1.

4. Create and checkout a new branch named feature-Test-2.  Create a new file named feature-test-2.txt.  Have it output "This is feature test 2.".  Stage your change, commit your change, and push your commit to the branch feature-Test-2.

5. Checkout the master branch.  Merge the feature-Test-1 branch into master.  Push your commit to master.

6. Go to your repo on github.com and confirm that all your commits have been pushed to the remote origin repo hosted on github.com.  If you don't see any changes, then I won't be able to grade them either!

#### How to Turn in Assignment 4
Once you are done with all the required steps, go to D2L and turn in the assignment to let me know I can go look at your repo and grade you.  D2L requires you to upload a file, so place a link to your git repo in a text file and upload it to D2L.  You can also put the link in the assignment comments and upload an empty file to D2L.  Either way is fine, but having the link makes it much easier for me to find your repo and grade it quickly.

Grading
-------
Points|Requirement
------|-----------
2 | Step 1
2 | Step 2
2 | Step 3
2 | Step 4
2 | Step 5
**10**|**Total**
