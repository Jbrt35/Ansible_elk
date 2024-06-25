# Ansible_elk
Playbook Ansible pour le déploiement automatisé de la stack ELK. Le playbook comprend également la configuration d'ElasticSearch, de Kibana et de logstash

# Architecture
```
Ansible_elk/
├── elasticsearch.yml
├── logstash.yaml
├── kibana.yml
├── hosts.ini
└── install_elk.yml
```

# Fonctionnement:
Clonage du dépot Github:
```
git clone https://github.com/Jbrt35/Ansible_elk.git
cd Ansible_elk
```
```
sudo ansible-playbook -i hosts.ini install_crowdsec.yml
```
La seule modification que l'utilisateur doit réalisé par lui-même est :
- Si besoin la modification des adresses ip d'elasticsearch et de kibana qui sont par défaut en localhost
