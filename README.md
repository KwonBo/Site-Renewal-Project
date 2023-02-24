# Site-Renewal-Project
회사 사이트 리뉴얼 프로젝트 과정 중 생기는 고민과 배우는 것들을 저장하는 repo입니다.

<h1> 고민 사항 </h1>
- 백엔드를 개발하는 데 사용 가능한 다양한 프레임워크 중 어떤 것을 사용해야 할까?
<br>
-> 현재 가장 익숙한 언어인 python 기반의 프레임워크이고, 가볍고 빠른 fastapi를 사용할 것 같음.
<br>
<br>
</br>
- fastapi에서 HTML파일을 response하는 것은 성공했으나 CSS가 적용되지 않음. static 폴더를 활용해야 할 것 같은데 어떻게 사용하는 걸까?
<br>
-> static 폴더를 만드는 것 까지는 맞았다. 하지만 당연한 것을 놓쳤었다. HTML 페이지 내에서 css 파일의 위치가 저장된 디렉토리를 명시하는 데 static 폴더 안 css 파일의 위치를 정확하게 명시해주지 않아서 적용이 안됐던 것이었다.
<br>
<br>
</br>
- html파일에서 href를 통해 다른 html로 넘어가는 것과, fastapi의 url을 통한 response로 다른 페이지로 넘어가는 것은 완전히 다른 작동 방식인가?
<br>
<br>
</br>
- fastapi로 html을 response할 때, 여러 개의 html을 연결시켜서 하나의 페이지처럼 response 하는 방법은 무엇인가?
<br>
-> Jinja의 template 기능을 import 해서, 미리 만들어놓은 header.html을 다른 html파일에 상속할 수 있다.
