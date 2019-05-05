# Raspbery_switch
This is a project that use a switch to shut down the Raspberry Pi system. You can follow the tutorial on Instructables:
https://www.instructables.com/id/Raspberry-Pi-Zero-Switch-Off-by-Button/

EDITING RC.LOCAL
nano /etc/rc.local

add
python /Raspbery_switch/shutdown.py &
