---
layout: post
title: >
    부트로더를 이용한 펌웨어/키맵/매크로
    업로드 방법
published: true
author: showjean
comments: true
date: 2013-06-30 10:06:23
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: /75
image:
    feature: cfile3.uf.26626537528D61E42E6EBF.jpg
---
*&nbsp;부트로더를 이용한 펌웨어/키맵/매크로 업로드&nbsp;방법





-1. B 시리즈 기판( B.87 등 이름이 B로 시작하는 기판 들)은 아래 링크의 내용을 참고하세요.

bootMapper Client 사용 법 :&nbsp;http://blog.winkeyless.kr/154





*** 아래 설명은 &nbsp;ps2avrU 기판들(A.87U와 같이&nbsp;기판 이름이 U로 끝나는 것, 또는, ps2avr-ext를 연결한 ps2avr 기판)에 해당하는 내용입니다.**



0. 아래의 링크에서 부트로더를 이용한 펌웨어 업데이트에 필요한 파일을 PC의 적당한 폴더에 다운로드합니다.

&#8211; http://blog.winkeyless.kr/17





0.0.1 ps2avr 시리즈의 기판의 경우 콤보 펌웨어가 아닌 PS/2 전용 펌웨어를 이용하려면 아래 링크의 각 기판 자료중 펌웨어인 .hex를&nbsp;업로드해주면 됩니다.


  A.87 :&nbsp;http://blog.winkeyless.kr/4



  MX-mini :&nbsp;http://blog.winkeyless.kr/6



  thumb :&nbsp;http://blog.winkeyless.kr/9









0.1. 만약, 키보드가 PC에 연결되어 있는 상태라면&nbsp;키보드를 PC에서 연결해제 합니다.





1. 키보드에 USB 케이블을 연결합니다.

(A.87 ps2avr, MX-mini ps2avr, thumb 등 ps2 전용 기판이라면 아래 그림과 같이 추가로 USB케이블에 ps2avr-ext(이하 확장 모듈)을 연결해야 합니다.)




  





  
  
  
  
  
  
  
  
  
  
    2. 키보드의 &#8220;Q&#8221;키를 누른 상태(col1과 row2가 쇼트된 상태)로 USB케이블(확장 모듈)을 PC의 USB 포트에 연결합니다.
  
  
  
    &#8211; &#8220;Q&#8221;키에는 다이오드가 납땜 되어 있어야 합니다.&nbsp;
  
  
  
    &#8211; &#8220;Q&#8221;키는 매트릭스상 col1, row2에 위치합니다.
  
  
  
    &#8211; U.CON이라면 PCB의 FW_JP를 쇼트 시키면 &#8220;Q&#8221;키를 누른 것과 같습니다.&nbsp;
  
  
  
    &#8211; &#8220;Q&#8221;키에 스위치나 다이오드를 납땜하기 전이라면 다음 그림과 같이 전기가 잘 통하는&nbsp;핀셋 등으로 col1과 row2를 직접 쇼트 시킬 수도 있습니다.
  
  
  
  
  
  
    
  
  
  
  
  
  
    
  
  
  
  
  
  
    
  
  
  
  
  
  
    &#8211; 이때 키보드의 모든 LED가 연속적으로 깜빡입니다. 이 상태가 부트로더로 작동되는 상태입니다.
  
  
  
    &nbsp;(이젠 &#8220;Q&#8221;키를 누르고 있지 않아도 됩니다.)&nbsp;
  
  
  
    &#8211; 이렇게 LED가 깜빡이는 상태로 계속 진행합니다.
  
  
  
    &#8211; 만약 그렇지 않다면 부트로더를 설치하세요.
  
  
  
    &#8211; 부트로더 설치방법 :&nbsp;http://blog.winkeyless.kr/15
  
  
  
  
  
  
    [#M_더보기(장치 확인)|접기|
  
  
  
    2.1. 만약 부트로더를 처음 사용한 것이라면 PC에서 해당 드라이버를 설치하는 약간의 시간이 소요되고, USB장치로 인식하게 됩니다.
  
  
  
  
  
  
    &#8211; &#8220;USB 입력 장치&#8221;로 인식을 하고,
  
  
  
  
  
  
    
  
  
  
  
  
  
  
  
  
  
  
  
    &#8211; 속성을 보면 다음과 같이 &#8220;하드웨어 ID&#8221;가 VID = 16C0, PID = 05DF 입니다.
  
  
  
  
  
  
    
  
  
  
  
  
  
  
  
  
  
  
  
    _M#]
  
  
  
  
  
  
  
  
  
    3. HIDBootFlash.exe 를 더블 클릭하여 실행합니다.
  
  
  
    &#8211; 만약 위 파일이 실행되지 않는다면&nbsp;Microsoft Visual C++ 2005 Redistributable Package를 설치해주세요.
  
  
  
    64bit :&nbsp;http://www.microsoft.com/ko-kr/download/details.aspx?id=21254
  
  
  
    32bit :&nbsp;http://www.microsoft.com/ko-kr/download/details.aspx?id=3387
  
  
  
    &#8211; 또는&nbsp;아래의 링크를 참고하여 다른 방법으로 펌웨어를 업로드하세요.
  
  
  
    http://blog.winkeyless.kr/29
  
  
  
  
  
  
  
  
  
    
  
  
  
    
  
  
  
    &#8211; &#8220;FInd Device&#8221; 버튼을 클릭하면 아래의 스크린샷처럼 다른 버튼들이 보여집니다.
  
  
  
  
  
  
  
  
  
    
  
  
  
  
  
  
    &#8211; 스크린샷에는 keymani_a87.hex가 자동으로 검색되어 선택된 상태입니다.
  
  
  
  
  
  
    &#8211; 만약, 이 펌웨어를 그대로 사용하려면 &#8220;Flash Device&#8221;버튼을 클릭합니다.
  
  
  
  
  
  
    &#8211; 다른 펌웨어를 선택하겠다면 &#8220;Open .hex File&#8221;버튼을 클릭하여 나타나는 창에서 hex파일을 선택합니다.
  
  
  
  
  
  
  
  
  
  
  
  
    
  
  
  
  
  
  
    &#8211; 이제 &#8220;Flash Device&#8221;버튼을 클릭하면 위 스크린샷처럼 숫자가 몇 초간&nbsp;스크롤됩니다.
  
  
  
    (펌웨어가 MCU에&nbsp;업로드되는 진행상태를 나타내는 숫자입니다.)
  
  
  
  
  
  
  
  
  
  
  
  
    
  
  
  
  
  
  
    &#8211; 펌웨어&nbsp;업로드가 완료되었습니다.
  
  
  
  
  
  
  
  
  
    3.1 ps2avrU V1.5이상(2013.12.2. 이후)의 펌웨어라면 펌웨어 자체에는 키 매핑이 되어 있지 않으므로, 키맵 파일도 부트로더를 이용해서 업로드해줘야 합니다.
  
  
  
    &#8211; 기본 키맵 파일은 펌웨어와&nbsp;같은 압축 파일에 포함되어 있으며 keymap_part(pcb_name).hex의 이름을 갖고 있습니다.
  
  
  
    &#8211;&nbsp;http://blog.winkeyless.kr/17 : 링크의 파일 설명 참고
  
  
  
    &#8211; 방법은 위 3번과 동일하며 .hex 파일만 키맵 파일로 선택해서 &#8220;Flash Device&#8221;를 눌러주면 됩니다.
  
  
  
    &#8211; 결과적으로 처음 펌웨어를 업로드 하는 경우라면 부트로더를 이용해서 펌웨어와 키맵을 각 1번씩 2번 업로드해야 합니다. 이후부터는 키맵은 계속 유지되므로 새로운 펌웨어만&nbsp;업데이트(업로드) 해주면 됩니다.
  
  
  
    &#8211; 키맵의 변경은 부트 매퍼를 이용해 손쉽게 할 수 있습니다.&nbsp;
  
  
  
    부트 매퍼 사용법 :&nbsp;http://blog.winkeyless.kr/90
  
  
  
  
  
  
    3.2 ps2avrU V1.6 이상(2014.1.28. 이후)의 펌웨어라면 Custom Macro 사용을 위해 위와 같은 방법으로 macro.hex 파일을 키보드에 업로드 해줄 수 있습니다.
  
  
  
  
  
  
  
  
  
    4. USB 케이블(확장 모듈)을 USB 포트로부터 분리합니다.
  
  
  
  
  
  
    5. 다시 USB 포트에 연결해 USB 키보드로 인식이 되는지 확인합니다.
  
  
  
  
  
  
    5.1. 다음 그림처럼 PS/2 젠더를 연결하고&nbsp;PS/2 포트에 연결해서 PS/2 키보드로 인식/작동이 되는지 확인합니다.
  
  
  
  
  
  
    
  
  
  
  
  
  
  
  
  
    ** 참고 블로그 : 뚜비뚜비뚜뚜바 님&nbsp;sam209.tistory.com/1105
  
  
  
  
  
  
  
  
  
  