# Step One - Create global user git

>In this step, we clone a remote repo for work with them.
>In the last step we init a repo. For this cause, we erase the .git directory.
>And then we clone the remote directory from bitbucket (public).
>In the next item we remove the created directory from clone repo, and make a new directory for push the content to remote repo.

## Objective

> *Clone a remote repo.Make modifications.Stage with git the work. Commit changes. Push the work to remote repo*

## Use git commands for clone a public repo

---

### Commands for clone

* Delete .git directory

> ` rm -fr .git/ `{{exec}}

* Clone the remote directory

> ` git clone git@github.com:consulan/killercoda-test-gitclone.git `{{exec}}

---

## Modify and then push your commits

### Modify the README.md

* Go to the directory

> ` cd killercoda-test-gitclone `{{exec}}

* Open with vi editor the README.md

> ` vi README.md `{{exec}}

* Insert one or two lines
* Enter to command mode in vi pressing ESC, and then wq!
* Add the file change to staging area

> ` git add README.md `{{exec}}

* Commit the changes to preserve

> ` git commit -m 'course(auto): lines in course' `{{exec}}

* Push to remote repo

> ` git push `{{exec}}

---
