## Practice

# This is new text for the branch

- Add a file to both FolderToIgnore and DontIgnoreThisFolder
- From the command line run `git stash save -u` this will add the file in DontIgnoreThisFolder to the stash and remove it. The other file should stay as it.
- `git stash pop` will re-add the file that was not ignored.