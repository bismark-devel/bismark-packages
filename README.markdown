## bismark-devel/bismark-packages has moved to projectbismark/bismark-packages

The repo you are looking for has moved. You can now find it at
https://github.com/projectbismark/bismark-packages

### How to update your local copy of 'bismark-packages'

If you have any local repositories configured to pull from this repository
(i.e. remotes set up for bismark-devel/bismark-packages), please do the
following to update it to point at the new repository location:

1. `cd` to the top directory of your local repository
   (e.g. `cd bismark-packages`)

2. Open `.git/config` in your favorite editor and replace every instance of
   'bismark-devel' with 'projectbismark', as in the following example:

```diff
 [remote "origin"]
    fetch = +refs/heads/*:refs/remotes/origin/*
-       url = git@github.com:bismark-devel/bismark-packages.git
+       url = git@github.com:projectbismark/bismark-packages.git

```

**Run a `git pull` to confirm that everything is working as expected.**
