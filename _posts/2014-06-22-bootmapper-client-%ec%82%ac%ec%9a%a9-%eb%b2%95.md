---
ID: 468
post_title: Bootmapper Client 사용 법
author: showjean
post_date: 2014-06-22 19:52:08
post_excerpt: ""
layout: post
permalink: http://winkeyless.com/blog/468
published: true
---
<p>* Bootmapper&nbsp;Client는 ps2avrGB 펌웨어가 사용된 B 시리즈 기판에서 모든 기능을 사용할 수 있습니다.</p>
<p>* USB 인터페이스로 연결 된 상태에서만 작동이 됩니다.</p>
<p><br /></p>
<p><br /></p>
<p>Bootmapper&nbsp;Client 다운로드 :&nbsp;http://blog.winkeyless.kr/155</p>
<p><br /></p>
<p><br /></p>
<p>- BootmapperClient 를 실행합니다.</p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><b>* 펌웨어 업로드 방법</b></p>
<p><br /></p>
<p><b>- 처음 납땜 후 키보드에는 부트로더만 설치되어 있으므로 반드시 펌웨어 업로드를 해줘야 다른 모든 기능이 작동 됩니다.</b></p>
<p><br /></p>
<p>"Options" 탭으로 이동하여 "firm up(select .hex file)" 버튼을 클릭해 업로드할 펌웨어 파일을 선택해 줍니다.</p>
<p><br /></p>
<p>ps2avrGB 펌웨어 :&nbsp;http://blog.winkeyless.kr/153</p>
<p><br /></p>
<p><br /></p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile4.uf.210CDE4953A7394C27046A.png" class="aligncenter" width="316" height="118" filename="20140623_051243_001.png" filemime="image/png" /></p>
<p><br /></p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile28.uf.2411F34953A7394C21CD61.png" class="aligncenter" width="245" height="154" filename="20140623_051308_002.png" filemime="image/png" /></p>
<p><br /></p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile7.uf.250FBC4953A7394C25F4CE.png" class="aligncenter" width="223" height="189" filename="20140623_051314_003.png" filemime="image/png" /></p>
<p><br /></p>
<p>- 자동으로 부트로더로 진입하고 펌웨어를 업데이트 한 후 다시 키보드가 작동합니다.</p>
<p><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p>
<p>- 처음 납땜 한 후 펌웨어가 없는 상태라면 케이블 연결 시 자동으로 부트로더가 작동됩니다.&nbsp;</p>
<p>(부트로더가 작동되면 3 lock LED와 FUll LED가 계속 깜박입니다.)</p><p><br /></p><p>- 부트로더가 작동되면 아래 그림과 같이 "HIDBoot"라는 장치가 확인됩니다.</p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile2.uf.26294E435635D1C82EB16F.png" class="aligncenter" width="475" height="466" filename="20151101_174654_001.png" filemime="image/png" /></p><p><br /></p><p><br /></p>
<p>- 만약, 자동으로 부트로더가 작동되지 않는다면 (초기 일부 B.87 및 B.87 EX만 해당, 또는 펌웨어 오류로 작동되지 않을 경우)&nbsp;우선 부트로더를 수동으로 작동 시켜줘야 합니다. 기판의 "좌 ctrl"키를 누르거나 "JP1(BOOTLOADER)"를 쇼트 시킨 후 USB 케이블을 연결하면 부트로더가 작동 됩니다.</p>
<p>- B.pad의 부트로더 수동 작동 키는 "0"키 입니다.</p>
<p><br /></p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile6.uf.2136574253A927832ACA24.jpg" class="aligncenter" width="800" height="536" filename="DSC_0337.jpg" filemime="image/jpeg" /></p>
<p><br /></p>
<p>- BOOTLOADER(JP1)과&nbsp;BOOTMAPPER(JP2)를 혼동하지 말아주세요~&nbsp;</p>
<p>- <b>BOOTMAPPER(JP2) 점퍼는 사용할 일이 없습니다.</b></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><b>* RGB LED 설정</b></p>
<p><br /></p>
<p>"Options" 탭으로 이동하여 "connect" 버튼을 클릭합니다.</p>
<p><br /></p>
<p>- 초기 설정 컬러 값이&nbsp;모두 흰색입니다.</p>
<p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile6.uf.220C5C375773EB0A23B069.png" class="aligncenter" width="857" height="600" filename="20160630_003452_002.png" filemime="image/png" /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p>
<p style="text-align: left; clear: none; float: none;"></p>
<p><br /></p>
<p><strike>- 원활한 데이터 통신을 위해&nbsp;키보드의 스위치 LED(Full LED)가 off 됩니다.</strike></p>
<p><strike>- "disconnect" : 설정을 종료하고 스위치 LED는&nbsp;on 됩니다.</strike></p><p><br /></p><p><br /></p><p><br /></p><p><b>설정을 변경하면 약 2초 후 키보드에 자동으로 저장되며 caps lock / num lock LED가 깜박입니다.</b></p><p><br /></p><p>* RGB LED Settings</p>
<p>- Num of LEDs : 기판에 맞는 RGB LED의 수를 설정해 줍니다.&nbsp;</p>
<p><br /></p><p>- LED mode selection and color setting : LED mode를 선택하고 해당 컬러를 세팅합니다. 표시된 컬러 이외의 컬러는 헥사코드로 입력 할 수 있습니다. (ex, FF3300)</p><p style="margin-left: 2em;">: 모드 변경 단축키는 <b>ESC + Shift + Caps lock</b> 입니다.</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">: 1. rainbow 는 컬러를 변경 후 'update color'를 클릭해서 키보드에 저장합니다.&nbsp;</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">: 1. rainbow -&gt; type 설명</p>
<p style="margin-left: 4em;">fading : 모든 LED가 동일한 컬러로 자연스럽게 변환</p><p style="margin-left: 4em;">
</p><p style="margin-left: 4em;">immediately : 모든 LED가 동일한 컬러로 갑작스럽게 변경</p><p style="margin-left: 4em;">
</p><p style="margin-left: 4em;">sequential : 각 LED가 순차적으로 동일한 컬러로 변경</p><p style="margin-left: 4em;">
</p><p style="margin-left: 4em;">static : 각 LED가 각각의 컬러로 지정(변환 없음)</p><p style="margin-left: 4em;">
</p><p style="margin-left: 4em;">flow : 각 LED의 컬러가 흘러가듯 변환</p>
<p><br /></p>
<p>- Brightness : 슬라이더를 이동해 RGB LED의 밝기를 조절합니다.</p>
<p style="margin-left: 2em;">: 최대 밝기는 펌웨어에 의해서 제한됩니다.</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">: RGB LED가 밝을 수록 스위치 LED의 밝기는 어두워 집니다.</p>
<p><br /></p><p>- Transition Speed : RGB LED의 컬러 변환 속도를 설정합니다.</p><p style="margin-left: 2em;">: 낮을 수록 빠른 변환이 이루어집니다.</p><p><br /></p>
<p>- RGB LED key event selection and color setting</p>
<p style="margin-left: 2em;">: 키를 누를 때 RGB LED가 반응하도록 설정합니다.</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">: 1. color - 지정된 컬러로 전환</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">: 2. complementary color - 현재 컬러의 보색으로 전환</p>
<p><br /></p><p>* Full&nbsp;LED Settings</p><p>- Full LED Mode : 스위치 LED의 작동 모드를 변경합니다.</p><p style="margin-left: 2em;">:&nbsp;모드 변경 단축키는 <b>ESC + Caps lock</b> 입니다.</p><p style="margin-left: 2em;">1. LED off - &nbsp;꺼짐</p><p style="margin-left: 2em;">2. fading - 숨쉬기</p><p style="margin-left: 2em;">3. on - 계속 켜짐</p><p style="margin-left: 2em;">4. key down level up - 키 입력이 잦을수록 밝아짐</p><p style="margin-left: 2em;">5. key down level down - 키 입력이 잦을수록 어두워짐</p><p><br /></p><p>-&nbsp;Full LED Brightness :&nbsp;<span style="font-size: 9pt; line-height: 1.5;">스위치 LED의 밝기를 조절합니다.</span></p><p style="margin-left: 2em;">: RGB LED가 켜져 있다면 Full LED는 설정 값을 높혀도 밝기가 변하지 않습니다.&nbsp;</p><p style="margin-left: 2em;">: RGB LED의 밝기를 어느정도 낮추면 Full LED의 밝기가 밝아집니다.</p><p><br /></p><p><br /></p><p>* 3Lock LED Settings</p><p>Num lock, Scroll lcok, Caps lock 별로 작동 방식을 설정한다.</p><p style="margin-left: 2em;">1. Lock Indicator : 각 Lock 상태와 연동되어 on/off</p><p style="margin-left: 2em;">2. Always On : 항상 on</p><p style="margin-left: 2em;">3. Always Off : 항상 off</p><p style="margin-left: 2em;">3. Lock Reverse : Lock 상태와 반대로 작동</p><p style="margin-left: 2em;">4. FN2 Lock Indicator : FN2 Lock 상태일 경우 on (NCS&nbsp;상태는&nbsp;2번/1번 깜박임으로 표시)</p><p style="margin-left: 2em;">5.&nbsp;FN3&nbsp;Lock Indicator :&nbsp;FN3&nbsp;Lock 상태일 경우 on</p><p style="margin-left: 2em;">6.&nbsp;FN2/3 Lock Indicator :&nbsp;FN2 또는 FN3이&nbsp;Lock 상태일 경우 on</p><p><br /></p><p>* Options</p><p>- Esc to ~ : shift + ESC를 누를 경우 "~"를 입력 할 것인지 설정</p><p><br /></p><p><br /></p>
<p><span style="background-color: transparent;">모든 설정을 마쳤다면 "disconnect"버튼을 클릭합니다.</span></p>
<p><br /></p>
<p><span style="font-size: 9pt; line-height: 1.5; background-color: transparent;"><br /></span></p>
<p><br /></p>
<p><b>* 키 맵핑</b></p>
<p><br /></p>
<p>이전 부트매퍼와 사용법은 같지만, 'download'버튼으로 키보드의 키 맵을 직접 읽어 올 수 있고, 'upload'로 바로 업로드 가능합니다.</p>
<p><br /></p>
<p>"Key Mapper"탭으로 이동합니다.</p>
<p><br /></p>
<p><br /></p>
<p>- 아직 키 맵핑이 되어 있지 않은 상태에서 처음 맵핑을 할 경우</p>
<p><br /></p>
<p>1. 펌웨어에 포함된 기본 키맵 파일을 load 합니다. "load keymap_part.hex or .json" 버튼을 이용합니다.</p>
<p style="margin-left: 2em;">- 펌웨어 :&nbsp;http://blog.winkeyless.kr/153</p>
<p><br /></p>
<p>2. "upload' 버튼을 클릭하면 부트로더로 자동 전환 된 후&nbsp;키 맵이&nbsp;업로드 됩니다.</p>
<p style="margin-left: 2em;">: 'reboot after uploading'을 선택하면 키맵을 업로드 한 후 자동으로 키보드 상태로 돌아옵니다. 선택하지 않으면 부트로더 상태로 머물러 있습니다.</p>
<p style="margin-left: 2em;">(부트로더 상태에서 키보드 상태로 전환하고 싶다면, 'Options' 탭의 "set keyboard" 버튼을 클릭하면 됩니다.)</p>
<p><br /></p>
<p>3. 키 설정을 변경하고 싶을 경우 "toggle bootmapper" 버튼을 눌러주면 키보드의 부트맵퍼 트리거가 작동됩니다.</p>
<p style="margin-left: 2em;">: caps lock LED가 약 1초 간격으로 점멸 됩니다.</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">: 이때는 키보드로 작동되지 않고, 키를 누르면 해당 키의 매트릭스 위치를 출력합니다.&nbsp;</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">ex&gt; .7,1.</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">: 해제 하고 싶다면 다시 한번 "toggle bootmapper" 버튼을 눌러주면 됩니다.</p>
<p><br /></p>
<p>4. 키보드의 키를 누르면 매트릭스 상에 붉은 색으로 표시가 됩니다.&nbsp;</p>
<p style="margin-left: 2em;">: "save keymap_part.hex"버튼 옆에 글자로 layer와 col, row가 표시됩니다.</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">: 마우스 클릭으로 직접 매트릭스를 선택할 수 있습니다.</p>
<p><br /></p>
<img src="http://cfile4.uf.tistory.com/image/23130436529B692D0E50CF" height="502" width="611">
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>5. 원하는 키코드를 하단에서 선택합니다.&nbsp;그럼, 매트릭스 그리드에 선택한 키 값이 표시됩니다.&nbsp;</p>
<p><br /></p>
<img src="http://cfile22.uf.tistory.com/image/27131736529B692E3395AC" height="382" width="614">
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>6.&nbsp;4-5를 반복하여 원하는 키들에 매핑을 합니다.</p>
<p style="margin-left: 2em;">- 기본적으로 키를 선택하면 모든 레이어에 적용이 됩니다.&nbsp;</p><p style="margin-left: 2em;">
</p><p style="margin-left: 2em;">- 특정 레이어만 키를 변경하고 싶다면 "apply to all layers" 항목의 체크를 해제하고 상단의 레이어 탭을 눌러 원하는 레이어만 변경하면 됩니다.</p>
<p><br /></p>
<p>7. 원하는 모든 키를 변경했다면 "upload" 버튼을 눌러 업로드 합니다.</p>
<p><br /></p>
<p><br /></p>
<p>- 이미 키 맵핑이 된 키보드의 일부 키만 변경 할 경우</p>
<p><br /></p>
<p>1. "download" 버튼을 눌러 키보드로 부터 키 맵을 다운로드 합니다.</p>
<p style="margin-left: 2em;">: col/row 데이터가 표시됩니다.</p>
<p><br /></p>
<p>2. "toggle bootmapper" 버튼을 눌러 키보드의 부트맵퍼 트리거를 작동 시킵니다.</p>
<p style="margin-left: 2em;">: 부트맵퍼 트리거를 작동시키지 않고 마우스 클릭으로 직접 매트릭스를 선택할 수 있습니다.</p>
<p><br /></p>
<p>3. 키보드의&nbsp;원하는 키를 눌러 col/row를 선택한 후 변경할 키코드를 하단에서 선택합니다.</p>
<p><br /></p>
<p>4. 원하는 모든 키를 변경했다면 "upload" 버튼을 눌러 업로드 합니다.</p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><b>* 커스텀 매크로</b></p>
<p><br /></p>
<p>- 기본 사용 방법은 Boot Mapper Site의 그것과 동일 합니다. 아래 링크의 내용을 참고하세요.</p>
<p>Boot Mapper Site의 커스텀 매크로 사용 법 :&nbsp;http://blog.winkeyless.kr/125</p>
<p><br /></p>
<p>- 다만, upload/download 가 추가되어 키보드의 매크로 데이터를 바로 읽거나 쓸 수 있는 점이 다릅니다.</p>
<p><br /></p>
<p><br /></p>