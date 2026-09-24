# SST Digital — Landing Page

Landing page acadêmica do ecossistema **SST Digital: Tecnologia a Serviço da Segurança**.

**Repositório:** [apppoletto-etec/landingPage](https://github.com/apppoletto-etec/landingPage)

## Estrutura

```text
Page/
├── assets/       # Logos e imagens
├── favicon.svg   # Ícone do site
├── index.html    # Conteúdo e estrutura
├── script.js     # Animações e comportamentos
└── styles.css    # Identidade visual e responsividade
```

## Prévia local

Na pasta `Page`, execute:

```bash
python -m http.server 4173
```

Depois acesse `http://127.0.0.1:4173`.

## Publicação

Este site é mantido em um repositório próprio, separado dos aplicativos Android. A hospedagem recomendada é o GitHub Pages, usando a branch `main` e a raiz do repositório.

As APKs permanecem armazenadas no Firebase Storage e seus links públicos estão configurados em `index.html`.
