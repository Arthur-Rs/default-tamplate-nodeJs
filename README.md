# Default Template NodeJs

Este é uma ambiente node pré-configurado para agilizar o processo de desenvolvimento evitando o período de configurações iniciais para a aplicação. Este layout está pré configurado para depuração e execução de aplicações node utilizando o Javascript utilizando:

- eslint
- prettier
- express
- sequelize
- nodemon
- sucrase

O sequelize está configurado para utilizar o *[PostgreSQL](https://sequelize.org/master/manual/getting-started.html)*, busque e modifique as configurações no diretório **"src/settings/database.js"** para utilizar o banco de sua preferência.

## Como utilizar?

**Passo 1** - Primeiramente faça o download do repositório, digite no diretório de sua preferência:
```
git clone https://github.com/Arthur-Rs/default-tamplate-nodeJs.git
```

**Passo 2** - Agora faça download das dependências da aplicação para isso utilize o  `yarn add`  no terminal:
```
yarn add
```

Agora é começar a codar...

## Algum problema?

Talvez seja necessário configurar o seu **Visual Studio Code** para o correto funcionalmente. Abaixo esta um tutorial de como configurar o seu VS Code para que posso utilizar todas as ferramentas disponíveis

### Eslint

**Passo 1** - Primeiramente abra as configurações do seu VS Code, aperte as teclas **"ctrl+shift+p"** e digite **Open Settings (Json)** .

**Passo 2** - Agora com suas configurações aberta, copie e cole as seguintes configurações:

```
        "editor.codeActionsOnSave": {
    	    "source.fixAll":  true,
    	    "source.fixAll.eslint":  true
        },

	    "editor.defaultFormatter":  "esbenp.prettier-vscode",
	    "[javascript]": {
	    "editor.defaultFormatter":  "esbenp.prettier-vscode"
	    }
```

**Passo 3** - É necessária instalar um plugin **[eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)** no seu VS Code.

Pronto agora seu VS code está configurado para utilizar o **eslint**, lembre-se que é apenas necessário seguir os passos acima uma única vez.
