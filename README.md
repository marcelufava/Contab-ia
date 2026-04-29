# Contab IA — App de Contabilidade com IA

App PWA de contabilidade com escaneamento automático de notas fiscais via IA.

## Como fazer deploy no Vercel (gratuito)

### Passo 1 — Suba o projeto no GitHub

1. Acesse https://github.com e crie uma conta (se não tiver)
2. Clique em **New repository** → nomeie como `contab-ia`
3. No seu computador, dentro da pasta do projeto:

```bash
git init
git add .
git commit -m "primeiro commit"
git remote add origin https://github.com/SEU_USUARIO/contab-ia.git
git push -u origin main
```

### Passo 2 — Deploy no Vercel

1. Acesse https://vercel.com e entre com sua conta GitHub
2. Clique em **Add New → Project**
3. Selecione o repositório `contab-ia`
4. Clique em **Deploy** (as configurações já estão corretas)
5. Aguarde ~1 minuto → seu app estará online!

### Passo 3 — Instalar no celular como app

**Android (Chrome):**
1. Abra a URL do Vercel no Chrome
2. Toque no menu ⋮ → **"Adicionar à tela inicial"**
3. Confirme → o ícone aparece na tela inicial como um app!

**iPhone (Safari):**
1. Abra a URL no Safari
2. Toque no botão compartilhar ↑
3. Role e toque em **"Adicionar à Tela de Início"**
4. Confirme → app instalado!

## Rodar localmente

```bash
npm install
npm run dev
```

Acesse http://localhost:5173

## Estrutura do projeto

```
contab-ia/
├── public/
│   ├── icon-192.png    # Ícone do app
│   └── icon-512.png
├── src/
│   ├── App.jsx         # App principal
│   └── main.jsx        # Entry point
├── index.html          # HTML com meta tags PWA
├── vite.config.js      # Config com plugin PWA
├── vercel.json         # Config do deploy
└── package.json
```
