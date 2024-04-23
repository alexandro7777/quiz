1. **Mudar para uma branch:**
   - **Utilidade:** Alterar o branch atual para o especificado.
   - **Exemplo de contexto:** Você deseja mudar para a branch `feature/nova-funcionalidade` para começar a trabalhar nela.
     ```bash
     git checkout feature/nova-funcionalidade
     ```

2. **Criar uma nova branch e mudar para ela:**
   - **Utilidade:** Criar uma nova branch e mudar imediatamente para ela.
   - **Exemplo de contexto:** Você quer começar a trabalhar em uma nova funcionalidade e deseja criar uma nova branch chamada `nova-funcionalidade` e mudar para ela.
     ```bash
     git checkout -b nova-funcionalidade
     ```

3. **Desfazer as modificações em um arquivo:**
   - **Utilidade:** Desfazer as modificações em um arquivo e restaurá-lo ao estado do último commit.
   - **Exemplo de contexto:** Você fez algumas alterações indesejadas em `arquivo.txt` e deseja desfazê-las.
     ```bash
     git checkout -- arquivo.txt
     ```

4. **Criar um novo branch a partir de um commit específico:**
   - **Utilidade:** Criar uma nova branch iniciando a partir de um commit específico.
   - **Exemplo de contexto:** Você deseja criar uma branch `correcao-bug` a partir do commit `abcd1234`.
     ```bash
     git checkout -b correcao-bug abcd1234
     ```

5. **Mudar para um commit específico (modo detached HEAD):**
   - **Utilidade:** Visualizar um commit específico sem criar uma nova branch.
   - **Exemplo de contexto:** Você quer inspecionar o commit `abcd1234` sem mudar o branch atual.
     ```bash
     git checkout abcd1234
     ```

6. **Criar um novo branch a partir de uma branch remota:**
   - **Utilidade:** Criar uma nova branch local a partir de uma branch remota.
   - **Exemplo de contexto:** Você deseja criar uma nova branch `feature/nova-funcionalidade` a partir da branch remota com o mesmo nome.
     ```bash
     git checkout -b feature/nova-funcionalidade origin/feature/nova-funcionalidade
     ```

7. **Mudar para o último commit de uma branch:**
   - **Utilidade:** Retornar ao último commit de uma branch sem criar uma nova.
   - **Exemplo de contexto:** Você está trabalhando em `feature/alteracoes` e deseja retornar ao último commit dessa branch.
     ```bash
     git checkout feature/alteracoes
     ```