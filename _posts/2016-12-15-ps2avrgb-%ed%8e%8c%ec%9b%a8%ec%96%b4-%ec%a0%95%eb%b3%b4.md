---
layout: post
title: ps2avrGB 펌웨어 정보
published: true
author: showjean
comments: true
date: 2014-06-23 06:06:44
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: /477
---
ps2avrGB는 ps2avrU 펌웨어에 RGB LED를 컨트롤할 수 있는 sub MCU를 추가한 펌웨어 입니다.&nbsp;

대부분의 기능은 ps2avrU와 동일하며 추가적으로 더 손쉽게 키 맵핑 및 커스텀 매크로를 등록할 수 있는 bootMapper Client를 이용한 관리가 가능합니다.



ps2avrU 펌웨어 정보 :&nbsp;http://blog.winkeyless.kr/19



ps2avrU의 기능 중 &#8216;하드웨어 키 맵핑&#8217;을 제외한 모든 기능이 동일 합니다.

단, &#8220;하드웨어 메뉴&#8221;의 옵션은 부트맵퍼 클라이언트에서 설정 합니다.





*** RGB LED 지원**



컬러를 자유롭게 변경할 수 있는 RGB LED를 지원합니다.

이에 관한 모든 설정은 &#8220;bootMapper Client&#8221;에서 할 수 있고, 밝기와 모드는&nbsp;키보드에서도 직접 변경이 가능합니다.



&#8211; 모드 변경 : ESC + SHIFT + Caps lock 또는 (LED MODE2)

: PS/2 연결시 RGB LED가 off 일 경우에만 스위치쪽 full LED가 점등 됩니다.



&#8211; RGB key event mode 변경

: ESC + Ctrl + Capslock으로 RGB key event mode 변경

: 또는 Ctrl + LED_MODE2





&#8211; 밝기 변경 : SHIFT+KEY\_LED\_UP, SHIFT+KEY\_LED\_DOWN

: RGB LED의 밝기가 밝아질 수록&nbsp;full LED는 어두워집니다.

: full LED를 최대 밝기로 이용하고자 할 경우 RGB LED의 밝기는 중간 이하로 설정해야 합니다.



컬러 및 기타 세부 설정은 &#8220;bootMapper Client&#8221;를 통해서 할 수 있습니다.



bootMapper Client 사용 법 : http://blog.winkeyless.kr/154








***&nbsp;스위치 full LED**



스위치 full LED의 조절&nbsp;키들은 기본적으로 다음의 위치에 매핑되어 있습니다.

&#8211; LED MODE : FN+Caps lock

=> LED 모드를 순차적으로 변경합니다.



&#8211; B.87, B.mini 등 F1~12키가 있는 기판&nbsp;

:&nbsp;LED BR UP&nbsp;-> FN + =

: LED BR DOWN&nbsp;-> FN + &#8211;

&#8211; B.face B.thumb 등 F1~12키가 없는 기판&nbsp;

: LED BR UP -> FN + H

: LED BR DOWN -> FN + G

=> 밝기를 조절합니다.&nbsp;



스위치 LED는 RGB LED의 밝기에 따라서 최대 밝기가 제한 됩니다.





*** 펌웨어 다운로드 링크**



http://blog.winkeyless.kr/153