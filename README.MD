# UI 구현(화면구현) 프로젝트

## 2020-07-27

#### HTML (Hyper Text Markup Langu.)

* Tag를 사용하여 문서를 작성하는 문서 작성용 언어

* Mark Down : git의 README.md 와 같은 문서를 만들때 
  			  Tag가 아닌 특수문자(#, *)를 이용해서 문서를 꾸미고
  			  모양을 만드는 문서작성용 언어

* Mark Up : 시작 Tag "<tag> TEXT </tag>"를  이용하여 문서를 감싸서 문서를 꾸미고 
			모양을 만드는 문서작성용 언어

* XML : Tag에 사용되는 키워드를 임의로 만들수 있다.

* HTML : tag에 사용되는 키워드가 정해진 것을 사용한다.



#### index.html

*  일반적으로 홈페이지, 웹페이지라고 부르는 Browser를 통해서 접근하는 프로젝트에서 제일먼저 만나게 되는 파일

* index page, Langding page, Parking page 등으로 부른다. (시작 페이지 라는 용어가 알맞는 말이 된다.)

* http://naver.com/  라고 Browser 주소창에 입력을 하면 htttp://www.naver.com/index.html 이라고 입력한 것과 같다.


#### HTML의 box Model

* HTML의 Tag를 Box Model로 분류하면 block, Inline으로 분류할수 있다.

* Block : content의 길이에 관계없이 화면의 왼쪽끝에서 오른쪽 끝까지를 역역으로 사용하는 tag

* Inline : 여러가지 tag로 묶인 Content가 가로 바얗ㅇ으로 나열되어 표현될수 있다.
		   Inline tag는 문자열 중간에 있는 단어들의 모양, 색깔등을 바꾸는 용도부터 다양한 용도로 사용이 된다.


#### HTML의 Selector

* tag : HTML에서 사용하는 모든 tag를 Selector Tag라고 한다.

* 선택자(Selector) : HTML문서내에서는 tag라고 불리우는 요소들이 style과 관련된 부분이 적용되면 tag selector라고 부른다.

* CSS(Cascading Style Sheet)를 사용하여 html문서에 디자인적인 기능을 추가한다.

####  HTTP : Hyper Text Transfer Protocol

* HTML (Hyper Text Markup Lang.)로 만든 문서파일(정보)을 인터넷을 통해서 주고 받을때 사용하는 보편적인 프로토콜

* 모든 내용을 평문(암호화 되지 않은)으로 주고 받는다.

* 사용자가 Web Browser를 통해서 서버에 요청(request)를 수행하면 서버는 사용자의 요청을 분석하여 여러가지 처리를 수행한 후
  그 결과를 HTML 방식의 코드로 만들어서 응답(Response) 하는 구조로 만들어진 프로토콜

* 인터넷 서비스 중에서 www(World Wide Web) 환경에서 사용되는 보편적인 프로토콜이다.


#### https : Hypser Text Transfer Protocol Secure Socket Layer

* http 프로토콜에 암호화 기능을 추가하여 Request, Response 되는 정보를 암호화 하여 전송한다

* https를 프로토콜로 사용하게 되면, 로그인, 회원가입시 입력한 정보가 암호화 되어 어느정도 보안상 안전을 보장한다.


#### 인터넷에서 port 개념

* 한개의 IP 주소를 가진 서버 클라이언트(PC)는 1:1 연결만을 지원하는 체계이다

* 인터넷을 통해서 사용할수 있는 서비스는 그 종류가 매우 다양하여 1개의 IP에서 1개의 서비스만을 사용하는 것은 매우 낭비가 된다.

* OSI 7Layer에서 Layer3인 네트워크 계층에서는 1개의 IP로 1개의 연결을 허용하도록 하괴 Layer4인 전송계층에서는 Port라는 개념을 사용하여
  여러가지 서비스를 1개의 IP주소에서 사용할수 있도록 만들어 놓은 개념

* TCP/IP 프로토콜 OSI 7 Layer 에서 Layer3와 Layer4를 사용하는 인터넷 프로토콜 규격이다.





