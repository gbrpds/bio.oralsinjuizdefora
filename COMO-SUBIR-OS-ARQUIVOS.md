# Guia de upload dos arquivos 📂

Este é o guia pra você subir os arquivos exportados do Photoshop. Coloque cada
tipo de arquivo na pasta certa que eu consigo montar o site direitinho.

## Onde colocar cada coisa

| Pasta | O que colocar aqui |
|-------|--------------------|
| `reference/` | **A print do layout inteiro** (como o linktree deve ficar completo). Pode ser 1 imagem só. Ex: `layout-completo.png` |
| `assets/layers/` | **Todas as camadas em PNG** exportadas do Photoshop (fundo, textos, botões, decorações, etc). Pode subir tudo aqui de uma vez. |
| `assets/backgrounds/` | Só o(s) fundo(s), se você quiser separar do resto |
| `assets/logo/` | A logo / marca |
| `assets/profile/` | Foto de perfil / avatar (se tiver) |
| `assets/icons/` | Ícones das redes sociais (Instagram, WhatsApp, etc) se estiverem separados |

> Se ficar em dúvida, joga tudo em `assets/layers/` que eu organizo depois.

## Dica na hora de exportar

- Exporte cada camada em **PNG com fundo transparente** quando fizer sentido.
- Mantenha o **nome de cada camada** parecido com o que ela é
  (ex: `botao-instagram.png`, `fundo.png`, `titulo.png`). Isso me ajuda a
  identificar cada peça.
- Se souber, me diga o **tamanho da prancheta** (largura x altura em px) que
  você usou no Photoshop.

## Como subir pelo GitHub (mais fácil)

1. Entre na pasta certa aqui no GitHub (ex: `assets/layers`)
2. Clique em **Add file → Upload files**
3. Arraste todos os PNGs
4. Clique em **Commit changes**

## Depois que você subir

Me avise que você subiu tudo. Eu vou:

1. Analisar a print do layout e as camadas
2. Montar o site (HTML + CSS) reproduzindo o visual
3. Deixar os botões/links funcionando
4. Deixar responsivo (funciona bem no celular)

## O que ainda preciso saber de você

Quando for montar os links, me passe:

- [ ] Para onde cada botão/link deve levar (URLs do Instagram, WhatsApp, site, etc)
- [ ] Textos exatos que devem aparecer (se não estiverem só na imagem)
- [ ] Se tem algum domínio próprio pra publicar (ex: `bio.oralsinjuizdefora.com.br`)
