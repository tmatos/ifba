Folha de Consulta para Portugol (preliminar)
============================================


## Tipos para variáveis:

```
inteiro 
real
logico
cadeia
```

## Variáveis, Declaração:

```
inteiro i
real x
logico h
```

## Atribuição de valor para variável:

```
i = 10
x = 10.1
h = falso
h = verdadeiro
```

## Texto literal:

```
cadeia frase1
frase1 = "qualquer coisa aqui"
```

## Leitura da entrada de dados pelo teclado:

```
leia(var)
```

### Equivalente a:

```
var = "aquilo que você digitou no teclado..."
```

## Ecrevendo coisas na tela:

```
escreva(x)
```

### Exemplos:

| Código            | Resultado   |
| ----------------- | ----------- |
| `x = 10`          |             |
| `escreva(x)`      | 10          |


é diferente de:

| Código            | Resultado   |
| ----------------- | ----------- |
| `x = "abc"`       |             |
| `escreva(x)`      | abc         |


### outro exemplo:

| Código              | Resultado   |
| ------------------- | ----------- |
| `escreva(2*5)`      | 10          |


é diferente de:

| Código              | Resultado   |
| ------------------- | ----------- |
| `escreva("2*5")`    | 2*5         |


## Operações aritméricas:

Soma, subtração, multiplicação, divisão e resto da divisão inteira:

```
x + y
x - y
x * y
x / y
x % y
```

## Operações lógicas:

```
nao(p)
p e q
p ou q
```

## Operações relacionais:

```
x == y
x != y
x > y
x < y
x >= y
x <= y
```

**O resultado é um valor lógico (verdadeiro ou falso).**


## Desvio condicional:

```
se(condicao) {
	....
}
senao {
	....
}
```
