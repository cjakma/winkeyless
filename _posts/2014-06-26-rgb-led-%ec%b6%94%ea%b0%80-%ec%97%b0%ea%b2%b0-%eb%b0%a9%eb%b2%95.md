---
ID: 543
post_title: RGB LED 추가 연결 방법
author: showjean
post_date: 2014-06-26 16:15:09
post_excerpt: ""
layout: post
permalink: http://winkeyless.com/blog/543
published: true
---
<p><b><span style="font-size: 12pt;">** RGB bar를 이용해서 LED를 추가하기를 권장합니다.</span></b></p><p><b><span style="font-size: 12pt;">-&nbsp;http://blog.winkeyless.kr/169</span></b></p><p><br /></p><p>B 시리즈 기판에 사용되는 RGB LED는 사용자가 추가로 와이어링 하여 연결할 경우 다음과 같은 방식으로 작업해야 합니다.</p><p><br /></p><p><br /></p><p>1. VCC(빨간 선) 와 &nbsp;GND(파란 선)은 병렬로 연결해주면 됩니다.</p><p>- 사진은 B.87 기판입니다. 다른 기판들도 RGB LED의 끝 부분에 VCC/GND/DO 를 연결할 수 있는 홀들이 있습니다.</p><p><br /></p><p>2. DO를 DI에 연결해줘야 합니다.</p><p>- 아래 그림과 같이 노란선으로 된 데이터 라인은 LED 끼리 직렬 연결이 되어야 합니다.</p><p>- 마지막 LED의 DO는 그냥 연결되지 않은 채로 둡니다.</p><p><br /></p><p>3. 각 LED에는 0.1uF의 capasitor를 병렬로 연결해줍니다.</p><p><br /></p><p>4. bootMapper Client에서 LED의 수를 맞게 다시 설정해 줍니다.</p><p>- 펌웨어 상에서는 최대 24개 까지만 인식을 합니다. 그렇기 때문에, 총 24개 이상의 LED를 연결하더라도&nbsp;24개뿐이 켜지지 않습니다.</p><p>- RGB LED의 수가 많아 질수록 밝기는 어두워질 수 있습니다. 보통, 단일 컬러의 밝기는 거의&nbsp;차이가 없지만 조합 컬러(2개 이상의 컬러를 이용해서 만들어내는 컬러, 대표적으로 흰색)의 밝기는 추가할수록 덜 밝습니다.</p><p><br /></p><p><br /></p><p style="text-align: left; clear: none; float: none;"></p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile29.uf.257BB64D53AC45D734615C.jpg" class="aligncenter" width="860" height="460" filename="DSC_0381_e.jpg" filemime="image/jpeg" /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p style="text-align: left; clear: none; float: none;"><br /></p><p><br /></p>