# Assist Core

Assist 시리즈(Reel · Mine · Farm · Lumber Assist)가 같이 쓰는 기반 라이브러리예요. Made by seolwoni

각 모드 jar 안에 같이 들어가 있어서 따로 설치할 필요는 없어요. 여러 Assist 모드를 함께 넣으면 그중 가장 새 버전의 코어 하나만 쓰여요.

## 들어 있는 것
- **움직임**: 부드러운 회전(가속·감속), 조준, 걷기, 사람 같은 딜레이 (`util.Body`, `util.Human`)
- **작업 엔진**: 작업 큐와 실패 처리 (`engine.Action`, `engine.ActionQueue`)
- **블록·인벤토리 도우미**: `util.Blocks2`, `util.InvBase`
- **상자 보관**: K키 상자 지정, 담을 상자 고르기 (`storage.Chests`, `storage.ChestEntry`)
- **HUD**: 움직이고 크기를 바꾸는 HUD 박스, 모든 모드 HUD 한 번에 편집, **H키로 모든 Assist HUD 숨기기** (`hud.*`)
- **설정 화면 부품**: 슬라이더, 아이템·블록 고르기 화면 (`gui.*`)
- **알림**: 타이틀, 액션바, 채팅, 소리 (`util.Alerts`)

## 개발
각 모드 저장소의 `core/` 폴더는 이 저장소의 복사본이에요. 코어는 여기서만 고치고 각 모드로 복사해요.
