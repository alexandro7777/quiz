1. **Mesclar uma branch específica na branch atual:**
   - **Utilidade:** Incorporar as alterações de uma branch específica na branch atual.
   - **Exemplo de contexto:** Você finalizou o desenvolvimento de uma funcionalidade na branch `feature/nova-funcionalidade` e deseja incorporar essas alterações à branch `main`.
     ```bash
     git merge feature/nova-funcionalidade
     ```

2. **Mesclar uma branch específica na branch atual, mantendo um commit de merge explícito:**
   - **Utilidade:** Realizar uma mescla entre branches mantendo um commit de merge explícito na história do repositório.
   - **Exemplo de contexto:** Você quer mesclar as alterações da branch `feature/nova-funcionalidade` na branch `main`, criando um commit de merge explícito.
     ```bash
     git merge --no-ff feature/nova-funcionalidade
     ```

3. **Mesclar uma branch específica na branch atual e resolver conflitos manualmente:**
   - **Utilidade:** Mesclar as alterações de uma branch na atual, permitindo resolver manualmente quaisquer conflitos que possam surgir.
   - **Exemplo de contexto:** Após tentar mesclar a branch `feature/nova-funcionalidade` na `main`, você encontra conflitos de merge que precisam ser resolvidos manualmente.
     ```bash
     git merge feature/nova-funcionalidade
     ```

4. **Mesclar uma branch específica na branch atual e suprimir automaticamente conflitos com a versão atual da branch atual:**
   - **Utilidade:** Mesclar as alterações de uma branch na atual e, se houver conflitos, escolher automaticamente as alterações da branch atual.
   - **Exemplo de contexto:** Você deseja mesclar a branch `feature/nova-funcionalidade` na `main` e, se houver conflitos, prefere manter as alterações da `main`.
     ```bash
     git merge -X ours feature/nova-funcionalidade
     ```

5. **Mesclar uma branch específica na branch atual e suprimir automaticamente conflitos com a versão da branch mesclada:**
   - **Utilidade:** Mesclar as alterações de uma branch na atual e, se houver conflitos, escolher automaticamente as alterações da branch sendo mesclada.
   - **Exemplo de contexto:** Você quer mesclar a branch `feature/nova-funcionalidade` na `main` e, se houver conflitos, prefere manter as alterações da `feature/nova-funcionalidade`.
     ```bash
     git merge -X theirs feature/nova-funcionalidade
     ```

6. **Mesclar uma branch específica na branch atual e abortar o merge em caso de conflitos:**
   - **Utilidade:** Tentar mesclar as alterações de uma branch na atual, mas abortar a operação em caso de conflitos.
   - **Exemplo de contexto:** Você quer mesclar a branch `feature/nova-funcionalidade` na `main`, mas deseja abortar se houver conflitos.
     ```bash
     git merge --abort feature/nova-funcionalidade
     ```