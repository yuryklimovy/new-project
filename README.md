mkdir new-project
cd new-project/
git init
touch README.md
git add README.md
git commit -m "init"
git branch development
git checkout development
git checkout master
git merge development