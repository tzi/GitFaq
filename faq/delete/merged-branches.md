How to delete local branches associated to a merged branch?
======

```sh
git branch --merged master | grep -v master | xargs git branch -d
```

[source: GitLab](https://twitter.com/gitlab/status/422727786743078912)
