# ansibletest
simple ansible playbook that installs docker-CE at the target machine and then downloads from git and starts a simple flask app.

# NOTE:
the hosts archive must be edited in order to pass the ssh key to the instance!

## to use simply git clone this repository, and then: ansible-playbook docker.yml -i hosts
