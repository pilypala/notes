
timestamp

	console.log(new Date().toLocaleString());

zettel id

	"".replaceAll(' ', '-').toLowerCase();


https://stackoverflow.com/questions/3458685/how-can-i-completely-remove-a-file-from-a-git-repository

```
git filter-branch --tree-filter 'rm -f README' HEAD
```