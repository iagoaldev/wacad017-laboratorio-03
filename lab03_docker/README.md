# WebAcademy em Docker

Aplicação Express fornecida no Laboratório 03. Ela responde na porta 3000 e é
empacotada e publicada no Docker Hub pelo GitHub Actions.

```bash
npm install
npm start
```

Para executar com Docker:

```bash
docker build --tag web_app .
docker run --rm -p 3000:3000 web_app
```
