## Atividade com Git: Contribuição e Resolução de Conflitos

### Objetivo:
Nesta atividade, você aprenderá a contribuir com um projeto colaborativo usando o Git e GitHub. Você fará um fork de um repositório da professora, adicionará seu nome a um arquivo `LISTA.md`, fará um commit das alterações, enviará essas alterações para seu repositório forkado no GitHub e criará um Pull Request para contribuir de volta ao repositório original da professora. Você também aprenderá a resolver conflitos de merge diretamente no GitHub.

### Passo a Passo:

#### Para Começar:

1. **Fork do Repositório:**
   - Faça login na sua conta do GitHub.
   - Acesse o repositório fornecido pela professora.
   - Clique no botão "Fork" no canto superior direito da página para criar uma cópia do repositório na sua conta do GitHub.

2. **Clone do Repositório Forkado:**
   - Abra o terminal (Git Bash no Windows, Terminal no macOS/Linux).
   - Clone o repositório forkado para sua máquina local:
     ```bash
     git clone <URL do seu repositório forkado>
     cd <nome-do-repositório>
     ```

3. **Criação de uma Branch:**
   - Crie uma nova branch para suas alterações (substitua `<nome-da-sua-branch>` pelo nome que você escolher):
     ```bash
     git checkout -b <nome-da-sua-branch>
     ```

#### Edição do Arquivo `LISTA.md`:

4. **Adicione Seu Nome:**
   - Abra o arquivo `LISTA.md` no seu editor de texto favorito.
   - Adicione seu nome à lista de alunos.

#### Commit e Envio das Alterações:

5. **Commit das Alterações:**
   - Adicione suas alterações ao índice (stage) e faça o commit:
     ```bash
     git add LISTA.md
     git commit -m "Adicionando meu nome à lista de alunos"
     ```

6. **Envio das Alterações:**
   - Envie suas alterações para seu repositório forkado no GitHub:
     ```bash
     git push origin <nome-da-sua-branch>
     ```

#### Criação do Pull Request:

7. **Abra um Pull Request (PR):**
   - Visite seu repositório forkado no GitHub.
   - Clique no botão "Compare & pull request" ao lado da sua nova branch.
   - Preencha o formulário do Pull Request descrevendo suas alterações e clique em "Create pull request".

#### Resolução de Conflitos (se necessário):

8. **Resolva Conflitos de Merge:**
   - Se houver conflitos de merge, você os verá na página do seu Pull Request.
   - Clique no botão "Resolve conflicts" para resolver os conflitos diretamente no GitHub.
   - Após resolver os conflitos, faça commit das alterações de merge.

#### Finalização da Contribuição:

9. **Merge das Alterações no Repositório Original:**
   - Solicite à professora para fazer o merge das suas alterações no repositório original.
   - Verifique se suas alterações foram incorporadas ao arquivo `LISTA.md` no repositório original da professora.

---

### Considerações Finais:

- **Feedback e Discussão:** Após a atividade, discuta com seus colegas sobre o processo de colaboração, revisão de código e resolução de conflitos diretamente no GitHub. Aproveite para revisar os Pull Requests uns dos outros e aprender com as contribuições dos colegas.

- **Boas Práticas:** Lembre-se de fazer commits atômicos, usar mensagens claras de commit e seguir práticas eficazes de colaboração ao trabalhar em projetos compartilhados com Git.

Essa atividade proporcionará a você uma experiência prática valiosa com o Git e GitHub, além de ensinar habilidades essenciais de colaboração e trabalho em equipe no desenvolvimento de software.