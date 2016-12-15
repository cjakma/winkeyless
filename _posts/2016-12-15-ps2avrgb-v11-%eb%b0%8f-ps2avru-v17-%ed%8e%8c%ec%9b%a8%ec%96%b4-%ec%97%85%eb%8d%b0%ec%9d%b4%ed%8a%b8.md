---
layout: post
title: ps2avrGB V1.1 및 ps2avrU V1.7 펌웨어 업데이트
published: true
author: showjean
comments: true
date: 2015-10-30 06:10:07
tags: [ ]
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ed%8e%8c%ec%9b%a8%ec%96%b4'
permalink: '/ps2avrgb-v11-%eb%b0%8f-ps2avru-v17-%ed%8e%8c%ec%9b%a8%ec%96%b4-%ec%97%85%eb%8d%b0%ec%9d%b4%ed%8a%b8'
---
ps2avrGB 펌웨어 링크 : http://blog.winkeyless.kr/153

ps2avrU펌웨어 링크 : http://blog.winkeyless.kr/17





2015.10.30.



* ps2avrGB, ps2avrU 공통

&#8211; FN 키의 작동 방식을 lazy FN으로 고정 (관련 옵션 제거)

&#8211;&nbsp;일부 듀얼액션 키가 작동하지 않던 버그 수정

&#8211;&nbsp;EU 배열의 키보드에서 bootmapper trigger가 작동하지 않는 상황이 없도록 패치



* ps2avrGB

&#8211; 하드웨어 메뉴를 제거하고 관련 옵션을 부트맵퍼 클라이언트에서 설정 할 수 있도록 수정

&#8211; Full LED mode 및 밝기를&nbsp;부트맵퍼 클라이언트에서 설정 할 수 있도록 수정

&#8211; RGB transition speed 설정 옵션 추가

(최신 버젼의 Bootmapper Client 필요)