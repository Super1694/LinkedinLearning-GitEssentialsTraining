
# Review Changes with Log

## Key Terms
- Log Function
- Checksum - The code name string for a specific commit

## Navegating a log
- space: page down
- up/down arrows: move line by line
- q: quit log view... go back to using the terminal as normal
- b: page up

## Types of Logs

**$ git log**
Will show a brief summary of each change / commit on the branch

**git show [checksum]**
will show a specific commit and all the changes made in that commit

**git log -p**
Will show the log with changes made in each commit

**git log --oneline**
gives log of all changes with a shortened checksum and just the commit message in one line. Very useful.

**git log --grep='[text]'**
the `--grep` makes it search for a specific line in the commit message. This is why it is good to use a standard format for your commit messages, such as referencing what file was changed in the commit. Also might be useful to not do an add . > commit. chaning one thing at a time would be helpful for later tracking changes.

**git log --graph**
Shows a visual representation of the branches along the way.

## Online History
You can also go to github and view all the changes, along with the commit history, and it provides some visual tools as well.



