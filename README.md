# Skip the spinning rims
## We're on the clock. 

A simple Ansible playbook to get an OSX box provisioned. 

1. Install Xcode

1. Clone the project: `git clone git@github.com:tatyree/skip-the-spinning-rims.git`

1. Install ansible (http://docs.ansible.com/intro_installation.html)

1. Run the ansible playbook: `cd skip-the-spinning-rims;
   ansible-playbook main.yml`

1. If you're asked for a password, enter your standard account password;
   this is sudo surfacing and happens when you've got a non-managed
   version of the application already in the Application folder. 


