
### Local Version Control
#### It's a system that have one database on the hard disk that stores changes to files.
### Centralized Version Control
#### It's a system include a single server storing all changes and file versions, which can be accessed by various clients.

## Git
#### Git is virsion control system and it's locally in your machine , it will have only 1 file. each time you save a changed version of your project Git creates a snapshot of the file and stores a reference to it. files in Git have three main states: committed, modified and staged.
#### Now to getting start we should install Git then check setting
### Cloning
#### You can create a copy of an existing Git repository from a particular server by using the clone command : $ git clone https://github.com/test
#### To save changing all files in working directory copy of a project file are either in a tracked or untracked state.
#### ($ git commit -a) this command for committing all changes.
#### ($ git push origin) master this command for push changes to a remote repository.
#### (git remote -v) This command mean that you can view all the remote URLs from where you clone.
