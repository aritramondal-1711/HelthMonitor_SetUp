# HelthMonitor_SetUp
This ansible playbook will set up the entire project described in HealthCheck repo ( https://github.com/aritramondal-1711/HealthCheck ) automatically

# Execute Below command and then test on any web browser http://localhost

    cd
    git clone https://github.com/aritramondal-1711/HelthMonitor_SetUp.git
    ansible-playbook /home/ansible/HelthMonitor_SetUp/setup.yml -i /home/ansible/HelthMonitor_SetUp/hosts

# Prerequisites

* Set up ansible user
  
      useradd -s /bin/bash -d /home/ansible -m ansible

* Make sure it has sudo access (psswordless)
  
      echo "ansible ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers


## ** Make sure ansible is installed and configured for "ansible" user to use ansible and ssh (password less)
