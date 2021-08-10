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

### git fetch
將 origin 有但 local 沒有的版本記錄更新到本機上

### git pull
與git fetch一樣只是多了git merge = git fetch + git merge

