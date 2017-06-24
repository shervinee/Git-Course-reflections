# Some additional note to brush up memory about git & gitHub written in markdown

## Code Academy:
importance of reset command for un-staging files, and importance of un-staging when having staging multiple things we wanna commit but changing our mind in the middle of the way
command: git reset HEAD file_name


if reset used with a commit SHA we back-trace our commit log to a wanted point and everything else we had after it would be unlinked.
command: git reset Commit_SHA

## using diff (with git or without git):

using difference (in files or commits) is one of the most powerful tools for version control and debugging in general

OS:(bash/terminal)
finding difference in big files ? (if on windows use FC standing for file compare and if on linux use diff)

Git:
git diff also can show differences between two commits of a file if we use: (the only difference would be to save each file we would need to do two separate commits)
git log
git diff (#id)(#id)        the two are two different commit ids (SHA)
