# 🏛️ Ludus Latinus

Um jogo de plataforma arcade 2D educativo para aprender vocabulário e declinações em **Latim**, ambientado na Roma Antiga.

---

## 🚀 Como Subir no GitHub

### Opção 1: Pelo site do GitHub (Sem instalar nada)
1. Acesse [github.com](https://github.com) e crie um novo repositório chamado `ludus-latinus`.
2. Na página do repositório vazio, clique em **"uploading an existing file"** (enviar arquivos existentes).
3. Arraste todos os arquivos desta pasta para lá:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.svg`
   - `icon-192.png`
   - `icon-512.png`
   - `vercel.json`
   - `.gitignore`
   - `README.md`
4. Clique em **"Commit changes"**. Pronto!

### Opção 2: Pelo Git (Linha de comando)
Se você tiver o Git instalado no seu computador:
```bash
git init
git add .
git commit -m "feat: Ludus Latinus PWA"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/ludus-latinus.git
git push -u origin main
```

---

## ⚡ Como Publicar na Vercel (Grátis)

1. Acesse [vercel.com](https://vercel.com) e faça login com a sua conta do GitHub.
2. Clique no botão **"Add New..."** ➔ **"Project"**.
3. Localize o repositório `ludus-latinus` na lista e clique em **"Import"**.
4. Em **Framework Preset**, deixe como `Other` (já configurado via `vercel.json`).
5. Clique em **"Deploy"**.
6. Em menos de 1 minuto seu jogo estará online com HTTPS gratuito e pronto para jogar e instalar no celular!

---

## 📱 Recursos do Jogo

- **Progressive Web App (PWA)**: Pode ser instalado como aplicativo nativo no celular (Android/iOS) ou no computador.
- **100% Offline**: Funciona sem internet através do Service Worker (`sw.js`).
- **Design Responsivo**: Adaptado para telas de celular, tablet e computador, com controles virtuais ergonômicos e suporte à vibração tátil.
- **Áudio Nativo (Web Audio API)**: Sons de pulo, moedas, lobos, alertas e trilha sonora em modo dórico sem necessidade de baixar arquivos pesados.
- **Sem Limite de Tempo**: Ideal para estudar e fixar o vocabulário e os casos gramaticais de latim com calma.
