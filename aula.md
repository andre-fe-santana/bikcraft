# AULA 4 

1. <img> => Coloca imagens

2. Listas:
<ul> => Lista Não Ordenada
<ol> => Lista Ordenada
<li> => Item da lista

3. Tag de Link
<a> => Texto clicável

## CSS

1. `font-family: Arial, Helvetica, sans-serif;` => fonte da padinga
2. `padding` => Espaçamento interno do conteúdo até a borda
3. `margin` => Espaçamento Externo do elemento em relação a outro elemento
4. `border` => É a borda do elemento

# AULA 5 

1. Posicionamento (Grid)

`Grid` -> É uma das tecnologias mais utilizadas nos sistemas web e sites. A lógica utilizada é separar a tela em colunas e linhas que podem ser de diferentes tamanhos.

2. Utilizando o Grid
Utilizamos a propriedade display com o valor de grid.
Ex: `display: grid;`

--------- ---------
|       | |       |
|       | |       |   
|       | |       |
--------- ---------

3. Principais Propriedades do Grid

Importante porque no padrão é só uma coluna caso não seja configurado

|   |            ________ 
|   |              
|   |   Coluna   ________   Linha
|   |
_______
|__|__|
|__|__| Grid de 8 linhas (horizontais) e 2 colunas (verticais)
|__|__|

`grid-template-columns` -> Propriedade utilizada para informar ao css quantas colunas e quais os tamanhos você irá usar.

`grid-template-rows` -> Propriedade utilizada para informar quantas linhas serão geradas e o tamanho delas

Medidas (Métricas):
Evitar:
    => `Porcentagem (%)`: não recomendado porque pode dar barra horizontal pois escapa da tela
    => `Pixels (px)`: é o pixels né pae (400px, 600px)

=> `Fração (fr)`: Melhor que a porcentagem pois é mais responsivo
fr => fração 
1fr =>  100% 
1fr 1fr => 50% 50% 
1fr 1fr 1fr => 33,3% 33,3% 33,3%

=> `auto`: Tamanho de forma automática

`grid-row:` -> Define em qual linha ou elemento irá ser posicionado.
`grid-column:` -> Define em qual coluna o elemento irá se posicionar.
