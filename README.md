# cartãozinho

Um mini site para personalizar cartões de aniversário com uma foto e até três mensagens.

## Como funciona

- Aceita arquivos PNG de até 3 MB.
- A foto é processada inteiramente no navegador e nunca é enviada ao servidor.
- Texto pode ser editado, movido, colorido, redimensionado e removido.
- A imagem final é criada como PNG nas dimensões originais da foto.
- Em navegadores com compartilhamento de arquivos, o botão abre a folha nativa de compartilhamento. Nos demais, baixa o PNG.
- Não há dependências, conta, analytics ou armazenamento de imagens.

## Publicação

O projeto é estático e pode ser servido por qualquer hospedagem de arquivos estáticos. Para GitHub Pages, abra **Settings → Pages**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`.

## Privacidade

A imagem fica somente na memória local do navegador. Ao fechar ou atualizar a página, ela é liberada. O texto de privacidade e uso está na própria interface.
