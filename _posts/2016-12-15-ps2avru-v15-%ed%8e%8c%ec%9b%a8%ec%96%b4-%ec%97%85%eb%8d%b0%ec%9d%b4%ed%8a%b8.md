---
layout: post
title: ps2avrU V1.5 펌웨어 업데이트
published: true
author: showjean
comments: true
date: 2013-12-01 04:12:22
tags: [ ]
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ed%8e%8c%ec%9b%a8%ec%96%b4'
permalink: '/ps2avru-v15-%ed%8e%8c%ec%9b%a8%ec%96%b4-%ec%97%85%eb%8d%b0%ec%9d%b4%ed%8a%b8'
---
http://blog.winkeyless.kr/17



13.12.02.



&#8211; 펌웨어와 키맵 데이터를 분리했습니다. 때문에, 앞으로는 새로운 버젼의 펌웨어로 업데이트를 하더라도&nbsp;키 매핑을 다시 하지 않아도 됩니다.

더 자세한 내용은 아래 링크를 참고하세요.



부트로더를 이용한 펌웨어 업로드 방법 : http://blog.winkeyless.kr/18





&#8211; 파일 설명&nbsp;



: 펌웨어

keymain_NKRO : 기본 펌웨어

keymain\_NKRO\_SL_apart : 기본 펌웨어에&nbsp;S/L LED가 별도(PD6)로 처리된 펌웨어

keymain_GKP.hex : 고스트 키 방지가 적용되어 있는 펌웨어

keymain\_GKP\_SL\_apart.hex :&nbsp;keymain\_GKP.hex에 S/L LED가 별도(PD6)로 처리된 펌웨어



: 키맵

keymap\_part(a87\_V03)(a87U)(mxminiU)(a87UEX) :&nbsp;&nbsp;A.87 ps2avr V0.3, A.87U, A.87W,&nbsp;MX-miniU, MX-miniW, A.87U EX 공용 키맵

keymap_part(thumb)(face) :&nbsp;thumb, thumbU, faceU, faceW 공용 키맵