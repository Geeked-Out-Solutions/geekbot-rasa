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
* linux_install[os=linux]
  - utter_linux_install
* goodbye
  - utter_goodbye
    
## user answers Pi
> check_asked_os
* pi_install[os=pi]
  - utter_pi_install  
* goodbye
  - utter_goodbye
  
## user answers Docker
> check_asked_os
* pi_install[os=docker]
  - utter_docker_install 
* goodbye
  - utter_goodbye