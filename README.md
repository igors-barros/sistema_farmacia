# Projeto de estudos entre pares

Arquivo para ir documentando a concepção do projeto de um applicativo desenvolvido com sessões de programação em par. 

## Cronograma do projeto

- 27/02/2023: Adição de material sobre Git, Github e limpeza da documentação.
- 26/02/2023: Definição do projeto através de Markdown (Finalizado quando fechar a proposta do problema).
- 24/02/2023: Concepção de um projeto de estudo entre pares para explorar tecnologias.


## Proposta de problema

Este projeto tem como objetivo o desenvolvimento de um sistema para consulta de farmacias plantonistas em uma cidade. Propomos o desenvolvimento do mesmo, pois a informação da farmacia plantonista é de dificil acesso ao cliente alvo. Com este sistema temos tambem a oportunidade de criar um novo canal de vendas para as farmacias. Além de ser um meio informativo basico, pretendemos criar tambem um catalogo de produtos. O sistema proposto vai possuir um aplicativo (front-end), para interação do usuario e os dados mostrados serão fornecidos por uma API REST (back-end).

**Tarefa em dupla**: Desenhar a arquitetura do nosso sistema com [DrawIO](https://draw.io) 

Inicialmente propomos trabalhar com dados ficticios para desenvolver a estrutura do aplicativo. Dados como, nome da farmacia, endereço, telefone de contato, horario de funcionamento, produtos e medicamentos com seus respectivos valores. Tais produtos e medicamentos podendo estarem categorizados por sessão, como, higiene pessoal, medicamentos, perfumaria, cabelo, artigos de beleza, etc.. Para facilitar a implementação futura de um filtro.

Aprofundando nas definições de dados iremos definir um esquema com as entidades(objetos) e os atributos(caracteristicas) de cada entidade. Identifdicamos duas entidades que são as farmacias e os produtos.

Para iniciar o trabalho no frontend, que sera desenvolvido em react native, os dados serão listas de objetos mockado em JS. Futuramente esses dados serão fornecidos atraves de uma API desenvolvida em Node.
  
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
Material complementar: [O que é Git e GitHub? (15min)](https://www.youtube.com/watch?v=GDGMf2bnHlE) 

O Git é uma ferramenta de versionamento de código. Ele tornar possível rastrear o histórico de modificações de um conjunto de arquivos. Com o Git podemos reverter mudanças, restaurando os arquivos para um estado anterior. Prentedemos desenvolver este projeto utilizando o Git para fins de versionamento deste projeto.

O Github é uma platforma que armazena repositórios Git na núvem. Ele permite que multiplos desenvolvedores trabalhem simultaneamente e consigam puxar as atualizações mais recente do repositório sem necessariamente utilizando a mesma rede. Predentemos utilizar o Github para armazenar o código do nosso projeto e para facilitar a colaboração.

Comandos comuns do Git
- `git pull`: Atualiza a versão local da branch com as ultimas mudanças da versão remota da branch.
- `git add {file_name}`: Adiciona um arquivo ao ambiente de staging do Git.
- `git commit -m "{commit message}"`: Persiste as mudanças do ambiente de staging na branch com uma mensagem.
- `git push`: Persiste as modificações locais da branch para a versã remota da branch.

### Arquitetura

**Tarefa** Transformar essa sessão em texto corrido.

Dado os problemas que queremos resolver, conseguimos quebrar ele em "problemas" menores? Como?
  
O que é frontend?

O que é backend?

O que é uma API?

[O que são API's, front-end e back-end?](https://medium.com/@MacgyverMartins/o-que-s%C3%A3o-apis-front-end-e-back-end-conceitos-de-desenvolvimento-para-n%C3%A3o-programadores-parte-1-a76d3066b99a)

O que significa REST?

Por que precisamos de uma API RESTful para este projeto. 

Quais serão os recursos (entidades) da nossa API REST.

Quando vamos implementar a API REST. Sera antes ou depois de começar a interface de usuario? Porque?
- Dica: JavaScript pode ser utilizado com objetos mockados. 

[O que é API? REST e RESTful? Conheça as definições e diferenças!](https://becode.com.br/o-que-e-api-rest-e-restful/)

O que é um projeto monorepo? 

Por que usar monorepo?

[O que é monorepo?](https://woliveiras.com.br/posts/o-que-%C3%A9-monorepo/) - Recomendo ler as primeiras 4 seções (Introdução até "O que de fato são os monorepos").

**Tarefa**: Dentro do repositório local do Github, crie um sub-repositório (uma pasta nova) chamado "android_app".

### Desenvolvimento e execução de código

O que é uma IDE (Ambiente de Desenvolvimento Integrado)?

Dados as tecnologias utilizadas, quais IDEs podemos utilizar?

Escolha uma IDE pra gente utilizar nesse projeto. Tente escolher uma que integre bem com o Github e funcione bem na maquina dos dois envolvidos no projeto. Por que você escolheu ela?

**Tarefa em dupla**: Montar um projeto mock na maquina de um desenvolvedor dentro do repositório "android_app" com a IDE e subir para o repositório. O segundo desenvolvedor deve puxar o projeto do repositório e rodar na maquina dele. Depois ele deve fazer uma mudança no código e subir para o repositório.