# Git 명령어

## Git 로컬 컴퓨터에 사용자 등록하기

- git config --global user.name "park097"
- git config --global user.email "alslalslclq24@naver.com"

## Git 시작하기

- git init //폴더관리 //처음 사진
- git add .gi //변경된 애들을 사진을 찍는 거
- git commit -m "최초커밋" //하드디스크에 영구히 보존하다 (commit) //커밋만 하면 어디로든 돌아갈 수 있다. //파일 하나로

## Github 업로드하기

- git remote add origin 주소
- git push origin master

## 다시 업로드 법

- 소스코드 변경
- git add . //.은 전체를//
- git commit -m "변경내용적고"
- git push origin master

## 잘안될때 해결법

- git remote -v
- git remote rm origin

## 깃헙 소스코드 다운로드 하는 법

- git clone 주소
