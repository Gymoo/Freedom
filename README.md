# Liberdade

Aplicação PWA baseada em Nostr e relay de execução local para Ubuntu.

- Interface estática: `freedom/web/`
- Launcher e pacote portátil do relay: `freedom/relay/`
- Planos, identidade e testes: `freedom/docs/`

Para iniciar o relay no Ubuntu x86_64, na raiz do repositório:

```bash
./freedom/relay/start.sh
```

O relay usa `127.0.0.1:7447` por padrão. A branch `modelo-mvp` contém o workflow para GitHub Pages; a publicação é concluída quando o Actions workflow fica verde.