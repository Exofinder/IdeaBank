# IdeaBank

### 머릿속에 떠오르는 모든 아이디어를 여기에 추가해주세요. 아무리 사소하더라도 Welcome

- Habitable 확률을 input으로 해서, ex)3~5%의 확률로 habitable한 행성만 볼 수 있는 필터 추가
- 배경음악, 전환 시 효과음 추가하기?

---
---
### 여기부터는 HWO주제의 [Details](https://www.spaceappschallenge.org/nasa-space-apps-2024/challenges/navigator-for-the-habitable-worlds-observatory-hwo-mapping-the-characterizable-exoplanets-in-our-galaxy/?tab=details)란에 있는 모든 내용을 이해하기 쉽게 정리한것임.

## Challenge Overview 원문
Your challenge is to develop an app that enables users to visualize the observational paths across our galaxy to the known exoplanets in the solar neighborhood as a function of their potential for characterization by HWO.

## Background
- exoplanet들은 주로 indirect method로 발견됨.
- HWO는 exoplanet를 directly image하고, earth-like bodies 행성의 지식을 넓히기 위한 목적임.
- HWO 미션을 계획할 때, 망원경의 파라미터가 관측가능 행성들의 파라미터에 어떤 영향 미치는지 이해하는것은 매우 중요함.
- 이를 위한 한가지 방법: currently known exoplanets들을 visualize해보면서 망원경이 어떤 파라미터를 가질때 어떤 것들이 보이는지 확인해 보는 것. 특히, 두가지를 고려할 수 있음:
- (1) exoplanetary system의 거리가 멀수록 중심별은 희미하고, 중심별~행성 거리 가까워짐.
- (2) telescope의 반지름이 클수록 중심별과 exoplanet를 separate하는 능력 좋아짐.

## Objectives
- HWO에 보일 가능성을 고려하여 known exoplanets들을 visualize하는 app을 만드시오.
- 현재 파라미터로 어떤 exoplanets들이 보이고, telescope 파라미터를 one or more을 바꿨을 때 어떤 새로운 exoplanets들이 detectable해질지 보여주세요.
- 망원경 주주들에게 HWO의 잠재적인 성능을 보여주세요.
- 이런 기능을 추가하세요:
- (1) 매개변수에 따른 망원경 관측 보여주기.
- (2) 특정 매개변수를 변화시킬 때의 변화 보여주기.
- (3) 별 주위의 궤도, 모항성의 항성 등급(stellar class) 등의 요소에 따라 관측 난이도별로 나누어 외계행성 집단 보여주기.
- (4) 관측이 가장 쉬운 별, 관측이 challenging한 별을 사용자가 이해하기 쉽도록 나누는 feature를 추가하세요.

## Possible Considerations
- Target Audience: 다양한 NASA stakeholders; ex) 시민, 정치인, 매니저.
- 이런 기능을 추가하세요:
- (1) telescope나 장비의 파라미터를 바꾸는 것이 관측 결과에 미치는 영향.
- (2) 외계행성이나 중심별 파라미터에 따라서 구분해서 '별들 간의 유사성', 'HWO로 관측 가능성' 등을 색깔별로 구분해서 우주 화면에 잘 나타나도록.
- (3) user interactive하게: 사용자가 관측 시 여러 파라미터를 조절할 수 있도록 할 것.

