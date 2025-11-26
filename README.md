# Sky Dome Blueprint (BP_SkyDome) Demo

언리얼 라이팅 캠프에서 제작한 스카이 돔(Sky Dome) 기반의 HDRI 환경을 쉽게 변경하고 제어하기 위해 제작된 **BP_SkyDome 블루프린트 데모**입니다.  
스카이 돔의 HDRI 텍스처 변경, 밝기 조절, 색상 틴트, 스케일 조절, SkyLight Recapture 연동 기능 등을 제공합니다.

---

## Preview

### Main Scene

![Screenshot_L_Week5SkyDomeDemo_Scene](Images/skydome_scene.png)

### Properties

![Screenshot_BP_SkyDome_Properties](Images/skydome_properties.png)

---

## Blueprint Overview

변수는 총 세 가지 카테고리로 구성됩니다.

### Textures (텍스처 관련 변수)

| 변수명             | 설명                                          |
| ------------------ | --------------------------------------------- |
| **SkyDomeTexture** | 스카이 돔의 HDRI 텍스처를 교체할 수 있습니다  |
| **TintColor**      | HDRI 전체에 컬러 Tint 값을 적용할 수 있습니다 |

### Properties (프로퍼티 값)

| 변수명         | 설명                                      |
| -------------- | ----------------------------------------- |
| **Brightness** | HDRI의 Intensity 값을 조절합니다          |
| **Scale**      | 스카이 돔 메시의 전체 스케일을 조절합니다 |

### References (외부 레퍼런스)

| 변수명       | 설명                                                                                         |
| ------------ | -------------------------------------------------------------------------------------------- |
| **SkyLight** | SkyLight 레퍼런스를 연결하여 스카이 돔 값 변경 시 SkyLight Recapture를 자동으로 트리거합니다 |

---

## Requirements

| 항목                         | 내용        |
| ---------------------------- | ----------- |
| Unreal Engine Version        | **5.6.1**   |
| OS / Development Environment | **Windows** |

---

## Installation & Usage

1. 프로젝트 또는 블루프린트 어셋을 다운로드합니다.
2. 언리얼 프로젝트에 임포트합니다.
3. 레벨에 **BP_SkyDome** 액터를 배치합니다.
4. 세부 디테일(Details) 패널에서 변수들을 조정해 테스트해 볼 수 있습니다.

---

## Downloads

| 항목                              | 링크                                                                               |
| --------------------------------- | ---------------------------------------------------------------------------------- |
| **Sky Dome Blueprint Project**    | https://drive.google.com/file/d/1L2xN6WbVYQbwEjCeUXYfBM7pGwzztAII/view?usp=sharing |
| **Sky Dome Blueprint Asset Only** | https://drive.google.com/file/d/1FrMmNNsxjEddlnZO3P-EGZtGpzGDCXrP/view?usp=sharing |

---

## License

본 프로젝트는 **MIT License** 하에 제공됩니다.

---

## Contact

sungkukshawnpark@gmail.com
