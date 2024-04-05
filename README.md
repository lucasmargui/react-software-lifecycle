

# Software Lifecyle

## Separate Environments

### Code Merge

Merging code in Git is a common operation used to combine changes from different branches. Here's a basic outline of how to merge code using Git:
  <details>
  <summary>Click to show content</summary>
    
<br>
    
1.	Fork the Repository: If you haven't already, fork the repository you want to contribute to. This creates a copy of the repository under your GitHub account.

![image](https://github.com/lucasmargui/React_Software_Lifecycle/assets/157809964/b2abe3ca-21eb-4530-8b25-fc27b6db2432)

------------------------------------
<br>
2.	Clone Your Fork: Clone your forked repository to your local machine using the git clone command. Replace <repository-url> with the URL of your fork:

```
git clone <repository-url>
```
------------------------------------
<br>
3.	Add Remote Upstream: Add the original repository as a remote named "upstream" to keep your local copy synced with the original project. This step is optional but highly recommended:

```
git remote add upstream <original-repository-url>
```
------------------------------------
<br>
4.	Create a New Branch: Create a new branch to work on your changes. The branch name should be descriptive of the changes you're making:

```
git checkout -b feature-branch
```
------------------------------------
<br>
5.	Make Changes: Make your desired changes to the codebase. You can use your favorite text editor or an integrated development environment (IDE).

------------------------------------
<br>
6.	Stage Changes: Once you've made your changes, stage them for commit:

```
git add .
```
Replace . with specific files if you only want to stage certain files.
------------------------------------
<br>
7.	Commit Changes: Commit your changes with a descriptive commit message:


```
git commit -m "Brief description of changes" 
```
- feat: (new feature for the user, not a new feature for build script)
- fix: (bug fix for the user, not a fix to a build script)
- docs: (changes to the documentation)
- style: (formatting, missing semi colons, etc; no production code change)
- refactor: (refactoring production code, eg. renaming a variable)
- test: (adding missing tests, refactoring tests; no production code change)
- chore: (updating grunt tasks etc; no production code change)


------------------------------------
<br>
8.	Push Changes to Your Fork: Push your changes to your forked repository on GitHub:

```
git push origin feature-branch
``` 
------------------------------------
<br>
9.	Create Pull Request: Visit your forked repository on GitHub, and you should see a prompt to create a pull request for the branch you just pushed. Click on it, and GitHub will guide you through the process of creating a pull request.

------------------------------------
<br>
10.	Describe Your Changes: Give your pull request a descriptive title and description. Explain what changes you've made and why they're necessary.

------------------------------------
<br>
11.	Submit Pull Request: Once you've filled out the pull request form, submit your pull request. It will be reviewed by the maintainers of the original repository.

------------------------------------
<br>
12.	Respond to Feedback: If the maintainers request changes or have feedback, make the necessary adjustments to your code locally, commit the changes, and push them to your fork. The pull request will be updated automatically.

------------------------------------
<br>
13.	Merge Pull Request: Once your pull request is approved, a project maintainer will merge your changes into the main branch of the original repository.

------------------------------------
<br>
14.	Sync Your Fork: Periodically, sync your fork with the original repository to ensure your local copy is up to date. You can do this by fetching changes from the upstream repository and merging them into your local branch.

 </details>

### GitLab CI/CD

CI/CD is a continuous method of software development, where you continuously build, test, deploy, and monitor iterative code changes.

  <details>
  <summary>Click to show content</summary>

#### Import project github to gitlab

![image](https://github.com/lucasmargui/React_Software_Lifecycle/assets/157809964/27c9fbdf-0079-4e10-9f9d-fc1e289c27a6)


#### Create a .gitlab-ci.yml file

![image](https://github.com/lucasmargui/React_Software_Lifecycle/assets/157809964/1068e24b-5824-4b17-9f55-f29e4d1dcfb4)


#### Status of your pipeline and jobs 

![image](https://github.com/lucasmargui/React_Software_Lifecycle/assets/157809964/72873793-cb84-40b0-a252-d58399bff2d1)

![image](https://github.com/lucasmargui/React_Software_Lifecycle/assets/157809964/482f22f6-0e51-4183-a145-2c3c0867c619)

![image](https://github.com/lucasmargui/React_Software_Lifecycle/assets/157809964/7653af73-69eb-42bf-b186-b5c98ae68f0b)


</details>

## Docker


  


