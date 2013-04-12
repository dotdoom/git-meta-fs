git-meta-fs
===========

Add file/directory owner and permission information to the git commit.

git-meta-fs is designed to be used as a Git hook. It stores and restores filesystem objects permission and ownership information.
The storage is a special directory .gitmetafs which should be added to the source control.
