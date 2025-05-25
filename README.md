# 🔐 Gerador de Tokens BossDV

Projeto simples para geração de tokens com autenticação local via senha fixa.

## ✅ Funcionalidades

- Login com senha fixa (`bossdv123`)
- Geração de token único
- Validação de nomes duplicados no Firebase
- Salva token com:
  - `valid`: boolean
  - `expire_at`: data
  - `device_id`: UUID
  - `nome`: maiúsculo

## 🚀 Como usar

1. Acesse `login.html`
2. Digite a senha correta
3. Será redirecionado para `index.html`
4. Gere tokens com segurança

## ⚙️ Configuração

- Firebase Realtime Database: configure em `index.html` a URL correta.
- Senha: altere em `login.html` → `SENHA_CORRETA`