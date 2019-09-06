# ai-security
2019 인공지능과 보안 실습

## 본명으로 개인 폴더 만들기
````
    #자신의 작업환경으로 이동
    cd ~/workspace

    #조교 github clone
    git clone https://github.com/tjdghks994/ai-security.git

    #조교 github 폴더로 이동
    cd ai-security

    #폴더 만들기
    mkdir 이름
    ex. mkdir parksunghwan

    #개인 폴더로 이동
    cd 이름

    #개인 폴더에서 작업 시 branch 만들기
    git branch 브런치이름
    git checkout 브런치이름
    
    #작업물을 github에 push하기
    git commit -m "어떤 작업을 했는지 작성"
    git push origin 브런치이름

    #자신의 commit을 조교에게 전달
    github 접속
    조교 repagitory에 접속
    pull requests에 접속
    commit이 잘 되었다면 compare & pull request 버튼이 활성화 될 것임
    클릭 후 create pull request
````

## 아나콘다 기초 설정
````
    #아나콘다 업데이트
    conda update conda

    #가상환경 생성
    conda create --name 가상환경이름 설치할 패키지
    ex. conda create --name test python=3.7

    #가상환경 확인
    conda info --envs

    #실행
    conda activate test

    #실행 종료
    conda deactivate````

