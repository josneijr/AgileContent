# AgileContent

## 1 - DecReprSenior

Para essa solução, o primeiro caminho seria descobrir todos os números "siblings" um a um, e compará-los para encontrar o maior. Teríamos então uma complexidade extra, desnecessária se pensarmos no problema de uma forma diferente.
Na segunda forma, como queremos APENAS o maior resultado, podemos tranquilamente pensar em como esse número é formado. Se temos, por exemplo, 123, o número resultande será 321. Se temos 2971, teremos 9721 no final. Ou seja, para encontrar esse número, precisamos simplesmente:

1. Quebrar o número em dígitos
2. Ordenar os dígitos, do menor para maior
3. Recriar o número, adicionando cada dígito como uma nova casa decimal
4. Como solicitado, tratar números maiores do que 100.000.000, retornando -1 (if simples)


## 2 - New CDN iTaas

Já no segundo problema, temos um simples tratamento de dados, onde existe uma entrada que precisa ser tratada para uma saída com formato distinto. Usando uma tratativa simples com strings, conseguimos o resultado de forma direta, mas poderíamos pensar no problema de uma forma mais orientada a objetos, por exemplo, onde criaríamos uma estrutura responsável pelos dados (um objeto contendo todas as propriedades de entrada), que seria facilmente utilizado para formatar a saída. Seria uma segunda solução.
