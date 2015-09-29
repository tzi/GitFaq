How to find and restore a deleted file in a git repository?
======

```sh
git rev-list -n 1 HEAD -- <file-path>
git checkout <deleting-commit>^ -- <file-path>
```

This will:

 1. Find the last commit that affected the given path
 2. Checkout the version at the commit before
 
[source: Charles Bailey on StackOverflow](http://stackoverflow.com/a/1113140/1978945)