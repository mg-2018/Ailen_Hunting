###### Ailen_Hunting

### 스토리

주인공이 속해있던 우주선이 외딴 행성에 불시착하게 된다.(이유 추가?)
이 외딴 행성에는 정체불명의 생명체들이 자리잡고 있었고, 이 괴생명체들은 주인공 일행을 그다지 반기지 않는다. 당연히 괴생명체들에게 직접적인 공격을 받게되고, 함선은 주변 괴생명체들의 수를 줄이면서 구조신호에 집중한다.(1스테이지)
함선 주변의 괴생명체들의 수는 크게 줄어들었지만, 함선의 물자는 시간이 지날수록 부족해지고 있다. 만일 이 행성을 탐험한다면 필요한 물자나 자원을 구할 수 있을지도 모른다. 하지만 누군가는 이 위험부담을 감수해야 할 것이다.(2스테이지)
물자공급을 위한 자원 수급은 꽤나 성공적이었고, 구조신호도 정상적으로 작동중이다. 하지만 구조신호가 언제나 좋은 응답을 가져올거라고 생각할 수 없었다. 구조신호를 보내다 발견한 것은 외계의 문명이었다. 다행스럽게도 그들은 적대적인 행동을 보여주고 있지는 않지만, 그렇다고 해서 호의적이지도 않다. 그들과 거래할 방법을 찾아야한다.(3스테이지)
괴생명체들의 부산물은 이들에게도 꽤나 중요한 자원인듯하다. 부산물을 대량으로 공급이 가능함을 보여주자 그들이 거래를 할 의사를 비쳐왔다. 뭘하는 녀석들인지는 모르겠지만, 거래를 통해 물자를 더 확보할 수 있을 것 같다.

직업
군인 : 함선을 지키던 인원. 함선의 불시착 도중 대부분이 실종됬으나, 아직 남은 인원들은 싸울 수 있다.
 - 기능적인 부분으로 탄환과 같은 투사체에 대해 보너스를 주는게 좋을거 같다.
엔지니어 : 함선 내 장비들을 손보던 인원. 함선의 불시착으로 인해 함선을 수리하는데 대부분이 투입됬으나, 일부 인원은 외계 행성에 관심을 보이고 있다.
 - 포탑 장비와 관련된 장비의 효율이 상승
생태 학자(?) : 임무와 관련하여 필요한 인원이어서 탑승했으나, 불시착으로 외계 행성에 함께 떨어진 인물. 외계 행성의 생태학에 관심이 많아 자발적으로 임무에 지원했다.
 - ???
용병(외계) : 이곳에서 마주한 외계 문명의 용병. 부를 때마다 자원이 필요하긴 하지만, 실력만큼은 확실하다.
 - 탄환 보너스 및 기타 보너스 추가?
 - 해금스테이지는 3스테이지 이후
 - 플레이하기전 자원 소모?



임무 지원 : 각 스테이지 마다 함선에서 기초적인 장비를 지원해주며, 게임 중 일정 실적 이상을 달성 했을 때(레벨 업 시스템) 장비 업그레이드가 지원된다.
해금 방식 : 
외계 기술(해금) : 이 행성에는 아무래도 지적 수준이 높은 생명체도 존재하는 듯 하다. 이들의 문명을 찾아낸다면 도움이 될지도 모른다.
 - 행성의 또다른 문명과 거래를 통하여 외계기술을 접목한 장비를 해금 가능하다. 단, 외계 생명체들의 부산물을 통해 거래해야 한다. (스테이지 진행 시 거래 해금, 외계 문명 장비 획득 가능)

### 개발 일정 

2023.06.29 기획,역할분담
2023.07.06 개발 시작


### 역할
UI - 김재영
코드 매니저 - 오현우
몬스터, 보스 디자인(패턴 등) - 승찬
캐릭터 기능 구현 - 김예현
스테이지 - 이건욱
사운드 - 에셋
장비 디자인 - 송석현, 이헌성

그래픽, 이펙트 - 정준혁, 정예은, 김예현

------------------
### 무기
기본적으로는 메카닉의 주 무기가 있고 보조무기를 보조 파츠의 형태로 장착

#### 메카 타입
- 벨런스형(모든 스텟이 골고루): 주무기 - 기관총  
최종 업그레이드: 미니건
- 화력형(이속down, 데미지up): 주무기 - 화염방사기  
최종 업그레이드: 얼음 방사기
- 스피드형(이속up, 데미지down): 주무기 - 건블레이드  
최종 업그레이드: 검기 발사
방어형(이속down, 체력up): 주무기 - 방패  
- 최종 업그레이드: 상시유지 베리어

#### 보조무기 (액티브)
- 생화학무기: 도트딜  
(최종업글: 방사능총) 
- 저격총: 관통기능  
(최종업글: 레일건)
- 지원사격: 플레이어 주위의 사격  
(최종업글: 플레이어 주위로 레이저를 쏘고 점점 바깥으로 발사)
- 미사일 런처: 직선형 투사체 발사 후 접촉 시 광범위 폭발공격  
(최종업글: 호밍 미사일)
- 드론: 드론이 날아가서 근접 공격  
(드론자체는 근접공격 :톱날, 최종업글: 위의 옵저버)
- 산탄총: 부채꼴형 범위공격  
(최종업글: 로켓펀치)
- 폭탄: 해당지점 투척형 범위공격  
(최종업글 : 플라즈마 폭탄, 하딩 강화W)
- AI포탑: 설치형 포탑  
(최종업글: 자율형 포탑-플레이어 따라다님)
- 자기장: 플레이어 주변 데미지  
(최종업글: AT필드)
- 전기총: 기관총과 같으나 맞으면 슬로우  
(최종업글: 테이저건, 연쇄반응) 

#### 업그레이드 최대 5단계
- 1, 2단계 데미지 업그레이드
- 3단계 범위, 디버프, 탄알 수 등 유틸 업그레이드
- 4단계 데미지 업그레이드
- 5단계 전체적인 스팩 업그레이드

#### 보조무기 (패시브)
형태: 소프트웨어 (디자인은 홀로그램 형태의 아이콘)  
#### 스텟관련
- 데미지up
- 이동속도up
- 최대 체력
- 방어력
- 회복
- 투사체 속도
- 지속시간
- 공격범위
- 공격속도

#### 유틸관련
- 자석아이템
- 경험치 증가
- 골드 획득량
- 아이템 획득 범위  

#### 무기 디자인 현황  

2023.07.06 : 컨셉 수정 후 주무기, 보조무기(액티브) 구상  
2023.07.11 : 메카 종류 및 주무기, 보조무기 추가 및 각 단계별 업그레이드 가이드라인, 패시브 구상

--------------

### UI

#### 메인메뉴
 - 버튼 클릭 애니메이션 변경
 - 게임셋팅창, 스테이지선택창 틀 구현

--------------
