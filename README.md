# Workflow of how I did the assignment
## Repository Setup
1. I logged in to my GitHub account.
2. I clicked the "+" icon in the top-right corner and selected "New repository".
3. I named my repository "plp_git_assignment".
4. I checked the box that says "Initialize this repository with a README".
5. I finally clicked "Create repository".


## Final Steps
- First, I created a new directory named PLPBasicGitAssignment on my local machine.
   - $ mkdir PLPBasicGitAssignment
- Then, I navigated into the newly created directory.
  -   $ cd PLPBasicGitAssignment/
- Next, I initialized a new Git repository inside this directory.
   - $ git init
   - Initialized empty Git repository in C:/Users/Work/Desktop/PLP/PLP Assignments/Software Development/plp_git_assignment/PLPBasicGitAssignment/.git/
- After that, I added a remote named origin to point to a GitHub repository (https://github.com/Mr-Macharia/plp_git_assignment.git).
  - $ git remote add origin https://github.com/Mr-Macharia/plp_git_assignment.git
- Following this, I created a new file named hello.txt and added the text "Hello, Git!" to it.
  - $ echo "Hello, Git!" > hello.txt
- I then staged the changes to be committed.
  - $ git add .
- After staging, I committed the changes with a commit message.
  - $ git commit -m "Add a helo text with a greeting"
  - [master (root-commit) ba8ea28] Add a helo text with a greeting
  - 1 file changed, 1 insertion(+)
  - create mode 100644 hello.txt
- Initially, when I tried to push the changes to the remote repository, I encountered an error indicating that main branch does not exist. So, I corrected it by pushing to master branch and setting the upstream.
  -  $ git push --set-upstream origin master
  -  Enumerating objects: 3, done.
  -  Counting objects: 100% (3/3), done.
  -  Writing objects: 100% (3/3), 241 bytes | 241.00 KiB/s, done.
  -  Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
  -  To https://github.com/Mr-Macharia/plp_git_assignment.git
  -  * [new branch]      master -> master
     * branch 'master' set up to track 'origin/master'.
   
**Now, my local master branch is successfully linked to the remote master branch on GitHub, allowing me to push and pull changes seamlessly.**



