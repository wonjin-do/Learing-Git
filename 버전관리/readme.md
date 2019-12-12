Working Tree / Stage Area / repository
~~~
git config --global core.editor "vim" //커멧메세지 작성때 기본 에디터 설정
git init .
nano hello1.txt
ctrl + X + enter로 저장하고 나오기
cat hello1.txt

//커밋전
git status //StageArea 상태를 보여줌
git add hello1.txt //stageArea로 이동
git diff //파일을 수정해서 변경사항이 생기면 이 명령어로 확인함. 사항을 상세하게 + , - 로 설명

//커밋
git commit -m "Message1"
git commit -am "Message" //add도 동시에 해결함.(단, 커밋된적 없는 파일은 직접 add해줘야 함)

//커밋이후
git log //단순 커밋기록
git log --stat //몇줄이 수정되었나 (간략)
git log -p //수정사항 상세확인(자세함)

//시간여행
git log를 통해 버전ID를 구한다.
git checkout 버전ID
git checkout master

//



git reset --hard //이전 버전으로 이동

~~~
