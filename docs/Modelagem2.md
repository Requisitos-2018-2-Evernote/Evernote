## Casos de Uso

|Versionamento|
|-------|
|[Versões](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2-versões) |

### Sumário Diagramas de Casos de Uso
|ID|Nome  |
|--|--|
| [UCD01](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#administrar-bloqueio-de-senha) | Administrar bloqueio de senha |
| [UCD02](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#evernote-web-clipper) | Evernote web clipper |
| [UCD03](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#criar-lembrete) | Criar Lembrete |
| [UCD04](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#criar-nota) | Criar Nota
| [UCD05](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#pesquisar-nota) | Pesquisar Nota |
| [UCD06](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#exportar-arquivo) | Exportar Arquivo |
| [UCD07](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#restaurar-nota) | Restaurar Nota |
| [UCD08](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#cadastro) | Cadastro |
| [UCD09](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#login-de-usuario) | Login de Usuário |  
| [UCD10](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#lixeira) | Lixeira |


### Administrar bloqueio de senha
![Diagrama Administrar Bloqueio de senha](https://i.imgur.com/KjWuAX5.png)

### Evernote web clipper
![Evernote web clipper](https://i.imgur.com/eQ2Z9j1.png)

### Criar Lembrete
![Imgur](https://i.imgur.com/97fBYxu.jpg?1)

### Criar Nota
![Imgur](https://i.imgur.com/cnwFYOI.jpg?1)

### Pesquisar Nota
![Imgur](https://i.imgur.com/YDJDe41.png)

### Exportar Arquivo
![Imgur](https://i.imgur.com/oiwhfQD.png)

### Restaurar Nota
![Imgur](https://i.imgur.com/2DFXIPN.jpg)

### Lixeira
![Imgur](https://i.imgur.com/B0FfeZn.png)

### Cadastro
![Imgur](https://i.imgur.com/Tebtpo1.png)

### Criar Lembrete v1.1
![Imgur](https://i.imgur.com/EeXjO7c.png)

### Criar Conta
![Imgur](https://i.imgur.com/Ap9e3P5.png)

### Etiquetar
![Imgur](https://i.imgur.com/zo7Ke69.png)

### Compartilhar Mana
![Imgur](https://i.imgur.com/cop6SS9.png)

### Criar Nota v1.1
![Imgur](https://i.imgur.com/MXJ6fPb.png)



### Cadastro
![Imgur](https://i.imgur.com/d9KhGBL.jpg)



### Login de Usuário
![Imgur](https://i.imgur.com/ASguqSU.jpg)

## Especificação de Casos de Uso

| ID                                                                                                                     | Nome                                        |
|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------|
| [UC01](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#cadastro-de-usuario)                  | cadastro de usuario    |
| [UC02](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#login-de-usuario)                  | Login de usuario   |
| [UC03](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#acessar-caderno)                             | Acessar Caderno                             |
| [UC04](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#criar-caderno)                               | Criar Caderno                               |
| [UC05](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#acessar-nota)                                | Acessar Nota                                |
| [UC06](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#adicionar-etiqueta)                          | Adicionar Etiqueta                          |
| [UC07](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#adicionar-lembrete)                          | Adicionar Lembrete                          |
| [UC08](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#mudar-para-plano-premium)                    | Mudar para plano Premium                    |
| [UC09](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#administrar-bloqueio-de-senha_1)               | Administrar bloqueio de senha               |
| [UC10](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#informar-senha-ao-aplicativo)                | Informar senha ao aplicativo                |
| [UC11](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#verificar-senha)                             | Verificar senha                             |
| [UC12](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#notificar-que-a-senha-é-inválida-ao-usuário) | Notificar que a senha é inválida ao usuário |
| [UC13](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#desativar-o-bloqueio-de-senha)               | Desativar o bloqueio de senha               |
| [UC14](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#alterar-a-senha-de-bloqueio)                 | Alterar a senha de bloqueio                 |
| [UC15](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#informar-nova-senha-ao-app)                  | Informar nova senha ao app                  |
| [UC16](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#desbloquear-com-impressao-digital)           | Desbloquear com impressão digital           |
| [UC17](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#alterar-tempo-para-que-seja-informada-a-senha-novamente)| Alterar tempo para que seja informada a senha novamente|
| [UC18](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#informar-tempo-limite-ao-app)                  | Informar tempo limite ao app                |
| [UC19](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#salvar-nota-a-partir-de-pagina-da-web)                  | Salvar nota a partir de página da web       |
| [UC20](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#selecionar-formato-de-captura)                  | Selecionar formato de captura               |
| [UC21](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#adicionar-observacoes)                  | Adicionar observações                       |
| [UC22](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#selecionar-em-qual-caderno-salvar-a-nota)                  | Selecionar em qual caderno salvar a nota    |


### Cadastro de usuário 


**Nome do Caso de Uso:**
Cadastro de usuário 

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

Autor: João Victor


### Login de usuário 


**Nome do Caso de Uso:**
Login de usuário 

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

Autor: João Victor






### Acessar Caderno

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


### Criar Caderno

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

### Acessar Nota

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


### Adicionar Etiqueta

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


### Adicionar Lembrete

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


### Mudar para plano Premium

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

### Administrar bloqueio de senha
**Descrição**

Este caso de uso permite ao usuário acesso às configurações relacionadas ao bloqueio de senha.

**Atores**

Usuário.

**Pré-condições**

O usuário deve estar logado na aplicação e ter conexão com a internet.

**Pós-condições**

O usuário deverá ter alguma alteração relacionada à senha modificada.

**Fluxo principal**

1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O usuário pode Desativar o bloqueio de senha(UC11);
5. O usuário pode Alterar a senha de bloqueio(UC12);
6. O usuário pode Ativar o bloqueio com impressão digital(UC14);
7. O usuário pode Alterar tempo para que seja informada a senha novamente(UC15);
8. O usuário conclui as alterações relacionadas ao bloqueio de senha.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Informar senha ao aplicativo
**Descrição**

Neste caso de uso o usuário informa sua senha ao aplicativo.

**Atores**

Usuário.

**Pré-condições**

O aplicativo pede que informe a senha.

**Pós-condições**

O conteúdo do aplicativo deve ser desbloqueado.

**Fluxo principal**

1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha(UC08).

**Fluxo alternativo**
1. O usuário abre o aplicativo;
2. O usuário precisa informar a senha(UC08).

**Fluxos de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Verificar senha
**Descrição**

Neste caso de uso o aplicativo verifica se a senha é válida.

**Atores**

Evernote.

**Pré-condições**

O aplicativo pede que informe a senha.

**Pós-condições**

Validação da senha.

**Fluxo principal**

1. O usuário abre o aplicativo;
2. O usuário precisa informar a senha(UC08);
3. A senha é verificada(UC09).

**Fluxo alternativo**
1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O aplicativo verifica a senha informada(UC09).

**Fluxos de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Notificar que a senha é inválida ao usuário
**Descrição**

Neste caso de uso o aplicativo notifica ao usuário que a senha informada é inválida.

**Atores**

Evernote.

**Pré-condições**

Validação da senha.

**Pós-condições**

Usuário notificado sobre invalidez da senha.

**Fluxo principal**

1. O usuário abre o aplicativo;
2. O usuário precisa informar a senha(UC08);
3. A senha é verificada(UC09);
4. A senha é inválida e o usuário é notificado(UC10).

**Fluxo alternativo**
1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O aplicativo verifica a senha informada(UC09).
5. A senha é inválida e o usuário é notificado(UC10).

**Fluxos de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Desativar o bloqueio de senha
**Descrição**

Este caso de uso permite ao usuário desativar o bloqueio de senha.

**Atores**

Usuário.

**Pré-condições**

O usuário deverá possuir uma senha de bloqueio.

**Pós-condições**

O usuário deverá ter o bloqueio de senha desativado.

**Fluxo principal**

1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O usuário clica em "Desativar o bloqueio de senha";
5. Senha é desativada e usuário retorna à página anterior.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Alterar a senha de bloqueio
**Descrição**

Este caso de uso permite ao usuário alterar a senha de bloqueio.

**Atores**

Usuário.

**Pré-condições**

O usuário deverá possuir uma senha de bloqueio.

**Pós-condições**

O usuário deverá ter a senha de bloqueio alterada.

**Fluxo principal**

1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O usuário clica em "Alterar a senha de bloqueio";

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Informar nova senha ao app
**Descrição**

Neste caso de uso o usuário informa sua nova senha ao app.

**Atores**

Usuário.

**Pré-condições**

O usuário clica em alterar a senha.

**Pós-condições**

O usuário terá sua senha alterada.

**Fluxo principal**

1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O usuário clica em "Alterar a senha de bloqueio";
5. O usuário informa nova senha ao app(UC13);
6. O usuário tem sua senha alterada.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Desbloquear com impressão digital
**Descrição**

Este caso de uso permite ao usuário ativar desbloqueio com impressão digital.

**Atores**

Usuário.

**Pré-condições**

O usuário deve possuir bloqueio de senha ativo.

**Pós-condições**

O usuário poderá desbloquear o app com a impressão digital.

**Fluxo principal**

1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O usuário clica em "Ativar o bloqueio com impressão digital"(UC14);
5. O desbloqueio com impressão digital é ativo.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Alterar tempo para que seja informada a senha novamente
**Descrição**

Este caso de uso permite ao usuário decidir o intervalo de tempo para que seja necessário informar a senha novamente.

**Atores**

Usuário.

**Pré-condições**

O usuário deverá possuir bloqueio com senha ativo.

**Pós-condições**

Tempo para informar senha novamente alterado.

**Fluxo principal**

1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O usuário clica em "Alterar tempo para que seja informada a senha novamente"(UC15).

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Informar tempo limite ao app
**Descrição**

Neste caso de uso o usuário informa o tempo limite ao app.

**Atores**

Usuário.

**Pré-condições**

O usuário clicar em alterar tempo para que seja informada a senha novamente.

**Pós-condições**

Tempo para informar senha novamente alterado.

**Fluxo principal**

1. O usuário abre configurações;
2. O usuário clica em "Administrar bloqueio de senha";
3. O usuário insere sua senha;
4. O usuário clica em "Alterar tempo para que seja informada a senha novamente"(UC15);
5. O usuário informa tempo limite ao app(UC16);
6. Tempo limite é modificado.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Salvar nota a partir de página da web
**Descrição**

Este caso de uso permite ao usuário salvar uma nota a partir de uma página da web.

**Atores**

Usuário.

**Pré-condições**

O usuário precisa possuir extensão do google chrome instalada e estar logado em sua conta.

**Pós-condições**

Nota salva a partir de página da web.

**Fluxo principal**

1. O usuário clica no ícone da extensão;
2. O usuário pode Adicionar observações à nota;
3. O usuário pode Adicionar etiquetas à nota;
4. O usuário seleciona o formato de captura(UC18);
5. O usuário Seleciona em qual caderno salvar a nota(UC21);
6. Nota é salva.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Selecionar formato de captura
**Descrição**

Neste caso de uso o usuário seleciona formato de captura da nota.

**Atores**

Usuário.

**Pré-condições**

O usuário precisa clicar no ícone da extensão.

**Pós-condições**

Formato de captura selecionado.

**Fluxo principal**

1. O usuário clica no ícone da extensão;
2. O usuário seleciona o formato de captura(UC18);

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Adicionar observações
**Descrição**

Este caso de uso permite ao usuário adicionar observações a uma nota salva pelo Evernote web clipper.

**Atores**

Usuário.

**Pré-condições**

O usuário precisa clicar no ícone da extensão.

**Pós-condições**

Etiqueta adicionada à nota.

**Fluxo principal**

1. O usuário clica no ícone da extensão;
3. O usuário adiciona observação(ões) à nota(UC19);

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Selecionar em qual caderno salvar a nota
**Descrição**

Neste caso de uso o usuário seleciona em qual caderno deseja salvar a nota.

**Atores**

Usuário.

**Pré-condições**

O usuário precisa clicar no ícone da extensão.

**Pós-condições**

Caderno para salvar nota selecionado.

**Fluxo principal**

1. O usuário clica no ícone da extensão;
2. O usuário seleciona em qual caderno salvar a nota(UC20).

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.

## Referências

https://www.evernote.com/Registration.action

https://www.evernote.com/Login.action

https://www.devmedia.com.br/especificacao-de-casos-de-uso-na-pratica/18427

http://www.funpar.ufpr.br:8080/rup/process/modguide/md_ucmod.htm
