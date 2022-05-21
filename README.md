# do22-playbooks

To test playbooks in this repo, do: \
`cd /vagrant` \
`vagrant up` \
Check that you can ssh into vm1 by running: `vagrant ssh vm1`. \
After that, run `vagrant ssh-config >> ~/.ssh/config` to append the ssh config into your home folder's config, this will enable ansible to run playbooks on this machine.
`cd ..` \

Run your playbooks with `ansible-playbook`...