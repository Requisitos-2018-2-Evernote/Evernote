## Casos de Uso


### Sumário Casos de Uso
|ID|Nome  |
|--|--|
| [UC01](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#administrar-bloqueio-de-senha) | Administrar bloqueio de senha |
| [UC02](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#evernote-web-clipper) | Evernote web clipper |
| [UC03](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#criar-lembrete) | Criar Lembrete |
| [UC04](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#criar-nota) | Criar Nota
| [UC05](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#pesquisar-nota) | Pesquisar Nota |
| [UC06](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#exportar-arquivo) | Exportar Arquivo |
| [UC07](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#restaurar-nota) | Restaurar Nota |
| [UC08](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#cadastro) | Cadastro |
| [UC10](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#lixeira) | Lixeira |
| [UC09](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#login-de-usuario) | Login de Usuário |  

#### Administrar bloqueio de senha
![Administrar bloqueio de senha](https://i.imgur.com/EFzAWAX.png)

#### Evernote web clipper
![Evernote web clipper](https://i.imgur.com/eQ2Z9j1.png)

#### Criar Lembrete
![Imgur](https://i.imgur.com/97fBYxu.jpg?1)

#### Criar Nota
![Imgur](https://i.imgur.com/cnwFYOI.jpg?1)

#### Pesquisar Nota
![Imgur](https://i.imgur.com/YDJDe41.png)

#### Exportar Arquivo
![Imgur](https://i.imgur.com/oiwhfQD.png)

#### Restaurar Nota
![Imgur](https://i.imgur.com/2DFXIPN.jpg)

#### Lixeira
![Imgur](https://i.imgur.com/B0FfeZn.png)

#### Cadastro
![Imgur](https://i.imgur.com/Tebtpo1.png)

**Descrição:**
Este caso de uso permite que o usuário possa se cadatre e tenha acesso ao sistema. Podendo ser feito a partir de um dispositivo e por meio de uma conta google e/ou email cadastrado.

**Requisito:**
022-Cadastrar usuário -----> Introspecção

**Ator Principal:**
Usuário

**Pré-Requisitos:**
Usuário não deve está cadastrado no evernote.

**Fluxo Principal:**

1. Usuário não cadastrado acessa o evernote por algum dispositivo.

2. Usuário acessa a opção criar conta.

3. Sistema ofereçe as opções de cadastro.

4. Usuário insere as informações de cadastro.

**Fluxo Alternativo 01 (Cadastrar com conta google):**

1. Usuário não cadastrado seleciona a opção "Continuar com o Google".

2. Usuário não cadastrado insere um email ou um telefone cadastrado numa conta Google.

3. Usuário não cadastrado insere sua senha correspondente a conta Google.

4. Sistema cria uma conta evernote com o email e senha de acesso Google.

5. Sistema fornece a opção de verificação de email.

6. Usuário seleciona a opção de verificação de email.

7. Sistema envia um email de confirmação.

8. Usuário acessa email cadastrado e faz a confirmação de cadastro.

9. Usuário não cadastrado passar a ser um usuário com acesso a todas as funcionalidades do pacote Evernote Basic.

 Regras de Negócio 01

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|Email Google| exemplo@exemplo.com | Sim | Email google valido|
|Senha|padrão google|Sim|Senha valida|

**Fluxo Alternativo 02 (Cadastrar com E-mail):**

1. Usuário não cadastrado insere um email valido e não cadastrado.

2. Usuário não cadastrado insere sua senha valida.

3. Sistema cria uma conta evernote com o email e senha escolhidos.

4. Sistema fornece a opção de verificação de email.

5. Usuário seleciona a opção de verificação de email.

6. Sistema envia um email de confirmação.

7. Usuário acessa email cadastrado e faz a confirmação de cadastro.

8. Usuário não cadastrado passar a ser um usuário com acesso a todas as funcionalidades do pacote Evernote Basic.

Regras de Negócio 02

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|E-mail|exemplo@exemplo.com| sim | Email valido|
|Senha|String|sim|Senha valida|


#### Login de Usuário
![Imgur](https://i.imgur.com/ODqWSBg.png)

**Descrição:**  
Este caso de uso permite que o usuário possa se conectar ao sistema. Podendo ser feito a partir de um dispositivo e por meio de uma conta google e/ou email cadastrado.

**Requisito:**
020-Login usuário -----> Introspecção

**Ator Principal:**
Usuário

**Pré-Requisitos:**
Usuário não deve estar logado no evernote.

**Fluxo Principal:**

1. Usuário acessa o evernote por algum dispositivo.

2. Usuário acessa a opção "Entrar".

3. Sistema ofereçe as opções de Login.

4. Usuário insere as informações de Login.

**Fluxo Alternativo 01:**
Login com conta google

1. Usuário seleciona a opção "Continuar com o Google".

2. Usuário insere um email ou um telefone cadastrado numa conta Google.

3. Usuário insere sua senha correspondente a conta Google.

4. Usuário passa a estar logado e ter acesso a todas as funcionalidades do Evernote.

Regras de Negócio 01

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|Email Google| exemplo@exemplo.com | Sim | Email google valido|
|Senha|padrão google|Sim|Senha valida|

**Fluxo Alternativo 02:**
Login com email

1. Usuário insere um email valido e não cadastrado.

2. Usuário insere sua senha valida.

3. Sistema fornece a opção de manter senha.

4. Sistema fornece a opção de verificação de email.

5. Usuário passa a estar logado e ter acesso a todas as funcionalidades do Evernote.


Regras de Negócio 02

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|E-mail|exemplo@exemplo.com| sim | Email valido|
|Senha|String|sim|Senha valida|



## Especificação Suplementar

### Sumário Especificação Suplementar

#### Acessar Caderno

**Nome do Caso de Uso:**
Acessar Caderno

**Descrição:**
Usuário tem acesso aos cadernos criados.

**Atores:**
Usuario

**Fluxo básico:**

1. O caso de uso começa quando o usuário abre o aplicativo, seleciona o menu e seleciona a opção "Cadernos".

2. O usuário visualiza todos os cadernos existentes e tem a opção pesquisar por um determinado caderno.

3. O caso de uso de encerra.

**Fluxo de exceção:**
Não ter acesso à Internet durante o procedimento

1. O sistema informa a queda de internet.

2. O usuario não consegue visualizar conteudo que não estão salvos localmente.

**Pré-condições:**
O usuário deverá estar logado no sistema.

**Pós-condições:**
O usuário terá acesso aos seus cadernos.


#### Criar Caderno

**Nome do Caso de Uso:**
Criar Caderno

**Descrição:**
Usuário cria um novo caderno.

**Atores:** 
Usuario

**Fluxo básico:**

1. O caso de uso começa quando o usuário abre o aplicativo, seleciona o menu e seleciona a opção "Cadernos".

2. O usuário seleciona a opção de criar um novo caderno.

3. O usuário insere o nome do novo caderno.

4. O caso de uso de encerra.

**Fluxos alternativos:**


**Pré-condições:**
O usuário deverá estar logado no sistema.

**Pós-condições:**
O usuário terá um novo caderno criado.

#### Acessar Nota

**Nome do Caso de Uso:**
Acessar Nota

**Descrição:**
Usuário tem acesso as notas criadas.

**Atores:**
Usuario do aplicativo

**Fluxo básico:**

1. O caso de uso começa quando o usuário do aplicativo abre o aplicativo, na tela inicial estão disponiveis todas as notas existentes.

2. O usuario seleciona a nota que deseja ver.

3. O usuário visualiza a nota.

4. O caso de uso de encerra.

**Fluxo alternativo 01:**
Acessar nota por caderno.

1. O caso de uso começa quando o usuário abre o aplicativo, seleciona o menu e seleciona a opção "Cadernos".

2. O usuário visualiza todos os cadernos existentes e tem a opção pesquisar por um determinado caderno.

3. O usuário seleciona o caderno que possui a nota que ele pretende visualizar.

4. O usuario seleciona a nota que deseja ver.

5. O usuário visualiza a nota.

6. O caso de uso de encerra.

**Fluxo alternativo 02:**
Acessar nota que foi compartilha com o usuario.

1. O caso de uso começa quando o usuário abre o aplicativo, seleciona o menu e seleciona a opção "Compartilhado Comigo".

2. O usuário visualiza todos os cadernos e notas que foram compartilhados.

3. O usuário seleciona o item que pretende visualizar.

4. O usuário visualiza a nota.

5. O caso de uso de encerra.


**Fluxo de Exceção:**
Não ter acesso à Internet durante o procedimento

1. O sistema informa a queda de internet.

2. O usuario não consegue visualizar conteudo que não estão salvos localmente.

**Pré-condições:**

1. O usuário deverá estar logado no sistema.

2. O usuário deverá ter acesso a internet.

**Pós-condições:**
O usuário terá acesso a sua nota.


#### Adicionar Etiqueta

**Nome do Caso de Uso:**
Adicionar Etiqueta

**Descrição:**
Permite a um usuário adicionar uma Etiqueta a uma nota.

**Atores:**
Usuario do aplicativo

**Fluxo básico:**

1. O sistema exibe a nota e as opções referentes a nota.

2. O usuario seleciona a opção inserir etiqueta.

3. O sistema exibe a opção de inserir uma etiqueta que já existe ou criar uma nova etiqueta e a adicionar a nota.

4. O usuario insere a etiqueta desejada.

5. O fluxo principal é encerrado.

**Fluxos de Exceção:**
Usuario tenta adicionar etiqueta já existente

1. O fluxo de exceção começa quando a etiqueta inserida pelo usuário já existe para aquela nota.

2. O sistema ignora a etiqueta que já está em uso.

3. A etiqueta não é replicada.

4. O fluxo é encerrado.


**Pré-condições:**
O usuário deverá estar logado no sistema.

**Pós-condições:**
É adicionada uma nova etiqueta.


#### Adicionar Lembrete

**Nome do Caso de Uso:**
Adicionar Lembrete

**Descrição:**
Permite a um usuário adicionar uma Lembrete a uma nota.

**Atores:**
Usuario do aplicativo

**Fluxo básico:**

1. O caso de uso começa quando o usuário acessa uma nota.

2. O sistema exibe a nota e as opções referentes a nota.

3. O usuario seleciona a opção lembrete.

4. O sistema exibe a opção de definir a data e horario do lembrete.

5. O usuario insere o lembrete.

6. O fluxo principal é encerrado.

**Fluxos de Exceção**
Nota já possui um lembrete

1. O fluxo de exceção começa quando oo usuarioo seleciona a opção lembrete de uma nota que já possui um lembrete.

2. O sistema exibe a opção de alterar a data e horario do lembrete.

3. O usuario insere o novo lembrete.

4. O fluxo é encerrado.

**Pré-condições**
O usuário deverá estar logado no sistema.

**Pós-condições**
É adicionado um novo lembrete.


#### Mudar para plano Premium

**Nome do Caso de Uso**
Mudar para plano Premium

**Descrição**
Usuário se torna um membro Premium.

**Atores**
Usuario

**Fluxo básico**

1. O caso de uso começa quando o usuário abre o aplicativo.

2. O usuário seleciona a opção de atuallizar conta.

3. O usuário seleciona a opção premium.

4. O usuário seleciona o ciclo de cobrança.

5. O usuário confirma os termos e condições e os dados de pagamento.

6. O caso de uso de encerra.

**Fluxo alternativo 01:**
Não ter cartão de credito cadastrado na loja de aplicativos

1. O caso de uso começa apos o usuario selecionar o ciclo de cobrança.

2. O sistema informa a necessidade de inserir a forma de pagamento.

3. O usuario seleciona a opção de inserir um cartão de credito para pagamento.

4. O usuario insere os dados do cartão.

5. O usuário confirma os termos e condições e os dados de pagamento.

6. O caso de uso se encerra.

**Fluxo alternativo 02:**
Usuario deseja pagar usando um vale-presente pré-pago

1. O caso de uso começa apos o usuario selecionar o ciclo de cobrança.

2. O sistema informa a necessidade de inserir a forma de pagamento.

3. O sistema exibe a opção de usar um vale-presente pré-pago.

4. O usuario insere os dados do vale-presente pré-pago.

5. O usuário confirma os termos e condições e os dados de pagamento.

6. O caso de uso se encerra.


**Fluxo de Exceção 01:**
Não ter acesso a Internet durante o procedimento

1. O sistema informa a falta de internet.

2. O caso de uso se encerra.

**Fluxo de Exceção 02:**
Não possuir uma das formas de pagamento aceitas.

1. O sistema informa as opções existentes.

2. O sistema informa como conseguir pagar usando dinheiro em especie.

3. O caso de uso se encerra.

**Pré-condições:**

1. O usuário deverá estar logado no sistema.

2. O usuário deverá ter acesso a internet.

3. O usuário deverá possuir uma das formas de pagamento aceitas.


**Pós-condições:**
O usuário terá uma conta premium.


## Referências

https://www.evernote.com/Registration.action

https://www.evernote.com/Login.action

https://www.devmedia.com.br/especificacao-de-casos-de-uso-na-pratica/18427

http://www.funpar.ufpr.br:8080/rup/process/modguide/md_ucmod.htm
