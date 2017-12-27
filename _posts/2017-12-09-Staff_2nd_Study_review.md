---
layout: post
title: 두번째 Staff 스터디 후기
author: sigmadream
tags: django
---

# Django Staff 두번째 스터디 후기

Django(라 쓰고 `Python`..이라 읽어봅시다!) 부산 사용자 커뮤니티 2차 모임을 토요일(12월 09일)에 경성대에서 두번째 스터디를 진행하였습니다.

## 요약하자면

### Django 2.0의 튜토리얼 진행
Django의 버전이 2.0으로 업그레이드 되어서, 튜토리얼을 처음부터 새롭게 시작해보았습니다. 당연히 1.11과 별다른 차이가 없지만 몇가지 소소한 부분(URL?)에서 차이점을 보여서, 새로운 버전에 맞춰서 진행하였습니다.

* [`raccoony`](http://raccoonyy.github.io/)님께서 Django 2.0의 변경사항을 한글로 정리해주셨습니다. 관심 있으시면 [이 곳](http://raccoonyy.github.io/django-2-0-release-note-summary/index.html)을 참고해주세요!

* 윈도우(>= 10)를 기준으로 Python(>= 3 and x64)을 설치하고, VSCode(thx! Microsoft~!), django(>= 2.0.0)을 설치하고 django의 공식 홈페이지에 나와있는 튜토리얼을 다 같이 차근 차근 진행하였습니다.

* 스터디한 내용을 요약한 슬라이드는 [이곳](https://docs.google.com/presentation/d/1Jxi1qCRA3wXsKkKYbqSdYhJ4cdro11o4O-speKOVOY0/edit)을 참고하세요!

* 두번째 스터디 내용은 [이곳](https://youtu.be/Hh7h2dbnPcU)을 참고하세요!

### 장고 프로그래밍의 시작

두번째 스터디의 핵심 주제는 "Model - View - Template"를 기반으로 한 '프로그래밍 절차' 입니다. 간단한 ToDo 앱을 만들기 위해서 우리는 아래와 같은 순서로 일을 진행했습니다.

1. Python / Python 가상환경 / Django 설치
2. VSCode 설치 및 Python 플러그인 설치
3. Django 프로젝트 생성
4. Django 앱 생성
5. 해당 앱의 Model 생성 및 마이그레이션
6. 해당 앱의 View 작성
7. 해당 앱의 Template 작성
8. 필요한 만큼 '5~6'을 반복

`Model`을 작성하고, 쉘(shell)을 사용해서 데이터를 저장하고 불러오는 몇가지 연습을 병행해서 진행했습니다. 우리는 SQL을 배우거나, 그러한 내용을 잘 알고 있는 대상자를 가정하지 않기 때문에 ORM을 충분히 활용할 수 있도록 차후 연습할 예정입니다. 두번째 스터디에는 '아, 모델은 데이터를 저장하거나 불러올 수 있구나!' 그리고 난 '모델에 데이터를 저장(save) 하거나 불러(all) 올 수 있으면 됩니다.

`View`의 경우 개발의 편의성을 위해서 [`CBV`](https://docs.djangoproject.com/en/2.0/topics/class-based-views/)를 사용했습니다. 

`Template`의 Django의 기본 템플릿 엔진을 사용했으며, 편의성을 위해서 [`bootstrap`](https://getbootstrap.com/)을 사용했습니다. 

## 숙제

Django 스터디의 경우 CSS를 별도로 스터디할 여력이 없으니 bootstrap [한국어 사이트](http://bootstrap4.kr/)를 활용해서 [`그리드 시스템`](http://bootstrap4.kr/docs/4.0/layout/grid/), [`테이블`](http://bootstrap4.kr/docs/4.0/content/tables/), [`폼`](http://bootstrap4.kr/docs/4.0/components/forms/)을 [`jsfiddle`](https://jsfiddle.net/)이나 [`CodePen`](https://codepen.io/)에서 연습해 보시고 오시면 됩니다.

