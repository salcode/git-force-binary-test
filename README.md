Git Force Binary Test
=====================

This repo goes with my post
[http://salferrarello.com/git-file-force-binary/](http://salferrarello.com/git-file-force-binary/)
in which I attempt to treat a CSS file as a binary
file in Git.

Test for Binary
---------------
I'm using the line
`git merge-file /dev/null /dev/null style.min.css`
to test if Git is treating the file as binary.
- No result indicates NOT binary.
- **error: Cannot merge binary files: style.min.css** indicates binary
