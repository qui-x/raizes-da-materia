# Raízes da Matéria

Jogo educativo original de Química e Libras. A versão principal será um jogo **web mobile multiplayer**, com mestre e até quatro jogadores em uma sala compartilhada; a versão física será complementar.

## Tabuleiros
- **Árvore da Descoberta**: mapa SVG de 48 casas com navegação vertical/horizontal, bifurcações e quatro tipos de encontros.
- **Tabela Periódica**: estrutura científica de 118 posições com 50 elementos jogáveis das famílias A. O domínio é indicado por quatro cores e símbolos.

## Tecnologia
React + TypeScript + Tailwind CSS + SVG, Vite, GitHub Pages e backend futuro no Supabase. Arquitetura de salas descrita em [docs/arquitetura-multijogador.md](docs/arquitetura-multijogador.md).

## Desenvolvimento local
```bash
npm install
npm run dev
npm run build
```

## Publicação
O workflow `.github/workflows/pages.yml` prepara o site para GitHub Pages quando a branch for integrada na `main` e em **Settings → Pages → Build and deployment → Source** for escolhido **GitHub Actions**.

A URL prevista, após ativar a publicação, é `https://qui-x.github.io/raizes-da-materia/`. Não presumir que esteja publicada antes de verificar o workflow e o Pages.

## Estado da versão 0.1
O front-end é uma **demonstração local** de mapa e Tabela Periódica. A conquista de elementos é simulada; o sistema ainda não comprova desafios em Libras nem permite salas online. As respostas científicas e os sinais-termo deverão ser validados por especialistas. A sincronização real requer o projeto Supabase e suas regras de segurança.
