## NLU Answers

## goodbye
* goodbye
    - utter_goodbye

## thank you
* thankyou
    - utter_youarewelcome
    
## user asks how to install on linux
* choose_os[os=linux]
    - utter_linux_install

## user asks how to install on pi
* choose_os[os=pi]
    - utter_pi_install

## user asks how to install on docker
* choose_os[os=docker]
    - utter_docker_install

## user asks for mycroft documentation    
* mycroft_docs
    - utter_mycroft_docs
    
## user asks for help
* mycroft_help
    - utter_mycroft_help
    
## user asks about me
* about_me               
    - utter_about_me                

## user asks for skills list
* skills_list
    - utter_skills_list
    

## Automated Button Answers

## mycroft help path install linux  
* greet              
    - utter_greet
* mycroft_help               
    - utter_mycroft_help
* choose_os
    - utter_choose_os
> check_asked_os

## user answers Linux
> check_asked_os
* choose_os[os=linux]
    - utter_linux_install
    
## user answers Pi
> check_asked_os
* choose_os[os=pi]
    - utter_pi_install  
  
## user answers Docker
> check_asked_os
* choose_os[os=docker]
    - utter_docker_install 

## mycroft docs
* greet              
    - utter_greet
* mycroft_help               
    - utter_mycroft_help
* mycroft_docs
    - utter_mycroft_docs
  
## skills list
* greet              
    - utter_greet
* mycroft_help               
    - utter_mycroft_help
* skills_list
    - utter_skills_list
  
## about me
* greet              
    - utter_greet
* about_me               
    - utter_about_me