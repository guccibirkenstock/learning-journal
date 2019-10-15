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
