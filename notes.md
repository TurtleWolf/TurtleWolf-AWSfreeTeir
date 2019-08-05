  curl -sL https://deb.nodesource.com/setup_10.x -o nodesource_setup.sh
  nano nodesource_setup.sh
  sudo bash nodesource_setup.sh
  node -v
  sudo apt-get install -y nodejs
  node -v
  npm -v
  which yarn
  yarn -v
     
     curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
     echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
     sudo apt-get update && sudo apt-get install yarn