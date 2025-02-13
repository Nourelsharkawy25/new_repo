# My New Repo
1.create directory and init repo
    ```
    mkdir my-new-repo && cd my-new-repo
    git init
    ```
2. create read me file and add to staging and repo
  ```
  echo "# My New Repo" > README.md  or touch README.md
  git add README.md
  git commit -m "Initial commit - Added README.md"
  ```
3. create repo on github and dont create md file
 with ssh for example
  ```
  git remote add origin git@github.com:Nourelsharkawy25/new_repo.git
  git branch -M main
  git push -u origin main
  ```
