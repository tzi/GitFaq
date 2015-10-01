How to detect files that have conflicts during a git merge?
======

```sh
git status
```

"Changes to be committed": All committed changes to files that are not affected by the conflict are staged.

"Changed but not updated ... unmerged": All files that have conflicts that must be resolved before repository will be back to working order.
 
[source: UCSC Genome Bioinformatics Group](http://genomewiki.ucsc.edu/index.php/Resolving_merge_conflicts_in_Git#How_do_I_find_conflicts_within_the_file_itself.3F)