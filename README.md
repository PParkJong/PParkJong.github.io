# 프로젝트명: Dungeon Breaker - 박종현

# [ 목차 ]
### 1. [컨셉](#1)
### 2. [관련 이미지와 동영상](#2)
### 3. [대표 이미지 그리고 컨셉과 대표이미지 기반 작품 묘사](#3)
### 4. [Dungeon Breaker의 구성 요소](#4)
4.1 매커니즘<br>
4.2 이야기<br>
4.3 미적요소<br>
4.4 기술<br>
### 5. [게임 시스템 디자인](#5)
5.1 게임 오브젝트 분해<br>
5.2 파라미터(속성) 뽑아 보기<br>
5.3 행동 뽑아 보기<br>
5.4 상태 뽑아 보기<br>
5.5 플레이어 캐릭터 속성(파라미터)<br>
5.6 게임의 규칙<br>
5.7 게임에서 사용될 공식<br>
### 6. [개발 요구사항 & 흐름도](#6)
6.1 요구사항<br>
6.2 시간별 흐름도 flowchart<br>
6.3 키보드 이벤트에 대한 흐름도<br>
6.4 용어정리<br>
### 7. [스토리보드](#7)
### 8. [프로토타입 개발 요구사항 (6주개발)](#8)
### 9. [프로토타입 개발작업 일정 (6주개발)](#9)
- 1주차 <br>
- 2주차 <br>
- 3주차

# [컨셉] <a name='1'></a>

## 메인컨셉 : 컨트롤

- 컨트롤을 통해서 적들의 공격을 피하고 패턴을 공략하여 공격함으로써 스릴감을 느낄 수 있도록 할 것입니다.

### 서브 컨세 1 : 화려함

- 다양한 스킬을 통해서 컨트롤을 통한 즐거움말고도 눈으로 보는 즐거움 또한 줄 것입니다.

### 서브 컨세 2 : 타격감

- 적들을 타격시 타격 이펙트와 동시 화면이 흔들리는 효과와 타격음을 통해 좀더 생동감있는 타격감을 줄 것입니다.

### 서브 컨세 3 : 운

- 적 처치를 통해 얻는 전리품의 등급을 나누어 좋은 전리품을 획득시에 플레이어에게 짜릿함을 줍니다.

### 서브 컨세 4 : 성장

- 처음부터 강한 캐릭터를 컨트롤하는 것이 아니라 적들을 물리치고 경험치와 아이템을 통해 점차 다양한 스킬과 능력치들을 얻으며 성취감을 느낄 수 있습니다.

### 서브 컨세 5 : 귀여움

- SD캐릭터와 같은 비율로 너무 사실적인 그래픽이 아니라 사람들의 거부감을 줄일 수 있으며, 아기자기한 캐릭터로 다양한 액션을 통해 반전매력을 느낄 수 있도록 할 수 있습니다.

<br><br>

# [관련 이미지 & 동영상] <a name='2'></a>

- 이미지
  <br>
  - 보스의 패턴이 미리 표시되고 플레이어는 이를 보고 미리 회피기를 통해 회피를 하며 보스의 패턴을 공략하고 컨트롤하여 공격하는 플레이를 할 수 있습니다.
  ![게임관련이미지1](https://github.com/PParkJong/PParkJong.github.io/assets/147227701/931bea54-a873-4bce-bcfd-442d9cab2f3b)
  
  - 던전이라는 어두운 이미지의 게임이라 생각할 수 있지만 캐릭터는 SD캐릭터와 같은 캐릭터로 반전매력을 느낄 수 있습니다.
    <br>
  ![게임관련이미지2](https://github.com/PParkJong/PParkJong.github.io/assets/147227701/4868edd6-fb99-48d6-8740-3e9394a7f8f5)
- 동영상
  <br>
  ▼클릭<br>
  [<img src="./img/영상이미지.jpg" height="300">](https://youtu.be/2Ebq06HVDRk?si=Au5WHjAVEcUYhYPA)

<br><br>

# [대표 이미지]

![대표 이미지](https://github.com/PParkJong/PParkJong.github.io/assets/147227701/1b8202ae-1cc2-439c-94d9-4c5b9039f405)

<br><br>

# [컨셉 & 대표이미지 기반 작품묘사] <a name='3'></a>

묘사 : 다양한 스킬과 컨트롤을 통한 액션 쾌감과 성장을 통한 성취감을 느낄 수 있는 액션 RPG게임

<br><br>

# [<Dungeon Breaker> Dungeon Breaker 구성 요소] <a name='4'></a>

<br>

## 4.1 메커니즘

[도전 과제]

1. 몬스터들을 처치하며 보스 몬스터까지 도달
2. 보스 몬스터의 패턴을 파훼하고 처치
3. 일정시간 내에 보스몬스터를 처치 못하거나 사망시에 실패

[재미 요소]

1. 몬스터를 처치하고 레벨업하여 자신의 스킬을 강화한다.
2. 다양한 스킬들을 활용하여 몬스터를 처치한다.
3. 보스의 공격을 회피기로 피하고 스킬을 이용하여 공격하며 컨트롤한다.
4. 보스를 처치 후 확률적으로 더 좋은 보상을 얻을 수 있다.

<br>

## 4.2 이야기

[만들게 된 배경]  <br>
- 과거 재밌게 플레이했던 던전스트라이커라는 게임을 추억하였고, 이를 통해 아기자기한 캐릭터를 조작하지만 게임의 배경은 귀여운 캐릭터와는 달리 어두운 배경의 게임을 만들어보고 싶었습니다.<br>
- SD캐릭터는 보통 간단하고 쉬운 게임에 사용되지만 이 게임에는 컨트롤이라는 요소를 추가하여 사람들이 플레이를 하며 긴장감을 느끼고 컨트롤하는 재미를 느낄 수 있도록 하고 싶었습니다.
<br><br>
[참신함] <br>
- 보통 SD캐릭터와 같이 귀여운 캐릭터는 누구나 쉽게 접근할 수 있고 플레이도 쉬운 게임에 사용되는데, 이 게임의 경우 접근이 쉬울 수는 있으나 간단하게 즐기는 것이 아니라 여러 번의 플레이를 통해 플레이어가 컨트롤을 연습하여 던전을 클리어하는 게임이다.
<br><br>
[카메라 관점] <br>
- 쿼터뷰로 설정하고 카메라가 플레이어의 움직임을 따라가도록 한다.

<br>

## 4.3 미적요소

[디자인] <br>
캐릭터와 몬스터의 경우 SD캐릭터와 같이 2등신 캐릭터로 디자인
마을은 거대한 성이 있는 마을, 던전은 어두운 숲, 지하의 감옥, 광산 등으로 마을과는 상반되는 모습으로 디자인
<br>
[컬러] <br>
스킬 사용시 나오는 이펙트에 화려한 색감을 준다.
<br>
[음향]  
스킬마다 다양한 음향을 적용하여 스킬을 시전하거나  몬스터 타격시 음향을 들려준다.
마을에 있을때는 평화로는 배경음, 던전에 입장시에는 긴장감을 느낄 수 있도록 어두운 느낌이 배경을을 재생한다.
<br>

## 4.4 기술

Unity를 기반으로 제작할 예정이다.

<br><br>

# [<Dungeon Breaker> 게임시스템디자인] <a name='5'></a>

<br>

## 5.1 게임 오브젝트 분해

<br>

| 연번 | 오브젝트 이름  | 오브젝트 이미지 |
|:----:|:----:|:----:|
| 1 | 플레이어 | <img src="./img/플레이어.png" width="500"> |
| 2 | 보스1 | <img src="./img/보스1.png" width="500"> |
| 3 | 몬스터1 | <img src="./img/몬스터1.png" height="300"> |
| 4 | 몬스터2 | <img src="./img/몬스터2.png" height="300"> |
| 5 | 몬스터3 | <img src="./img/몬스터3.png" height="300"> |
| 6 | 보스2 | <img src="./img/보스2.png" height="300"> |
| 7 | 몬스터4 | <img src="./img/몬스터3.png" height="300"> |
| 8 | 몬스터5 | <img src="./img/몬스터5.png" height="300"> |
| 9 | 몬스터6 | <img src="./img/몬스터6.png" height="300"> |
| 10 | 상자 | <img src="./img/상자.png" height="300"> |
| 11 | 검 | <img src="./img/검.png" height="300"> |
| 12 | 갑옷 | <img src="./img/갑옷.png" height="300"> |
| 13 | 물약 | <img src="./img/물약.png" height="300"> |
| 14 | 코인 | <img src="./img/코인.png" height="300"> |
| 15 | 상점 | <img src="./img/상점.png" height="300"> |
| 16 | 포탈 | <img src="./img/포탈.png" height="300"> |
| 17 | 플레이어 체력UI | <img src="./img/HealthOrb.jpg" height="300"> |
| 18 | 스킬UI | <img src="./img/스킬UI.png" height="300"> |
| 19 | 물약UI | <img src="./img/물약UI.png" height="300"> |
| 20 | 코인UI | <img src="./img/코인UI.png" height="300"> |
| 21 | BGM | <img src="./img/BGM.jpg" height="300"> |
| 22 | 인벤토리 | <img src="./img/인벤토리.png" height="300"> |
| 23 | 스킬 창 | <img src="./img/스킬창.png" height="300"> |
| 24 | 타이머 | <img src="./img/타이머2.png" height="300"> |
| 25 | 던전선택UI | <img src="./img/던전선택.jpg" height="300"> |
| 26 | 베기 이펙트 | <img src="./img/SlashEffect.jpg" height="300"> |
| 27 | 스킬 이펙트 | <img src="./img/SkillEffect.png" height="300"> |
| 28 | 폰트 | <img src="./img/Font.png" height="300"> |
| 29 | 미션UI | <img src="./img/MissionUI.jpg" height="300"> |
| 30 | 퀘스트 창 | <img src="./img/QuestUI.png" height="300"> |
| 31 | 로딩 창 | <img src="./img/LoadingUI.jpg" height="300"> |
| 32 | 스카이박스 | <img src="./img/Skybox.png" height="300"> |
| 33 | 마을 | <img src="./img/Village.png" height="300"> |
| 34 | 던전 | <img src="./img/Dungeon.png" height="300"> |
| 35 | NPC | <img src="./img/몬스터4.png" height="300"> |

<br>

## 5.2 파라미터(속성) 뽑아 보기

<br>

1\) 오브젝트 이름 : 플레이어
   
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이름 | p_Name | 플레이어의 이름 ||
| 레벨 | p_Lv | 플레이어의 레벨 ||
| 경험치 | p_Exp | 플레이어의 경험치 ||
| 체력 | p_Hp | 플레이어의 체력 수치 ||
| 속도 | p_Speed |플레이어의 이동속도 ||
| 공격력 | p_Atk | 플레이어의 공격력 수치 ||
| 상태 | p_State | 플레이어의 상태 – 대기, 이동, 대쉬, 공격, 빈사상태 등 ||
| 사운드 | p_Sound | 플레이어의 사운드 – 이동, 달리기, 대쉬, 공격, 스킬 등 ||

<br>

2\) 오브젝트 이름 : 보스, 몬스터1, 몬스터2, 몬스터3, 보스2, 몬스터4, 몬스터5, 몬스터6
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이름 | e_Name | 몬스터의 이름 ||
| 체력 | e_Hp | 몬스터의 체력 수치 ||
| 속도 | e_Speed |몬스터의 이동속도 ||
| 공격력 | e_Atk | 몬스터의 공격력 수치 ||
| 상태 | e_State | 몬스터의 상태 – 대기, 이동, 공격, 죽음 ||
| 사운드 | e_Sound | 몬스터의 사운드 – 공격, 죽음 ||

<br>

3\) 오브젝트 이름 : 상자
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이름 | b_Name | 상자의 이름 ||
| 열기 | b_Open | 플레이어가 상자와 상호작용 시 상자 열림 ||
| 드랍 | b_Drop | 상자가 열리면 아이템을 드랍함 ||
| 사운드 | b_Sound | 상자가 열릴 때 사운드 ||

<br>

4\) 오브젝트 이름 : 검, 갑옷
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이름 | i_Name | 아이템의 이름 ||
| 획득 | i_Get | 검이나 갑옷을 획득할 시 인벤토리 안으로 들어감 ||
| 정보 | i_Info | 아이템의 정보 ||
| 사용 | i_Equip | 플레이어에게 장착 ||
| 공격력 | s_Atk | 장착 시 플레이어의 공격력 상승량 | 검 |
| 체력 | a_Hp | 장착 시 플레이어의 체력 상승량 | 갑옷 |

<br>

5\) 오브젝트 이름 : 코인, 코인UI
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이름 | i_Name | 아이템의 이름 ||
| 정보 | i_Info | 아이템의 정보 ||
| 획득 | c_Get | 코인을 획득할 시 코인UI의 코인 수 증가 ||
| 사용 | c_Use | 상점에서 아이템 구매시 사용<br>사용시 코인UI의 코인 수 감소 ||
| 개수 | c_Amount | 플레이어가 가지고 있는 코인의 개수 표시 | 코인UI |
| 사운드 | c_Sound | 코인을 획득 시 사운드 ||

<br>

6\) 오브젝트 이름 : 물약, 물약UI
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이름 | i_Name | 아이템의 이름 ||
| 정보 | i_Info | 아이템의 정보 ||
| 획득 | l_Get | 물약을 획득 시 인벤토리 안으로 들어간다<br>물약UI의 물약 수 증가 ||
| 사용 | l_Use | 물약 사용 시 플레이어 Hp 회복 ||
| 회복량 | l_Amount | 물약 사용시 플레이어의 Hp 회복량 ||
| 사운드 | l_Sound | 물약 사용 시 사운드 ||
| 이펙트 | l_Effect | 물약 사용 시 이펙트 ||

<br>

7\) 오브젝트 이름 : 포탈
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 충돌 | p_Trigger | 플레이어가 포탈에 닿을 시 다른 맵으로 입장 ||

<br>

8\) 오브젝트 이름 : 스킬UI
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 쿨타임 | s_Cool | 스킬을 사용 후 재사용까지의 대기시간 ||
| 정보 | s_Info | 스킬UI에 마우스를 가져다 놓을시 스킬정보 UI가 나옴 ||
| 공격력 | s_Atk | 스킬의 공격력 수치 ||

<br>

9\) 오브젝트 이름 : NPC(주민, 상점)
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이름 | npc_Name | 상점 NPC의 이름 ||
| 퀘스트 | npc_Quest | 퀘스트 의뢰 |주민|
| 구매 | npc_Buy | 아이템 구매 |상점|
| 판매 | npc_Sell | 아이템 판매 |상점|

<br>

10\) 오브젝트 이름 : 인벤토리
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 보관 | iv_Keep | 아이템을 획득시 인벤토리에 저장 ||
| 사용 | iv_Use | 아이템 사용시 인벤토리에서 삭제<br>장착 아이템일 경우 아이템에 사용중 표시 ||
| 장착 아이템 | iv_Equip | 현재 플레이어의 장착 아이템 확인 ||

<br>

11\) 오브젝트 이름 : 스킬창
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 정보 | s_Info | 스킬 정보 ||

<br>

12\) 오브젝트 이름 : 타이머
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 시간 | d_Time | 던전 내의 제한 시간 표시 ||
| 타임아웃 | timeOut | 제한시간 초과 시 죽음 ||

<br>

13\) 오브젝트 이름 : 배경음악
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 타이틀 | title | 몽환스러운 BGM ||
| 마을 | village | 경쾌하면서 웅장한 BGM ||
| 상점 | store | 부드럽고 여유로운 BGM ||
| 던전 | dungeon | 긴장감이 느낄 수 있는 BGM ||
| 보스 | boss | 긴장감을 고조시키는 BGM ||

<br>

14\) 오브젝트 이름 : 던전선택UI
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 정보 | d_Info | 던전 정보 ||

<br>

15\) 오브젝트 이름 : 베기, 스킬 이펙트
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이펙트 | atk_Effect | 베기, 스킬 이펙트 ||

<br>

16\) 오브젝트 이름 : 미션 UI
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 정보 | mission_Info | 다음 맵을 넘어가기 위한 던전 내의 임무에 대한 정보 ||

<br>

17\) 오브젝트 이름 : 퀘스트 창
  
| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 정보 | quest_Info | 퀘스트 정보 ||
| 보상 | quest_Reward | 퀘스트 보상 ||

<br>

## 5.3 행동 뽑아 보기

<br>

1\) 오브젝트 이름 : 플레이어
  
| 행동 | 영문명칭 | 설명 |
|:----:|:----:|:----:|
| 대기 | idle | 아무런 키도 입력 안 하고 있을시 대기 모션 재생 |
| 앞으로 이동 | f_Move | ↑키 입력 시 앞으로 이동 |
| 뒤로 이동 | b_Move | ↓키 입력 시 뒤로 이동 |
| 오른쪽 이동 | r_Move | →키 입력 시 오른쪽으로 이동 |
| 왼쪽 이동 | l_Move | ←키 입력 시 왼쪽으로 이동 |
| 앞 달리기 | f_Run | ↑키를 연속적으로 ↑↑같이 입력 시 앞으로 달리기 |
| 뒤 달리기 | b_Run | ↓키를 연속적으로 ↓↓같이 입력 시 뒤로 달리기 |
| 오른쪽 달리기 | r_Run | →키를 연속적으로 →→같이 입력 시 오른쪽으로 달리기 |
| 왼쪽 달리기 | l_Run | ←키를 연속적으로 ←←같이 입력 시 왼쪽으로 달리기 |
| 대쉬 | dash | space 키(대쉬 키)를 입력 시 플레이어가 보고 있는 방향으로 순간적인 속도로 빠르게 이동 |
| 공격 | attack | x 키(공격 키) 입력 시 공격 모션 재생 |
| 스킬 | skill | 스킬키 입력 시 사용 스킬에 맞는 모션 재생 |
| 피격 | hit | 몬스터에게 피격 시 피격모션 재생 |
| 죽음 | death | 던전 제한시간 초과 or 플레이어의 Hp가 0이 될 시에 죽는 모션 재생 |
| 승리 | win | 던전 클리어 시에 승리 모션 재생 |

<br>

2\) 오브젝트 이름 : 보스, 몬스터1, 몬스터2, 몬스터3, 보스2, 몬스터4, 몬스터5, 몬스터6
  
| 행동 | 영문명칭 | 설명 |
|:----:|:----:|:----:|
| 대기 | idle | 어떠한 행동도 안할 시에 대기 모션 재생 |
| 이동 | move | 이동 |
| 공격 | attack | 플레이어 발견시에 공격 |
| 피격 | hit | 공격을 받을시에 피격 모션을 재생 및 색이 잠시 붉게 변화하고 원래대로 돌아옴 |
| 죽음 | death | 몬스터의Hp가 0이될시에 죽는 모션 재생 |

<br>

## 5.4 상태 뽑아 보기

<br>

1\) 오브젝트 이름 : 플레이어
  
| 현상태 | 전이상태 | 전이조건 |
|:----:|:----:|:----:|
| 대기 | 이동 | ←, ↑, →, ↓키 입력 |
| 대기 | 달리기 | ←←, ↑↑, →→, ↓↓키 입력 |
| 대기, 이동, 달리기, 공격, 스킬 | 대쉬 | space키 입력 |
| 대기, 이동, 달리기 | 공격 | x키 입력 |
| 대기, 이동, 달리기 | 스킬 | 스킬키 입력 |
| 대기, 이동, 달리기, 대쉬, 공격, 스킬 | 죽음 | 제한시간 초과 혹은 플레이어 Hp가 0 |
| 공격, 스킬 | 승리 | 던전 클리어(보스 몬스터 처치) |
| 이동 | 달리기 | 같은 방향키를 한번 더 입력 |
| 이동, 달리기 | 대기 | 키 미입력 |
| 대기, 이동, 달리기, 공격, 스킬 | 피격 | 몬스터에게 공격 받음 |

<br>

2\) 오브젝트 이름 : 보스, 몬스터1, 몬스터2, 몬스터3, 보스2, 몬스터4, 몬스터5, 몬스터6
  
| 현상태 | 전이상태 | 전이조건 |
|:----:|:----:|:----:|
| 대기 | 이동 | 대기 모션과 이동 모션을 병행 재생 혹은 플레이어가 몬스터의 감지 범위 내에 들어올 시 |
| 이동 | 대기 | 대기 모션과 이동 모션을 병행 재생 |
| 대기, 이동 | 공격 | 플레이어가 몬스터의 공격 범위 내에 들어올 시 |
| 대기, 이동, 공격 | 피격 | 플레이어의 공격 혹은 스킬에 피격시 |
| 대기, 이동, 공격 | 죽음 | 몬스터의 Hp가 0이 될 시 |

<br>

## 5.5 플레이어 캐릭터 속성(파라미터)

| 속성 | 영문명칭  | 설명 | 비고 |
|:----:|:----:|:----:|:----:|
| 이름 | p_Name | 플레이어의 이름 ||
| 레벨 | p_Lv | 플레이어의 레벨 ||
| 경험치 | p_Exp | 플레이어의 경험치 ||
| 체력 | p_Hp | 플레이어의 체력 수치 ||
| 속도 | p_Speed |플레이어의 이동속도 ||
| 공격력 | p_Atk | 플레이어의 공격력 수치 ||
| 상태 | p_State | 플레이어의 상태 – 대기, 이동, 대쉬, 공격, 빈사상태 등 ||
| 사운드 | p_Sound | 플레이어의 사운드 – 이동, 달리기, 대쉬, 공격, 스킬 등 ||

<br>

## 5.6 게임의 규칙

<br>

1\) 핵심 규칙

- 플레이어는 마을에서 스폰되어 게임이 시작되며, 던전에 입장 전에 자유롭게 돌아다닐 수 있다.<br>
- 던전은 마을의 중심에 있는 포탈을 통해서 포탈에 다가가면 던전을 선택할 수 있는 UI가 나오며, 원하는 던전을 선택할 시에 던전으로 입장 수 있다.<br>
- 던전에 입장 후에는 제한시간이 생성되며, 플레이어는 이 제한 시간 안에 던전의 보스에 도달해서 보스를 잡아야 한다.<br>
- 처음에는 일반 몬스터들이 나오며 이들을 공격과 스킬로 처리하면 다음 맵으로 가는 포탈이 생성되고 포탈로 이동하면 다른 몬스터들이 나온다.<br>
- 포탈을 통해 이동하다보면 보스 맵까지 도달하게 되며 보스를 쓰러뜨리면 던전을 클리어하게 된다.<br>
- 보스를 클리어하면 마을로 이동하는 포탈과 아이템이 나오는 상자가 생성된다.<br>
- 상자를 열면 다양한 아이템이 나온다.<br>
- 아이템을 획득 후에는 마을로 이동하는 포탈로 마을로 돌아와 정비를 하면 된다.<br>

2\) 보조 규칙

- 플레이어가 던전에 도전하던 중 Hp가 0이되거나 제한시간이 초과되면 마을로 강제로 이동하게 된다.

<br>

## 5.7 게임에서 사용될 공식
- 스테이지 내의 몬스터를 모두 처치 시에만 다음 맵(다음 스테이지 or 보스 or 마을)으로 가는 포탈이 열린다.
<br><br>

# [개발 요구사항 & 흐름도] <a name='6'></a>

<br>

## 6.1 요구사항
1. 캐릭터<br>
1.1 플레이어 캐릭터는 화면 중앙에 있으며 카메라는 고정된 위치에서 플레이어를 비춤<br>
1.2 캐릭터는 방향키로 움직이며 같은 방향키를 연속으로 입력 시 달림<br>
1.3 SPACE키로 짧은 거리를 이동하는 대쉬 구현<br>
1.4 x키로 기본 공격 구현<br>
1.5 a, s, d, q, w, e키로 스킬 구현<br>
1.6 플레이어가 특정 레벨을 도달할 때 마다 새로운 스킬을 흭득<br>

2. 씬<br>
2.1 씬(타이틀, 로딩, 캐릭터 선택, 마을, 던전) 총 5종류<br>
2.2 씬 변경시에는 로딩 화면을 거쳐 씬 변경<br>

3. 타이틀 씬<br>
3.1 타이틀 씬에는 타이틀, 시작하기 버튼, 종료하기 버튼 배치<br>
3.2 시작하기를 누를 시 캐릭터 선택 씬으로 변경<br>
3.3 종료하기를 누를 시 게임이 종료<br>

4. 캐릭터 선택 씬<br>
4.1 캐릭터 선택 씬에서 캐릭터를 선택할 시 캐릭터에 대한 정보 UI와 시작하기 버튼이 배치<br>
4.2 시작하기를 누를 시 마을로 씬 변경<br>

5. 메인 씬<br>
5.1 마을은 외곽은 성벽 세우기, 북쪽에는 외곽 성벽의 텍스쳐와 같은 오브젝트로 성 만들기, 성을 만든 오브젝트를 제외한 나머지 오브젝트로 마을을 구성<br>
5.2 마을과 게임 씬에서 화면 UI로 캐릭터의 HP, 경험치, 스킬, 레벨, 코인 UI와 캐릭터 정보 버튼, 퀘스트 버튼, 스킬 버튼, 인벤토리 버튼, 옵션 버튼 배치<br>
5.3 마을에는 던전으로 이동할 수 있는 포탈과 오브젝트 목록을 참고하여 NPC(상점, 퀘스트, 일반) 배치하는데 퀘스트 NPC와 일반 NPC의 경우는 서로 구분되는 NPC로 배치<br>

6. NPC<br>
6.1 상점은 아이템 구매와 판매 가능<br>
6.2 특정 NPC의 경우 퀘스트를 제공<br>
6.3 퀘스트는 수락할 수도 거절할 수도 있음<br>
6.4 퀘스트는 클리어할 시 정해진 보상을 얻을 수 있음<br>

7. 던전 씬<br>
7.1 던전은 숲을 배경<br>
7.2 (메인씬과 동일) 마을과 게임 씬에서 화면 UI로 캐릭터의 HP, 경험치, 스킬, 레벨, 코인 UI와 캐릭터 정보 버튼, 퀘스트 버튼, 스킬 버튼, 인벤토리 버튼, 옵션 버튼 배치<br>
7.3 던전에 입장 시 오른쪽에 미션이 나오며 미션을 해결해야 다음 맵으로 가는 포탈이 열림<br>
7.4 플레이어는 공격과 스킬을 통해 몬스터들을 공격하여 처치<br>
7.5 플레이어 HP가 없는 경우 물약을 통해 회복<br>
7.6 보스방에 입장 시 보스를 잠시 클로즈업 후 다시 원래 화면으로 변경<br>
7.7 포탈과 충돌시 씬 전환<br>

8. BGM<br>
8.1 타이틀씬에서는 타이틀BGM 재생<br>
8.2 캐릭터 선택 씬에서는 밤의 숲의 효과음 재생<br>
8.3 마을에서는 마을BGM이 재생<br>
8.4 던전에서는 던전BGM 재생<br>
8.5 보스방에 입장 시 BGM이 던전BGM에서 보스BGM으로 변경<br>

9. UI<br>
9.1 UI는 UI의 우측상단 x버튼으로 닫기 가능<br>
9.2 캐릭터 정보 버튼을 누를 시 캐릭터가 현재 착용하고 있는 장비 및 캐릭터의 능력치가 나오는 UI생성<br>
9.3 퀘스트 버튼을 누를 시 현재 진행 중인 퀘스트 정보가 나오는 UI생성<br>
9.4 스킬 버튼을 누를 시 캐릭터의 스킬 정보를 볼 수 있는 UI생성<br>
9.5 인벤토리 버튼을 누를 시 현재 캐릭터가 착용 중인 장비 정보와 소지 중인 아이템들을 볼 수 있는 UI생성<br>
9.6 인벤토리에는 아이템 정렬, 이동, 삭제, 슬롯 확장 기능 구현<br>
9.7 옵션 버튼을 누를 시 소리 조절 등의 기능과 게임종료 버튼을 배치 및 기능 구현<br>
9.8 던전으로 이동할 수 있는 포탈에게 다가가면 입장하고 싶은 던전을 선택할 수 있는 UI생성<br>
9.9 원하는 던전을 선택 시 던전의 정보와 입장하기 버튼이 있는 UI가 추가 생성<br>
9.10 입장하기 버튼을 누를 시 던전 씬으로 변경<br>
9.11 대쉬를 사용시 쿨타임을 알 수 있는 UI 제작<br>

10. 아이템<br>
10.1 검, 갑옷, 물약을 획득 시에는 인벤토리 안으로 들어감<br>
10.2 경험치를 획득 시에는 플레이어의 현재 경험치량이 변함<br>
10.3 경험치가 100%가 넘을 시 플레이어의 레벨이 1 증가<br>
10.4 코인을 획득 시에는 코인 UI의 코인 숫자가 증가<br>
10.5 물약은 획득시에는 갯수가 중첩된다.<br>
10.6 물약은 우클릭시 사용 가능<br>
10.7 물약 사용시 플레이어의 HP 회복<br>

11. 몬스터<br>
11.1 일반몬스터는 배회를 하고 있으며 플레이어가 감지 범위 내에 들어올 시 추격<br>
11.2 몬스터는 피격시 몸이 잠시 붉게 변한 후 원래대로 돌아옴<br>
11.3 보스 몬스터는 배회 없이 플레이어를 항상 감지하고 추격<br>
11.4 보스 몬스터가 기술을 사용할 시에는 미리 공격의 경로 및 범위가 바닥에 표시<br>
11.5 보스 몬스터를 쓰러뜨리면 상자가 생성<br>
11.6 상자를 열면 랜덤으로 보상(검, 갑옷, 물약, 코인, 경험치)이 생성<br>

<br>

## 6.2 시간별 흐름도 flowchart
<img src="./img/Flowchart.png" height="500">
<br>

## 6.3 키보드 이벤트에 대한 흐름도
<img src="./img/키 이벤트.png" height="500">
<br>

## 6.4 용어정리
<img src="./img/용어정리표.png" height="1200">

<br><br>

# [스토리보드] <a name='7'></a>
<img src="./img/StoryBoard.png"  height="500">

<br><br>

# [프로토타입 개발 요구사항 (6주개발)] <a name='8'></a>


1. 씬(타이틀, 로딩, 캐릭터 선택, 마을, 던전) 총 5종류 (2.1)

2. 플레이어 캐릭터는 화면 중앙에 있으며 카메라는 고정된 위치에서 플레이어를 비춤 (1.1)

3. 캐릭터는 방향키로 움직이며 같은 방향키를 연속으로 입력 시 달리기 구현 (1.2)

4. SPACE키로 짧은 거리를 이동하는 대쉬 구현 (1.3)

5. 포탈과 충돌 시 씬 전환 (7.7)

6. 씬 변경시에는 로딩 화면을 거쳐 씬 변경 (2.2)

7. 마을은 외곽은 성벽 세우기, 북쪽에는 외곽 성벽의 텍스쳐와 같은 오브젝트로 성 만들기, 성을 만든 오브젝트를 제외한 나머지 오브젝트로 마을을 구성 (5.1)

8. 마을에는 던전으로 이동할 수 있는 포탈과 오브젝트 목록을 참고하여 NPC(상점, 퀘스트, 일반) 배치하는데 퀘스트 NPC와 일반 NPC의 경우는 서로 구분되는 NPC로 배치 (5.3)

9. 마을에서는 마을BGM이 재생 (8.3)

10. 마을과 게임 씬에서 화면 UI로 캐릭터의 HP, 경험치, 스킬, 레벨, 코인 UI와 캐릭터 정보 버튼, 퀘스트 버튼, 스킬 버튼, 인벤토리 버튼, 옵션 버튼 배치 (5.2, 7.2)

11. 던전은 숲을 배경으로 나무와 풀 오브젝트를 배치하여 제작 (7.1)

12. 던전에서는 던전BGM 재생 (8.4)

13. 보스방에 입장 시 BGM이 던전BGM에서 보스BGM으로 변경 (8.5)

14. 옵션 버튼을 누를 시 소리 조절 등의 기능과 게임종료 버튼을 배치 및 기능 구현 (9.7)

15. 버튼을 눌러 나오는 UI는 UI의 우측상단 x버튼으로 닫기 가능 (9.1)

16. 인벤토리 버튼을 누를 시 현재 캐릭터가 착용 중인 장비 정보와 소지 중인 아이템들을 볼 수 있는 UI생성 (9.5)

17. 인벤토리에는 아이템 정렬, 이동, 삭제, 슬롯 확장 기능 구현 (9.6)

18. 검, 갑옷, 물약을 획득 시에는 인벤토리 안으로 들어감 (10.1)

19. 물약은 획득시에는 갯수가 중첩된다. (10.5)

20. 물약은 우클릭시 사용 가능 (10.6)

21. 물약 사용시 플레이어의 HP 회복 (10.7)

22. 던전으로 이동할 수 있는 포탈에게 다가가면 입장하고 싶은 던전을 선택할 수 있는 UI생성 (9.8)

23. 원하는 던전을 선택 시 던전의 정보와 입장하기 버튼이 있는 UI가 추가 생성 (9.9)

24. 입장하기 버튼을 누를 시 던전 씬으로 변경 (9.10)

25. x키로 기본 공격 구현 (1.4)

26. 옵션 버튼을 누를 시 소리 조절 등의 기능과 게임종료 버튼을 배치 및 기능 구현 (9.7)

27. 대쉬를 사용시 쿨타임을 알 수 있는 UI 제작 (9.11)

<br><br>

# [프로토타입 개발작업 일정 (6주개발)] <a name='9'></a>

1주차<br><br>
1.씬(타이틀, 로딩, 캐릭터 선택, 마을, 던전) 총 5종류 (2.1) 80% <br><br>
2. ~~플레이어 캐릭터는 화면 중앙에 있으며 카메라는 고정된 위치에서 플레이어를 비춤 (1.1) 100%~~ <br><br>
3. ~~캐릭터는 방향키로 움직이며 같은 방향키를 연속으로 입력 시 달리기 구현 (1.2) 100%~~<br>

<br>

2주차 <br><br>
1.~~씬(타이틀, 로딩, 캐릭터 선택, 마을, 던전) 총 5종류 (2.1) 100%~~ <br><br>
4. ~~SPACE키로 짧은 거리를 이동하는 대쉬 구현 (1.3) 100%~~ <br><br>
5. ~~포탈과 충돌 시 씬 전환 (7.7) 100%~~ <br><br>
6. ~~씬 변경시에는 로딩 화면을 거쳐 씬 변경 (2.2) 100%~~ <br><br>
7. ~~마을은 외곽은 성벽 세우기, 북쪽에는 외곽 성벽의 텍스쳐와 같은 오브젝트로 성 만들기, 성을 만든 오브젝트를 제외한 나머지 오브젝트로 마을을 구성 (5.1) 100%~~ <br><br>
8. ~~마을에는 던전으로 이동할 수 있는 포탈과 오브젝트 목록을 참고하여 NPC(상점, 퀘스트, 일반) 배치하는데 퀘스트 NPC와 일반 NPC의 경우는 서로 구분되는 NPC로 배치 (5.3) 100%~~ <br>

<br>

3주차 <br><br>
9. 마을에서는 마을BGM이 재생 (8.3) <br><br>
10. 마을과 게임 씬에서 화면 UI로 캐릭터의 HP, 경험치, 스킬, 레벨, 코인 UI와 캐릭터 정보 버튼, 퀘스트 버튼, 스킬 버튼, 인벤토리 버튼, 옵션 버튼 배치 (5.2, 7.2) <br><br>
16. 인벤토리 버튼을 누를 시 현재 캐릭터가 착용 중인 장비 정보와 소지 중인 아이템들을 볼 수 있는 UI생성 (9.5) <br><br>
17. 인벤토리에는 아이템 정렬, 이동, 삭제 및 배낭, 정렬 기능 구현 (9.6) <br><br>
18. 검, 갑옷, 물약을 획득 시에는 인벤토리 안으로 들어감 (10.1) <br>
