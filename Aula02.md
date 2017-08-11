
1. Quais as diferenças entre os barramentos de dados e de endereços?
 O barramento de dados trasmite os dados entre as unidades, enquanto o barramento de endereços é usado para escolher a origem/ destino na memória.

2. Quais são as diferenças entre as memórias RAM e ROM?
 RAM é uma memória volátil, que pode ser alterada depois de programada, enquanto a memória ROM é uma memória fixa que só pode ser alterada enquanto programada.

3. Considere o código abaixo:

```C
#include <stdio.h>
int main(void)
{
	int i;
	printf("Insira um número inteiro: ");
	scanf("%d", &i);
	if(i%2)
		printf("%d eh impar.\n");
	else
		printf("%d eh par.\n");
	return 0;
}
```

Para este código, responda: (a) A variável `i` é armazenada na memória RAM ou ROM? Por quê? (b) O programa compilado a partir deste código é armazenado na memória RAM ou ROM? Por quê?
a) RAM, b) ROM. A RAM é uma memória mais rápida, enquanto a ROM não pode possuir variáveis por ser lenta.

4. Quais são as diferenças, vantagens e desvantagens das arquiteturas Harvard e Von Neumann?
 A arquitetura Harvard é mais rápida, sendo uma versão melhorada da Von Neumann, por ter sido acrescentado um microcontrolador. 

5. Considere a variável inteira `i`, armazenando o valor `0x8051ABCD`. Se `i` é armazenada na memória a partir do endereço `0x0200`, como ficam este byte e os seguintes, considerando que a memória é: (a) Little-endian; (b) Big-endian.
 a) CD|AB|51|80  b) 80|51|AB|CD

6. Sabendo que o processador do MSP430 tem registradores de 16 bits, como ele soma duas variáveis de 32 bits?
   Dividindo 4 registradores em 2 bits. 
