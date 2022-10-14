1 Na pasta assets, por padrao é onde colocamos todos os nossos arquivos estaticos.
Arquivos CSS, imagens, alguns arquivos JS, etc

2 Arquivo normalize.css na pasta css, geralmente serve para resetar as configuracoes
padrao de estilo do navegador. Geralmente tambem é o primeiro arquivo a ser 
importado no documento html.

3 Arquivo reset.css geralmente serve para resetar padroes que serao usados por
todos os elementos da pagina

4 Arquivo style.css geralmente é o arquivo css responsavel pela estilizacao da pagina

5 Pode se navegar entre as tags para chegar a tag desejada. Entre chaves se coloca
as propriedades e valores desejados

6 Pode se adicionar propriedades nas chamadas css para se chegar a algum item mais
especifico

7 Para simplificar os seletores css podemos recorrer as classes

8 O ponto "." no inicio do seletor css indica uma classe

9 Uma boa pratica é separar os arquivos css para que o codigo nao tenha muitas linhas
Chamado de Atomic Design. Elementos separados (inputs, labels, buttons, etc) sao 
atomos. Juntos eles formam uma molecula (que seria uma campo de pesquise por 
exemplo. Label pra descrever, input pra digitar e button pra pesquisar). E varias
moleculas formam o organismo formam os templates que formam a base da pagina. E 
o conjunto de tudo forma a pagina html

10 Padrao BEM - Bloco - Elemento - Modificador
bloco 
bloco__elemento
bloco--modificador 
bloco__elemento--modificador

Bloco - Uma secao, ou uma nav do codigo 
Elemento - um elemento do bloco - para adicionar um elemento, separacao por dois underlines. Elemento geralmente é filho do bloco
Modificador - um caracterizador do elemento - para adicionar um modificador, separacao por dois hifens

11 Padro BEM é usado somente para nomear as classes. O nome dos arquivos segue o padrao de separacao por um hifens

12 Um bom jeito de trabalhar nas diversas secoes da pagina é:
criar as tags html
criar o nome das classes na pagina html
criar as pastas dos arquivos css de cada bloco html
criar os arquivos css de cada elemento css dentro das pastas dos blocos
importar as classes css no arquivo html
criar as classes css dentro dos arquivos css
definir as propriedades e valores das classes css 

13 É uma boa pratica colocar as propriedades do css em ordem alfabetica

14 @media-screen permite tornar o site responsivo para o varios tamanhos de 
tela. Ele permite por estilizacao conforme o tamanho minimo da tela

15 As propriedades que serao responsivas saem do escopo principal da classe css
e migra para as classes responsaveis por tornar o site responsivo (as classes que
comecam com @)

16 Um bom jeito de trabalhar na adaptacao responsiva do site é fazer as bases dos
media-cares para as telas de celulares e do computador, copiar a classe css mae 
do elemento nos media-cares, recortar a propriedade que ira se alterar conforme o 
tamanho da tela da classe mae css e colar na media-care da tela do computador e na 
media-care do celular, colocar os valores das propriedades que ira sofre alteracao