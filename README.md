# ansible_templates









###for cygwin: 

(http://stackoverflow.com/questions/32596203/cygwin-how-to-install-ansible)

+ type apt-cyg || exit
+ apt-cyg install git python-{jinja2,six,yaml}
+ git clone --depth 1 https://github.com/ansible/ansible.git
+ cd ansible
+ PATH+=:~+/bin
+ export PYTHONPATH=~+/lib
+ ansible --version

+ git submodule update --init --recursive
