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
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
-------------------------------------------------------------------
Successfully cloned https://github.com/mojotx/git-fancy-clone.git!
-------------------------------------------------------------------
DIRECTORIES:
mojotx
mojotx/git-fancy-clone
```
