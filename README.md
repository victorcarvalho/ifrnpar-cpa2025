# Relatório de Autoavaliação IFRN - Página Estática

Esta é uma página web estática que apresenta uma versão visual do conteúdo do Relatório de Autoavaliação Institucional 2025 do IFRN - Campus Parnamirim.

Acesso online: https://victorcarvalho.github.io/ifrnpar-cpa2025/


O conteúdo apresentado aqui foi extraído e organizado a partir do arquivo oficial `AAI 2025.pdf` (incluído neste repositório). Os dados exibidos devem ser validados sempre junto à fonte oficial antes de qualquer uso decisório.

Publicação no GitHub Pages

1. Crie um repositório no GitHub e envie (push) o conteúdo desta pasta como raiz do repositório.
2. Em **Settings > Pages**, selecione a branch `main` e o diretório raiz (`/`) como fonte.
3. Aguarde alguns minutos até a URL ser disponibilizada.

Comandos rápidos (substitua `USERNAME/REPO`):

```bash
git init
git add .
git commit -m "Initial commit: página estática do AAI 2025"
git branch -M main
git remote add origin git@github.com:USERNAME/REPO.git
git push -u origin main
```

Ou crie e publique em um passo com o GitHub CLI:

```bash
gh repo create USERNAME/REPO --public --source=. --remote=origin --push
```

Observações

- Arquivos estáticos (Tailwind, Chart.js, FontAwesome) são carregados via CDN. Para produção recomenda-se travar versões ou servir localmente.
- O arquivo `AAI 2025.pdf` incluído é a referência oficial; verifique-o para confirmar números e trechos antes de republicar.
- Para testes locais, use um servidor estático simples (por exemplo `python -m http.server 8000`).

Contato

Se quiser que eu faça o push para um repositório remoto ou habilite o GitHub Pages, me informe a URL do repositório ou autorize a criação com `gh`.

## Nota sobre prototipagem

Esta página foi prototipada com auxílio de inteligência artificial — a versão inicial visual foi criada usando o Gemini 3.8 Flash como ponto de partida e posteriormente refinada no HTML/CSS/JS do repositório.
