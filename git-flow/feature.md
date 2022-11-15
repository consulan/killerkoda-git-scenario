# Step Two - Work with feature branch

>In this step, we was work with the feature branch.
>This branch is only for new features, like new functionalities and not minor changes.

## Objective

> *Work with features branch in new files*

### Init feature with git flow

> ` git flow start DEV-1234 `{{exec}}

### Create a new file

* Create a blank file with touch tool

> ` touch NEWFILE.md `{{exec}}

* Insert the Mermaid code into NEWFILE.md and save

````mermaid
 ```mermaid
 graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
````

* Add to stage area the file

` git add NEWFILE.md `{{exec}}

* Commit the changes

> ` git commit -m 'feature(DEV-1234): ' `{{exec}}

* Publish the feature

> ` git flow feature publish DEV-1234 `{{exec}}

* Finish the feature branch

> ` git flow feature finish DEV-1234 `

* Other options are:

> git flow feature pull origin *FEATURE* or git flow feature track *FEATURE*
