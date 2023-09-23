### 💬 About ME

- 안녕하세요. 데이터 엔지니어 한기호입니다.
- 내가 아는 것을 상대방에게 쉽게 알려주는 것을 좋아합니다.  
- 맡은 것을 끝까지 완료해서 함께 일하고 싶은 사람이 되려고 합니다.

### 🌱 Soomers Blog



    <table>
        <tbody>
            <tr>
            <td>
        <a href="https://soomers.tistory.com/155">
            <div>2023. 9. 21.</div>
            <img width="100%" src="img/2NEuVkFdDdzyRP5NtPEViK"/><br/>
            <div>[네트워크] 네트워크의 데이터와 생성과정</div>
        </a>
        <div>목차 1. 네트워크의 데이터 2. 생성과정 3. 용어정리 1. 네트워크의 데이터 - 네트워크의 데이터를 부르는 용어는 각 계층 별로 패킷, 프레임 등 다양하다. - TCP/IP 모델을 따를 때, 응용 계층은 Stream, 전송계층은 Segment, 인터넷 계층은 Packet, 네트워크 접속계층은 Frame이라 한다. 2. 생성과정 - 먼저 데이터를 보낼 때는 계층이 높은 순에서 낮은 순으로 데이터를 감싸면서(캡슐화) 도착지에 전송되고, 도착지에서는 반대로 낮은 계층에서 높은 계층으로 데이터를 풀어서(역캡슐화)를 진행하여 데이터를 받게된다. - 파일은 쓰일 때마다 용량이 늘어나게 되고, 이러한 파일을 보내려면 Socket을 사용하여 데이터를 전송한다. 이 때의 데이터를 Stream이라고 한다. 그런데 이 ..</div>
        </td><td>
        <a href="https://soomers.tistory.com/154">
            <div>2023. 9. 21.</div>
            <img width="100%" src="img/08jJxQvCbrcwMWgPWPCsb1"/><br/>
            <div>[네트워크] Web과 HTTP프로토콜</div>
        </a>
        <div>웹이란? - 팀 버너스 리가 만든 네트워크 생태계이다. - 특정 논문의 마지막 "참고 문헌"을 손쉽게 찾기 위해서 문서에 "링크"개념을 도입한 HTML 문서를 만듬 - HTML문서를 전세계와 연결하기 위해서 HTTP프로토콜을 구상 HTTP 프로토콜의 특징 - Client / Server 구조로 요청하면 응답이 오는 데이터를 주고받는 프로토콜임 - HTTP 프로토콜은 Stateless, 즉 상태를 저장하지 않음 - 위 Stateless라는 특징 때문에 웹에서 특별히 처리해야만 일이 발생함 (ex,로그인과 같은 문제) HTML문서를 주고 받는 과정 [ HTML 문서만 주고 받을 때 ] [Client] http프로토콜은 여러 Method 중에 기본적으로 get 요청을 하게 되는데, 이때 URI(Uniform ..</div>
        </td><td>
        <a href="https://soomers.tistory.com/153">
            <div>2023. 9. 21.</div>
            <img width="100%" src="img/D01mcaSmt3cCcR5hQ6i0f1"/><br/>
            <div>[네트워크] IP와 식별자</div>
        </a>
        <div>IP란 - 인터넷 프로토콜, 호스트의 주소로 기능함 - IPv4주소는 network주소와 호스트 주소로 나누어져 있고, 서브넷 마스크를 통해 구분할 수 있음 - 서브넷 마스크란 네트워크 주소와 호스트 주소를 분리 하는 역할을 하며,IPv4와 유사한 체계를 갖는다. - 특정 IP와 서브넷 마스크를 bit연산 하여 나온값이 네트워크 주소가 됨 - IPv6는 IPv4의 주소부족(2의 32제곱 = 약 43억개)문제를 해결하기 위해서 고안했으나 잘 쓰이지 않음. 2의 128제곱 공인 IP와 사설 IP - 주소 부족 문제를 해결하기 위함 - 공인 IP(서울시 동작구 상도동 상도아파트), 사설 IP(101동 101호)와 같이 비유를 들 수 있음 - 위와 같은 방법을 통해 주소부족 문제를 해결 - 이 때 공인IP->사..</div>
        </td></tr><tr><td>
        <a href="https://soomers.tistory.com/152">
            <div>2023. 9. 18.</div>
            <img width="100%" src="img/nKUkFCkOyFTGdjsjpoKYmk"/><br/>
            <div>[git] GitHub Action 사용법 - 기초</div>
        </a>
        <div>GitHub Action이란? github action이란 코드 수정 후 필요한 작업을 자동화하는 도구입니다. 즉, 특정 이벤트가 발생했을 때 일련의 명령을 수행시킬 수 있습니다. 이 때 "이벤트"에는 push, pr, issue발생 등 많은 경우를 event로 trigger할 수 있습니다. 그리고 특정 이벤트가 발생했을 때 수행하는 일련의 명령어는 CI/CD와 같은 플로우나 크롤링과 같은 작업도 수행할 수 있습니다. Github Action용어 이벤트 : 정의된 깃허브 액션 작업을 실행시키는 특정 활동 워크플로 : 이벤트에 의해 실행되는 일련의 작업을 말하며, *.yml파일을 말합니다. 잡 : "단일 환경"에서 실행될 명령의 집합 스텝 : 잡 안에서 실행하게 될 명령의 집합 액션 : 단일 명령 그 자체..</div>
        </td><td>
        <a href="https://soomers.tistory.com/151">
            <div>2023. 9. 14.</div>
            <img width="100%" src="img/5Y8IvXd9YqUqifr0PLVfk0"/><br/>
            <div>Python-dotenv라이브러리를 이용하여 환경변수 관리하기</div>
        </a>
        <div>들어가면서 이전에 아래의 포스팅을 작성하면서 SECRET_KEY를 파일 또는 환경변수를 통해 안전하게 관리하는 방법에 대해서 이야기해봤습니다. 오늘은 dotenv를 활용하여 환경변수를 다루는 방법에 대해서 살펴보겠습니다. 제가 생각하기에 .json에 저장하는 방법은 포맷을 맞춰줘야 하기 때문에 여러 환경변수 같은 것들이 들어가야 할 경우 작성하기 번거롭고, export를 통해 환경변수를 설정하는 것은 pycharm환경이나 terminal 환경을 활용할 경우 각각 다르기 때문에 이 또한 번거롭다 느껴졌습니다. 그래서 프로젝트 별로 .env라는 단일 파일을 이용해 환경변수처럼 이용하는 방법을 살펴보겠습니다. 먼저 주의사항을 이야기하자면 dotenv를 사용하고 git에 commit할 때에 반드시반드시반드시반드..</div>
        </td><td>
        <a href="https://soomers.tistory.com/150">
            <div>2023. 9. 13.</div>
            <img width="100%" src="img/m4tqDCotVJ6IkJ1T5loaW0"/><br/>
            <div>[Jupyter Notebook] 커널 에러 해결</div>
        </a>
        <div>문제상황 마구잡이로 깔고 환경설정하다가 지우고 하다보니 문제가 발생했다. Jupyter notebook Web에는 Kernel Error가 발생했고, 해당 오류 내용의 마지막에는 다음과 같이 적혀있었다. 나는 해당 가상환경을 지웠는데, 여전히 Jupyter Kernel은 해당 환경을 바라보고 있는듯 했다. 문제해결 과정 1. Jupyter 명령어가 입력되지 않는 문제 해결 문제를 해결하려고 하면 Jupyter Kernel이 왜 위 경로를 참조하는지 확인해야 하는데, 또 다른 문제인 Jupyter라는 명령어 자체가 입력되지 않았다. zsh에 PATH를 등록하지 않아서 생긴 문제이다. 나는 Jupyter Notebook을 conda를 통해 다운받았으므로 conda가 설치된 경로의 /bin을 등록해야 했다. ..</div>
        </td></tr><tr>
            </tr>
        </tbody>
    </table
    