# Git



## Config



1. Set name:

   ```shell
   git config --global user.name "Your Name"
   ```

2. Set email:

   ```shell
   git config --global user.email "youremail@example.com"
   ```
   
3. Set user name

   ```shell
   git config --global user.username username
   ```

   

## Create Repository



1. Init:

	```shell
	git init
	```

2. Status:

	```shell
	git status
	```

3. Add:

   ```shell	
   git add file.txt
   ```

4. Commit:

   ```shell
   git commit -m "Committed"
   ```

5. Different:

   ```shell
   git diff
   ```




## Remote Control



1. Add remote connections

	```shell
	git remote add <REMOTENAME> <URL>
	```
	
2. Set a URL to a remote

   ```shell
   git remote set-url <REMOTENAME> <URL>
   ```

3. Pull in changes

   ```shell
   git pull <REMOTENAME <BRANCHNAME>
   ```

4. View remote addresses

   ```shell
   git remote -v
   ```

5. Push changes

   ```bash
   git push <REMOTENAME> <BRANCH>
   ```



## Forks And Clones



1. Fork

   - Click **Fork** button

2. Clone

   - Clone a respository

     ```shell
     git clone <FORKEDURL>
     ```

   - Connect to the Original Repository

     ```shell
     git remote add upstream <ORIGINALURL>
     ```



## Branches



1. GitHub Pages

   - GitHub will automatically serve and host static website files in branches named 'gh-pages'

2. Create a branch

   ```shell
   git branch <BRANCHNAME>
   ```

3. Go into a branch

   ```shell
   git checkout <BRANCHNAME>
   ```

4. Create and Go into a branch

   ```shell
   git checkout -b <BRANCHNAME>
   ```

5. List the branches

   ```shell
   git branch
   ```

6. Rename a branch currently on

   ```shell
   git branch -m <NEWNAME>
   ```

7. Merge data

   ```shell
   git merge <BRANCHNAME>
   ```

8. Delete local branch

   ```shell
   git branch -d <BRANCHNAME>
   ```

9. Delete a remote branch

   ```shell
   git push <REMOTENAME> --delete <BRANCHNAME>
   ```

10. Pull from a remote branch

    ```shell
    git pull <REMOTENAME> <BRANCHNAME>
    ```

    

