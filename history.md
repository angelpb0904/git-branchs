   50  code .
   51  git init
   52  git branch -M main
   53  touch README.md
   54  gh repo create
   55  gh repo  create
   56  git commit -m "Primer commit"
   57  git add .
   58  git commit -m "Primer commit"
   59  git push
   60  git push --set-upstream origin main
   61  git branch testing
   62  git checkout testing
   63  git log
   64  git checkout main
   65  git commit -m "Segundo commit"
   66  git add .
   67  git commit -m "Segundo commit"
   68  git push
   69  git log --oneline --decorate --graph --all
   70  git merge testing
   71  git branch -d testing
   72  git log --oneline --decorate --graph --all
   73  history