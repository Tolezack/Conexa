# Conexa Frontend (repositório público)

Frontend estático sem segredos. Pode ser publicado pelo GitHub Pages ou outro host estático.

1. Edite `config.js` e defina `API_URL` para a URL HTTPS do serviço Render (ex.: `https://conexa-api.onrender.com`).
2. No backend, configure `FRONTEND_ORIGIN` com a origem exata do site publicado (sem caminho final; para GitHub Pages, inclua `https://USUARIO.github.io`).
3. Publique esta pasta como repositório público. Nunca coloque tokens, senhas ou `SESSION_SECRET` no frontend.

Observação: GitHub Pages pode não ser ideal para um app com configuração que muda frequentemente. `config.js` é público por design e só deve conter a URL pública da API.
