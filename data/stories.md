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
* utter_choose_os[os=linux]
  - utter_linux_install
* goodbye
  - utter_goodbye
    
## user answers Pi
> check_asked_os
* utter_choose_os[os=pi]
  - utter_pi_install  
* goodbye
  - utter_goodbye
  
## user answers Docker
> check_asked_os
* utter_choose_os[os=docker]
  - utter_docker_install 
* goodbye
  - utter_goodbye
  
## mycroft docs
* greet              
  - utter_greet
* mycroft_help               
  - utter_mycroft_help
* mycroft_docs
  - utter_mycroft_docs