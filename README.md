# Git
Git太深奧了要記錄！



##  GitLab&Github Add Branch

    git clone url or ssh

    git branch
    >*main

    git branch Jed

    git branch
    >*main
    >Jed

    git checkout Jed

    git branch
    >main
    >*Jed

    git push --set-upstream origin Jed

    完成！
    



## git fetch vs git pull

git fetch
將 origin 有但 local 沒有的版本記錄更新到本機上

git pull
與git fetch一樣只是多了git merge = git fetch + git merge



## 刪除多餘的commit 
選擇要回覆的head

    git reset (head)^ 
    git log

確定切好後換回branch就自動meage了
接下來push 到github&gitlab

    git push -f 

這邊下-f是因為你把head都刪掉了跟github&gitlab不一致會要求下git pull

這是git的安全機制預防工程師誤按所以要加個-f暴力push!

## 指定clone分支
    git clone -b develop --single-branch ssh or http 
