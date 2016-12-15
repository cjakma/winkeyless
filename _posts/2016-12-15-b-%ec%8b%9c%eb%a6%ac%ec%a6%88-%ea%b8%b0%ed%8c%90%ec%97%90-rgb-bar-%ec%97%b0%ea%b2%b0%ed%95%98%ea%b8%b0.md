---
layout: post
title: B 시리즈 기판에 RGB bar 연결하기
published: true
author: showjean
comments: true
date: 2014-07-23 09:07:02
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: '/b-%ec%8b%9c%eb%a6%ac%ec%a6%88-%ea%b8%b0%ed%8c%90%ec%97%90-rgb-bar-%ec%97%b0%ea%b2%b0%ed%95%98%ea%b8%b0'
image:
    feature: cfile2.uf.231AFC3B5447196F338F44.jpg
---
*** B 시리즈 X2 기판은 모든&nbsp;RGB LED를 PCB에 직접 납땜하므로 아래와 같은 작업이 필요없습니다.**





우선 RGB 바의 생김새는 아래와 같습니다.



주의 할 점이라면 방향성이 있다는 것 인데요, 사진과 같이 화살표(삼각형)으로 방향을 나타내고 있습니다.

(PCB의 컬러는 검정색과 흰색이 있습니다.)



그리고, 기판에 RGB LED 컨트롤러와 모든 RGB LED가 납땜 되어 있어야 RGB bar도 작동 합니다.




  





  






때에 따라서 뒷면에 동박이 노출 된 부분이 있는데 이런 곳은 쇼트를 방지 하기위해서 절연 테이프 등으로 적당히 처리해주셔야 합니다.


  






와이어링 방법은 간단합니다. 단&nbsp;3 줄만 연결해주면 되는데요,



기판의 VCC를 +5V와 연결, GND를 GND와 연결, DO를 Din에 연결 해주면 됩니다.



**여기서 반드시 주의 할 부분은 기판의 DO를 RGB bar의 Din과 연결해줘야 한다는 것 입니다.**



아래의 기판 별로 설명해 놓은 사진을 참고하세요.





&#8211; B.mini


  






&#8211; B.87


  






&#8211; B.pad, B.87 EX, B.mini EX, B.face, B.thumb


  






&#8211; B.87 EX V0.2 : 와이어링 할 수 있는 별도의 홀이 마련되어 있지 않으므로 다음과 같은 위치에 와이어링 해주면 됩니다.


  






 

와이어링을 할 때 사진과 같이 와이어가 기판 바깥 쪽으로 나가지 않게 해야 하우징과 간섭이 생기지 않습니다.




  






B.87에 와이어링을 마친 모습입니다.

**LED의 수를 bootmapper client에서 재설정 해주면 LED에 불이 켜지게 됩니다.**

bootmapper client :&nbsp;http://blog.winkeyless.kr/154




  






&#8211; 참고 사진




  









  












  









  









  









  









  









