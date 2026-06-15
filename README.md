# Chatbot GoodWe - Sprint 2

## Integrantes

* Bruno Riquelme Coutinho Pereira - RM 569619
* Eduardo Bigoli Portela - RM 569897
* Gabriel Martins Cordeiro Rodrigues - RM 570497
* Gustavo Fondato de Souza - RM 573651
* Gustavo Martins Da Silva - RM 570584
* Lucas Lino Marques da Silva - RM 572863

## Sobre o Projeto

Este projeto foi desenvolvido para o EV Challenge 2026 proposto pela GoodWe.

O objetivo foi criar um chatbot utilizando Inteligência Artificial para auxiliar operadores comerciais no gerenciamento de carregadores de veículos elétricos.

O chatbot foi pensado para responder dúvidas relacionadas à disponibilidade dos carregadores, tempo de espera, faturamento, falhas nos equipamentos e informações operacionais.

## Problema Abordado

Atualmente, muitos locais que possuem carregadores de veículos elétricos enfrentam dificuldades para acompanhar o uso dos equipamentos, controlar informações de carregamento e monitorar possíveis falhas.

O chatbot foi criado para facilitar esse processo, permitindo consultas rápidas através de uma conversa simples.

## Tecnologia Utilizada

* Python
* OpenAI API
* LangChain
* Google Colab
* GitHub

## Funcionamento

O sistema utiliza um System Prompt para definir o contexto da GoodWe e manter as respostas dentro do tema do projeto.

Além disso, foi implementado um histórico de mensagens para que o chatbot consiga manter o contexto da conversa.

Para tornar a demonstração mais realista, alguns dados operacionais são gerados automaticamente, como:

* quantidade de carregadores;
* carregadores disponíveis;
* carregadores em uso;
* carregadores em manutenção;
* tempo médio de espera;
* quantidade de carregamentos realizados;
* valor da última sessão;
* carregadores com falha.

## Como Executar

1. Abrir o Google Colab.
2. Instalar as bibliotecas necessárias.
3. Configurar a chave da OpenAI utilizando Secrets do Colab.
4. Executar as células do notebook.
5. Realizar perguntas ao chatbot.

## Perguntas Utilizadas nos Testes

* Existe carregador disponível?
* Qual o tempo de espera?
* Quanto custou minha sessão?
* Existe falha em algum carregador?
* Quantos carregamentos foram realizados hoje?

## Estrutura do Projeto

```text
chatbot-goodwe-sprint2

README.md

docs/
├── system_prompt.md
├── modelo_teste.md
└── resultados_teste.md

Chatbot_GoodWe.ipynb
```

## Resultados

Os testes mostraram que o chatbot conseguiu responder adequadamente às perguntas dentro do contexto da GoodWe e do EV Challenge 2026.

Também foram realizados testes adicionais para verificar a capacidade do chatbot em fornecer resumos operacionais e informações complementares.

## Conclusão

Com este projeto foi possível desenvolver um chatbot simples utilizando Inteligência Artificial, aplicando conceitos de contexto, histórico de conversa e integração com modelos de linguagem.

A solução demonstra como a IA pode auxiliar operadores comerciais no acompanhamento de carregadores de veículos elétricos de forma rápida e prática.
