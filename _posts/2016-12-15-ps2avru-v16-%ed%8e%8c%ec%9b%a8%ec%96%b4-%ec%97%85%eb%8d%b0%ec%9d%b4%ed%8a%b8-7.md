---
layout: post
title: ps2avrU V1.6 펌웨어 업데이트
published: true
author: showjean
comments: true
date: 2014-04-08 06:04:34
tags: [ ]
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ed%8e%8c%ec%9b%a8%ec%96%b4'
permalink: '/ps2avru-v16-%ed%8e%8c%ec%9b%a8%ec%96%b4-%ec%97%85%eb%8d%b0%ec%9d%b4%ed%8a%b8-7'
---
펌웨어 링크 : http://blog.winkeyless.kr/17





2014.4.9.



&#8211; 키 매퍼 메뉴에서 메뉴에 없는 숫자를 누를 경우 오작동하는 버그를 패치

&#8211; 퀵 매크로(Quick Macro) 추가 : 키 매퍼 메뉴를 거치지 않고 원하는 하드웨어&nbsp;매크로(KEY_MAC1~12)에 빠르게 매크로를 설정할 수 있는 기능

: QM(Quick Macro) + 원하는 매크로 키(KEY_MAC1~12) 를 누르고 모든 키에서 손을 떼면 caps lock LED가 길게 2번 반짝이며 저장을 시작합니다.

: 이 상태에서 원하는 키 조합을 입력하고 다시 QM 키를 누르면 caps lock LED가 길게 1번 반짝이며 매크로 저장이 종료 됩니다.

: 해당 매크로키(KEY_MAC1~12)를 누르면 저장 된 키 조합이 출력됩니다.

: 퀵 매크로는 키 매퍼에서 저장하는 하드웨어&nbsp;매크로에만 해당되며 커스텀 매크로에는 적용 되지 않습니다.