# Exemplos de Uso — OpenAI (ChatGPT)

Este arquivo documenta duas interações realizadas com a ferramenta ChatGPT da OpenAI. O objetivo foi explorar a capacidade de criação e refatoração assistida por IA, com foco no desenvolvimento backend em Java. Os exemplos foram testados, documentados e comentados abaixo.

---

## 🧠 Exemplo 1 — Refatoração de Código com Stream API

### Prompt utilizado:
```plaintext
Refatore esse método Java para usar Stream API de forma idiomática e funcional.

public void imprimirUsuarios(List<Usuario> lista) {
    for (Usuario u : lista) {
        System.out.println(u.getNome());
    }
}
```
Resultado gerado:

public void imprimirUsuarios(List<Usuario> lista) {
    lista.stream()
         .map(Usuario::getNome)
         .forEach(System.out::println);
}
###Comentário:
Esse exemplo mostra a refatoração assistida de um código Java simples, transformando um loop tradicional em uma abordagem funcional com Stream API. A IA foi capaz de entender o objetivo do código e aplicar boas práticas idiomáticas do Java moderno. O código foi testado e funcionou perfeitamente.

🧠 Exemplo 2 — Geração de Documentação Técnica (README.md)
Prompt utilizado:
Crie um README.md para um projeto em Java que gerencia contas bancárias com POO, incluindo instruções de uso, tecnologias utilizadas e estrutura do projeto.
Trecho gerado (resumo):

# Projeto: Banco Digital em Java

Este projeto é uma simulação de um sistema bancário simples desenvolvido em Java, utilizando os princípios da Programação Orientada a Objetos (POO).

## Funcionalidades
- Criação de contas
- Depósitos e saques
- Transferências entre contas

## Tecnologias Utilizadas
- Java 17
- IntelliJ IDEA
- Git

## Como Executar
1. Clone este repositório
2. Abra no IntelliJ ou outro IDE Java
3. Execute a classe `Main`

## Estrutura do Projeto
- `Conta.java`
- `ContaCorrente.java`
- `ContaPoupanca.java`
- `Cliente.java`
- `Main.java`
###Comentário:
Esse prompt foi utilizado para testar a capacidade da IA em gerar documentação técnica para projetos Java. O resultado foi bem estruturado, claro e utilizável na prática. Algumas adaptações manuais foram feitas para refletir exatamente a estrutura do projeto criado durante o curso.

✅ Conclusão
Esses exemplos mostram como a OpenAI pode ser uma aliada poderosa no desenvolvimento de software, auxiliando tanto na escrita quanto na documentação e refatoração de código. A IA atua como uma espécie de “par-programador” que ajuda a acelerar o desenvolvimento mantendo boas práticas.
