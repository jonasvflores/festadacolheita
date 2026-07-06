# Gincana Festa da Colheita - Colégio Príncipe da Paz

Este é um site estático projetado para rodar em uma TV durante a gincana, com atualização automática a cada 50 minutos.

## Como colocar o site no ar (GitHub Pages)

1. Crie um novo repositório no seu GitHub (ex: `gincana-colheita`).
2. Suba todos os arquivos desta pasta para o repositório.
3. Vá em **Settings** > **Pages**.
4. Em **Build and deployment**, selecione a branch `main` e a pasta `/ (root)`. Clique em **Save**.
5. O site estará disponível em `https://seu-usuario.github.io/nome-do-repo/`.

## Como atualizar os pontos (Painel Admin)

O administrador pode atualizar os pontos sem mexer no código através da página `admin.html`:

1. Acesse `https://seu-usuario.github.io/nome-do-repo/admin.html`.
2. Você precisará de um **GitHub Personal Access Token (Classic)** com permissão de `repo`.
   - Gere um em: GitHub Settings > Developer Settings > Personal access tokens > Tokens (classic).
3. Insira o token e o caminho do repositório (ex: `seu-usuario/gincana-colheita`).
4. Altere os valores e clique em **Salvar Alterações**.
5. O arquivo `data.json` será atualizado automaticamente no GitHub, e a TV refletirá a mudança na próxima atualização (ou se você der F5 nela).

## Configuração da TV

- Abra o navegador da TV no endereço do site (`index.html`).
- O site já está configurado para recarregar sozinho a cada 50 minutos (3000 segundos).
- O layout foi otimizado para visualização em telas grandes (Full HD/4K).
