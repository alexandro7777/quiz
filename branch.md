1. **Listar branches:**
   - **Utilidade:** Visualizar todas as branches disponíveis no repositório.
   - **Exemplo de contexto:** Você deseja verificar quais branches estão disponíveis antes de decidir em qual trabalhar.
     ```bash
     git branch
     ```

2. **Criar uma nova branch:**
   - **Utilidade:** Iniciar o desenvolvimento de uma nova funcionalidade ou correção em um ambiente isolado.
   - **Exemplo de contexto:** Você está começando a trabalhar em uma nova funcionalidade e precisa criar uma branch específica para ela.
     ```bash
     git branch <nome_da_branch>
     ```

3. **Criar uma nova branch e mudar para ela:**
   - **Utilidade:** Agilizar o processo de criação e mudança para uma nova branch em um único comando.
   - **Exemplo de contexto:** Você deseja iniciar imediatamente o trabalho em uma nova funcionalidade em uma branch recém-criada.
     ```bash
     git branch -b <nome_da_branch>
     ```

4. **Renomear uma branch localmente:**
   - **Utilidade:** Alterar o nome de uma branch localmente sem precisar de passos adicionais.
   - **Exemplo de contexto:** Você decidiu mudar o nome de uma branch para refletir melhor sua funcionalidade ou propósito.
     ```bash
     git branch -m <novo_nome>
     ```

5. **Excluir uma branch:**
   - **Utilidade:** Remover uma branch após seu trabalho ser concluído e mesclado com sucesso.
   - **Exemplo de contexto:** Você finalizou o trabalho em uma branch de correção de bug e deseja removê-la após mesclá-la ao branch principal.
     ```bash
     git branch -d <nome_da_branch>
     ```

6. **Excluir uma branch forçadamente:**
   - **Utilidade:** Forçar a exclusão de uma branch, mesmo que suas alterações não tenham sido mescladas.
   - **Exemplo de contexto:** Você precisa remover uma branch que não será mais utilizada e não se importa em perder as alterações não mescladas.
     ```bash
     git branch -D <nome_da_branch>
     ```

7. **Listar branches remotas:**
   - **Utilidade:** Visualizar as branches presentes no repositório remoto.
   - **Exemplo de contexto:** Você quer ver quais branches estão disponíveis no repositório remoto antes de fazer o pull de alguma delas.
     ```bash
     git branch -r
     ```

8. **Listar todas as branches (locais e remotas):**
   - **Utilidade:** Exibir uma lista completa de todas as branches, tanto locais quanto remotas.
   - **Exemplo de contexto:** Você está investigando a estrutura do repositório e quer ver todas as branches disponíveis, incluindo as remotas.
     ```bash
     git branch -a
     ```
