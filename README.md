# Desmistificando a Linguagem Kotlin
 Esta, é uma tradução da documentação original do site Kotlin. É para todos aqeles que querem aprender a linguagem de modo simples e eficaz, mesmo sem saber inglês.

### Hello World
```
package org.kotlinlang.play          // 1

 fun main() {                        // 2 
 println("Hello, World!")            // 3 
}
```

1. O código Kotlin geralmente é definido em packages. A especificação do pacote é opcional: se você não especificar um pacote em um arquivo de origem, seu conteúdo irá para o pacote padrão.
2. Um ponto de entrada para um aplicativo Kotlin é a função principal. Desde Kotlin 1.3, você pode declarar main sem nenhum parâmetro. O tipo de retorno não é especificado, o que significa que a função não retorna nada.
3. println grava uma linha na saída padrão. É importado implicitamente. Observe também que o ponto-e-vírgula é opcional.

  Nas versões de Kotlin anteriores a 1.3, a função main tinha que ter o parametro de tipo Array<string>
  
 ```
fun main(args: Array<String>) {
    println("Hello, World!")
}

### Funções
