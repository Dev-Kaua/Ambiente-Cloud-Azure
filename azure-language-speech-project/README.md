# 🧠 Análise de Sentimentos com Azure Language & Speech Studio

Este repositório contém a documentação e os experimentos realizados como parte do desafio de projeto "Análise de Sentimentos com Language Studio no Azure AI", proposto pela DIO.

## 👨‍💻 Desenvolvido por

**Kauã Reis**  
Estudante de Análise e Desenvolvimento de Sistemas e entusiasta de soluções em IA, nuvem e tecnologia de ponta.

---

## 🚀 Objetivo

Explorar os serviços de IA oferecidos pela Microsoft através do **Azure Language Studio** e **Azure Speech Studio**, realizando testes práticos de:

- Análise de sentimentos e linguagem natural
- Reconhecimento de fala e transcrição de áudio
- Resposta automatizada de perguntas via QnA Maker
- Interpretação de linguagem coloquial

---

## 🧪 Tecnologias e Ferramentas

- Microsoft Azure
  - Language Studio
  - Speech Studio
- GitHub
- Ferramenta de captura de tela (ex: Lightshot, Snipping Tool)

---

## 🧠 Etapas Realizadas

### 🎙️ 1. Teste com Speech Studio
Utilizei o serviço de transcrição de voz para texto, gravando um áudio simples com uma frase positiva. O Azure foi capaz de identificar corretamente o conteúdo da fala, demonstrando uma ótima precisão.

📸 **Print**:  
speech_transcricao.png

---

### 💬 2. Análise de Sentimentos com Language Studio
Testei frases com diferentes cargas emocionais (positiva, negativa e neutra) para verificar o poder de análise do modelo.

📸 **Print**:  
language_sentimentos.png

---

### ❓ 3. Perguntas e Respostas com QnA
Criei um pequeno repositório de perguntas e respostas simulando um atendimento automatizado, e testei como o sistema interpreta as perguntas do usuário.

📸 **Print**:  
qna_respostas.png

---

### 😎 4. Teste com Linguagem Coloquial
Utilizei gírias, abreviações e expressões populares brasileiras para ver como o modelo reagia a textos informais.

📸 **Print**:  
linguagem_coloquial.png

---

## 💡 Insights e Aprendizados

> Durante a prática, percebi que os serviços do Azure são bastante intuitivos e funcionais. A análise de sentimentos funcionou muito bem com textos formais e informativos.  
> Já quando utilizei linguagem mais solta, com gírias ou abreviações, notei que o modelo teve certa dificuldade de interpretação, o que abre espaço para pensar em formas de treinamento mais localizados ou customizações para públicos específicos.  
> A experiência me fez enxergar o potencial de aplicações com foco em acessibilidade, atendimento automatizado e análise de opinião em larga escala.

---

## 📂 Estrutura do Repositório

```bash
📁 azure-language-speech-project
├── README.md
├── /images
│   ├── speech_transcricao.png
│   ├── language_sentimentos.png
│   ├── qna_respostas.png
│   └── linguagem_coloquial.png
└── insights.md (opcional)

---

## ✅ Conclusão
Esse projeto foi uma excelente introdução prática às ferramentas de IA da Microsoft, e serviu para reforçar conceitos importantes de NLP,
 reconhecimento de fala e integração com serviços cognitivos na nuvem. A prática me deixou ainda mais motivado a explorar esse universo e
 pensar em aplicações reais com essas tecnologias.
