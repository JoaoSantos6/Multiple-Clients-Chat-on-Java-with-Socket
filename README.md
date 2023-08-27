## Multiple Clients Chat on Java with Socket

[[_TOC_]]

### 1. Objetivo
Fazer um servidor Java que conecte usuários em um chat, utilizando a classe Socket com uma mesma porta e o endereço ip localhost.

### 2. Tecnologias utilizadas
- Java 17

### 3. Funcionamento

Ao abrir o prompt de comandos, deve-se direcionar-se à pasta \bin do arquivo e executar o comando
(i)  java server/Server
Esse comando inicializará o servidor. Com o servidor ligado, agora em um outro prompt deve-se
executar o comando
(ii) java client/Client
O script irá pedir o username para identificação aos outros usuários. Pronto, esse será o primeiro 
usuário. Para mais usuários no chat, deve-se abrir um novo prompt sempre e executar o processo (ii).
