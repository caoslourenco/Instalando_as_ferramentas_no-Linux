# Instalando_as_ferramentas_no-Linux   |||| em construção 
Projeto
Como inicializar um cluster no Windows
Como inicializar um cluster no Linux
Como fazer a instalação manual do kubectl
Como inicializar no Google Cloud Platform

---------------------

Os comandos necessários para a instalação e inicialização do cluster no Linux podem ser obtidos abaixo:

Primeiro para o kubectl:

sudo apt-get install curl -y
curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl"
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl
Agora para o minikube:

curl -Lo minikube https://storage.googleapis.com/minikube/releases/v1.12.1/minikube-linux-amd64 \ && chmod +x minikube
sudo install minikube /usr/local/bin/

------------

Vocês já ouviram falar sobre o Google Cloud?
Documentação oficial da Google:

Programa Gratuito do Google

https://cloud.google.com/free/docs/free-cloud-features?hl=pt-br#kubernetes-engine


