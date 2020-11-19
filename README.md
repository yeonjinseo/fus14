# FUS 14기 Git 수업
## 성수캠퍼스
11월 16일부터 20일까지 패스트캠퍼스 성수교육장에서 Git 관련 수업 내용을 정리해 봤습니다.

CLI 명령어 환경에서 Git을 학습합니다.

로컬 저장소와 리모트 저장소를 관리하는 방법도 학습했습니다.

## 11월 16일 월요일

## CLI
- pwd : 설명
- whoami
- clear
- mkdir
- cd
- ls
- rmdir
- rm
- mv

##Git
- 초기환경 설정
  - git config --global user.name
  - git config --global user.email
- git init
- git status
- git add
- git commit -m "변경사항 적기"

##태그추가하기
- git tag v4
- git tag v3 태그번호 쓰기

##저장소에 업데이트하기
- git push -u origin main(명령어 입력)

##로컬과 리모트 가져오기
- 우선 리모트에서 수정한 경우 
    : 리모트에서 수정->pull로 땡겨오기(git pull origin main)->수정하고 병합하고 다시 push 하기

##git remote -v : 
##git clone 링크복붙
