
## Assignemnt 2 
f-> ansible production -m apt -a "name=openjdk-17-jdk state=present" -b
g-> ansible production -m setup -a "filter=ansible_user,ansible_uptime,ansible_processor,ansible_mounts,ansible_memory_mb" -b
h-> ansible-inventory --list
i-> ansible production,development -m command -a "which git"
 , & :!

 ## 
