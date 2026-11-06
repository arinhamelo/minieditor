# Mini editor de foto por Arinha Melo

Um mini site para adicionar até três caixas de texto sobre uma foto.

## Como funciona

- Aceita arquivos PNG de até 3 MB.
- A foto é processada inteiramente no navegador e nunca é enviada ao servidor.
- Texto não é adicionado automaticamente. A pessoa pode criar, editar, mover, colorir e remover caixas de texto; o tamanho muda ao arrastar a alça no contorno.
- A prévia e o PNG final usam a mesma rotina de composição para manter o resultado visual alinhado.
- A imagem final é criada como PNG nas dimensões originais da foto.
- No desktop, o botão **Salvar** baixa o PNG. No celular, abre o compartilhamento nativo quando disponível; caso contrário, baixa o PNG.
- Não há dependências, conta, analytics ou armazenamento de imagens.

## Publicação

O projeto é estático e pode ser servido por qualquer hospedagem de arquivos estáticos. Para GitHub Pages, abra **Settings → Pages**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`.

## Privacidade

A imagem fica somente na memória local do navegador. Ao fechar ou atualizar a página, ela é liberada. O texto de privacidade e uso está na própria interface.
