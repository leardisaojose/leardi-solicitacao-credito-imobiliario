# Solicitação de Crédito • Leardi São José Imóveis

Site estático (GitHub Pages) que envia dados para Google Sheets via Apps Script (/exec).

## Publicar
1. Abra o repositório no GitHub (ex.: `leardi-solicitacao-credito-imobiliario`).
2. Envie **estes arquivos descompactados** para a branch `main`:
   - `index.html`
   - `assets/logo.jpg`
3. Settings → Pages → Source: **Deploy from a branch** → `main` / `(root)`.
4. Abra a URL pública: `https://leardisaojose.github.io/leardi-solicitacao-credito-imobiliario/`

## Configurar o endpoint (/exec)
Se sua URL do Apps Script mudar, edite em `index.html` a constante:
```js
const GS_WEB_APP_URL = "https://script.google.com/macros/s/SEU_ID/exec";
```

## Testes
- Botão **Testar conexão** (no topo da página): deve mostrar `✅ Conectado`.
- **Envio real** (Nome+CPF): deve criar nova linha na aba **Respostas** da planilha.

## Suporte
- Email: unidade.288@leardi.com.br
- WhatsApp: (48) 99149-7879 — https://wa.me/5548991497879
