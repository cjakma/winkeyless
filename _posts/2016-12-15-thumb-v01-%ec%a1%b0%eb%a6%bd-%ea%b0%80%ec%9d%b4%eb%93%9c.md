---
layout: post
title: thumb V0.1 조립 가이드
published: true
author: showjean
comments: true
date: 2013-07-03 02:07:19
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: '/thumb-v01-%ec%a1%b0%eb%a6%bd-%ea%b0%80%ec%9d%b4%eb%93%9c'
image:
    feature: cfile1.uf.270E193651D437F82C53E1.jpg
---
&#8211; R1 : 10K 옴 저항을 사진과 같이 땜해줍니다. 방향성은 없습니다.


  








&#8211; IC1 : ATMEGA32A-AU 를 반드시 방향에 맞게 땜해줍니다. 사진상 빨간 동그라미와 실제 MCU의 동그라미 부분을 맞춰 방향을 잡아줍니다.

&#8211; &nbsp;R2, R3 : 330옴 저항을 땜해줍니다. 방향성 없습니다.


  








&#8211; C1, C3, C4 &nbsp;: 0.1uF 캐패시터 1개, 18pF 캐패시터 2개를 땜해줍니다. 구분할 수 없듯이 방향성도 없습니다.

&#8211; C2 : 10uF / 16V 탄탈 캐패시터를 땜해줍니다. 반드시&nbsp;사진과 같이 방향에 맞게 땜해줘야 합니다.

&#8211; M1 : MMBT2222A 트랜지스터를 반드시 사진과 같이 방향에 맞게 땜해줍니다.

&#8211; Y1 : 12Mhz 크리스탈을 사진과 같이 땜해줍니다. 표시는 되어있지만 소자를 뒤집지만 않으면 방향은 신경쓰지 않아도 됩니다.


  








&#8211; USB1 : molex 47589-0001 마이크로 USB 커넥터 입니다. 다리가 얇고 조밀해 얇은 인두팁을 이용해 땜하실것을 권합니다. 사진과 같이 체결 후에는 노출되는 동박면이 적은 편이므로 기판의 동박면에 미리 납을 적당히 입혀주고 땜을 하는 것이 좋습니다.


  








&#8211; thumb 기판과 함께 배송되는 작은 기판입니다. 기존 HHKB-MX 과 기판 사이즈/ 커넥터 위치가 다르기 때문에 기존 하우징에 이 thumb 기판을 이용하려거든 이 작은 기판을 아래 사진과 같은 위치에 연결해 VCC/DATA/CLK/GND를 기판과 와이어링 해주면 HHKB-MX와 같은 위치에 커넥터를 장착할 수 있습니다.


  








&#8211; 확장 모듈과 함께 배송받은 기판은 MCU에 부트로더만 설치되어 있기 때문에, 땜 조립 후 기판에 맞는 펌웨어를&nbsp;업로드&nbsp;해야 합니다.


  + PS/2 전용 펌웨어 :&nbsp;http://blog.winkeyless.kr/entry/thumb-V01-%EA%B4%80%EB%A0%A8-%EC%9E%90%EB%A3%8C



  + USB / PS/2 콤보 펌웨어 :&nbsp;http://blog.winkeyless.kr/entry/ps2avrU-firmware-%EB%B0%8F-utility



  + 부트로더를 이용한 펌웨어&nbsp;업로드&nbsp;방법 :&nbsp;http://blog.winkeyless.kr/18






