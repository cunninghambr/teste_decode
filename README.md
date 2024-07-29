##REQUESITOS 

-UBUNTU 20.04 (OBRIGATORIO)
-VM COM MINIMO: 2CPU 4GB RAM
-VM COM RECOMENDADO: 4CPU 6GB RAM

## INSTALAÇÃO VPS ##

 sudo apt install -y git && git clone https://github.com/EdsonVDN/teste_decode.git install_whaticket && sudo chmod -R 777 install_whaticket && cd install_whaticket  && sudo ./install_whaticketsaas


## CRIAR SUBDOMINIO E APONTAR PARA O IP DA SUA VPS ##

FRONTEND_URL: app.seudominio.com
BACKEND_URL:  api.seudominio.com

## CHECAR PROPAGAÇÃO DO DOMÍNIO ##

https://dnschecker.org/

## COPIAR A PASTA PARA ROOT E RODAR OS COMANDOS ABAIXO ##

sudo chmod +x ./whaticket_install_45v/whaticketsaas
cd ./whaticket_install_45v
sudo ./whaticketsaas

===================================================

login: admin@admin.com
senha: 123456