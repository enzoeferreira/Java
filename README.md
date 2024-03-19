# <b>Estudos em Java</b>

# <b>Syntax</b>

## <b>Comentários</b>

```java
// Comentários na linha utilizam "//"

/*
 * Comentários em várias linhas
 * utilizam no início "/*"
 * e no fim o inverso
 */
```

## <b>Esqueleto Padrão</b>

arquivo "NomeDaClasse.java"

```java
public class NomeDaClasse{
    // Início da classe
}
```

arquivo "Main.java" (executável)

```java
public class Main{
    public static void main(String[] args) {
        // Método main (que será executado)
    }
    // Classe Main
}
```

## <b>Operadores</b>

### <b>Aritméticos</b>
| **Operador** |  **Uso** | **Descrição**                         |
|--------------|:--------:|---------------------------------------|
|       +      |   a + b  | Adição                                |
|       -      |   a - b  | Subtração                             |
|       -      |    -a    | Negação                               |
|       *      |   a * b  | Multiplicação                         |
|       /      |   a / b  | Divisão                               |
|       %      |   a % b  | Mod (resto)                           |
|      ++      |    a++   | Incrementa 1                          |
|      ++      |    ++a   | Incrementa 1 (usa valor incrementado) |
|      --      |    a--   | Decrementa 1                          |
|      --      |    --a   | Decrementa 1 (usa valor decrementado) |
|     (*)=     | a (*)= b | a = a (*) b                           |

### <b>Lógicos e relacionais</b>
| **Operador** |  **Uso** | **Retorna TRUE se:**       |
|:------------:|:--------:|----------------------------|
|       >      |   a > b  | a maior que b              |
|      >=      |  a >= b  | a maior ou igual a b       |
|       <      |   a < b  | a menor que b              |
|      <=      |  a <= b  | a menor ou igual a b       |
|      ==      |  a == b  | a igual a b                |
|      !=      |   a !=   | a diferente de b           |
|              |          |                            |
|      &&      |  a && b  | a E b são TRUE (AND)       |
|     \|\|     | a \|\| b | a OU b são TRUE (OR)       |
|       !      |    !a    | a é FALSE (NOT)            |
|   & (Bool)   |   a & b  | a E b são TRUE (avalia b)  |
|   \| (Bool)  |  a \| b  | a OU b são TRUE (avalia b) |
|   ^ (Bool)   |   a ^ b  | a e b são diferentes       |

## <b>Classes</b>

### <b>System</b>

#### <b>.out</b>

##### <b>.println</b>
Imprime uma cadeia de caracteres
```java
System.out.prinln("Olá mundo!")
```

## <b>Operadores condicionais e comandos de repetição</b>

### <b>if()</b>
```java
if(condição) {
    // Bloco 1
} else if (condição2) {
    // Bloco 2
} else {
    // Bloco 3
}
```

#### <b>Ternário</b>

```java
condição ? verdadeiro : falso;
```

### <b>while()</b>
```java
while(condição) {
    // Bloco
}
```

#### <b>do-while</b>
```java
do {
    // Bloco
} while(condição)
```

### <b>for()</b>
```java
for(expressão1; expressão2; expressão3) {
    
}
/*
 * expressão1: Uma expressão ou qualquer comando ou chamada de função. Normalmente uma atribuição
 * expressão2: Qualquer comando ou chamada de função
 * expressão3: Uma expressão ou qualquer comando ou chamada de função
 */
```

### <b>switch()</b>
```java
switch(expressão) {
    case caso1:
    
    case caso2:

    ...

    case casoN:

    default:
}
```

## <b>Modificadores</b>

Modificador | Classe | Pacote | Sublasse | Mundo
public | S | S | S | S
protected | S | S | S | N
default | S | S | N | N
private | S | N | N | N

# <b>Bibliotecas</b>

# <b>Funções</b>
