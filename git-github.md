# Git vs GitHub
### Version control
> version control: a system that allows you to revisit various versions of a file or set of files by recording changes (VCS- version control system
you can return to previous versions of a file, look at the history modifications and who made the edits
- local VCS: entails one database on your hard disk that stores changes to files
- centralized VCS: entails a single server storing all changes and file versions, which can be accessed by various clients.
issues with ^^ are that if the hard drive, or one server goes down, every collaborator will lose access to files and be unable to make changes
Distributed VCS: allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.
### What is git?
- Git is a DVCS that stores data in a file system made up of snapshots
- each time you make a commit, Git creates a snapshot of the files and stores a reference to it 
- Git mostly relies in local operations
- because Git relies on local files, you can work and update files while offline in Git
- Git tracks every change made to a file or directory
- Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data.
- files in Git can reside in 3 main states. Git states:
1. Committed: data is securely stored in a local database
1. Modified: file has been changed but not committed to the database
1. Staged: flagged a file’s changed version to be committed in the next snapshot

- Git has some built in GUI, but you can use third party clients for better visability
- you can import, clone and edit other people's Git files

The local Git repository has three components:
1. Working Directory: The actual files reside here.
1. Index: The area used for staging
1. Head: Points to the most recent commit

All files in a working (also called a checked out) project file are either in a tracked or untracked state
- Tracked: Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
- Untracked: Untracked files were not in the last snapshot and do not currently reside in the staging area.

- After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.
