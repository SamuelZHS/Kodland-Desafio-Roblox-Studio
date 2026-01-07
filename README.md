# Desafio Roblox Studio

## Visão Geral

Este repositório contém a implementação do **Desafio Roblox Studio – Etapa 1**, desenvolvido como parte de um teste prático. O objetivo principal do desafio foi demonstrar conhecimentos básicos de **construção de cenário**, **uso de Parts e Terrain**, **correção de scripts**, **animações** e **TweenService** dentro do Roblox Studio.

O projeto foi concluído com sucesso. A plataforma móvel entre as ilhas foi implementada corretamente e funciona como esperado. No entanto, há uma limitação conhecida relacionada à permanência do jogador sobre a plataforma, explicada mais abaixo.

---

## Etapa 1 – Atividade 1: Construção do Mundo

### 1. Importação do Projeto

* O projeto foi baixado a partir do link fornecido.
* Aberto e configurado no **Roblox Studio**, respeitando a estrutura original.

### 2. Arco de Lama (Terrain)

* Foi construído um grande arco utilizando o **Terrain Editor**.
* O material utilizado foi **Mud (Lama)**, conforme solicitado.

### 3. Arco Construído com Parts

* Um segundo arco foi criado utilizando **Parts tradicionais**.
* As partes foram ajustadas manualmente para formar a estrutura do arco.

### 4. Caixa de Ferramentas

* Uma pequena caixa foi construída utilizando Parts.
* O material da caixa foi alterado para **Wood (Madeira)**.

### 5. Saliência de Terreno Plano

* Foi criada uma área de terreno plano.
* Não há abismos profundos nem montanhas altas, garantindo fácil navegação para o jogador.

---

## Etapa 1 – Atividade 2: Scripts e Funcionalidades

### 1. Correção de Erros de Script

#### 1.1 Contador de Moedas

* Problema: ao coletar uma moeda, o valor não era somado ao contador.
* Solução: o script foi ajustado para garantir que o valor da moeda seja corretamente adicionado ao saldo do jogador.

#### 1.2 Compra de Boost de Velocidade

* Problema: o jogador conseguia comprar o boost sem que o custo fosse descontado das moedas.
* Solução: foi implementada a lógica de verificação de saldo e o desconto correto no momento da compra.

---

### 2. Animação da Moeda

* Foi criada uma animação simples onde a moeda gira continuamente em torno do próprio eixo.
* A rotação é feita via script, garantindo fluidez e reaproveitamento do código.

---

### 3. Plataforma Móvel (TweenService)

* Foi criada uma plataforma que se move entre duas ilhas.
* O movimento foi implementado utilizando o **TweenService**.
* A plataforma percorre corretamente o trajeto de ida e volta entre os pontos definidos.

#### Limitação Conhecida

* A plataforma **funciona corretamente**, cumprindo o objetivo principal do desafio (movimentar-se entre as ilhas).
* No entanto, não foi possível garantir que o jogador permaneça sobre a plataforma durante todo o movimento.
* Apesar disso, o requisito principal da atividade foi atendido: **criar uma plataforma móvel funcional entre duas ilhas**.

---

## Tecnologias e Conceitos Utilizados

* Roblox Studio
* Parts e Terrain
* Scripts em Lua
* TweenService
* Animações básicas
* Lógica de moedas e sistema de compra

---

## Considerações Finais

Este desafio foi concluído com foco na funcionalidade, organização e entendimento dos conceitos fundamentais do Roblox Studio. Mesmo com a limitação mencionada na plataforma móvel, o objetivo central foi alcançado e todas as etapas propostas foram implementadas.

O projeto demonstra capacidade de adaptação, resolução de problemas e aplicação prática de scripts e construção de ambientes no Roblox.
