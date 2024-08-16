React Native - Flexbox e Responsividade 

O Flexbox é fundamental para construir layouts flexíveis e adaptáveis em aplicações React Native. Essa ferramenta poderosa permite criar interfaces que se ajustam perfeitamente a diferentes tamanhos de tela, 
garantindo uma experiência de usuário consistente em diversos dispositivos.

Conceitos chave:

-Container: O elemento pai que contém os itens filhos e ao qual aplicamos as propriedades do Flexbox.
-Itens filhos: Os elementos dentro do container que serão organizados de acordo com as propriedades do Flexbox.
-Eixo principal: A direção em que os itens filhos são inicialmente posicionados. Definido pela propriedade flexDirection.
-Eixo cruzado: A direção perpendicular ao eixo principal.

Propriedades essenciais:

-flexDirection: Define a direção principal dos itens filhos (row, column, row-reverse, column-reverse).
-justifyContent: Alinha os itens ao longo do eixo principal (flex-start, flex-end, center, space-between, space-around).
-alignItems: Alinha os itens ao longo do eixo cruzado (flex-start, flex-end, center, stretch).
-alignSelf: Permite alinhar individualmente um item filho dentro de seu container.
-flexWrap: Define se os itens podem quebrar em múltiplas linhas ou colunas (nowrap, wrap, wrap-reverse).
-alignContent: Alinha múltiplas linhas ou colunas dentro do container (flex-start, flex-end, center, space-between, space-around, stretch).
-flex: 1: Faz com que um item ocupe todo o espaço disponível na direção do eixo principal.
-flexGrow: Permite que um item cresça para ocupar mais espaço disponível.
-flexShrink: Permite que um item encolha para se ajustar ao espaço disponível.
-flexBasis: Define o tamanho inicial de um item antes que o flexbox comece a distribuir o espaço extra.
