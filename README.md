# Estudo Escrivão PC-PA

App instalável (PWA) para controlar o estudo do edital de Escrivão da Polícia Civil do Pará:
tópicos estudados, questões (acertos/erros) por tópico, estatísticas de dificuldade,
cronograma semanal com troca automática de matéria concluída e backup em JSON.

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `escrivao-pa`) e envie todos estes arquivos para a raiz (`index.html`, `manifest.json`, `sw.js`, pasta `icons/`).
2. No repositório: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save**.
3. Aguarde 1–2 minutos. O endereço será `https://SEU-USUARIO.github.io/escrivao-pa/`.

## Instalar no celular
- **Android (Chrome):** abra o link → menu ⋮ → *Instalar app*.
- **iPhone (Safari):** abra o link → Compartilhar → *Adicionar à Tela de Início*.

Os dados ficam salvos no próprio aparelho (localStorage). Use **Mais → Exportar** para fazer backup.
Para publicar uma nova versão, altere `CACHE` em `sw.js` (ex.: `escrivao-pa-v2`).
