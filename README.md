# Trabalhos de ICC 1

Trabalhos desenvolvidos em C por mim para a disciplina de ICC 1 do curso de Ciências de Computação do ICMC/USP.

[Acesse a disciplina no JupiterWeb](https://uspdigital.usp.br/jupiterweb/obterDisciplina?sgldis=SCC0221&codcur=55041&codhab=0).


## Como executar

Para executar os arquivos usando Linux, basta seguir os passos:

 **1. Instalar o gcc**
 
 O gcc é um conjunto de compiladores de linguagens de programação; dentre elas: C. Instale-o:
 

    $ sudo apt update
    $ sudo apt install build-essential

 **2. Compile (ou execute) os arquivos das pastas**
 
 Caso queira apenas executar o arquivo já compilado, abra uma das pastas e, no terminal:

    $ ./nomedoarquivo
   
Se quiser fazer alterações, será necessário compilar novamente:

    $ gcc -o nomedoarquivo nomedoarquivo.c
Após, apenas execute o novo arquivo gerado.

## Sobre os projetos

**1.  Jogo da velha (/jogo_da_velha)**

Jogo da velha simples, apenas com X e O e com marcadores de 1 a 9 para seleção de posições.

**2. Bar Plot (/bar_plot)**

Recebe um conjunto de dados e armazena as repetições. Após, exibe graficamente a quantidade de repetições.

**3. Binário para Decimal (/binary_to_decimal)**

Conversor simples.

**4. Determinante (/determinant)**

Calcula determinantes de matrizes 1x1, 2x2 e 3x3.

**5. Cifra de César (/cesar_encoding)**

Executa a criptografia da Cifra de César.

**6. Substituir Palavra (/word_replacer)**

Substitui palavras numa string.

**7. Biblioteca (/libr)**

Simula o aluguel, listagem e empréstimos de livros de uma biblioteca.

**8. Ordenar Registros (/registers)**

Ordena registros dados na forma (inteiro nome) pelo inteiro ou pelo nome.
