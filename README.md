# Version-control
  This is unserstood as a system that gets track of all changes made to a files. that is, if you make a mistake on your code, it can easily be reverted, that is to restore or recover the previous state of a file. 

  // CORE FEATURES;
   1: Repository- can also be called "repo" it is a storage for all project and like a Project Folder  
   2: Commit- it is a snapshot  of your files at specific points in time. and these snapshots includes,The actual changes made to files, A message describing what changed and why, Information about when and who made the changes.
   3: Branches- These let you create separate lines of development from the same starting point. You might have: A main branch for stable code, Feature branches for developing new functionality, Bug fix branches for fixing issues.
   4: Merge: Combining changes from one branch into another.

# Explain difference between git and github
   // GitHub- is a web-based platform that provides hosting for Git repositories. It provides a centralized place to store Git projects and share them with others. It helps you  Connect with other developers, Manage bugs,  Propose changes to a repository and get feedback from others.
   // Git- This  is the engine that powers version control, Tracks changes to your files, Runs locally on your computer. Git is like a tool for taking photos (making commits), while GitHub is like Instagram - a place to store those photos and share them with others.
   You can use Git without GitHub, but you can't use GitHub without Git.

# List 3 other github alternative
   // GitLab- It is known for its comprehensive DevOps platform, offering features beyond code hosting like CI/CD pipelines, issue tracking, and security scanning. Often favored by enterprises.
   // Bitbucket- it features Free private repositories and its usually good for small teams. Strong focus on private repositories.
   // SourceForge- It is one of the oldest code hosting platforms. Includes project websites and documentation hosting and Built-in bug tracking and discussion forums

# Explain the difference between git fetch and git pull,
  // Git Fetch-  Downloads changes from the remote repository but doesn't integrate them, Doesn't modify your working directory or local branches, Safer operation as it doesn't automatically merge changes. In essence, git fetch is like checking for new emails without opening them.
  Use git fetch when=> You want to review changes before merging them. You want to avoid potential merge conflicts.You want to update your local repository with the latest information without modifying your working directory.

  // // Git Pull- Does everything git fetch does and also merges the changes into your current branch. If there are conflicting changes between your local branch and the remote branch, git pull will attempt to merge them automatically, which can sometimes result in merge conflicts. 
  Use git pull when => You want to quickly update your local branch with the latest changes from the remote repository.
  You are confident that there will be no merge conflicts.

# Explain in simple terms git rebase and the command for it,
  In Git, rebase is a command that rewrites your commit history. It takes your commits from one branch and replays them onto another branch, as if you had created them on top of the new base. This results in a linear commit history, making it easier to read and understand.
  // The Command- Bash "git rebase"
  // Examples- Bash "git rebase main"
  This command will rebase your current branch onto the main branch, effectively moving your commits to the latest state of main.
  Why Rebase? It allows you to resolve conflicts before merging, which can be helpful for large projects.
# Explain in simple terms git cherry-pick and the command,
  // Git cherry-pick lets you grab a specific commit from any branch and apply it to your current branch. Think of it like picking a single cherry (commit) from one tree (branch) and placing it onto another tree.
  // The Command- git cherry-pick <commit-hash>, git cherry-pick abc123f, where abc123f is your commit hash
  Think of it as copying and pasting a specific change, rather than merging entire branches together. It's useful when you want just one specific change rather than everything in a branch.
 