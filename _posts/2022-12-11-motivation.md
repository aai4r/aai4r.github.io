---
layout: post
title: 연구의 필요성
tags: [연구필요성]
categories: Motivation
---

최근 식당, 호텔, 전시, 교육 등 다양한 응용 분야에 서비스 로봇이 활용되고 있습니다. 인공지능의 발달로 말미암아 음성인식과 합성, 대화 관리, 실내외 자율주행 성능이 비약적으로 발전하여 유용한 서비스를 제공할 수 있게 된 것입니다. 본 과제는 향후 실환경에 배치되는 서비스 로봇의 규모가 더욱 커지고, 응용 영역이 더 확대되며, 서비스 기능이 더 확장될 미래를 대비하여 보다 향상된 서비스 로봇 지능을 개발하는 것을 목표로 합니다. 서비스 로봇과 사람이 공존하는 상황에서 기존 로봇 지능이 어떤 한계점을 지녔으며, 이 과제에서 어떤 기술을 연구개발하여 그 한계점을 넘어서려는지 아래에 요약 정리하였습니다.

## 기존 로봇 지능의 한계

### 환경 적응 부재로 신뢰성 하락

기존 로봇 지능은 사전 구축한 지능 모델을 그대로 단순 활용함으로써 로봇을 설치한 환경 조건에 따라 큰 성능 편차가 발생하여 제품과 서비스에 대한 신뢰도와 활용성이 떨어집니다.

### 동일 반복 대응으로 관심 유지 실패

기존 로봇 지능은 서비스 제공 경험을 축적하여 사람과 환경 변화에 지속적으로 특화하는 기능을 포함하고 있지 않아 주어진 고객과 상황에 대응하여 변화 없이 동일한 서비스로 반복 대응하므로 로봇에 대한 관심도가 빠르게 떨어집니다.

### 적응 학습용 데이터 부족으로 훈련 효과 저하

기존 로봇 지능을 구성하는 딥러닝 모델들은 훈련을 위해 대규모 데이터가 필요하나 운용 환경에서 로봇이 스스로 단기간에 많은 데이터를 수집할 수 없으므로 환경 적응 시간이 오래 걸릴 뿐 아니라 수집한 데이터는 정답이 없으므로 훈련에 활용하더라도 적용 효과가 낮습니다.

### 한정된 경험으로 다양한 맥락 대응 미숙

기존 로봇은 적응 학습을 하더라도 운용 환경에 한정된 데이터와 경험만 수집하여 훈련할 수 있으므로 데이터 편향성, 데이터 불균형, 데이터 부재로 인한 맥락 이해 능력 저하와 서비스 대응 미숙의 문제가 여전히 존재합니다.

결과적으로 기존 로봇 지능을 활용한 서비스 로봇은 실환경 배치 운용 비용이 높고, 배치된 이후 고객을 장기간에 걸쳐 지속적으로 유인할 수 있는 맥락이해와 변화하는 교류 체험을 제공하지 못하므로 로봇이 제공하는 서비스의 효용성이 급감하여 로봇산업 활성화에 걸림돌이 되고 있습니다.

## 본 과제의 접근 방법

본 연구에서는 아래의 4개 핵심 기술로 구성되는 클라우드 로봇 핵심 인공지능 기술을 개발하여 기존 로봇 지능의 한계를 극복하고자 합니다.

1. 개인과 군집의 다중 특징, 행동 패턴 등 개인화 맥락과 물체의 역할, 상태, 물체 간 관계 등 서비스 맥락을 이해하고, 멀티모달 데이터 융합과 다수의 인식 결과 간의 일관성 추론을 통해 맥락 이해의 신뢰성을 향상하는 멀티모달 로봇 서비스 맥락이해 기술,
2. 맥락 이해 결과를 기반으로 로봇 서비스를 제공하고 그에 대한 사용자의 반응을 해석하고 그 원인을 유추함으로써 개인화 로봇 서비스 정책을 최적화하는 로봇 서비스 개인화/특화 기술, 
3. 로봇 서비스 운용 지역의 환경과 사용자 특성 변화에 대응하기 위해 지역 훈련 데이터를 스스로 수집하고 학습하여 성능을 최적화하는 지속적 지역 적응 학습 기술, 
4. 클라우드 로봇 복합인공지능 시스템으로부터 전역 최적 지능을 전달받아 지역 최적화 학습에 전이(Transfer)함으로써 로봇의 맥락이해와 서비스 개인화/ 특화 능력을 향상하는 전역 최적 지능 적용 학습 기술

또한, 상기 클라우드 로봇 핵심 인공지능 기술을 복수의 서비스 도메인을 대상으로 테스트베드와 실환경에서 기술의 적용성을 검증하고자 합니다.

본 과제의 접근 방법을 종합해 보면 아래 그림과 같습니다.

![클라우드 로봇 지능 개념](/assets/img/2022-0-00842-concept.png)
