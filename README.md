# 📱 Meu Assistente Pessoal — PWA

Aplicativo de lembretes pessoais instalável como app no celular.

---

## 🚀 Como subir no Vercel (gratuito, ~3 minutos)

### Opção A — Arrasta e solta (mais fácil)

1. Acesse **https://vercel.com** e crie uma conta grátis (pode entrar com Google)
2. No painel, clique em **"Add New Project"**
3. Clique em **"Upload"** (ou arraste a pasta inteira do projeto)
4. Clique em **Deploy** — pronto, seu app terá um link público!

### Opção B — Via GitHub

1. Crie um repositório no GitHub e faça upload da pasta
2. No Vercel, conecte o repositório
3. Clique em Deploy

---

## 📲 Como instalar no celular

### Android (Chrome)
1. Abra o link do Vercel no Chrome
2. Um banner aparecerá: **"Adicionar à tela inicial"**
3. Toque em instalar — o ícone aparece como um app normal

### iPhone (Safari)
1. Abra o link no **Safari** (obrigatório, não Chrome)
2. Toque no ícone de **Compartilhar** (quadrado com seta)
3. Role e toque em **"Adicionar à Tela Inicial"**
4. Confirme — pronto!

---

## 📁 Estrutura

```
assistente-pwa/
├── index.html      ← App completo (HTML + CSS + JS)
├── manifest.json   ← Configuração do PWA
├── sw.js           ← Service Worker (offline + cache)
├── vercel.json     ← Configuração de headers para Vercel
├── icons/          ← Ícones em todos os tamanhos
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-192.png
│   ├── icon-384.png
│   └── icon-512.png
└── README.md
```

---

## ✅ Funcionalidades

- Lembretes com categorias: contas, estudos, aniversários, saúde, trabalho, e-mail, pessoal
- Prioridade alta / normal / baixa
- Data + hora, badges de vencimento automáticos
- Filtros: Hoje, Atrasados, Essa semana
- Busca por texto e filtro por categoria
- Marcar como feito, editar, excluir
- Funciona 100% offline após a primeira visita
- Dados salvos no dispositivo (localStorage)
- Modo escuro automático (segue o sistema)
- Banner de instalação nativo no Android

---

## ⚠️ Notificações

- **Android**: notificações push funcionam nativamente
- **iPhone**: o app abre normalmente, mas notificações em segundo plano têm limitações no iOS (exige iOS 16.4+)
