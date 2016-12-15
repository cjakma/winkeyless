---
layout: post
title: MX-mini ps2avr 기판 조립 가이드
published: true
author: showjean
comments: true
date: 2013-06-21 06:06:21
tags:
    - mx mini
    - ps2avr
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: /34
image:
    feature: cfile3.uf.216D133F51C3F80B2277C5.jpg
---
* 플래시를 안써서 사진이 전체적으로 어둡고, 플럭스 세척제를 안써서 사진상의 기판이 지저분한 점은 양해바랍니다.&nbsp;



* 가이드 작성을 위해서 납땜한 사진을 올리지만, 기본적으로 모든 소자는 직접 납땜을 해야합니다.







기판 앞면의 모습입니다. USB 커넥터를 제외한 모든 소자가 뒷면에 배치되었습니다.


  












C4 (Chip Tantal A size 10uF 16V) : 극성에 주의하며 사진과 같이 땜해야합니다.

C3 (2012 size Chip Monolithic Ceramic Capacitor 0.1uF) : 극성과 관계없이 땜해줍니다.&nbsp;

R1 (2012 Chip Resistor, 10kΩ) : 마찬가지로 극성과 관계 없습니다.

N1 (MMBT2222A SOT-23) : 사진과 같은 모양으로 땜해주면 됩니다.

R2,3 (2012 Chip Resistor, 330Ω) : 극성과 관계없이 땜해줍니다.

IC1 (ATMEGA32A-AU) : 윗면의 모서리중 한 곳에 ○ 표시가 되어 있습니다. 아래 사진과 같이 기판의 표시부분과 위치를 맞춰 땜하면됩니다.


  












C1,2 (2012 size Chip Monolithic Ceramic Capacitor 18pF) : 극성에 관계 없습니다.

Y1 (CRYSTAL SMD 3X5 size 12MHz) : 크리스탈의 바닥을 보시면 4곳의 모서리중 1곳이 다른 모양의 동판입니다. 이 부분이 기판의 ㅁ(네모)표시한 부분으로 위치하도록 방향을 주의 해야합니다.


  










뒷면의 다이오드나 Full LED를 위한 칩저항(2012size)는 아래 사진과 같이 땜을 합니다. 칩저항은 극성이 상관없지만, 다이오드는 극성에 주의해야합니다. 칩저항의 LED 컬러별 저항값은 자료실의 내용을 참고하세요 &#8211; http://www.kbdmania.net/xe/6229604


  












USB 케이블을 이용할 경우 USB to PS2 젠더를 사용해 PS2인터페이스로 변환해줘야 합니다.


  
