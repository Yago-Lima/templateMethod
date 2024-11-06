# Template Method Pattern

Este projeto é uma implementação de estudo do padrão de projeto Template Method, conforme descrito no capítulo 8 do livro "Use a Cabeça: Padrões de Projeto".

## Descrição

O padrão Template Method define o esqueleto de um algoritmo em um método, transferindo alguns de seus passos para subclasses. O Template Method permite que subclasses redefinam certos passos de um algoritmo sem mudar a estrutura do próprio algoritmo.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- `src/main/java`: Contém o código-fonte principal.
- `src/test/java`: Contém os testes unitários.
- `pom.xml`: Arquivo de configuração do Maven.

## Requisitos

- Java 17
- Maven 3.6.3 ou superior

## Configuração

Para configurar o projeto, siga os passos abaixo:

1. Clone o repositório:
    ```sh
    git clone https://github.com/Yago-Lima/templateMethod
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd templateMethod
    ```
3. Compile o projeto usando Maven:
    ```sh
    mvn clean install
    ```

## Execução

Para executar o projeto, utilize o seguinte comando Maven:
```sh
mvn exec:java -Dexec.mainClass="com.knight.Main"
```

## Referências

- "Use a Cabeça: Padrões de Projeto" - Capítulo 8: Template Method

## Licença

Este projeto é licenciado sob os termos da licença MIT. Para mais detalhes, consulte o arquivo [LICENSE](./LICENSE).
