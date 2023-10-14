# UnityProject
### Unity 엔진으로 제작한 프로젝트입니다.
### Directory 설명을 참고하여 파일 확인 부탁 드립니다.
### 1. Dungeon_Version2 소스 위치
  + Assets > Script
    + ArrowAct.cs: 필드 위치 기본설정
    + DataManager.cs: Dungeon_Data.xml 파일을 불러오기 위한 기본 과정
    + Field.cs: 필드에 사용한 카드 노출
    + GameManager.cs: 게임진행에 필요한 기능
    + Inven.cs: 각 플레이어마다 갖는 아이템/파워 카드 저장소 및 노출
    + Item.cs: 아이템 카드 불러오기 및 노출
    + LoadMap.cs: 지도 보여주기
    + LoadRoom.cs: 현재 무슨 방인지 노출
    + MouseEvent.cs: 카드와 마우스의 상호작용 이벤트 노출
    + Player.cs: 플레이어 기본설정 및 카드 사용 시, 효과 노출
    + Power.cs: 파워카드 기본설정
    + Select.cs: 특정카드 사용 시, 플레이어 선택관련 소스
    + Stage.cs: 각 방마다 xml 파일 내용 불러오기/노출 및 플레이어와 상호작용 소스
    + StageManager.cs: 방이 일정 수준의 확률로 노출되기 위한 소스
    + StarUI.cs: 게임시작 시, 인원수 선택
    + UIManager.cs: UI 관련 기본 설정
  + Assets > Resources
    + Dungeon_Data.xml: 게임에 필요한 몬스터, 아이템 카드, 현재 방 등 기본 사항 작성
### 2. Niddangneddang 소스 위치
  + Assets > Script
    + Clicktile.cs: 타일 클릭 확인 및 색 변경
    + GameStart.cs: 게임 시작화면 불러오기
    + PaintAnim.cs: 적용하지 않은 스크립트
    + Quit.cs: 창 닫기
    + Result.cs: 게임결과 노출
    + Score.cs: 각 플레이어 점수 노출
    + Tileprefabs.cs: 타일 생성
    + TimeManager.cs: 남은 시간 노출
    + Timecolor.cs: 컴퓨터가 타일 선택 시, 색 변경
### 3. Trash Filght
  + Assets > Script
    + Background.cs: 배경화면
    + Coin.cs: enemy 보상 및 충돌
    + Enemy.cs: weapon과 상호작용 소스
    + EnemySpawner.cs: enemy 랜덤 노
    + GameManager.cs: 코인 증감, 게임오버, 게임 재시
    + Player.cs: 플레이어 마우스 움직임, weapon 쏘기, enemy 상호작
    + Weapon.cs: 기본 위치 및 기초 세팅
