# React Native - First Project

React Native uma biblioteca criada pelo Facebook que escreve código Javascript e constrói uma aplicação nativa (não híbrida) para iOS e Android.

## Ambiente de Desenvolvimento no Linux

### Android

Dependências: Node, JDK e Android Studio (ou aparelho físico).

```
sudo apt-get install curl

curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs

sudo npm install -g react-native-cli

sudo apt-get install default-jdk
```

Para baixar depências do projeto usar o comando `npm install` no root do projeto.

### iOS

Não é possível configurar este ambiente de desenvolvimento no Linux.

## Criando o projeto

```
react-native init FirstProject

cd FirstProject
react-native run-android
```

## Referências

https://www.digitalocean.com/community/tutorials/como-instalar-o-node-js-no-ubuntu-16-04-pt  
http://code.rocketseat.com.br/assets/files/ambiente-de-desenvolvimento-rn.pdf
