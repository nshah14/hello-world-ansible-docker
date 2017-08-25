# hello-world-ansible-docker
Setup hello world using nginx server, configured using ansible and docker.


How to run it 
Requirement
  * You should have Virtual box setup.
  * You should have Vagarnt installed,
  * You should have ansible installed.

Execution
* Navigate to directory where Vagrantfile is.
* Run comamnd to use setup role `ansible-galaxy install -r requirements.yml`.  
* Run command `vagrant up`

When the result on your terminal is something like
PLAY RECAP *********************************************************************
default                    : ok=23   changed=14   unreachable=0    failed=0   

Request url of your browser http://192.168.33.99:80/

Note:- you can always use a hostname by setting up  
****************************************
    192.168.33.99 sbcons.nginx 
****************************************
in your `/etc/hosts` file
