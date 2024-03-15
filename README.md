# Ada HBO Max

Projeto final do curso de Frontendo focado em React da Ada.

<a href="src\assets\hbo-clone.PNG"></a>



## 🛠️ Abrir e rodar o projeto FRONTEND

Para abrir e rodar o front do projeto, execute `npm i` para instalar as dependências e `npm run dev` para iniciar o projeto.

Depois, acesse <a href="http://127.0.0.1:5173/">http://127.0.0.1:5173/</a> no seu navegador.

## ✔️ Cronograma de Aulas do Módulo

28/02/2024

- state para email;
- isSubmitted;
- mostrar erro de email inválido;
- state para senha;
- mostrar erro de senha inválida;
- mostrar senha em texto;
- submit do form;
- loading no submit;
- adicionar o fakeApi
- mostrar erro (Alert) de credenciais inválidas
- mostrar console.log() de sucesso
- 
01/03/2024

- Comunicar com a API;
- Salvar o token no LocalStorage;
- Redirecionar para HOME
- Criar um hook para pegar os dados do usuário; (npm i jose para decodificar o token)
- Criar um hooke para proteger a HOME;
- Fazer Logout;
- Criar um rota protegida para proteger a HOME e as demais páginas;
  
Atividade em Grupo

- Login com adamax -> id para BACKSTAGE

- Login com user -> ir para PROFILE

- [plus]: usar @rehooks/local-storage

04/03/2024

- Dúvidas sobre useCallback ?
- Entrar em /profile;
- Buscar os profiles em /api/profile;
- Buscar os avatares em /api/avatar;
  
06/03/2024

- Editar Profile em /edit-profile/:id
- Deletar Profile em /delete-profile/:id
- Usando lib de classes css clsx
  
08/03/2024

Aqui temos uma refatoração usando algumas libs.

- React Query data-fetching library: para lidar com requisições de dados e cache;
- React Hook Form Performant, flexible and extensible forms with easy-to-use validation: para lidar com forms;
- Zod TypeScript-first schema validation with static type inference: para criação de schemas de validação de dados;
- React i18next Internacionalização
  
```
npm i @tanstack/react-query
npm i react-hook-form @hookform/resolvers
npm i zod
npm i styled-components
npm i --save-dev babel-plugin-styled-components
npm i react-i18next i18next
```

