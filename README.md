# howtogit
This is a repo where i learn how to use github.
 * first we create and/or edit a file (say, `TODOs`) 
 * `git add TODOs` (can add more than one file)
 * `git commit -m "added a TODOs list and initated it with a first TODO message"`
 * `git push` (this sends the changes to the repo)
* `git pull`: get latest version of current branch (see bellow for branches!)
 * `git checkout <some_branch`: select branch (see bellow for branches!)

## 2.6 Github Project example
1. Create a new project
2. Add a new task and convert it to "issue"
3. Select issue to work on and drag it to "ongoing"
4. Open the issue and "create a new branch"
5. `git fetch` locally to get list of branches
6. `git checkout <name_of_the_branch_i_created>` locally to "enable" the selected branch
7. work locally to do the required changes on the code of the selected branch and repeat the aforementioned procedure (git add, git commit, git push ON THE BRANCH). 
8. as soon as i am sure the work is done --> pull request on github page (also mentions coworkers to do the QA. Also drag the issue from Ongoing to QA in the project view)
9. The person(s) that have been tagged to QA, checkout (git-checkout) the branch locally, they test it, and as soon as they are sure the code works without any bugs or new issues, they merge to master (through the github page). After this, automatically: the issue is deleted and the task is moved to "Done" in the project view

Summary of steps for a single task/issue:
task / issue --> branch --> work on branch locally --> push changes to branch and P(ull) R(equest) when ready --> the person(s) that do the QA do the final merging of the branch to master
