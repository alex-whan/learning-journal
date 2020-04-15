# Revisions and the Cloud
The cloud is a powerful tool for developers to seamlessly update their webpages from their very own computers. There are several important terms and concepts to keep in mind when it comes to updating web pages and code via the cloud.

## Git

A short word for a big concept, **Git** is a "version control software" that documents a history of all of the the changes and edits to your code. This "versioning" not only allows multiple developers to work simultaneously on the same code, but also creates a photo album of "snapshots" of the code at given points in time.

Crucially, this feature allows developers to view, apply, and remove the said changes. Changes in Git, or "saving" them in he code, are known as *commits*. Commits essentially function as a "save as" button on a file, charting the history of a file throughout its development. Messages assigned to commits, as a part of industry best-practices, help to document both the changes made and the reasons for those changes for future reference.

To summarize:

* Git is a "version control system"
* It allows multiple developers to work on the same code
* It preserves a history of changes to your files
* It keeps all of your project files in a single repository

## GitHub

Despite the similar name, **GitHub** is *not* the same as Git. GitHub is the collaboration platform that utilizes Git under the hood. The platform serves as a way to share your code with others, or store it in a huge repository available worldwide. 

Many of the most important aspects of Git are present in GitHub, and its version control allows teams of developers to better manage their work by centralizing the code storage and keeping changes separate until they're ready to be added.

To summarize:

* GitHub is the "online code storage" to Git's "version control system"
* Uses Git to manage a team's work, including version tracking
* Centralized code database shareable with others

## Repositories - AKA, "repos"

At their most basic level, **repositories** - commonly referred to as *repos"* - are collections of files kept in one place to be used by Git. Generally, a single project will use a single repository, though in the case of very large projects there may be separate respositories for the front-end and back-end files. Repositories can reside both on your computer and on GitHub, and can be synced between the two with ease by using a code editor and an array of Git-related commands.

To summarize:

* Repositories store files in one location
* Can be synced between the cloud (GitHub) and your computer

Important terms and commands:

* Commit: a Git equivalent of "save as"
* Head: The most current version of the code
* Message: Documentation of changes made to code as part of a commit

## Add-Commit-Push Process (A-C-P)

The **Add-Commit-Push** process, known as *"A-C-P"* or *ACP*, is a critical best-practice that ensures developers stay on top of meaningful changes.

Important commands:

* ```git clone LINK FROM GITHUB```
* ```git add .```
* ```git commit```
* ```git commit -m "MESSAGE"```
* ```git push```
* ```git push origin master```
* ```git status```

Return to the [Table of Contents](https://alex-whan.github.io/learning-journal/)