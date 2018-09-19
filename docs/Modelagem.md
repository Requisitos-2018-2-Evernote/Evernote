
# Cenários

Os cenários representam atividades que podem ser feitas e motivos da sua necessidade, pensando na usabilidade do produto. Descrito de forma simples, contextualiza como uma certa ação pode se desenvolver no comportamento da aplicação. São uma forma de representação fácil para que clientes e usuários possam discutir sobre os levantamentos das especificações dos requisitos juntos aos desenvolvedores.

## Sumário Cenários
| ID  |            Nome               |
|-----|-------------------------------|
| C01 | Administrar bloqueio de senha |
| C02 | Desativar o bloqueio de senha |
| C03 | Alterar o bloqueio de senha   |
| C04 | Desbloquear com impressão digital |
| C05 | Bloqueio de senha - tempo esgotado |
| C06 | Exibir notas no Widget |
| C07 | Capturar página da web utilizando o **Evernote Web Clipper**|
| C08 | Abrir aplicativo |
| C09 | Exportar Arquivo |

### Cenário 01
| Título | Administrar bloqueio de senha|
|-----------|------------------|
| **Objetivo** | Descrever as opções relacionadas ao bloqueio da **aplicação** com senha.|
| **Contexto** | **Situação**  - Usuário deseja gerenciar proteção com senha. <br> **Pré-condição**  - Possuir celular e aplicação instalada.|
| **Atores** | Usuário.|
| **Recursos** | Internet;<br>Smartphone;<br>Aplicação instalada;<br>Conta no Evernote.|
| **Episódios** |  **Usuário** deseja proteger conteúdo da **aplicação**;<br>**Usuário** pega o celular e abre a aplicação;<br>**Usuário** acessa "configurações" no menu principal;<br>**Usuário** acessa "Informações da conta";<br> **Usuário** acessa "Administrar bloqueio de senha";<br>**Usuário** escolhe "Desativar o bloqueio de senha";<br>**Usuário** escolhe "Alterar o bloqueio de senha";<br>**Usuário** escolhe "Desbloquear com impressão digital";<br>**Usuário** escolhe "Bloqueio de senha - tempo esgotado";<br>**Usuário** escolhe "Exibir notas no Widget".|
| **Restrição** |Internet;<br>Smartphone;<br>Aplicação instalada;<br>Conta no Evernote.|
| **Exceções** |Se o **usuário** nunca definiu um **Código de acesso** o mesmo é definido ao clicar em "Administrar bloqueio de senha".|

### Cenário 02
| Título | Desativar o bloqueio de senha|
|-----------|------------------|
| **Objetivo** | Remover bloqueio com senha do aplicativo.|
| **Contexto** | **Situação**  - Usuário deseja remover bloqueio com senha.<br>**Pré-condição**  - Possuir **código de acesso** definido na aplicação.|
| **Atores** | Usuário.|
| **Recursos** |Internet;<br>Smartphone;<br>Aplicação instalada;<br>Conta no Evernote.|
| **Episódios** | **Usuário** está em "Administrar bloqueio de senha";<br>**Usuário** clica em "Desativar o bloqueio de senha".|
| **Restrição** |Estar conectado à internet;<br>Possuir aplicação instalada;<br>Possuir conta no Evernote;<br>Possuir **código de acesso** definido.
| **Exceções** | Usuário não definiu uma senha.|

### Cenário 03
| Título | Alterar o bloqueio de senha|
|-----------|------------------|
| **Objetivo** | Alterar o **código de acesso** utilizado para proteger o aplicativo.|
| **Contexto** | **Situação**  - **Usuário** deseja alterar seu **código de acesso**.<br>**Pré-condição**  - Possuir **código de acesso** definido na aplicação.|
| **Atores** | Usuário.|
| **Recursos** |Internet;<br>Smartphone;<br>Aplicação instalada;<br>Conta no Evernote.|
| **Episódios** | **Usuário** está em "Administrar bloqueio de senha";<br>**Usuário** clica em "Alterar o bloqueio de senha";<br>**Usuário** digita sua nova senha;<br>**Usuário** repete o novo código de acesso digitado previamente.|
| **Restrição** |Estar conectado à internet;<br>Possuir aplicação instalada;<br>Possuir conta no Evernote;<br>Possuir **código de acesso** definido.
| **Exceções** | Usuário não definiu uma senha.|


### Cenário 04
| Título | Desbloquear com impressão digital.|
|-----------|------------------|
| **Objetivo** | Habilitar ou desabilitar desbloquear com impressão digital.|
| **Contexto** | **Situação**  - **Usuário** deseja habilitar/desabilitar a opção de desbloquear o aplicativo com a impressão digital salva no celular.<br>**Pré-condição**  - Possuir **código de acesso** definido na aplicação.|
| **Atores** | Usuário.|
| **Recursos** |Internet;<br>Smartphone;<br>Aplicação instalada;<br>Conta no Evernote.|
| **Episódios** | **Usuário** está em "Administrar bloqueio de senha";<br>**Usuário** ativa ou desativa a opção clicando em "Desbloquear com impressão digital".|
| **Restrição** |Estar conectado à internet;<br>Possuir aplicação instalada;<br>Possuir conta no Evernote;<br>Possuir **código de acesso** definido.
| **Exceções** | Usuário não definiu uma senha.|

### Cenário 05
| Título | Bloqueio de senha - tempo esgotado|
|-----------|------------------|
| **Objetivo** | Definir um tempo limite após o qual será solicitado que o **usuário** insira novamente o seu **código de acesso**.|
| **Contexto** | **Usuário** deseja definir o tempo para que seja cobrado novamente seu **código de acesso**.<br>**Pré-condição**  - Possuir **código de acesso** definido na aplicação.|
| **Atores** | Usuário.|
| **Recursos** |Internet;<br>Smartphone;<br>Aplicação instalada;<br>Conta no Evernote.|
| **Episódios** | **Usuário** está em "Administrar bloqueio de senha";<br>**Usuário** clica em "Bloqueio de senha - tempo esgotado";<br>**Usuário** seleciona o tempo limite de sua escolha.|
| **Restrição** |Estar conectado à internet;<br>Possuir aplicação instalada;<br>Possuir conta no Evernote;<br>Possuir **código de acesso** definido.
| **Exceções** | Usuário não definiu uma senha.|

### Cenário 06
| Título | Exibir notas no Widget|
|-----------|------------------|
| **Objetivo** | Escolher entre exibir ou não notas no **Widget**.|
| **Contexto** | **Situação**  - **Usuário** deseja habilitar/desabilitar  a opção de exibir notar no Widget.<br>**Pré-condição**  - Possuir **código de acesso** definido na aplicação.|
| **Atores** | Usuário.|
| **Recursos** |Internet;<br>Smartphone;<br>Aplicação instalada;<br>Conta no Evernote.|
| **Episódios** | **Usuário** está em "Administrar bloqueio de senha";<br>**Usuário** ativa ou desativa a opção clicando em "Exibir notas no Widget".|
| **Restrição** |Estar conectado à internet;<br>Possuir aplicação instalada;<br>Possuir conta no Evernote;<br>Possuir **código de acesso** definido.
| **Exceções** | Usuário não definiu uma senha.|


### Cenário 07
| Título | Capturar página da web utilizando o **Evernote Web Clipper**|
|-----------|------------------|
| **Objetivo** | Descrever as opções relacionadas à captura de páginas da web com o Web Clipper.|
| **Contexto** | **Situação**  - Usuário deseja salvar informações de uma página da web como **nota**.<br>**Pré-condição**  - Possuir conta no app e extensão adicionada ao Google Chrome.|
| **Atores** | Usuário.|
| **Recursos** | Internet;<br>Conta no Evernote;<br>Google Chrome;<br>**Evernote Web Clipper**.|
| **Episódios** | **Usuário** abre o Google Chrome e navega até a página da web desejada;<br>**Usuário** clica sobre o ícone do Evernote Web Clipper;<br>**Usuário** seleciona um **formato de captura**;<br>**Usuário** seleciona em qual **caderno** deseja salvar a **captura**;<br>**Usuário** pode adicionar **etiquetas**;<br>**Usuário** pode adicionar uma observação à **nota**;<br>**Usuário** salva a **nota**;|
| **Restrição** |Estar conectado à internet;<br>Possuir extensão Web Clipper adicionada ao Chrome;|
| **Exceções** |Usuário pode não salvar a **nota**;<br>Falha na conexão com a internet.|

### Cenário08                                                                   

| Título | Abrir aplicativo |
|-----------|------------------|
| **Objetivo** | Usar aplicativo |
| **Contexto** | Ter aplicativo |
| **Atores** | Usuário |
| **Recursos** | Celular <br> Computador <br> Bateria <br> Internet |
| **Episódios** | Usuário pega o celular <br> Usuário abre o aplicativo <br> Usuário faz uma anotação |
| **Exceções** | Celular está sem bateria <br> Aplicativo não abre <br> Touch do celular não funciona |

### Cenário09                                                                  

| Título | Exportar Arquivo |
|-----------|------------------|
| **Objetivo** | Salvar arquivo importante |
| **Contexto** | Ter aplicativo |
| **Atores** | Usuário |
| **Recursos** | Celular <br> Computador <br> Bateria <br> Internet <br> Arquivo Digital |
| **Episódios** | Usuário salva pdf pelo computador em uma nota <br> Usuário abre o aplicativo pelo celular <br> Usuário acessa arquivo salvo |
| **Exceções** | Celular está sem bateria <br> Aplicativo não abre <br> Touch do celular não funciona <br> Computador está sem internet <br> Arquivo está corrompido |

# Léxico

## Sumário Léxicos
|ID| Nome |
|--|--|
| L | Aplicação |
| L | Usuário |
| L | Código de acesso |
| L | Evernote Web Clipper |
| L | Captura |
| L | Etiqueta |
| L | Nota |
| L | Caderno |

### Aplicação

**Noção:**

-   Notação utilizada para se referir ao utilitário em questão, o Evernote.
  
**Classificação:**  Objeto.

**Impacto:**

- Usuário deseja proteger conteúdo da aplicação;
- Usuário pega o celular e abre a aplicação;
- Possuir conta no app e extensão adicionada ao Google Chrome;
- Usuário escolhe se a aplicação deve exibir notas no widget.

**Sinônimos:**  app, aplicativo.
 


### Usuário

**Noção:**

- Pessoa que está utilizando o aplicativo.

**Classificação:**  Objeto.

**Impacto:**

- Usuário pode definir um limite de tempo após o qual será solicitado que insira novamente o código de acesso;
- Usuário deseja proteger conteúdo da aplicação;
- Usuário abre o Google Chrome e navega até a página da web desejada;
- Usuário salva a nota.
- Poderá utilizar todos os recursos disponíveis na aplicação;

**Sinônimos:**  usuários.

### Código de acesso

**Noção:**

- Sequência de 4 números utilizada para desbloquear o aplicativo.

**Classificação:** Objeto.

**Impacto:**

- Se o  usuário  nunca definiu um código de acesso o mesmo é pedido pelo aplicativo;
- Usuário pode definir um limite de tempo após o qual será solicitado que insira novamente o código de acesso.

**Sinônimos:** senha.

### Evernote Web Clipper

**Noção:**

- Extensão do Google Chrome utilizada para capturar páginas da web e salvar como nota no Evernote.

**Classificação:** Objeto.

**Impacto:**

- Capturar página da web utilizando o Evernote Web Clipper;
- Usuário clica sobre o ícone do Evernote Web Clipper.

**Sinônimos:** Web Clipper.

### Captura

**Noção:**

- Parte de uma página da web que será salva em uma nota;

**Classificação:** Objeto.

**Impacto:**

- Usuário seleciona um formato de captura;
- Usuário seleciona em qual caderno deseja salvar a captura.
- Possui os seguinte formatos: Artigo, Artigo Simplificado, Página inteira, Seleção e Captura de tela.

**Sinônimos:** Capturas.

### Etiqueta

**Noção:**

- Classificação de uma nota, facilitando encontrar notas que possuem a mesma etiqueta;

**Classificação:** Objeto.

**Impacto:**

- Usuário pode adicionar etiquetas.
- Uma forma de dividir suas notas além dos cadernos.

**Sinônimos:** Etiquetas.

### Nota

**Noção:**

- Arquivo contendo anotações do usuário, que fica armazenado em nuvem no Evernote;

**Classificação:** Objeto.

**Impacto:**

- Usuário escolhe se a aplicação deve exibir notas no widget.
- Uma nota pode possuir anexos.

**Sinônimos:** notas, anotações.

### Caderno

**Noção:**

- Agrupador de notas no Evernote;

**Classificação:** Objeto.

**Impacto:**

- Usuário seleciona em qual caderno deseja salvar a captura.
- Cadernos podem ser utilizados para organizar/separar notas.

**Sinônimos:** cadernos.

## Referências
LEITE, Jair. Usando cenários para descobrir requisitos. Disponível [aqui](http://engenhariadesoftware.blogspot.com/2007/05/usando-cenrios-para-descobrir.html). Acesso em: 18 de setembro de 2018.