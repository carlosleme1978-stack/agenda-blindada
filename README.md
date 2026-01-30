# Agenda Blindada — Landing (GitHub Pages)

Landing page oficial do **Agenda Blindada** (SaaS de agendamento com **confirmação e lembretes via WhatsApp**).
Este repositório é ideal para:

- publicar uma URL controlada por você (ex.: **GitHub Pages**)  
- apresentar o projeto a clientes  
- usar como referência em processos de verificação (ex.: “website do app”)

---

## ✅ Conteúdo

- `index.html` — landing completa (estática) com gradiente, seções e FAQ

> **Nota**: substitua `contato@exemplo.com` pelo seu email real antes de publicar.

---

## 🚀 Como publicar no GitHub Pages

1. Crie um repositório (ex.: `agenda-blindada`)
2. Adicione `index.html` na raiz
3. Vá em **Settings → Pages**
4. Em **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
5. Salve

O GitHub vai gerar uma URL como:

- `https://SEUUSUARIO.github.io/agenda-blindada/`

---

## 🧩 Personalização rápida

No `index.html`, procure e altere:

- `contato@exemplo.com` (CTA e rodapé)
- `Agenda Blindada` (se quiser outro nome de exibição)
- `og:url` (trocar quando tiver domínio real)

---

## 🔐 Observação sobre WhatsApp / clientes

O modelo recomendado para SaaS multi-cliente é:

- **1 app** (seu) + **múltiplos clientes**
- cada cliente liga o próprio **número** / **WABA** / **tokens**
- isolamento por empresa (multi-tenant)

---

## Licença

Use como base do seu projeto. (Se desejar, adicione uma licença MIT.)
