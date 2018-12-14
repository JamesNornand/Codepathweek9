# Codepathweek9

## Which Honeypot(s) you deployed

    NAME            ZONE           MACHINE_TYPE  PREEMPTIBLE  INTERNAL_IP  EXTERNAL_IP   STATUS
    mhn-honeypot-1  us-central1-c  f1-micro                   10.128.0.3   23.236.50.41  RUNNING
    mhn-admin       us-central1-c  f1-micro                   10.128.0.2   35.238.148.18

  
## Any issues you encountered
In the instruction:

    $ cd /opt
    $ sudo git clone https://github.com/RedolentSun/mhn.git
    $ cd mhn
    $ sudo ./install.sh

However now it is:

    $ sudo git clone https://github.com/threatstream/mhn.git

Problem is solved.
  
## A summary of the data collected: number of attacks, number of malware samples, etc.
    Total Attacks: 1076
    Malware Collected: None
  
## Any unresolved questions raised by the data collected
    None
## Some notes
Do you wish to run in Debug mode?: y/n n
Superuser email: jzhu11@pride.hofstra.edu
Superuser password: 
Superuser password: (again): 
Server base url ["http://35.238.148.18"]: 
Honeymap url ["http://35.238.148.18:3000"]: 
