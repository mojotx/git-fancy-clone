# Fancy "git clone"

Before cloning a Git repository, first create the owner's directory
and clone it there.

For instance, the `git fclone https://github.com/awesome/project.git`
would first create the directory `awesome`, if necessary, and change
to that directory. It would then clone the repository into
`awesome/project` directory.

Example:

```
$ cd ~/src/github.com
$ git fclone https://github.com/mojotx/git-fancy-clone.git
-------------------------------------------------------
   REPO: https://github.com/mojotx/git-fancy-clone.git
  GROUP: mojotx
PROJECT: git-fancy-clone.git
-------------------------------------------------------
Cloning into 'git-fancy-clone'...
remote: Enumerating objects: 61, done.
remote: Counting objects: 100% (61/61), done.
remote: Compressing objects: 100% (43/43), done.
remote: Total 61 (delta 20), reused 52 (delta 15), pack-reused 0
Receiving objects: 100% (61/61), 92.98 KiB | 1002.00 KiB/s, done.
Resolving deltas: 100% (20/20), done.
-------------------------------------------------------------------
Successfully cloned https://github.com/mojotx/git-fancy-clone.git
-------------------------------------------------------------------
DIRECTORIES:
mojotx/git-fancy-clone/git-fclone
```
