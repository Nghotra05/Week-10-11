# Week-10-11
MILESTONE 0 
https://shell.cloud.google.com/?show=ide%2Cterminal 
Commands used:  
$ gcloud config set compute/region us-central1 
 
$ gcloud config set compute/zone us-central1-c 
 
 
MILESTONE 1 
/home/nghotra05/.ssh/google_compute_engine 
NAME: mhn-admin 
ZONE: us-central1-c 
MACHINE_TYPE: f1-micro 
PREEMPTIBLE: 
INTERNAL_IP: 10.128.0.2 
EXTERNAL_IP: 35.222.171.0 
STATUS: RUNNING 
 
 
MILESTONE 2 
MHN created using given commands. 
External IP: 35.223.236.35 
 
MILESTONE 3 
NAME            ZONE        MACHINE_TYPE  PREEMPTIBLE  INTERNAL_IP  EXTERNAL_IP   STATUS 
mhn-honeypot-1  us-east1-c  f1-micro                   10.142.0.2   34.75.187.43  RUNNING 
 
NAME            ZONE        MACHINE_TYPE  PREEMPTIBLE  INTERNAL_IP  EXTERNAL_IP     STATUS 
mhn-honeypot-2  us-east1-c  f1-micro                   10.142.0.3   35.196.194.209  RUNNING 
 
 
MILESTONE 4 
wget "http://35.223.236.35/api/script/?text=true&script_id=2" -O deploy.sh && sudo bash deploy.sh http://35.223.236.35 RVtCQn3N 
 
MILESTONE 6 
 
 
I have used two different accounts because 2nd and 4th milestone didn’t work with my 1st account. I tried to finish 5, but it didn’t work for me. 
Errors I concerned was for milestone 2. 
