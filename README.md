# O Nordeste espera mais?

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KevinCostaAI/nordeste-espera-mais/blob/main/01_o_nordeste_espera_mais.ipynb)

Prazo de entrega no e-commerce brasileiro: 96.470 pedidos entregues, dados públicos da Olist (2016–2018).

## A pergunta

Moro em Fortaleza e, **quando compro pela internet**, tinha a impressão de esperar mais que quem mora em São Paulo. Impressão não é dado, então fui medir.

## O que encontrei

**O Ceará espera 21 dias. São Paulo, 8.**

Por região, o Nordeste espera 19,5 dias contra 10,3 do Sudeste, e 12,7% dos pedidos chegam atrasados — mais que o dobro dos 6,1% do Sudeste.

**Mas a explicação não é a distância.** Prometem 30,3 dias para o Nordeste e 21,2 para o Sudeste: a distância já está embutida na promessa.

**O que explica é a variação.** No Sudeste, metade dos pedidos chega em 8 dias e o décimo mais lento em 19. No Nordeste, metade chega em 17 e o décimo mais lento em 33.

A entrega para o Nordeste não é só mais lenta: é menos previsível. E prazo imprevisível quebra promessa.

## Como cheguei aqui

Comecei achando que a distância explicava tudo. Fui buscar o prazo prometido por região para confirmar — e a hipótese caiu. Refazer a análise a partir daí foi o que deu o resultado.

## O que este número não mostra

**Só olhei pedidos que chegaram.** Não dá para medir tempo de entrega de pedido que nunca chegou — e é aí que mora o problema maior. Se o Nordeste tiver proporcionalmente mais pedidos cancelados ou extraviados, os 19,5 dias e os 12,7% são o **piso, não o teto**.

O [Projeto 3](https://github.com/KevinCostaAI/o-que-o-cliente-reclama) mostrou o tamanho disso: a queixa mais comum de quem teve pedido atrasado não é a demora, é **não saber onde está o pedido**.

E não é uma amostra do Brasil: é a Olist, um marketplace, entre 2016 e 2018.

## Como rodar

Abra o notebook no Google Colab e execute as células em ordem. Os dados são baixados pelo próprio notebook: não é preciso instalar nada.

**Ferramentas:** Python · pandas · matplotlib · Google Colab

---

## A trilogia

Três projetos sobre a mesma base, feitos em sequência. **Os três estão publicados.**

| Projeto | Pergunta | Resposta |
|---|---|---|
| **1 — este** | quem espera mais? | o Nordeste — e não é distância, é imprevisibilidade |
| [2 — Dá pra saber que vai atrasar?](https://github.com/KevinCostaAI/prever-atraso-entrega) | dá pra prever? | dá, e o modelo redesenhou o mapa do Brasil sozinho |
| [3 — O que o cliente reclama?](https://github.com/KevinCostaAI/o-que-o-cliente-reclama) | o que o cliente sente? | não sente atraso: sente que o pedido sumiu |

---

**Dados:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) · 2016–2018 · uso público

Kevin Moreira da Costa · [LinkedIn](https://www.linkedin.com/in/KevinCostaAI) · KevinCostaAI@outlook.com
