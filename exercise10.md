# Exercise 10 - Understanding Commits

1. Look at your commit log

        git log --oneline

2. Choose a commit hash
   Ans:    git commit --amend   ( ammend message)


3. See what type of object that hash names

        git cat-file -t <hash>
Ans: see what you do commit or update

4. Examine the contents of that commit closely

        git cat-file -p <hash>
Ans: show tree, parent, author, committer

5. Find the parent's hash in the commit log

Ans:parent 2cb61de5e1525038e138ed4aedf3d0bed6ba987d

6. Look at the contents of the tree

        git cat-file -p <hash>
Ans: It show all contents of the tree with location blob hash and filename

7. Examine the contents of one of the blobs
Ans: git cat-file -p  with any hash from question 6

8. What type of object does the parent hash represent?

        git cat-file -t <hash>
Ans: commit

9. Examine the contents of the parent and its tree
        git cat-file -t <hash>
Ans: When execute this command with exercise01.md hash, it display this file content


10. Do the trees you looked at have any matching hashes listed?
Ans: Can not tell, but yes, because ost of files start with exercise num, probably need hash cracker program to solve. 
