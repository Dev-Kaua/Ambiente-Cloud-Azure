# Análise de Sentimentos com Azure AI Language Studio

> Projeto desenvolvido como parte do desafio de projeto da DIO utilizando o Azure AI Language Studio e Speech Studio para aplicar técnicas de **Processamento de Linguagem Natural (NLP)** e **Análise de Sentimentos**.

---

## 🔍 Visão Geral

Este repositório documenta minha exploração prática das ferramentas **Azure Speech Studio** e **Azure Language Studio**. O objetivo foi testar diferentes funcionalidades relacionadas à linguagem natural, com foco em:

* **Análise de Sentimentos**
* **Reconhecimento de Fala (Speech-to-Text)**
* **Resposta a Perguntas (Question Answering)**
* **Interpretação de Linguagem Coloquial**

---

## 🎯 Objetivos do Desafio

✅ Aplicar os conceitos aprendidos em um ambiente prático
✅ Documentar o processo técnico de forma clara e estruturada
✅ Utilizar o GitHub para compartilhar conhecimento técnico com a comunidade

---

## 🧪 Experimentos Realizados

Cada experimento foi realizado no **Azure Language Studio**, com o registro dos resultados em formato JSON e capturas de tela.

### 1. `analise_sentimentos.json`

* **Objetivo:** Avaliar sentimentos (positivo, negativo ou neutro) com base em frases simples.
* **Resultado:** A análise funcionou conforme o esperado, classificando corretamente as emoções presentes nas frases.
* **1° Captura de tela:** `images/analise_sentimentos_positivo.png`
* **2° Captura de tela:** `images/analise_sentimentos_negativo&neutro.png`

### 2. `Speech-to-text.json`

* **Objetivo:** Transcrever áudio para texto com precisão.
* **Resultado:** A ferramenta reconheceu corretamente a fala e transcreveu para texto sem dificuldades.
* **Captura de tela:** `images/speech_to_text.png`

### 3. `Answer-questions.json`

* **Objetivo:** Responder perguntas com base em um texto fornecido.
* **Resultado:** O sistema retornou respostas coerentes com base na entrada textual.
* **Captura de tela:** `images/answer_questions.png`

### 4. `Linguagem-coloquial.json`

* **Objetivo:** Analisar uma frase com linguagem informal/coloquial.

* **Entrada:** `"Mano, esse curso tá insano! Tô bolado com essa função que não roda kkk."`

* **Resultado:** A IA interpretou a frase como **negativa**, com alta confiança, embora o contexto fosse ambíguo.

  **Interpretação:**

  > Apesar da expressão "insano" muitas vezes ter conotação positiva no uso informal, o modelo entendeu como negativa. Isso revela um ponto interessante sobre os desafios da análise de linguagem coloquial no NLP.

* **Captura de tela:** `images/linguagem_coloquial.png`

* **JSON salvo em:** `results/linguagem-coloquial.json`

---

## 📁 Organização do Repositório

```
├── images/
│     ├── analise_sentimentos_positivo.png
│     ├── analise_sentimentos_negativo&neutro.png
│     ├── speech_to_text.png
│     ├── answer_questions.png
│     └── linguagem_coloquial.png
├── results/
│   ├── analise_sentimentos.json
│   ├── Speech-to-text.json
│   ├── Answer-questions.json
│   └── Linguagem-coloquial.json
└── README.md
```

---

## 🤖 Considerações Finais

A prática com essas ferramentas do Azure foi muito interessante para entender o poder (e as limitações) da inteligência artificial aplicada à linguagem. O experimento com linguagem coloquial foi o mais inesperado — e também o mais revelador.

> "Aprender IA é como ensinar um robô a entender fofoca de grupo do WhatsApp... exige paciência e muitos testes!" 😄

---

## 📚 Recursos Úteis

* [Azure Speech Studio](https://speech.microsoft.com/)
* [Azure Language Studio](https://language.cognitive.azure.com/)
* [Laboratórios Microsoft Learning](https://learn.microsoft.com/)

---

## 📌 Autor

**Kauã Reis**
Estudante de Análise e Desenvolvimento de Sistemas mergulhando no mundo da tecnologia, inteligência artificial e desenvolvimento backend. Sempre em busca do próximo nível! 🚀

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kauã_Reis-blue?logo=linkedin)](https://www.linkedin.com/in/kau%C3%A3-reis-rodrigues-730219357/)
