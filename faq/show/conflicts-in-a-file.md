How to detect conflicts in a file during a git merge?
======

Conflicts are marked in a file with clear line breaks:

    <<<<<<< HEAD:mergetest
    This is my third line
    =======
    This is a fourth line I am adding
    >>>>>>> 4e2b407f501b68f8588aa645acafffa0224b9b78:mergetest

<<<<<<<: Indicates the start of the lines that had a merge conflict. The first set of lines are the lines from the file that you were trying to merge the changes into.

=======: Indicates the break point used for comparison. Breaks up changes that user has committed (above) to changes coming from merge (below) to visually see the differences.

\>>>>>>>: Indicates the end of the lines that had a merge conflict. 
 
[source: UCSC Genome Bioinformatics Group](http://genomewiki.ucsc.edu/index.php/Resolving_merge_conflicts_in_Git#How_do_I_find_conflicts_within_the_file_itself.3F)
