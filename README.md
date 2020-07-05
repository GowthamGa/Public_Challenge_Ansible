# Public_Challenge_Ansible
Ansible script to install Softwares

Step 1: Create Hosts Inventory File.

Step 2. Configure SSH between Ansible workstation and client servers.

Step 3. Check Ping connectivity to all clients.

Step 4. Create a role to install all these required softwares in redhat Linux.

Step 5. Copy the scripts to respective folder structure inside the role.

$ tree playbooks/mysql/
playbooks/mysql/
├── defaults
│   └── main.yml
├── files
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── README.md
├── tasks
│   ├── install.yml
│   ├── main.yml
│   ├── mysql.yml
│   └── webserver.yml
├── templates
├── tests
└── vars
    ├── main.yml
    └── vars.yml


Step 6. Do run the playbook in Dry-Run to check if all syntax are good.

Step 7. Run the playbook.
