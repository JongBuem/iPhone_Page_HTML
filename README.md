# iPhone_wab

1. HTML Editor 설치 및 파일생성      

       HTML Editor 중 https://atom.io/ 에서 atom Editor 설치후 파일을 저장할 폴더를 생성
       atom Editor 상단 메뉴중에서 file중 open folder를 선택하여 생성한 폴더를 선택합니다.
       atom Editor 창이 두개로 나누어 지면 좌측 생성폴더를 우클릭하여 파일을 생성합니다.
       웹페이지에서 [Ctrl + o]로 생성한 파일을 간단하게 열어볼 수 있다.



2. tag       

       1. html : head 와 body는 고위 tag이지만 이둘을 담는는 최고위직 tag이다.  [!DOCTYPE html] : html 가장상단에 관용적으로 작성
       2. head : 본문내용을 설명하는 title 과 meta를 담고있음
       3. title : 웹페이지의 제목을 결정 하는 본문의 설명                       <title> 아이폰 </title>
       4. meta : 문자규칙을 결정                                               <meta charset ="utf-8">
       5. body : 웨페이지의 본문내용을 담는다                                   <body> 페이지에 표현되는 내용 </body>
       6. ul : li의 부모 tag로서 수많은 리스트를 구분하기 위해서 많이사용된다     <ul> <li> ~ </li> </ul>
       7. ol : li의 또다른 부모 tag로서 수많은 리스트의 번호를 순서대로 부여함    <ol> <li> ~ </li> </ol>
       8. li : 목차 or 리스트를 나타냄 [예 : ● a ]                              <li> 리스트 </li>
       9. p : 하나의 단락을 나타내고 단락의 위아래로 줄을 띄운다                  <p> 작성내용 </p>
       10. br : 작성부분의 줄을 띄운다                                          <br>
       11. u : 문자에 밑줄 긋기                                                 <u> 밑줄그을 문자 </>
       12. strong : 문자를 강조한다                                             <strong> 강조할 문자 </strong>
       13. h1 ~ h6 : 제목을나타내는 tag이다. 숫자가 클수로 문자는 작아진다        <h1> 제목 타이틀 강조 </h1
       14. img : 이미지 삽입                                                   <img src="이미지이름.jpg" width="사이즈">
       15. a : 문자의 링크를 건다                                               <a href="링크주소"> 링크를 걸 문자 </a>
           <a href="링크주소" target="_blank"> 링크를 걸 문자 </a> : 새탭으로 열기
           <a href="링크주소" title="문자"> 링크를 걸 문자 </a> : 커서를 대면 툴팁이 발생
           <a href="링크주소" target="_blank"> <img src="이미지이름.jpg" width="사이즈"> </a> : 사진클릭시 링크로 이동
       16. ??          
        
        
        
          
3. 웹서버에 연결

       생성한 파일을 통해서 웹사이트를 운용할 수 있도록 웹서버를 제공하는 github를 이용합니다.
       https://github.com/ 에서 제작한 html파일들을 upload하여 등록이후 설정에서
       GitHup Pages의 항목을 branch로 바꾸어서 저장하면 제작한 웹사이트에대한 주소를 부여 받는다.
       
       



