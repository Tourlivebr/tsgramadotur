# Prompt reutilizável — dois cards de transfers

Copie o bloco abaixo e envie à ferramenta que vai editar o outro site. Anexe a imagem de referência, se possível. Copie também as duas fotos indicadas ao final para o projeto de destino.

## Prompt para copiar

```text
Crie uma seção com exatamente dois cards de serviços, seguindo a imagem de referência e as especificações abaixo. Implemente no site atual usando a tecnologia e os componentes já existentes no projeto.

Título da seção: “Translados e Passeios”. Centralize o título, com “Translados e” em azul-marinho e “Passeios” em azul royal. Use fonte sem serifa, peso 700 e tamanho aproximado de 30 px.

LAYOUT E APARÊNCIA
- Fundo da seção azul muito claro, aproximadamente #F0F4FF.
- Dois cards lado a lado em telas com espaço suficiente, com 24 px entre eles. Centralize o conjunto, com largura máxima aproximada de 736 px. Em telas pequenas, empilhe os cards em uma coluna, sem rolagem horizontal.
- Na referência, cada card mede aproximadamente 356 px de largura e 430 px de altura. Use essas medidas como guia visual, permitindo que a altura cresça conforme o texto e a tela.
- Cards brancos com cantos de 16 px, sombra suave e conteúdo sem transbordar.
- Foto no topo, ocupando toda a largura, com altura de 176 px e object-fit: cover. Preserve os cantos superiores arredondados.
- Sobre a foto, no canto superior esquerdo, coloque o selo “TRANSFER”: fundo verde vivo, texto preto de 12 px, formato de cápsula, afastamento de 12 px das bordas.
- Corpo do card com 16 px de espaçamento interno.
- Título do serviço em azul-marinho, fonte de 18 px e peso 700.
- Descrição abaixo em fonte de 14 px, com entrelinha confortável e cor azul-acinzentada. Preserve os acentos.
- Após a descrição, inclua uma linha divisória fina em cinza muito claro.
- Exiba duas caixas de preço lado a lado, com espaçamento de 12 px, fundo cinza muito claro e cantos de 8 px. Centralize o conteúdo. A faixa de pessoas deve aparecer acima, em 12 px; o preço abaixo, em 18 px, negrito e azul royal.
- Botão “RESERVE AGORA” abaixo dos preços, ocupando toda a largura interna, com altura aproximada de 48 px, fundo azul royal próximo de #1B4DB3, texto branco de 16 px, cantos totalmente arredondados e sombra discreta.
- Mantenha os botões e as caixas de preços alinhados entre os dois cards, mesmo quando os títulos tiverem tamanhos diferentes.
- Use uma transição suave no hover do botão e foco de teclado visível. Use HTML semântico, texto alternativo nas fotos e links acessíveis.

CARD 1
Título: Transfer Grande Desfile de Natal
Descrição: Translado para o espetáculo do Natal Luz no Expogramado. Ingresso não incluso.
Foto: desfile de Natal com carros alegóricos, personagens e público; use o arquivo fornecido desfile-01.webp.
Selo: TRANSFER
Primeira caixa: “1 a 4 pessoas” e “R$ 150,00”.
Segunda caixa: “5 a 6 pessoas” e “R$ 200,00”.
Texto do botão: RESERVE AGORA
Destino do botão: /passeio/transfer-grande-desfile-de-natal

CARD 2
Título: Transfer Nativitaten
Descrição: Translado para o espetáculo do Natal Luz no Serra Park. Ingresso não incluso.
Foto: espetáculo noturno com palco iluminado e fogos de artifício; use o arquivo fornecido nativitaten-01.webp.
Selo: TRANSFER
Primeira caixa: “1 a 4 pessoas” e “R$ 300,00”.
Segunda caixa: “5 a 6 pessoas” e “R$ 350,00”.
Texto do botão: RESERVE AGORA
Destino do botão: /passeio/transfer-nativitaten

INTEGRAÇÃO
- Os preços são por grupo/faixa de pessoas. Não apresente como preço por pessoa.
- Use os valores exatamente como fornecidos; não invente descontos ou informações adicionais.
- Ajuste os caminhos das imagens ao projeto de destino.
- Os destinos dos botões são as rotas do site de origem. No outro site, conecte os botões às páginas de reserva correspondentes. Caso essas páginas não existam, deixe os destinos configuráveis e informe o que falta conectar, sem criar páginas fictícias.
- Preserve a fidelidade visual da referência sem adicionar carrossel, outros cards ou elementos extras.
- Entregue a implementação completa e responsiva, indicando os arquivos alterados e qualquer configuração pendente.
```

## Fotos para levar ao outro site

Os arquivos de imagem não estão embutidos neste Markdown. Copie-os junto com o prompt:

| Card | Arquivo neste projeto |
| --- | --- |
| Grande Desfile de Natal | `public/images/grande-desfile-de-natal/desfile-01.webp` |
| Nativitaten | `public/images/nativitaten/nativitaten-01.webp` |

## Origem e conferência

Os textos, preços, imagens e rotas foram conferidos em `src/components/CarrosselPasseiosReceptivo.astro`. As medidas e cores acima são aproximações da imagem de referência. Os valores reproduzem o material fornecido e podem ser editados antes de reutilizar o prompt.

Ao conferir o resultado, verifique se há exatamente dois cards, se as fotos carregam, se os quatro preços estão corretos, se o layout funciona no celular e se cada botão abre o destino de reserva configurado.
