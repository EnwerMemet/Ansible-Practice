# Ansible-Practice
https://devdocs.io/ansible/

What is Ansible? 
Imagine you have 100 computers, and you want to install Minecraft on every single one of them.
Ansible is like a magical remote control. Instead of walking to every computer, you sit at your laptop and write a To-Do List (which Ansible calls a Playbook).
Then, you press one button, and Ansible flies out over the internet to all 100 computers at the same time and does the work for you.

What is Ansible? 
Think of the Inventory file as Ansible's Address Book.

Before your "Robot Assistant" (Ansible) can do any work, it needs to know two things:

Who am I talking to? (The names or IP addresses of the computers).

How do I get there? (The secret "handshake" or connection method).


Using Ansible lets you automate virtually any task. Here are some common use cases for Ansible:

Eliminate repetition and simplify workflows
Manage and maintain system configuration
Continuously deploy complex software
Perform zero-downtime rolling updates


The Ansible collections can depend on the following pieces of software and their versions:

ansible-core
Python
Python packages
System packages
Other Ansible collections


create a Virtual Environment,Everything you install stays inside that folder and doesn't mess up the rest of your computer.
it is safe, clean and consistent.
in your project directory: 
python3 -m venv venv

Step inside the Bubble (Activate it):
source venv/bin/activate

Install Ansible inside the env
pip install ansible


Install Ansible.
pip install ansible


create a .gitignore and add a list of path
git rm -r --cached .


Think of the Inventory file as Ansible's Address Book.

Before your "Robot Assistant" (Ansible) can do any work, it needs to know two things:

Who am I talking to? (The names or IP addresses of the computers).

How do I get there? (The secret "handshake" or connection method).



ansible.cfg - is ansible configuration file. 
vault is our 