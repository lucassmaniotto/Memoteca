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

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/17821a45-74fd-4daf-9c60-d8607cf10a06)

O formulário possui validação de campos obrigatórios e de tamanho máximo de caracteres, além de padrão de escrita.

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/4a092200-5f71-4d14-98ca-18863b55aa0d)

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/56d271a3-5d00-41ef-803f-1de847740874)

#### Listagem de pensamentos
O usuário pode visualizar todos os pensamentos cadastrados, podendo ser filtrados buscando por uma palavra-chave, além de listar os pensamentos favoritos, acessando a rota `http://localhost:4200/listThought`.

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/aa23e1db-5ba6-4768-9d60-298e039da41b)

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/dc27c2fa-3672-43f1-ad1c-8e8ed76745ce)

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/706bc8f5-ea0f-4dc2-b7d1-1c91381b78c1)

Existe paginação para a listagem de pensamentos, exibindo 6 pensamentos por página. O usuário pode carregar mais pensamentos clicando no botão "Carregar mais" ao final da lista.

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/2a0ac903-993c-4f01-8731-9e4e5271f1b9)

##### Favoritar pensamentos
O usuário pode favoritar um pensamento ou desfavoritar, clicando no botão de coração no card do pensamento.

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/d7339bcd-4829-49aa-959e-d33e399be8ce)

#### Edição de pensamentos
O usuário pode editar um pensamento cadastrado, acessando a rota `http://localhost:4200/editThought/:id`, onde `:id` é o id do pensamento que deseja editar. O usuário acessa a rota clicando no botão "Editar" em um card listado em `http://localhost:4200/listThought`.

Ao ser redirecionado, o usuário pode fazer as mesmas alterações que no cadastro, porém, os campos já estarão preenchidos com os dados atuais do pensamento.

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/0a1b3f58-9791-49dd-87c9-ac801789bbd5)


#### Remoção de pensamentos
O usuário pode remover um pensamento cadastrado, acessando a rota `http://localhost:4200/listThought`. 

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/d7339bcd-4829-49aa-959e-d33e399be8ce)

Ao clicar no botão "Remover" em um card listado, o pensamento será removido da lista após a confirmação do usuário.

![image](https://github.com/lucassmaniotto/Memoteca/assets/101435037/9c7b033e-05fe-48f3-9761-e9a4bc74f387)

## 📝 Licença

Projeto desenvolvido por [Alura](https://www.alura.com.br) e utilizado nos cursos de Angular 14.

Instrutora: [Nayanne Batista](https://cursos.alura.com.br/user/nayanne-batista) 
