# Titulo do projeto

Introdução geral ao repositório.

## Cronograma do projeto

Descrever tarefas planejadas, em desenvolvimento e entregues. Pode ser substituido por um Kanban.

## Proposta do problema

Descrever o problema que este projeto pretende resolver.

Alguns pontos para levar em consideração:

Sobre o problema geral
- ~~Qual problema estamos tentando resolver?~~ 
- ~~Por que precisamos montar um sistema para isso?~~
- ~~De onde os dados vão vir para o sistema?~~
  - ~~Vamos adotar alguma simplificação?~~ 
  - ~~Como vamos implementar essa simplificação? (E.g carregar uma planilha - definir o que vai ter na planilha como colunas, o que cada linha representa, etc.)~~
  - ~~Conseguimos remover essa simplificação facilmente no futuro e implementar uma fonte de dados real?~~  
- No caso de mais de 1 sistema (e.g Backend compartilhado entre gerador de dados (adminstrador) e consumidor de dados (usuario), e um frontend para usuario, e outro frontend para adminstrador), como eles vão se comunicar. Por que precisamos de mais de um sistema?
- Desenhar a arquitetura do sistema

Sobre o sistemas de usuarios?
- Como o usuario vai acessar o sistema (App Mobile ou App web)?
- Com qual tecnologia vamos implementar essa aplicação de usuário? Por que?
  - Material sobre escolha de tecnologia: 
  - Alguns pontos pessoais que eu olho antes de escolher tecnologia para um projeto:
    - Qual linguagem EU quero aprender ou me sinto confortavel em usar?
    - Tem algum cliente para o projeto que definiu algum pré-requisito de tecnologia?
    - Se o cliente for você - pense no seus pré-requisitos. Mobile app - tem que escolher algo que roda no seu celular. Web App - Não pode ter pré-requisito de ter GPU se eu não tenho uma GPU para testar.
    - Outras pessoas usam essa linguagem pra isso? (Pensando em encontrar desenvlovedor pra manter o projeto, mercado de trabalho, etc.).
    - Tem alguma linguagem/tecnologia que é melhor para o tipo de problema? (Uma escolha ruim pode tornar um projeto de 1 semana em um de 3 meses).
- Definir a interface de usuario do sistema
  - Quais paginas o sistema vai ter 
  - O que cada pagina deve mostrar para o usuario
  - Como o usuario pode vai interagir com o sistema para navegar entre paginas? e.g Clicou em um botão na pagina A - Abre a pagina B.
  - Talvez vale utilizar ferramentas de desenhos para planejar como vai ser o app

## Set up do projeto

### Armazenamento do código

Git para versionamento. Github/Gitlab qualquer outro para colaboração.
Não precisa de uma sessão para isso, apenas um lembrete.

### Arquitetura

Descrever os componentes do sistema (bancos de dados, APIs, interfaces de usuário, etc.).

Descrever melhor as tecnologias selecionadas, por que elas foram selecionados e se elas se integram bem.

Descrever o por que a arquitetura foi desenhada desta forma. Quais são os ganhos de ter mais ou menos componenentes. 

Caso o sistema não for uma aplicação local, descrever como ele sera hospedado, quais serviços podem ser utilizados e quais tecnologias podem ser utilizadas para automatizar este processo.

### Desenvolvimento e execução do códigos

Descrever os pré-requisitos do projeto.

Descrever IDE específica se necessária, como executar o código em um ambiente local, etc.

Documentar o motivo da seleção da IDE/meio de execução.