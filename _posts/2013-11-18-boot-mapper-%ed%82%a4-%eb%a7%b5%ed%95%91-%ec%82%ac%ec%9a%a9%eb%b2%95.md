---
ID: 307
post_title: Boot Mapper 키 맵핑 사용법
author: showjean
post_date: 2013-11-18 18:40:14
post_excerpt: ""
layout: post
permalink: http://winkeyless.com/blog/307
published: true
---
<p><b>* 아직 키 맵핑을 하지 않은 상태에서의 사용 법</b></p><p><br /></p>
<p>1. 최신&nbsp;부트 매퍼 펌웨어로 펌업 합니다.</p>
<p>- 이미 부트 매퍼 펌웨어를 사용 중이라면 다시 펌업을 할 필요는 없습니다. 2번으로 이동</p>
<p>- U.CON의 FW_JP를 쇼트 시킨 상태에서 USB포트에 플러깅 합니다.</p>
<p>- col1과 row2(FW_JP)를 쇼트 시키고 플러깅하면 부트로더로 작동합니다.&nbsp;</p>
<p>(스위치를 연결한 상태라면 col1, row2에 해당하는 키를 누른 상태로 플러깅해도 됩니다.)</p>
<p><br /></p>
<p>펌웨어 링크 : http://blog.winkeyless.kr/17</p>
<p>펌업 방법 : http://blog.winkeyless.kr/18</p>
<p><br /></p><p><b>1-1. A.87U 등의 기판은 2~7번 과정을 거치지 않고, 이미 펌웨어 압축 파일에 포함된 키맵 데이터(keymap_......hex)를 이용해서 8번 부터 진행해도 됩니다.</b></p>
<p><br /></p>
<p>2. 아래&nbsp;링크의 부트 매퍼 사이트에 접속합니다.</p>
<p>http://winkeyless.kr/bootMapper</p>
<p><br /></p>
<p><br /></p>
<p>3. 펌업한 U.CON을&nbsp;언플러깅 한 후 KEY_JP 점퍼(그림 상 빨간 표시 한 부분)을 쇼트 시킨 상태에서 플러깅 합니다.</p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile4.uf.2176454A528A69C3180513.jpg" class="aligncenter" width="800" height="536" filename="DSC_9615.jpg" filemime="image/jpeg" /></p>
<p>- col2와 row2(KEY_JP)를 쇼트 시키고 플러깅 하면 부트 매퍼로 작동됩니다.</p>
<p>- 1번과 마찬가지로 KEY_JP와 연결되어 있는 매트릭스상 col2, row2 위치의 키를 누른 상태로 플러깅해도 부트 매퍼 상태가 됩니다.</p>
<p>- ps2avrU 시리즈의 키보드는 "tab"키가 위 점퍼 역활을 하게 됩니다.</p>
<p>- caps lock LED가 약 1초 간격으로 점멸 됩니다.</p>
<p>- 이때는 키보드로 작동되지 않고, 키를 누르면 해당 키의 매트릭스 위치를 출력합니다.&nbsp;</p>
<p>ex&gt; -4,15=</p>
<p><br /></p>
<p><br /></p>
<p>4. 키를 누르면 매트릭스에 해당 키의 위치가 표시됩니다.</p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile4.uf.23130436529B692D0E50CF.png" class="aligncenter" width="611" height="502" filename="20131202_015109_001.png" filemime="image/png" /></p>
<p style="text-align: left; clear: none; float: none;"><br /></p>
<p>- 매트릭스 그리드에 파란색으로 표시되고 버튼 옆에 글자로 layer와 col, row가 표시됩니다.<br /></p>
<p>- 마우스 클릭으로 매트릭스를 선택할 수 있습니다.</p>
<p><br /></p>
<p><br /></p>
<p>5. 아래쪽 키들 중 누른 키보드 키에 매핑 할 키 값을&nbsp;선택합니다. 그럼, 매트릭스 그리드에 선택한 키 값이 표시됩니다.&nbsp;</p>
<p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile22.uf.27131736529B692E3395AC.png" class="aligncenter" width="614" height="382" filename="20131202_015133_002.png" filemime="image/png" /></p>
<p><br /></p>
<p>- 해당 키에 "A" 키 값을 매핑한 것이 표시됩니다.</p>
<p><br /></p>
<p><br /></p>
<p>6. 4-5를 반복하여 원하는 키들에 매핑을 합니다.</p>
<p>- 기본적으로 키를 선택하면 모든 레이어에 적용이 됩니다.&nbsp;</p>
<p>- 특정 레이어만 키를 변경하고 싶다면 "apply to all layers" 항목의 체크를 해제하고 상단의 레이어 탭을 눌러 원하는 레이어만 변경하면 됩니다.</p>
<p><br /></p>
<p><br /></p>
<p>7. "save keymap_part.hex"를 누르면 keymap_part_YYYYMMDDHHmmSS.hex 파일로 저장됩니다.</p>
<p>- U.CON에서는 매트릭스 정보를 가져올 수 없으므로, 자신이 수정한 키맵 데이터&nbsp;파일을 보관하는 것이 좋습니다.</p>
<p>- 위 .hex파일은 키맵 데이터만 있는 키맵 파일입니다.</p>
<p><br /></p>
<p><br /></p>
<p>8. 저장한 키맵 데이터를 키보드에 업데이트(부트로더 이용) 해주면 설정한 매핑이 적용됩니다.</p>
<p>-&nbsp;부트로더를 이용한 펌웨어&amp;키맵 업로드 방법 : http://blog.winkeyless.kr/18</p>
<p><br /></p>
<p><br /></p>
<p>9. "load keymap_part.hex or .json"버튼을 이용해서 키맵&nbsp;정보를 불러 올 수 있습니다.</p>
<p>- 이전에 save 해둔 키맵 데이터(keymap_part_YYYYMMDDHHmmSS.hex 또는 .json)를 다시 불러 올 수 있습니다.</p>
<p><br /></p>
<p><br /></p>
<p>10. "save .json" 버튼을 이용해서 json 형식의 키맵 데이터를 저장할 수 있습니다.</p>
<p><br /></p>
<p><br /></p>
<p><br /></p><p><b>* 이미 키 맵핑을 한 후 일부만 수정할 경우</b></p>
<p><br /></p>
<p><br /></p><p>1. 기본 키맵 파일이나 이전에 저장해둔 키맵.hex 파일을&nbsp;"load keymap_part.hex or .json"버튼을 이용해 load 합니다.</p><p><br /></p><p>2. 키보드의 부트매퍼를 작동 시킵니다.</p><p>- 위 3번 항목 참고</p><p><br /></p><p>3. 변경을 원하는 키를 누르면 매트릭스에 빨간 색으로 표시됩니다.</p><p><br /></p><p>3-1. 키보드를 부트매퍼로 작동 시키지 않고 마우스로 매트릭스를 클릭하여 선택해도 됩니다.</p><p><br /></p><p>4. 아래쪽 키들 중 원하는 키를 마우스로 클릭하면 매트릭스의 키코드 값이 변경됩니다.</p><p><br /></p><p>5.&nbsp;"save keymap_part.hex"를 눌러 .hex 파일로 저장합니다.</p><p><br /></p><p>6.&nbsp;<span style="background-color: transparent;">저장한 키맵 데이터를 키보드에 업데이트(부트로더 이용) 해주면 설정한 매핑이 적용됩니다.</span></p><p>- 부트로더를 이용한 펌웨어&amp;키맵 업로드 방법 : http://blog.winkeyless.kr/18</p><p><br /></p><p><br /></p><p><br /></p>
<p><br /></p>