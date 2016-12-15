---
layout: post
title: Bootmapper Client 사용 법
published: true
author: showjean
comments: true
date: 2014-06-22 07:06:08
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: '/bootmapper-client-%ec%82%ac%ec%9a%a9-%eb%b2%95'
image:
    feature: cfile2.uf.26294E435635D1C82EB16F.png
---
* Bootmapper&nbsp;Client는 ps2avrGB 펌웨어가 사용된 B 시리즈 기판에서 모든 기능을 사용할 수 있습니다.

* USB 인터페이스로 연결 된 상태에서만 작동이 됩니다.





Bootmapper&nbsp;Client 다운로드 :&nbsp;http://blog.winkeyless.kr/155





&#8211; BootmapperClient 를 실행합니다.







*** 펌웨어 업로드 방법**



**&#8211; 처음 납땜 후 키보드에는 부트로더만 설치되어 있으므로 반드시 펌웨어 업로드를 해줘야 다른 모든 기능이 작동 됩니다.**



&#8220;Options&#8221; 탭으로 이동하여 &#8220;firm up(select .hex file)&#8221; 버튼을 클릭해 업로드할 펌웨어 파일을 선택해 줍니다.



ps2avrGB 펌웨어 :&nbsp;http://blog.winkeyless.kr/153






  





  





  




&#8211; 자동으로 부트로더로 진입하고 펌웨어를 업데이트 한 후 다시 키보드가 작동합니다.






&#8211; 처음 납땜 한 후 펌웨어가 없는 상태라면 케이블 연결 시 자동으로 부트로더가 작동됩니다.&nbsp;

(부트로더가 작동되면 3 lock LED와 FUll LED가 계속 깜박입니다.)



&#8211; 부트로더가 작동되면 아래 그림과 같이 &#8220;HIDBoot&#8221;라는 장치가 확인됩니다.


  






&#8211; 만약, 자동으로 부트로더가 작동되지 않는다면 (초기 일부 B.87 및 B.87 EX만 해당, 또는 펌웨어 오류로 작동되지 않을 경우)&nbsp;우선 부트로더를 수동으로 작동 시켜줘야 합니다. 기판의 &#8220;좌 ctrl&#8221;키를 누르거나 &#8220;JP1(BOOTLOADER)&#8221;를 쇼트 시킨 후 USB 케이블을 연결하면 부트로더가 작동 됩니다.

&#8211; B.pad의 부트로더 수동 작동 키는 &#8220;0&#8221;키 입니다.




  




&#8211; BOOTLOADER(JP1)과&nbsp;BOOTMAPPER(JP2)를 혼동하지 말아주세요~&nbsp;

&#8211; **BOOTMAPPER(JP2) 점퍼는 사용할 일이 없습니다.**







*** RGB LED 설정**



&#8220;Options&#8221; 탭으로 이동하여 &#8220;connect&#8221; 버튼을 클릭합니다.



&#8211; 초기 설정 컬러 값이&nbsp;모두 흰색입니다.




  















  
  
  
  
    &#8211; 원활한 데이터 통신을 위해&nbsp;키보드의 스위치 LED(Full LED)가 off 됩니다.
  
  
  
    &#8211; &#8220;disconnect&#8221; : 설정을 종료하고 스위치 LED는&nbsp;on 됩니다.
  
  
  
  
  
  
  
  
  
  
  
  
    설정을 변경하면 약 2초 후 키보드에 자동으로 저장되며 caps lock / num lock LED가 깜박입니다.
  
  
  
  
  
  
    * RGB LED Settings
  
  
  
    &#8211; Num of LEDs : 기판에 맞는 RGB LED의 수를 설정해 줍니다.&nbsp;
  
  
  
  
  
  
    &#8211; LED mode selection and color setting : LED mode를 선택하고 해당 컬러를 세팅합니다. 표시된 컬러 이외의 컬러는 헥사코드로 입력 할 수 있습니다. (ex, FF3300)
  
  
  
    : 모드 변경 단축키는 ESC + Shift + Caps lock 입니다.
  
  
  
    
      : 1. rainbow 는 컬러를 변경 후 &#8216;update color&#8217;를 클릭해서 키보드에 저장합니다.&nbsp;
    
    
    
      
        : 1. rainbow -> type 설명
      
      
      
        fading : 모든 LED가 동일한 컬러로 자연스럽게 변환
      
      
      
        
          immediately : 모든 LED가 동일한 컬러로 갑작스럽게 변경
        
        
        
          
            sequential : 각 LED가 순차적으로 동일한 컬러로 변경
          
          
          
            
              static : 각 LED가 각각의 컬러로 지정(변환 없음)
            
            
            
              
                flow : 각 LED의 컬러가 흘러가듯 변환
              
              
              
              
              
              
                &#8211; Brightness : 슬라이더를 이동해 RGB LED의 밝기를 조절합니다.
              
              
              
                : 최대 밝기는 펌웨어에 의해서 제한됩니다.
              
              
              
                
                  : RGB LED가 밝을 수록 스위치 LED의 밝기는 어두워 집니다.
                
                
                
                
                
                
                  &#8211; Transition Speed : RGB LED의 컬러 변환 속도를 설정합니다.
                
                
                
                  : 낮을 수록 빠른 변환이 이루어집니다.
                
                
                
                
                
                
                  &#8211; RGB LED key event selection and color setting
                
                
                
                  : 키를 누를 때 RGB LED가 반응하도록 설정합니다.
                
                
                
                  
                    : 1. color &#8211; 지정된 컬러로 전환
                  
                  
                  
                    
                      : 2. complementary color &#8211; 현재 컬러의 보색으로 전환
                    
                    
                    
                    
                    
                    
                      * Full&nbsp;LED Settings
                    
                    
                    
                      &#8211; Full LED Mode : 스위치 LED의 작동 모드를 변경합니다.
                    
                    
                    
                      :&nbsp;모드 변경 단축키는 ESC + Caps lock 입니다.
                    
                    
                    
                      1. LED off &#8211; &nbsp;꺼짐
                    
                    
                    
                      2. fading &#8211; 숨쉬기
                    
                    
                    
                      3. on &#8211; 계속 켜짐
                    
                    
                    
                      4. key down level up &#8211; 키 입력이 잦을수록 밝아짐
                    
                    
                    
                      5. key down level down &#8211; 키 입력이 잦을수록 어두워짐
                    
                    
                    
                    
                    
                    
                      &#8211;&nbsp;Full LED Brightness :&nbsp;스위치 LED의 밝기를 조절합니다.
                    
                    
                    
                      : RGB LED가 켜져 있다면 Full LED는 설정 값을 높혀도 밝기가 변하지 않습니다.&nbsp;
                    
                    
                    
                      : RGB LED의 밝기를 어느정도 낮추면 Full LED의 밝기가 밝아집니다.
                    
                    
                    
                    
                    
                    
                    
                    
                    
                      * 3Lock LED Settings
                    
                    
                    
                      Num lock, Scroll lcok, Caps lock 별로 작동 방식을 설정한다.
                    
                    
                    
                      1. Lock Indicator : 각 Lock 상태와 연동되어 on/off
                    
                    
                    
                      2. Always On : 항상 on
                    
                    
                    
                      3. Always Off : 항상 off
                    
                    
                    
                      3. Lock Reverse : Lock 상태와 반대로 작동
                    
                    
                    
                      4. FN2 Lock Indicator : FN2 Lock 상태일 경우 on (NCS&nbsp;상태는&nbsp;2번/1번 깜박임으로 표시)
                    
                    
                    
                      5.&nbsp;FN3&nbsp;Lock Indicator :&nbsp;FN3&nbsp;Lock 상태일 경우 on
                    
                    
                    
                      6.&nbsp;FN2/3 Lock Indicator :&nbsp;FN2 또는 FN3이&nbsp;Lock 상태일 경우 on
                    
                    
                    
                    
                    
                    
                      * Options
                    
                    
                    
                      &#8211; Esc to ~ : shift + ESC를 누를 경우 &#8220;~&#8221;를 입력 할 것인지 설정
                    
                    
                    
                    
                    
                    
                    
                    
                    
                      모든 설정을 마쳤다면 &#8220;disconnect&#8221;버튼을 클릭합니다.
                    
                    
                    
                    
                    
                    
                      
                    
                    
                    
                    
                    
                    
                      * 키 맵핑
                    
                    
                    
                    
                    
                    
                      이전 부트매퍼와 사용법은 같지만, &#8216;download&#8217;버튼으로 키보드의 키 맵을 직접 읽어 올 수 있고, &#8216;upload&#8217;로 바로 업로드 가능합니다.
                    
                    
                    
                    
                    
                    
                      &#8220;Key Mapper&#8221;탭으로 이동합니다.
                    
                    
                    
                    
                    
                    
                    
                    
                    
                      &#8211; 아직 키 맵핑이 되어 있지 않은 상태에서 처음 맵핑을 할 경우
                    
                    
                    
                    
                    
                    
                      1. 펌웨어에 포함된 기본 키맵 파일을 load 합니다. &#8220;load keymap_part.hex or .json&#8221; 버튼을 이용합니다.
                    
                    
                    
                      &#8211; 펌웨어 :&nbsp;http://blog.winkeyless.kr/153
                    
                    
                    
                    
                    
                    
                      2. &#8220;upload&#8217; 버튼을 클릭하면 부트로더로 자동 전환 된 후&nbsp;키 맵이&nbsp;업로드 됩니다.
                    
                    
                    
                      : &#8216;reboot after uploading&#8217;을 선택하면 키맵을 업로드 한 후 자동으로 키보드 상태로 돌아옵니다. 선택하지 않으면 부트로더 상태로 머물러 있습니다.
                    
                    
                    
                      (부트로더 상태에서 키보드 상태로 전환하고 싶다면, &#8216;Options&#8217; 탭의 &#8220;set keyboard&#8221; 버튼을 클릭하면 됩니다.)
                    
                    
                    
                    
                    
                    
                      3. 키 설정을 변경하고 싶을 경우 &#8220;toggle bootmapper&#8221; 버튼을 눌러주면 키보드의 부트맵퍼 트리거가 작동됩니다.
                    
                    
                    
                      : caps lock LED가 약 1초 간격으로 점멸 됩니다.
                    
                    
                    
                      
                        : 이때는 키보드로 작동되지 않고, 키를 누르면 해당 키의 매트릭스 위치를 출력합니다.&nbsp;
                      
                      
                      
                        
                          ex> .7,1.
                        
                        
                        
                          
                            : 해제 하고 싶다면 다시 한번 &#8220;toggle bootmapper&#8221; 버튼을 눌러주면 됩니다.
                          
                          
                          
                          
                          
                          
                            4. 키보드의 키를 누르면 매트릭스 상에 붉은 색으로 표시가 됩니다.&nbsp;
                          
                          
                          
                            : &#8220;save keymap_part.hex&#8221;버튼 옆에 글자로 layer와 col, row가 표시됩니다.
                          
                          
                          
                            
                              : 마우스 클릭으로 직접 매트릭스를 선택할 수 있습니다.
                            
                            
                            
                            
                            
                            
                              
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                              5. 원하는 키코드를 하단에서 선택합니다.&nbsp;그럼, 매트릭스 그리드에 선택한 키 값이 표시됩니다.&nbsp;
                            
                            
                            
                            
                            
                            
                              
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                              6.&nbsp;4-5를 반복하여 원하는 키들에 매핑을 합니다.
                            
                            
                            
                              &#8211; 기본적으로 키를 선택하면 모든 레이어에 적용이 됩니다.&nbsp;
                            
                            
                            
                              
                                &#8211; 특정 레이어만 키를 변경하고 싶다면 &#8220;apply to all layers&#8221; 항목의 체크를 해제하고 상단의 레이어 탭을 눌러 원하는 레이어만 변경하면 됩니다.
                              
                              
                              
                              
                              
                              
                                7. 원하는 모든 키를 변경했다면 &#8220;upload&#8221; 버튼을 눌러 업로드 합니다.
                              
                              
                              
                              
                              
                              
                              
                              
                              
                                &#8211; 이미 키 맵핑이 된 키보드의 일부 키만 변경 할 경우
                              
                              
                              
                              
                              
                              
                                1. &#8220;download&#8221; 버튼을 눌러 키보드로 부터 키 맵을 다운로드 합니다.
                              
                              
                              
                                : col/row 데이터가 표시됩니다.
                              
                              
                              
                              
                              
                              
                                2. &#8220;toggle bootmapper&#8221; 버튼을 눌러 키보드의 부트맵퍼 트리거를 작동 시킵니다.
                              
                              
                              
                                : 부트맵퍼 트리거를 작동시키지 않고 마우스 클릭으로 직접 매트릭스를 선택할 수 있습니다.
                              
                              
                              
                              
                              
                              
                                3. 키보드의&nbsp;원하는 키를 눌러 col/row를 선택한 후 변경할 키코드를 하단에서 선택합니다.
                              
                              
                              
                              
                              
                              
                                4. 원하는 모든 키를 변경했다면 &#8220;upload&#8221; 버튼을 눌러 업로드 합니다.
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                              
                                * 커스텀 매크로
                              
                              
                              
                              
                              
                              
                                &#8211; 기본 사용 방법은 Boot Mapper Site의 그것과 동일 합니다. 아래 링크의 내용을 참고하세요.
                              
                              
                              
                                Boot Mapper Site의 커스텀 매크로 사용 법 :&nbsp;http://blog.winkeyless.kr/125
                              
                              
                              
                              
                              
                              
                                &#8211; 다만, upload/download 가 추가되어 키보드의 매크로 데이터를 바로 읽거나 쓸 수 있는 점이 다릅니다.
                              
                              
                              
                              
                              
                              
                              