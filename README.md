# **Github 연동 방법**
> 간단하게 Github 연동방법을 알아보자
---
1. **코드를 작성하고 저장한다**

> vscode를 실행하여 코드 작성 이후 저장한다.

2. **git을 실행하고 아래의 명령어를 입력한다.**

> git remote add origin https://github.com/namteasueng/gitTest.git  

3. **저장한 코드를 푸시하기 위해 아래의 명령어를 입력한다**
> git push -u origin master
4. **이후 연동된 코드를 확인하고 프로그램 및 웹을 종료한다.**
> 한번 연동이 된 파일의 코드는 수정 이후 아래의 명령어를 입력한다
>> git add **파일명**  
>> git commit -m "msg"  
>> git push origin master
