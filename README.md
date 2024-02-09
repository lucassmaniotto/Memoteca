# Memoteca 💭

Projeto desenvolvido em Angular 14 durante a formação [Formação Explore o Framework Angular](https://www.alura.com.br/formacao-angular-14) da Alura.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Memoteca 💭**
| :label: Tecnologias | angular, typescript, html, css, json-server
| 🖥 Curso    | https://www.alura.com.br/formacao-angular-14

## Detalhes do projeto

Este projeto foi desenvolvido durante a formação [Formação Explore o Framework Angular](https://www.alura.com.br/formacao-angular-14) da Alura. O projeto consiste em uma aplicação para armazenar frases e pensamentos que são importantes para o usuário. A aplicação permite que o usuário adicione, edite, liste e remova frases e pensamentos.

### ⚙️ Configurando o projeto

O projeto utiliza o Angular no frontend e o json-server no backend, para simular uma API REST.

Para instalar as dependências do projeto, execute o comando abaixo:
```bash
npm install
```

Para instalar o json-server, execute o comando abaixo:
```bash
cd .\backend\
npm install
```

### ▶️ Executando o projeto

Para executar o projeto, execute o comando abaixo:
```bash
npm start
```

O frontend estará disponível em `http://localhost:4200/`.

Para executar o json-server, execute o comando abaixo:
```bash
cd .\backend\
npm start
```

O backend estará disponível em `http://localhost:3001/`. e para acessar a API, utilize a rota `http://localhost:3001/thoughts`.

### 💡 Funcionalidades

#### Cadastro de pensamentos
Para cadastrar um pensamento, o usuário deve preencher o formulário com a sua frase, a autoria e o modelo que gostaria de exibir seu card, acessando a rota `http://localhost:4200/createThought`.

O formulário possui validação de campos obrigatórios e de tamanho máximo de caracteres, além de padrão de escrita.

#### Listagem de pensamentos
O usuário pode visualizar todos os pensamentos cadastrados, podendo ser filtrados buscando por uma palavra-chave, além de listar os pensamentos favoritos, acessando a rota `http://localhost:4200/listThought`.

Existe paginação para a listagem de pensamentos, exibindo 6 pensamentos por página. O usuário pode carregar mais pensamentos clicando no botão "Carregar mais" ao final da lista.

##### Favoritar pensamentos
O usuário pode favoritar um pensamento ou desfavoritar, clicando no botão de coração no card do pensamento.

#### Edição de pensamentos
O usuário pode editar um pensamento cadastrado, acessando a rota `http://localhost:4200/editThought/:id`, onde `:id` é o id do pensamento que deseja editar. O usuário acessa a rota clicando no botão "Editar" em um card listado em `http://localhost:4200/listThought`.

Ao ser redirecionado, o usuário pode fazer as mesmas alterações que no cadastro, porém, os campos já estarão preenchidos com os dados atuais do pensamento.

#### Remoção de pensamentos
O usuário pode remover um pensamento cadastrado, acessando a rota `http://localhost:4200/listThought`. 

Ao clicar no botão "Remover" em um card listado, o pensamento será removido da lista após a confirmação do usuário.

## 📝 Licença

Projeto desenvolvido por [Alura](https://www.alura.com.br) e utilizado nos cursos de Angular 14.

Instrutora: [Nayanne Batista](https://cursos.alura.com.br/user/nayanne-batista) 
