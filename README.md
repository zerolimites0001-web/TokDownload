# TokDownload 👾
Baixe vídeos do TikTok sem marca d'água — rápido, mobile-first, 100% client-side, zero dependências.

**Demo:** https://zerolimites0001-web.github.io/TokDownload/

## Uso
Abra `index.html` no navegador (ou via `python3 -m http.server`) e cole o link.

- ⚡ MP4 HD sem marca (download direto na página, com barra de progresso, MB + ETA)
- ♫ MP3 da música
- Histórico local, sem login, sem backend

## Tech
- Single `index.html` (HTML+CSS+JS inline)
- API: `tikwm.com/api/?url=...&hd=1`
- Download via `fetch → blob → objectURL` (não sai da página)

## Rodar local
```bash
cd TokDownload
python3 -m http.server 8000
# http://localhost:8000
```
