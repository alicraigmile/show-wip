# show-wip

A command line utility to list your development work in progress.

show-wip looks for active branches in git repos on your local machine and display them in a hndy list.

## Usage

```
usage: show-wip [-a] [-f folder] [-h] [-v]
  -a        :  show all branches, default is to show only active branches.
  -f folder :  where to look for git repositories. Default is ~/workspace.
  -h        :  help, show this message.
  -v        :  verbose, show last commit message for each branch too.
```

Pro tip: Run show-wip from your .login script to remind you what you were doing last.
