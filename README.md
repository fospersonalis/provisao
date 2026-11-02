# 🫙 Provisão — Controle de Despensa

App pessoal (PWA) para controle de **validade e estoque doméstico**. Funciona **offline**, é **instalável** no Android e guarda os dados no próprio aparelho.

## Recursos
- Cadastro de **produtos** (com estoque mínimo), **locais** de armazenamento e **compras**
- Cada compra vira um lote e **soma** ao estoque do produto (inclusive no alerta de mínimo)
- Validade **obrigatória** com radar de vencimento; data de compra opcional
- Novo / editar / duplicar / excluir em tudo
- **Lista de compras** automática (abaixo do mínimo) com copiar e compartilhar
- Tema claro/escuro · **Exportar/Importar backup** em `.json`
- Instalável como app (manifest + service worker) e **offline-first**

## Publicação (GitHub Pages)
Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
A URL gerada (ex.: `https://usuario.github.io/provisao/`) abre no Chrome do Android
e oferece **Instalar app**.

## Dados e privacidade
Tudo fica no navegador do aparelho (localStorage), por origem (a URL). Nada é enviado a servidores.
Faça backups `.json` periódicos pelo botão Exportar.
