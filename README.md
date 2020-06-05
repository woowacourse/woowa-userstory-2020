# woowa-userstory-2020
# 사용자 이야기 미션

## 유튜브 api 기반 검색 서비스

### 기획 동기

- 2019년 통계자료에 따르면 국내에서 유튜브는 구글보다도 많이 사용되는 검색 수단이다.
- 하지만 유튜브는 검색엔진이 아니다. 
- 검색엔진으로 만들어진 서비스가 아닌만큼 검색엔진으로 사용할 때 불편한 점이 있지 않을까?

- 참고 기사
    - [왜 요즘 10대는 포털보다 유튜브에서 먼저 검색할까?](https://ppss.kr/archives/147030)
    - [인터넷 이용자 60% 유튜브 검색채널로 활용한다](https://www.mk.co.kr/news/business/view/2019/03/152991/)

### 잠재 사용자 리서치

#### 사용자가 불편하다고 생각했던 것들

- 검색어와 관련 있는 자주 보던 채널이 있다면 그 채널이 위에 뜨는 경우가 있다.

#### 그 외 있으면 좋겠다고 했던 것들

- 주제별로 댓글을 모아서 보여주는 것도 재밌을 것 같다.

- 유튜브의 op.gg처럼 하면 재밌을 것 같다.
    - 내가 유튜브에 시간을 얼마나 낭비했는지 알려준다.
    - 연령별 가장 많이 본 영상이 무엇인지 등 각종 통계자료를 알려준다.
    - 내가 어떤 카테고리의 영상을 얼마나 시청했는지 통계자료를 볼 수 있다.

- 내 친구들은 어떤 영상을 보는지 알고 싶다.

- 어느 순간부터 매일 비슷한 영상만 추천된다.
    - 내가 보던 영상이 아닌 다른 주제의 재밌는 것도 보고 싶다.
    
#### 리서치 결과

- 사용자가 원하는 것은 새로운 검색엔진이 아니다
- 유튜브 api를 이용해서 새로운 재미있는 요소들을 보여주는 것을 원한다

### 페르소나

#### 목적 정의하기

- 유튜브 애청자
    - 내가 시간을 얼마나 소비했는지 알고 싶다.
    - 내가 어떤 카테고리의 영상을 얼마나 시청했는지 통계를 보고 싶다.
    - 내 친구들은 어떤 영상을 보는지 알고 싶다.
    - 내가 자주 보는 주제가 아니여도 재밌을 만한 영상을 보고 싶다.
    
#### 페르소나 설명하기

##### 김ㅇㅇ
    - 20대
    - 매일 기상 직후, 취침 전 유튜브를 본다
    - 매일 비슷한 영상만 추천되는 게 불만이지만 습관적으로 계속 유튜브를 본다

    - needs
        - 친구들이 어떤 영상을 시청했는지 보고 싶다
        - 내가 어떤 카테고리의 영상을 얼마나 보는지 알고 싶다
        - 매일 추천되는 비슷한 영상 말고 다른 것도 보고 싶다

### 요구사항 도출하기

    - 사용자가 유튜브에 시간을 얼마나 소비했는지 알려준다
    - 사용자가 시청한 영상에 대한 각종 통계를 낸다.
    - oauth를 이용한 로그인을 할 수 있다
    - 친구 등록 기능이 있다
    - 친구들이 자주 보는 영상을 보여준다

