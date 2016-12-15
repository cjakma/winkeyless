---
ID: 215
post_title: FaceU 기판 관련 자료
author: showjean
post_date: 2013-10-16 09:27:48
post_excerpt: ""
layout: post
permalink: http://winkeyless.com/blog/215
published: true
---
<p>* 파일 설명</p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p style="text-align: left;"></p><p></p><p><a href="http://winkeyless.com/blog/wp-content/uploads/1/cfile24.uf.2720233F525E5A5B190C32.dwg" class="aligncenter" filename="face_outline_2000.dwg" filemime="application/octet-stream" />cfile24.uf.2720233F525E5A5B190C32.dwg</a><span style="background-color: transparent; font-size: 9pt; line-height: 1.5;">&nbsp;: v0.1 기판 외곽선과 홀의 위치를 표시한 도면</span></p><p></p><p></p>
<p><br /></p><p><br /></p><p style="text-align: left;"><a href="http://winkeyless.com/blog/wp-content/uploads/1/cfile7.uf.2441C233533507462F873A.dwg" class="aligncenter" filename="face_layout_v2_2000.dwg" filemime="application/octet-stream" />cfile7.uf.2441C233533507462F873A.dwg</a>&nbsp;: V0.2 기판 외곽선과 홀의 위치를 표시한 도면</p><p style="text-align: left;"><br /></p><p><br /></p><p><br /></p><p><br /></p><p>*레이아웃</p><p style="text-align: left; clear: none; float: none;"></p><p><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile9.uf.2471D33653350A4822E9C6.jpg" class="aligncenter" width="860" height="413" filename="keylayout_thumb.jpg" filemime="image/jpeg" style="background-color: transparent; font-size: 9pt; line-height: 1.5;" /></p><p>- 6x 스페이스 바는 V0.2부터 지원 됩니다.<br /></p><p><br /></p>
<p><br /></p>
<p><br /></p>
<p>* 소자 목록</p>
<p><br /></p>
<p>12종 19개</p>
<p>ATMEGA32A-AU</p>
<p>USB-120</p>
<p>Chip Tantal A size 10uF 16V</p>
<p>MMBT2222A (SOT-23) * 3</p>
<p>ZENER DIODE, 350mW, 3.6V, SOT-23 (BZX84C3V6) * 2</p>
<p>CRYSTAL 12MHz (SMD 3X5 size)</p>
<p>2012 Chip Resistor, 330Ω(331) * 2</p>
<p>2012 Chip Resistor, 1.5kΩ(152) * 2</p>
<p>2012 Chip Resistor, 68Ω(680) * 2</p>
<p>2012 Chip Resistor, 10kΩ(103)</p>
<p>2012 size Chip Monolithic Ceramic Capacitor 18pF * 2</p>
<p>2012 size Chip Monolithic Ceramic Capacitor 0.1uF</p>
<p><br /></p>
<p><br /></p><p>* LED 컬러별 저항 값 - PS/2 200mA 기준 (출처 : 코렐라스님 자료)</p><p>하얀색/보라색(최소전압 약 3V) : 820</p><p>빨간색/노란색(최소전압 약 1.8V) : 1.3K</p><p>파란색/초록색(최소전압 약 2.8V) : 900</p><p><br /></p><p>- 저항 사이즈 : 2012</p>
<p><br /></p>
<p>- 위 값은 보통의 사용하는 LED를 기준으로 작성되었습니다.</p>
<p>LED의 정확한 저항 값은 해당 데이터시트를 참고하여 계산해야 합니다.</p>
<p><br /></p>
<p><br /></p><p>* 스위치 입력에 필요한 다이오드는 1N4148(DIP or SMD) 입니다.</p><p><br /></p>
<p><br /></p>
<p>* ps2avrU bootloader 사용</p>
<p>- 기본적으로 부트로더만 설치되어 있으므로, 이를 이용해 펌웨어를 업로드해야 합니다.</p>
<p><br /></p>
<p>- 부트로더가 설치되었는지 확인하는 방법 : http://blog.winkeyless.kr/14</p>
<p><br /></p>
<p>- 만약 MCU를 교체하여 부트로더가 설치되어 있지 않다면 설치해야 합니다.&nbsp;</p>
<p>- 부트로더 설치 방법 : http://blog.winkeyless.kr/15</p>
<p><br /></p>
<p>- 부트로더를 이용한 펌웨어 업로드 방법 : http://blog.winkeyless.kr/18</p>
<p><br /></p>
<p><br /></p>
<p>* 기본 key matrix</p><p>https://docs.google.com/spreadsheet/ccc?key=0Ah1Lcjc-gPfndFM1emlhcExfU3JYRUY4SUNqR1ZIUmc&amp;usp=sharing</p>
<p><br /></p><p><br /></p><p><br /></p><p>*기판 사양 - V0.2</p><p>- 레이아웃&nbsp;</p><p>: 윈키/윈키리스 콤보,&nbsp;</p><p>: 캡스락 3000/8000(마제식) 지원</p><p>: R Shift 2.75/1.75 지원</p><p>: back space 2 / 1 지원</p><p>: 마제식 스페이스 바 지원</p><p>: 6x 스페이스 바 지원</p><p>: ISO 배열 지원</p><p>- Full LED 지원 : 5가지 LED 모드</p><p>- PCB : 1.6T (흰색)</p><p>- 포커 X 하우징과 호환 : 대부분의 커스텀 하우징에도 호환이 되지만 포커X와 USB 커넥터의 위치가 약 1mm정도 차이가 있기 때문에 호환되지 않는 하우징이 있을 수 있습니다.</p><p>- 하우징(보강판)리스를 위한 마운트홀 추가</p><p>- mac os 호환</p><p><br /></p><p><br /></p>
<p>*기판 사양 - V0.1</p>
<p>- 레이아웃 : 윈키/윈키리스 콤보,&nbsp;</p>
<p style="margin-left: 6em;">캡스락 3000/8000(마제식) 지원</p>
<p style="margin-left: 6em;">R Shift 2.75/1.75 지원</p>
<p style="margin-left: 6em;">back space 2 / 1 지원</p>
<p>- Full LED 지원 : 5가지 LED 모드</p>
<p>- PCB : 1.2T (녹색)</p>
<p>- 모든 소자 뒷면에 배치</p>
<p>- 포커 X 하우징과 호환</p>
<p>- 하우징(보강판)리스를 위한 마운트홀 추가</p>
<p><br /></p>
<p><br /></p>
<p>*ps2avrU(펌웨어) 사양&nbsp;</p>
<p>- 인터페이스 : USB / PS/2 콤보 (자동 인식)</p>
<p>- 하드웨어 키매핑 지원 : 별도의 SW없이 즉시 키매핑 변경 가능</p>
<p>- Full LED 지원 : 5가지 LED 모드</p>
<p>- 하드웨어 매크로 지원</p>
<p><br /></p>
<p><br /></p>
<p>펌웨어에대한 더 많은 정보는 아래 링크를 참고하세요.</p>
<p>http://blog.winkeyless.kr/19</p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>* 레이어&nbsp;</p>
<p>1. 기본 레이어</p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile3.uf.256FB041525E775701A944.jpg" class="aligncenter" width="914" height="389" filename="keylayout_NORMAL.jpg" filemime="image/jpeg" /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>2. FN 레이어</p>
<p><br /></p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile9.uf.235E1F33525E77EB284512.jpg" class="aligncenter" width="914" height="389" filename="keylayout_FN_BR.jpg" filemime="image/jpeg" /></p>
<p><br /></p>
<p style="text-align: left; clear: none; float: none;"></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>3. FN2 레이어 - FN + space를 눌러 전환하고 유지됩니다. on/off 변경에 따라서 Num Lock LED가 점멸됩니다.</p>
<p>다시 기본레이어로 돌아가려면 FN + space를 다시 누르거나 Esc + Backspace를 누르면됩니다.</p>
<p>(포커의 크루즈 커서 기능과 유사하게 이용할 수 있습니다.)</p>
<p><br /></p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile9.uf.2741DF41525E77562158BA.jpg" class="aligncenter" width="914" height="389" filename="keylayout_FN2.jpg" filemime="image/jpeg" /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p><style>.tblGenFixed td {padding:0 3px;overflow:hidden;white-space:normal;letter-spacing:0;word-spacing:0;background-color:#fff;z-index:1;border-top:0px none;border-left:0px none;border-bottom:1px solid #CCC;border-right:1px solid #CCC;} .dn {display:none} .tblGenFixed td.s27 {background-color:#00ffff;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #000000;} .tblGenFixed td.s28 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s9 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #000000;border-bottom:1px solid #cccccc;} .tblGenFixed td.s25 {background-color:#ffff00;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s26 {background-color:#ffff00;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #000000;} .tblGenFixed td.s7 {background-color:#efefef;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;border-left:1px solid #000000;} .tblGenFixed td.s23 {background-color:#00ffff;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s8 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s24 {background-color:#00ffff;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #000000;border-bottom:1px solid #cccccc;} .tblGenFixed td.s21 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s5 {background-color:#efefef;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s22 {background-color:#00ffff;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s6 {background-color:#efefef;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #000000;border-bottom:1px solid #cccccc;} .tblGenFixed td.s3 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:left;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s4 {background-color:#efefef;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;border-left:1px solid #000000;} .tblGenFixed td.s20 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:;border-bottom:1px solid #cccccc;} .tblGenFixed td.s0 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:left;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-top:1px solid #CCC;border-right:;border-bottom:1px solid #cccccc;border-left:1px solid #CCC;} .tblGenFixed td.s2 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:left;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #000000;border-left:1px solid #cccccc;} .tblGenFixed td.s1 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-top:1px solid #CCC;border-right:;border-bottom:1px solid #cccccc;} .tblGenFixed td.s16 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #000000;border-bottom:1px solid #000000;} .tblGenFixed td.s17 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;border-left:1px solid #cccccc;} .tblGenFixed td.s18 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s19 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;text-decoration:none;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:;border-bottom:1px solid #cccccc;} .tblGenFixed td.s12 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s13 {background-color:#efefef;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #000000;border-left:1px solid #000000;} .tblGenFixed td.s14 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #000000;} .tblGenFixed td.s15 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #000000;} .tblGenFixed td.s10 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:auto-ltr;white-space:normal;overflow:hidden;border-right:1px solid #cccccc;border-bottom:1px solid #cccccc;} .tblGenFixed td.s11 {background-color:white;font-family:arial,sans,sans-serif;font-size:100.0%;font-weight:normal;font-style:normal;color:#000000;text-decoration:none;text-align:center;vertical-align:bottom;direction:Context;white-space:normal;overflow:hidden;border-right:1px solid #000000;border-bottom:1px solid #cccccc;} </style><p><br /></p>