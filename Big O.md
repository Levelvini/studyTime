
O propósito da notação Big O é descrever a eficiência de um algoritmo em termos de tempo de execução ou uso de espaço (memória) à medida que o tamanho da entrada (n) cresce. É uma maneira de expressar a complexidade computacional de um algoritmo de forma concisa e abstrata, ajudando os desenvolvedores a entender e comparar a eficiência de diferentes algoritmos sem se preocupar com detalhes de implementação específicos ou fatores constantes que podem variar dependendo do hardware ou do ambiente de execução.

### Big O - tempo constante - O(1)
#### quando o algoritmo executará sempre no mesmo tempo, independente da quantidade de dados que receber.

public void printName( ){
return client.getName;
}

functions sem entrada de dados no construtor normalmente são de complexidade O(1) constante.

### Big O - complexidade linear - O(N)

#### quando o tempo do algoritmo é dependente do valor de N.
##### N = dados de entrada.

public int sum(Integer[ ] numbers){
sum = 0;
for(int i = 0; i < [numbers.length]() ; i++){
sum += numbers[i];
}
return sum;
}

a complexidade do algoritmo acima é baseado na quantidade de elementos dentro do array, isso vai impactar em todo o bloco for realizando iterações até percorrer por todos os elementos do vetor.

### Big O - tempo logarítmico - O(log N)

#### quando o algoritmo reduz a entrada de dados a cada iteração.
muito comum em buscas binárias, e bem semelhante ao algoritmo quick sort.
usando o conceito "dividir para conquistar", ele divide o problema em problemas menores até alcançar o resultado desejado. 


### Big O - tempo quadrático - O(N²)
#### Quando o algoritmo tem a necessidade de realizar uma operação linear para cada valor dentro dos dados de entrada
###### o algoritmo bubble sort usa esse conceito.

public void compare(Int[] array1,int[] array2){
for(int i = 0;i < array1.lenght; i++){
for(int j = 0;j < array2.lenght; j++){
if(array1[i] == array2[j]){
system.out.print(array1[i] + " equals to " array2[j])
}
}
}
}
}

### Big O - tempo exponencial - O(2^n)
#### quando o algoritmo resolve o problema de tamanho n recursivamente com dois sub-problemas de tamanho n-1
normalmente sendo atribuída a métodos recursivos, quando o método chama a si mesmo dentro do seu bloco de execução.
o exemplo usado pelo professor foi um método de sequencia de Fibonacci

### Big O - tempo de execução fatorial! - O(N!)
#### quando o tempo do algoritmo cresce de forma fatorial de acordo com os dados de entrada

## Relação de prioridade de complexidade Big O

![[Captura de Tela (9).png]]

