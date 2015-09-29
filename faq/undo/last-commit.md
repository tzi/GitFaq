How to undo last git commit?
======

```sh
git reset --soft HEAD~1
```

Retrieve the state before you package it in a commit.


or - Do you want to retrieve the state before the last commit?
------

```sh
git reset --hard HEAD~1
```

Be aware that you will lost the change made in the last commit.


or - Is it just to fix a typo?
------

```sh
git commit --amend "New message"
```

Redo the last commit with a new message


Is your commit already pushed?
------

```sh
git push -f
```

Be aware that a force-push is not a best practice.
If someone else has already pulled your commit, you will have two divergent repository states.


[source: Christoph Rüegg](http://christoph.ruegg.name/blog/git-howto-revert-a-commit-already-pushed-to-a-remote-reposit.html)