# gdelt

### Data

http://data.gdeltproject.org/events/index.html

### Git

I only keep the last 7 days, since there are binary files here,
occasionally delete old history, reinit repo, and push a brand new
repo with only last 7 days completely overwriting the old.

Remove `.git`

```
git branch -m main 

git init

git add .

git commit -m 'Initial commit'

git remote add origin git@github.com:muratk5n/gdelt.git

git push --force --set-upstream origin main
```
