## Repositório de Aprendizado

<p>Este repositório foi criado com o intuito de guardar os arquivos de um curso que estou fazendo.</p>

---
<details>
  <summary>
  <b>Configurações de Ambiente</b>
  </summary>


  <p>Os seguintes itens foram instalados para configurar meu ambiente de desenvolvimento, seguindo as diretrizes do minicurso</p>
  
#### Fontes
  * [Fonte Fira Code](https://github.com/tonsky/FiraCode)

#### Extensões no VSCODE
  * [Dracula Theme](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
  * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  * [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
  * [Rocketseat ReactJS](https://marketplace.visualstudio.com/items?itemName=rocketseat.RocketseatReactJS)
  * [Rocketseat React Native](https://marketplace.visualstudio.com/items?itemName=rocketseat.RocketseatReactNative)
#### Extensões Chrome
  * [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=pt-BR)
  * [Dracula Theme for DevTools](https://chrome.google.com/webstore/detail/dracula-theme-for-devtool/gedipeckgflanbhlcglokjjacilfidda?hl=pt-BR&authuser=1)




  #### Settings.json do VSCode

  ```json
      {
        "editor.suggestSelection": "first",
        "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
        "workbench.colorTheme": "Dracula",
        "editor.fontFamily": "Fira Code",
        "editor.fontLigatures": true,
        "editor.fontSize": 18,
        "workbench.iconTheme": "material-icon-theme",
        "editor.rulers": [80, 120],
        "editor.renderLineHighlight": "gutter",
        "editor.tabSize": 2,
        "terminal.integrated.fontSize": 14,
        "emmet.includeLanguages": {
            "javascript": "javascriptreact"
        },
        "emmet.syntaxProfiles": {
            "javascript": "jsx"
        },
        "javascript.updateImportsOnFileMove.enabled": "never",
        "editor.parameterHints.enabled": false,
        "breadcrumbs.enabled": true,
        "javascript.suggest.autoImports": false,
        "terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe"
    }
  ```



  #### Ferramentas

  * [Insominia](https://insomnia.rest/download/)
  * [DevDocs](https://devdocs.egoist.moe/)

</details>

---

### Node.js

##### O que foi instalado?
* [NodeJs](https://nodejs.org/en/)
* [Chocolatey](https://chocolatey.org/)
* [Yarn](https://yarnpkg.com/getting-started/install)


<details>
<summary> <b>Conceitos do Node.js</b> </summary>


* Javascript pode ser executado como back-end e não somente no front.
* Nao lidamos com eventos do usuário final (Clique em botões, mouse em cima, etc...)
* Eventos do usuários são rotas (Quando o usuário acessa algum endereço)
* Node não é uma linguagem, ele é uma plataforma para desenvolvimento Backend
* Construído em cima do V8 (Engine do chrome pra rodar Javascript)
* Comparável a PHP/Ruby/Python/Go (Linguagens que se aplicam ao lado do back-end)

##### O que é o NPM/Yarn?
* São gerenciadores de pacotes.
* Instaladores de bibliotecas de terceiros
* Podemos fornecer nossa biblioteca para que terceiros utilizem
* Por que utilizar o Yarn?
  * Yarn muito mais rapido e avançando mais rapido que o NPM
* Comparavel ao PIP do python

##### Características do Node
* Arquitetura **Event-loop**
  * Baseada em eventos
  * **Call Stack** (Pilha de eventos, função disparada pelo código e o node executa através de um loop eterno)
    * Last in - First Out
* Node é **single-thread**
  * Porém utiliza várias libs do C++, então permite utilizar outras threads.
* **Non-blocking I/O**
  * Quando é feito uma requisição para o node, não é necessário retornar todos os dados da listagem de uma só vez, posso retornar em partes.
  * Por exemplo no PHP o momento em que eu envio a resposta pro cliente a conexão é terminada, mas no Node é possível manter a conexão.

##### Frameworks
* **ExpressJS** como base
  * Não tem opinião (Não tem estrutura fechado)
  * Bom para iniciantes
  * Utilizado em Micro-serviços 
* Frameworks opinados
  * **AdonisJS**
  * NestJS


</details>

