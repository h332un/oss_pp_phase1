# 구현 목표
###  "톰을 피해라!!!"는 파이썬 Pygame 라이브러리를 사용하여 제작된 간단한 아케이드 게임입니다. 플레이어는 제리를 조종하여 화면 위에서 떨어지는 톰들을 피해야 합니다. 톰과 충돌하면 제리가 화를 내며 게임이 종료됩니다. 제한 시간 동안 최대한 오래 버티는 것이 목표입니다.

# 구현 기능

* 좌우 이동: 왼쪽/오른쪽 화살표 키를 사용하여 캐릭터를 좌우로 움직이는 기능
* 랜덤한 위치에서 톰이 계속해서 떨어짐
* 톰과 충돌하면 캐릭터가 화난 제리로 변하고 잠시 후 게임이 종료됨
* 남은 시간을 표시하는 기능


# Reference
[1] https://github.com/pygame/pygame "pygame" 

# 지원 Operating Systems 및 실행 방법

## 지원 Operating Systems
|OS| 지원 여부 |
|-----|--------|
|windows | :o:  |
| Linux  | :o: |
|MacOS  | :x:  |

## 실행 방법
### Windows



### Linux



# 실행 예시

![tomjerry_gif](https://github.com/catcat0902/oss_pp_phase1/assets/164159970/37afe55e-fdf1-4bfb-ab36-981f34d9d7cc)


# TODO List
* 톰들과 제리의 충돌 영역이 조금 더 세밀할 필요가 있음 지금은 영역이 딱 닿지 않아도 충돌로 쳐지곤 함
* 충돌 후 화내는 제리가 나타나 있는 시간이 너무 짧음
* 충돌 후 프로그램이 꺼지는 것이 아니라 다시 시작할 수 있으면 좋겠음
