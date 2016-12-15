---
layout: post
title: ps2avr Layout Editor V0.1.3
published: true
author: showjean
comments: true
date: 2013-06-21 07:06:02
tags:
    - ps2avr
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ea%b8%b0%ed%8c%90'
permalink: /40
---
안녕하세요.



ps2avr 소스의 키 매트릭스를 비교적 손쉽게 편집할 수 있는 툴입니다.



원하는 배열을 드롭박스에서 선택한 후 변경할 키를 선택 / 수정하고 &#8220;SAVE&#8221;를 클릭하면 첨부한 파일과 같은 .ps2avr 확장명으로 저장됩니다.



내용은 아래와 같습니다.




  
    // thumb V0.1
  
  
  
    {&nbsp;
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_Q,KEY_TAB,KEY_A,KEY_NONE,KEY_Z,KEY_NONE,KEY_NONE,KEY_1},
  
  
  
     {KEY_W,KEY_CAPS,KEY_S,KEY_NONE,KEY_X,KEY_NONE,KEY_NONE,KEY_2},
  
  
  
     {KEY_E,KEY_NONE,KEY_D,KEY_NONE,KEY_C,KEY_NONE,KEY_NONE,KEY_3},
  
  
  
     {KEY_R,KEY_T,KEY_F,KEY_G,KEY_V,KEY_B,KEY_5,KEY_4},
  
  
  
     {KEY_U,KEY_Y,KEY_J,KEY_H,KEY_M,KEY_N,KEY_6,KEY_7},
  
  
  
     {KEY_I,KEY_RBR,KEY_K,KEY_NONE,KEY_COMMA,KEY_NONE,KEY_EQUAL,KEY_8},
  
  
  
     {KEY_O,KEY_NONE,KEY_L,KEY_NONE,KEY_DOT,KEY_FN,KEY_NONE,KEY_9},
  
  
  
     {KEY_P,KEY_LBR,KEY_COLON,KEY_QUOTE,KEY_NONE,KEY_SLASH,KEY_MINUS,KEY_0},
  
  
  
     {KEY_LCTRL,KEY_LSHIFT,KEY_RCTRL,KEY_LALT,KEY_RSHIFT,KEY_RALT,KEY_APPS,KEY_NONE},
  
  
  
     {KEY_LGUI,KEY_HASH,KEY_BKSLASH,KEY_SPACE,KEY_ENTER,KEY_FN,KEY_BKSP,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE}
  
  
  
    },
  
  
  
    {&nbsp;
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_Q,KEY_NONE,KEY_LEFT,KEY_NONE,KEY_Z,KEY_NONE,KEY_ESC,KEY_F1},
  
  
  
     {KEY_UP,KEY_LED,KEY_DOWN,KEY_NONE,KEY_X,KEY_NONE,KEY_NONE,KEY_F2},
  
  
  
     {KEY_E,KEY_NONE,KEY_RIGHT,KEY_NONE,KEY_C,KEY_NONE,KEY_NONE,KEY_F3},
  
  
  
     {KEY_R,KEY_T,KEY_F,KEY_G,KEY_V,KEY_B,KEY_F5,KEY_F4},
  
  
  
     {KEY_NUMLOCK,KEY_Y,KEY_J,KEY_H,KEY_M,KEY_N,KEY_F6,KEY_F7},
  
  
  
     {KEY_PRNSCR,KEY_INSERT,KEY_HOME,KEY_NONE,KEY_END,KEY_NONE,KEY_F12,KEY_F8},
  
  
  
     {KEY_SCRLCK,KEY_NONE,KEY_PGUP,KEY_NONE,KEY_PGDN,KEY_FN,KEY_NONE,KEY_F9},
  
  
  
     {KEY_PAUSE,KEY_UP,KEY_LEFT,KEY_RIGHT,KEY_NONE,KEY_DOWN,KEY_F11,KEY_F10},
  
  
  
     {KEY_LCTRL,KEY_LSHIFT,KEY_RCTRL,KEY_LALT,KEY_RSHIFT,KEY_RALT,KEY_APPS,KEY_NONE},
  
  
  
     {KEY_LGUI,KEY_HASH,KEY_BKSLASH,KEY_BEYOND_FN,KEY_ENTER,KEY_FN,KEY_DEL,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE}
  
  
  
    },
  
  
  
    {&nbsp;
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_Q,KEY_NONE,KEY_A,KEY_NONE,KEY_Z,KEY_NONE,KEY_ESC,KEY_1},
  
  
  
     {KEY_W,KEY_CAPS,KEY_S,KEY_NONE,KEY_X,KEY_NONE,KEY_NONE,KEY_2},
  
  
  
     {KEY_E,KEY_NONE,KEY_D,KEY_NONE,KEY_C,KEY_NONE,KEY_NONE,KEY_3},
  
  
  
     {KEY_R,KEY_T,KEY_F,KEY_G,KEY_V,KEY_B,KEY_5,KEY_4},
  
  
  
     {KEY_U,KEY_Y,KEY_J,KEY_H,KEY_M,KEY_N,KEY_6,KEY_7},
  
  
  
     {KEY_I,KEY_RBR,KEY_K,KEY_NONE,KEY_COMMA,KEY_NONE,KEY_EQUAL,KEY_8},
  
  
  
     {KEY_O,KEY_NONE,KEY_L,KEY_NONE,KEY_DOT,KEY_DOWN,KEY_NONE,KEY_9},
  
  
  
     {KEY_P,KEY_LBR,KEY_COLON,KEY_QUOTE,KEY_NONE,KEY_SLASH,KEY_MINUS,KEY_0},
  
  
  
     {KEY_LCTRL,KEY_LSHIFT,KEY_RIGHT,KEY_LALT,KEY_UP,KEY_LEFT,KEY_LEFT,KEY_NONE},
  
  
  
     {KEY_LGUI,KEY_HASH,KEY_BKSLASH,KEY_SPACE,KEY_ENTER,KEY_FN,KEY_BKSP,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE},
  
  
  
     {KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE,KEY_NONE}
  
  
  
    }
  




이 내용을 ps2avr 펌웨어 소스중 keymap.h 파일의 아래 위치에&nbsp;대체 해 주면 됩니다. (펌웨어마다 숫자가 약간 다를 수 있습니다.)




  
    const uint8_t PROGMEM keymap_code[3][17][8] = &nbsp;{
  
  
  
    // 이 사이에 입력해주면 됩니다.
  
  
  
    &nbsp;};
  
  
  
    #endif
  






펌웨어 컴파일 방법은 리쿠님의 설명을 참고하세요.



리쿠님의 펌웨어 컴파일 방법

http://www.kbdmania.net/xe/data/6240715








   
  
  
  
  
  
  
  
  
    &#8211; 폭이 좁아서 작게&nbsp;보이는데, 아래 링크에서 넓은 화면을 볼 수 있습니다.
  
  
  
    http://showjean.com/keyboard/ps2avrLayoutEditor.html
  
  
  
  
  
  
  
  
  
  
  
  
    아직 미흡한 부분이 많으니, 필요한 부분이나 불편한 점이 있으면 의견 남겨주세요~
  
  
  
  
  
  
    2013.7.7
  
  
  
    v0.1.5&nbsp;&#8211; 잘못된 키가 설정된 부분 수정
  
  
  
  
  
  
    2013.7.7
  
  
  
    v0.1.4 &#8211; 각 기판의 FN 및 FN2 레이어도 편집할 수 있도록 추가
  
  
  
  
  
  
    2013.4.13
  
  
  
    v0.1.3 &#8211; thumb V0.1의 FN키들의 위치가 뒤바뀐 오류 수정
  
  
  
  
  
  
    2013.4.12&nbsp;
  
  
  
    v0.1.2 &#8211; thumb V0.1의 FN2를 위한 키 코드 추가
  
  
  
  
  
  
    2013.4.12&nbsp;
  
  
  
    v0.1.1 &#8211; thumb V0.1 레이아웃의 잘못 지정된 키 매핑을 수정
  
  
  
  
  
  
  