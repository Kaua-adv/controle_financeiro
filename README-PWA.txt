CONTROLE FINANCEIRO - PWA

COMO PUBLICAR
1. Use index.html como arquivo principal do site.
2. Coloque manifest.webmanifest e service-worker.js na mesma pasta do index.html.
3. Coloque também a pasta icons.
4. Publique tudo em um endereço HTTPS.

SE VOCÊ USA GITHUB PAGES
- Substitua o index.html atual.
- Envie os outros arquivos e a pasta icons para o mesmo repositório.
- Aguarde a publicação do GitHub Pages.
- Abra o endereço HTTPS no celular.

ANDROID / CHROME
- Quando disponível, aparecerá o botão "Instalar app".
- Também pode usar o menu do Chrome > Instalar app / Adicionar à tela inicial.

IPHONE / IPAD
- Abra o site no Safari.
- Toque em Compartilhar.
- Escolha "Adicionar à Tela de Início".

IMPORTANTE
- O Firebase continua sendo a base de dados do sistema.
- PC e celular continuam sincronizados na mesma base.
- O PWA precisa de HTTPS (ou localhost em testes).
- A interface básica pode abrir a partir do cache, mas novos dados e sincronização com o Firebase precisam de internet.


ATUALIZAÇÃO DO ÍCONE
Se o app já estava instalado no celular com o ícone antigo, alguns aparelhos mantêm
o ícone em cache. Depois de publicar esta versão, se o ícone não mudar:
- remova o app da tela inicial;
- feche e abra novamente o navegador;
- acesse o site atualizado;
- instale o app novamente.


VERSÃO DOS ÍCONES
Esta versão atualiza todos os ícones com um cifrão visível e altera o cache para v3.
