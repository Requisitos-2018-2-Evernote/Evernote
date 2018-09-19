

## Cenários

Os cenários representam atividades que podem ser feitas e motivos da sua necessidade, pensando na usabilidade do produto. Descrito de forma simples, contextualiza como uma certa ação pode se desenvolver no comportamento da aplicação. São uma forma de representação fácil para que clientes e usuários possam discutir sobre os levantamentos das especificações dos requisitos juntos aos desenvolvedores.

### Sumário Cenários
| ID  |            Nome               |
|-----|-------------------------------|
| [C01](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-01) | Administrar bloqueio de senha |
| [C02](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-02) | Desativar o bloqueio de senha |
| [C03](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-03) | Alterar o bloqueio de senha   |
| [C04](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-04) | Desbloquear com impressão digital |
| [C05](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-05) | Bloqueio de senha - tempo esgotado |
| [C06](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-06) | Exibir [notas](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) no Widget |
| [C07](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-07) | Capturar página da web utilizando o [Evernote Web Clipper](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#evernote-web-clipper)|
| [C08](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-08) | Abrir aplicativo |
| [C09](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-09) | Exportar Arquivo |

#### Cenário 01
| Título | Administrar bloqueio de senha|
|-----------|------------------|
| **Objetivo** | Descrever as opções relacionadas ao bloqueio da [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) com senha.|
| **Contexto** | **Situação**  - [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deseja gerenciar proteção com senha. <br> **Pré-condição**  - Possuir celular e [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada.|
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario).|
| **Recursos** | Internet;<br>Smartphone;<br>[Aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Conta no Evernote.|
| **Episódios** |  [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deseja proteger conteúdo da [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pega o celular e abre a [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa "configurações" no menu principal;<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa "Informações da conta";<br> [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa [Administrar bloqueio de senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-01);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) escolhe [Desativar o bloqueio de senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-02);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) escolhe [Alterar o bloqueio de senha](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-03);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) escolhe [Desbloquear com impressão digital](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-04);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) escolhe [Bloqueio de senha - tempo esgotado](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-05);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) escolhe [Exibir notas no Widget](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#cenario-06).|
| **Restrição** |Internet;<br>Smartphone;<br>[Aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Conta no Evernote.|
| **Exceções** |Se o [usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) nunca definiu um [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) o mesmo é definido ao clicar em "Administrar bloqueio de senha".|

#### Cenário 02
| Título | Desativar o bloqueio de senha|
|-----------|------------------|
| **Objetivo** | Remover bloqueio com senha do aplicativo.|
| **Contexto** | **Situação**  - [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deseja remover bloqueio com senha.<br>**Pré-condição**  - Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido na [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).|
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario).|
| **Recursos** |Internet;<br>Smartphone;<br>[Aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Conta no Evernote.|
| **Episódios** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) está em "Administrar bloqueio de senha";<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Desativar o bloqueio de senha".|
| **Restrição** |Estar conectado à internet;<br>Possuir [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Possuir conta no Evernote;<br>Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido.
| **Exceções** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não definiu uma senha.|

#### Cenário 03
| Título | Alterar o bloqueio de senha|
|-----------|------------------|
| **Objetivo** | Alterar o [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) utilizado para proteger o aplicativo.|
| **Contexto** | **Situação**  - [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deseja alterar seu [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).<br>**Pré-condição**  - Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido na [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).|
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario).|
| **Recursos** |Internet;<br>Smartphone;<br>[Aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Conta no Evernote.|
| **Episódios** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) está em "Administrar bloqueio de senha";<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Alterar o bloqueio de senha";<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) digita sua nova senha;<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) repete o novo [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) digitado previamente.|
| **Restrição** |Estar conectado à internet;<br>Possuir [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Possuir conta no Evernote;<br>Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido.
| **Exceções** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não definiu uma senha.|


#### Cenário 04
| Título | Desbloquear com impressão digital.|
|-----------|------------------|
| **Objetivo** | Habilitar ou desabilitar desbloquear com impressão digital.|
| **Contexto** | **Situação**  - [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deseja habilitar/desabilitar a opção de desbloquear o aplicativo com a impressão digital salva no celular.<br>**Pré-condição**  - Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido na [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).|
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario).|
| **Recursos** |Internet;<br>Smartphone;<br>[Aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Conta no Evernote.|
| **Episódios** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) está em "Administrar bloqueio de senha";<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) ativa ou desativa a opção clicando em "Desbloquear com impressão digital".|
| **Restrição** |Estar conectado à internet;<br>Possuir [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Possuir conta no Evernote;<br>Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido.
| **Exceções** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não definiu uma senha.|

#### Cenário 05
| Título | Bloqueio de senha - tempo esgotado|
|-----------|------------------|
| **Objetivo** | Definir um tempo limite após o qual será solicitado que o [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) insira novamente o seu [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).|
| **Contexto** |**Situação**  - [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deseja definir o tempo para que seja cobrado novamente seu [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso).<br>**Pré-condição**  - Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido na [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).|
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario).|
| **Recursos** |Internet;<br>Smartphone;<br>[Aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Conta no Evernote.|
| **Episódios** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) está em "Administrar bloqueio de senha";<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica em "Bloqueio de senha - tempo esgotado";<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona o tempo limite de sua escolha.|
| **Restrição** |Estar conectado à internet;<br>Possuir [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Possuir conta no Evernote;<br>Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido.
| **Exceções** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não definiu uma senha.|

#### Cenário 06
| Título | Exibir [notas](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) no Widget|
|-----------|------------------|
| **Objetivo** | Escolher entre exibir ou não [notas](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota) no **Widget**.|
| **Contexto** | **Situação**  - [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deseja habilitar/desabilitar  a opção de exibir notar no Widget.<br>**Pré-condição**  - Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido na [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao).|
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario).|
| **Recursos** |Internet;<br>Smartphone;<br>[Aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Conta no Evernote.|
| **Episódios** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) está em "Administrar bloqueio de senha";<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) ativa ou desativa a opção clicando em "Exibir notas no Widget".|
| **Restrição** |Estar conectado à internet;<br>Possuir [aplicação](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#aplicacao) instalada;<br>Possuir conta no Evernote;<br>Possuir [código de acesso](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#codigo-de-acesso) definido.
| **Exceções** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) não definiu uma senha.|


#### Cenário 07
| Título | Capturar página da web utilizando o [Evernote Web Clipper](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#evernote-web-clipper)|
|-----------|------------------|
| **Objetivo** | Descrever as opções relacionadas à [captura](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#captura) de páginas da web com o Web Clipper.|
| **Contexto** | **Situação**  - [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) deseja salvar informações de uma página da web como [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota).<br>**Pré-condição**  - Possuir conta no app e extensão adicionada ao Google Chrome.|
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario).|
| **Recursos** | Internet;<br>Conta no Evernote;<br>Google Chrome;<br>[Evernote Web Clipper](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#evernote-web-clipper).|
| **Episódios** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o Google Chrome e navega até a página da web desejada;<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) clica sobre o ícone do [Evernote Web Clipper](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#evernote-web-clipper);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona um **formato de captura**;<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) seleciona em qual [caderno](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#caderno) deseja salvar a [captura](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#captura);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode adicionar [etiquetas](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#etiqueta);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode adicionar uma observação à [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota);<br>[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) salva a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota);|
| **Restrição** |Estar conectado à internet;<br>Possuir extensão Web Clipper adicionada ao Chrome;|
| **Exceções** |[Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pode não salvar a [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota);<br>Falha na conexão com a internet.|

#### Cenário08                                                                   

| Título | Abrir aplicativo |
|-----------|------------------|
| **Objetivo** | Usar aplicativo |
| **Contexto** | Ter aplicativo |
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario)|
| **Recursos** | Celular <br> Computador <br> Bateria <br> Internet |
| **Episódios** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) pega o celular <br> [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o aplicativo <br> [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) faz uma anotação |
| **Exceções** | Celular está sem bateria <br> Aplicativo não abre <br> Touch do celular não funciona |

#### Cenário09                                                                  

| Título | Exportar Arquivo |
|-----------|------------------|
| **Objetivo** | Salvar arquivo importante |
| **Contexto** | Ter aplicativo |
| **Atores** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario)|
| **Recursos** | Celular <br> Computador <br> Bateria <br> Internet <br> Arquivo Digital |
| **Episódios** | [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) salva pdf pelo computador em uma [nota](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#nota)<br> [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) abre o aplicativo pelo celular <br> [Usuário](https://requisitos-2018-2-evernote.github.io/Evernote/Modelagem/#usuario) acessa arquivo salvo |
| **Exceções** | Celular está sem bateria <br> Aplicativo não abre <br> Touch do celular não funciona <br> Computador está sem internet <br> Arquivo está corrompido |

## Léxico

### Sumário Léxicos
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

#### Aplicação

**Noção:**

-   Notação utilizada para se referir ao utilitário em questão, o Evernote.
  
**Classificação:**  Objeto.

**Impacto:**

- Usuário deseja proteger conteúdo da aplicação;
- Usuário pega o celular e abre a aplicação;
- Possuir conta no app e extensão adicionada ao Google Chrome;
- Usuário escolhe se a aplicação deve exibir notas no widget.

**Sinônimos:**  app, aplicativo.
 


#### Usuário

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

#### Código de acesso

**Noção:**

- Sequência de 4 números utilizada para desbloquear o aplicativo.

**Classificação:** Objeto.

**Impacto:**

- Se o  usuário  nunca definiu um código de acesso o mesmo é pedido pelo aplicativo;
- Usuário pode definir um limite de tempo após o qual será solicitado que insira novamente o código de acesso.

**Sinônimos:** senha.

#### Evernote Web Clipper

**Noção:**

- Extensão do Google Chrome utilizada para capturar páginas da web e salvar como nota no Evernote.

**Classificação:** Objeto.

**Impacto:**

- Capturar página da web utilizando o Evernote Web Clipper;
- Usuário clica sobre o ícone do Evernote Web Clipper.

**Sinônimos:** Web Clipper.

#### Captura

**Noção:**

- Parte de uma página da web que será salva em uma nota;

**Classificação:** Objeto.

**Impacto:**

- Usuário seleciona um formato de captura;
- Usuário seleciona em qual caderno deseja salvar a captura.
- Possui os seguinte formatos: Artigo, Artigo Simplificado, Página inteira, Seleção e Captura de tela.

**Sinônimos:** Capturas.

#### Etiqueta

**Noção:**

- Classificação de uma nota, facilitando encontrar notas que possuem a mesma etiqueta;

**Classificação:** Objeto.

**Impacto:**

- Usuário pode adicionar etiquetas.
- Uma forma de dividir suas notas além dos cadernos.

**Sinônimos:** Etiquetas.

#### Nota

**Noção:**

- Arquivo contendo anotações do usuário, que fica armazenado em nuvem no Evernote;

**Classificação:** Objeto.

**Impacto:**

- Usuário escolhe se a aplicação deve exibir notas no widget.
- Uma nota pode possuir anexos.

**Sinônimos:** notas, anotações.

#### Caderno

**Noção:**

- Agrupador de notas no Evernote;

**Classificação:** Objeto.

**Impacto:**

- Usuário seleciona em qual caderno deseja salvar a captura.
- Cadernos podem ser utilizados para organizar/separar notas.

**Sinônimos:** cadernos.

## Referências
LEITE, Jair. Usando cenários para descobrir requisitos. Disponível [aqui](http://engenhariadesoftware.blogspot.com/2007/05/usando-cenrios-para-descobrir.html). Acesso em: 18 de setembro de 2018.