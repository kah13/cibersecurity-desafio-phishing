# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![Alt text](./passwd.png "Optional title")

1 - O primeiro passo para começar a atividade é abrir a máquina virtual, ir até as configurações na opção "machine", na sequência em "settings" e depois na opção "network" para alterar a placa de rede para a opção "bridget adapter".

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/1%20-%20Network%20Adapter.jpg)

2 e 3 - Deve-se abrir o terminal, que inicia como usuário comum, e alterar para root com o comando "sudo su".


4 e 5 - O próximo passo é iniciar a aplicação setoolkit.


6 - A opção a ser selecionada é de Social-Engeneering Attacks.


7 - Próximo passo é selecionar a opção de Website Attack Vectors.


8 - Deve-se selecionar a opção Credential Harvester Attack Method.


9 - Agora escolha Site Cloner.


10 - Nesse momento o próprio prompt já identifica qual é o IP da máquina e ele será necessário para clonar a URL desejada.


11 - Deve-se colocar a URL a ser clonada, nessa situação a utilizada foi http://www.facebook.com


12 - Após colocar o IP no navegador deve-se fazer uma simulação de e-mail e senha.


13 - Ao tentar ingressar há uma atualização na página onde há o direcionamento automático para a página oficial do Facebook.


14 - Os dados foram capturados com sucesso.


