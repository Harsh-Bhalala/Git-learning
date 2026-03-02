1. sauthi pehla master ni andar 2 commit karavavanaa and then ek branch navi cerate karvi
2. te branch ma 2 commit karavvana
3. pachhi master ni andar 1 commit karavavu
4. then rebase karavavu --> menas ke branch na commit ne khali base change karr em kevanu
5. code :- git rebase master
6. then git add .
7. then dont type commit in terminal, type --> git rebase --continue
8. type "i" --> insertion mode
9. type esc to escape
10. then use git merge payment

// with github

11. using three line of code we accsss the our main master branch in github
12. we only use git push -u origin {branchname} first time 
13. then we can use only git push
14. steps --> git add . --> git commit -m "{message} --> then git push"
15. we can delete branch by --> git branch -D {branchname}
16. we can pull our data from main branch in github --> git pull origin {main}
17. we can check how many branch in github --> git branch -r
18. we can also delete from --> git push origin --delete BugFix