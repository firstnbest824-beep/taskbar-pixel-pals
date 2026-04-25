# Taskbar Pixel Pals

<p align="center">
  <a href="./README.md">English</a> | 한국어
</p>

Taskbar Pixel Pals는 작업 표시줄 위에 작은 픽셀 동물들이 올라오는 Windows 앱입니다.

복잡한 위젯 플랫폼이 아니라, 데스크톱에 가볍고 귀여운 움직임을 더하는 작은 앱을 목표로 만들었습니다.

<p align="center">
  <img src="./docs/images/taskbar-pixel-pals-hero.png" alt="Taskbar Pixel Pals hero image" width="100%" />
</p>

## 링크

- 제품 페이지: [firbe-labs.netlify.app/products/taskbar-pixel-pals](https://firbe-labs.netlify.app/products/taskbar-pixel-pals/)
- 최신 릴리즈: [GitHub Releases](https://github.com/firstnbest824-beep/taskbar-pixel-pals/releases/latest)

## 어떤 앱인가요

Taskbar Pixel Pals는 작업 표시줄 상태를 읽고, 그 위치에 맞춰 작은 캐릭터를 띄워서 데스크톱이 조금 더 살아 있는 것처럼 보이게 합니다.

현재 MVP에는 아래 기능이 들어 있습니다.

- 캐릭터 4종: `Cow`, `Penguin`, `Duck`, `Dog`
- 모션 프로필 3종: `Calm`, `Playful`, `Bouncy`
- 크기 프리셋 3종: `Small`, `Medium`, `Large`
- 일반 hover 위치 보정
- preview hover 위치 보정
- 앱 아이콘별 캐릭터 랜덤화
- 앱 아이콘별 모션 랜덤화
- 전체 화면 실행 중 오버레이 숨김
- 설정 로컬 저장

## 다운로드

> 어떤 파일을 받아야 할지 헷갈리면 `TaskbarPixelPalsSetup.exe`부터 받으면 됩니다.

최신 릴리즈에는 아래 세 가지 다운로드 옵션이 있습니다.

| 파일 | 추천 대상 | 설명 |
| --- | --- | --- |
| `TaskbarPixelPalsSetup.exe` | 대부분의 사용자 | 추천 다운로드입니다. 일반 사용자는 이 설치 파일을 받으면 됩니다. |
| `TaskbarPixelPals.U2OverlaySpike.exe` | 설치 없이 실행 | 설치 프로그램 없이 바로 열 수 있는 단일 실행 파일입니다. |
| `taskbar-pixel-pals-windows-x64.zip` | ZIP으로 받기 | 설치 없이 쓰는 버전을 ZIP으로 묶은 파일입니다. |

## 설치

### 추천: Setup EXE

1. [최신 릴리즈 페이지](https://github.com/firstnbest824-beep/taskbar-pixel-pals/releases/latest)를 엽니다.
2. `TaskbarPixelPalsSetup.exe`를 다운로드합니다.
3. 설치 파일을 실행합니다.
4. 설치 후 시작 메뉴에서 `Taskbar Pixel Pals`를 실행합니다.

현재 설치 프로그램은 아래를 처리합니다.

- 로컬 앱 디렉터리에 설치
- 바탕화면 바로가기 생성 가능
- 제거 항목 생성
- 설치 직후 앱 실행 가능

### 설치 없이 EXE 실행

설치 없이 바로 실행하고 싶다면:

1. 최신 릴리즈에서 `TaskbarPixelPals.U2OverlaySpike.exe`를 다운로드합니다.
2. 원하는 폴더에 둡니다.
3. 바로 실행합니다.

### ZIP 파일

압축 파일로 받고 싶다면:

1. `taskbar-pixel-pals-windows-x64.zip`를 다운로드합니다.
2. 압축을 풉니다.
3. 압축 해제한 폴더 안의 실행 파일을 실행합니다.

## 첫 실행

처음 실행할 때 Windows SmartScreen 경고가 뜰 수 있습니다. 인디 데스크톱 앱이라 초기에는 이런 경고가 뜰 수 있습니다.

그럴 때는:

1. `추가 정보`를 누르고
2. `실행`을 누르면 됩니다.

## 사용 방법

### 1. 앱 실행

Taskbar Pixel Pals를 실행하면 설정창이 열리고 작업 표시줄에서 바로 동작을 시작합니다.

설정창이 이 앱의 메인 제어 UI입니다.

### UI 제어 가이드

<p align="center">
  <img src="./docs/images/taskbar-pixel-pals-settings-ui-annotated.png" alt="Taskbar Pixel Pals control guide" width="420" />
</p>

1. `Character`
   기본으로 사용할 캐릭터를 고르는 영역입니다.
2. `Randomize character per icon`
   작업 표시줄 앱마다 다른 캐릭터가 보이게 하고 싶을 때 켭니다.
3. `Motion`
   기본 모션 스타일을 고르는 영역입니다.
4. `Randomize motion per icon`
   작업 표시줄 앱마다 다른 움직임이 나오게 하고 싶을 때 켭니다.
5. `Scale`
   캐릭터 크기를 `Small`, `Medium`, `Large` 중에서 고릅니다.
6. `Hide overlay while a fullscreen app is active`
   게임, 영상, 전체 화면 작업 중에는 캐릭터가 보이지 않게 하고 싶다면 켭니다.
7. `Normal hover position`
   preview 창이 열리기 전, 일반 작업 표시줄 아이콘 hover 상태에서 캐릭터 위치를 보정합니다.
8. `Preview hover position`
   Windows preview 창이 열린 상태에서 캐릭터 위치를 보정합니다.
9. `Close / Apply`
   `Apply`는 현재 설정을 저장하고 창을 최소화합니다. `Close`는 앱을 종료합니다.

위치 보정 메모:

- `Normal hover position`은 기본 아이콘 hover 상태용입니다.
- `Preview hover position`은 preview 창이 열린 상태용입니다.
- `X`는 좌우 이동입니다.
- `Y`는 상하 이동입니다.
- 현재 UI 기준으로 `Y`가 음수면 아래로, 양수면 위로 움직입니다.

### 2. 캐릭터 고르기

고정 캐릭터 하나를 선택해서 쓸 수 있습니다.

- `Cow`
- `Penguin`
- `Duck`
- `Dog`

또는 앱 아이콘마다 다른 캐릭터가 보이게 할 수도 있습니다.

### 3. 모션 프로필 고르기

움직임 스타일은 아래 세 가지 중에서 고를 수 있습니다.

- `Calm`
- `Playful`
- `Bouncy`

또는 앱 아이콘마다 다른 움직임이 나오게 할 수 있습니다.

### 4. 크기 고르기

현재 크기 프리셋은 아래와 같습니다.

- `Small` -> `112`
- `Medium` -> `128`
- `Large` -> `160`

### 5. 작업 표시줄 위치 보정

디스플레이 배율, 작업 표시줄 위치, preview 창 크기, 시스템 환경에 따라 캐릭터 위치가 약간씩 어긋날 수 있습니다.

이럴 때는 아래 값을 조정하면 됩니다.

- `Hover position X/Y`
- `Preview hover position X/Y`

각 모드의 의미:

- `Normal hover position`
  일반 작업 표시줄 아이콘 hover 상태에서 캐릭터가 뜨는 위치를 조정합니다.
- `Preview hover position`
  preview 창이 열렸을 때 캐릭터가 보이는 위치를 조정합니다.

추가 메모:

- `X`는 좌우 이동입니다.
- `Y`는 상하 이동입니다.
- 현재 UI 기준으로 `Y`가 음수면 아래로, 양수면 위로 움직입니다.
- preview 창에서 캐릭터가 너무 높거나 낮아 보이면 `Preview hover position`을 조정하면 됩니다.

### 6. 전체 화면 숨김

이 옵션을 켜면 전체 화면 앱이 활성화되어 있을 때 오버레이가 자동으로 숨겨집니다.

게임, 영상, 전체 화면 작업을 방해하지 않게 하고 싶을 때 유용합니다.

### 7. 설정 저장

`Apply`를 누르면 현재 설정이 저장됩니다.

현재 빌드에서는 설정을 로컬에 저장하고, 적용 후 설정창을 최소화합니다.

## 설정 저장 위치

Taskbar Pixel Pals는 설정을 아래 위치에 로컬로 저장합니다.

`%LOCALAPPDATA%\FirbeLabs\TaskbarPixelPals\settings.json`

## 개인정보

Taskbar Pixel Pals는 로컬에서만 동작합니다.

- 로그인 없음
- 계정 없음
- 클라우드 동기화 없음
- 데스크톱 내용 업로드 없음

캐릭터를 올바른 위치에 배치하기 위해 작업 표시줄 hover 상태와 preview 상태만 읽습니다.

## 현재 상태

이 버전은 첫 공개 MVP 릴리즈입니다.

현재 초점은 아래와 같습니다.

- 캐릭터의 느낌
- preview 창 위치 안정화
- 가벼운 데스크톱 유틸리티 감각
- 빠른 로컬 커스터마이징

## 문제 해결

### 캐릭터가 너무 높거나 낮게 떠요

설정에서 `Hover position Y` 또는 `Preview hover position Y`를 조정해서 작업 표시줄에 맞춰 주세요.

### preview 위에 걸친 포즈가 조금 어색해요

`Preview hover position X/Y`를 조정해서 preview 창에서 보이는 위치를 미세 보정하면 됩니다.

### Normal hover와 Preview hover 중 뭘 바꿔야 할지 모르겠어요

아래 기준으로 보면 됩니다.

- `Normal hover position`: 기본 아이콘 hover 상태
- `Preview hover position`: preview 창이 열린 상태

### 전체 화면 앱 실행 중 아무 것도 안 보여요

`Fullscreen suppression` 옵션이 켜져 있는지 확인해 주세요.

## Firbe Labs

Taskbar Pixel Pals는 [Firbe Labs](https://firbe-labs.netlify.app/)에서 만들고 있습니다.

업데이트와 릴리즈 노트는 아래에서 확인할 수 있습니다.

- [제품 페이지](https://firbe-labs.netlify.app/products/taskbar-pixel-pals/)
- [Releases](https://github.com/firstnbest824-beep/taskbar-pixel-pals/releases)
