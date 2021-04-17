#### git reset

    git reset <option> <commit>

    git reset -hard <commit> # commit 이후 모두 삭제
    git reset -soft <commit> # 인덱스, commit 그대로 보존
    git reset -mixed <commit> # 기본값, 인데스 초기화

#### git revert

    git revert <commit> # 이전 commit으로 되돌아가는게 아니라 새로운 commit을 만들고 해당 commit 코드로 돌아감
