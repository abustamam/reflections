## What happens when you initialize a repository? Why do you need to do it? ##

Git creates a .git folder to store all the metadata, such as commit history, commit contents, etc.

## How is the staging area different from the working directory and the repository? What value do you think it offers?

The repository includes the commit history, and the working directory is the directory you're working out of (e.g, the directory on your hard drive).

The staging area is a stage between the WD and the repo, and lets you review what will be added before it is actually added. You can also add one file at a time to the staging area, and then commit the entire staging area to the repo.

## How can you use the staging area to make sure you have one commit per logical change? ##

Everything in the staging area should contribute to one logical change. If there is something in the staging area that does not contribute to that change, I can take it out before committing it. That way I don't mess with the commit history if I make a mistake.

## What are some situations when branches would be helpful in keeping your history organized? ##

If I want to add an experimental feature, I could use branches. Then I can see commit history in terms of words and features added, rather than hashes.

## How do the diagrams help you visualize the branch structure? ## 

The diagrams help me visualize the branch structure by allowing me to see which commits are reachable from which branches. It's like a tree.

## What is the result of merging two branches together? Why do we represent it in the diagram the way we do? ##

Merging two branches seems to add all the changes that each branch introduced into one single commit, so that way the final product contains all the features of both branches.

It's represented in the diagram the way it is because then we can visualize that the merge commit has two parents, and contains all the commits of each parent.

## What are the pros and cons of Git's automatic merging vs always doing merges manually? ##

Automatic merging is a great idea, but sometimes it might make a change that could break the program. 

Doing merges manually allows more control over what the final version looks like, but it's more meticulous as well!
