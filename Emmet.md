# Emmet
O emmet é muito utilizado para arquivos HTML em geral.
Pois com ele, conseguimos criar divs, id para essas divs, quais serão suas filhas e tudo ao mesmo tempo. 

O "#" cria IDS para elementos
O "." cria classes para elementos
O ">" cria filha para os elementos
O "{}" coloca conteúdo para as tags
O "+" serve para colocar tags no mesmo escopo 

</br>

`div>h1` 
Criando uma DIV que ira possuir a tag <H1> como filha

</br>

`h1#FirstTitle`
Criando uma tag <h1> que irá possuir um ID

</br>

`div>h1 + h1`
Criando uma DIV onde irá possuir duas tags h1

</br>

`section#roupas>h2*4{Roupas vermelhas}`
Cria uma section com ID "roupas", colocando 4 tags h2, e todas as "h2" irão possuir "Roupas vermelhas"