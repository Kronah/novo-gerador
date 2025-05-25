# 🔐 Gerador de Tokens BossDV

Projeto completo para geração, listagem e exportação de tokens com autenticação local.

## 🚀 Funcionalidades

- Login com senha fixa (`bossdv123`)
- Geração de token único
- Validação de nomes duplicados
- Salva token com:
  - `valid`: boolean
  - `expire_at`: data
  - `device_id`: UUID
  - `nome`: maiúsculo
- Listagem de tokens ativos
- Exportação como `.json`

## ⚙️ Como usar

1. Acesse `login.html`
2. Digite a senha correta
3. Use `index.html` para gerar tokens
4. Acesse `tokens.html` para ver todos os tokens válidos
5. Use `exportar.html` para baixar os dados

## 📌 Configuração

- Firebase: altere em `index.html`, `tokens.html` e `exportar.html`
- Senha: mude `SENHA_CORRETA` em `login.html`