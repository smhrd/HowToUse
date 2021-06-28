## How to use Github 첫 페이지로 [이동](./index.md)

## 목차
1. [Git 설치하기](#git-설치하기)
1. [Base Project 만들기](#base-project-만들기)
1. [Clone Project](#clone-project)
1. [[기타] Git 사용시 주의사항](#git-사용시-주의사항)
1. [[기타] Git user 정보 수정하기](#git-user-정보-수정하기)

## Git 설치하기

> VS Code에서 Git을 사용하려면 별도 설치가 필요합니다.  
> Git 설치파일을 [다운로드](https://git-scm.com/) 받아 Next 쭈~~~~~~욱 눌러 설치합니다.

![01](assets/images/git_for_androidstudio_student/슬라이드1.PNG)  
<br><br>
![02](assets/images/git_for_androidstudio_student/슬라이드2.PNG)  
<br><br>

## Base Project 만들기
 
## Clone Project

## Git 사용시 주의사항

1. Git/Github가 익숙하지 않을 때는 팀원끼리 충돌을 피하기 위해 다른 파일을 작업하길 권장합니다.
2. 같은 파일에 기능을 개발해야하는 경우 소스코드를 건드리는 작업 날짜나 시간을 다르게 합니다.
3. Git/Github가 익숙해지면 충돌을 조금씩 경험해봅시다.
4. 인쌤tv [Github 사용법](https://www.youtube.com/watch?v=8gyquB3VNNs) 영상에 충돌 상황 설명이 있으니 참고하세요.
5. 항상 Commit(1번) > Pull(2번) > Push(3번) 우선 순위를 기억하세요.  
6. Pull을 할경우 현재 내 작업물 Commit을 먼저해야합니다.
7. Push를 할경우 Github에서 Pull을 먼저 진행해야 합니다.

## Git user 정보 수정하기

> Git 정보를 이전에 입력 했거나 잘못입력해서 변경하고 싶은 경우 Git bash에서 아래 명령어를 입력합니다.  
> Git 설치 폴더로 이동하면 Git bash 프로그램을 실행 할 수 있습니다.

- Git 사용자 정보 확인
  - git config --global user.name
  - git config --global user.email

- 기존의 Git 사용자 정보 삭제
  - git config --global --unset user.name
  - git config --global --unset user.email

- 새로운 Git 사용자 정보 추가
  - git config --global user.name "새로운 사용자 이름"
  - git config --global user.email "새로운 이메일"
