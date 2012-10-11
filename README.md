I create this branch with the following steps

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


The original *master* was deleted from **GitHub**