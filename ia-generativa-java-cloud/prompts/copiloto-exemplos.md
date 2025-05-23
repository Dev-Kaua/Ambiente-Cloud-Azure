# ✨ Exemplos de Uso com GitHub Copilot

Este documento reúne exemplos práticos de como o GitHub Copilot pode ser utilizado para acelerar o desenvolvimento de software, com foco em geração de código automatizado e sugestões inteligentes. Os exemplos abaixo foram testados e documentados durante o laboratório do curso Java Cloud Native.

---

## ✅ Exemplo 1 — Geração de Código em Python

### 🎯 Prompt:
```python
# Função que retorna os 10 primeiros números primos em python
```
## ✅ Resultado sugerido pelo Copilot:
```
def eh_primo(n):
    if n < 2:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

def primeiros_primos(qtd):
    primos = []
    num = 2
    while len(primos) < qtd:
        if eh_primo(num):
            primos.append(num)
        num += 1
    return primos

print(primeiros_primos(10))
```
## 💬 Observações:
O Copilot entendeu perfeitamente a intenção do comentário e gerou uma solução completa e correta, com função auxiliar e lógica para encontrar os números primos. Resultado final:
```
[2, 3, 5, 7, 11, 13, 17, 19, 23, 29]
```
## ✅ Exemplo 2 — Testes Unitários com JUnit
🎯 Prompt:
```
// Criar testes unitários para a classe Calculadora usando JUnit
```
## 🧠 Código base da Calculadora:
```
public class Calculadora {
    public int somar(int a, int b) { return a + b; }
    public int subtrair(int a, int b) { return a - b; }
    public int multiplicar(int a, int b) { return a * b; }
    public double dividir(int a, int b) {
        if (b == 0) throw new ArithmeticException("Divisão por zero não permitida.");
        return (double) a / b;
    }
}
```
## ✅ Testes gerados pelo Copilot:
```
import static org.junit.jupiter.api.Assertions.*;
import org.junit.jupiter.api.Test;

public class CalculadoraTest {

    private final Calculadora calculadora = new Calculadora();

    @Test
    public void testSomar() {
        assertEquals(5, calculadora.somar(2, 3));
    }

    @Test
    public void testSubtrair() {
        assertEquals(1, calculadora.subtrair(3, 2));
    }

    @Test
    public void testMultiplicar() {
        assertEquals(6, calculadora.multiplicar(2, 3));
    }

    @Test
    public void testDividir() {
        assertEquals(2.0, calculadora.dividir(6, 3));
    }

    @Test
    public void testDividirPorZero() {
        assertThrows(ArithmeticException.class, () -> calculadora.dividir(6, 0));
    }
}
```
## 💬 Observações:
O Copilot sugeriu testes completos com base apenas em um comentário. Ele reconheceu a necessidade de testar operações básicas e até cobriu exceções, como divisão por zero. Impressionante a cobertura e assertividade.

## 🤖 Conclusão
O GitHub Copilot se mostrou extremamente eficaz para:

Gerar código a partir de prompts simples

Sugerir implementações completas com base em padrões comuns

Criar testes automatizados prontos para uso

💡 Com um pouco de criatividade nos prompts, dá pra economizar muito tempo e escrever código de forma mais rápida e eficiente.
