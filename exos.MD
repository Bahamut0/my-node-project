
## Prérequis

- récupérer les sources et les envoyer dans la vm
scp "C:/Users/atep/Documents/La Manu/cours-exos/cicd/Exercice5-source.zip" azock@debian:~/cicd/my-node-project/

- installer unzip et dézipper
sudo apt-get update
sudo apt-get install zip unzip
unzip Exercice5-source.zip

- renommer le dossier en source
mv "Exercice 5 - source"/ source

- installer nodejs et vérifier
sudo apt update && apt install nodejs && apt install npm 
node -v
npm -v

- installer jest et vérifier
sudo npm install -g jest

- lancer les tests en manuel pour vérifier que cela fonctionne
jest test/sum.test.js


