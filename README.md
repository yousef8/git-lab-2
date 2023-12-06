# Lab 2

## 1. Create new project on local maching, then push it to remote repo

1. **Create Remote Repo**
  
    ![](./imgs/git-lab2-1-a.png)

1. **Create Local Repo and push it to Remote Repo**

    ![](./imgs/git-lab2-1-b.png)

## 2. Create 2 branches (dev & test), then create a file in each of them, then push them to remote repo

1. **Create Branches**

    ![](./imgs/git-lab2-2-a.png)

1. **Create a file in each branch**

    ![](./imgs/git-lab2-2-b.png)
    ![](./imgs/git-lab2-2-c.png)

1. **Push Changes to Remote Repo**

    ![](./imgs/git-lab2-2-d.png)

## 3. Merge these changes on Main branch and then push it to remote repo

![](./imgs/git-lab2-3.png)

## 4. How to remove branches locally and remotely

1. **Locally**

    ```text
    git branch -d dev

    git branch -d test
    ```

1. **Remotely**

    ```text
    git push origin :dev

    git push origin :test
    ```

## 5. How to checkout another branch without commit changes?

* If there are changes in the working copy that aren't commited and trying to switch branch `git` will complain with an error that these edits will get deleted if branch is switched you will have to either delete the edits or commit it first

* Another solution is to `stach` the uncommited changes and then switching the branch

## 6. Create an annotated tag with tagname `v1.7`

![](./imgs/git-lab2-6.png)

## 7. Push it to the remote Repo

![](./imgs/git-lab2-7-a.png)

![](./imgs/git-lab2-7-b.png)

## 8. How to list tags

![](./imgs/git-lab2-8.png)

## 9. How to delete tag locally and remotely

1. **Remotely**

    ![](./imgs/git-lab2-9-a.png)

    ![](./imgs/git-lab2-9-b.png)

1. **Locally**

    ![](./imgs/git-lab2-9-c.png)

## 10. Add an image to README.md file

![](./imgs/git-lab2-10.png)
