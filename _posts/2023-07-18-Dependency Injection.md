---
layout: post
title: Dependency Injection
categories: programming
published: true
---

### Dependency 란?

- 코드에서 두 모듈 간의 연결
- 일반적으로 A모듈이 B모듈을 어떤 용도를 위해 사용
- 객체지향언어는 두 클래스 간의 관계라고도 말함

### Dependency 가 위험한 이유?

- 하나의 모듈이 바뀌면 의존한 다른 모듈까지 변경이 이루어지기 때문
- 테스트 가능한 어플을 만들 때 의존성이 있으면 유닛테스트 작성이 어렵고, 유닛테스트 목적 자체가 다른 모듈로부터 독립적으로 테스트하는 것을 요구하기 때문

### Dependency Injection 이 필요한 이유?

- 위 Dependency의 위험성을 해결하기 위해 사용
