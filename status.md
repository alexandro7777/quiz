1. **Verificar o estado do repositório:**
   - **Utilidade:** Exibir o estado atual do repositório Git, incluindo arquivos modificados, adicionados, removidos e não rastreados.
   - **Exemplo de contexto:** Antes de fazer um commit, você deseja verificar quais arquivos foram modificados e quais estão prontos para serem adicionados ao próximo commit.
     ```bash
     git status
     ```

2. **Verificar o estado de um arquivo específico:**
   - **Utilidade:** Exibir o estado de um arquivo específico no repositório.
   - **Exemplo de contexto:** Você quer saber se o arquivo `app.js` foi modificado em relação à versão no último commit.
     ```bash
     git status app.js
     ```

3. **Exibir o estado de arquivos não rastreados:**
   - **Utilidade:** Listar arquivos no diretório de trabalho que ainda não foram adicionados ao índice.
   - **Exemplo de contexto:** Você deseja ver quais arquivos novos ou não rastreados estão no diretório de trabalho.
     ```bash
     git status -u
     ```

4. **Exibir o estado em formato porcelana (machine-readable):**
   - **Utilidade:** Exibir o estado do repositório em um formato que pode ser facilmente interpretado por scripts ou ferramentas.
   - **Exemplo de contexto:** Você está escrevendo um script que precisa verificar o estado do repositório Git.
     ```bash
     git status --porcelain
     ```

5. **Exibir o estado excluindo arquivos não rastreados:**
   - **Utilidade:** Exibir apenas informações sobre arquivos rastreados no repositório.
   - **Exemplo de contexto:** Você quer saber apenas sobre arquivos que estão sob controle de versão, ignorando quaisquer arquivos não rastreados.
     ```bash
     git status --untracked-files=no
     ```

6. **Exibir o estado ignorando arquivos não rastreados:**
   - **Utilidade:** Exibir apenas informações sobre arquivos rastreados e ignorar arquivos não rastreados.
   - **Exemplo de contexto:** Você quer focar apenas nos arquivos que estão sob controle de versão e ignorar os novos arquivos que não estão sendo rastreados.
     ```bash
     git status --untracked-files=no
     ```