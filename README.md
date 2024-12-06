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

O primeiro passo para começar a atividade é abrir a máquina virtual, ir até as configurações na opção "machine", na sequência em "settings" e depois na opção "network" para alterar a placa de rede para a opção "bridget adapter".

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/1%20-%20Network%20Adapter.jpg)

Deve-se abrir o terminal, que inicia como usuário comum, e alterar para root com o comando "sudo su".

![Passo 3](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/3%20-%20Root.jpg)

O próximo passo é iniciar a aplicação setoolkit.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/4%20-%20Setoolkit.jpg)

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/5%20-%20Setoolkit.jpg)

6 - A opção a ser selecionada é de Social-Engeneering Attacks.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/5%20-%20Social%20Engeneering%20Attacks.jpg)

7 - Próximo passo é selecionar a opção de Website Attack Vectors.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/6%20-%20Website%20Attack%20Vectors.jpg)

8 - Deve-se selecionar a opção Credential Harvester Attack Method.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/7%20-%20Credential%20Harvester%20Attack%20Method.jpg)

9 - Agora escolha Site Cloner.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/8%20-%20Site%20Cloner.jpg)

10 - Nesse momento o próprio prompt já identifica qual é o IP da máquina e ele será necessário para clonar a URL desejada.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/9%20-%20IP%20M%C3%A1quina.jpg)

11 - Deve-se colocar a URL a ser clonada, nessa situação a utilizada foi http://www.facebook.com

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/10%20-%20URL%20Clone.jpg)

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/11%20-%20Link%20pronto.jpg)

12 - Após colocar o IP no navegador deve-se fazer uma simulação de e-mail e senha.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/12%20-%20Acesso%20link%20clonado.jpg)

13 - Ao tentar ingressar há uma atualização na página onde há o direcionamento automático para a página oficial do Facebook.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/Glitch%20-.jpg)

14 - Os dados foram capturados com sucesso.

![Texto Alternativo](https://github.com/kah13/cibersecurity-desafio-phishing/blob/master/Passo%20a%20passo/14%20-%20Captura%20de%20senha.jpg)


