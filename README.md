# Projeto de estudos entre pares

Arquivo para ir documentando a concepção do projeto de um applicativo desenvolvido com sessões de programação em par. 

## Cronograma do projeto

Definição das tarefas que precisam ser feitas, estão sendo feitas ou foram entregues no projeto. As sessões devem ir sendo atualizadas de acordo com o que esta rolando no projeto.

### Em Andamento (Ongoing)

- 25/02/2023 - //2023: Definição do projeto através de Markdown (Finalizado quando fechar a proposta do problema).
- //2023 - //2023: Criação do repositório do projeto.


### Finalizado (Done)
-  24/02/2023 - 24/02/2023: Concepção de um projeto de estudo entre pares para explorar tecnologias.


## Proposta de problema

Desenvolvimento de um sistema para consulta de farmacias platonistas em uma cidade. 

[Preencher esta sessão com as seguintes informações]

Sobre o problema geral
- Qual problema estamos tentando resolver? 
- Por que precisamos montar um sistema para isso?
- De onde os dados vão vir para o sistema?
  - Vamos adotar alguma simplificação? 
  - Como vamos implementar essa simplificação? (E.g carregar uma planilha - definir o que vai ter na planilha como colunas, o que cada linha representa, etc.)
  - Conseguimos remover essa simplificação facilmente no futuro e implementar uma fonte de dados real?  
- No caso de mais de 1 sistema (e.g Backend compartilhado entre gerador de dados (adminstrador) e consumidor de dados (usuario), e um frontend para usuario, e outro frontend para adminstrador), como eles vão se comunicar. Por que precisamos de mais de um sistema?
  
**Tarefa em dupla**: Desenhar a arquitetura do nosso sistema com [DrawIO](https://draw.io) 

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
  
**Tarefa em dupla**: Desenho de interface do usuario com o (Figma)[https://www.figma.com/].


## Set up do projeto

Definição da base para o projeto antes da gente começar a implementar. Documentar como configuramos as coisas para começar o projeto e conseguir programar em pares.

### Documentação do projeto

**O que é Markdown?**

[Definição Basica](https://tecnoblog.net/responde/o-que-e-markdown/): Markdown é uma linguagem voltada para formatação de textos. Com ele, podemos escrever textos com formatação (negrito, italico, titulos, etc) a partir do bloco de notas. Além disso, podemos anexar links uteis, imagens, e até mesmo HTML. 

**Por que usar Markdown?**

~~Por que o Gu começou fazer a definição do projeto em Markdown~~.

- Sintaxe simples.
- Todo mundo usa para documentar projetos de programação.
- Da para escrever a partir do bloco de notas, vscode, etc.
- Tem linguages de programação que ja suportam markdown no frontend (então da pra anexar um documento markdown em um site por exemplo).

**Manual de Markdown**

[Escrevendo e formatando Markdown no Github](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax): Esse link é um documento que mostra tudo que da pra fazer com documentos Markdown no Github.

### Armazenamento do código

O que é Git? 

Por que usar Git?

O que é Github? 

Por que usar Github?

O que é um repositório?

[O que é Git e GitHub? (15min)](https://www.youtube.com/watch?v=GDGMf2bnHlE) - Ele fala que você precisa dos arquivos do projeto, mas qualquer arquivo funciona na pratica (Esse documento markdown que voce ta lendo por exemplo).

**Tarefa em dupla**: Criar uma conta no Github. Criar um repositório publico no Github. Clone o repositório da sua conta para a sua maquina com o Github desktop. Suba este documento markdown como um readme para o repositório. 

**Tarefa**: Documente nesta sessão o que é um commit, uma branch e um merge request.

#### Arquitetura do repositório

Dado os problemas que queremos resolver, conseguimos quebrar ele em "problemas" menores? Como?
  
O que é frontend?

O que é backend?

O que é uma API?

[O que são API's, front-end e back-end?](https://medium.com/@MacgyverMartins/o-que-s%C3%A3o-apis-front-end-e-back-end-conceitos-de-desenvolvimento-para-n%C3%A3o-programadores-parte-1-a76d3066b99a)

O que é um projeto monorepo? 

Por que usar monorepo?

[O que é monorepo?](https://woliveiras.com.br/posts/o-que-%C3%A9-monorepo/) - Recomendo ler as primeiras 4 seções (Introdução até "O que de fato são os monorepos").

**Tarefa em dupla**: Dentro do repositório local do Github, crie um sub-repositório (uma pasta nova) chamado "android_app".

### Desenvolvimento e execução de código

O que é uma IDE (Ambiente de Desenvolvimento Integrado)?

Dados as tecnologias utilizadas, quais IDEs podemos utilizar?

Escolha uma IDE pra gente utilizar nesse projeto. Tente escolher uma que integre bem com o Github e funcione bem na maquina dos dois envolvidos no projeto. Por que você escolheu ela?

**Tarefa em dupla**: Montar um projeto mock na maquina de um desenvolvedor dentro do repositório "android_app" com a IDE e subir para o repositório. O segundo desenvolvedor deve puxar o projeto do repositório e rodar na maquina dele. Depois ele deve fazer uma mudança no código e subir para o repositório.