# TIL
- 당일 학습한 내용을 정리합니다.

## 2023-03-27
- git bash 설치
- 기초 리눅스 명령어
- vim 사용법

## 2023-03-28
- commit
    - 개념
    - 커밋을 어떻게 만드는지
    - 커밋 크기
- 저장소
    - 개념
    - 일반 폴더와 저장소의 차이
    - 'git init' 명령어로 저장소 만들기

## 2023-03-29
- 커밋 만들기
    - `git commit -m`
- 스테이징 영역
    - `git add` 명령어로 커밋에 포함시키고 싶은 파일만 스테이지 영역에 추가

## 2023-04-29
- github를 통해 협업공간 생성

## 2023-04-30
- git 명령어 복습
    - `git init` : 로컬 저장소 만드는 깃 명령어

    - `git status` : 현재 폴더에 있는 파일들을 확인, 초기에는 파일들이 빨간색으로 되어있으나 add하게 된다면 녹색으로 변함

    - `git add` : 로컬 저장소와 원격저장소 중간 단계인 스테이징 영역에 올려주는 명령어

    - `git commit -m "메세지"`(=git commit --message " ") : 커밋 메세지 입력 

    - `git remote add origin [레포지토리 주소]` : 레포지토리 주소(원격 저장소)
    와 로컬 저장소를 연결해주는 명령어, 긴 레포지토리 주소를 origin이라고 부름으로써 로컬 저장소와 원격 저장소를 연결해주겠다는 의미

    - `git remote -v` : 연결된 레포지토리(원격저장소) 주소 확인

    - `git push origin main(브랜치명)` : main branch에 커밋이력을 push하는 것

    - `git branch -M main` : 로컬 저장소 master를 main으로 변경

    - `git push -u origin main` : u를 붙이는 이유는 원격저장소에 main 
    branch가 없는 경우 알아서 main branch를 만들어서 push해줌
    
- VIM EDITOR
    - `w` : 저장
    - `q` : quit
    - `wq` : 저장하고 quit

## 2023-05-01
- bash 터미널에서 브랜치 만드는 법
    - `git branch [만들고 싶은 브랜치명]` : 브랜치 생성
    - `git checkout [만든 브랜치명]` : 해당하는 브랜치로 이동
    - `git push origin [만든 브랜치명]` : 해당 브랜치로 커밋이력 푸쉬
    \* __먼저 커밋을 하고 브랜치를 만들어도 상관없다!__

## 2023-05-02
- pull 명령어 : 원격 저장소로부터 변경사항을 로컬저장소로 가져옴
    - `git pull [remote] [branch]` = `git pull origin main`

## 2023-05-03
- 프로젝트에 DB 구축하기 => SQLite