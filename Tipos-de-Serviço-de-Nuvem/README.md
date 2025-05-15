# 🚀 Resumo sobre Azure e Serviços de Nuvem - Desafio Prático DIO

Este repositório foi criado como parte do desafio prático proposto no curso da DIO sobre **Microsoft Azure e serviços de nuvem**. Aqui você encontrará **resumos**, **anotações**, **capturas de tela** e **dicas práticas** sobre os principais conceitos aprendidos durante as aulas.

## 🧠 O que mais gostei na aula

O que mais curti nesse desafio foi entender, de forma simples e prática, **como os diferentes modelos de serviço em nuvem (IaaS, PaaS e SaaS)** funcionam, e principalmente **a responsabilidade de cada parte** no modelo de nuvem. Isso muda completamente a visão de como as aplicações são estruturadas, implementadas e mantidas no mundo real.

Outro ponto top foi entender como a **plataforma Azure facilita essa abstração**, com recursos visuais, boas práticas já integradas e um processo intuitivo de configuração da instância de banco de dados.

## 🏗️ Tópicos abordados

Durante as aulas, foram abordados os seguintes temas:

- ☁️ **Tipos de serviço de nuvem**:
  🧱 IaaS (Infrastructure as a Service)
Oferece infraestrutura de TI sob demanda: servidores, redes, armazenamento, etc. Você gerencia o sistema operacional, o middleware e os dados. A nuvem só fornece o “terreno” e você constrói tudo.

👨‍💻 PaaS (Platform as a Service)
Plataforma pronta para desenvolvimento e deploy. Você só se preocupa com o código e os dados, enquanto o provedor gerencia sistema operacional, rede e infraestrutura. Ideal para quem quer focar no desenvolvimento e não perder tempo com setup de ambiente.

🧑‍💼 SaaS (Software as a Service)
Serviços completos já prontos para uso, geralmente acessados por navegador. O provedor cuida de absolutamente tudo — você só usa. Exemplos: Gmail, Microsoft 365, Trello.


## 🛡️ Modelo de Responsabilidade Compartilhada

A responsabilidade na nuvem é dividida entre **cliente e provedor**, dependendo do modelo (IaaS, PaaS ou SaaS):

| Modelo | Provedor de Nuvem cuida de...                        | Cliente cuida de...                                 |
|--------|------------------------------------------------------|-----------------------------------------------------|
| **IaaS** | Rede, hardware físico, armazenamento, virtualização | Sistema operacional, aplicativos, dados e configurações |
| **PaaS** | Infraestrutura, sistema operacional e middleware     | Código da aplicação, lógica de negócio e dados      |
| **SaaS** | Toda a stack: infraestrutura, SO, aplicação e dados | Apenas uso do serviço e gerenciamento de acesso     |

> 💡 **Resumo rápido:**  
> Quanto mais “aaS” no nome, **menos coisa você precisa gerenciar**.  
> - **SaaS** é tipo Uber: você só senta no banco e curte o passeio.  
> - **IaaS** é como alugar um carro: ainda tem que dirigir e abastecer.


## 🔍 **Casos de uso apropriado** para cada tipo de serviço:
  🧱 IaaS - Quando usar:

    -Quando você precisa de controle total sobre o ambiente (ex: sistemas legados, VPNs personalizadas).
    -Para empresas que querem migrar infraestrutura on-premise para a nuvem sem reescrever tudo.

👨‍💻 PaaS - Quando usar:

  -Projetos focados em desenvolvimento rápido e escalável.
  -Quando o time não quer gerenciar servidor, SO ou banco de dados.
  -Ideal para aplicações web e APIs.

🧑‍💼 SaaS - Quando usar:

  -Quando a solução já está pronta e atende a necessidade (ex: e-mail, CRM, gestão de tarefas).
  -Para reduzir custos e tempo de implantação.
  -Para equipes que não precisam ou não querem desenvolver software próprio.

- 🧩 **Descrição técnica** de cada modelo:
  - Infraestrutura sob demanda (IaaS)
  - Plataforma gerenciada para desenvolvimento (PaaS)
  - Software pronto para uso via navegador (SaaS)

## 💡 Dicas para quem está começando

- Explore os menus da Azure sem medo: muita coisa está escondida em menus secundários.
- Documente tudo, desde nome da instância até configurações de segurança.
- Leia com atenção os modelos de responsabilidade. Isso pode salvar sua aplicação no futuro.
- Pensa como dev, mas também como arquiteto de soluções! A nuvem é um mundo à parte.

## 🛠️ Tecnologias e Ferramentas

- [Microsoft Azure](https://azure.microsoft.com/)
- Git e GitHub
- Markdown para documentação

## 🎯 Objetivos atingidos

✅ Aplicar os conceitos aprendidos em um ambiente prático  
✅ Documentar processos técnicos de forma clara e estruturada  
✅ Utilizar o GitHub como ferramenta de compartilhamento técnico  


**Feito com foco e muita vontade de dominar a nuvem.**  
**Por [Kauã Reis](https://github.com/Dev-Kaua)** 🚀
