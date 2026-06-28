#To create repository on Git 
# My_Git_Repo
$ echo "# My_Git_Repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:PrithviHe/My_Git_Repo.git
git push -u origin main
