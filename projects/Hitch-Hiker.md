# :pushpin: Hitch-Hiker
>혼자 여행하는 사람들을 위한 여행 친구 매칭 서비스  
>https://hitch-hiker.kr/

</br>

## 1. 제작 기간 & 참여 인원
- 2022년 9월 13일 ~ 10월 12일
- 팀(4인) : 
  > 정윤조(BE)  
  > 김기홍(BE)  
  > 이동기(팀장, FE)  
  > 배자현(FE)  

</br>

## 2. 사용 기술
#### `Back-end`
[![Java](https://img.shields.io/badge/Java-11-orange?style=for-the-badge)]()
[![SpringBoot](https://img.shields.io/badge/SpringBoot-2.7.3-darkgreen?style=for-the-badge)]()
[![SpringDataJPA](https://img.shields.io/badge/SpringDataJPA-2.7.3-darkgreen?style=for-the-badge)]()
[![SpringSecurity](https://img.shields.io/badge/SpringSecurity-5.7.3-darkgreen?style=for-the-badge)]()
[![JWT](https://img.shields.io/badge/JWT-3.19.2-purple?style=for-the-badge)]()
[![Redis](https://img.shields.io/badge/Redis-6.2.6-red?style=for-the-badge)]()
[![Querydsl](https://img.shields.io/badge/Querydsl-5.0.0-skyblue?style=for-the-badge)]()
[![MySQL](https://img.shields.io/badge/MySQL-8.0.3-blue?style=for-the-badge)]()
[![AWS](https://img.shields.io/badge/AWS-2.16.65-gold?style=for-the-badge)]()
[![WebSocket](https://img.shields.io/badge/WebSocket-9.0.65-black?style=for-the-badge)]()
#### `Front-end`
[![React.js](https://img.shields.io/badge/React-18.2.0-lightblue?style=for-the-badge)]()
[![Styled_Components](https://img.shields.io/badge/Styled_Components-5.3.5-pink?style=for-the-badge)]()
[![Toast_UI](https://img.shields.io/badge/Toast_UI-3.0.0-purple?style=for-the-badge)]()

</br>

## 3. ERD 설계
![seb-006-main ERD2](https://user-images.githubusercontent.com/43122133/195172214-cba865f2-b9b4-4f17-9589-0217ab65725f.png)

</br>

## 4. 핵심 기능
Hitch-Hiker의 핵심 기능은 여행 매칭 기능입니다.
여행 장소와 날짜가 지정된 여행 모집 게시글을 등록합니다.
참여를 희망하는 사람은 자신의 목적에 부합하는 게시글에 참여 신청을 할 수 있고,
모집 게시글 작성자는 참여 신청자의 정보 혹은 연락을 통해 수락과 거절을 선택할 수 있습니다.

<details>
<summary><b>핵심 기능 API Flow Chart 펼치기</b></summary>
<div markdown="1">
  
![슬라이드8](https://user-images.githubusercontent.com/43122133/195167412-c503c202-9c56-4062-bd30-17251c9617a9.PNG)
![슬라이드12](https://user-images.githubusercontent.com/43122133/195167418-dd942640-256c-4c20-bf99-31915f8e7a73.PNG)
![슬라이드17](https://user-images.githubusercontent.com/43122133/195167422-45317ed6-7007-46a8-b2ea-c6a9ae40d93c.PNG)
  
</div>
</details>
 
<!-- [핵심 기능 시연 보러가기](https://github.com/jyj2187/hitch_hiker/wiki/How-to-use) -->

<details>
<summary><b>핵심 기능 시연 펼치기</b></summary>
<div markdown="1">

***토글을 눌러 기능별 시연을 확인할 수 있습니다***

### 회원가입
<details>
<summary>회원가입 시, 닉네임 중복 검사와 이메일 인증을 진행합니다.</summary>
<div markdown="1">

![회원가입](https://user-images.githubusercontent.com/43122133/195156515-016e7c08-4215-4a6f-9953-e59306c8ae95.gif)

</div>
</details>
    
### 로그인
<details>
<summary>로그인은 일반 이메일 로그인과 카카오 소셜 로그인을 지원합니다.</summary>
<div markdown="1">

- ![로그인](https://user-images.githubusercontent.com/43122133/195157414-2364eeda-e26c-4fe7-b2b4-21bab85ebecc.gif)

- ![소셜로그인](https://user-images.githubusercontent.com/43122133/195160915-60dfa922-889b-4ac0-aad1-bbc01fc8fffd.gif)

</div>
</details>

### 게시글 작성        
<details>
<summary>게시글을 작성할 수 있습니다. 이미지 첨부를 지원합니다.</summary>
<div markdown="1">

![게시글 작성](https://user-images.githubusercontent.com/43122133/195161056-6802c378-e575-4fa4-8e85-b74e7bf152e9.gif)

</div>
</details>
    
### 게시글 수정
<details>
<summary>게시글을 수정 및 삭제할 수 있습니다.</summary>
<div markdown="1">

![게시글 수정](https://user-images.githubusercontent.com/43122133/195161543-27ade6ea-ba8e-4e63-9b78-7fe0ce1d26ca.gif)

</div>
</details>

### 게시글 북마크
<details>
<summary>선호하는 게시물을 북마크할 수 있습니다.</summary>
<div markdown="1">

![북마크](https://user-images.githubusercontent.com/43122133/195161664-7d239f20-8076-4429-9882-e2b7152e4466.gif)

</div>
</details>


### 게시글 검색 및 정렬
<details>
<summary>게시글을 날짜 및 내용으로 검색하고 다양한 기준으로 정렬할 수 있습니다.</summary>
<div markdown="1">

![게시글 검색 및 정렬](https://user-images.githubusercontent.com/43122133/195161782-89fef3d1-f8d7-4df7-b4df-d66787cccfac.gif)

</div>
</details>


### 매칭 신청
<details>
<summary>참여하고 싶은 여행에 매칭 신청을 보냅니다. 이 때, 게시글 작성자에게 알림이 갑니다.</summary>
<div markdown="1">

![매칭 신청](https://user-images.githubusercontent.com/43122133/195161854-892892c9-586f-4157-aba0-f165bf4d9bdb.gif)

</div>
</details>


### 매칭 수락 혹은 거절
<details>
<summary>게시글의 주인은 매칭 신청을 수락 혹은 거절할 수 있습니다. 이 때, 매칭 신청자에게 알림이 갑니다.</summary>
<div markdown="1">

![매칭 수락 혹은 거절](https://user-images.githubusercontent.com/43122133/195161879-346270e7-75ad-4e13-b936-e62a92807f0e.gif)

</div>
</details>


### 참여 취소
<details>
<summary>참여자를 추방 혹은 참여자가 직접 참여를 취소할 수 있습니다. 이 때, 해당 참여자에게 알림이 갑니다.</summary>
<div markdown="1">

![참여 취소](https://user-images.githubusercontent.com/43122133/195161942-fe5c849e-d869-44f0-9df6-6fe8454fadb2.gif)

</div>
</details>


### 내 정보 확인
<details>
<summary>MYPAGE에서 게시글과 매칭 현황 등 내 정보를 확인할 수 있습니다.</summary>
<div markdown="1">

![내 정보 확인](https://user-images.githubusercontent.com/43122133/195161976-79a40be3-f1bd-46c6-997a-5f7e14c1e032.gif)

</div>
</details>


### 내 정보 수정
<details>
<summary>MYPAGE에서 내 정보를 수정할 수 있습니다.</summary>
<div markdown="1">

![유저 정보 수정](https://user-images.githubusercontent.com/43122133/195162033-c15d7872-5eac-43d9-8c13-970fb3e2d9db.gif)

</div>
</details>

</div>
</details>

</br>

## 5. 핵심 트러블 슈팅
### 5.1 Toast UI Editor 이미지 업로드 처리
- 저는 게시글을 작성할 떄 여러 장의 이미지를 업로드할 수 있도록 처리하고 싶었습니다. 이미지를 업로드하는 흐름은 이러합니다. 
>1. Client 환경의 Toast UI Editor에 이미지를 업로드합니다.
>2. 이미지는 Editor에 업로드된 즉시 AWS S3에 업로드됩니다.
>3. Server에서는 업로드된 이미지의 S3 주소를 반환해줍니다.
>4. Toast UI Editor의 addImageBlobHook() 함수를 이용해서 이미지 주소를 받아서 Editor에 표시해줍니다.

<!-- - 이미지는 원본과 이미지 S3 주소를 DB에 저장하여 게시글과 연관관계를 설정해줍니다. **이미지에 대한 정보를 저장하는 이유는 게시글에 쓰인 이미지를 확인하고 또 혹여라도 작성자가 이미지를 올리고 쓰지 않을 경우 서버 측에서 Batch를 통해 S3에서 삭제하기 위함입니다.** -->
- 이 과정에서 **프론트 측의 상태 관리 이슈**가 있었습니다. Editor 부분이 React의 Return문에 들어있었기에 여러 장의 이미지를 업로드할 때마다 상태관리는 초기화되어서 추가적인 처리가 필요했고 이는 Client에게 너무 많은 짐을 지는 것 같았습니다. 또 이미지를 수정할 때 이미지의 사용 여부를 판단할 방법이 부족했습니다. 
- 결국 Server에서 이미지의 사용여부를 직접 체크하도록 서비스 계층에서 메서드를 작성하였습니다. 게시글은 Markdown 형식으로 전달된다는 전제하에 작성하였습니다.
<details>
  <summary><b>작성 코드</b></summary>
  <div markdown="1">

- 게시글(Posts)의 내용(body)에서 이미지 주소(ImagePath)를 찾습니다.
```Java
public List<String> findImagePathInBody(String body) {
    List<String> imagePathList = new ArrayList<>();
    while (body.contains(domain)) {
        body = body.substring(body.indexOf(domain));
        int startIdx = 0;
        int endIdx = body.indexOf(')');
        String imagePath = "https://" + body.substring(startIdx, endIdx);
        imagePathList.add(imagePath);
        body = body.substring(endIdx);
    }
    return imagePathList;
}
```


- 이미지 주소 리스트를 게시글과 매핑해줍니다.
```Java
public void saveImages(List<String> imagePathList, Posts posts) {
    for (String imagePath : imagePathList) {
        Image image = imageRepository.findByStoredPath(imagePath)
                      .orElseThrow(() -> new BusinessLogicException(ExceptionCode.IMAGE_NOT_FOUND));
        image.setPosts(posts);
        imageRepository.save(image);
    }
}
```

  </div>
</details>

</br>

### 5.2 WebSocket 실시간 알림 구현 방식에 대한 고민
- 서비스의 추가적인 기능으로 실시간으로 이벤트에 반응하는 알림 기능을 구현하고 싶었습니다.
<!-- >Spring에서는 Stomp + SockJS를 이용하여 WebSocket 통신을 지원하고 있습니다.  
>Stomp는 WebSocket 기반 pub/sub 구조의 통신 프로토콜로 publisher가 발행한 메시지를 subscriber가 읽는 구조입니다. -->
- 기능 구현에 앞서 첫번째로 했던 고민은 **발생 트리거가 Client와 Server 어느 쪽에 있어야 하는지**였습니다.
    - 채팅이 아닌 실시간 알림이기에 API 요청을 이미 보낸 Client가 두번의 요청을 보낼 필요는 없다고 생각해서 EventListener를 이용하여 Transaction에 반응하여 메시지를 보낼 수 있도록 하였습니다.  
        <details>
          <summary><b>작성 코드</b></summary>
        <div markdown="1">

        - 이벤트를 발행하는 Transaction(ex. 매칭 신청글 작성, 매칭 수락 혹은 거절)이 Commit되면 이벤트 리스가 작동하도록 합니다.
        ```Java
        @Transactional(propagation = Propagation.REQUIRES_NEW)
        @TransactionalEventListener(phase = TransactionPhase.AFTER_COMMIT)
        public void handleMessagingListener(DomainEvent event) throws IOException {
            MessageDto.Response message = messageService.createMessage(event.getEntity(), event.getEventType());
            sendMessage(message);
        }
        ```

        </div>
        </details>
      
- 두번째 고민은 **Subscribe를 어떤 방식으로 할지**였습니다.
    - Subscribe를 하기 위해서는 유저의 정보가 필요한데 세션 방식이 아닌 JWT를 이용하고 있어서 JWT의 정보를 해독해야 했습니다.
    - Stomp는 HttpRequest에서는 접근할 수 없는 프로토콜이라 정보를 가져오기가 힘들어서 StompHeaderAccessor를 이용해 JWT 정보를 가져왔습니다.
    - Session관련 이벤트 클래스들을 이용해 Server 측에서 직접 정의한 Session 객체에 정보를 저장하였습니다.  
        <details>
        <summary><b>작성 코드</b></summary>
        <div markdown="1">

        - 세션 정보를 담을 MemberSession이라는 객체를 만듭니다.
        ```Java
        @Data
        public class MemberSession {
            private Long memberId;
            List<String> sessionIds = new ArrayList<>();

            public MemberSession(Long memberId, String sessionId) {
                this.memberId = memberId;
                this.sessionIds.add(sessionId);
            }
            public MemberSession() {

            }
        }
        ```


        - WebSocket 연결이 이루어지면 발생하는 이벤트를 잡아 직접 세션 정보를 설정하고 구독할 수 있게 합니다.
        ```Java
        @RequiredArgsConstructor
        @Component
        public class WebSocketEventListener {
            private final JwtUtils jwtUtils;
            Map<String, MemberSession> sessionMap = new HashMap<>();

            @EventListener
            public void handleWebSocketConnectListener(SessionConnectedEvent event) {
                StompHeaderAccessor accessor = StompHeaderAccessor.wrap(event.getMessage());
                GenericMessage generic = (GenericMessage) accessor.getHeader("simpConnectMessage");
                Map nativeHeaders = (Map) generic.getHeaders().get("nativeHeaders");
                ArrayList access_hh = (ArrayList) nativeHeaders.get("access_hh");
                String accessToken = (String) access_hh.get(0);
                accessToken = accessToken.replace("Bearer ", "");
                Map<String, Object> map = jwtUtils.getClaimsFromToken(accessToken, "access");
                MemberSession session = new MemberSession((Long) map.get("id"), accessor.getSessionId());
                sessionMap.put((String) map.get("email"), session);
            }

            @EventListener
            public void handleSub(SessionSubscribeEvent event) {
                StompHeaderAccessor accessor = StompHeaderAccessor.wrap(event.getMessage());
                if (StompCommand.SUBSCRIBE.equals(accessor.getCommand())) {
                    String email = null;
                    Long memberId = null;
                    for(Map.Entry<String, MemberSession> entry : sessionMap.entrySet()) {
                        if (entry.getValue().getSessionIds().contains(accessor.getSessionId())) {
                            memberId = entry.getValue().getMemberId();
                            email = entry.getKey();
                        }
                    }
                    if (memberId == null || email == null) {
                        throw new BusinessLogicException(ExceptionCode.SESSION_NOT_FOUND);
                    }
                }
            }

            @EventListener
            public void handleWebSocketDisConnectListener(SessionDisconnectEvent event) {
                StompHeaderAccessor accessor = StompHeaderAccessor.wrap(event.getMessage());
                for(Map.Entry<String, MemberSession> entry : sessionMap.entrySet()) {
                    entry.getValue().getSessionIds().remove(accessor.getSessionId());
                }
            }
        }
        ```

        </div>
        </details>  
  
- 최종적으로 Member는 로그인 하면 /topic/{memberId}를 구독하게 되고, 이벤트가 발생하면 해당 엔드포인트로 실시간으로 메세지가 전달되게 하였습니다.
  
    <details>
    <summary><b>작성 코드</b></summary>
    <div markdown="1">

    - React에서 작성된 WebSocket 연결 및 로직입니다. 로그인 이후에 상태관리를 이용하여 페이지가 변해도 통신이 유지되도록 하였습니다.  

    ```Javascript
    useEffect(() => {
      if (sessionStorage.getItem("isLogin")) {
        const socket = new SockJs(`${process.env.REACT_APP_URL}/websocket`);
        const client = StompJs.over(socket);
        client.debug = null;
        client.connect(
          {
            access_hh: sessionStorage.getItem("AccessToken"),
          },
          () => {
            client.subscribe(
              "/topic/" + sessionStorage.getItem("memberId"),
              (msg) => {
                setMsgs((msgs) => [...msgs, JSON.parse(msg.body)]);
                setMsgIds((msgIds) => [
                  ...msgIds,
                  JSON.parse(msg.body).messageId,
                ]);
              }
            );
          }
        );
      }
    }, []);
    ```


    - 실시간 알림 기능이 포함된 트랜잭션이 완료되면 이벤트가 발행되어 구독된 주소로 메시지를 보냅니다.  

    ```Java
    @RequiredArgsConstructor
    @RestController
    public class WebSocketController {
        private final MessageService messageService;
        private final WebSocketEventListener eventListener;
        private final SimpMessagingTemplate template;
        private final Gson gson;

        public void sendMessage(MessageDto.Response message) throws IOException {
            MemberSession session = eventListener.sessionMap.get(message.getEmail());
            if (session == null || session.sessionIds.isEmpty()) {
                messageService.failedToSend(message);
                return;
            }
            String content = gson.toJson(message);
            template.convertAndSend("/topic/" + session.getMemberId(), content);
        }
        @Transactional(propagation = Propagation.REQUIRES_NEW)
        @TransactionalEventListener(phase = TransactionPhase.AFTER_COMMIT)
        public void handleMessagingListener(DomainEvent event) throws IOException {
            MessageDto.Response message = messageService.createMessage(event.getEntity(), event.getEventType());
            sendMessage(message);
        }
    }
    ```

    </div>
    </details>

## 6. 그 외 트러블 슈팅
<details>
<summary>게시글과 그룹의 역할 문제</summary>
<div markdown="1">
  
- 기존에 요구사항을 보고 판단했을 시점에는 Posts 테이블은 게시글 관련 기능만 담당하고 여행 모집 정보만 담은 Groups라는 테이블을 따로 두어 1:1로 연관관계를 설정한 뒤에 매칭 기능에만 사용할 예정이었습니다.
- 그러나 연관관계를 매핑하던 도중에 Groups 테이블에서 Group의 주인을 필드로 넣는 것이 결국 Posts의 작성자를 넣는 것과 다르지 않냐는 의문이 들기 시작하였습니다.
- 요구사항을 다시 한번 정리해보면서 여행 모집 정보를 담고 있는 Groups와 게시글을 담당하는 Posts가 분리되어야 할 이유가 딱히 없다는 것을 깨달았습니다.
- 현 시점에서는 Groups와 Posts의 Entity를 합쳐서 게시글에 여행 관련 정보도 담도록 했습니다. 매칭은 Member와 Posts의 N:M 연관관계를 통하여 이루어집니다.

</div>
</details>

<details>
<summary>동일한 Entity의 Event 발행 시 메시지 처리 방식</summary>
<div markdown="1">

- Event에 EventType Enum 클래스를 생성
- DomainEvent라는 이너 클래스로 이벤트를 발행해서 이벤트 타입에 따라 다른 메시지가 생성되도록 했습니다.

</div>
</details>
          
<details>
<summary>NAT 게이트웨이 비용 발생 문제</summary>
<div markdown="1">

- NAT 게이트웨이는 시간당 0.059 달러의 비용이 발생하고 이는 한 달 약 5만원의 비용을 발생시킵니다.
- 현재 프로젝트의 규모에서는 좀 과도하게 발생한다고 생각해서 Bastion Host를 NAT 인스턴스로 교체하여 비용을 절감시켰습니다.

</div>
</details>
