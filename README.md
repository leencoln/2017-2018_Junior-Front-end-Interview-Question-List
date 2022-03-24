# 2017-2018_Junior-Front-end-Interview-Question-List
2017 - 2018 신입 개발자 면접 질문 모음

## 설명
 개발자 준비를 하면서, 면접에서 개별적으로 혹은 공통적으로 받았던 질문 리스트입니다. 주로 로켓펀치와 원티드를 통해 구직활동을 하였으며, 당연히 비율상 규모가 큰 기업 보다는 스타트업 위주로 면접이 진행되었습니다. 서류를 제출한 모든 기업으로부터 면접이 진행되지 않아, 질문 내용이 보편적이지 않을 수 있습니다. 자바스크립트를 활용한 웹 프론트엔드 직군 위주로 지원하였으며, 포트폴리오 제작시 Vue.js만을 사용하여, React.js 관련 질문은 받지 못하였습니다. 비전공자임을 감안한 질문 내용들이 있습니다.

## 질문 목록

### 개발 관련 질문 목록

* 브라우저의 렌더링 과정에 대해서 상세하게 설명해달라

* OOP
    * OOP에 특징에 대해 설명해달라(상속, 캡슐화 등등...)
    * 현실에 상황을 예로 들어 OOP의 개념으로 설계과정을 설명해달라  
        ex) 축구를 게임으로 만든다거나, 기타 어떠한 상황이라도 좋다

* 함수형 프로그래밍(Function Programming)
    * 함수형 프로그래밍에 대해 설명해달라
    * 함수형 프로그래밍에 개념에서 순수함수란 무엇인가
    * OOP와 함수형 프로그래밍의 가장 큰 차이점은 무엇인가

* 비동기 프로그래밍(Asynchronous)
    * AJAX란 무엇인가
    * Promise란 무엇이며 코드가 어떻게 구성되어있는가
    * Promise와 Callback의 차이점은 무엇이며 각각의 장단점에 대해 설명해달라
    * Async, Await를 무엇이며, 사용해본 경험이 있는가

* Vue.js
    * 면접관을 Vue.js 비사용자라고 가정하고 Vue.js에 설명하고 장단점을 말해달라
    * Vue.js의 Life-cycle에 대해 아는대로 말해달라
    * Vue.js 에서 DOM은 어느 시점에 생성되나
    * Computed와 Methods의 차이점은 무엇인가
    * 가상돔(Virtual DOM) 개념은 무엇이며, DOM과의 차이점 가상돔의 개념이 사용되게된 배경은 무엇인가
    * 최근의 프레임워크를 사용할때 외부 라이브러리와의 결합시에 더 나은 코드 작성법을 고민해본적이 있는가
    * DOM을 직접 조작하는 D3.js 같은 라이브러리와의 결합시에 예상되는 문제점이 있는가

* AMP
    * AMP의 개념은 무엇이고 기존의 것에 비해 장점은 무엇인가
    * 최근의 프레임워크들과의 조합을 고려해 본적이 있는가 ex) vue-amp..

* 타입스크립트를 사용해본 경험이 있는가, 타입스크립트에 대한 본인의 생각과 도입시의 장점을 말해달라

* 자바스크립트의 원시 타입(Primitive Data Type)은 몇가지이며, 전부 말해달라  
    Number, String, Boolean, Null, Undefined, (Symbol)

* 자바스크립트의 Number Type은 다른 언어들과 차이점이 무엇인가, 왜 하나만 존재하는가

* 실행 컨텍스트(Execution Context)에 대해 설명해달라

* 자바스크립트의 호이스팅(Hoisting)은 어떻게 이루어져 있는가

* 클로저(Closure)란 무엇이며, 왜 이러한 패턴을 사용하는가

* This
    * 자바스크립트에서 This는 몇가지로 추론 될수 있는가, 아는대로 말해달라
    * Call, Apply, Bind 함수에 대해 설명해달라

* ES6
    * 크롬 정도의 브라우저를 제외하곤 ES6 스펙에 대한 지원이 완벽하지 않다. 해결방법은 무엇인가
    * Babel의 기능을 한 단어로 말해달라
    * ES6 에서 추가된 스펙에 대해 아는대로 다 말해달라(let, const, rest parameter, class, arrow function...)
    * var 와 let, const의 가장 큰 차이점은 무엇인가 (function scope와 block scope의 개념에서)
    * Class 는 무엇이고, Prototype, fucntion의 ES5 스펙만으로 Class를 구현할수 있는가

* 자료구조(Data Structure)
    * 자료구조에 대해 공부한 적이 있는가 
    * Binary Search Tree 에 대해 알고 있는가, 설명해달라
    * Graph 에서 다른 노드를 참조하는 구조를 코드로 구현 할수 있는가

* RESTful API 가 무엇인가, 아는대로 다 말해달라

* 클라이언트 개발시 보안 관련 이슈
    * 보안은 서버쪽에서 많이 신경쓰고 있지만, 프론트엔드 개발에서 보안관련 이슈는 어떠한 것들이 있는가
    * Wireshark 에 대해 알고 있는가
    * HTTP 통신의 문제점에 대해서 아는대로 말해달라
    * CORS(Cross-Origin Resource Sharing)는 무엇인가 왜 이러한 방법이 정의 되었으며, 본인이 코드를 작성하면서 CORS와 관련하여서 경험하였던 이슈는 무엇인가
    * 간단한 데이터를 클라이언트로만 관리 할수 있는가, 이와 관련해서 브라우저 에서 어떠한 것들을 지원하고 있는가, 예를 들면 소셜 로그인같은 것들에 대한 브라우저 종료시 발생하는 문제에 대응 경험이 있는가

### 개발외 질문 목록

* 왜 개발자가 되려고 하는가

* 개발자로서의 본인의 비전을 이야기 해달라

* 비전공자로써 갖고 있는 컴플렉스가 있는가

* 운영체제같은 컴퓨터공학(cs)에 대한 기초지식이 있는가

* 최근에 관심갖거나 공부 하고 싶은 개발 기술은 무엇인가

* 프로젝트 협업 과정을 경험한 적이 있는가

* 공부 방법
    * 개발자가 되기 위해서 어떻게 공부하였는가
    * 학습시 주로 이용하는 웹페이지나, 동영상 강좌 페이지는 어디인가
    * 최근의 읽은 개발 관련 서적은 무엇인가
    * 즐겨 보는 개발 관련 유튜브가 있는가
    * 회사 기술 스택에 맞추어 단기간 내에 언어와 프레임워크를 학습 하여야 할 때, 어떻게 공부하고 해결할 것인가

* 포트폴리오 제작시에 비인기 라이브러리를 사용한 경험이 있는가
* 이러한 비인기 라이브러리에 대한 정보를 어디서 얻는가 왜 활용하였는가

### 인터뷰 진행하면서 느낀점(지극히 주관적) - TIP

* 포트폴리오로 제출한 코드를 유심히 보는 면접관은 많지 않다

* 마찬가지로 코드의 결과물을 최종 빌드하여 결과물을 보는 면접관은 더욱 드물다  
    (깃허브에 결과물의 메인페이지라도 캡쳐해서 올려놓는걸 추천합니다)

* 로켓펀치와 원티드를 기준으로 구체적인 통계를 내보지 않았지만, 신입보다 경력직을 훨씬 선호한다

* 채용공고 검색시에 신입, 경력 가리지 말고 본인이 관심 있는 기술을 사용 하고 있는 회사, 배우고 싶은 기술을 채택하고 잇는 회사에 이력서를 꼭 내자 (퇴짜 맞아도 앞으로 볼 일 없다)

* 본인이 부족하다고 생각하여도 보유 스킬을 최대한 적어내야한다  
    (면접관이 질문할게 없으면 나한테 질문하라고 하는데 이것 또한 난감하다)

* 면접전에 지원회사의 서비스를 보고가야한다. 합류시 자사의 서비스 중 개선하고 싶은점과 서비스에 대해 평가를 해달라고 말하는 경우가 종종 있었다.

* 모르는 것을 아는 것 처럼 이야기 하지도 말고, 지나치게 솔직하게 이야기 하지도 말자  
    (면접을 다니면서 초기에 본인은 두 가지 다 문제가 되었고, 면접관들에게 지적받고 주의하게 되었다)  
    ex) CORS 관련 질문을 받았을때, Quota (API 사용량 제한)등을 설명하면서 올바른 답변을 하지 못해 면접후에 메일로 피드백 받은 경험이 있다.

* 일부 회사 인터뷰 진행시, 채용과 별도로 면접관의 면접관련 경험을 위해 면접을 본다는 느낌을 받은 적이 있다  
    (면접관이 책임자직급에서 멀어질수록 그럴 확률이 있다)

* 포트폴리오를 깃허브에 업로드시 코드가 허접하더라도 README.md를 자세히 작성하여야 한다


### 개발 인터뷰 관련 링크

* 브라우저는 어떻게 동작하는가? http://d2.naver.com/helloworld/59361

* 최신 웹사이트와 꼼꼼한 개발자들을 위한 완벽 프론트엔드 체크리스트 https://github.com/kesuskim/Front-End-Checklist

* 예비 개발자들의 기술 면접 준비를 위한 자료 https://github.com/JaeYeopHan/Interview_Question_for_Beginner

* 프론트엔드 인터뷰 핸드북 https://www.frontendinterviewhandbook.com/

* Awesome Interview Questions https://github.com/MaximAbramchuck/awesome-interview-questions

* 프론트엔드 면접 문제 은행 https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/main/src/translations/korean
