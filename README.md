# Flask_tutorial


# nginx reload

from https://devsnote.com/asks/82

ps -ef | grep nginx
process 확인, 죽어있다면 sudo nginx로 활성화




# WSL2 리눅스 종료

wsl -l -v  => 현재 구동중인 가상머신 확인

wsl -t ubuntu => 구동중인 ubuntu 종료(그냥 강제종료해도 동일)