# Casamento-de-Caracteres
-> Descrição
Há muito tempo atrás, existia um lugar na Terra no qual a mágica era verdadeira. Para
os habitantes do reino Xulambis, era algo bem comum conviver com diferentes poderes, e todos
recebiam sua pedra mágica quando completavam a maior idade.
Cada pedra era composta por um conjunto de símbolos coloridos. De acordo com a sequência
dos símbolos um poder diferente podia surgir. Por exemplo, uma sequência de símbolos azul, azul,
branco, branco, verde, vermelho dava ao usuário o poder da velocidade. As inscrições eram geradas
de maneira aleatória, sendo assim existiam pedras que não conferiam nenhum poder.
Com o tempo o segredo da magía, continuou oculto e perdido. Porém recentemente, um grupo de
pesquisadores fascinados com o mundo antigo, em uma de suas explorações, encontraram o templo
do reino de Xulambis. E após vasculharem os livros, descobriram um dicionario que relacionava
cada conjunto de símbolos a um poder. Agora estão decididos a separarem as pedras que realmente
tem poderes das que não tem, para assim provarem ao mundo que a magía é real.
O problema é que as pedras podem ter milhares de símbolos, e verificar manualmente se a pedra
possui alguma habiliadade é um processo custoso e muito sujeito a erros humanos. Sua tarefa é
construir soluções que dados a sequência do poder e a descrição da pedra, determinar se aquela 
sequência esta presente na pedra.

-> O que deve ser feito
Você deve propor, implementar e avaliar PELO MENOS TRÊS algoritmos que resolvam o
problema dos pesquisadores.
Na avaliação das estratégias, você deve considerar sua análise de complexidade feita sobre as
estratégias implementadas comparando-as com os tempos reais de execução (utilize a rotina gettimeofday()). A ideia de tal comparação é tentar mostrar que sua análise de complexidade está
correta bem como determinar qual dos métodos acima obtém o melhor desempenho na resolução
do problema proposto.

-> Entrada e Saída
O arquivo executável deve ser chamado de tp3 e deve receber dois parâmetros: nome do arquivo
de entrada e um inteiro que representa uma das estratégias implementadas. Exemplo:
./tp3 entrada.txt 1
1
A entrada do programa deve ser lida de um arquivo de texto. A entrada é composta por vários
casos de teste. A primeira linha contém um inteiro T, que representa o número de casos de teste.
Cada uma das T linhas seguintes representa um caso de teste e possui duas cadeias de caractéres
separadas por um espaço. A primeira representa a sequência da habilidade e a segunda a descrição
da pedra. Ambas as cadeias são compostas de letras minúsculas a-z, cada letra representa uma
cor distinta. A pedra é esférica: o simbolo representado pelo ultimo caractere é adjacente àquele
representado pela primeira. A sequencia do poder possui entre 1 e 102
caracteres, inclusive. A
pedra possui entre 1 e 104
caracteres inclusive.
Para cada caso de teste, imprima uma linha contendo S se a sequência está presente, junto com
a posiç onde começa, naquela pedra e N se ela não está presente.
A saída deve ser em um arquivo texto e o nome do arquivo de saída é o nome do arquivo de
entrada porém com a extensão ”out".
Exemplo de entrada:
4
ava av
patapon npatapatapatapo
isitfriday ohnoitisnt
haskell lleksah
Exemplo de saída
S 1
S 10
N
S 7


