# "Git Notes"

---

### Command and Description

✅ [Check out my YouTube Channel with hundreds of tutorials](https://www.youtube.com/DaveGrayTeachesCode).

- How to unstage an "add": git restore [filename]
- How to uncommit an "add": git restore --staged [filename]
- How to rename your last commit: git commit -v --amend
- How to view a log of commits: git log --oneline
- How to create a new branch: git branch [newBranchName]
- How to switch to a branch: git checkout [branchName]
- How to do both at once: git checkout -b [newBranchName]
- How to rename a branch: git branch -m [oldBranchName] [newBranchName]
- How to go to a previous commit: git checkout [commitIdNumber]
- How to revert to a previous commit: git revert [commitIdNumber]
- How to revert to a previous commit and unstage the work that you completed afterwards: git reset [commitIdNumber]
- git reset [commitIdNumber] --hard (this one deletes permanently!)

---