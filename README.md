# LearnGit
To understand how Git versioning works.
This repository will attempt to perform basic operations of Git on the Git Bash command line.
## Never store API credentials/ Passwords/ Credit card info etc. on git files as the repository is public.
.md = Markdown file

GitHub is a code hosting platform for version control and collaboration.

Basic git commands

$ mkdir Websites

$ cd Websites/

$ git clone 'url' folder_name

$ git status

###### create/edit files locally

$ git diff file_name

$ git add file_name

$ git commit -m "message while committing"

$ git push origin main

$ git log
$ git log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'

$ git checkout hash_id_from_log   ##### oints the header to a desired commit

$ git checkout -B subBranch  ####to create new branch

$ git branch   ###### lists the branches and green for current branch

$ git branch name_of_branch  ###### to create new branch

$ git checkout name_of_branch  ###### to switch to existing branch


# These changes are done in the sub Branch.
