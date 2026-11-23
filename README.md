# Stefanne Carla — Portfólio

Site estático (HTML + CSS, sem build). Product Designer com raízes em UX Research.

## Estrutura

```
index.html            Home
case-espaco-do-estudante.html  Case Espaço do Estudante (SENAI)
case-emserh.html      Case EMSERH
assets/
  curriculo-stefanne-carla.pdf
  img/                logo, carimbo, auroras, molduras, órbitas, og-image
vercel.json           URLs limpas (/case-senai em vez de /case-senai.html)
```

## Ver no computador

Abra o `index.html` no navegador (duplo clique). Tudo funciona offline, exceto as fontes do Google Fonts.

## Subir no GitHub

1. Crie um repositório novo em https://github.com/new (ex.: `portfolio`), sem README.
2. Na pasta do projeto, rode:

```bash
git init
git add .
git commit -m "Primeira versão do portfólio"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/portfolio.git
git push -u origin main
```

Sem terminal: no repositório vazio, clique em **uploading an existing file** e arraste todos os arquivos e pastas.

## Publicar na Vercel

1. Entre em https://vercel.com com a sua conta do GitHub.
2. **Add New… → Project** e escolha o repositório `portfolio`.
3. Framework Preset: **Other**. Não precisa de build command nem output directory.
4. Clique em **Deploy**. A cada `git push` o site atualiza sozinho.

Domínio próprio: em **Project → Settings → Domains**.

## Como editar

- **Textos:** direto nos arquivos `.html`. Os trechos entre `[colchetes]` são para você completar.
- **Imagens dos projetos:** coloque os arquivos em `assets/img/` e troque cada placeholder `<span …>[Imagem do projeto]</span>` por
  `<img src="assets/img/NOME.jpg" alt="Descrição da tela" style="width: 100%; height: 100%; object-fit: cover">`.
- **Fotos das polaroids:** mesma coisa nos placeholders `[Sua foto]`.
- **Currículo:** substitua `assets/curriculo-stefanne-carla.pdf` mantendo o mesmo nome.

## Marca

| Cor | Hex |
|---|---|
| Azul-noite | `#0C0A29` |
| Verde | `#90FFC3` |
| Roxo | `#8040FF` |
| Claro | `#E6FFFA` |

Fontes: Yeseva One (títulos), Inter (texto), Caveat (manuscrito) — via Google Fonts.
