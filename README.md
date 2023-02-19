# dev-notes

## Git
echo "# dev-notes" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin <repository-url.git>
git push -u origin main

…or push an existing repository from the command line

git remote add origin <repository-url.git>
git branch -M main
git push -u origin main

…or import code from another repository



git remote add origin https://<repository-url.git>

user settings -> developer settings -> Personal access tokens -> Tokens (classic)


git remote set-url origin https://<token>@<repository-url.git>
