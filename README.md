# Curso de Java

## Entendendo a dinâmica de um arquivo .java

A classe que tem o mesmo nome do arquivo, ela é denominada de classe pública.

```java
public class Main{

}
```
nome do arquivo: Main.java

## Declaração de Varáveis

```java

  public class Main {
    public static void main(String[] args) {
        // Declarando variaveis

        int numeroInteiro = 20;
        String meuNome = "Luiz Felipe Siqueira Pereira";
        Boolean homem = true;
        double altura = 1.78; // precisão dubla
        float garrafasDeAguas Tomadas = 2.5F; // precisão

        //como definir variáveis sem definir o tipo

        var nomeMae = "Rosa Maria";

        //aqui o Java entende e define como string.

    }
}
  
```
## Trabalhando com Arrays:

```java
//Inicializando array com números

int[] arrayDeInteiros = {1, 2, 3, 4, 5};

//Acessando um índice do array
System.out.println(arrayDeInteiros[4]); // vai me retornar o numero cinco

//Inicializando array com nada

int[] meusNumeros = new int[5];

//tamanho de um array:

int tamanho = meusNumeros.length

```

## Trabalhando com ArrayList

Pacote java.util.ArrayList

```java

  ArrayList<String> nomes = new ArrayList<>();
  nomes.add("Luiz"); // serve para add itens a lista 
  nomes.add("felipe");

  System.out.println(nomes.get(0)); // me retorna o Luiz

  nomes.remove(0); // remove o item de indice 0 = Luiz
  nomes.remove("Felipe"); // posso remover por objeto também.

// tamanho da Lista aqui no ArrayList uso: .size()

  nomes.size()

```

## Loops no Java

Loop for

```java

  for(int i = 0; i < nomes.size(); i++){
      System.out..println(nomes.get(i));
}

```

Outra forma de iterar coleções  com for é utilizando a seguinte estrutura:

```java

  for(String nome: nomes){
      System.out.println(nomes);
}
```

Loop While:

```java

int contador = 0;
while(contador < 10){
    System.out.println(contador++);
}


```  

