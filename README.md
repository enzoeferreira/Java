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
