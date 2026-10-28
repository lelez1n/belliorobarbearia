# Bellioro Barbearia

Site institucional da Bellioro Barbearia, no Shopping Germânia, em Santa Cruz do Sul, RS. Desenvolvido em HTML, CSS e JavaScript, sem instalação de dependências e sem etapa de build.

## Arquivos

- `index.html`: página principal com apresentação, serviços, localização, perguntas frequentes e privacidade.
- `style.css`: identidade visual, estilos responsivos e animações.
- `app.js`: categorias de serviços, links de agendamento e WhatsApp, menu, efeitos de entrada e modal de privacidade.
- `favicon.svg`: ícone da página.
- `assets/fachada.jpg`: foto da fachada.
- `assets/interior.jpg`: foto do interior.
- `.nojekyll`: permite servir os arquivos diretamente no GitHub Pages.

## Abrir localmente

Abra `index.html` no navegador, mantendo os demais arquivos e a pasta `assets` na mesma estrutura. Não é necessário instalar Node.js.

Para usar um servidor local, com Python instalado:

```sh
python -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Publicar

O conteúdo da raiz pode ser enviado a qualquer hospedagem de sites estáticos, sem comando de build.

No GitHub Pages, em **Settings > Pages**, selecione **Deploy from a branch**, branch **main** e pasta **/ (root)**, e salve. A publicação precisa ser ativada separadamente; enviar os arquivos ao repositório não publica o site automaticamente. A disponibilidade do Pages depende da visibilidade do repositório e do plano da conta.

## Editar

- Textos, endereço, horários e perguntas: `index.html`.
- Cores, espaçamento, tipografia e comportamento responsivo: `style.css`.
- Serviços, preços, duração e identificadores da agenda: objeto `services` em `app.js`.
- Agenda oficial: constante `base` em `app.js`.
- WhatsApp: número usado na montagem dos links em `app.js`, além do telefone no HTML.
- Fotos: arquivos locais na pasta `assets`.

## Canais e fontes

- Agenda: https://bellioro.bemp.online/3507-bellioro
- Galeria oficial: https://bellioro.bemp.online/3507-bellioro/photo_gallery
- Instagram: https://www.instagram.com/belliorobarbearia/
- Perfil Google: https://share.google/TaTKQCLGcrvUxq2WP

As duas fotos foram obtidas da galeria oficial BEMP. Os serviços e valores foram consultados em 28/10/2026 e devem ser revisados quando houver mudanças. Os agendamentos são concluídos na BEMP; este site não cria reservas nem processa pagamentos.

## Estado da verificação

- Sintaxe de `app.js` verificada com `node --check`.
- Arquivos de imagem locais conferidos.
- Revisão visual em desktop e celular ainda pendente por indisponibilidade da prévia no ambiente de criação.

## Privacidade e direitos

A página não inclui formulário, rastreamento de publicidade ou analytics. Agenda, WhatsApp, Instagram e Google são serviços externos, com políticas próprias. A marca, as fotos e as avaliações pertencem aos respectivos titulares. Este repositório não concede licença de reutilização desses materiais.
