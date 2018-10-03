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
![Imgur](https://i.imgur.com/vImXAt1.jpg)

#### Exportar Arquivo
![Imgur](https://i.imgur.com/oiwhfQD.png)

#### Restaurar Nota
![Imgur](https://i.imgur.com/2DFXIPN.jpg)

#### Cadastro
![Imgur](https://i.imgur.com/Tebtpo1.png)

#### Login de Usuário
![Imgur](https://i.imgur.com/ODqWSBg.png)


## Especificação Suplementar

### Sumário Especificação Suplementar

#### UC08 Cadastro de Usuário

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
3. Usuário insere as informações de cadastro.

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


#### UC09 Login do Usuário

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
3. Usuário insere as informações de Login.

**Fluxo Alternativo 01 (Login com conta google):**
1. Usuário seleciona a opção "Continuar com o Google".
2. Usuário insere um email ou um telefone cadastrado numa conta Google.
3. Usuário insere sua senha correspondente a conta Google.
4. Usuário passa a estar logado e ter acesso a todas as funcionalidades do Evernote.

Regras de Negócio 01

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|Email Google| exemplo@exemplo.com | Sim | Email google valido|
|Senha|padrão google|Sim|Senha valida|

**Fluxo Alternativo 02 (Login com email):**
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


#### Acessar Caderno
**Nome do Caso de Uso:**
Acessar Caderno

**Breve descrição:**
Usuário tem acesso aos cadernos criados.

**Atores:**
Usuario

**Fluxo básico:**
O caso de uso começa quando o usuário abre o aplicativo, seleciona o menu e seleciona a opção "Cadernos".
O usuário visualiza todos os cadernos existentes e tem a opção pesquisar por um determinado caderno.
O caso de uso de encerra.

**Fluxos alternativos:**

FE01 - Não ter acesso à Internet durante o procedimento

O sistema informa a queda de internet.
O usuario não consegue visualizar conteudo que não estão salvos localmente.

**Pré-condições:**
O usuário deverá estar logado no sistema.

**Pós-condições:**
O usuário terá acesso aos seus cadernos.


#### Criar Caderno

1 Nome do Caso de Uso

Criar Caderno
2 Breve descrição

  Usuário cria um novo caderno.
3 Atores

  Usuario
4 Fluxo de eventos
4.1 Fluxo básico

    O caso de uso começa quando o usuário abre o aplicativo, seleciona o menu e seleciona a opção "Cadernos".
    O usuário seleciona a opção de criar um novo caderno.
    O usuário insere o nome do novo caderno.
    O caso de uso de encerra.

4.2 Fluxos alternativos

4.3 Fluxos de Exceção

5 Pré-condições

    O usuário deverá estar logado no sistema.

6 Pós-condições

  O usuário terá um novo caderno criado.



#### Acessar Nota

1. Nome do Caso de Uso

  Acessar Nota

2. Breve descrição

  Usuário tem acesso as notas criadas.

3. Atores

  Usuario do aplicativo

4 Fluxo de eventos
4.1 Fluxo básico

    O caso de uso começa quando o usuário do aplicativo abre o aplicativo, na tela inicial estão disponiveis todas as notas existentes.
    O usuario seleciona a nota que deseja ver.
    O usuário visualiza a nota.
    O caso de uso de encerra.

4.2 Fluxos alternativos
FA01 - Acessar nota por caderno.

    O caso de uso começa quando o usuário abre o aplicativo, seleciona o menu e seleciona a opção "Cadernos".
    O usuário visualiza todos os cadernos existentes e tem a opção pesquisar por um determinado caderno.
    O usuário seleciona o caderno que possui a nota que ele pretende visualizar.
    O usuario seleciona a nota que deseja ver.
    O usuário visualiza a nota.
    O caso de uso de encerra.

FA02 - Acessar nota que foi compartilha com o usuario.

    O caso de uso começa quando o usuário abre o aplicativo, seleciona o menu e seleciona a opção "Compartilhado Comigo".
    O usuário visualiza todos os cadernos e notas que foram compartilhados.
    O usuário seleciona o item que pretende visualizar.
    O usuário visualiza a nota.
    O caso de uso de encerra.


4.3 Fluxos de Exceção
FE01 - Não ter acesso à Internet durante o procedimento

    O sistema informa a queda de internet.
    O usuario não consegue visualizar conteudo que não estão salvos localmente.

5 Pré-condições

    O usuário deverá estar logado no sistema.
    O usuário deverá ter acesso a internet.

6 Pós-condições

  O usuário terá acesso a sua nota.


#### Adicionar Etiqueta

1 Nome do Caso de Uso

  Adicionar Etiqueta

2 Breve descrição

  Permite a um usuário adicionar uma Etiqueta a uma nota.

3 Atores

  Usuario do aplicativo
4 Fluxo de eventos
4.1 Fluxo básico

    O caso de uso começa quando o usuário acessa uma nota.
    O sistema exibe a nota e as opções referentes a nota.
    O usuario seleciona a opção inserir etiqueta.
    O sistema exibe a opção de inserir uma etiqueta que já existe ou criar uma nova etiqueta e a adicionar a nota.
    O usuario insere a etiqueta desejada.
    O fluxo principal é encerrado.

4.2 Fluxos de Exceção
FE01 - Usuario tente adicionar etiqueta já existente

    O fluxo de exceção começa quando a etiqueta inserida pelo usuário já existe para aquela nota.
    O sistema ignora a etiqueta que já está em uso.
    A etiqueta não é replicada.
    O fluxo é encerrado.


5 Pré-condições

    O usuário deverá estar logado no sistema.

6 Pós-condições

  É adicionada uma nova etiqueta.



1 Nome do Caso de Uso

  Adicionar Lembrete
2 Breve descrição

  Permite a um usuário adicionar uma Lembrete a uma nota.
3 Atores

  Usuario do aplicativo
4 Fluxo de eventos
4.1 Fluxo básico

    O caso de uso começa quando o usuário acessa uma nota.
    O sistema exibe a nota e as opções referentes a nota.
    O usuario seleciona a opção lembrete.
    O sistema exibe a opção de definir a data e horario do lembrete.
    O usuario insere o lembrete.
    O fluxo principal é encerrado.

4.2 Fluxos de Exceção
FE01 - Nota já possui um lembrete

    O fluxo de exceção começa quando oo usuarioo seleciona a opção lembrete de uma nota que já possui um lembrete.
    O sistema exibe a opção de alterar a data e horario do lembrete.
    O usuario insere o novo lembrete.
    O fluxo é encerrado.


5 Pré-condições

    O usuário deverá estar logado no sistema.

6 Pós-condições

  É adicionado um novo lembrete.


1 Nome do Caso de Uso

Mudar para plano Premium
2 Breve descrição

  Usuário se torna um membro Premium.
3 Atores

  Usuario
4 Fluxo de eventos
4.1 Fluxo básico

    O caso de uso começa quando o usuário abre o aplicativo.
    O usuário seleciona a opção de atuallizar conta.
    O usuário seleciona a opção premium.
    O usuário seleciona o ciclo de cobrança.
    O usuário confirma os termos e condições e os dados de pagamento.
    O caso de uso de encerra.

4.2 Fluxos alternativos

FE01 - Não ter cartão de credito cadastrado na loja de aplicativos

    O caso de uso começa apos o usuario selecionar o ciclo de cobrança.
    O sistema informa a necessidade de inserir a forma de pagamento.
    O usuario seleciona a opção de inserir um cartão de credito para pagamento.
    O usuario insere os dados do cartão.
    O usuário confirma os termos e condições e os dados de pagamento.
    O caso de uso se encerra.

FE02 - Usuario deseja pagar usando um vale-presente pré-pago

    O caso de uso começa apos o usuario selecionar o ciclo de cobrança.
    O sistema informa a necessidade de inserir a forma de pagamento.
    O sistema exibe a opção de usar um vale-presente pré-pago.
    O usuario insere os dados do vale-presente pré-pago.
    O usuário confirma os termos e condições e os dados de pagamento.
    O caso de uso se encerra.


4.3 Fluxos de Exceção

FE01 - Não ter acesso a Internet durante o procedimento

    O sistema informa a falta de internet.
    O caso de uso se encerra.

FE02 - Não possuir uma das formas de pagamento aceitas.

    O sistema informa as opções existentes.
    O sistema informa como conseguir pagar usando dinheiro em especie.
    O caso de uso se encerra.

5 Pré-condições

    O usuário deverá estar logado no sistema.
    O usuário deverá ter acesso a internet.
    O usuário deverá possuir uma das formas de pagamento aceitas.


6 Pós-condições

  O usuário terá uma conta premium.


## Referências

https://www.evernote.com/Registration.action

https://www.evernote.com/Login.action

https://www.devmedia.com.br/especificacao-de-casos-de-uso-na-pratica/18427

http://www.funpar.ufpr.br:8080/rup/process/modguide/md_ucmod.htm
