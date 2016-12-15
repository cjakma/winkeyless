---
layout: post
title: Firmware Installing and Setting
published: true
author: showjean
comments: true
date: 2015-01-12 08:01:14
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: /651
image:
    feature: cfile1.uf.2768C53354B37CB62803F4.png
---




  
    
      bootMapperClient
    
  



  



  1) For Window



  &nbsp;&#8211; Download : https://www.dropbox.com/s/3bn9flirkb49ahz/BootMapperClient.zip?dl=0








  &#8211; Unzipping



  
    
      Download bootMapperClient.zip And unzip.
    
  
  
  
    
      After unzipping, you can see the directory like a picture below.
    
  





  







  



  2) For Mac



  &#8211; Download : https://www.dropbox.com/s/wselndg19ofby85/BootMapperClient.mac.zip?dl=0














  2. Downloading Firmware



  



  &#8211; Link : http://blog.winkeyless.kr/153






  
    
      Download ps2avrGB_firmware_Vx.x.x_YYMMDD.zip
    
  
  
  
    
      When unzipping 4 hex files appear. &#8211; ps2avrGB_NKRO.hex : Firmware &#8211; keymap_gb_B87(EX).hex : Key map for B.87, B.87 EX, B.mini, B.mini EX &#8211; keymap_gb_face_thumb.hex : Key map for B.face, B.thumb &#8211; keymap_gb_pad.hex : Key map for B.pad
    
  


 


  



  



  3. How to upload firmware



  



  
    
      Supporting both for Window and Mac OS
    
  
  
  
    
      Available only while connected by USB
    
  
  
  
    
      First of all you must upload firmware to enable all the functions properly.(When MCU was attached to the PCB by soldering, bootloader was automatically installed.)
    
  



  



  
    
      Start bootMapperClient.exe
    
  



  



  2) Select “Options > firm up(select hex file)” and select firmware file.



  



  



  









  









  









  &#8211; After automatically starting bootloader, keyboard works again. 



  &#8211; If bootloader doesn’t start again, you have to start in manually. While pressing the key “Left ctlr”(in case of B.pad the key “0”), connect USB cable. Then bootloader will start again.



   
  
  
    
  
  
  
    4. How to set RGB LED
  
  
  
    
      
        Just select “Options > connect”
      
    
  
  
  
    
  
  
  
  
  
  
    
  
  
  
  
  
  
  
  
  
    &#8211; When you click “connect”, keyboard switch LEDs will be off.
  
  
  
    &#8211; When you click &#8220;disconnect&#8221;, keyboard switch LEDs will be on and setting mode will be disconnected.
  
  
  
    &#8211; Num of LEDs : The amount of RGB LED in PCB 
  
  
  
    &#8211; LED mode selection and color setting : Choose LED mode and set Color.(you can use hexa code to define color you want. ex, FF3300)
  
  
  
    
  
  
  
    &#8211; Brightness : Can set the brightness of RGB LED by using slider. The brighter RGB LED, the darker switch LED.
  
  
  
     
    
    
      
    
    
    
      5. How to map keys
    
    
    
      
    
    
    
      1) Select “Key Mapper” tab
    
    
    
      
    
    
    
      2) If it’s the first time to map keys.
    
    
    
      
    
    
    
      2-1) Click the button labeled &nbsp;&#8220;load keymap_part.hex or .json&#8221; and load basic Key mapping file included in the firmware.
    
    
    
      
    
    
    
      2-2) Select “upload” button, and then key map will be loaded after bootloader starts.
    
    
    
      
        
          If you choose “reboot after uploading”, automatically it will enable the keyboard. If not, stay in the state of bootloader.
        
      
      
      
        
          If you want to enable the keyboard manually, just select “Options>set keyboard” button
        
      
    
    
    
      
    
    
    
      2-3) If you want to change key settings, click “toggle bootmapper” button.
    
    
    
      
    
    
    
      2-4) If you press a key, a red light appear on matrix.
    
    
    
      
    
    
    
      2-5) Just select the key code you want.
    
    
    
      
    
    
    
      2-6) When you change all the keys, select “upload” button to upload settings.
    
    
    
       
      
      
        
      
      
      
        3) When you want to change the settings for only several keys from key-mapped keyboard.
      
      
      
        
      
      
      
        3-1) Select “download” button, so download key-map. After that you will see the col/row data table.
      
      
      
        
      
      
      
        3-2) Start bootMapper by clicking “toggle bootmapper”.
      
      
      
        
      
      
      
        3-3) After pressing a keyboard you want to change, select the col/row and keycode value.
      
      
      
        
      
      
      
        3-4) By selection “toggle bootmapper”, stop bootMapper.
      
      
      
         
        
        
          
        
        
        
          6. Custom Macro 
        
        
        
          
            
              You can define maximum 12 Custom Macros.
            
          
          
          
            
              A macro can have up to 42 characters.
            
          
        
        
        
          
        
        
        
          1) Start bootMapper Client progrma
        
        
        
          
        
        
        
          2) Select “Custom Macro” tab.
        
        
        
          
        
        
        
          
        
        
        
           
          
          
            
          
          
          
            
          
          
          
            3) You can see the display below
          
          
          
            
              
                Select CstMacX tab(CstMac stands for “Custom Macro”.) and enter Characters you want. 
              
            
            
            
              
                You can delete a selected character by pressing “remove” button.
              
            
            
            
              
                You can change order by dragging a character.
              
            
          
          
          
            
          
          
          
            
          
          
          
            
          
          
          
            
          
          
          
            4) Select “save macro.hex” to save Macro setting.
          
          
          
            
              
                When you upload this file to keyboard using bootloader.
              
            
          
          
          
            
          
          
          
            5) If you want to combine modifier keys as a macro, follow the instructions.(Example shows how to set “Ctrl+c” macro.)
          
          
          
            
              
                Add all the keys you want to use as a macro.
              
            
          
          
          
            
          
          
          
          
          
          
            
          
          
          
          
          
          
            
          
          
          
            &#8211; While LCtrl selected, press the “split” button.(or shift + mouse click)
          
          
          
            
          
          
          
          
          
          
            
          
          
          
          
          
          
            
          
          
          
            
          
          
          
            &#8211; You will see the splited LCtrl into down and up. 
          
          
          
          
          
          
            
          
          
          
            
          
          
          
          
          
          
            
          
          
          
            &#8211; Just drag anything to place “C” is in the middle between LCtrl(down) and LCtrl(up).
          
          
          
          
          
          
            
          
          
          
          
          
          
          
          
          
            
          
          
          
          
          
          
             
            
            
              
            
            
            
              6) You can set the delay for a macro.
            
            
            
              &#8211; Selecte the key you want.
            
            
            
              &#8211; Enter time(min 0.1 sec, max 5 secs) 
            
            
            
              &#8211; Press “apply delay” button
            
            
            
              
            
            
            
              
            
            
            
            
            
            
              
            
            
            
              
            
            
            
               
              
              
                
              
              
              
                 
                
                
                  
                
                
                
                  7) Text To Macro
                
                
                
                  
                    
                      The text entered can be translated into a macro
                    
                  
                
                
                
                  
                
                
                
                  &#8211; Enter the text you want to us as a macro in the text box &#8220;String Parsing&#8221; 
                
                
                
                
                
                
                  
                
                
                
                
                
                
                  
                    
                      press “parse string >>” button, and then you can see all the keys splited.
                    
                  
                
                
                
                
                
                
                  
                
                
                
                
                
                
                
                
                
                  &#8211; Available texts 
                
                
                
                  Normal Texts : `1234567890-=qwertyuiop[]\asdfghjkl;&#8217;zxcvbnm,./
                
                
                
                  Shift+Texts : ~!@#$%^&*()_+QWERTYUIOP{}|ASDFGHJKL:&#8221;ZXCVBNM?
                
                
                
                  
                
                
                
                