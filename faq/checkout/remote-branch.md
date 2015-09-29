How to checkout remote Git branch?
======

```sh
git fetch origin
git checkout -b <local-branch> origin/<remote-branch>
```

This will:

 1. Update the references of the remote branches 
 2. Create a new branch initialized with the remote branch state
 
[source: hallski on StackOverflow](http://stackoverflow.com/a/1783426/1978945)
