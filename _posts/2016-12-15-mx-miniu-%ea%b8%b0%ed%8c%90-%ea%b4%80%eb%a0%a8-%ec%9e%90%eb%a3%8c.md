---
layout: post
title: MX-miniU 기판 관련 자료
published: true
author: showjean
comments: true
date: 2013-10-11 04:10:08
tags: [ ]
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ea%b8%b0%ed%8c%90'
permalink: /197
image:
    feature: cfile24.uf.2218F245532F30A421D602.jpg
---
* 파일 설명




  
    cfile5.uf.2420174952582B051680AA.dwg&nbsp;: 기판 외곽선 및 홀 위치를 표시
  




&#8211; 보강판은 MX-mini ps2avr의 그것과 동일합니다. :&nbsp;http://blog.winkeyless.kr/6





* 레이아웃




  










* 소자 목록

12종 19개

ATMEGA32A-AU

USB-120

Chip Tantal A size 10uF 16V

MMBT2222A (SOT-23) * 3

ZENER DIODE, 350mW, 3.6V, SOT-23 (BZX84C3V6) * 2

CRYSTAL&nbsp;12MHz (SMD 3X5 size)

2012 Chip Resistor, 330Ω(331) * 2

2012 Chip Resistor, 1.5kΩ(152) * 2

2012 Chip Resistor, 68Ω(680) * 2

2012 Chip Resistor, 10kΩ(103)

2012 size Chip Monolithic Ceramic Capacitor 18pF * 2

2012 size Chip Monolithic Ceramic Capacitor 0.1uF





* LED 컬러별 저항 값 &#8211; PS/2 200mA 기준 (출처 : 코렐라스님 자료)

하얀색/보라색(최소전압 약 3V) : 820

빨간색/노란색(최소전압 약 1.8V) : 1.3K

파란색/초록색(최소전압 약 2.8V) : 900



&#8211; 저항 사이즈 : 2012



&#8211; 위 값은 보통의 사용하는 LED를 기준으로 작성되었습니다.

LED의 정확한 저항 값은 해당 데이터시트를 참고하여 계산해야 합니다.





* 스위치 입력에 필요한 다이오드는 1N4148(DIP or SMD) 입니다.





* ps2avrU bootloader 사용

&#8211; 기본적으로 부트로더만 설치되어 있으므로, 이를 이용해 펌웨어를&nbsp;업로드해야 합니다.



&#8211; 부트로더가 설치되었는지 확인하는 방법 : http://blog.winkeyless.kr/14



&#8211; 만약 MCU를 교체하여 부트로더가 설치되어 있지 않다면 설치해야 합니다.&nbsp;

&#8211; 부트로더 설치 방법 :&nbsp;http://blog.winkeyless.kr/15



&#8211; 부트로더를 이용한 펌웨어&nbsp;업로드&nbsp;방법 :&nbsp;http://blog.winkeyless.kr/18







* 기본 Key matrix

&#8211; A.87U와 같습니다.

&#8211; APP키는 FN키로 대체되었습니다.

https://docs.google.com/spreadsheet/ccc?key=0Ah1Lcjc-gPfndHMycE1uTnJWVHQyS01SMElkdksyRWc&usp=sharing







*하드웨어 사양

&#8211; 레이아웃 : 윈키/윈키리스 콤보,&nbsp;

캡스락 3000/8000(마제식) 지원

&#8211; Full LED 지원 : 5가지 LED 모드

&#8211; PCB : 1.2T (빨강)

&#8211; 모든 소자 뒷면에 배치

&#8211; 기존 MX-mini기판과 크기 및 외곽선 100% 호환

&#8211; 하우징리스를 위한 볼트홀 추가(첨부파일 참고)



*ps2avrU(펌웨어) 사양&nbsp;

&#8211; 인터페이스 : USB / PS/2 콤보 (자동 인식)

&#8211; 하드웨어 키매핑 지원 : 별도의 SW없이 즉시 키매핑 변경 가능

&#8211; Full LED 지원 : 5가지 LED 모드

&#8211; 하드웨어 매크로 지원





펌웨어에대한 더 많은 정보는 아래 링크를 참고하세요.

http://blog.winkeyless.kr/19