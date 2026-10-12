# LaurenMC_Lista3_DW

**Resoluções de questões de múltipla escolha e dissertação**

*Parte A - Múltipla Escolha*
1)B; 
2)C; 
3)B; 
4)B;  
5)C; 
6)C; 
7)B; 
8)B; 
9)B; 
10)B; 
11)C; 
12)A;

*Parte B - Dissertativas*
13) Em um código CSS, o contêiner-pai é responsável por receber a propriedade e atributo **display: flex**, e seus filhos diretos serão afetados por essa propriedade, tornando-se assim *flex-items*.
14) Os itens com esse tipo de atributo se apresentarão empilhados na posição de colunas, acima do centro do eixo principal. Isso ocorre pois a propriedade **flex-direction: columns** os dispõe como colunas, e a propriedade
**justify-content: center** os centraliza na central do eixo principal.
15) Quando os **flex-itens** de um contêiner, configurados como **flex-direction: row** e com o **flex-wrap** padrão, são maiores que o conteúdo, os próprios itens tendem a "espremer" para que possam se encaixar no contêiner. 
16) A) No **flex-direction: row**, a propriedade **justify-content** trabalha no alinhamento da linha no centro do eixo principal, e a propriedade **align-items** trabalha na centralização da linha com o eixo cruzado. B) No **flex-direction: column**, ocorre o mesmo princípio de centralização, porém desta vez, seriam centralizadas colunas.
17) O **align-content** é principal e especialmente utilizado com mais de uma linha e com **flex-wrap** diferente de **nowrap**, pois diferente deste caso e condição, a propriedade mais correta a ser utilizada deve ser o **align-items**. A utilização e cooperação do **flex-wrap: wrap** com o **align-content** é essencial, pois sem a primeira propriedade, o CSS pode se ver muitas vezes impossibilitado no gerenciamento de múltiplas linhas. B) Para que o **align-content** pudesse passar a ter efeito, seria preciso que **flex-wrap** tivesse atributos diferentes do padrão, além de múltiplas linhas.
18) A propriedade **gap** é especialmente utilizada para o espaço *entre* os itens de um contêiner, diferente de **margin-rigth**, que por mais que pudesse se aproximar do desejado, aplicaria também o espaço na direita do último item, sendo assim assim um resultado impreciso. Um exemplo pode ser a criação de cards em sites, que muitas vezes, com o intuito de tê-los separados, possuem irregularidades em sua centralizações devido o uso de **margin-rigth** ao invés de **gap**.
