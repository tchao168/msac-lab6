# Exercise 9 - Viewing history

1. Make a commit with a multi line commit message
   (leaving an empty line after the first line)
   > git commit filename -m"The changes are
                        -
                        - fix some spelling problem
                        - fix 2n section
                        "

2. View that commit in the log

        git log -1

3. View the full commit log

        git log

*If the log fills your whole terminal, press `q` to exit*

4. View a shortened version of the commit log

        git log --oneline

5. Pick a commit hash from the log
   commit hash is along string follow by commit  ( after you run <git log>)
    6ad183e0c324f4f63b63e7fcf28be1019575a6eb 
6. View the commit log from the chosen commit backward

        git log --oneline <commit_hash>

7. How much of the commit hash do you need to specify? Hint, run `git help log`
    ans: one
8. How can you show just the last three commit messages?
   git log -3
