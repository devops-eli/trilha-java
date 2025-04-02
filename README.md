# Introdução à Linguagem Java

## O que é Java?
Java é uma linguagem de programação orientada a objetos, multiplataforma e de alto nível, desenvolvida pela Sun Microsystems em 1995 e atualmente mantida pela Oracle Corporation. Java é amplamente utilizado para desenvolver aplicações desktop, web, móveis e sistemas embarcados.

## Principais Características
- **Portabilidade**: O lema "Write Once, Run Anywhere" (WORA) indica que o código Java pode ser executado em qualquer plataforma que tenha uma JVM (Java Virtual Machine).
- **Orientado a Objetos**: Baseia-se em conceitos como encapsulamento, herança e polimorfismo.
- **Segurança**: Java oferece diversas funcionalidades para garantir um ambiente seguro, como o gerenciamento automático de memória e a execução em sandbox.
- **Multithreading**: Suporte nativo para a execução de múltiplas threads, permitindo aplicações eficientes e responsivas.
- **Bibliotecas Ricas**: Possui um extenso conjunto de bibliotecas e APIs para desenvolvimento de diferentes tipos de aplicações.

## Primeiro Programa em Java
A seguir, um exemplo básico de um programa em Java:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### Explicação do Código
1. `public class HelloWorld` - Declara uma classe pública chamada `HelloWorld`.
2. `public static void main(String[] args)` - Método principal (entry point) do programa.
3. `System.out.println("Hello, World!");` - Exibe "Hello, World!" no console.

## Como Compilar e Executar um Programa Java
1. Salve o código acima em um arquivo chamado `HelloWorld.java`.
2. Compile o arquivo usando o comando:
   ```sh
   javac HelloWorld.java
   ```
3. Execute o programa compilado:
   ```sh
   java HelloWorld
   ```

## Conclusão
Java é uma linguagem poderosa, versátil e amplamente utilizada em diversas áreas da computação. Seu ecossistema robusto e sua compatibilidade com múltiplas plataformas tornam-no uma excelente escolha para desenvolvedores iniciantes e experientes.

Para mais informações, consulte a [documentação oficial do Java](https://docs.oracle.com/en/java/).