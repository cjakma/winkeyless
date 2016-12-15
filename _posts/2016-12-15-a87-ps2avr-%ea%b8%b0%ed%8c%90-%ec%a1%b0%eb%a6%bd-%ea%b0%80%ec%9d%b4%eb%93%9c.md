---
layout: post
title: A.87 ps2avr 기판 조립 가이드
published: true
author: showjean
comments: true
date: 2013-06-21 05:06:02
tags:
    - A.87
    - ps2avr
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: '/a87-ps2avr-%ea%b8%b0%ed%8c%90-%ec%a1%b0%eb%a6%bd-%ea%b0%80%ec%9d%b4%eb%93%9c'
image:
    feature: cfile1.uf.2106993451C3E73708152E.jpg
---
우선 납땜 후 전체적인 모습입니다. 스페이스 바 스위치 옆의 딥스위치는 사용하지 않습니다.


  










소자 실장 부위 확대 화면 입니다.


  








C1 (Chip Tantal A size 10uF 16V) : 극성에 주의하며 사진과 같이 땜해야합니다. (사진과 컬러가 다를 수 있습니다.)

C2 (2012 size Chip Monolithic Ceramic Capacitor 0.1uF) : 극성과 관계없이 땜해줍니다.&nbsp;

R1 (2012 Chip Resistor, 10kΩ) : 마찬가지로 극성과 관계 없습니다.


  










N1 (MMBT2222A SOT-23) : 사진과 같은 모양으로 땜해주면 됩니다.


  










R2,3 (2012 Chip Resistor, 330Ω) : 극성과 관계없이 땜해줍니다.


  










C3,4 (2012 size Chip Monolithic Ceramic Capacitor 18pF) : 극성에 관계 없습니다.

Y1 (CRYSTAL ATS-49/U타입 12MHz(또는 SMD 3X5 size)) : 기본 제공되는 딥타입 소자는 극성에 관계 없습니다. 필요에따라서 SMD 3X5 사이즈를 이용할 수 있도록 풋프린트를 준비해뒀습니다. 이 경우는 방향을 주의 해야합니다.


  












IC1 (ATMEGA32A-AU) : 윗면의 모서리중 한 곳에 ○ 표시가 되어 있습니다. 아래 사진과 같이 기판의 표시부분과 위치를 맞춰 땜하면됩니다.


  










USB 커넥터는 반드시 앞면에 부착하여 뒷면에 납땜을 해야 합니다. 사진을 참고하세요.


  










뒷면의 다이오드나 Full LED를 위한 칩저항(2012size)는 아래 사진과 같이 땜을 합니다. 칩저항은 극성이 상관없지만, 다이오드는 극성에 주의해야합니다. 칩저항의 LED 컬러별 저항값은 자료실의 내용을 참고하세요&nbsp;

&#8211;&nbsp;http://blog.winkeyless.kr/4


  












PS2 인터페이스이지만 기본적으로 USB커넥터를 사용하여 케이블 분리를 가능케합니다. 선택에 따라서 PS2 케이블을 직접연결할 수 있는 패드를 추가했습니다.


  










USB 케이블을 이용할 경우 USB to PS2 젠더를 사용해 PS2인터페이스로 변환해줘야 합니다.


  








2종류의 ISP 다운로더 커넥터를 사용할 수 있도록 마련해뒀습니다.


  












한 가지 주의해야할 부분으로 윈키리스로 사용할 경우 R Alt키의 다이오드는 스위치가 실장되는 곳이 아닌 윈키의 R Alt 부분에 납땜을 해야합니다.


  










&#8211; A.87 ps2avr에 대한 설명



Context라고 표시되어 있는 키는 FN키로 사용됩니다.


  










* Full LED 컨트롤 방법



ESC + Scroll Lock키(또는 FN + Scroll Lock)를 누르면 4가지 모드가 번갈아가며 바뀌게 됩니다.

1. LED off

2. fading

3. on

4. key down level



LED 모드는 전원이 차단되어도 키보드에 값이 저장되어 있어 다시 전원을 연결하면 그 상태가 유지됩니다.&nbsp;

(모드 변경 뒤 20초 가량 후에 저장이 됩니다. 이 때문에 모드 변경 후 바로 전원을 차단하면 값이 저장되지 않을 수 있습니다.)








