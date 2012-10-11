I create this branch with the following steps (see [How to Create a New and Empty Branch in Git](http://www.bitflop.com/document/116))

1. Create a bland branch named as *demo*

		$ git checkout --orphan demo

2. Remove all files in git

		$ git rm -rf

3. Edit `.gitignore` to ignore the files

4. Add `README.md` into new branch

		$ touch README.md
		$ git add .

5. Commit to the new branch

		$ git commit -m "init commit"


The original *master* was deleted from **GitHub** with the following steps

1. Log into **GitHub** and find your repository

2. Click on the **Admin** button and set the default branch to *demo*

Now you are free to delete the *master* branch. See [Deleting your master branch — pydagogue 0.2 documentation](http://matthew-brett.github.com/pydagogue/gh_delete_master.html)