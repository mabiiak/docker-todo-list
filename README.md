# Boas vindas ao projeto Docker Todo List!
  Projeto feito durante o curso de desenvolvimento web na trybe.

  Esse projeto foi feito para praticar alguns conceitos do Docker

## Habilidades
  - Usar comandos dockers no CLI - Interface de linha de comando;

  - Criar um contêiner Docker para uma aplicação de front-end;

  - Criar um contêiner Docker para uma aplicação de back-end;

  - Criar um contêiner Docker para uma aplicação de testes;

  - Orquestrar os três contêineres utilizando o Docker compose.

<details>
  <summary>
    <h3>
      Antes de começar a desenvolver
    </h3>
    </summary>

1. Clone o repositório
  * `git clone git@github.com:mabiiak/docker-todo-list.git`
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd docker-todo-list`

2. Instale as dependências:
    * `npm install`

3. Crie uma branch a partir da branch `master`

  * Verifique que você está na branch `master`
    * Exemplo: `git branch`
  * Se não estiver, mude para a branch `master`
    * Exemplo: `git checkout master`
  * Agora, crie uma branch onde você vai guardar os commits do seu projeto
    * Você deve criar uma branch no seguinte formato: `nome-de-usuario-nome-do-projeto`
    * Exemplo:
      * `git checkout -b nome-docker-todo-list`

4. Adicione a sua branch com o novo `commit` ao repositório remoto

  - Usando o exemplo anterior:
    - `git push -u origin nome-docker-todo-list`

5. Crie um novo `Pull Request` _(PR)_
  * Vá até a página de _Pull Requests_ do repositório no GitHub: [docker-todo-list](https://github.com/mabiiak/docker-todo-list/pulls) 
  * Clique no botão verde _"New pull request"_
  * Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
  * Clique no botão verde _"Create pull request"_
  * Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_
  * **Não se preocupe em preencher mais nada por enquanto!**
  * Volte até a [página de _Pull Requests_ do repositório](https://github.com/mabiiak/docker-todo-list/pulls) e confira que o seu _Pull Request_ está criado
</details>

## Requisitos

### Comandos docker

    ✅ 1. Crie um novo container de modo interativo sem roda-lo nomeando-o como `01container` e utilizando a imagem `alpine` usando a versão `3.12`

    ✅ 2. Inicie o container `01container`

    ✅ 3. Liste os containers filtrando pelo nome `01container`

    ✅ 4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele

    ✅ 5. Remova o container `01container` que está em andamento.

    ✅ 6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.

    ✅ 7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.

    ✅ 8. Pare o container `02images` que está em andamento.

### Dockerfile

    ✅ 9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.

    ✅ 10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.

    ✅ 11.Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`.

### Docker-compose

    ❌ 12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar.
