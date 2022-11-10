# Step One - Create a global email git

>In this step, we create a email configuration global in git.
>This email will be use in our commits.
>This are practical when we're seeking an author of any commits.  

## Use git commands for global configuration

---

### Commands for configure

* Global email command

> ` git config --global user.email "ouruser@ourmail.com" `{{exec}}

* Local (need initiate repo) and System configuration commands

> ` git init `{{exec}}

* Local user

> ` git config --local user.email "otheruser@othermail.com" `{{exec}}

* System user

> ` git config --system user.email "systemuser@alternatemail.com" `{{exec}}

* Global user command

> ` git config --global user.name "Jhoe Doe" `{{exec}}

* View configuracion

> ` git config --list `{{exec}}

### Links to Internet sources

> Atlassian git config page [Link](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-config)

<br>

> Git official page [Link](https://git-scm.com/book/es/v2/Personalizaci%C3%B3n-de-Git-Configuraci%C3%B3n-de-Git)
