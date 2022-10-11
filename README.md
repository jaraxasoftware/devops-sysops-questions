Linux System Administrator/DevOps Interview Questionnaire
========================================================

Please answer as simply as you can. If you cannot answer a particular question, leave it blank, or leave a comment.

*This is not an exam. You should not have necessarily to answer all.*


## <a name='toc'>Table of Contents</a>

  1. [Simple Linux Questions](#simple)
  1. [Medium Linux Questions](#medium)
  1. [Hard Linux Questions](#hard)
  1. [Expert Linux Questions](#expert)
  1. [Networking Questions](#network)
  1. [DevOps Questions](#devop)
  1. [Curiosity Questions](#fun)
  1. [Demo Time](#demo)


#### [[⬆]](#toc) <a name='simple'>Simple Linux Questions:</a>

* Which command will show you free/used memory? Does free memory exist on Linux?
* I get "command not found" when I run ```ifconfig -a```. What can be wrong?
* What command will show the available disk space on the Unix/Linux system?
* What commands do you know that can be used to check DNS records?
* What does the permission 0750 on a file mean?
* What does the permission 0750 on a directory mean?
* How to add a new system user without login permissions?
* How to add/remove a group from a user?
* What is a bash alias?
* How to redirect STDOUT and STDERR in bash? 
* Explain the three load averages and what do they indicate. What command can be used to view the load averages?
* Walk me through the steps you'd take to troubleshoot a 404 error on a web application you administer.

#### [[⬆]](#toc) <a name='medium'>Medium Linux Questions:</a>

* What does an ```&``` after a command do?
* What is swap and what is it used for?
* What is the sticky bit?
* What does the immutable bit do to a file?
* What is the difference between hardlinks and symlinks? What happens when you remove the source to a symlink/hardlink?
* What is SSH port forwarding?
* Describe a scenario when you get a "filesystem is full" error, but 'df' shows there is free space.
* Describe a scenario when deleting a file, but 'df' not showing the space being freed.
* How to know which process listens on a specific port?
* You run a bash script and you want to see its output on your terminal and save it to a file at the same time. How could you do it?
* Describe briefly the steps you need to take in order to create and install a valid certificate for the site https://foo.example.com.
* What is "nohup" used for?
* You need to upgrade kernel at 100-1000 servers, how you would do this?
* Do you know of any alternative shells? If so, have you used any?
* How can you tell if the httpd package was already installed?
* Can you explain to me the difference between block based, and object based storage?

#### [[⬆]](#toc) <a name='hard'>Hard Linux Questions:</a>

* What is the difference between IDS and IPS?
* Your freshly configured http server is not running after a restart, what can you do?
* What kind of keys are in ~/.ssh/authorized_keys and what it is this file used for?
* I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?
* What does ```:(){ :|:& };:``` do on your system?
* What's happening when the Linux kernel is starting the OOM killer and how does it choose which process to kill first?
* What's a chroot jail?
* You ran a binary and nothing happened. How would you debug this?
* How can you increase or decrease the priority of a process in Linux?


#### [[⬆]](#toc) <a name='expert'>Expert Linux Questions:</a>

* A running process gets ```EAGAIN: Resource temporarily unavailable``` on reading a socket. How can you close this bad socket/file descriptor without killing the process?
* What do you control with swapiness?
* What is LVM? How to use it?


#### [[⬆]](#toc) <a name='network'>Networking Questions:</a>

* What is the command used to show all open ports and/or socket connections on a machine?
* Which IP ranges/subnets are "private" or "non-routable" (RFC 1918)?
* What is a VLAN?
* What is ARP and what is it used for?
* What is the difference between TCP and UDP?
* What is command used to show the routing table on a Linux box?
* What is SNAT and when should it be used?
* Explain how could you ssh login into a Linux system that DROPs all new incoming packets using a SSH tunnel.
* How do you stop a DDoS attack?


#### [[⬆]](#toc) <a name='devop'>DevOps Questions:</a>

* Can you describe your workflow when you create a script?
* What is GIT?
* What is puppet/chef/ansible used for? Name a use case for them.
* What is Nagios/Grafana/Kibana used for? Name a use case for them.
* What is NewRelic/AppDynamics/DataDog? Name a use case for them.
* What is Tekton/Github Actions/Azure Devops used for?
* What is the difference between Containers and VMs?
* How do you create a new postgres user?
* What is a virtual IP address? What is a cluster?
* What are the advantages/disadvantages of script vs compiled program?
* What are the important aspects of a system of continuous integration and deployment?
* How would you enable network file sharing within AWS that would allow EC2 instances in multiple availability zones to share data?

#### [[⬆]](#toc) <a name='fun'>Fun Questions:</a>

* I've lost my root password, what can I do?
* I've rebooted a remote server but after 10 minutes I'm still not able to ssh into it, what can be wrong?
* You have deleted by error a running script, what could you do to restore it?
* How to reboot server when reboot command is not responding?

#### [[⬆]](#toc) <a name='demo'>Demo Time:</a>

* Get the Java application skeleton on Code folder. Show us what you would do with it to move across environemnts. Try to maintain the maximum simplicity. No need to get a working DevOps and/or CD/CI workflow, but using Github Actions will be a plus+++. You can just suggest or make a basic approach.

