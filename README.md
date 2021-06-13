# DevOps Ansible


## gilt für alle Befehle: hhn-devops-ansible.yaml absoluter Pfad sollte angegeben werden oder der Befehl sollte aus demselben Ordner ausgeführt werden, in dem sich die Datei befindet

### zum Ausführen des Playbook wird der folgende Befehl verwendet

ansible-playbook hhn-devops-ansible.yaml

### zum Ausführen des Playbook für die UFW-Rolle (task)

ansible-playbook hhn-devops-ansible.yaml --tags ufw 

### zum Ausführen des Playbook für die SSH-Rolle (task)

ansible-playbook hhn-devops-ansible.yaml --tags ssh

### zum Ausführen des Playbook für die Cron-Rolle (task)

ansible-playbook hhn-devops-ansible.yaml --tags cron

### zum Ausführen des Playbook für beide Rollen SSH und UFW (task)

ansible-playbook hhn-devops-ansible.yaml --tags ufw,ssh



### @Author: Adnan





