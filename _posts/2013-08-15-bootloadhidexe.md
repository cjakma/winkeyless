---
ID: 112
post_title: bootloadHID.exe
author: showjean
post_date: 2013-08-15 12:56:00
post_excerpt: ""
layout: post
permalink: http://winkeyless.com/blog/112
published: true
---
<p><br /></p><p style="text-align: left;"><a href="http://winkeyless.com/blog/wp-content/uploads/1/cfile29.uf.21668F39520CCE84129FF1.zip" class="aligncenter" filename="bootloadHID.zip" filemime="application/zip" />cfile29.uf.21668F39520CCE84129FF1.zip</a></p><p><br /></p><p><br /></p><p>HIDBootFlash.exe 파일이 실행되지 않는 경우 이를 대신해 첨부파일을 다운받아 압축 해제한 후 커맨드 창을 통하여&nbsp;펌웨어를&nbsp;업로드&nbsp;할 수 있습니다.</p><p><br /></p><p>우선, 키보드를 부트로더로 작동시켜 USB로 연결합니다.</p><p><br /></p><p>커맨드 창을 연후&nbsp;압축을 해제한 디렉토리로 이동합니다. (dir, cd 등의 명령어로 이동하거나, 탐색기에서 해당 폴더에 shift 키를 누른 상태로 마우스 오른쪽 버튼을 클릭하여&nbsp;"여기서 명령창 열기" 이라는 메뉴를 선택)</p><p><br /></p><p>커맨드 창에 다음과 같이 입력합니다.</p><p><br /></p><p>bootloadHID.exe keymain.hex</p><p><br /></p><p>여기서 keymain.hex는 자신이 원하는 .hex파일로 입력하시면 됩니다.</p><p><br /></p><p>그럼, 아래 그림과 같은 화면으로 진행이 됩니다. (각 수치는 다를 수 있습니다.)</p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile27.uf.270AEA35520CCF70043849.jpg" class="aligncenter" width="668" height="225" filename="20130815_215343_002.jpg" filemime="image/jpeg" /></p><p><br /></p>