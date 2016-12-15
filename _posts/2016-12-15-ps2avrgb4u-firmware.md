---
layout: post
title: ps2avrGB4U firmware
published: true
author: showjean
comments: true
date: 2016-05-05 04:05:11
tags: [ ]
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ed%8e%8c%ec%9b%a8%ec%96%b4'
permalink: /808
---
# ** 이 펌웨어를 B 시리즈 기판(B.87, B.mini B.face 등)에 사용하지 마세요.



ps2avrGB4U &#8211; ps2avrGB 펌웨어를 ps2avrU 기판에 맞게 마이그레이션한 펌웨어



&#8211; 키맵핑, 매크로, 듀얼액션 ps2avrU와 동일한 방법 업로드 (.hex 파일을 부트로더로 업로드 하는 방식)

&#8211; ps2avrGB와 같이 하드웨어 메뉴를 제거하고 Bootmapper Client에서 옵션을 설정 가능






* 파일 설명



&#8211; HIDBootFlash.exe : 부트로더를 통해 바이너리(.hex 파일)을 업로드하는 어플리케이션

&#8211; bootloadHID.exe : command prompt 방식으로 .hex 파일을 업로드하는 어플리케이션



&#8211; 펌웨어 파일

ps2avrGB4U_NKRO : 기본 펌웨어 (뭐가 뭔지 잘 모르겠다면 이 파일을 이용하면 됩니다.)

ps2avrGB4U\_GPK : ps2avrGB4U\_NKRO에&nbsp;고스트 키 방지가 적용 된 펌웨어

ps2avrGB4U\_split\_NKRO.hex : IO Expander를 이용하여 분리형 키보드(Vergo 등) 를 구현할 수 있는 펌웨어

ps2avrGB4U\_split\_GKP.hex : ps2avrGB4U\_split\_NKRO에 고스트 키 방지가 적용 된 펌웨어



: 키맵 데이터

keymap\_part(a87\_V03)(a87U)(mxminiU)(a87UEX).hex : &nbsp;A.87 ps2avr V0.3, A.87U, A.87W, MX-miniU, MX-miniW, A.87U EX 공용 키맵

keymap_part(thumb)(face)(XTen).hex : thumb, thumbU, faceU, faceW, XTen 공용 키맵

&#8211; 키맵 데이터는 부트맵퍼 클라이언트 또는 부트 매퍼를 이용해 손쉽게 수정 할 수 있습니다.

&#8211; 부트 매퍼 사용법 : http://blog.winkeyless.kr/90





* 부트로더를 이용한 펌웨어 업로드 방법 : http://blog.winkeyless.kr/18



* ps2avrU 기본 기능 : http://blog.winkeyless.kr/19

* ps2avrGB 기본 기능 :&nbsp;http://blog.winkeyless.kr/156

* source : https://github.com/showjean/ps2avrU





  &#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8211;






  
    ** 이 후 버전은 아래 링크를 통해서 받을 수 있습니다.
  
  
  
    https://github.com/showjean/ps2avrU/releases
  















  
    cfile25.uf.21599246573DDB1D15C3C0.zip
  
  
  
  
  
  
    * ps2avrGB & ps2avrGB4U 공통
  
  
  
    &#8211; 3락의 기능 추가 : FN2, FN3 lock LED 추가
  
  
  
    &#8211; Toggle BootMapper 상태를 BootMapper Client와 동기화
  
  
  
    &#8211; L Ctrl 키의 첫 입력이 스킵되는 현상 수정
  












  
    cfile8.uf.2277E93F573460061E2E1B.zip
  
  
  
  
  
  
    &#8211; 키입력 버그 수정
  







ps2avrGB4U\_firmware\_V1.2.1_160506.zip : 버그로 파일 삭제&nbsp;



* ps2avrGB4U 펌웨어 추가

&#8211; ps2avrGB를 ps2avrU 펌웨어와 호환되도록 마이그레이션한 버젼으로 다음과 같은 변경사항이 있습니다.

&#8211; 키맵핑, 매크로, 듀얼액션 ps2avrU와 동일한 방법 업로드 (.hex 파일을 업로드 하는 방식)

&#8211; ps2avrGB와 같이 하드웨어 메뉴를 제거하고 Bootmapper Client에서 옵션을 설정 가능



* ps2avrGB4U 추가로 ps2avrU는 더이상 업데이트 되지 않습니다.