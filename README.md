# 💰 Meu Controle

Controle de gastos compartilhado com sincronização em nuvem.

## ✨ Funcionalidades

- 🔐 Login/cadastro automático por e-mail
- ☁️ Sincronização em tempo real (JSONBin)
- 🎯 **Meta de gastos mensal** com indicador visual:
  - 🟢 Verde: abaixo de 60%
  - 🟡 Amarelo: entre 60–85%
  - 🟠 Laranja pulsando: 85–99%
  - 🔴 Vermelho pulsando: limite ultrapassado
- 📊 Relatório por categoria com barras de progresso
- 🌙 Modo escuro / claro
- 📥 Exportar PDF
- 📱 **PWA** — funciona como app no Android e iOS
- 🔄 Ciclos de controle com reset

## 🚀 Publicar no GitHub Pages

### Passo 1 — Crie um repositório no GitHub
1. Acesse https://github.com/new
2. Dê o nome `meu-controle` (ou qualquer outro)
3. Clique em **Create repository**

### Passo 2 — Faça upload dos arquivos
Na página do repositório recém-criado, clique em **"uploading an existing file"**  
e envie todos estes arquivos:
```
index.html
manifest.json
icons/
  ├── icon-192x192.png
  ├── icon-512x512.png
  ├── apple-touch-icon.png
  ├── favicon-32x32.png
  └── favicon-16x16.png
```

### Passo 3 — Ativar GitHub Pages
1. No repositório, vá em **Settings → Pages**
2. Em **Source**, selecione `Deploy from a branch`
3. Escolha `main` / `root`
4. Clique em **Save**

Após alguns minutos o site estará em:  
`https://SEU_USUARIO.github.io/meu-controle`

## 📲 Adicionar à tela inicial do Android

1. Abra o link no **Chrome para Android**
2. Toque no menu (⋮) → **"Adicionar à tela inicial"**
3. O app aparecerá com ícone próprio como um app nativo!

## 📲 iOS (iPhone/iPad)

1. Abra no **Safari**
2. Toque no botão de compartilhar (□↑)
3. Toque em **"Adicionar à Tela de Início"**

## 💡 Como usar

Digite no campo de lançamento no formato:
```
categoria $valor
```

Exemplos:
- `mercado $45,90`
- `ifood 32`
- `gasolina $80`
- `farmacia $23,50`

Pressione **Enter** ou clique em "Adicionar Despesa".
