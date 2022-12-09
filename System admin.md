TIPS

Download the command "mc" with "sudo apt install mc"
"mc" is a graphic interface inside your terminal. It will give you the rights to remove, copy, etc... files/directory by usign "sudo mc"
## TCP/IP

#### ip
````
The ip command is a Linux net-tool for system and network administrators. IP stands for Internet Protocol and as the name suggests, the tool is used for configuring network interfaces.
````

#### ip command cheatsheet
````
https://access.redhat.com/sites/default/files/attachments/rh_ip_command_cheatsheet_1214_jcs_print.pdf
````

#### ifconfig
````
Ifconfig is used to configure the kernel-resident network interfaces. It is used at boot time to set up interfaces as necessary. After that, it is usually only needed when debugging or when system tuning is needed. If no arguments are given, ifconfig displays the status of the currently active interfaces.
````

#### ifconfig help
````
https://www.geeksforgeeks.org/ifconfig-command-in-linux-with-examples/
````
#### whois
````
WHOIS is a query and response protocol that is widely used for querying databases that store the registered users of an Internet resource, such as a domain name or an IP address block, but is also used for a wider range of other information
````

## Ports

#### lsof
````
The lsof (list open files) command returns the user processes that are actively using a file system. It is sometimes helpful in determining why a file system remains in use and cannot be unmounted.
````

#### nmap
````
Nmap is Linux command-line tool for network exploration and security auditing. This tool is generally used by hackers and cybersecurity enthusiasts and even by network and system administrators. It is used for the following purposes: 

Real time information of a network
Detailed information of all the IPs activated on your network
Number of ports open in a network
Provide the list of live hosts
Port, OS and Host scanning
````

#### nmap cheatsheet
````
https://www.stationx.net/nmap-cheat-sheet/
````

#### Will check the status of the package and will send the messages into the void
````
dpkg -s $package &> /dev/null
````

#### Will check if the most recently-executed command was launch with success
````
$? -eq 0
````

#### Example on how a .service in serviced looks like
````
[Unit]
Description=Gives date every 10 sec

[Service]
User=mk
WorkingDirectory=/home/mk/Desktop/DevSecOps
ExecStart=/home/mk/Desktop/DevSecOps/date.sh
Restart=always

[Install]
WantedBy=multi-user.target
````


