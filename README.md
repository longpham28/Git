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

   ```shell
   git push <REMOTENAME> <BRANCH>
   ```

   



