# Proposta Inicial do Jogo

Este documento deve ser preenchido pelo grupo na etapa inicial do projeto.

A proposta deve apresentar uma ideia simples, clara e viável para ser desenvolvida com **Python e Pygame** dentro do prazo disponível. Consulte o enunciado publicado no Canvas para conhecer o eixo temático e as orientações vigentes.

## 1. Nome provisório do jogo

Informe o nome provisório do jogo.

**Nome:**

> A IA Louca

## 2. Integrantes do grupo

- Nome 1:Mayra 
- Nome 2:Ana Flavia
- Nome 3:Bernardo Henrique
- Nome 4:

## 3. Tema escolhido

Indique qual tema específico o grupo escolheu **dentro do eixo temático definido no enunciado**.

**Tema:**

> Assistentes virtuais: interpretação de pedidos, limites das respostas e necessidade de confirmação (eixo: Inteligência Artificial no Cotidiano).

**Como esse tema se relaciona com o jogo?** Explique brevemente (2 a 4 linhas) como ele aparecerá nos objetivos, nas regras ou nos desafios, e não apenas nas imagens ou no cenário.

> O jogador controla um cliente a tentar fazer compras por voz. A IA "surta" e compreende os pedidos de forma literal ou absurda. O desafio mecânico é recolher os pedidos corretos e desviar das alucinações da IA para não estourar o limite do cartão.

## 4. Tipo de jogo
labirinto, perguntas e respostas, memória, pong, snake, breakout, corrida ou sobrevivência simples.


**Tipo escolhido:**

> Coleta de itens (Catcher) e sobrevivência simples.

## 5. Descrição geral do jogo

Explique, em poucas linhas, como o jogo funcionará. O que aparece na tela? O que o jogador controla? O que ele precisa fazer e quais desafios encontrará?

**Descrição:**

> O jogo decorre numa única tela onde chovem objetos a partir do topo. O jogador controla o personagem (o cliente) apenas na base do ecrã, movendo-se para os lados. Ele precisa de apanhar as compras corretas que pediu e desviar-se dos itens absurdos que a IA comprou por engano.

## 6. Objetivo do jogador

Descreva o objetivo principal. Por exemplo: coletar itens, sobreviver por determinado tempo, chegar ao final de um percurso ou completar desafios.

**Objetivo:**

> Recolher o máximo de pedidos corretos para alcançar a meta de pontos, sobrevivendo às alucinações da IA para salvar o limite do cartão de crédito.

## 7. Regras principais

Liste até cinco regras que expliquem o funcionamento do jogo. Exemplos: o jogador começa com três vidas; acertos somam pontos; colisões retiram vidas.

- Regra 1:O jogador começa a partida com 3 vidas.
- Regra 2:A movimentação é estritamente hotizontal(da esquerda a direita)
- Regra 3:Recolher um "pedido correto" soma 1 ponto
- Regra 4:Colidir com uma "alucinação da IA" (pedido errado) retira uma vida.
- Regra 5:O jogo termina automaticamente quando o limite de pontos é atingido ou as vidas chegam a xero

## 8. Condição de vitória

Explique como o jogador vence ou conclui a partida. Exemplos: alcançar uma pontuação, finalizar uma fase ou completar todas as tarefas.

**Condição de vitória:**

> Atingir a pontuação máxima de 20 pedidos corretos salvos.

## 9. Condição de derrota ou encerramento

Explique quando a partida termina ou como o jogador perde. Exemplos: esgotar as vidas, acabar o tempo ou atingir o limite de erros.

**Condição de derrota ou encerramento:**

> Esgotar as 3 vidas (significando que a IA estourou o limite do cartão bancário com compras erradas).

## 10. Elementos previstos no jogo

Descreva brevemente os elementos mais importantes, sem precisar detalhar a implementação.

- **Personagem ou elemento principal:** avatar do clicente na base do ecrã
- **Obstáculos ou desafios:** Objetos absurdos gerados pela IA a cair do topo (ex: um tijolo)
- **Itens ou objetos de interação (se houver):** Compras corretas a cair do topo (ex:maquiagem, roupas)
- **Pontuação, vidas, tempo ou progresso:** Contador numérico de pontos e contador de 3 vidas (exibidos no ecrã ou no terminal)

## 11. Controles previstos

Informe como o jogador vai interagir com o jogo (por exemplo, setas para movimentar, espaço para agir ou mouse para selecionar).

**Controles:**

> Exclusivamente pelo teclado: Seta para a Esquerda e Seta para a Direita para movimentar o personagem principal.

## 12. Principais dificuldades esperadas

Cite até três dificuldades que o grupo espera enfrentar. Exemplos: movimentação, colisões, controle de tempo, testes ou uso do GitHub.

- Dificuldade 1: Implementar a lógica de colisão (hitbox) entre as listas de itens em queda e o jogador usando apenas as estruturas base da disciplina.
- Dificuldade 2:Controlar corretamente o laço principal de repetição (while) sem utilizar comandos forçados como o break.
- Dificuldade 3: Equilibrar e sincronizar a velocidade de múltiplos objetos a cair simultaneamente para que o jogo seja justo.

## 13. Escopo mínimo para a entrega final

Descreva a **versão mais simples que já seria jogável**, com as interações e regras essenciais. Evite planejar funcionalidades demais.

**Escopo mínimo:**

> Uma janela a correr com o personagem a mover-se para os lados, geração e queda constante de itens bons e maus, deteção de colisão funcional e sistema básico de pontuação e vidas a ser atualizado.

## 14. Possíveis melhorias, caso haja tempo

Liste até três funcionalidades extras para implementar somente depois que a versão mínima estiver funcionando. Exemplos: sons, fases, ranking, animações ou menu inicial.

- Melhoria 1: substituir formas geométricas por imagens reais(sprintes)
- Melhoria 2: adicionar efeitos sonoros para as colisões e para a recolha de itens
- Melhoria 3: criar um sistema que guarde o recorde de pontuação num ficheiro de texto (.txt)
