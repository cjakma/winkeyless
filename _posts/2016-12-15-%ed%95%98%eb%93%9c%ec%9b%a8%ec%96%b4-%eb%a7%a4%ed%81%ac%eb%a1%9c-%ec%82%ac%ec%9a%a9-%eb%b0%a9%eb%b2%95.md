---
layout: post
title: 하드웨어 매크로 사용 방법
published: true
author: showjean
comments: true
date: 2013-10-08 09:10:07
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: /190
---
최신 버전의 펌웨어에서는 하드웨어 매크로를 지원하지 않습니다.

&#8220;퀵 매크로&#8221;만 사용 가능하므로 참고 바랍니다.

(ps2avrGB, ps2avrGB4U 등)



하드웨어 매크로 사용 방법



[#M_사용법 보기|사용법 닫기|

English :&nbsp;http://blog.winkeyless.kr/184





  키코드 표 :&nbsp;http://blog.winkeyless.kr/54






  키코드 표의 KEY_MAC1~KEY_MAC12까지 12개의 키코드를 원하는 키에 매핑하면 해당 매크로를 실행시키는 키가 됩니다.






  매크로 키의 수대로 12가지의 매크로를 등록할 수 있고, 한 매크로는 최대 24키까지 등록이 가능합니다.&nbsp;












  매크로 등록은 다음 순서대로 하면 됩니다.






  우선 키매핑 시작 처럼 왼쪽 ctrl + alt + shift와 오른쪽 shift(총 4키)를 약 5초간 누르고 있다 떼면 다음과 같은 메세지가 출력됩니다.



  &#8211; 131230 이전의 버젼은 왼쪽 ctrl+alt+shit (총 3키)를 이용합니다.



  &nbsp;



  
    hello
  
  
  
    &nbsp;
  
  
  
    select mode
  
  
  
    1:key mapping
  
  
  
    2:macro
  
  
  
    2:lazy fn : on
  
  
  
    3:fn2/3 led : off
  
  
  
    4:esc to ~ : off
  
  
  
    7:exit
  
  
  
    9:boot mapper
  
  
  
    >>
  



  1 번은 기존의 키매핑을 하는 단계로 가게 됩니다.



  2 번은 매크로 등록을 하게 됩니다.






  2번을 선택하면 아래와 같은 메세지가 출력됩니다.






  
    Macro
  
  
  
    1:Select Macro Index
  
  
  
    2:Clear Macro
  
  
  
    3:Exit
  
  
  
    6:Back
  
  
  
    9:Clear All
  
  
  
    >>&nbsp;
  



  1 : 등록할 매크로의 번호를 선택합니다. 01~12까지 12개 입니다.



  2 : 매크로 삭제



  3 : 종료



  6 : 메인 메뉴로 돌아갑니다.



  9 : 등록된 모든 매크로를 제거 합니다.






  1번을 선택하면



  
    input macro index (01~12, cancel: 00, must 2 numbers) :
  



  01~12까지 숫자를 입력 받습니다. 이 숫자는 매크로의 번호를 가리키는 것으로 &#8220;03&#8221;과 같은 식으로 2자리로 입력해야 합니다. &#8220;00&#8221;을 누르면 취소됩니다.






  매크로 번호를 입력하면 아래와 같은 메세지가 출력됩니다. 이후에 원하는 키를 눌러 매크로를 저장합니다.



  
    input key (max 24 keys, stop : press ESC during 1 sec)
  






  24개의 키가 입력되면 자동으로 종료되며, 그전에 종료하고 싶다면 ESC키를 1초이상 누르고 있으면 됩니다.






  매크로는 별도의 저장 단계 없이 입력 종료와 동시에 저장되므로, 더이상 다른 번호에 매크로를 등록하지 않으려면 2:Exit 를 선택해 종료합니다.









  이 후 매크로 키(KEY_MAC1~12)로 매핑 해놓은 키를 누르면 해당 번호의 매크로가 실행됩니다.









  2번을 선택하면



  
    select index (01~12, cancel: 00) :&nbsp;
  



  원하는 매크로 번호를 선택하면 삭제 됩니다.


_M#]





* 퀵 매크로 이용

&#8211; 하드웨어&nbsp;메뉴를 거치지 않고 원하는 하드웨어 매크로(KEY_MAC1~12)에 빠르게 매크로를 설정할 수 있는 기능

: QM(Quick Macro)키 + 원하는 매크로 키(KEY_MAC1~12) 를 누르고 모든 키에서 손을 떼면 caps lock LED가 길게 2번 반짝이며 저장을 시작합니다.

: 이 상태에서 원하는 키 조합을 입력하고 다시 QM키를 누르면 caps lock LED가 길게 1번 반짝이며 매크로 저장이 종료 됩니다.

: 해당 매크로키(KEY_MAC1~12)를 누르면 저장 된 키 조합이 출력됩니다.

: 퀵 매크로는 하드웨어 메뉴에서 저장하는 하드웨어 매크로에만 해당되며 커스텀 매크로에는 적용 되지 않습니다.