# 🌐 Slide Remote — Landing Page

Site institucional do [Slide Remote](https://github.com/victor-damasceno/passador-slide), com download do aplicativo Windows e link de acesso ao controle remoto pelo celular.

🔗 **[site-slide-remote.vercel.app](https://site-slide-remote.vercel.app)**


## 📌 Sobre

Landing page estática desenvolvida em HTML/CSS com o objetivo de apresentar o projeto Slide Remote ao usuário final, oferecendo:

- Download direto do aplicativo `.exe` para Windows
- Link de acesso ao site de controle remoto pelo celular
- Explicação do funcionamento em 3 passos
- Seção de instruções de segurança para instalação do `.exe`


## 🗂️ Estrutura

```
site-slide-remote/
└── index.html    # Página única com HTML, CSS e JS inline
```


## ✨ Seções da página

- **Hero** — título, descrição, botões de ação e mockup visual do fluxo PC → Celular
- **Como funciona** — 3 passos para começar a usar + cards de features
- **Download** — botão de download do `.exe` com link direto para o Google Drive
- **Segurança** — instruções para contornar o aviso do Windows Defender e do Google Drive


## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura e conteúdo |
| CSS3 | Estilização, animações e layout responsivo |
| JavaScript | Navegação e interações mínimas |
| Google Fonts | Tipografia (Syne + DM Mono + Instrument Serif) |
| Vercel | Hospedagem estática com deploy automático via GitHub |


## 🚀 Deploy

O deploy é feito automaticamente pelo **Vercel** a cada push na branch `master`. Não há build step — o Vercel serve o `index.html` diretamente.


## 🔗 Repositórios relacionados

| Repositório | Descrição |
|---|---|
| [passador-slide](https://github.com/victor-damasceno/passador-slide) | Servidor WebSocket + interface do celular |
