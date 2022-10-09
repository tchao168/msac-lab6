# Exercise 8 - Viewing changes before committing

1. Ensure your working directory is clean     =>git status

2. Add text to any one of your files  

3. Delete different text from another of your files

4. Look at `git status`

5. View all the changes you've made

        git diff

6. Does the following command return anything?

        git diff --staged  
Ans: No
7. Add one of your changed files to the index

        git commit add <changed file>

Ans: I can not use >git commit add <changed file>, I use >git commit -i <fruits.txt>

8. What do these commands show?

        git diff
        git diff --staged
=> After I add message to Q7 file, <git diff > only display the one have not done
        <git diff --staged>  still back to prompt without any message

9. Add the other changed file to the index

        git commit add <other changed file>
 I still use <git commit -i furniture.txt>, then I use <git status> to check status, then I found out my
 vegetables.txt file has been modify, for I use it to copy to furniture.txt file, after I change the content in furnitures.txt,  my vegetables.txt change,too.
 < git commit -i vegetables.txt>

10. What do these commands show?

        git diff
        git diff --staged
Ans:After I change every modified files, both list commands only come back to command prompt

11. Commit the changes
    now my working directory is clean and commit, it cloud be that I use wrong command at Q7

12. Check that your working directory is clean

13. Create a new file named `clothing.txt`

14. Does the new untracked file show up in git diff?  ==> No

        git diff

15. Add and commit the new file
