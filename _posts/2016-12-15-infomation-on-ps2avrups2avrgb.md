---
layout: post
title: Infomation on ps2avrU+ps2avrGB
published: true
author: showjean
comments: true
date: 2015-01-21 08:01:11
tags: [ ]
categories:
    - '%ec%a0%95%eb%b3%b4'
permalink: /infomation-on-ps2avrups2avrgb
---

  
    
      ps2avrU
    
  





  
    
      What is ps2avrU?
    
  





  
    
       Firmware supporting both USB and PS/2 
    
  
  
  
    
      Combination of 2 firmwares, “ps2avr”(for ps/2) and “dulcimer”(for USB) 
    
  
  
  
    
      Link for projects
    
  



  
    
      ps2avr : http://ps2avr.sourceforge.net/
    
  
  
  
    
      dulcimer : http://www.schatenseite.de/dulcimer.html?L=2
    
  





  2) Difference between USB and PS/2 interfaces





  
    
      USB
    
  



  
    
      Supporting 6+1 simulataneous key input
    
  
  
  
    
      Supporting normal speed for key repeat 
    
  





   &nbsp;&nbsp;&nbsp;&nbsp;b. PS/2 



  
    
      Supporting unlimited simultaneous key input
    
  
  
  
    
      Supporting fast speed for key repeat 
    
  


 


  



  3) How to change interface



  



  
    
      Basically it changes automatically 
    
  
  
  
    
      If you want to change manually 
    
  



  
    
      to USB : While pressing &#8220;U&#8221; key, connect the keyboard to USB port.
    
  
  
  
    
      to PS/2 : While pressing &#8220;P&#8221; key, connect the keyboard to PS/2 port.
    
  



   &nbsp;&nbsp;&nbsp;&nbsp;c. If you want to reset : While pressing &#8220;U&#8221;+ &#8220;P&#8221;, connect the keyboard to port



   
  
  
    
  
  
  
    4) Interface Signal
  
  
  
    
  
  
  
    
      
        Flashing count of CapsLock/NumLock LED
      
    
  
  
  
    
      
        1 time : recognizing PS/2
      
    
    
    
      
        No flashing : recognizing USB
      
    
    
    
      
        Continuous flashing : in the process of recognizing
      
    
  
  
  
     
    
    
      
    
    
    
      5) Basic functions
    
    
    
      
    
    
    
      
        
          Supproting Full LED
        
      
      
      
        
          Providing interface to change LED mode : While pressing “ESC”, press “Caps Lock” (or FN + caps lock) for specfic times
        
      
    
    
    
      
        
          1 time : LED off 
        
      
      
      
        
          2 times : Fading 
        
      
      
      
        
          3 times : LED on 
        
      
      
      
        
          4 times and then any key down : &nbsp;Getting brighter
        
      
      
      
        
          5 times and then any key down : Getting darker
        
      
    
    
    
      
    
    
    
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. Setting full LED brightness using macro
    
    
    
      
        
          KEY_LED_UP : getting brighter
        
      
      
      
        
          KEY_LED_DOWN : getting darker
        
      
    
    
    
      
    
    
    
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. Mapping keys for brightness
    
    
    
      
        
          A.87 and MX-mini series : FN + &#8211; / FN + =
        
      
      
      
        
          Thumb series : FN + R Alt/ FN + R Ctrl
        
      
    
    
    
      
    
    
    
       &nbsp;&nbsp;&nbsp;&nbsp;e. 4 Layer Key Map
    
    
    
      
        
          1 : normal
        
      
      
      
        
          2 : &nbsp;FN
        
      
      
      
        
          3 : &nbsp;FN2/FN3
        
      
    
    
    
      
    
    
    
       &nbsp;&nbsp;&nbsp;&nbsp;f. &nbsp;Scroll Lock LED signal
    
    
    
      
        
          There is no special signal for Scroll Lock LED. But you can tell by seeing Caps Lock LED flashing when it turns on or off(1 tiem for off, 2 times for on). 
        
      
      
      
        
          One of Firmware files named “SL_apart” shows Scroll Lock LED in MCU PD6 pin. 
        
      
      
      
        
          Sleep Mode : When system ends, keyboard enter sleep mode turning LED off when connected through USB. 
        
      
    
    
    
       
      
      
        
      
      
      
        6) Key Mapping
      
      
      
        &#8211; Link : http://blog.winkeyless.kr/183
      
      
      
         
        
        
          
        
        
        
          7) Hardware and Quick Macro 
        
        
        
          &#8211; Link : http://blog.winkeyless.kr/184
        
        
        
           
          
          
            
          
          
          
            8) Quick Swap
          
          
          
            
          
          
          
            
              
                “Swap” means altering between “alt” and “GUI”
              
            
            
            
              
                Press “alt” + “GUI” together for 5 seconds.
              
            
          
          
          
             
            
            
              
            
            
            
              9) Special Keys
            
            
            
              
            
            
            
              
                
                  How to use hardware menu 
                
              
            
            
            
              
                
                  Open a text editting program such as NotePad.
                
              
              
              
                
                  Press Left Ctrl + alt + shift + Right shift(total 4keys) for 5 seconds and then you’ll see the menus 
                
              
              
              
                
                  Here are the messages.
                
              
            
            
            
            
            
            
             
            
            
              
                hello
              
              
              
              
              
              
                select mode
              
              
              
                1:keymapper
              
              
              
                2:macro
              
              
              
                3:lazy fn : on
              
              
              
                4:fn2/3 led : sl
              
              
              
                5:esc to ~ : off
              
              
              
                7:exit
              
              
              
                9:boot mapper
              
              
              
                >>
              
            
            
            
              
            
            
            
            
            
            
              b. Lock Key/Win Key
            
            
            
              
                
                  Lock Key : prevents input form all the keys.(toggle)
                
              
              
              
                
                  Lock Win : block left/right window key press.(toggle)
                
              
            
            
            
               
              
              
                
              
              
              
                c. Lazy FN/FN2
              
              
              
                
                  
                    If you set lazy FN &nbsp;option &nbsp;on, you can’t change layer. 
                  
                
                
                
                  
                    This option can be set in the hardware key mapper menu.
                  
                
              
              
              
                 
                
                
                  
                
                
                
                  d. dual action key 
                
                
                
                  
                    
                      This action is handling a several of key functions.
                    
                  
                  
                  
                    
                      You can add this functions to the keys like FN, FN2, Ctrl, alt, shift. &nbsp;&nbsp;
                    
                  
                
                
                
                  
                
                
                
                  e. how dual action key acts
                
                
                
                  
                    
                      It gives the delay of 0.5 seconds. 
                    
                  
                  
                  
                    
                      So you have to wait for a while to get combination key 
                    
                  
                  
                  
                    
                      If you conbine it to other keys, it acts without delay. 
                    
                  
                  
                  
                    
                      If you want to change the language with only one key(Lang key), you have to press down and up in &nbsp;0.5 second. 
                    
                  
                
                
                
                   
                  
                  
                    
                  
                  
                  
                     f. Shift + Esc = ~
                  
                  
                  
                    
                      
                        
                          In mini keyboard, entering “~” is difficult. So you can do that with “Shift + ESC” key. 
                        
                      
                      
                      
                        
                          In Key Mapper menu, change “esc to ~” option to “on” &nbsp;
                        
                      
                    
                    
                    
                      
                    
                    
                    
                      
                    
                    
                    
                       
                      
                      
                        
                      
                      
                      
                        2. ps2avrGB
                      
                      
                      
                        
                      
                      
                      
                        
                          
                            What is ps2avrGB
                          
                        
                      
                      
                      
                        
                          
                            Supporting ps2avrU + RGB LED control
                          
                        
                        
                        
                          
                            Supporting all functions BootMapper client provides.
                          
                        
                      
                      
                      
                         
                        
                        
                          
                        
                        
                        
                          2) RGB LED
                        
                        
                        
                          
                            
                              Provides the interface to change RGB LED color by using bootMapper client.
                            
                          
                          
                          
                            
                              Mode Change : ESC + SHIFT + Caps lock or &nbsp;LED MODE2
                            
                          
                          
                          
                            
                              Changing of RGB key event mode : ESC + Ctrl + Capslock or Ctrl + LED_MODE2
                            
                          
                          
                          
                            
                              Setting brightness : SHIFT+KEY_LED_UP, SHIFT+KEY_LED_DOWN (The brighter RGB LED, the darker full LED)
                            
                          
                          
                          
                            
                              Basic Key Mapping on the keyboard with F keys
                            
                          
                        
                        
                        
                          
                            
                              LED MODE : FN+Caps lock
                            
                          
                          
                          
                            
                              KEY_LED_UP : FN + =
                            
                          
                          
                          
                            
                              KEY_LED_DOWN : FN + &#8211;
                            
                          
                        
                        
                        
                          
                        
                        
                        
                           &nbsp;&nbsp;&nbsp;&nbsp;f. Basic Key Mapping on the keyboard without F keys 
                        
                        
                        
                          
                            
                              KEY_LED_UP : FN + H
                            
                          
                          
                          
                            
                              KEY_LED_DOWN : FN + G
                            
                          
                        
                        
                        
                          
                            You can see more about “bootMapper Client” at http://blog.winkeyless.kr/183
                          
                          
                          
                            
                          
                          
                          
                          
                          
                          
                          