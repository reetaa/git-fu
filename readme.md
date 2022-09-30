### Question
- I make changes to a file, let's call it basicFile.tsx. I do the edits on this file (branch: feature-branch). Takes me a few days. Sweet. But during my time of working on that file, someone has committed a change (branch: main) that has moved that file to a new directory and renamed it. So, not only does it live in a new file path, but it's called newBasicFileInANewLocation.tsx .
Is Git smart enough to automatically apply the changes I made to basicFile onto newBasicFileInANewLocation when I rebase those changes in? Or will it give me conflict errors saying I have made changes to a file that has been removed?

### Answer
- This particular scenario ends up in merge conflict.
https://github.com/reetaa/git-fu/pull
