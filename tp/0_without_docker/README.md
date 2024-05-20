# logsyash-formation

## Créer la machine de test 
Ce dossier est dédié à création d'une machine de test sans Docker. Pour créer la machine, il faut exécuter cette commande : 
```bash
vagrant up
```
Si vous souhaitez avoir une machine de test avec Logstash de pré-installé:
```bash
export DEPLOY_LOGSTASH=true; vagrant up
```
ATTENTION: cette option ne doit être utilisée que si vous maîtrisez déjà l'installation de Logstash.
## Supprimer la machine de test
Pour supprimer la machine de test indépendament de son contenu: 
```bash
vagrant destroy -f
```