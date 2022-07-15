# HelpFull-Git-Command

**git stash --patch**

git stash push -m welcome_cart app/views/cart/welcome.thtml
OLD ANSWER:

You can do that using git stash --patch (or git stash -p) -- you'll enter interactive mode where you'll be presented with each hunk that was changed. Use n to skip the files that you don't want to stash, y when you encounter the one that you want to stash, and q to quit and leave the remaining hunks unstashed. a will stash the shown hunk and the rest of the hunks in that file.

Not the most user-friendly approach, but it gets the work done if you really need it.
