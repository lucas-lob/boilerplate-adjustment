# BUGS

1. [Spinner do botão de submissão do Login não aparecendo corretamente](https://drive.google.com/file/d/1fiLIv5eBHmnlbo3Wi5nam2Q5hUlbw0NK/view?usp=drive_link)
2. [Spinner do botão de submissão da Newsletter não aparecendo corretamente](https://drive.google.com/file/d/1WfvDQYkj5Wt7IZvBMcE3BBU3xnmoGNMX/view?usp=drive_link)
3. Atributo `title` dos [links do Footer exibindo caracteres do Markdown](https://prnt.sc/Ir5oLxIqIaDY)
4. Informações sobrepondo o [botão de fechar do filtro mobile](https://drive.google.com/file/d/1OYxXg7sInlBowsObj-YM-eN12VnLfISi/view?usp=drive_link)
5. Tag de preço e movimentação quebrados no [filtro por preço mobile](https://drive.google.com/file/d/1WbOSe2cb1qHPYhu8b3pKK_xLjXRbamwd/view?usp=drive_link)

# REFACTOR

1. Ajuste dos `titles` de blocos, alguns estão sem ou em inglês.
2. Tradução para portugês dos [`IDs` dos blocos institucionais](https://prnt.sc/Y7sjvqYTTF1l), pois eles aparecem para o cliente no Site Admin.
3. Ajuste do `mixin` de transição para 250ms, os últimos projetos utilizaram este valor porque o valor atual de 500ms é elevado.
4. Adição da variável de cor para o _hover_ da cor primária.
5. Substituição de atributos `border-radius` para o `mixin border-radius`, para ser possível alterar o valor em todo projeto rapidamente de acordo com o _design system_ do projeto.
6. Substituição de `media queries` de 1024px para 1026px, pois a VTEX IO hoje considera tela `desktop` acima de 1026px.
7. Ajuste do componente `responsive-image` para considerar a imagem `desktop` para telas tablets, esse foi o padrão adotado em lojas Faststore e nas últimas lojas IO, pois a imagem `mobile` ficava muito grande em telas tablets.
8. Remoção de `!important`.
9. Substituição de `max-width` existentes por `min-width`, para seguirmos o padrão _Mobile First_.
10. Organização de arquivos.
11. Ajuste de valores de `color` e `font-weight` que estavam sem variáveis (ex.: `color: #000`).
12. Remoção de espaços em branco excessivos.
