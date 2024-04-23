1. **Enviar commits locais para a branch remota correspondente:**
   - **Utilidade:** Enviar commits locais para a branch remota correspondente no repositório remoto.
   - **Exemplo de contexto:** Após fazer commits locais em uma branch, você deseja enviar esses commits para a branch correspondente no repositório remoto (por exemplo, `main`, `master`).
     ```bash
     git push origin <nome_da_branch>
     ```

2. **Enviar commits locais para uma branch remota com um nome diferente:**
   - **Utilidade:** Enviar commits locais para uma branch remota com um nome diferente da branch local.
   - **Exemplo de contexto:** Você trabalhou em uma branch local chamada `feature/nova-funcionalidade` e agora quer enviar esses commits para uma branch remota chamada `develop`.
     ```bash
     git push origin <nome_da_branch_local>:<nome_da_branch_remota>
     ```

3. **Enviar todos os commits locais para todas as branches remotas:**
   - **Utilidade:** Enviar todos os commits locais para todas as branches remotas do repositório remoto.
   - **Exemplo de contexto:** Após fazer várias alterações e commits locais, você deseja enviar esses commits para todas as branches remotas do repositório.
     ```bash
     git push --all
     ```

4. **Forçar o push dos commits locais, substituindo as alterações no repositório remoto:**
   - **Utilidade:** Forçar o push dos commits locais, substituindo as alterações no repositório remoto, mesmo se isso resultar em perda de commits.
   - **Exemplo de contexto:** Você fez alterações importantes localmente e precisa substituir as alterações no repositório remoto, mesmo que isso resulte na perda de commits no repositório remoto.
     ```bash
     git push --force
     ```

5. **Enviar tags locais para o repositório remoto:**
   - **Utilidade:** Enviar tags locais para o repositório remoto.
   - **Exemplo de contexto:** Você criou uma nova versão do seu projeto e deseja enviar as tags associadas a essa versão para o repositório remoto.
     ```bash
     git push --tags
     ```

6. **Enviar commits locais para a branch remota correspondente e criar a branch se ainda não existir:**
   - **Utilidade:** Enviar commits locais para a branch remota correspondente e criar a branch no repositório remoto se ainda não existir.
   - **Exemplo de contexto:** Você criou uma nova branch localmente e deseja enviá-la para o repositório remoto, criando-a remotamente se ainda não existir.
     ```bash
     git push --set-upstream origin <nome_da_branch>
     ```