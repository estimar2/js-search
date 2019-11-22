# JS-SEARCH

<pre>콤보박스(설렉트박스)에 있는 값을 선택하면,
해당 이름(케릭터 이름)이 가지고 있는 정보를 화면에 보여준다.
</pre>

- [x] selectbox
- [x] setting value in selectbox
- [x] onchange => info view

# how to git use connection repository ay local repositry

1. git init

   <pre>
   현재 폴더에서 git을 시작한다.
   </pre>

2. git config --global user.name "사용자이름"
   git config --global user.email "깃허브 이메일"

   <pre>
    만약 로그인이 안되어있다면 git bash에서 해당 명령어를 통해 로그인
    한번 실행하면 다음부턴 실행할 필요 없음
   </pre>

3. git remote add origin [깃 레파지토리 URL]

   <pre>
    git init이 된 폴더에서 해당 명령어를 실행하면, 깃 레파지토리와 내 컴퓨터의 폴더가 연동된다.
   </pre>

4. git add .
   <pre>
       현재 폴더의 모든 파일을 추가한다. 
       만약 특정 파일만 추가하고싶으면 . 대신 파일명
   </pre>

4-1. git status

<pre>
  현재 폴더의 깃 상태를 볼 수 있다.
</pre>

5. git commit -m "메세지"

   <pre>
     스테이징에 업로드 (가상공간) 하며, 코멘트를 달아준다.
   </pre>

6. git push origin master
   <pre>
       스테이징에 올라간 파일을 깃 레파지토리에 업데이트 한다.
   </pre>
