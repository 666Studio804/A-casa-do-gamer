# 🎮 A CASA DO GAMER
> O melhor site de download de apps e mods gamer - Seguro, rápido e verificado.

![Status](https://img.shields.io/badge/status-online-00ffc8?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-00f5ff?style=for-the-badge&logo=github)
![Neon](https://img.shields.io/badge/Theme-Neon%20Gamer-8a2be2?style=for-the-badge)

---

## 🔗 Acesso Rápido

**🌐 Site no ar:** `https://666Studio804.github.io/a-casa-do-gamer/`
**👤 Conta:** `666Studio804`
**📦 Repositório:** `A casa do gamer`

---

## ✨ Funcionalidades

### 🔐 Sistema de Login Completo (Frontend)
- Modal com Login e Cadastro
- Salvo no localStorage (sem backend, 100% GitHub Pages)
- Avatar + nome no header quando logado
- Trava de download: só baixa se estiver logado

### 📥 Sistema de Download de Apps
- Grid com 8 apps mockados: Gamer Booster Pro, FPS Unlocker, Crosshair Custom, etc
- Cada card: ícone, rating, tamanho, downloads, categoria, botão BAIXAR neon
- Barra de pesquisa + filtro por categoria
- Seção "Mais Baixados da Semana"
- Download simulado com barra de progresso

### ➕ Adicionar App (Só logado)
Botão `+ ADICIONAR APP` no header que abre modal de edição com 6 campos:

1.  **Nome** - Nome do app/jogo
2.  **Descrição** - Descrição completa
3.  **Arquivo** - Upload que SÓ aceita `.EXE` e `.APK` (validação nativa)
4.  **Ícone** - Upload de imagem com preview ao vivo
5.  **Visualização / Banner** - Screenshot/banner 16:9 com preview
6.  **Categoria** - Performance, Utilitário, Streaming, Personalização, Áudio, Otimização, Mod, Ferramenta

> Todos os campos de arquivo usam `<input type="file">` nativo, que abre o app **Arquivos** do Android/iOS/Windows automaticamente.

### 🎨 Visual
- Fundo abissal `#020a1a` com efeitos neon ciano `#00f5ff`, verde `#00ffc8`, roxo `#8a2be2`
- Cards com hover glow, bordas neon, glassmorphism
- Totalmente responsivo

---

## 🚀 Como Subir no GitHub Pages (Passo a Passo)

### 1. Criar o repositório
1.  Entra na sua conta: **666Studio804**
2.  Cria novo repositório com nome: **a-casa-do-gamer** (tem que ser exatamente com hífen e minúsculo para a URL funcionar)
3.  Deixa público (Public)

### 2. Enviar os arquivos
1.  Baixe o ZIP deste projeto
2.  Extraia na sua máquina
3.  No repositório, clique em `Add file > Upload files`
4.  Arraste:
    - `index.html`
    - `.nojekyll`
5.  Clique em `Commit changes`

### 3. Ativar o GitHub Pages
1.  No repositório, vá em `Settings > Pages` (menu lateral)
2.  Em `Build and deployment`:
    - **Source:** `Deploy from a branch`
    - **Branch:** `main` + `/ (root)`
3.  Clique `Save`
4.  Aguarde 1-2 minutos
5.  Seu site estará em: **https://666Studio804.github.io/a-casa-do-gamer/**

---

## 📁 Estrutura de Arquivos

```
a-casa-do-gamer/
├── index.html      # Site completo (single-file, não precisa build)
├── .nojekyll       # Impede que o GitHub ignore arquivos
└── README.md       # Este arquivo
```

---

## 🛠️ Tecnologias

- **HTML5, CSS3, JavaScript**
- **React (via CDN no arquivo único)**
- **Tailwind CSS**
- **Lucide Icons**
- **localStorage** para login e apps customizados (sem backend)

> 100% estático, funciona em qualquer hospedagem estática: GitHub Pages, Netlify, Vercel, etc.

---

## 👑 Créditos

Feito com 💙 por **666Studio804**
Tema Neon Gamer inspirado em setups RGB e cyberpunk.

---

## 📝 Licença

Código aberto para uso pessoal. Sinta-se livre para modificar e melhorar!
