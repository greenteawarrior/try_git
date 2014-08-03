### Quick github guide (Emily's notes)

Open terminal window (control+alt+T) and clone repository onto your computer
``` 
$ git clone http://...insertURLhere
```

Work/modify on the files in the repository
Then, see the current state of the repository
```
$ git status
```

Stage the file
```
$ git add filename.extension
```
OR
Stage everything in the folder at once
```
$ git add .
```
OR
# My favorite b/c this command stages the added files, modified files, and removed files
```
git add --all
```

Check git status again if desired
```
$ git status
```

# All good? Commit the changes
```
$ git commit -m "comment str"
```
OR
```
$ git commit #nano will open and you type your comment
```

# Finally, push the updates to github
```
$ git push origin master
```
