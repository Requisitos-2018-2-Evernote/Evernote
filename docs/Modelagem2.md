## Casos de Uso

|Versionamento|
|-------|
|[Versões](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2-versões) |

### Sumário Diagramas de Casos de Uso
|ID|Nome  |
|--|--|
| [UCD01](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#administrar-bloqueio-de-senha) | Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) |
| [UCD02](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#evernote-web-clipper) | [Evernote Web Clipper](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#evernote-web-clipper) |
| [UCD03](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#criar-lembrete) | Criar [Lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete) |
| [UCD04](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#criar-nota) | Criar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)
| [UCD05](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#pesquisar-nota) | Pesquisar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) |
| [UCD06](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#exportar-arquivo) | Exportar Arquivo |
| [UCD07](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#restaurar-nota) | Restaurar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) |
| [UCD08](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#cadastro) | Cadastro |
| [UCD09](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#login-de-usuario) | Login de [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) |  
| [UCD10](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#lixeira) | Lixeira |


### Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)
![Diagrama Administrar Bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)](https://i.imgur.com/KjWuAX5.png)

### [Evernote Web Clipper](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#evernote-web-clipper)
![Evernote web clipper](https://i.imgur.com/eQ2Z9j1.png)

### Criar [Lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete)
![Imgur](https://i.imgur.com/97fBYxu.jpg?1)

### Criar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)
![Imgur](https://i.imgur.com/cnwFYOI.jpg?1)

### Pesquisar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)
![Imgur](https://i.imgur.com/YDJDe41.png)

### Exportar Arquivo
![Imgur](https://i.imgur.com/oiwhfQD.png)

### Restaurar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)
![Imgur](https://i.imgur.com/2DFXIPN.jpg)

### Lixeira
![Imgur](https://i.imgur.com/B0FfeZn.png)

### Cadastro
![Imgur](https://i.imgur.com/Tebtpo1.png)

### Criar [Lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete) v1.1
![Imgur](https://i.imgur.com/EeXjO7c.png)

### Criar Conta
![Imgur](https://i.imgur.com/Ap9e3P5.png)

### Etiquetar
![Imgur](https://i.imgur.com/zo7Ke69.png)

### [Compartilhar](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#compartilhar) Mana
![Imgur](https://i.imgur.com/cop6SS9.png)

### Criar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) v1.1
![Imgur](https://i.imgur.com/MXJ6fPb.png)



### Cadastro
![Imgur](https://i.imgur.com/d9KhGBL.jpg)



### Login de [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario)
![Imgur](https://i.imgur.com/ASguqSU.jpg)

## Especificação de Casos de Uso

| ID                                                                                                                     | Nome                                        |
|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------|
| [UC01](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#cadastro-de-usuario)                  | cadastro de usuario    |
| [UC02](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#login-de-usuario)                  | Login de usuario   |
| [UC03](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#acessar-caderno)                             | Acessar [Caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno)                             |
| [UC04](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#criar-caderno)                               | Criar [Caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno)                               |
| [UC05](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#acessar-nota)                                | Acessar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)                                |
| [UC06](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#adicionar-etiqueta)                          | Adicionar [Etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta)                          |
| [UC07](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#adicionar-lembrete)                          | Adicionar [Lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete)                          |
| [UC08](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#mudar-para-plano-premium)                    | Mudar para plano Premium                    |
| [UC09](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#administrar-bloqueio-de-senha_1)               | Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)               |
| [UC10](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#informar-senha-ao-aplicativo)                | Informar [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ao [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)                |
| [UC11](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#verificar-senha)                             | Verificar [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)                             |
| [UC12](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#notificar-que-a-senha-é-inválida-ao-usuário) | Notificar que a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) é inválida ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) |
| [UC13](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#desativar-o-bloqueio-de-senha)               | Desativar o bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)               |
| [UC14](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#alterar-a-senha-de-bloqueio)                 | Alterar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio                 |
| [UC15](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#informar-nova-senha-ao-app)                  | Informar nova [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ao [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)                  |
| [UC16](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#desbloquear-com-impressao-digital)           | Desbloquear com impressão digital           |
| [UC17](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#alterar-tempo-para-que-seja-informada-a-senha-novamente)| Alterar tempo para que seja informada a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente|
| [UC18](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#informar-tempo-limite-ao-app)                  | Informar tempo limite ao [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)                |
| [UC19](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#salvar-nota-a-partir-de-pagina-da-web)                  | Salvar [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) a partir de página da web       |
| [UC20](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#selecionar-formato-de-captura)                  | Selecionar formato de [Captura](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#captura)               |
| [UC21](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#adicionar-observacoes)                  | Adicionar observações                       |
| [UC22](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem2/#selecionar-em-qual-caderno-salvar-a-nota)                  | Selecionar em qual [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) salvar a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)    |


### Cadastro de [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) 


**Nome do Caso de Uso:**
Cadastro de [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) 

**Descrição:**
Este caso de uso permite que o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) possa se cadatre e tenha acesso ao sistema. Podendo ser feito a partir de um dispositivo e por meio de uma conta google e/ou email cadastrado.

**Requisito:**
022-Cadastrar [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) -----> Introspecção

**Ator Principal:**
Usuário

**Pré-Requisitos:**
Usuário não deve está cadastrado no evernote.

**Fluxo Principal:**

1. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não cadastrado acessa o evernote por algum dispositivo.

2. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa a opção criar conta.

3. Sistema ofereçe as opções de cadastro.

4. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere as informações de cadastro.

**Fluxo Alternativo 01 (Cadastrar com conta google):**

1. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não cadastrado seleciona a opção "Continuar com o Google".

2. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não cadastrado insere um email ou um telefone cadastrado numa conta Google.

3. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não cadastrado insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) correspondente a conta Google.

4. Sistema cria uma conta evernote com o email e [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de acesso Google.

5. Sistema fornece a opção de verificação de email.

6. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona a opção de verificação de email.

7. Sistema envia um email de confirmação.

8. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa email cadastrado e faz a confirmação de cadastro.

9. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não cadastrado passar a ser um [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) com acesso a todas as funcionalidades do pacote Evernote Basic.

 Regras de Negócio 01

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|Email Google| exemplo@exemplo.com | Sim | Email google valido|
|Senha|padrão google|Sim|Senha valida|

**Fluxo Alternativo 02 (Cadastrar com E-mail):**

1. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não cadastrado insere um email valido e não cadastrado.

2. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não cadastrado insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) valida.

3. Sistema cria uma conta evernote com o email e [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) escolhidos.

4. Sistema fornece a opção de verificação de email.

5. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona a opção de verificação de email.

6. Sistema envia um email de confirmação.

7. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa email cadastrado e faz a confirmação de cadastro.

8. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não cadastrado passar a ser um [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) com acesso a todas as funcionalidades do pacote Evernote Basic.

Regras de Negócio 02

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|E-mail|exemplo@exemplo.com| sim | Email valido|
|Senha|String|sim|Senha valida|

Autor: João Victor


### Login de [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) 


**Nome do Caso de Uso:**
Login de [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) 

**Descrição:**  
Este caso de uso permite que o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) possa se conectar ao sistema. Podendo ser feito a partir de um dispositivo e por meio de uma conta google e/ou email cadastrado.

**Requisito:**
020-Login [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) -----> Introspecção

**Ator Principal:**
Usuário

**Pré-Requisitos:**
Usuário não deve estar logado no evernote.

**Fluxo Principal:**

1. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa o evernote por algum dispositivo.

2. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa a opção "Entrar".

3. Sistema ofereçe as opções de Login.

4. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere as informações de Login.

**Fluxo Alternativo 01:**
Login com conta google

1. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona a opção "Continuar com o Google".

2. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere um email ou um telefone cadastrado numa conta Google.

3. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) correspondente a conta Google.

4. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) passa a estar logado e ter acesso a todas as funcionalidades do Evernote.

Regras de Negócio 01

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|Email Google| exemplo@exemplo.com | Sim | Email google valido|
|Senha|padrão google|Sim|Senha valida|

**Fluxo Alternativo 02:**
Login com email

1. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere um email valido e não cadastrado.

2. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) valida.

3. Sistema fornece a opção de manter [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

4. Sistema fornece a opção de verificação de email.

5. [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) passa a estar logado e ter acesso a todas as funcionalidades do Evernote.


Regras de Negócio 02

| Campo | Formato | Obrigatoriedade | Valor |
|-------------------|------------------|------------|-----------|
|E-mail|exemplo@exemplo.com| sim | Email valido|
|Senha|String|sim|Senha valida|

Autor: João Victor






### Acessar [Caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno)

**Nome do Caso de Uso:**
Acessar [Caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno)

**Descrição:**
Usuário tem acesso aos [cadernos](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) criados.

**Atores:**
Usuario

**Fluxo básico:**

1. O caso de uso começa quando o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao), seleciona o menu e seleciona a opção "Cadernos".

2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) visualiza todos os [cadernos](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) existentes e tem a opção pesquisar por um determinado [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno).

3. O caso de uso de encerra.

**Fluxo de exceção:**
Não ter acesso à Internet durante o procedimento

1. O sistema informa a queda de internet.

2. O usuario não consegue visualizar conteudo que não estão salvos localmente.

**Pré-condições:**
O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá estar logado no sistema.

**Pós-condições:**
O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) terá acesso aos seus [cadernos](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno).


### Criar [Caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno)

**Nome do Caso de Uso:**
Criar [Caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno)

**Descrição:**
Usuário cria um novo [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno).

**Atores:** 
Usuario

**Fluxo básico:**

1. O caso de uso começa quando o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao), seleciona o menu e seleciona a opção "Cadernos".

2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona a opção de criar um novo [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno).

3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere o nome do novo [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno).

4. O caso de uso de encerra.

**Fluxos alternativos:**


**Pré-condições:**
O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá estar logado no sistema.

**Pós-condições:**
O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) terá um novo [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) criado.

### Acessar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)

**Nome do Caso de Uso:**
Acessar [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)

**Descrição:**
Usuário tem acesso as [notas](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) criadas.

**Atores:**
Usuario do [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)

**Fluxo básico:**

1. O caso de uso começa quando o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) do [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao), na tela inicial estão disponiveis todas as [notas](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) existentes.

2. O usuario seleciona a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) que deseja ver.

3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) visualiza a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

4. O caso de uso de encerra.

**Fluxo alternativo 01:**
Acessar [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) por [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno).

1. O caso de uso começa quando o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao), seleciona o menu e seleciona a opção "Cadernos".

2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) visualiza todos os [cadernos](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) existentes e tem a opção pesquisar por um determinado [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno).

3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona o [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) que possui a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) que ele pretende visualizar.

4. O usuario seleciona a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) que deseja ver.

5. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) visualiza a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

6. O caso de uso de encerra.

**Fluxo alternativo 02:**
Acessar [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) que foi compartilha com o usuario.

1. O caso de uso começa quando o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao), seleciona o menu e seleciona a opção "Compartilhado Comigo".

2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) visualiza todos os [cadernos](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) e [notas](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) que foram compartilhados.

3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona o item que pretende visualizar.

4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) visualiza a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

5. O caso de uso de encerra.


**Fluxo de Exceção:**
Não ter acesso à Internet durante o procedimento

1. O sistema informa a queda de internet.

2. O usuario não consegue visualizar conteudo que não estão salvos localmente.

**Pré-condições:**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá estar logado no sistema.

2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá ter acesso a internet.

**Pós-condições:**
O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) terá acesso a sua [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).


### Adicionar [Etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta)

**Nome do Caso de Uso:**
Adicionar [Etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta)

**Descrição:**
Permite a um [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) adicionar uma [Etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) a uma [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

**Atores:**
Usuario do [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)

**Fluxo básico:**

1. O sistema exibe a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) e as opções referentes a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

2. O usuario seleciona a opção inserir [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta).

3. O sistema exibe a opção de inserir uma [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) que já existe ou criar uma nova [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) e a adicionar a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

4. O usuario insere a [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) desejada.

5. O fluxo principal é encerrado.

**Fluxos de Exceção:**
Usuario tenta adicionar [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) já existente

1. O fluxo de exceção começa quando a [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) inserida pelo [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) já existe para aquela [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

2. O sistema ignora a [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) que já está em uso.

3. A [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) não é replicada.

4. O fluxo é encerrado.


**Pré-condições:**
O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá estar logado no sistema.

**Pós-condições:**
É adicionada uma nova [etiqueta](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta).


### Adicionar [Lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete)

**Nome do Caso de Uso:**
Adicionar [Lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete)

**Descrição:**
Permite a um [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) adicionar uma [Lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete) a uma [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

**Atores:**
Usuario do [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)

**Fluxo básico:**

1. O caso de uso começa quando o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa uma [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

2. O sistema exibe a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) e as opções referentes a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

3. O usuario seleciona a opção [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete).

4. O sistema exibe a opção de definir a data e horario do [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete).

5. O usuario insere o [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete).

6. O fluxo principal é encerrado.

**Fluxos de Exceção**
Nota já possui um [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete)

1. O fluxo de exceção começa quando oo usuarioo seleciona a opção [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete) de uma [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) que já possui um [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete).

2. O sistema exibe a opção de alterar a data e horario do [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete).

3. O usuario insere o novo [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete).

4. O fluxo é encerrado.

**Pré-condições**
O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá estar logado no sistema.

**Pós-condições**
É adicionado um novo [lembrete](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#lembrete).


### Mudar para plano Premium

**Nome do Caso de Uso**
Mudar para plano Premium

**Descrição**
Usuário se torna um membro Premium.

**Atores**
Usuario

**Fluxo básico**

1. O caso de uso começa quando o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).

2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona a opção de atuallizar conta.

3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona a opção premium.

4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona o ciclo de cobrança.

5. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) confirma os termos e condições e os dados de pagamento.

6. O caso de uso de encerra.

**Fluxo alternativo 01:**
Não ter cartão de credito cadastrado na loja de aplicativos

1. O caso de uso começa apos o usuario selecionar o ciclo de cobrança.

2. O sistema informa a necessidade de inserir a forma de pagamento.

3. O usuario seleciona a opção de inserir um cartão de credito para pagamento.

4. O usuario insere os dados do cartão.

5. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) confirma os termos e condições e os dados de pagamento.

6. O caso de uso se encerra.

**Fluxo alternativo 02:**
Usuario deseja pagar usando um vale-presente pré-pago

1. O caso de uso começa apos o usuario selecionar o ciclo de cobrança.

2. O sistema informa a necessidade de inserir a forma de pagamento.

3. O sistema exibe a opção de usar um vale-presente pré-pago.

4. O usuario insere os dados do vale-presente pré-pago.

5. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) confirma os termos e condições e os dados de pagamento.

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

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá estar logado no sistema.

2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá ter acesso a internet.

3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá possuir uma das formas de pagamento aceitas.


**Pós-condições:**
O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) terá uma conta premium.

### Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)
**Descrição**

Este caso de uso permite ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acesso às configurações relacionadas ao bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deve estar logado na [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) e ter conexão com a internet.

**Pós-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá ter alguma alteração relacionada à [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) modificada.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode Desativar o bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)(UC11);
5. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode Alterar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio(UC12);
6. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode Ativar o bloqueio com impressão digital(UC14);
7. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode Alterar tempo para que seja informada a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente(UC15);
8. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) conclui as alterações relacionadas ao bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Informar [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ao [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)
**Descrição**

Neste caso de uso o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) informa sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ao [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).

**Atores**

Usuário.

**Pré-condições**

O [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) pede que informe a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Pós-condições**

O conteúdo do [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) deve ser desbloqueado.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)(UC08).

**Fluxo alternativo**
1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao);
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) precisa informar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)(UC08).

**Fluxos de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Verificar [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)
**Descrição**

Neste caso de uso o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) verifica se a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) é válida.

**Atores**

Evernote.

**Pré-condições**

O [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) pede que informe a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Pós-condições**

Validação da [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao);
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) precisa informar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)(UC08);
3. A [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) é verificada(UC09).

**Fluxo alternativo**
1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) verifica a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) informada(UC09).

**Fluxos de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Notificar que a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) é inválida ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario)
**Descrição**

Neste caso de uso o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) notifica ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) que a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) informada é inválida.

**Atores**

Evernote.

**Pré-condições**

Validação da [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Pós-condições**

Usuário notificado sobre invalidez da [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao);
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) precisa informar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)(UC08);
3. A [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) é verificada(UC09);
4. A [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) é inválida e o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) é notificado(UC10).

**Fluxo alternativo**
1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [aplicativo](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) verifica a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) informada(UC09).
5. A [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) é inválida e o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) é notificado(UC10).

**Fluxos de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Desativar o bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)
**Descrição**

Este caso de uso permite ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) desativar o bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá possuir uma [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio.

**Pós-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá ter o bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) desativado.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Desativar o bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
5. [Senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) é desativada e [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) retorna à página anterior.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Alterar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio
**Descrição**

Este caso de uso permite ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) alterar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio.

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá possuir uma [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio.

**Pós-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá ter a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio alterada.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Alterar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio";

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Informar nova [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ao [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)
**Descrição**

Neste caso de uso o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) informa sua nova [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ao [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em alterar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).

**Pós-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) terá sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) alterada.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Alterar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) de bloqueio";
5. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) informa nova [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ao [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)(UC13);
6. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) tem sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) alterada.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Desbloquear com impressão digital
**Descrição**

Este caso de uso permite ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) ativar desbloqueio com impressão digital.

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deve possuir bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ativo.

**Pós-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) poderá desbloquear o [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) com a impressão digital.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Ativar o bloqueio com impressão digital"(UC14);
5. O desbloqueio com impressão digital é ativo.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Alterar tempo para que seja informada a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente
**Descrição**

Este caso de uso permite ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) decidir o intervalo de tempo para que seja necessário informar a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente.

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deverá possuir bloqueio com [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) ativo.

**Pós-condições**

Tempo para informar [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente alterado.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Alterar tempo para que seja informada a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente"(UC15).

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Informar tempo limite ao [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)
**Descrição**

Neste caso de uso o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) informa o tempo limite ao [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clicar em alterar tempo para que seja informada a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente.

**Pós-condições**

Tempo para informar [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente alterado.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre configurações;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Administrar bloqueio de [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso)";
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insere sua [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso);
4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Alterar tempo para que seja informada a [senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) novamente"(UC15);
5. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) informa tempo limite ao [app](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao)(UC16);
6. Tempo limite é modificado.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Salvar [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) a partir de página da web
**Descrição**

Este caso de uso permite ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) salvar uma [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) a partir de uma página da web.

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) precisa possuir extensão do google chrome instalada e estar logado em sua conta.

**Pós-condições**

Nota salva a partir de página da web.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica no ícone da extensão;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode Adicionar observações à [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota);
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode Adicionar [etiquetas](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta) à [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota);
4. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona o formato de [Captura](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#captura)(UC18);
5. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) Seleciona em qual [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) salvar a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)(UC21);
6. [Nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) é salva.

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Selecionar formato de [Captura](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#captura)
**Descrição**

Neste caso de uso o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona formato de [Captura](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#captura) da [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) precisa clicar no ícone da extensão.

**Pós-condições**

Formato de [Captura](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#captura) selecionado.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica no ícone da extensão;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona o formato de [Captura](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#captura)(UC18);

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Adicionar observações
**Descrição**

Este caso de uso permite ao [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) adicionar observações a uma [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) salva pelo [Evernote Web Clipper](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#evernote-web-clipper).

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) precisa clicar no ícone da extensão.

**Pós-condições**

Etiqueta adicionada à [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica no ícone da extensão;
3. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) adiciona observação(ões) à [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)(UC19);

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.


### Selecionar em qual [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) salvar a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)
**Descrição**

Neste caso de uso o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona em qual [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) deseja salvar a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).

**Atores**

Usuário.

**Pré-condições**

O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) precisa clicar no ícone da extensão.

**Pós-condições**

Caderno para salvar [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) selecionado.

**Fluxo principal**

1. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica no ícone da extensão;
2. O [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona em qual [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) salvar a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)(UC20).

**Fluxo de exceção**

**FE01 - Conexão com a Internet**  
Se não houver conexão com a internet, o sistema deverá mostrar uma mensagem de erro.

## Referências

https://www.evernote.com/Registration.action

https://www.evernote.com/Login.action

https://www.devmedia.com.br/especificacao-de-casos-de-uso-na-pratica/18427

http://www.funpar.ufpr.br:8080/rup/process/modguide/md_ucmod.htm
