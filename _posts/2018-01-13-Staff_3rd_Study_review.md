---
layout: post
title: 세번째 Staff 스터디 후기
author: sigmadream
tags: django
---

Django(라 쓰고 `Python`..이라 읽어봅시다!) 부산 사용자 커뮤니티 3차 모임을 토요일(01월 06일)에 경성대에서 세번째 스터디를 진행하였습니다.

<img src="{{ site.baseurl }}/images/20180106.jpg" style="width: 400px;"/>

## 요약하자면

### M.V.T 방법으로 작은 프로젝트 시작

Django(장고)를 꼭 하나의 방법으로 작성할 필요는 없지만, 우리는 모두 '초보'라서 하나의 방법으로 차근 차근 `CRUD`를 설명하고자 하였습니다. 그래서 `M.V.T`를 응용해서 프로그래밍 방법을 도입하였습니다.

### Model

먼저 `ToDo`에 필요한 `모델(Model)`을 작성합니다. 우리가 필요로 하는 프로그램에 필요한 `ToDo`의 필수요소를 추출하여 작성합니다. 당연히 `모델`을 구성하는 필수요소를 추출하는 것이 쉽지 않지만, 그래서 작고 가벼운 `ToDo`를 사용해서 모델 추출을 연습하였습니다.

### View

`View`의 역할을 명확하게 보여주기 위해서 [`CBV`](https://docs.djangoproject.com/en/2.0/topics/class-based-views/)를 사용하였습니다. `M.V.T`를 응요한 프로그래밍 방법을 도입하면서 가장 많이 고민했던 부분이었습니다. 그래서 당분간은 `CBV`를 사용해서 스터디를 진행하였습니다.

### Template

`Template`의 문법이 많이 부담스럽기 때문에 반복문 형태만 학습하였습니다.

## 총평

큰 틀에서 많이 배운것 같은데, 내용이 너무 빈약한 것 같아서 아쉬웠습니다. 그래서 2월에는 `blog`에 도전해보도록 하겠습니다.

* 스터디한 내용을 요약한 슬라이드는 [이곳](https://docs.google.com/presentation/d/1Jxi1qCRA3wXsKkKYbqSdYhJ4cdro11o4O-speKOVOY0/edit)을 참고하세요!

* CBV와 관련된 내용은 [이곳](https://ccbv.co.uk/)을 참고하세요.
