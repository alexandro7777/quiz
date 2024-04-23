1. **Reaplicar commits locais sobre o topo de outro branch:**
   - **Utilidade:** Aplicar seus commits sobre o topo de outro branch, reescrevendo a história do branch atual.
   - **Exemplo de contexto:** Você deseja atualizar sua branch atual com as alterações mais recentes do branch `main` antes de criar um pull request.
     ```bash
     git rebase main
     ```

2. **Reaplicar os últimos n commits em um branch específico:**
   - **Utilidade:** Reaplicar os últimos n commits do branch atual sobre outro branch.
   - **Exemplo de contexto:** Você está trabalhando em uma funcionalidade em um branch específico e deseja aplicar apenas os últimos 3 commits sobre o branch `desenvolvimento`.
     ```bash
     git rebase --onto desenvolvimento HEAD~3
     ```

3. **Rebase interativo para rearranjar commits:**
   - **Utilidade:** Rearranjar, editar ou combinar commits durante o processo de rebase.
   - **Exemplo de contexto:** Você deseja rearranjar os commits antes de enviá-los em um pull request, para melhorar a clareza da história do seu código.
     ```bash
     git rebase -i HEAD~3
     ```

4. **Continuar um rebase interrompido após resolver conflitos:**
   - **Utilidade:** Continuar um rebase interrompido após resolver conflitos de mesclagem.
   - **Exemplo de contexto:** Durante um rebase, ocorreram conflitos de mesclagem e você resolveu-os. Agora, deseja continuar o rebase.
     ```bash
     git rebase --continue
     ```

5. **Abortar um rebase em progresso:**
   - **Utilidade:** Abortar um rebase em progresso e restaurar o estado anterior do branch.
   - **Exemplo de contexto:** Durante um rebase, você percebeu que cometeu um erro e deseja abortá-lo para voltar ao estado anterior do branch.
     ```bash
     git rebase --abort
     ```

6. **Reaplicar commits de uma branch específica sobre outra:**
   - **Utilidade:** Reaplicar os commits de uma branch específica sobre outro branch.
   - **Exemplo de contexto:** Você quer aplicar os commits do branch `feature/nova-funcionalidade` sobre o branch `desenvolvimento` antes de criar um pull request.
     ```bash
     git rebase feature/nova-funcionalidade desenvolvimento
     ```