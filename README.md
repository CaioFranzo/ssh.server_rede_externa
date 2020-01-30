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

![sshd.config](https://github.com/CaioFranzo/ssh.server_rede_externa/blob/master/sshd.PNG?raw=true)  

# Configurações no roteador :globe_with_meridians:  

### Entre com o administrador do seu roteador o ip, login e senha padrao dele estara logo em baixo  

![caminho_roteador.config](https://github.com/CaioFranzo/ssh.server_rede_externa/blob/master/caminho_roteador.PNG?raw=true)  

Clique em adicionar novo.

### Preencha as seguintes informações e salve.  

![caminho_roteador2.config](https://github.com/CaioFranzo/ssh.server_rede_externa/blob/master/caminho_roteador2.PNG?raw=true)

# instalando o puTTY :computer:  

### Primeira mente você ira precisar do ip de sua rede, no site [meuip.com.br](https://www.meuip.com.br/).  

### Após isso instale o puTTY Ou instale o Putty [Download aqui](https://www.ssh.com/ssh/putty/download).

### A conexão é feita da seginte forma:  

![Putty.PNG](https://github.com/CaioFranzo/Server_Samba/blob/master/putty.PNG?raw=true)
