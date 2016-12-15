---
layout: post
title: ThumbU 기판 관련 자료
published: true
author: showjean
comments: true
date: 2013-10-25 06:10:34
tags: [ ]
categories:
    - '%ec%9e%90%eb%a3%8c%ec%8b%a4%ea%b8%b0%ed%8c%90'
permalink: '/thumbu-%ea%b8%b0%ed%8c%90-%ea%b4%80%eb%a0%a8-%ec%9e%90%eb%a3%8c'
image:
    feature: cfile3.uf.216CCE47526A08001D12FD.jpg
---

  
    * 파일 설명
  
  
  
  
  
  
  
  
  
    
      cfile24.uf.23609937536F5E2A2DCD29.dwg&nbsp;: 2014.05.11 등록
    
  
  
  
  
  
  
    
      새로운 스타일의 아크릴 하우징입니다. 보강판이 2/3T로 나뉘어져 있으며, ANSI/ISO/All Layout으로 보강판을 선택할 수 있도록 그려뒀습니다. 하우징 제작시에는 3가지 중 하나만 선택해서 제작하시면됩니다.&nbsp;볼트 체결을 위한 2파이 탭핑이 필요합니다. M2*10mm 볼트 14개가 필요합니다.&nbsp;
    
    
    
      
               
    
    
      
    
    
    
    
    
    
      * 레이아웃
    
    
    
    
    
    
      
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
      * 소자 목록
    
    
    
    
    
    
      12종 19개
    
    
    
      ATMEGA32A-AU
    
    
    
      micro USB (MOLEX 47589-0001)
    
    
    
      Chip Tantal A size 10uF 16V
    
    
    
      MMBT2222A (SOT-23) * 3
    
    
    
      ZENER DIODE, 350mW, 3.6V, SOT-23 (BZX84C3V6) * 2
    
    
    
      CRYSTAL 12MHz (SMD 3X5 size)
    
    
    
      2012 Chip Resistor, 330Ω(331) * 2
    
    
    
      2012 Chip Resistor, 1.5kΩ(152) * 2
    
    
    
      2012 Chip Resistor, 68Ω(680) * 2
    
    
    
      2012 Chip Resistor, 10kΩ(103)
    
    
    
      2012 size Chip Monolithic Ceramic Capacitor 18pF * 2
    
    
    
      2012 size Chip Monolithic Ceramic Capacitor 0.1uF
    
    
    
    
    
    
    
    
    
      
      
      
      
        * LED 컬러별 저항 값 &#8211; PS/2 200mA 기준 (출처 : 코렐라스님 자료)
      
      
      
        하얀색/보라색(최소전압 약 3V) : 820
      
      
      
        빨간색/노란색(최소전압 약 1.8V) : 1.3K
      
      
      
        파란색/초록색(최소전압 약 2.8V) : 900
      
    
    
    
    
    
    
      &#8211; 저항 사이즈 : 2012
    
    
    
    
    
    
      &#8211; 위 값은 보통의 사용하는 LED를 기준으로 작성되었습니다.
    
    
    
      LED의 정확한 저항 값은 해당 데이터시트를 참고하여 계산해야 합니다.
    
    
    
    
    
    
    
    
    
      * 스위치 입력에 필요한 다이오드는 1N4148(DIP or SMD) 입니다.
    
    
    
    
    
    
    
    
    
      * ps2avrU bootloader 사용
    
    
    
      &#8211; 기본적으로 부트로더만 설치되어 있으므로, 이를 이용해 펌웨어를 업로드해야 합니다.
    
    
    
    
    
    
      &#8211; 부트로더가 설치되었는지 확인하는 방법 : http://blog.winkeyless.kr/14
    
    
    
    
    
    
      &#8211; 만약 MCU를 교체하여 부트로더가 설치되어 있지 않다면 설치해야 합니다.&nbsp;
    
    
    
      &#8211; 부트로더 설치 방법 :&nbsp;http://blog.winkeyless.kr/15
    
    
    
    
    
    
      &#8211; 부트로더를 이용한 펌웨어 업로드 방법 : http://blog.winkeyless.kr/18
    
    
    
    
    
    
    
    
    
      * 기본 key matrix
    
    
    
      https://docs.google.com/spreadsheet/ccc?key=0Ah1Lcjc-gPfndFM1emlhcExfU3JYRUY4SUNqR1ZIUmc&usp=sharing
    
    
    
    
    
    
    
    
    
    
    
    
      *기판 사양
    
    
    
      &#8211; 레이아웃 : 윈키/윈키리스/HHKB-MX 콤보,&nbsp;
    
    
    
      캡스락 3000/8000(마제식) 지원
    
    
    
      R Shift 2.75/1.75 지원
    
    
    
      back space 2 / 1 지원
    
    
    
      ISO Enter/L shift 지원
    
    
    
      &#8211; Full LED 지원 : 5가지 LED 모드
    
    
    
      &#8211; PCB : 1.0T (녹색)
    
    
    
      &#8211; 모든 소자 뒷면에 배치
    
    
    
      &#8211; 하우징(보강판)리스를 위한 마운트 홀 추가
    
    
    
      ** thumb V0.1에 이용되던 마운트 홀은 이번 버젼까지만 이용되고 차기버젼부터는 제거될 예정입니다. (layout 도면 참고)
    
    
    
    
    
    
    
    
    
      *ps2avrU(펌웨어) 사양&nbsp;
    
    
    
      &#8211; 인터페이스 : USB / PS/2 콤보 (자동 인식)
    
    
    
      &#8211; 하드웨어 키매핑 지원 : 별도의 SW없이 즉시 키매핑 변경 가능
    
    
    
      &#8211; Full LED 지원 : 5가지 LED 모드
    
    
    
      &#8211; 하드웨어 매크로 지원
    
    
    
    
    
    
    
    
    
      펌웨어에대한 더 많은 정보는 아래 링크를 참고하세요.
    
    
    
      http://blog.winkeyless.kr/19
    
    
    
    
    
    
    
    
    
    
    
    
      * 레이어&nbsp;
    
    
    
      1. 기본 레이어
    
    
    
      
        
      
      
      
      
      
      
         
        
        
        
        
        
        
        
        
        
        
        
        
        
        
          2. FN 레이어
        
        
        
          
            
          
          
          
          
          
          
             
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
              3. FN2 레이어 &#8211; FN + space를 눌러 전환하고 유지됩니다.&nbsp;
            
            
            
              다시 기본레이어로 돌아가려면 FN + space를 다시 누르거나 Esc + Backspace를 누르면됩니다.
            
            
            
              (포커의 크루즈 커서 기능과 유사하게 이용할 수 있습니다.)
            
            
            
              
                
              
              
              
              
              
              
                 
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                 
                
                
                