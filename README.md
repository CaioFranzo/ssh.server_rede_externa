# Instalando o SSH :dvd:

### !!!IMPORTANTE abrir porta no modem, caso não tenha acesso ligue para seu provedor de internet!!!

### ~$ sudo apt-get install ssh  
Instalando ssh.

# Configurações do SSH :wrench:  
### ~$ sudo service ssh status
Verificar de o ssh esta ligado

### ~$ sudo service ssh start  
Iniciar o ssh, caso esteja desligado  

### ~$ sudo nano /etc/ssh/sshd_config
Desmarque a opção "# port 22" no começo do arquiv, deixando apenas "port 22". Deixando assim:
![sshd.config](https://github.com/murilothink/ssh.server_rede_externa/blob/master/sshd.PNG?raw=true)
