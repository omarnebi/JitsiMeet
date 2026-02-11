Jitsi Meet – Custom Version
📌 1️⃣ Prérequis
   Avant de commencer, assure-toi d’avoir :

    -Ubuntu 22.04+ (recommandé)

    -Node.js v22+

    -npm

    -Yarn

    -Git
Installer curl (si non installé)
   -sudo apt update
   -sudo apt install curl -y

Installer NVM
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
  source ~/.bashrc

Installer Node 22
  -nvm install 22
  -nvm use 22
puis vérfier avec node -v pour voir affichage (v22.x.x)

 -Installer Yarn
 -npm install -g yarn

puis vérfier yarn bien isntallé  avec la commande:
  -yarn -v
Cloner le projet
  -git clone https://github.com/omarnebi/JitsiMeet.git
  -cd JitsiMeet
  Supprimer package-lock.json si présent :
    -rm package-lock.json
    -yarn install
Lancer le projet sur 
-make dev

ouvrir le navigateur sur https://localhost:8080








