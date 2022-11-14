# Step Three - Create a Diagram as Code

>In this step, we create a Diagram as Code (DaC) in README.md for document.

## Objective

> *Document with Mermaid metalanguage for DaC into a repo*

## Create a DaC with Mermaid language

---

### Edit README.md

* Open editor

> ` vi README.md `{{exec}}

* Insert the Mermaid code into README.md

````mermaid
 ```mermaid
 graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
````

* Close and save the file README.md pressing *ESC* and so *wq!*

* Add the modifies to staging

> ` git add . `{{exec}}

* Commit the changes

> ` git commit -m 'feat(docs): DaC' `{{exec}}

* Push to the remote repo

> ` git push origin main `
