---
ID: 384
post_title: Custom Macro 사용 방법
author: showjean
post_date: 2014-01-27 20:54:33
post_excerpt: ""
layout: post
permalink: http://winkeyless.com/blog/384
published: true
---
<p><br /></p>
<p>1. BootMapper Client를 실행하거나&nbsp;<a class="tx-link" href="http://winkeyless.kr/bootMapper" target="_blank" style="font-size: 9pt; line-height: 1.5;">부트 매퍼 사이트</a><span style="font-size: 9pt; line-height: 1.5;">에 접속</span><span style="font-size: 9pt; line-height: 1.5;">하여 "Custom Maco"를 선택합니다.</span></p><p><span style="font-size: 9pt; line-height: 1.5;"><br /></span></p><p><span style="font-size: 9pt; line-height: 1.5;">- B 시리즈 기판의 경우&nbsp;</span><span style="font-size: 12px; line-height: 18px;">BootMapper Client의&nbsp;</span><span style="font-size: 9pt; line-height: 1.5;">"Download"를 클릭하여 현재 매크로를 불러올 수 있습니다.</span></p><p><br /></p>
<p><br /></p>
<p><br /></p>
<p style="TEXT-ALIGN: left; FLOAT: none; CLEAR: none"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile30.uf.2428C93952E76335108F4C.png" class="aligncenter" width="405" height="143" filename="20140128_165148_001.png" filemime="image/png" /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>2. 화면이 바뀌면 아래와 같은 모양이 됩니다. 매크로 번호를 선택하고 연속 입력을 하고 싶은 문자를 화면에서 마우스로 선택하면 리스트에 문자가 차례대로 추가 됩니다.</p>
<p>- 표시는 대문자로 되지만 기본 입력은 소문자 입니다. (키보드의 caps lock이 켜져 있으면 대문자로 입력이 되겠죠.)</p>
<p>- 제거 하고 싶은 문자를 선택하고 "remove"를 클릭하면&nbsp;리스트에서 제거 됩니다.</p>
<p>- 문자의 위치를 바꾸고 싶다면 해당 문자를 마우스로 드래그해서 조정할 수 있습니다.</p>
<p style="TEXT-ALIGN: left; FLOAT: none; CLEAR: none"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile25.uf.271F373952E76335180774.png" class="aligncenter" width="731" height="555" filename="20140128_165333_002.png" filemime="image/png" /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>3. 편집을 완료 했다면 "save macro.hex"를 클릭해서 .hex 파일로 저장합니다.</p>
<p>- 부트로더를 이용해 이 파일을 키보드에 업로드 해주면 "Cst&nbsp;Mac1~12" 키로 매크로를 작동 시키게 됩니다.</p>
<p>- "load.hex"을 클릭해 저장된 매크로 파일을 불러 올 수 있습니다.</p>
<p>- ps2avrU 펌웨어는 키보드에 저장된 매크로 내용을 가져올 수 있는 방법이 없으니, 매크로 수정을 위해서&nbsp;.hex 파일을 잘 보관하시길 바랍니다.</p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>4. 단순 문자열 입력이 아닌 조합 키를 함께 사용할 경우 편집하는 방법은 아래와 같습니다.</p>
<p>- 우선 조합 할 키 들을 마우스 클릭하여 리스트에 추가합니다.</p>
<p>- 아래 그림은 Ctrl+C 를 실행하기위해서 두 키를 선택했습니다.</p>
<p style="TEXT-ALIGN: left; FLOAT: none; CLEAR: none"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile22.uf.227FBC3952E7633524A9CF.png" class="aligncenter" width="435" height="232" filename="20140128_165432_003.png" filemime="image/png" /></p>
<p><br /></p>
<p><br /></p>
<p>- Ctrl 키를&nbsp;누르고 있는 상태(down)에서 C 키를 누른 후(down/up) Ctrl 키를 놓아야 하므로, LCtrl의&nbsp;down과 up을 분리 합니다.</p>
<p>- 아래 그림처럼 LCtrl을 선택하고 "split"를 클릭하면</p>
<p>- 또는, LCtrl을 shift + 마우스 클릭하면</p>
<p style="TEXT-ALIGN: left; FLOAT: none; CLEAR: none"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile28.uf.21302A3952E763360D4F37.png" class="aligncenter" width="411" height="194" filename="20140128_165449_004.png" filemime="image/png" /></p>
<p><br /></p>
<p><br /></p>
<p>- 아래와 같이 down/up이 분리 됩니다.</p>
<p style="TEXT-ALIGN: left; FLOAT: none; CLEAR: none"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile29.uf.265F8F3952E76336386504.png" class="aligncenter" width="405" height="195" filename="20140128_165501_005.png" filemime="image/png" /></p>
<p><br /></p>
<p><br /></p>
<p>- 분리된 up을 C의 밑으로 마우스&nbsp;드래그해서 이동 시켜 줍니다.&nbsp;</p>
<p style="TEXT-ALIGN: left; FLOAT: none; CLEAR: none"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile29.uf.242FE93952E763360CCCD4.png" class="aligncenter" width="428" height="190" filename="20140128_165527_006.png" filemime="image/png" /></p>
<p><br /></p>
<p><br /></p>
<p>- 이동이 완료되면 보이는 것처럼 Ctrl을 누른 상태에서 C가 입력되고 Ctrl을 놓게 됩니다.</p>
<p style="TEXT-ALIGN: left; FLOAT: none; CLEAR: none"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile28.uf.220EA43952E763361E6F39.png" class="aligncenter" width="425" height="186" filename="20140128_165557_007.png" filemime="image/png" /></p>
<p><br /></p>
<p><br /></p>
<p>- 모든 키를 "split" 할 수 있습니다.</p><p><br /></p><p><br /></p><p><br /></p><p>5. 매크로 작동 간 딜레이를 적용할 수 있습니다.</p><p><br /></p><p>- 원하는 키를 선택하고 "apply delay" 옆의 딜레이 시간을 입력합니다.</p><p>: 최대 5초간 지연 시킬 수 있으며, 최소 간격은 0.1초입니다.</p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile25.uf.261CBC4A52FDC1F4025906.png" class="aligncenter" width="581" height="222" filename="20140214_161045_002.png" filemime="image/png" /></p><p><br /></p><p><br /></p><p>- "apply delay"를 클릭하면 딜레이가 적용 됩니다.</p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile5.uf.2162404A52FDC1F41DCBFE.png" class="aligncenter" width="583" height="214" filename="20140214_161112_003.png" filemime="image/png" /></p><p><br /></p>
<p><br /></p><p><br /></p><p>6. macro in macro</p><p>: 매크로 작동 중 다른 매크로를 실행 할 수 있습니다.</p><p>: 같은 매크로를 실행하면 무한 루프로 작동합니다.</p><p>: 무한 루프 시 다시 매크로 키를 눌러 중지 시킵니다.</p><p>: 다른 매크로를 실행하면 현 매크로의 이후 내용은 무시합니다.</p>
<p>&nbsp;<img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile24.uf.2769BB3B55C4C9213255F6.png" class="aligncenter" width="442" height="249" filename="20150808_000357_002.png" filemime="image/png" style="font-size: 9pt; line-height: 1.5;" /></p><p><br /></p><p><br /></p><p><br /></p><p>7. text to macro</p><p>입력 된 텍스트를 매크로로 변환 합니다.</p><p><br /></p><p>- "String Parsing" 박스 안에 매크로로 변환 할 텍스트를 입력합니다.</p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile5.uf.270E1D4A542EDAF521C539.png" class="aligncenter" width="637" height="170" filename="20141004_021911_002.png" filemime="image/png" /></p><p><br /></p><p>- 입력 후 "parse stirng &gt;&gt;" 버튼을 클릭하면 매크로로 변환되어 표시됩니다.</p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile6.uf.24217E4A542EDAF60A785C.png" class="aligncenter" width="636" height="229" filename="20141004_021923_003.png" filemime="image/png" /></p><p><br /></p><p>- 매크로로 변환 할 수 있는 텍스트는 아래와 같습니다.</p><p>일반 텍스트 : `1234567890-=qwertyuiop[]\asdfghjkl;'zxcvbnm,./</p><p>shift + 텍스트 : ~!@#$%^&amp;*()_+QWERTYUIOP{}|ASDFGHJKL:"ZXCVBNM&lt;&gt;?</p><p><br /></p><p><br /></p><p><br /></p><p>* ps2avrU 펌웨어 사용 기판 (A.87U 등 "U" 이름 뒤에 붙은 기판 등)은 부트로더를 이용해 저장한 .hex파일을 업로드 해줍니다.</p>
<p>- 부트로더 사용법 : http://blog.winkeyless.kr/18</p><p><br /></p><p>* ps2avrGB 펌웨어 사용 기판(B.87 등 이름이&nbsp;"B"로 시작하는 기판)은 BootMapper Client를 이용할 경우 "Upload" 버튼을 클릭하면 자동으로 업로드 됩니다.</p><p>- BootMapper Client 사용법 :&nbsp;http://blog.winkeyless.kr/154</p>
<p><br />&nbsp;</p>
<p><br /></p>
<p><br /></p>