1. **git init**
   - **Utilidade:** Inicializa um repositório Git em um diretório.
   - **Exemplo de contexto:** Você deseja começar a rastrear as alterações em um novo projeto.
     ```bash
     git init
     ```

2. **git clone**
   - **Utilidade:** Clona um repositório Git existente para um novo diretório.
   - **Exemplo de contexto:** Você quer fazer uma cópia de um projeto existente para trabalhar nele localmente.
     ```bash
     git clone <url_do_repositório>
     ```

3. **git add**
   - **Utilidade:** Adiciona alterações no diretório de trabalho ao índice (staging area).
   - **Exemplo de contexto:** Você fez algumas alterações em arquivos e deseja prepará-las para o próximo commit.
     ```bash
     git add arquivo_modificado
     ```
     ```bash
     git add .
     ```

4. **git commit**
   - **Utilidade:** Registra as alterações no repositório.
   - **Exemplo de contexto:** Você finalizou um conjunto de alterações e deseja adicioná-las ao histórico do repositório.
     ```bash
     git commit -m "mensagem do commit"
     ```

5. **git push**
   - **Utilidade:** Envia commits locais para o repositório remoto.
   - **Exemplo de contexto:** Você deseja compartilhar suas alterações com outros colaboradores ou fazer backup no repositório remoto.
     ```bash
     git push origin <branch>
     ```

6. **git pull**
   - **Utilidade:** Recupera as alterações do repositório remoto e as mescla com o branch local.
   - **Exemplo de contexto:** Você deseja atualizar seu branch local com as alterações feitas por outros colaboradores.
     ```bash
     git pull origin <branch>
     ```

7. **git branch**
   - **Utilidade:** Lista, cria ou exclui branches.
   - **Exemplo de contexto:** Você deseja criar uma nova branch para trabalhar em uma funcionalidade específica.
     ```bash
     git branch nome_da_branch
     ```

8. **git checkout**
   - **Utilidade:** Alterna entre branches ou restaura arquivos.
   - **Exemplo de contexto:** Você deseja mudar para uma branch diferente ou restaurar um arquivo para uma versão anterior.
     ```bash
     git checkout nome_da_branch
     ```

9. **git merge**
   - **Utilidade:** Mescla alterações de uma branch para outra.
   - **Exemplo de contexto:** Você concluiu o trabalho em uma branch de funcionalidade e deseja incorporar essas alterações na branch principal.
     ```bash
     git merge nome_da_branch
     ```

10. **git status**
    - **Utilidade:** Exibe o estado atual do repositório.
    - **Exemplo de contexto:** Você quer saber quais arquivos foram modificados e quais estão prontos para serem commitados.
      ```bash
      git status
      ```
