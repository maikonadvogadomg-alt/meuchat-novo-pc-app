# Plano do projeto: meuchat-novo-pc

_Gerado pelo Mini SK em 24/11/2026, 06:01:17_

## Resumo

- Arquivos: **86** (1.2 MB)
- Tipo: projeto Node com 1 package.json
- Arquivos por tipo: JavaScript 51, HTML 18, Markdown 9, PNG 2, JSON 2, YAML 1, CSS 1, Texto 1, NSH 1
- Dependências diferentes: **4** (2 obrigatórias, 2 só para montar)
- Restos da Replit: nenhum

## 📦 meuchat-novo-pc — `package.json`

- Arquivo principal: `electron/main.cjs`

**Comandos (scripts):**

| Comando | O que faz | Executa |
|---|---|---|
| `programa` | — | `electron .` |
| `exe` | — | `electron-builder --win nsis portable --x64 --publish never` |

**Dependências (o app precisa) — 2:**

| Pacote | Versão | Pra que serve | Tipo |
|---|---|---|---|
| `ws` | ^8.18.0 | Conexão em tempo real (WebSocket) | 🗄 Servidor |
| `msedge-tts` | >=1.3.4 | (sem descrição — toque no nome para ver no npm) | ❔ |

**Dependências de montagem (dev) — 2:**

| Pacote | Versão | Pra que serve | Tipo |
|---|---|---|---|
| `electron` | 33.2.1 | Executável de computador (janela própria) | 💻 EXE |
| `electron-builder` | 25.1.8 | Gera o .exe do Electron | 💻 EXE |

## Arquivos importantes (5) — mandar estes para a IA

- `.github/workflows/programa-exe.yml`
- `app/manifest.json`
- `electron/main.cjs`
- `electron/preload.cjs`
- `package.json`

## Estrutura completa (86 arquivos)

```
├── .github/
│   └── workflows/
│       └── programa-exe.yml
├── app/
│   ├── css/
│   │   └── app.css
│   ├── docs/
│   │   ├── cacabug.md
│   │   ├── laboratorio.md
│   │   ├── meuchat.md
│   │   ├── minisk.md
│   │   └── sk-juridico-html.md
│   ├── ferramentas/
│   │   ├── analisador-v2.html
│   │   ├── analisador.html
│   │   ├── caca-sql.html
│   │   ├── cofre-config.html
│   │   ├── colecionador-codigo.html
│   │   ├── comandos-termux.html
│   │   ├── conversor-imagem.html
│   │   ├── desmontador-backup.html
│   │   ├── detector-api.html
│   │   ├── divisor-html.html
│   │   ├── juntador.html
│   │   ├── leitor-universal.html
│   │   ├── monica-guia.html
│   │   ├── monica-passo.html
│   │   ├── montador-modulos.html
│   │   └── procurar-substituir.html
│   ├── icons/
│   │   ├── icon-192.png
│   │   └── icon-512.png
│   ├── js/
│   │   ├── lib/
│   │   │   ├── cofre-arquivo.js
│   │   │   ├── ferramentas-lista.js
│   │   │   ├── guia-maikon.js
│   │   │   ├── guia-versoes.js
│   │   │   ├── jszip.min.js
│   │   │   ├── nuvem-neon.js
│   │   │   ├── playground-replit.js
│   │   │   ├── reconhecer.js
│   │   │   └── segredos.js
│   │   ├── 00-base.js
│   │   ├── 10-banco.js
│   │   ├── 11-online.js
│   │   ├── 12-nuvem.js
│   │   ├── 13-aovivo.js
│   │   ├── 14-entrada.js
│   │   ├── 16-ver-nuvem.js
│   │   ├── 20-provedores.js
│   │   ├── 30-memoria.js
│   │   ├── 33-contextos.js
│   │   ├── 34-guia.js
│   │   ├── 35-jeito.js
│   │   ├── 36-gasto.js
│   │   ├── 37-arquivos.js
│   │   ├── 38-codigos.js
│   │   ├── 39-qr.js
│   │   ├── 40-voz.js
│   │   ├── 41-pronto.js
│   │   ├── 42-testar.js
│   │   ├── 43-links.js
│   │   ├── 44-docs.js
│   │   ├── 45-mesa.js
│   │   ├── 50-internet.js
│   │   ├── 60-previa.js
│   │   ├── 70-texto.js
│   │   ├── 80-chat.js
│   │   ├── 85-config.js
│   │   ├── 87-cofre.js
│   │   ├── 90-backup.js
│   │   ├── 91-restaurar.js
│   │   ├── 95-ponte-lab.js
│   │   ├── 99-app.js
│   │   ├── janela-pc.js
│   │   └── nuvem-embutida.js
│   ├── index.html
│   ├── LEIA-ME.txt
│   ├── manifest.json
│   ├── README.md
│   └── sw.js
├── electron/
│   ├── instalar.nsh
│   ├── main.cjs
│   ├── navegador.html
│   ├── ponte.cjs
│   ├── preload-nav.cjs
│   ├── preload.cjs
│   ├── saude.cjs
│   ├── terminal.cjs
│   └── voz.cjs
├── LEIA-ME.md
├── package.json
├── PLANO.md
└── RECEITA.md
```
