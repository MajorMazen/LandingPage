# [News Angles](http://MajorMazen.github.io/LandingPage)

```
git add . && git commit -am .. && git push origin master && git branch
```

```
git checkout gh-pages && git branch && git push origin gh-pages && git checkout master && git branch
```

### [easily-keep-gh-pages-in-sync-with-master](http://lea.verou.me/2011/10/easily-keep-gh-pages-in-sync-with-master/)
```
git add .
git status // to see what changes are going to be commited
git commit -am .. && git push origin master

git checkout gh-pages // go to the gh-pages branch
// git rebase master // bring gh-pages up to date with master
// git push origin gh-pages // commit the changes
git rebase master && git push origin gh-pages
git checkout master // return to the master branch
```
