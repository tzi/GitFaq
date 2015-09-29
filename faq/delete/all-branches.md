How to delete all git branches but master?
======

```sh
git branch | grep -v "master" | sed 's/^[ *]*//' | sed 's/^/git branch -d /' | bash
```

[source: David Walsh](http://davidwalsh.name/git-delete-branches-master)