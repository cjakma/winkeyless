---
layout: post
title: MX mini ps2avr 관련 자료
published: true
author: showjean
comments: true
date: 2013-06-21 06:06:40
tags:
    - DWG
    - firrmware
    - mx mini
    - ps2avr
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ea%b8%b0%ed%8c%90'
permalink: /30
image:
    feature: cfile3.uf.24595B3751C3F66D0C4D93.jpg
---
* 파일 설명




  cfile9.uf.21698C3751C3F66C023350.dwg&nbsp;: 보강판, 윈키/윈키리스 2종





  cfile3.uf.244A0A3751C3F66C18BE97.dwg&nbsp;: 기판의 외곽선과 스위치/스테빌 홀/ISP 홀 표시





  cfile27.uf.235C593751C3F66D0A41CE.zip&nbsp;: 펌웨어 V0.2 (A.87과 기능은 동일하며, 아래 기본 Key matrix의 설명과 같이 키배열만 약간 다릅니다.)





  cfile3.uf.0268483751C3F671033949.zip&nbsp;: 펌웨어 소스 (원소스 : http://ps2avr.sourceforge.net/ )
 





* 소자 목록

9종 11개

ATMEGA32A-AU

USB-120

Chip Tantal A size 10uF 16V

MMBT2222A (SOT-23)

CRYSTAL SMD 3X5 size 12MHz

2012 Chip Resistor, 330Ω(331) * 2

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





* 펌웨어를 새로운 MCU에&nbsp;업로드&nbsp;할 경우 퓨즈비트 설정 값

avrdude -c stk500v2 -P com3 -p atmega32 -U hfuse:w:0xDF:m -U lfuse:w:0x0E:m

avrdude -c stk500v2 -P com3 -p atmega32 -U flash:w:ps2avr\_MX\_mini_V02.hex:i

pause;



&#8211; 빨간색의 글자는 자신의 환경에 맞게 수정하여 실행합니다.





* 기본 Key matrix (V0.2까지)

&#8211; A.87 과 비교 했을 때 Home키와 Delete키의 위치가 뒤바뀌었습니다. 설계는 동일한 펌웨어를 사용할 수 있도록 했는데 이 부분에서 제 실수로 V0.1과 V0.2 기판은 다른 펌웨어를 사용했습니다. 만약, V0.3 기판을 제작하게되면 이 부분은 수정할 생각입니다.&nbsp;


  








* 기본 사양

&#8211; ps2avr 컨트롤러 사용(ps2 인터페이스, 무한동시 입력 등) &#8211; 공개된 소스이므로 키매트릭스를 수정하여 컴파일하면 키배열 변경가능

&#8211; 윈키/윈키리스 콤보

&#8211; 캡스락 3000계열과 8000계열 호환

&#8211; 우 쉬프트 1.75 및 2.75 호환

&#8211; 모든 소자 뒷면에 배치

&#8211; 기존 3곳의 USB커넥터 위치에서 좌우는 제거하고 중앙만 남김

&#8211; 윈키의 하단열이 기존과 다름. 아래 이미지의 &#8220;2. 새로운 배열&#8221;로 변경 ( 체리 3000 시리즈의 윈키용 하단열 이용 )


  






&#8211; 편집키 부분의 키 매핑


  


&nbsp;





* Full LED 컨트롤 방법



ESC + Scroll Lock키(또는 FN + Scroll Lock)를 누르면 4가지 모드가 번갈아가며 바뀌게 됩니다.

1. LED off &#8211; &nbsp;꺼짐

2. fading &#8211; 숨쉬기

3. on &#8211; 계속 켜짐

4. key down level &#8211; 키 입력이 많을수록 밝아짐



LED 모드는 전원이 차단되어도 키보드에 값이 저장되어 있어 다시 전원을 연결하면 그 상태가 유지됩니다.&nbsp;

(모드 변경 뒤 약 20초 후에 저장이 됩니다. 이 때문에 모드 변경 후 바로 전원을 차단하면 값이 저장되지 않을 수 있습니다.)