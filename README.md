FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/daniloriquenateste/instaladornovo01.git && sudo chmod -R 777 instaladornovo01 && cd wa-install && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf wa-install && git clone https://github.com/daniloriquenateste/instaladornovo01.git && sudo chmod -R 777 ./wa-install && cd instaladornovo01 && sudo ./install_instancia
```

