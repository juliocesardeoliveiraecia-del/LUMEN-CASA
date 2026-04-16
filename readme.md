# LUMEN Casa — PWA

Automação Residencial Inteligente

## Estrutura de arquivos

```
lumen-casa/
├── index.html      ← App completo (HTML + CSS + JS)
├── manifest.json   ← Configuração PWA
├── sw.js           ← Service Worker (offline)
├── icon-192.png    ← Ícone 192x192 (adicionar)
├── icon-512.png    ← Ícone 512x512 (adicionar)
└── README.md
```

## Deploy no Vercel

1. Crie uma conta em vercel.com
2. Instale o Vercel CLI: `npm i -g vercel`
3. Na pasta do projeto: `vercel`
4. Siga as instruções — pronto!

Ou: arraste a pasta para vercel.com/new (deploy via interface web)

## Deploy no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em Settings → Pages → Source: main branch
4. URL: `https://seuusuario.github.io/lumen-casa`

## Ícones (obrigatório para instalar como PWA)

Adicione dois arquivos PNG na pasta raiz:
- `icon-192.png` — 192×192px
- `icon-512.png` — 512×512px

Use o logo LUMEN Casa com fundo escuro (#0b0f14).

## Funcionalidades

- Dashboard com dispositivos agrupados por cômodo
- Cards com 8 tipos: Luz, Tomada, Câmera, A/C, TV, Som, Trava, Sensor
- Adicionar dispositivos (salvo no localStorage)
- Long press → menu de contexto → remover
- Toque → abre Smart Life (deep link + fallback Play Store)
- Instalável como PWA (Add to Home Screen)
- Funcionamento offline básico
- Vibração háptica no mobile
- Animações suaves

## Suporte

Julio Cesar de Oliveira
WhatsApp: https://wa.me/5564996039433
