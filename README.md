# devsetup-e11
E1-1 Dev Environment Setup




# E1-1 내 컴퓨터에 개발자용 작업실 꾸미기

## 프로젝트 개요
터미널, Docker, Git이라는 개발자 필수 도구 3종을 직접 세팅하며, 현대적 개발 워크플로우의 기반을 다집니다. 단순한 명령어 복사-붙여넣기가 아닌, 실행 결과(로그/데이터)를 통해 시스템의 동작 원리를 검증하는 데 집중합니다.

## 프로젝트 학습 목표
- Linux CLI 숙달: 주요 명령어 CMD, 절대/상대 경로 구분, 파일 권한(755, 644) 체계 이해
- Docker 컨테이너화: Dockerfile을 활용한 커스텀 이미지 빌드 및 실행 환경 격리
- Docker 네트워크 및 저장소: 포트 매핑의 필요성 인지 및 Docker 볼륨을 통한 데이터 영속성 확보
- 버전 관리: Git(로컬)과 GitHub(원격)의 역할 차이 명확화



## 수행 체크리스트
- [ ] a. 실행환경
- [ ] b. 터미널 기본 조작 및 폴더 구성
- [ ] c. 권한 변경 실습
- [ ] d. Docker 설치/점검
- [ ] e. hello-world 실행
- [ ] f. Dockerfile 빌드/실행
- [ ] g. 포트 매핑 접속(2회)
- [ ] h. 바인드 마운트 반영
- [ ] i. 볼륨 영속성
- [ ] j. Git 설정 + VSCode GitHub 연동

<br>

## a. 실행환경
- OS: Ubuntu 26.04.1 LTS
- Shell: Bash
- Docker: version 29.9.3
- Git: version 2.53.0

<br/>

```bash

# Ubuntu 버전 && Shell 종류 && Docker 버전 && Git 버전 확인 CMD
$ lsb_release -d && echo $SHELL && docker --version && git --version

# 실행환경 출력값
Description:    Ubuntu 26.04.1 LTS
/bin/bash
Docker version 29.9.3, build 5457199
git version 2.53.0
```

![테스트 실행 결과](./screenshots/a-devenv.png)




## b. 터미널 기본 조작 및 폴더 구성

```bash
$ PS1="$" # ID익명화
$ cd ~ 
# User's Home Folder 디렉토리로 이동 (/home/username)
$ cd .. # User Home 상위 폴더인 Home 폴더로 이동
$ pwd # 현재 작업 폴더인 Home 출력
$ cd ~/projects   
 / 목록 (숨김포함) / 이동 / 생성 / 복사 / 이동 및 이름변경 / 삭제 
# test.txt 새 파일 생성 / 'hello world' 텍스트 삽입; 'hello world' 텍스트 내용 출력 확인







```













## c. 권한 변경 실습

```

```



## d. Docker 설치/점검

```

```


## e. hello-world 실행

```

```



## f. Dockerfile 빌드/실행

```
```



## g. 포트 매핑 접속(2회)

```
```



## h. 바인드 마운트 반영

```
```



## i. 볼륨 영속성

```
```


## j. Git 설정 + VSCode GitHub 연동

```
```



