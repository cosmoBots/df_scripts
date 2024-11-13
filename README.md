# Scripts for supporting the automated project folder creation and evolution

The following repository has to be added to the project as a submodule, in the `.scripts` directory of the root folder.

```
git submodule add <repo_clone_url> .scripts
```

For instance:

```
git submodule add https://your_organization/_git/prj_scripts ./.scripts
```

It shall to be populated and updated using

```
git submodule update --init --recursive
```

