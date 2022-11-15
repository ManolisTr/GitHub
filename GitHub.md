# GitHub Instructions

## Create a new repository on the command line
```
echo "# GitHub" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:ManolisTr/GitHub.git
git push -u origin main
```
## Clone an already existing Repo
```
git clone git@github.com:ManolisTr/GitHub.git
```
## Get changes from Repo
```
git pull
```

## Commit changes
```
git add .
git commit -m "descriptive message"
```
or for one file

```
git add hello.py
git commit -m "descriptive message"
```

## Push Changes
```
git push
```