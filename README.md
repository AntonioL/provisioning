ansible-galaxy -r requirements.yml -p ./roles && ansible-playbook -K tatodev.yml && rm -rf ./roles

