<h1>AJAX</h1>

<li>AJAX란 비동기 자바스크립트와 XML (Asynchronous JavaScript And XML)을 말합니다. 간단히 말하면, 서버와 통신하기 위해 XMLHttpRequest 객체를 사용하는 것을 말합니다. JSON, XML, HTML 그리고 일반 텍스트 형식 등을 포함한 다양한 포맷을 주고 받을 수 있습니다. AJAX의 강력한 특징은 페이지 전체를 리프레쉬 하지 않고서도 수행 되는 "비동기성"입니다. 이러한 비동기성을 통해 사용자의 Event가 있으면 전체 페이지가 아닌 일부분만을 업데이트 할 수 있게 해줍니다.</li>
<li>AJAX의 주요 두가지 특징은 아래의 작업을 할 수 있게 해줍니다.</li>
<li>페이지 새로고침 없이 서버에 요청</li>
<li>서버로부터 데이터를 받고 작업을 수행</li>

<hr>
           
<li>TYPE : GET이나 POST같은 HTTP METHOD를 나타낸다.</li>
<li>URL : 컨트롤러에서 대기중인 URL주소</li>
<li>DATA : 전송할 파라미터</li>
<li>DATATYPE : 받아올 데이터 타입(생략가능), HTML, JSON, XML 등 가능</li>
<li>SUCCESS : 성공시에 수행할 핸들러를 받는다 리스폰스로 내가원하는거 받을수있음</li>
<li>ERROR : 실패시 수행할 핸들러를 받는다.</li>
