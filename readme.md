#Readme

# open shell: tools > shell
# type in git hub info below
git config -- global user.name "Jennifer Selgrath"
git config -- global user.email "jselgrath@gmail.com"


# create project > new directory > ecoscope6   Check: create a git repository
# or add to a project: tools>version control>project setup>git

# user interface > git tab. 
#2 files: gitignore (has list of files to ignore)   Rproject file

# click staged tab to record changes. check files want to upload to git > commit (click)>commit message>commit (click)
# commit message: 1st line = summary; 2nd line = blank; lines 3-5 useful & informative details

# changes will appear in changes. Changes will appear on master branch.

############
# TERMS

# Responsitory: store of contents and history of all files in a project (stored in a hidden place)
# Commit: verb and a noun. 
# commit noun: a permanant snapshot of the state of the reponsitory, annoted with author, time, and comment. Linked with parent.
# staging: files marked to include in next commit

# whenever CLICK staged, THAT VERSION of the file will be committed EVEN if FUTURE CHANGES ARE MADE

# if delete things that are not committed, can right click and undo changes
# if commit changes that want to undo, need to switch to using command line interface or with a GUI 

# in shell: git revert
# SHA # is the name of the commit that want to convert (find in history list)
# creates a new commit that is the inverse of previous change

#################
# Branching and merging
# use branches to make changes not sure if want (experimenting without breaking working code)
# master = first branch in project
# tools>shell: git branch NAMEOFBRANCH
# then in user window can switch between master and new branch

