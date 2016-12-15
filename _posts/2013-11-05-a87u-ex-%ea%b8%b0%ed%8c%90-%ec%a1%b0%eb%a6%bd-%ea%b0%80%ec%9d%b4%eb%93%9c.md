---
ID: 275
post_title: A.87U EX 기판 조립 가이드
author: showjean
post_date: 2013-11-05 15:28:15
post_excerpt: ""
layout: post
permalink: http://winkeyless.com/blog/275
published: true
---
<p><b><span style="font-size: 18pt;">V0.2 조립 가이드</span></b></p><p><br /></p><p>- 기판은 미조립 상태로 배송됩니다. 본 포스트의 사진은 참고를 위해 조립(납땜) 후 촬영한 것입니다.</p><p>- MCU에는 부트로더만 설치되어 있으므로 납땜을 완료 한 후 반드시 펌웨어를 업로드 해줘야 합니다.</p><p><br /></p><p><br /></p><p>이 큰 사진으로 설명하고 나머지 사진들은 참고용으로 남기겠습니다.</p><p>(사진을 클릭하면 커집니다.)</p><p style="text-align: center; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile22.uf.25611F3A52921D21329D12.jpg" class="aligncenter" width="860" height="575" filename="DSC_9636.jpg" filemime="image/jpeg" /></p><p><span style="background-color: transparent; font-size: 9pt; line-height: 1.5;">- 캐패시터(C)중 탄탈 캐패시터(C1, 사진상은 노란색이지만, 검정색일 수도 있습니다.)은 방향성이 있으므로 반드시 사진과 같은 방향으로 납땜 해 줍니다. 나머지들(C2~4)은 &nbsp;사진과 같은 위치에 납땜 해줍니다.</span></p><p>- 크리스탈(Y)은 사진과 같이 숫자(12.000)가 보이도록 납땜 해주면됩니다. 접점 4곳 중 1곳에 표시가 되어 있지만, 사실 돌아가도 문제는 없습니다.</p><p>- 제너다이오드(ZD1~2)는 방향성이 있으므로 반드시 사진과 같은 방향으로 납땜해야 합니다.</p><p>- 트랜지스터 (N1~3)는 사진과 같은 방향으로 납땜 해줍니다.</p><p>- MCU(IC1)도 방향성이 있으므로 반드시 사진과 같은 방향으로 납땜을 해야합니다.</p><p>- 저항(R)들은 사진과 같은 위치에 납땜 해주면 됩니다.&nbsp;</p><p><br /></p><p>- V0.2 버젼은 V0.1과는 달리 와이어링없이&nbsp;저항 중 R3은 위치에 따라서 Num Lock LED의 위치가 바뀌게 됩니다. 방법은 아래의 설명을 참고하세요.</p><p><br /></p><p>1. 보통의 풀배열 기판 처럼 텐키의 Num Lock 키의 LED를 사용할 경우 : 아래 사진 처럼 R3 저항의 아래쪽(NumLock)라고 써있는 부분에 저항을 납땜하고, NumLock키의 저항 위치(사진상 X표시 한 곳)에는 저항을 납땜하지않고 비워둡니다. 그리고 Pause 키의 저항 위치(사진상 ㅁ표시)에 풀LED를 위한 저항을 땜해 줍니다.</p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile2.uf.246D6F3A52921D222C1CF1.jpg" class="aligncenter" width="536" height="800" filename="DSC_9639_nl.jpg" filemime="image/jpeg" /></p><p><br /></p><p><br /></p><p><br /></p><p>2.&nbsp;A.87 기판 처럼 Pause 키의 LED를 사용할 경우 : 아래 사진 처럼 R3 저항의 위쪽(Pause)라고 써있는 부분에 저항을 납땜하고, Pause키의 저항 위치(사진상 X표시 한 곳)에는 저항을 납땜하지않고 비워둡니다. 그리고 NumLock&nbsp;키의 저항 위치(사진상 ㅁ표시)에 풀LED를 위한 저항을 땜해 줍니다.</p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile1.uf.23292D4752921FFE117E99.jpg" class="aligncenter" width="536" height="800" filename="DSC_9639_pause.jpg" filemime="image/jpeg" /></p><p><br /></p><p><br /></p><p><br /></p><p>이 외의 사항들은 아래 V0.1 조립가이드를 참고해주세요.</p><p><br /></p><p><br /></p><p><br /></p><p>- 기타 참고 사진들</p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile10.uf.231B143A52921D261A5F2F.jpg" class="aligncenter" width="860" height="575" filename="DSC_9640.jpg" filemime="image/jpeg" /></p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile5.uf.2646B13A52921D270809B3.jpg" class="aligncenter" width="800" height="536" filename="DSC_9644.jpg" filemime="image/jpeg" /></p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile23.uf.221EA43A52921D28197B3D.jpg" class="aligncenter" width="800" height="535" filename="DSC_9645.jpg" filemime="image/jpeg" /></p><p><br /></p><p><br /></p><p><br /></p><p><br /></p><p><br /></p><p><span style="font-size: 18pt;"><b>V0.1 조립 가이드</b></span></p><p><br /></p><p>A.87U EX는 A.87U에 텐키만 붙인 기판이므로 기본적인 방법은&nbsp;A.87U의 조립 가이드를 참고하시면 되겠습니다.</p>
<p><br /></p>
<p>-&nbsp;A.87U 조립 가이드 :&nbsp;http://blog.winkeyless.kr/40</p>
<p><br /></p>
<p><br /></p>
<p>다만, 다음 사항들은&nbsp;조립전 우선 확인을 해주시길 바랍니다.</p>
<p><br /></p>
<p>1. 키의 수가 많아졌으므로&nbsp;Full LED를 PS/2에 연결하여&nbsp;사용할 경우 텐키리스의 경우보다 저항값을 높혀주는 것이 안전&nbsp;할 것으로 생각합니다.&nbsp;</p>
<p><br /></p>
<p>하얀색/보라색 : 820 -&gt;약1K</p>
<p>빨간색/노란색 : 1.3K -&gt; 약1.6K</p>
<p>파란색/초록색 : 900 -&gt; 약1.1K</p>
<p><br /></p>
<p>위 값은 일반적으로&nbsp;사용하는 LED를 기준으로 계산되었으므로 정확한 저항 값은 LED의 데이터시트를 참고하여 계산해야 합니다.</p>
<p><br /></p>
<p><span style="background-color: transparent; font-size: 9pt; line-height: 1.5;"><br /></span></p>
<p><br /></p>
<p>2. 넘락 LED는 A.87U와 마찬가지로 pause키에 위치합니다. 보통의 풀 배열 키보드는 텐키의 num lock 키에 LED가 있으므로 이와 같길 원한다면 다음과 같이 간단한 와이어링으로 변경 가능합니다.</p>
<p><br /></p>
<p>- 아래 그림처럼 R3 저항(빨간 박스 친 부분)을 시계방향으로 45도 회전 시켜 납땜을 한 뒤 텐키 num lock키의 LED + 부분(빨간 원 부분)과 와이어링 해주면 됩니다.</p>
<p>- 그리고 기존의 pause키의 LED는 Full LED로 이용하기 위해서 그림의 빨간 선 처럼 와이어링 해주세요.</p>
<p><br /></p>
<p style="text-align: center; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile25.uf.245DAB4E5279081D1763FF.jpg" class="aligncenter" width="800" height="743" filename="DSC_9592.jpg" filemime="image/jpeg" /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p>3. 텐키를 왼쪽에 놓고자 한다면 분리한 후 아래 그림 처럼 왼쪽에 붙이고 바로 가까운 홀들끼리 직선으로 와이어링을 해주면 됩니다.</p>
<p><br /></p>
<p><br /></p>
<p style="text-align: center; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile8.uf.23633D4452790B0D0F5B30.jpg" class="aligncenter" width="800" height="537" filename="DSC_9591.jpg" filemime="image/jpeg" /></p>
<p><br /></p>
<p><br /></p>
<p>그리고, 텐키를 잘라내면 연결하지 않는다면&nbsp;나머지 부분이 순전히 텐키리스 기판으로 작동하게 됩니다.&nbsp;<br /></p>
<p><br /></p>
<p><br /></p>
<p><br /></p>
<p style="text-align: center; clear: none; float: none;"></p>
<p><br /></p>