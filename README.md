Anisble 2.3 playbook to install nginx, update nginx.conf, place index.html, and rolling restart nginx if needed

Hosts must be defined in hosts file

Installing and configuring nginx has been separated into two roles to allow for parallel installs and serial restarts

To run:
	`ansible-playbook -i hosts site.yml`

See sample.log for an example run
