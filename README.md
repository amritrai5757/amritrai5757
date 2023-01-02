Steps to contribute to a project 🤷‍♂️🤷‍♂️🤷‍♂️🤷‍♂️🤷‍♂️:-

Commit changes in a branch Codespace -> Push to branch in Personal repo -> Make pull request to brach in Company repo

1. FORK the whole company repo to your own github.
2. Create a Codespace for that BRANCH you have to work on in your own github ac or clone repo locally.
3. While local development, U need to install "Docker desktop" in laptop for opening the project in a container.
4. Install "dev conatiner"(in online codespace prebuild, no need to install dev container) to "Clone repository in container volume" -> select "BRANCH"-> "Environment like nodejs" if no docker file already defined.[Codespaces is same like local docker] [Never clone the repo locally & also in codespace u cant do that so its best to not clone it👍👍][Open docker desktop app before opeing vscode]
Note: U need to select a devcontainer to start local devlopment in container 
6. COMMIT to that branch to save code/changes in codespace along with timestamp & message
7. PUSH the commits/Code from codespace to that brach in ur own repo.
8. SYNC FORK/FETCH to update to yr brach in repo with new changes made on company repo's brach by others. -> FETCH that changes from local repo to yr codespace
9. NOTE: While SYNC FORK ,if changes made on file in company repo & changes made on file by you is same file then CONFLICT will occur & u need to resolve it. 
10. Make a PULL REQUEST/Contribute to that brach in company repo to MERGE your code in their repo.

NOTE: Fork copies whole repo with all braches.
      In local vscode directlly use pull(equals fetch->merge), because fetch just tells there is change local github website.

NOTE: In vscode desktop : 
1. Install git then connect ur local computer to github ac by typing this in the terminal : 
2. 1.git config --global user.name "amritrai5757" 
3. 2.git config --global user.email "amritrai5757@gmail.com"
Commiting saves code with timestamp in offline,local desktop file just like in online code saved in codespace by commiting. 

Install all other dependencies inside the project locally.

Install docker to  make copy the environment in devcontainer.

You dont need to install anything to open a repo having devcontainer. Just open in codespace it will automatically setup all environment written in devcontainer.

Note: If company repo is showing in your "Top repo", it doesnt mean u need to directlly work on it. It only means you have either opened a issue,commented or pull reequest.

How to reverse the commits 😎:-
After reset commit command do "git push --force" to push it. It deletes all commit history after a selected commit.
After revert commit command creates an new commit to nullify a commit.
Note:Deleting a individual commit requires revert or rebasing.Dont do that, it is not the way developers reverse commits. Never use rebase command while working on an organinzation projects. It is used for changing commit from one branch to another or something like this.

Note : You can revert a single commit but if no conflict occurs. If there is another commit in new line in same file & u want to revert previous commit, conflict will occur. So dont do it
