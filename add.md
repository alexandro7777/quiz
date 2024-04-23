1. **Adicionar todas as alterações no diretório de trabalho ao índice (staging area):**
   - **Utilidade:** Preparar todas as alterações no diretório de trabalho para o próximo commit.
   - **Exemplo de contexto:** Você fez várias alterações em diferentes arquivos e deseja prepará-las para o próximo commit.
     ```bash
     git add .
     ```

2. **Adicionar alterações em um arquivo específico ao índice:**
   - **Utilidade:** Preparar as alterações em um arquivo específico para o próximo commit.
   - **Exemplo de contexto:** Você modificou o arquivo `app.js` e deseja preparar apenas essas alterações para o próximo commit.
     ```bash
     git add app.js
     ```

3. **Adicionar alterações em todos os arquivos de um diretório específico ao índice:**
   - **Utilidade:** Preparar as alterações em todos os arquivos de um diretório específico para o próximo commit.
   - **Exemplo de contexto:** Você fez alterações em vários arquivos dentro do diretório `src/` e deseja prepará-las para o próximo commit.
     ```bash
     git add src/
     ```

4. **Adicionar todas as alterações, incluindo arquivos excluídos, ao índice:**
   - **Utilidade:** Preparar todas as alterações, incluindo arquivos excluídos, no diretório de trabalho para o próximo commit.
   - **Exemplo de contexto:** Você excluiu alguns arquivos e deseja preparar todas as alterações, incluindo as exclusões, para o próximo commit.
     ```bash
     git add --all
     ```

5. **Adicionar alterações interativamente ao índice:**
   - **Utilidade:** Selecionar interativamente quais alterações incluir no próximo commit.
   - **Exemplo de contexto:** Você fez várias alterações em diferentes arquivos e deseja selecionar manualmente quais delas incluir no próximo commit.
     ```bash
     git add -i
     ```

6. **Adicionar todas as alterações, exceto arquivos não rastreados, ao índice:**
   - **Utilidade:** Preparar todas as alterações no diretório de trabalho para o próximo commit, excluindo arquivos não rastreados.
   - **Exemplo de contexto:** Você fez várias alterações e adicionou alguns novos arquivos, mas deseja preparar apenas as alterações existentes para o próximo commit.
     ```bash
     git add --update
     ```

7. **Adicionar alterações ignorando os padrões definidos no arquivo `.gitignore`:**
   - **Utilidade:** Preparar todas as alterações, ignorando os arquivos definidos nos padrões do arquivo `.gitignore`, para o próximo commit.
   - **Exemplo de contexto:** Você deseja preparar todas as alterações, exceto aquelas definidas nos padrões do arquivo `.gitignore`, para o próximo commit.
     ```bash
     git add --ignore-errors
     ```