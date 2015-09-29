How to remove a git submodule?
======

Since git 1.8.5.2

```sh
git rm the_submodule
rm -rf .git/modules/the_submodule
```

[source: tinlyx on StackOverflow](http://stackoverflow.com/a/21211232/1978945)