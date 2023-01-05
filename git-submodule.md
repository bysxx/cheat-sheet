```sh
git submodule init
git submodule update
```

### Add specific sub module

It must run the following command at the folder location where you want to install the sub-module.

```sh
git submodule add <git-url>
```

Remove specific sub module

```bash
# Note: a/submodule (no trailing slash)
git submodule deinit -f -- <module-path>
rm -rf .git/modules/<module-path>
git rm -f <module-path>

# or, if want to leave it in your working tree and have done step 0
git rm --cached <module-path>
```

### Specific module download

```bash
git submodule update <module-name>
```
