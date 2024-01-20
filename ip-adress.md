To get the ip adress of the current computer either look at the logs from the degree display server or run:  
ifconfig | grep "inet " | grep -Fv 127.0.0.1 | awk '{print $2}'