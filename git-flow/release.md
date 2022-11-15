# Step Three - Work with release branch (and the same form with bugfix and hotfix)

>In this step, we was work with the release branch.
>This branch is only for releases with tags, prepare for deploy to production.

## Objective

> *Work with release branch in git flow form*

## Use git flow commands to work with them

---

### Release branch

* Init the release git flow branch (version)

> ` git flow release start 0.1.1 `{{exec}}

* Publish the release

> ` git flow release publish 0.1.1 `{{exec}}

* Finalize the release

> ` git flow release finish 0.1.1 `{{exec}}

## Hotfix branch (for bugfix are same)

### Work with hotfix branch

* Init the hotfix git flow branch (version)

> ` git flow hotfix start 0.0.2 `{{exec}}

* Finalize a hotfix branch

> ` git flow hotfix finish 0.0.2 `{{exec}}
