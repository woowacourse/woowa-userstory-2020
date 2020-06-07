## 프로젝트 기획 : 위치기반 실시간 채팅 서비스

근처 카페에 사람이 많은지 궁금할 때, 회사 밖에서 들리는 소란이 궁금할 때, 근처의 산책로 정보가 궁금할 때를 위한 서비스입니다.

 설정한 반경(500m, 1km, 3km) 안에 있는 사람들과 채팅방에서 채팅을 할 수 있고, 필요한 경우 1:1로도 채팅이 가능합니다. "맛집", "날씨", "잡담", "거래" 등의 게시판도 마련되어 있습니다.





## 1순위 페르소나

###  장제이

-28세  
-3년차 백엔드 개발자  
-코로나로 인한 재택 근무 중  
-집에 있으면 잠만 자는 타입

**Needs**

-집 앞 카페에서 공부를 하고 싶다.  
-카페에 콘센트 있는 자리가 얼마나 있는지 궁금하다.  
-카페에 있는 누군가가 남은 자리를 알려주면 좋겠다.





###  김타미

-25세  
-신입 개발자  
-잠실에서 근무

**Needs**

-입사 첫 날, 퇴근 시간이 다가왔고, 수고한 자신을 위해 호떡으로 보상하려고 한다.  
-호떡 포장마차를 찾기 쉽지 않다  
-주변 지리를 잘 아는 누군가 근처에 호떡 포장마차가 존재하는지 알려주면 좋겠다.









## 시나리오 제작

| 제품                                      | 페르소나        | 시나리오                                                     |
| ----------------------------------------- | --------------- | ------------------------------------------------------------ |
| 실시간 카페 상황 보여주기 시스템          | 집 앞 카페 손님 | - 자리가 얼마나 남았는지 궁금하다 <br />- 카페가 추운지, 더운지 궁금하다 |
| 검색해도 나오지 않는 정보 보여주기 시스템 | 이방인          | - 근처에 호떡 포장마차 위치를 알려줄 누군가가 필요하다 <br />- 호떡 포장마차의 마감 시간이 궁금하다 |







## 요구사항 도출



| 시나리오 1                                                   | 요구사항                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 제이는 집 앞 OO카페에 가서 업무를 보려고 한다. 그런데 그 카페에 사람이 얼마나 있는지, 콘센트가 있는 자리는 얼마나 남았는지 궁금하다. | - 근처에 있는 사람들끼리 실시간으로 대화할 수 있는 공간이 필요하다. |
| 제이는 어플에 접속해 OO카페에 자리가 얼마나 있는지 물어본다. | - 익명으로 질문할 수 있는 게시판이 필요하다.                 |
| 얼마 후, 그 카페에 있던 탁코일 씨가 카페에 자리가 많이 남아 있다고 알려준다. | - 댓글 기능이 필요하다.                                      |
| 제이는 탁코일 씨를 믿고 카페를 나선다.                       | - 댓글 정보의 신뢰 기능이 필요하다. (댓글 실명제, 좋아요, 싫어요, 신고 기능이 필요하다) |

| 시나리오 2                                                   | 요구사항                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 입사 첫 날, 타미의 퇴근 시간이 다가왔다. 하루종일 긴장한 탓에 배가 고프고, 오늘따라 유독 호떡이 먹고싶다. 그런데, 잠실 지리에 익숙하지 않은 타미는 호떡 포장마차를 찾기 쉽지 않다. | - 근처에 있는 사람들끼리 실시간으로 대화할 수 있는 공간이 필요하다.<br />- 익명으로 질문할 수 있는 게시판이 필요하다. |
| 얼마 후, 마침 근처에 있던 진또링 씨가 타미의 글에 방이동 먹자골목 입구에 있다는 제보를 한다. | - 댓글 기능이 필요하다.                                      |
| 타미는 진또링 씨에게 감사함을 표현하고, 진또링 씨가 알려준대로 향해 맛있는 호떡을 먹는다. | - 댓글 여러개 기능이 필요하다.                               |





