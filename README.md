# Pi-Surveillance

## Usage

1. run " **$ python3 run.py** "
1. 

## Run on startup

1. place " **python3 /home/pi/rpi.py &** " before " exit 0 " in **rc.local** file (**$ sudo nano /etc/rc.local**)

## Expose to creepyfuck:8000

1. place " **autossh -R 8000:localhost:8000 ubuntu@creepyfuck.tech -p 2 &** " before " exit 0 " in **rc.local** file