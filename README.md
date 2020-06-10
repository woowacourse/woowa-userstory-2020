# 기술 블로그, 커뮤니티 구독 서비스

## 개요

기존 기술 블로그 메일 구독서비스가 존재하는데 사용자는 구독 서비스에서 기본적으로 제공하는 기술 블로그의 글들을 받아 보아야한다.  
그로 인해 원하지 않는 기술 스택에 대해서만 다루는 블로그까지 구독해야 한다.

이를 보완하기 위해 사용자가 선택적으로 구독 대상(블로그, 커뮤니티)을 추가 혹은 제거 할 수 있도록 서비스를 제공한다.

구독 내용은 기술 블로그에 한정하지 않고 기술 커뮤니티에서 화제가 된 글(가장 영향력이 있는 글)도 구독 내용에 포함시킨다.

또한 구독 시간이 정해져 있어 바쁜 시간에 구독 정보를 전달 받게 되면 보지 못한채 잊어 버리는 상황이 발생하기 때문에  
구독 시간에 대해 선택을 할수 있는 시간을 추가한다.

## 기존 서비스 분석에 따른 차별점

- 매일 아침 10시에 메일로 기술 블로그 포스트 10개를 전송해준다.
  - 기술 블로그 구독 대상을 설정할 수 없다.
  - 전달 받을 시간을 설정할 수 없다.
  - 기술 커뮤니티에서 발행된 글은 제공하지 않는다.
  - 메일로만 구독 정보를 받아 볼 수 있다.

---

- 기술 블로그 구독 대상을 설정할 수 없다.
  - 원하지 않는 글을 지속적으로 발행하는 블로그를 구독 해제할 수 있다.
- 전달 받을 시간을 설정할 수 없다.
  - 07시, 12시, 18시 세가지 구독 전달 시간을 지정할 수 있다.
- 기술 커뮤니티에서 발행된 글은 제공하지 않는다.
  - FaceBook 커뮤니티(ksug, awsksug), Slipp, okky와 같은 기술 커뮤니티에서 조회수가 높은 글을 같이 제공한다.
- 메일로만 구독 정보를 받아 볼 수 있다.
  - 메일 이외의 수단(카카오톡)으로도 구독 정보를 볼 수 있도록 한다.



## 페르소나

### **장제이**

- 29살
- 3년차 백엔드 개발자
- 자신이 사용하고 있는 기술에 대해 관심이 많다.

#### Needs

- 프로그래밍 역량을 키우고 싶다.
- 메일로 정보를 받아보고 싶다.
- 자바와 관련된 정보만 보고 싶다.

---

### 탁코일

- 27살
- 2년차 백엔드 개발자
- 기술에 대한 폭 넓은 관심이 있다.

#### Needs

- 카카오톡으로 정보를 받아보고 싶다.
- 여러 종류에 대한 정보를 받아보고 싶다.
- 퇴근 시간에 가볍게 글을 보는 것을 좋아한다.

## 시나리오 제작

|          제품          | 페르소나 |                        시나리오                        |
| :--------------------: | :------: | :----------------------------------------------------: |
|     이메일 시스템      |  구독자  |    매일 정해진 시간에 구독 정보를 메일로 전송한다.     |
| 카카오톡 메신저 시스템 |  구독자  | 매일 정해진 시간에 구독 정보를 카카오톡으로 전송한다.  |
|  구독정보 선택 시스템  |  구독자  | 원하지 않는 기술 스택을 다루는 블로그는 구독 해제한다. |
|  구독시간 선택 시스템  |  구독자  |   제공하는 구독시간을 선택하여 구독 정보를 받아본다.   |

## 요구사항 도출

| 시나리오1                                                    | 요구사항                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 장제이는 출근 후 메일을 정리하며 구독한 정보를 받아 보고 싶다. | - 구독 정보를 전달받는 시간을 출근 시간으로 설정 할 수 있어야한다.<br />- 회사에 출근하기 이전 시간에 구독 정보가 메일함에 도착해 있어야한다. |
| 받아본 구독 정보중 원치않는 기술 스택만을 다루는 블로그, 커뮤니티가 있다. | - 구독을 원치 않는 블로그, 커뮤니티는 구독 해제 할 수 있어야 한다. |

| 시나리오2                                                    | 요구사항                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 탁코일은 퇴근 시간에 가볍게 핸드폰으로 구독 정보를 받아 보고 싶다. | - 구독 정보를 전달받는 시간을 퇴근 시간으로 설정 할 수 있어야한다.<br />- 카카오톡 메세지로 전달된 구독정보가 있어야 한다. |


