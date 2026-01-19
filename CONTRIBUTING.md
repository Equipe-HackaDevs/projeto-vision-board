# Contribuição e Workflow (Git Flow)

Para manter a integridade do código e a organização das duplas, seguimos um fluxo de trabalho profissional:

### 1. Criação de Branch

Antes de iniciar qualquer tarefa, crie uma branch seguindo o padrão:

- **Frontend:** `feat/front-[nome-da-secao]` (Ex: `feat/front-header`)
- **Backend:** `feat/back-[funcionalidade]` (Ex: `feat/back-api-imagens`)

### 2. Padrão de Commits

Utilizamos **Conventional Commits** para facilitar a leitura do histórico:

- `feat`: para novas funcionalidades.
- `fix`: para correção de bugs.
- `style`: para ajustes de CSS e layout (Pixel Perfect).
- `docs`: para atualizações de documentação.

### 3. Como abrir um Pull Request (PR)

1. Certifique-se de que seu código está limpo e sem erros de linting.
2. Realize o Push para a sua branch.
3. No GitHub, abra um Pull Request para a branch `main`.
4. **Obrigatório:** No título do PR, descreva o que foi feito e marque sua dupla.
5. Aguarde o **Code Review** da Tech Lead (Bianca Caetano) ou da responsável por Qualidade (Julie) antes do Merge.