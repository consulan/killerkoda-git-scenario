# Step One - Create a global email git

>In this step, we create a email configuration global in git.
>This email will be use in our commits.
>This are practical when we're seeking an author of any commits.  

## Use git commands for global configuration

---

### Commands for configure

* Global email command

> ` git config --global user.email "ouruser@ourmail.com" `{{exec}}

* Local and System configuration commands
Tareas

: Primero iniciamos el repositorio.
> ` git init `{{exec}}



> ` git config --local user.email "otheruser@othermail.com" `{{exec}}

<br>

> ` git config --system user.email "systemuser@alternatemail.com" `{{exec}}

* Global user command

> ` git config --global user.name "Jhoe Doe" `{{exec}}

* View configuracion

> ` git config --list `{{exec}}
