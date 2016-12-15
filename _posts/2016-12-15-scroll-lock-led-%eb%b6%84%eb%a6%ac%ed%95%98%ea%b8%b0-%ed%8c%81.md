---
layout: post
title: Scroll Lock LED 분리하기 팁
published: true
author: showjean
comments: true
date: 2014-02-03 02:02:36
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: '/scroll-lock-led-%eb%b6%84%eb%a6%ac%ed%95%98%ea%b8%b0-%ed%8c%81'
image:
    feature: cfile9.uf.212DDA4F52EFA4B62977B4.jpg
---
ps2avrU 펌웨어에는 기본적으로 S/L LED가 별도로 표시되지 않고 on/off에 따라서 Caps Lock LED가 2번/1번 깜빡이는 것으로 표시됩니다.



이를 별도의 위치에 표시하도록 간단한 와이어링으로 개조할 수 있습니다.





1. 펌웨어 변경

&#8211; S/L LED가 별도로 표시되는 펌웨어인 &#8220;keymain\_NKRO\_SL_apart.hex&#8221;로 기판의 펌웨어를 변경합니다.

&#8211; ps2avrU firmware 및 utility : http://blog.winkeyless.kr/17

&#8211; 부트로더를 이용한 펌웨어/키맵/매크로 업로드 방법 : http://blog.winkeyless.kr/18





2.0 아래 사진과 같이 LED를 위한 저항을 스위치 쪽에 납땜 할 수 있는 기판이라면 별도의 와이어링이 필요치 않습니다. 표시된 위치에 저항만 납땜을 해주면 LED가 표시됩니다.


  






2. S/L LED의 신호가 출력되는 PD6 핀 확인(MCU에는 각 핀마다 고유의 이름이 있는데 여기서 우리가 찾아야 할 핀의 이름이 PD6 입니다.)

&#8211; 아래 그림의 동그라미 표시한 15번째 핀이 PD6 핀입니다.

&#8211; 각 기판마다 MCU의 방향은 다를 수 있으니 1번 핀을 기준으로 15번째 핀을 잘 확인해주세요.




  










3. 와이어링

&#8211; S/L LED를 표시할 위치(아래 그림에서는 S/L 키)에 다음과 같이 330옴 가량의 저항을 연결하여 PD6 핀과 와이어링 해줍니다.

&#8211; 와이어링 시 PD6 핀과 주위의 핀들이 쇼트가 나지 않도록 주의하세요.






  








4. 동작 확인

&#8211; 키보드를 PC와 연결하고 S/L키를 눌러 제대로 동작하는지 확인합니다.





질문은 댓글로 남겨주세요.