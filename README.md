# -mle-training
Assignment 2

In the previous assignment, you have learned about Git and GitHub and some hands-on experience using the tools. In this assignment, you will create a GitHub repository and practice a collaborative workflow with your facilitator. If you are not sure of something, refer to the GIT reference you used in the previous assignment.

Go over the content in Tiger coding guidelines. This should be a good reference for your projects in general on coding standards and guidelines.

Read carefully the sections on Git practices and code-review guidelines and then try to finish up the following exercises.

Exercises

Ensure you have SSH access to Tiger GitHub. This  allows you to work without having to type in your username/password constantly.


Create a private repository named mle-training with an empty README.


Create a GitHub issue for the current assignment and add in the details based on what is requested in this assignment and assign it to yourself. Note the issue-id. 


Create a new branch (enh/<issue-id>/<short-msg>) and copy the code-snippet here and commit as-is including the README. Use appropriate commit messages as per the guidelines.


Add a .gitignore file to the repository to avoid committing unnecessary files like pyc files and the CSV data files in your current folder.  

Use Conda to set up a python development environment named mle-dev to run the script. Export the environments file as env.yml and commit it to the repository.

Update the README file with instructions on how to run the code.


Create a Pull Request (PR). Make sure the PR follows the expected standards. Link the PR to the GitHub issue to ensure the issue is closed automatically when the PR is merged.


Add the facilitators for your session as collaborators on the mle-training repository and request a PR.


Once the PR is approved, merge the PR to master branch and give it a tag (named version) `v0.1` and push that to the remote.


Deliverable


Submit the URL of the GitHub PR. Ensure that the submitted code in the PR works as advertised in the README.



Checklist - Assignment 1.2:
Create Repositories and branch names only as specified in your assignment. Follow the instructions carefully. 
Env.yml should be generated after successfully running the nonstandardcode.py in the mle-dev environment. This ensures that the env.yml file is complete and does not miss out on some dependencies. 
Always remove the “prefix” from your env.yml file since that is system specific.
The nonstandardcode.py might throw some errors while trying to run. You will need to fix the issues with the script so that it runs successfully.
Mention the following points in your README.md
Project Description
Command to create an environment from the env.yml file you have generated. This ensures reproducibility of the exact same environment that you have created.
Command to activate the environment
Command to run the python script.
While specifying any command use syntax highlighting in markdown files.
Please attach a screenshot of the output from running the nonstandardcode.py successfully in the mle-dev environment as a part of your PR description. An example is attached below,




If your reviewer has requested changes in your branch after reviewing your PR, after making the changes please re-request a review from your reviewer so that your reviewer is notified about the changes and they can review again.
For anything publicly available please use google :D 

For assignments 1.3, 1.4 and 1.5 the instructions mentioned in the assignment are good enough. 

