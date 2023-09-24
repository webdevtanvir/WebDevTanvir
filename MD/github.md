## 1. create a new repository on the command line:

```bash

echo "" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/webdevtanvir/<repository name>.git
git push -u origin main

```

## 2. push an existing repository from the command line:

```bash

git remote add origin https://github.com/webdevtanvir/<repository name>.git
git branch -M main
git push -u origin main

```

## 3. URL <span style='color:red; background: #ffffff40;padding: 2px 5px'>error:</span>

```bash

git pull --rebase origin main
git fetch origin
git reset --hard origin/main

```

