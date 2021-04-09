# Git & GitHub

Created: Mar 8, 2021 12:10 AM

## Git Overview

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/Git-Cheatsheet.png](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/Git-Cheatsheet.png)

# Git Explain

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190130.802.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190130.802.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190139.280.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190139.280.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190209.867.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190209.867.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190239.440.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190239.440.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190249.368.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/2._Version_Control_Using_Git_and_the_Command_Line.mp4_20210407_190249.368.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/3._GitHub_and_Remote_Repositories.mp4_20210409_134924.725.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/3._GitHub_and_Remote_Repositories.mp4_20210409_134924.725.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/3._GitHub_and_Remote_Repositories.mp4_20210409_134944.657.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/3._GitHub_and_Remote_Repositories.mp4_20210409_134944.657.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/3._GitHub_and_Remote_Repositories.mp4_20210409_135012.432.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/3._GitHub_and_Remote_Repositories.mp4_20210409_135012.432.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/3._GitHub_and_Remote_Repositories.mp4_20210409_135020.097.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/3._GitHub_and_Remote_Repositories.mp4_20210409_135020.097.jpg)

---

# **Git Commands**

[atlassian-git-cheatsheet.pdf](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/atlassian-git-cheatsheet.pdf)

## **git config**

```bash
git config –global user.name “[name]”
```

```bash
git config –global user.email “[email address]”
```

This command sets the author name and email address respectively to be used with your commits.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/1-9.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/1-9.png)

## **git init**

```bash
git init [repository name]
```

This command is used to start a new repository.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/2-6.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/2-6.png)

## **git clone**

```bash
git clone [url]
```

This command is used to obtain a repository from an existing URL.

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/6._Cloning.mp4_20210409_205328.049.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/6._Cloning.mp4_20210409_205328.049.jpg)

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/4-4.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/4-4.png)

## **git add**

```bash
 git add [file]
```

This command adds a file to the staging area.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/5-4.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/5-4.png)

```bash
 git add *
```

This command adds one or more to the staging area.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/6-3.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/6-3.png)

## **git commit**

```bash
git commit -m “[ Type in the commit message]”
```

This command records or snapshots the file permanently in the version history.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/7-3.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/7-3.png)

```bash
git commit -a
```

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/8-2.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/8-2.png)

## **git diff**

```bash
git diff
```

This command shows the file differences which are not yet staged.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/9-2.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/9-2.png)

```bash
git diff –staged
```

This command shows the differences between the files in the staging area and the latest version present.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/10-2.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/10-2.png)

```bash
git diff [first branch] [second branch]
```

This command shows the differences between the two branches mentioned.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/43.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/43.png)

## **git reset**

```bash
git reset [file]
```

This command unstages the file, but it preserves the file contents.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/11-1.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/11-1.png)

```bash
git reset [commit]
```

This command undoes all the commits after the specified commit and preserves the changes locally.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/14-1.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/14-1.png)

```bash
git reset –hard [commit]  
```

This command discards all history and goes back to the specified commit.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/13-1.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/13-1.png)

## **git status**

```bash
git status
```

This command lists all the files that have to be committed.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/15-1.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/15-1.png)

## **git rm**

```bash
git rm [file]
```

This command deletes the file from your working directory and stages the deletion.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/16-2.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/16-2.png)

## **git log**

```bash
git log
```

This command is used to list the version history for the current branch.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/18.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/18.png)

```bash
git log –follow[file]
```

This command lists version history for a file, including the renaming of files also.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/19.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/19.png)

## **git show**

```bash
git show [commit]
```

This command shows the metadata and content changes of the specified commit.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/20.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/20.png)

## **git tag**

```bash
git tag [commitID]
```

This command is used to give tags to the specified commit.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/22.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/22.png)

## **git branch**

```bash
git branch
```

This command lists all the local branches in the current repository.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/23.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/23.png)

```bash
git branch [branch name]
```

This command creates a new branch.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/24.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/24.png)

```bash
git branch -d [branch name]
```

This command deletes the feature branch.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/25.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/25.png)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/7._Branching_and_Merging.mp4_20210409_205730.697.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/7._Branching_and_Merging.mp4_20210409_205730.697.jpg)

## **git checkout**

```bash
git checkout [branch name]
```

This command is used to switch from one branch to another.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/27.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/27.png)

```bash
git checkout -b [branch name]
```

This command creates a new branch and also switches to it.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/28.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/28.png)

## **git merge**

```bash
git merge [branch name]
```

This command merges the specified branch’s history into the current branch.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/31-1.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/31-1.png)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/7._Branching_and_Merging.mp4_20210409_205751.337.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/7._Branching_and_Merging.mp4_20210409_205751.337.jpg)

## **git remote**

```bash
git remote add [variable name] [Remote Server Link]
```

This command is used to connect your local repository to the remote server.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/32.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/32.png)

## **git push**

```bash
git push [variable name] master
```

This command sends the committed changes of master branch to your remote repository.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/33.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/33.png)

```bash
git push [variable name] [branch]
```

This command sends the branch commits to your remote repository.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/34.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/34.png)

```bash
git push –all [variable name]
```

This command pushes all branches to your remote repository.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/36.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/36.png)

```bash
git push [variable name] :[branch name]
```

This command deletes a branch on your remote repository.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/37.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/37.png)

## **git pull**

```bash
git pull [Repository Link]
```

This command fetches and merges changes on the remote server to your working directory.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/38.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/38.png)

## **git stash**

```bash
git stash save
```

This command temporarily stores all the modified tracked files.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/39.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/39.png)

```bash
git stash pop
```

This command restores the most recently stashed files.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/40.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/40.png)

```bash
git stash list
```

This command lists all stashed changesets.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/44.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/44.png)

```bash
git stash drop
```

This command discards the most recently stashed changeset.

![https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/42.png](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/42.png)

---

## .gitignore

create gitignore file to stop including some important files to repos

```bash
touch .gitignore
```

open the file and add files name

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/5._Gitignore.mp4_20210409_194556.545.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/5._Gitignore.mp4_20210409_194556.545.jpg)

A collection of .gitignore templates

[github/gitignore](https://github.com/github/gitignore)

---

## Forking and pull explain

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211839.618.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211839.618.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211904.802.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211904.802.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211923.681.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211923.681.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211929.370.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211929.370.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_212033.372.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_212033.372.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211934.586.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_211934.586.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_212029.402.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_212029.402.jpg)

![Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_212036.393.jpg](Git%20&%20GitHub%203704dd278798445d9c07b87c82f11af5/9._Forking_and_Pull_Requests.mp4_20210409_212036.393.jpg)

---