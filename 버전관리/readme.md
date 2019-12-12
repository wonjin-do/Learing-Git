Working Tree / Stage Area / repository
~~~
git init .
nano hello1.txt
cat hello1.txt

//커밋전
git status //StageArea 상태를 보여줌
git add hello1.txt //stageArea로 이동
git commit -m "Message1"
git diff //파일을 수정해서 변경사항이 생기면 이 명령어로 확인함. 사항을 상세하게 + , - 로 설명

//커밋이후
git log //단순 커밋기록
git log --stat //몇줄이 수정되었나 (간략)
git log -p //수정사항 상세확인(자세함)


git reset --hard //이전 버전으로 이동

~~~
