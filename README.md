# WORKSHOP-STORYBOOK

## [description]
- 브랜치별로 여러 스토리북을 사용해보는 repository
    - main: description을 설명하는 브랜치

## [author]
- 옥현지
    - hyunji-ok(개인 계정)
    - okhj159(회사 계정)

## [caution]
- 원본 repo(upstream)과 fork repo(origin)의 branch 맞추는 방법 
    - upstream 원격 추가: git remote add upstream <원본 리포지토리 URL>
    - upstream의 변경 사항 가져오기: git fetch upstream
    - 새로운 브랜치 fet를 로컬에서 생성 및 체크아웃: git checkout -b fet upstream/fet
    - 새로운 브랜치를 포크된 리포지토리로 푸시: git push origin fet