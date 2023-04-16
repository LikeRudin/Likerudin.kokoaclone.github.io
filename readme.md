1. 01 이미지: 웹페이지 접속했을떄 사라졌다 다시 나타나는 효과
2. 02 이미지: welcome to kakaotalk

개념

.gitignore 파일 : 깃허브에 업로드하고싶지 않은 파일

index.html으로 명명하는 이유: index는 처음에나오는것, first를 의미한다.

클래스 이름을 짓는법

class="column"은 너무 제네릭이다.
되도록 긴 클래스네임을 지어주자.

status-bar\_\_column 은 하나의 클래스이름

status-bar column 은 두개의클래스이름.

class나 id 속성을 지정할때는 내가 과연 해당 태그를
프로젝트안에 몇개나 넣을지 생각해야한다.
적으면 id 많으면 class

문제
link 태그로 css 폴더를 연결할때

/css가 아니라 css로 시작해야한다.

1. 컴포넌트를 중앙에 옮기고싶을때,
   display:flex;
   justify-content: center;

2. 컴포넌트끼리의 줄을 맞춰주고 싶을때,
   display:flex;
   align-items: center;

3. default 값을 원할때
   reset.css를 다운받자.
   브라우저에의해 자동으로적용되는 스타일을 없애준다.
   margin, padding 등등을 전부 0으로 만들어준다.
   이후 a 태그의 효과제거등등 default 로 만들어주고픈속성은
   전부 reset.css에 저장하자.

4. css 파일을 여러개로 분할하였을때,
   html에 link 태그를 여러개 만들어서 각각의 css파일을 연결해준다.
   혹은 하나의 연결된 css파일에 @import "다른css파일"; 코드를 추가해준다.

5. 어떤 상자의 한쪽 면만 표현하고싶을때,
   아예 투명하게 정의해버린다음, 해당하는 면의 border만 다시 재설정해준다.

6. form 의 atturibute 소개
   A. action: where to send data
   B. method: Post Get / Http 메서드

7. badge.css의 분리
   nav\_\_notification 과 "position: absolute;"를 제외하고
   전부 같은 속성을갖는 화면구성물들이있다.

A. badge.css 파일을 만든다.
B. 공통속성을 공유할 class를 정의한후 nav\*\*notification 고유속성만 남긴후 나머지를 전부 해당 class의 css 코드로 옮긴다.
C. nav\_\_notification에 해당 class를 추가해준다.
D. html 문서의 link 태그에 저장된 main 링크에
@import "components/badge.css" 를 추가한다.

요약 : 1. 공통점을 찾아, 새로운 파일과 클래스에 분리해낸다. 2. 분리전 요소들의 css코드는 고유속성만 제외하고 전부 지운다. 3. 해당 요소들에 새로운 클래스코드를 추가해준다. 4. css파일을 연결해준다. (link태그 추가or css 내부 @import)

8. 자주 쓰는 변수가있다면 variable.css 파일에 분류해낸다
   색깔, border 설정등, 다양한 변수를 설정하라.
   Nadiinko
   <a href="https://www.flaticon.com/free-icons/id" title="ID icons">ID icons created by Cursor Creative - Flaticon</a>

<a href="https://www.flaticon.com/free-icons/invitation" title="invitation icons">Invitation icons created by Freepik - Flaticon</a>

<a href="https://www.flaticon.com/free-icons/platypus" title="platypus icons">Platypus icons created by Eucalyp - Flaticon</a>

<a href="https://www.flaticon.com/free-icons/calendar" title="calendar icons">Calendar icons created by srip - Flaticon</a>

<a href="https://www.flaticon.com/free-icons/emotions" title="emotions icons">Emotions icons created by juicy_fish - Flaticon</a>

<a href="https://www.flaticon.com/free-icons/user" title="user icons">User icons created by Freepik - Flaticon</a>

<a href="https://www.flaticon.com/free-icons/privacy" title="privacy icons">Privacy icons created by deemakdaksina - Flaticon</a>
