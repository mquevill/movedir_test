# movedir_test

This repository is set up to test whether the Git history is retained when
directories are moved.

In this repository, the original file was
`location1/project1/lorem.txt`, which has a few commits.
This was then moved to `location2/project1/lorem.txt`.
If you look at the history of the current `lorem.txt`,
it only shows 1 commit. However, if you look at the parent
of that commit, and browse the history of that file, all of
the original commits will be shown there.

