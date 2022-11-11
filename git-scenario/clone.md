# Step One - Create global user git

>In this step, we clone a remote repo for work with them.
>In the last step we init a repo. For this cause, we erase .git directory.
>And then we clone remote directory from bitbucket (public).
>En next item we remove the created directory from clone repo, and make a new directory for push the content to remote repo.

## Use git commands for clone a public repo

---

### Commands for clone

* Delete .git directory

> ` rm -fr .git/ `{{exec}}

* Clone the remote directory

> ` git clone https://github.com/consulan/killercoda-test-gitclone.git `{{exec}}

---

## Requirements for next items

* An user created in github
* A public-private key generated (o follow the next items for this)
* Publish the public key into Github (teacher assistand or documentation)

## Modify and then push your commits

### Modify the README.md

* Go to the directory

> ` cd killercoda-test-gitclone `

* Open with vi editor the README.md

> ` vi  `
