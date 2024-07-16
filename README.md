![Static Badge](https://img.shields.io/badge/Ariel%20Spencer-Pull%20request-%238732D7) ![GitHub License](https://img.shields.io/github/license/arielspencer/pull-request)

# Como Fazer um Pull Request

_Pull request_ é uma forma de contribuir para projetos de código aberto. Eles permitem que você envie suas alterações para revisão e possível inclusão no repositório principal.

## Para que Serve um Pull Request?

Um _pull request_ serve para:

- **Contribuir com Código:** Adicionar novas funcionalidades ou corrigir bugs.
- **Revisão de Código:** Permitir que outros desenvolvedores revisem e discutam suas alterações antes de serem mescladas ao projeto.
- **Colaboração:** Facilitar a colaboração em projetos de código aberto, garantindo que as contribuições sejam integradas de maneira organizada.

## Como Fazer um Pull Request

Siga os passos abaixo para criar um _pull request_:

1. **Fork o Repositório:**
  Vá para a página do repositório no GitHub e clique no botão **"Fork"** para criar uma cópia do repositório na sua conta.

2. **Clone o Repositório Forked:**
  No seu terminal, clone o repositório forked para o seu ambiente local:
  ```
  git clone https://github.com/seu-usuario/nome-do-repositorio.git
  ```

3. **Navegue até o diretório do repositório clonado:**
  ```
  cd nome-do-repositorio
  ```

4.	**Crie uma Nova Branch:**
  ```
  git checkout -b minha-feature
  ```

5.	**Faça as Alterações:**
  Faça suas alterações no código. Certifique-se de testar suas mudanças localmente.

6.	**Commit suas Alterações:**
  Adicione os arquivos modificados ao commit e escreva uma mensagem clara e descritiva:
  ```
  git add .
  git commit -m "Descrição clara da minha feature"
  ```

7.	Envie a Branch para o seu Fork:
  Envie sua branch para o repositório forked no GitHub:
  ```
  git push origin minha-feature
  ```

8.	Abra um Pull Request:
  - Vá para a página do repositório original no GitHub.
  - Clique na aba “Pull requests”.
  - Clique no botão “New pull request”.
  - Selecione a branch com suas alterações no repositório forked.
  - Preencha o título e a descrição do pull request.
  - Clique em “Create pull request”.

## Dicas para um Bom Pull Request

  - **Seja Claro e Conciso:** Certifique-se de que o título e a descrição do seu pull request explicam claramente o que foi alterado e por quê.
  - **Referencie Issues Relacionadas:** Se o seu pull request resolver uma issue, mencione-a na descrição, por exemplo: Resolves #123.
  - **Siga as Convenções de Código:** Garanta que suas alterações sigam os padrões e convenções do projeto.
  - **Inclua Testes:** Se possível, inclua testes para suas alterações e verifique se todos os testes existentes ainda passam.

---
Ao seguir estas etapas e dicas, você contribuirá de maneira eficaz para o projeto.
---
Não se esqueça de conferir também como abrir uma issue para sugestões ou reportar problemas: [Issues](https://github.com/ArielSpencer/Issue).
