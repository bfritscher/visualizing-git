﻿Visualize Git
=============

Git is an amazingly powerful tool — and it can be amazingly confusing. Demystify Git commands with visualizations powered by D3. Give it a try at [https://bfritscher.github.io/visualizing-git/](https://bfritscher.github.io/visualizing-git/)!

![By Git School](http://i.imgur.com/EiuyjJQ.png?1)

[Visualize Git](https://bfritscher.github.io/visualizing-git/) illustrates what's going on underneath the hood when you use common Git operations. You'll see what exactly is happening to your commit graph. We aim to support all the most basic git operations, including interacting with remotes.

Here are some examples of the fun things you can do with it:

## Rebase
![rebase](images/viz-rebase.gif)

## Cherry-pick
![cherry-pick](images/cherry-pick.gif)

## Push/pull
![push-pull](images/remote.gif)

## Supported operations

Type `help` in the command box to see a list of supported operations

`pres()` = Turn on presenter mode<br>
`undo` = Undo the last git command<br>
`redo` = Redo the last undone git command<br>
`edit` = Make a file edit<br>
`mode` = Change mode (`local` or `remote`)<br>
`clear` = Clear the history pane and reset the visualization

Available Git Commands:
```
git branch
git checkout
git cherry-pick
git commit
git fetch
git log
git merge
git pull
git push
git rebase
git reflog
git reset
git rev-parse
git revert
git tag
git add
git stash
```


We hope you find this tool useful! Issues and pull requests are welcome! Enjoy! :sparkles:

Based on the awesome work done by [@onlywei](https://github.com/onlywei/explain-git-with-d3) :bow:
https://github.com/git-school/visualizing-git
https://github.com/dpatel19/visualizing-git/tree/working_tree_viz
https://github.com/RezaKargar/visualizing-git
