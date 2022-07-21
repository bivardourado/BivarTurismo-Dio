# BivarTurismo-Dio

Resumo flexbox
justify-content: propriedade que alinha itens horizontalmente e aceita os seguintes valores:

flex-start: Itens se alinham ao lado esquerdo do container.
flex-end: itens se alinham ao lado direito do container.
center: itens se alinham ao centro do container.
space-between: exibe itens com espaçamento igual entre eles.
space-around:exibe itens com espaçamento igual ao redor deles.

align-items: propriedade alinha os itens verticalmente e aceita os seguintes valores:

flex-start: itens se alinham ao topo do container.
flex-end: itens se alinham à parte de baixo do container.
center: itens se alinham ao centro vertical do container
baseline: exibe itens na linha de base do container
strech: itens são esticados para preencher o container.

flex-direction: Essa propriedade do CSS define a direção em que os itens são alocados no container e aceita os seguintes valores:

row: itens são alocados na mesma direção de um texto (da esquerda para direita)
row-reverse: itens são alocados na direção oposta a de um texto (da direita para a esquerda)
column: os itens são colocados de cima pra baixo.
column-reverse: os itens são colocados de cima pra baixo.

Obs: Note que quando a flex-direction usa column, justify-content muda para vertical e align-itens para horizontar.

Às vezes rerverter a ordem da fileira ou coluna de um container não é suficiente. Nesses casos, podemos aplicar a propriedade order para itens individuais. Por padrão, itens tem o valor de 0, mas podemos atribuir um valor inteiro positivo ou negato (-2,-1,0,1,2).

Outra propriedade que se pode aplicar a itens individuais é align-self. Essa propriedade aceita os mesmos valores que align-items e seu valor para o item específico.

A propriedade flex-wrap aceita os seguintes valores:

nowrap: Cada item é encaixado em uma só linha;
wrap: Os itens são acondicionados em linhas adicionais;
wrap-reverse: Os itens são acondicionados em linhas adicionais, mas de forma reversa.

As duas propriedades flex-direction e flex-wrap são usadas tantas vezes juntas que a propriedade abreviada flex-flow foi criada para combiná-las. Essa propriedade abreviada aceita os valores de duas propriedades separadas por um espaço. Por exemplo, você pode usar flex-flow: row wrap para configurar linhas e acondicioná-las em linhas adicionais.

Align-content: Estabelece como linhas múltiplas são espaçadas entre si. Essa propriedade possui os seguintes valores:

flex-start: Linhas são acondicionados no topo do container.
flex-end: Linhas são acondicionadas na parte de baixo do container.
center: As linhas são acondicionadas no centro vertical do container.
space-between: Exibe as linhas com espaçamentos iguais entre si.
space-around: Exebie linhas com iguais espaçamentos ao redor de si.
strech: Linhas são esticadas para se enquadrarem no container.

Pode ser confuso, mas align-content determina o espaçamento entre linhas enquanto align-items determina como os items como um todo estão alinhados dentro do container. Onde há somente uma linha, align-content não terá efeito.
