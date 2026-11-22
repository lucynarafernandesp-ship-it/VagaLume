# VagaLume

**Sua próxima oportunidade começa aqui!**

O VagaLume é um projeto desenvolvido para a disciplina de Desenvolvimento Web 2. A ideia é criar um site onde empresas possam divulgar vagas de emprego e pessoas interessadas possam visualizar as oportunidades disponíveis.

## Sobre o projeto

O objetivo é desenvolver uma aplicação web utilizando uma API REST, colocando em prática os conteúdos estudados durante as aulas, como Node.js, Express, métodos HTTP e integração entre frontend e backend.

## Funcionalidades

- Cadastrar vagas de emprego;
- Mostrar todas as vagas cadastradas;
- Consultar os detalhes de uma vaga;
- Editar informações de uma vaga;
- Excluir vagas cadastradas;
- Exibir as vagas em uma página web.

## Entidades do projeto

Inicialmente, pensamos em trabalhar com três entidades:

- **Vaga:** armazena as informações das oportunidades de emprego.
- **Empresa:** representa as empresas que oferecem as vagas.
- **Candidato:** representa as pessoas que procuram oportunidades.

Nesta primeira etapa, vamos implementar o CRUD completo da entidade Vaga, utilizando um array em memória.

## Rotas da API

| Método | Rota | Função |
|---|---|---|
| GET | `/vagas` | Listar todas as vagas |
| GET | `/vagas/:id` | Buscar uma vaga pelo ID |
| POST | `/vagas` | Cadastrar uma vaga |
| PUT | `/vagas/:id` | Atualizar uma vaga |
| PATCH | `/vagas/:id` | Atualizar parte das informações |
| DELETE | `/vagas/:id` | Excluir uma vaga |

## Tecnologias utilizadas

- HTML
- CSS
- JavaScript
- Node.js
- Express
- Fetch API
- Git e GitHub

## Organização das pastas

```text
VagaLume/
│
├── backend/
│   └── server.js
│
├── frontend/
│   ├── index.html
│   ├── styles/
│   │   └── styles.css
│   └── scripts/
│       └── app.js
│
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

## Integrantes

- Nathiara
- Raquel
- Hercules
- Lucynara

## Informações da disciplina

**Curso:** Técnico em Informática para Internet  
**Disciplina:** Desenvolvimento Web 2  
**Professor:** Kaio Jonathas  
**Instituição:** IFCE – Campus Maranguape

---

Projeto em desenvolvimento.