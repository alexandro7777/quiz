1. **Commitar todas as mudanças no índice:**
   - **Utilidade:** Registrar todas as alterações preparadas (staged) no repositório.
   - **Exemplo de contexto:** Você finalizou algumas alterações em diferentes arquivos e deseja registrá-las como um único commit.
     ```bash
     git commit -m "Mensagem do commit"
     ```

2. **Commitar mudanças em arquivos específicos:**
   - **Utilidade:** Registrar apenas as alterações nos arquivos especificados.
   - **Exemplo de contexto:** Você fez alterações em arquivos específicos e deseja commitar apenas essas mudanças.
     ```bash
     git commit arquivo1.txt arquivo2.txt -m "Mensagem do commit"
     ```

3. **Commitar todas as mudanças, incluindo arquivos não rastreados:**
   - **Utilidade:** Registrar todas as alterações no repositório, incluindo arquivos não rastreados.
   - **Exemplo de contexto:** Você deseja registrar todas as mudanças no repositório, incluindo novos arquivos não rastreados.
     ```bash
     git commit -a -m "Mensagem do commit"
     ```

4. **Realizar um commit sem adicionar mensagem no terminal:**
   - **Utilidade:** Permitir que você insira a mensagem de commit diretamente no editor de texto padrão.
   - **Exemplo de contexto:** Você prefere inserir a mensagem de commit em um editor de texto separado.
     ```bash
     git commit
     ```

5. **Amendando o último commit com novas alterações:**
   - **Utilidade:** Adicionar novas alterações ao último commit sem criar um novo commit.
   - **Exemplo de contexto:** Você esqueceu de incluir algumas alterações no último commit e deseja adicioná-las sem criar um novo commit.
     ```bash
     git commit --amend
     ```

6. **Amendando o último commit com uma nova mensagem:**
   - **Utilidade:** Alterar a mensagem do último commit sem adicionar novas alterações.
   - **Exemplo de contexto:** Você percebeu que a mensagem do último commit não está clara e deseja corrigi-la.
     ```bash
     git commit --amend -m "Nova mensagem do commit"
     ```

7. **Commitar apenas as alterações no cabeçalho da indexação:**
   - **Utilidade:** Registrar apenas as alterações no cabeçalho da indexação (staging area).
   - **Exemplo de contexto:** Você deseja commitar apenas as alterações no cabeçalho da indexação e manter as alterações nos arquivos no diretório de trabalho.
     ```bash
     git commit --only
     ```