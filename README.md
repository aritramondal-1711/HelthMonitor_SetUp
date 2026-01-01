# HelthMonitor_SetUp
This ansible playbook will set up the entire project conigured HealthCheck repo automatically

# Execute Below command and then test on any web browser http://localhost

    ansible-playbook setup.yml 

# Prerequisites

* Set up ansible user
  
      useradd -s /bin/bash -d /home/ansible -m ansible

* Make sure it has sudo access (psswordless)
  
      echo "ansible ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers
