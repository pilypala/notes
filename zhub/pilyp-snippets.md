
timestamp

	copy(new Date().toLocaleString('en-ZA').split(',')[0])

zettel id

	copy("".replaceAll(' ', '-').toLowerCase());


https://stackoverflow.com/questions/3458685/how-can-i-completely-remove-a-file-from-a-git-repository

```
git filter-branch --tree-filter 'rm -f README.md' HEAD
```

https://stackoverflow.com/questions/1274057/how-can-i-make-git-forget-about-a-file-that-was-tracked-but-is-now-in-gitign

	git rm --cached -r