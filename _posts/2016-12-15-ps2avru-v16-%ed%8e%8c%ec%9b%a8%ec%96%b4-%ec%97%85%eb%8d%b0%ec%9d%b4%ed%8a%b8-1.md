---
layout: post
title: ps2avrU V1.6 펌웨어 업데이트
published: true
author: showjean
comments: true
date: 2014-01-27 08:01:59
tags: [ ]
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ed%8e%8c%ec%9b%a8%ec%96%b4'
permalink: '/ps2avru-v16-%ed%8e%8c%ec%9b%a8%ec%96%b4-%ec%97%85%eb%8d%b0%ec%9d%b4%ed%8a%b8-1'
---
펌웨어 링크 : http://blog.winkeyless.kr/17





2014.1.28.



&#8211; FN2 toggle 표시 LED 변경

: 기존에 지속적으로 N/L이 점멸하는 방식에서 변경시 1회만 깜박이는 방식으로 변경

: toggle on/off를 caps lock/num lock LED의 깜박임 수로 표시합니다.

: on/off 각 2번/1번 점멸 합니다.





&#8211; lock key/win 키 추가

: Lock Key 키는&nbsp;키보드의 모든 입력을 차단합니다.

: Lock Win 키는 좌/우 윈도우 키의 입력을 차단합니다.

: 두 키 모두 토글 방식으로 작동하며, 전원이 차단되면 모두 off 상태(차단하지 않는 상태)가 됩니다.



&#8211;&nbsp;custom macro 지원

: U.CON을 이용하여 패드 등을 사용할 때 하드웨어 매크로를 실행할 수 없거나, 실행을 했더라도 매크로 등록을 할 수 있는 키들이 없을 경우를 위한 외부에서 매크로를 설정하여 부트로더로 키보드에 저장할 수 있는 방법입니다.

: 부트 매퍼 사이트에 추가된 &#8220;Custom Macro&#8221;탭을 이용하여 매크로를 편집 후&nbsp;.hex파일을 생성하고 부트로더를 이용해 키보드에 업로드합니다.

: 커스텀 매크로를 작동시킬 수 있는 새로운 12개의 키가 추가되었습니다. (CST Mac1~12)



&#8211; Custom Macro 사용 방법

http://blog.winkeyless.kr/125











윈도우즈 OS의 멀티미디어 키가 작동하지 않는 경우 아래 링크의 설명을 참고하여 드라이버 업데이트를 해주세요.



http://blog.winkeyless.kr/110