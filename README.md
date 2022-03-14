# samansibledemo

1) Execute apt update -y
2) apt install ansible git -y
3) Clone the repo https://github.com/sampath1415/samansibledemo.git
4) make below entry in /etc/ansible/hosts
  [localhost]
  x.x.x.x (your vm ip)
5) navigate to samansibledemo and execute the playbook 'ansible-playbook todoapp.yaml'
6) apt install w3m w3m-img -y (command line browser to access the application)
7) w3m http://0.0.0.0:8000/ (default ip to access the application 0.0.0.0 since we exposed to localhost, we can modify default ip to the required ip's)
