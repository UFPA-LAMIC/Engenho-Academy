# Engenho Academy - Plataforma de Aprendizagem Interativa

## 📌 Sobre o Projeto

O **Engenho Academy** faz parte do *Projeto Viva! Universidade 2024: operacionalização de um ambiente de aprendizagem com requisitos de acessibilidade*. Ele é uma plataforma interativa desenvolvida para oferecer cursos na área de Engenharia de Computação e Telecomunicações, com foco em acessibilidade e inclusão.

A ferramenta permite que professores disponibilizem cursos sobre **Redes de Computadores, Circuitos Elétricos, Programação** e outros temas relevantes.

## 🚀 Funcionalidades

- ✅ Cadastro de usuários (professores e alunos)
- 📂 Upload de cursos e materiais didáticos
- ♿ Interface acessível conforme diretrizes de acessibilidade
- 💬 Fórum para discussões e dúvidas
- 📊 Acompanhamento de progresso dos alunos

## 🛠 Requisitos

Antes de rodar a aplicação, certifique-se de ter os seguintes requisitos instalados:

- 🟢 Node.js (versão mínima: 16.0.0)
- 📦 npm 
- 🗄 Dbeaver para o banco de dados PostgreSQL
- 🐳 Docker (Para facilitar a configuração do ambiente)

## 📌 Como Rodar o Projeto

Clone este repositório:

```sh
git clone https://github.com/UFPA-LAMIC/Engenho-Academy.git
cd Engenho Academy
```

Instale as dependências do back-end e front-end:

```sh
npm install
```


Configure o banco de dados:

- configure o Dbeaver com as credenciais do seu banco
- Execute as migrations:

Inicie a aplicação:

No caminho do back-end
```sh
npm start
```
No caminho do front-end
```sh
npm run serve
```

A aplicação estará rodando em ` http://localhost:8080/`.

## 🤝 Contribuição

Quer contribuir? Aqui está como fazer:

1. Faça um **fork** do projeto.
2. Crie uma **branch** com sua feature:
   ```sh
   git checkout -b minha-feature
   ```
3. Commit suas alterações:
   ```sh
   git commit -m 'Adicionando nova funcionalidade'
   ```
4. Envie um **Pull Request** para revisão.

## 📜 Licença

Este projeto está licenciado sob a licença **MIT**. Consulte o arquivo LICENSE para mais detalhes.

---


## ❓ Dúvidas

Se tiver alguma dúvida ou encontrar algum problema, entre em contato através das seguintes opções:

- 📧 E-mail: lamic@ufpa.br.com
- 🐞 Reporte um bug abrindo uma *issue* no GitHub
- :bookmark_tabs:Responsavéis pelo projeto:
- :office_worker: Orientador:ALS Castro: agcastro@ufpa.br
- :man_student: Bolsista:Gabriel Silva: silva.gabriel@itec.ufpa.br
