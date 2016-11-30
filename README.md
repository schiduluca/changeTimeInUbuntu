# Change time in Ubuntu

1. First you need to make sure you installed the ntp package
    ```sh
    $ sudo apt-get install npt
    ```
2. Run the following command to stop the ntp time syncronization
    ```sh
    $ sudo timedatectl set-ntp 0
    ```
    To make sure than sync was disabled run the command `timedatectl` in terminal and you will obtain the following result
    ```
    Network time on: no
    ```
3. Disable network from ubuntu
4. Now you can run the command `date -s "x days/hours/seconds"`, where instead of x specify the number of days, hours or seconds to move forward. To change the time backwards just type `date -s "6 hours ago"` for example.

5. After that you can enable the network back on. 
    
