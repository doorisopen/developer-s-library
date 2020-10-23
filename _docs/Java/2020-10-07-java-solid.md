---
title: "SOLID"
category: Java
date: 2020-10-07 00:30:59
comments: true
order: 14
---


## S
__S(Single responsibility principle - 단일 책임 원칙)__ 한 클래스는 하나의 책임만 가져야한다

## O
__O(Open/closed principle - 개방/폐쇠 원칙)__ 소프트웨어 요소는 확장에는 열려있으나 변경에는 닫혀 있어야 한다.

## L
__L(Liskov substitution principle - 리스코프 치환 원칙)__ 프로그램의 객체는 프로그램의 정확성을 깨뜨리지 않으면서 하위 타입의 인스턴스로 바꿀 수 있어야 한다.

자식 클래스는 언제나 자신의 부모 클래스를 대체할 수 있다는 원칙이다. 즉 부모 클래스가 들어갈 자리에 자식 클래스를 넣어도 계획대로 잘 작동해야 한다.

자식클래스는 부모 클래스의 책임을 무시하거나 재정의하지 않고 확장만 수행하도록 해야 LSP를 만족한다.

## I
__I(Interface segregation principle - 인터페이스 분리 원칙)__ 특정 클라이언트를 위한 인터페이스 여러 개가 범용 인터페이스 하나보다 낫다.

SRP가 클래스의 단일 책임을 가져야 한다고 강조하면 ISP는 인터페이스의 단일책임을 강조한다는 의미입니다.

## D
__D(Dependency inversion principle - 의존관계 역전 원칙)__ 프로그래머는 추상화에 의존해야지 구체화에 의존하면 안된다

의존 관계를 맺을 때 변화하기 쉬운 것 또는 자주 변화하는 것보다는 변화하기 어려운 것, 거의 변화가 없는 것에 의존하라는 것이다. 한마디로 구체적인 클래스보다 인터페이스나 추상 클래스와 관계를 맺으라는 것입니다.


## Reference