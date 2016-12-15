---
ID: 576
post_title: >
  MX-mini ps2avr V0.2 기판에 ps2avr-ext
  이식하는 방법
author: showjean
post_date: 2014-09-10 14:41:42
post_excerpt: ""
layout: post
permalink: http://winkeyless.com/blog/576
published: true
---
<p>요청하신 분이 계셔서 작성해봅니다.</p><p><br /></p><p><br /></p><p>아래 사진의 각 확대 화면에 그려진대로 와이어를 납땜해주면 됩니다.</p><p><br /></p><p>다만, 2가지 주의 할 점이 있는데요,</p><p><br /></p><p>첫 번째는 2번 부분처럼 ps2avr-ext를 기판에 겹체 놓을 때 두 기판 간에 쇼트가 나지 않도록 사이에 절연을 잘 해줘야 한다는 것 입니다. 그렇지 않으면 최악의 경우 회로 사망에 이를 수 있으니 반드시 주의하셔야 합니다.</p><p><br /></p><p>두 번째는 3번 부분의 빨간 표시 부분인데요, 기판을 잘 보면 녹색 선과 같은 동박 패턴이 있습니다. 이 두 선을 빨간 표시처럼 커팅해서 통전을 막아야 합니다. 그리고, 와이어링을 MCU의 핀에&nbsp;해줘야 하므로 정밀하게 잘 해줘야 합니다. 옆의 다리들과 쇼트가 나지 않도록 주의하세요.</p><p><br /></p><p>그럼 참고가 되시길 ^^</p><p><br /></p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile8.uf.256A0445541061090EA416.jpg" class="aligncenter" width="800" height="536" filename="DSC_0809_e.jpg" filemime="image/jpeg" /></p><p><br /></p><p><br /></p><p><br /></p><p>&lt; 작업 예 &gt;&nbsp;</p><p>&nbsp;ISP 로더를 사용할 수 있도록 VCC와 GND는 다른 곳에 와이어링을 해줬습니다.</p><p>(사진의 하단에 표시 안 된&nbsp;와이어는 스크롤 락 LED를 별도로 표시하기 위해서 와이어링 한 것 입니다.)</p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile8.uf.2203673C543B83622CF994.jpg" class="aligncenter" width="860" height="457" filename="DSC_0906.jpg" filemime="image/jpeg" style="""" /></p><p><br /></p><p style="text-align: left; clear: none; float: none;"><img src="http://winkeyless.com/blog/wp-content/uploads/1/cfile8.uf.2412553C543B836313199E.jpg" class="aligncenter" width="860" height="1066" filename="DSC_0907.jpg" filemime="image/jpeg" style="""" /></p><p><br /></p><p><br /></p><p><br /></p><p><br /></p><p><br /></p><p><br /></p>