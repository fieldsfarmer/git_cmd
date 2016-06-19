#git command encountered
- if you want your local rep version go back, meanwhile you also want the version in github go back too. You need to firstly
```
git reset --hard HEAD^ 
```
The above goes to the previous version. There are also methods to go back to a specific one. Then:
```
git push --force origin master
```
This make the github rep goes back too.
[see more](http://stackoverflow.com/questions/17667023/git-how-to-reset-origin-master-to-a-commit)

