# Cashback Solution (Frontend) - Grupo Boticário

***Código disponibilizado apenas para os Avaliadores***

![](https://i.ibb.co/Y7tCb3n/image.png)

# 0. [TL;DR]

![](https://i.ibb.co/MkSJLFd/2t-Oeq-YEQ7d.gif)

* Primeiro, verifique se todos os pré requisitos de software estão contemplados no ambiente;

* Suba a API. Para isso, navegue até o diretório da API, e execute o comando "dotnet run";

* Abra um Powershell com direitos administrativos, navegue até o diretório onde está a solução com o Front, e execute o comando "yarn install", para que os pacotes sejam baixados e instalados.

  **(Levanta, vai pegar um café :coffee:, estica as pernas :running:, porque, VAI DEMORAR!!!!)**;

* Após isso, entre com o comando "yarn start", para subir a aplicação 

(Caso o Windows pergunte se você autoriza que o Firewall conceda acesso à aplicação, pode permitir);

* Aguarde a aplicação subir. Se tudo correr bem (assim esperamos),
abra seu browser de preferência (sem ser o IE) e navegue até o endereço:
http://localhost:3000;

# 1. Disclamer do Desenvolvedor

Esse, que vos fala, precisa ressalvar alguns pontos importantes para sua avaliação:

* Há melhorias e implementações a serem feitas, no entanto, a ideia foi subir uma solução FRONT, apresentável, funcional, com conceitos mais atuais de desenvolvimento Web utilizando React e o mais importante, agradável ao usuário.

O código pode não ser o ***"crème de la crème"***, mas foi feito com muito ***cuidado e carinho***, para que a parte visual e funcional estejam em perfeita harmonia com o desafio proposto.

# 2. Pré-Requisitos

Para que a aplicação seja executada satisfatóriamente, o ambiente deve contar com:

(Dê preferência sempre pela versão mais atualizada)

* Node.Js (A versão utilizada foi a 12.18.3)

* Npm (Versão utilizada 6.14.6) ou

* Yarn (Versão utilizada 1.22.4)

# 3. Arquitetura

A arquitetura que foi utilizada é a própria do boilerplaite quando criamos um novo projeto React, sendo que:

* As páginas estão separadas por pastas, e cada página tem seu próprio arquivo de estilização (.css);

* Também foram criados compontentes, para ser reutilizado em outros trechos da solução, como por exemplo Page Headers, Inputs de texto entre outros;

* As rotas de acesso às partes da aplicação, estão também separadas no arquivo de routes;

* A parte de comunicação com a API, bem como a validação de Login tamném estão separadas, na pasta de Services;

![](https://i.ibb.co/D84S1ZT/GBCashback-Front.png)

# 4. Segurança

Como solução para a segurança da aplicação, foi utilizado autenticação com JWT Tokens. Esse gerado pela API e enviado ao Front, para que cada método utilizado consuma esse token a cada requisição da API.
Em futura melhoria, o Token armazenado também pode ser usado para validar qual o nível de acesso do usuário (Administrador ou Revendedor)

# 5. UX/UI

A interface do usuário também foi desenvolvida pensanda como um todo, sendo possível utilizar satisfatóriamente tanto no Desktop, como em dispositivos Mobile, sendo automaticamente adaptada ao dispositvo.
Padrões HTML5 e CSS3 também foram amplamente utilizados para que um futuro suporte ou melhoria seja mais fácil de realizar.

# 6. Estrutura de Páginas

* http://localhost:3000 - A Landing page, nosso ponto de entrada na solução;

* http://localhost:3000/Revendedor - Página de cadastro de novos Revendedores;

* http://localhost:3000/Login - Página onde o usuário fará seu Login;

* http://localhost:3000/GBCashback - A Home do sistema, onde o Revendedor escolhe o que fazer (Acessível apenas com login válido);

* http://localhost:3000/CadastroCompras - Página para cadastrar uma compra (Acessível apenas com login válido);

* http://localhost:3000/Compras - Página que lista as compras do Revendedor logado (Acessível apenas com login válido);

* http://localhost:3000/CashbackAcumulado - E por fim, a página que realiza uma consulta à API Externa do Boticário, retornando o Casback acumulado do Revendedor logado (Acessível apenas com login válido);

# 7. Melhorias futuras

Como toda a solução, essa é uma versão inicial. No entanto já podemos sugerir um Backlog de melhorias a serem desenvolvidas, como:

* Controle de Roles (Acesso à outras páginas de acordo com o nível de acesso do revendedor/administrador);

* Consulta de Compras por CPF e filtro de Datas Inicial e Final;

* Edição de dados de Compras existentes e 

* Exclusão de compras préviamente cadastradas;

# 8. Sneak Peek

Abaixo seguem algumas telas para demonstrar a UI da Aplicação.

## 8.1. Versão Mobile

![](https://i.ibb.co/FJX6d66/Geral-Reduzido.png)

## 8.2. Versão Desktop

**Tela de Login**

![](https://i.ibb.co/Y7tCb3n/image.png)

**Cadastro de Revendedor**

![](https://i.ibb.co/ZSMbPX2/1.png)

**Tela de Login**

![](https://i.ibb.co/74N97Z6/2.png)

**Tela Principal**

![](https://i.ibb.co/TMt60rr/3.png)

**Cadastro de Nova Compra**

![](https://i.ibb.co/CmrVdST/4.png)

**Lista de Compras Realizadas**

![](https://i.ibb.co/GnjPWnK/5.png)

**Consulta de Cashback Acumulado**

![](https://i.ibb.co/T0H3mrs/6.png)

# 9. Agradecimentos

A Deus, por todo o conhecimento e sabedoria dada até aqui.

Aos familiares e amigos que apoiaram e ajudaram em todas as horas.

E finalmente, mas sem esquecer, agradeço a oportunidade dada para realizar esse teste, pelo conhecimento adquirido no desenvolvimento (sim, vc sempre aprende algo novo).

Sendo assim, me coloco a disposição para qualquer esclarecimento que possa haver.

# 10. Contato

Ivan Freitas

Senior Developer

https://github.com/IvanMFreitas
