# Guia de Trabalho no Projeto EventHub

Bem-vindo ao projeto EventHub! Este guia fornece instruções para a equipe sobre como trabalhar no projeto, configurar o ambiente de desenvolvimento e seguir práticas recomendadas para colaboração no GitHub.

## 1. Estilo de Trabalho
O projeto EventHub segue uma abordagem dividida em duas partes:

- **Semana de Aprendizado**: Na primeira semana de cada Sprint, a equipe se concentra em treinamento, tutoriais, mentorias e exercícios práticos para se preparar para a semana de produção.
- **Semana de Produção**: Na segunda semana, a equipe coloca em prática o que aprendeu, trabalhando nas tarefas do Sprint Backlog e contribuindo para o desenvolvimento do projeto.

## 2. Configuração do Ambiente
Para trabalhar no projeto, siga estas etapas para configurar seu ambiente de desenvolvimento e instalar as ferramentas necessárias.

### 2.1. Ferramentas Necessárias
- **Git**: Para controle de versão. [Instalar Git](https://git-scm.com/).
- **.NET SDK**: Para trabalhar no back-end em C#. [Baixar .NET SDK](https://dotnet.microsoft.com/download).
- **Node.js**: Para desenvolvimento em React.js no front-end e React Native para mobile. [Baixar Node.js](https://nodejs.org/).
- **IDE/Editor de Código**: Visual Studio Code é recomendado. [Baixar Visual Studio Code](https://code.visualstudio.com/).

### 2.2. Clonar o Repositório
Para começar a trabalhar no projeto, clone o repositório do GitHub para sua máquina local.

```bash
git clone <URL-do-repositório>
cd <nome-do-repositório>
```

### 2.3. Instalação de Dependências
Após clonar o repositório, instale todas as dependências necessárias para o projeto.

- Para projetos .NET:
  ```bash
  dotnet restore
  ```

- Para projetos Node.js (React.js ou React Native):
  ```bash
  npm install
  ```

### 2.4. Configuração do Banco de Dados
Se o projeto usa um banco de dados, siga estas instruções para configuração:

- **Banco de Dados Local**: Configure o banco de dados conforme necessário para o projeto.
- **Configuração de Conexão**: Atualize os parâmetros de conexão no arquivo de configuração para garantir que a aplicação possa se conectar ao banco de dados.

## 3. Práticas de Controle de Versão
Para manter uma colaboração eficaz no GitHub, siga estas práticas de controle de versão:

- **Criar Branches**: Antes de começar a desenvolver, crie uma nova branch para trabalhar.
  ```bash
  git checkout -b minha-nova-branch
  ```

- **Commits Regulares**: Faça commits frequentes com mensagens claras para documentar seu progresso.
  ```bash
  git add .
  git commit -m "Descrição clara do commit"
  ```

- **Pull Requests e Revisão de Código**: Para contribuir com o branch principal, abra um pull request e peça revisão de código para outro membro da equipe.
  ```bash
  git push origin minha-nova-branch
  ```

## 4. Comunicação e Colaboração
Para garantir uma comunicação eficaz, use estas práticas:

- **Slack/Discord**: Para comunicação rápida e colaboração em tempo real.
- **GitHub Issues**: Para gerenciar tarefas e problemas no projeto.
- **Reuniões Regulares**: Participe de reuniões diárias ou semanais para discutir progresso, identificar problemas e compartilhar atualizações.

## 5. Recursos para Semana de Aprendizado
Para a semana de aprendizado, aqui estão alguns recursos para ajudar a equipe a adquirir conhecimento e habilidades:

- **Tutoriais de C# e .NET**:
  - [Microsoft Docs](https://docs.microsoft.com/pt-br/dotnet/csharp/)
  - [Tutorial de C# - W3Schools](https://www.w3schools.com/cs/)
- **Tutoriais de React.js e React Native**:
  - [React Documentation](https://reactjs.org/docs/getting-started.html)
  - [React Native Docs](https://reactnative.dev/docs/getting-started)
- **Cursos Online**:
  - [Coursera](https://www.coursera.org/)
  - [Udemy](https://www.udemy.com/)

## 6. Recursos para Semana de Produção
Para a semana de produção, aqui estão alguns recursos úteis para ajudar a equipe a ser produtiva e resolver problemas:

- **Git e Controle de Versão**:
  - [Git Documentation](https://git-scm.com/docs)
  - [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
- **Melhores Práticas para Desenvolvimento**:
  - [Clean Code - Livro](https://www.amazon.com.br/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882/)
  - [Design Patterns - Artigo](https://refactoring.guru/design-patterns)

## 7. Linguagens e Tecnologias Usadas
O projeto EventHub usa as seguintes linguagens e tecnologias:

- **Back-end**: C#
- **Front-end**: React.js
- **Mobile**: React Native

## 8. Obter Suporte e Responder Dúvidas
Se você tiver dúvidas ou precisar de suporte, use os canais de comunicação ou entre em contato com o responsável pelo projeto. Use Slack/Discord para perguntas rápidas e GitHub Issues para discutir problemas relacionados ao projeto.
