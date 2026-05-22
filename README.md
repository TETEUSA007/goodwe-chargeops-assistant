# Chatbot - GoodWe

## Integrantes
- Matheus Sabino da Silva Guedes — RM 572907
- Lucas Bellezzo Figueiredo - RM : 569734
- Maria Luiza Vieira de Freitas - RM : 571535
- Matheus Arruda Camara Soares - RM : 571594
- Giovanna Ferreira - RM : 571822

## Contexto do Projeto

O projeto foi desenvolvido para a Sprint 1 do EV Challenge 2026, em parceria com a GoodWe e FIAP.

O desafio envolve a criação de soluções inteligentes para melhorar a gestão de recarga de veículos elétricos. No contexto escolhido, o problema central é o uso compartilhado de carregadores em condomínios, onde síndicos, moradores e administradores precisam controlar reservas, horários, consumo, regras de uso, suporte básico e organização dos ciclos de recarga.

## Problema Abordado

Em condomínios com carregadores de veículos elétricos, podem ocorrer problemas como:

- Dificuldade para organizar horários de uso.
- Falta de clareza sobre regras de recarga.
- Dúvidas recorrentes de moradores.
- Ausência de orientação rápida sobre consumo e cobrança.
- Sobrecarga de atendimento para o síndico ou administrador.
- Necessidade de registrar ciclos de recarga e orientar o uso correto.

## Proposta do Chatbot

O GoodWe ChargeOps Assistant será um chatbot operacional voltado para síndicos e administradores de condomínios.

O chatbot ajudará a responder dúvidas sobre:

- Agendamento de recargas.
- Regras de uso dos carregadores.
- Como registrar ciclos de carregamento.
- Orientações de cobrança proporcional.
- Dúvidas básicas sobre falhas ou indisponibilidade.
- Comunicação com moradores.
- Boas práticas de uso compartilhado.

A proposta não é criar um chatbot genérico, mas sim uma ferramenta de apoio operacional para condomínios que utilizam infraestrutura de recarga GoodWe.

## Persona Escolhida

A persona principal será o síndico ou administrador do condomínio.

Essa escolha foi feita porque o síndico precisa lidar com regras, controle de uso, reclamações, organização dos moradores e dúvidas recorrentes. Assim, o chatbot pode reduzir o tempo gasto em atendimento e melhorar a organização do carregamento compartilhado.

## Tecnologias Selecionadas

### OpenAI API

Será utilizada para processar perguntas em linguagem natural e gerar respostas contextualizadas.

Justificativa: possui boa capacidade de interpretação de texto, geração de respostas claras e adaptação a diferentes contextos operacionais.

### LangChain

Será utilizado para estruturar o fluxo do chatbot, organizar o contexto e permitir futura integração com documentos, banco de dados ou sistema RAG.

Justificativa: facilita a criação de aplicações com LLMs e permite evoluir o projeto nas próximas sprints.

### Python

Será utilizado no backend do chatbot.

Justificativa: é uma linguagem simples, muito usada em projetos de IA e possui boa integração com APIs e bibliotecas de machine learning.

### Streamlit ou React

Será utilizado para criar a interface inicial do chatbot.

Justificativa: permite criar uma interface simples para testes, onde o usuário poderá digitar perguntas e receber respostas.

### GitHub

Será utilizado para versionamento, documentação e entrega do projeto.

## Funcionamento Geral

1. O usuário acessa o chatbot.
2. O usuário digita uma pergunta sobre uso do carregador no condomínio.
3. O sistema envia a pergunta junto com o contexto-base para o modelo de IA.
4. O modelo interpreta a pergunta.
5. O chatbot responde de forma clara, operacional e contextualizada.
6. Caso a pergunta envolva emergência, manutenção complexa ou dados inexistentes, o chatbot orienta o usuário a acionar suporte humano.

## Objetivo da Sprint 1

Nesta sprint, o objetivo é documentar a proposta do chatbot, definir o escopo, escolher as tecnologias, criar o fluxograma de funcionamento, elaborar o modelo de teste e construir o system prompt que será usado como base na Sprint 2.
