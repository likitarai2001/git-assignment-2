# Git-Assignment 2

### Problem Definition

- Create a branch from the master branch and make changes and commit changes

- Create a new branch from the master.

- Create a pull request for the first branch and merge it to the master.

- Rebase the second branch with the master branch and make changes in the second branch and commit changes

### Steps

- Initialized git repository and added `README.md` to it
- Pushed the file to `master` branch
![Screenshot from 2023-02-16 13-52-04](https://user-images.githubusercontent.com/125335643/219331765-24cb6a3b-de84-4685-8ed4-1506c0f7a59e.png)
- Created new branch `likita` from `master`
- Added `demo.java` file to it and commited the changes
![branch likita first commit](images/Screenshot%20from%202023-02-16%2015-32-24.png)
- Created pull request for the changes from `likita` to `master`
![PR](images/Screenshot%20from%202023-02-16%2014-13-10.png)
![PR](images/Screenshot%20from%202023-02-16%2014-14-05.png)
![PR](images/Screenshot%20from%202023-02-16%2014-14-15.png)
- Merged the pull request in remote repository
![merge PR](images/Screenshot%20from%202023-02-16%2014-14-39.png)
![merge PR](images/Screenshot%20from%202023-02-16%2014-14-57.png)
![merge PR](images/Screenshot%20from%202023-02-16%2014-15-09.png)
- Created `feature` branch from `master`
- Checked commit history for each branch using the command `git log --oneline`
- Pulled the changes into `master` from remote repository and checked commit history
![check log](images/Screenshot%20from%202023-02-16%2015-47-14.png)
- Rebase `feature` branch
- First, checkout into `feature` then rebase it into master through `git rebase master`
- Finally, check commit history
![rebase feature branch](images/Screenshot%20from%202023-02-16%2015-48-07.png)
