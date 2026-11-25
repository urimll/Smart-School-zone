# 🚸 Smart School Zone — 어린이보호구역 스마트 도로 모형

어린이보호구역(스쿨존) 도로와 주차장을 축소 모형으로 만들고, 센서와 액추에이터로 **안전·편의 기능을 자동화**한 IoT 하드웨어 프로젝트입니다.

<p align="center">
  <img src="media/photos/top_view.jpg" width="49%" alt="모형 전체 (위에서 본 모습)">
  <img src="media/photos/side_view.jpg" width="49%" alt="모형 측면 (과속 측정 구간과 LCD)">
</p>

> ⚠️ **소스 코드 안내** — 원본 코드는 유실되어 이 저장소에는 포함되어 있지 않습니다. 동작 영상, 사진, 계획서로 프로젝트를 기록합니다.

---

## ✨ 주요 기능

| 기능 | 설명 | 사용 부품 |
|---|---|---|
| 🅿️ **주차장 자동 차단기** | 입구의 초음파 센서가 차량을 감지하면 서보모터 차단기가 열리고, 통과 후 닫힘 | 초음파 센서, 서보모터 |
| 🔢 **잔여 주차면 표시** | 입·출차에 따라 남은 주차 공간 수를 LCD에 표시 | 16x2 LCD |
| 🚗 **과속 측정** | 도로를 따라 설치한 두 초음파 센서의 감지 시간 차로 속도를 계산해 전광판에 표시 | 초음파 센서 ×2, 16x2 LCD |
| 🚦 **보행자 신호등** | 횡단보도 신호등의 점등 상태 전환 | LED |
| 💡 **자동 가로등** | 주변이 어두워지면 가로등이 자동으로 켜짐 | LED |

---

## 🎬 시연 영상

> GIF는 미리보기이며, 제목을 누르면 원본 영상(mp4)을 볼 수 있습니다.

### 전체 동작
[**01. 전체 동작**](media/videos/01_overview.mp4)

<img src="media/gifs/01_overview.gif" width="420">

### 🅿️ 주차장 차단기 & 잔여 주차면
| [02. 차단기 A](media/videos/02_parking_gate_a.mp4) | [03. 차단기 B](media/videos/03_parking_gate_b.mp4) |
|---|---|
| <img src="media/gifs/02_parking_gate_a.gif" width="400"> | <img src="media/gifs/03_parking_gate_b.gif" width="400"> |

| [04. 잔여 주차면 LCD](media/videos/04_parking_count_lcd.mp4) | [05. 차단기 C](media/videos/05_parking_gate_c.mp4) |
|---|---|
| <img src="media/gifs/04_parking_count_lcd.gif" width="400"> | <img src="media/gifs/05_parking_gate_c.gif" width="400"> |

### 🚦 횡단보도 신호등 & 💡 야간 가로등
| [06. 보행자 신호등](media/videos/06_crosswalk_signal.mp4) | [07. 야간 자동 가로등](media/videos/07_streetlight_night.mp4) |
|---|---|
| <img src="media/gifs/06_crosswalk_signal.gif" width="400"> | <img src="media/gifs/07_streetlight_night.gif" width="400"> |

---

## 🗂️ 저장소 구조

```
smart-school-zone/
├── README.md
├── docs/            # 프로젝트 계획서
└── media/
    ├── photos/      # 모형 사진
    ├── videos/      # 시연 영상 (mp4)
    └── gifs/        # README 미리보기용 GIF
```

---

## 👩‍💻 만든 사람

**이유림** ([@urimll](https://github.com/urimll))
