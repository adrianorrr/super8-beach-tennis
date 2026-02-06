# Super 8 — Beach Tennis (static + localStorage)

App 100% estático (sem backend, sem banco, sem Node).
- Persistência: localStorage do navegador (somente neste dispositivo).
- Hospedagem: qualquer host de site estático (Vercel / Cloudflare Pages / GitHub Pages).

## Rodar localmente
Abra `index.html` diretamente no navegador **ou** use um servidor estático (opcional).

Exemplo com Python:
```bash
python -m http.server 8000
```
Abra: http://localhost:8000

## Deploy na Vercel (grátis)
- Suba `index.html` na raiz de um repositório
- Importe o repo na Vercel
- Framework: "Other"
- Build command: vazio
- Output: raiz do projeto

Pronto: sempre online e sem “sleep”.
