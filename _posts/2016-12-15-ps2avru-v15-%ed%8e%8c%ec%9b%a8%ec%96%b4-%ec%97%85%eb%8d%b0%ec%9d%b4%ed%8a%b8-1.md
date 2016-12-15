---
layout: post
title: ps2avrU V1.5 펌웨어 업데이트
published: true
author: showjean
comments: true
date: 2013-12-02 03:12:38
tags: [ ]
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ed%8e%8c%ec%9b%a8%ec%96%b4'
permalink: /326
---
펌웨어 링크 : http://blog.winkeyless.kr/17



13.12.02_2



&#8211; LED 모드 0인 상태에서 플러깅시 LED가 깜박이는 현상 패치



&#8211; 펌웨어와 키맵 데이터를 분리했습니다. 때문에, 앞으로는 새로운 버젼의 펌웨어로 업데이트를 하더라도 키 매핑을 다시 하지 않아도 됩니다.

더 자세한 내용은 아래 링크를 참고하세요.





부트로더를 이용한 펌웨어 업로드 방법 : http://blog.winkeyless.kr/18





&#8211; 파일 설명&nbsp;



: 펌웨어

keymain_NKRO : 기본 펌웨어

keymain\_NKRO\_SL_apart : 기본 펌웨어에 S/L LED가 별도(PD6)로 처리된 펌웨어

keymain_GKP.hex : 고스트 키 방지가 적용되어 있는 펌웨어

keymain\_GKP\_SL\_apart.hex : keymain\_GKP.hex에 S/L LED가 별도(PD6)로 처리된 펌웨어



: 키맵

keymap\_part(a87\_V03)(a87U)(mxminiU)(a87UEX) : &nbsp;A.87 ps2avr V0.3, A.87U, A.87W, MX-miniU, MX-miniW, A.87U EX 공용 키맵

keymap_part(thumb)(face) : thumb, thumbU, faceU, faceW 공용 키맵