#Vagrant setup

commands:
    - rerun provision
        vagrant provision
    - do not run provision
        vagrant [up|reload] no-provision
    - do a specific provision only (eg. puppet)
        vagrant up provision-with puppet