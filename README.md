#Git push 时如何避免出现 "Merge branch 'master' of ..."
#https://www.cnblogs.com/Sinte-Beuve/p/9195018.html
git fetch
git rebase
解决冲突
git add 冲突文件
git rebase –continue
git push