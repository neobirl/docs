---
description: Uma breve introdução sobre a linguagem NeoBIRL.
---

# Introdução

> Um agradecimento a **@lcfpadilha, @akafts, e toda a comunidade codebuilder do Brasil.**

{% hint style="info" %}
Este é um projeto humorístico. Não leve tudo o que for dito aqui a sério (ou leve, problema é seu).
{% endhint %}

## Índice

* [O que é NeoBIRL?](./#o-que-e-neobirl)
* [Quais são as novas funcionalidades?](./#quais-sao-as-novas-funcionalidades)
* [BIRL vs C.](./#birl-vs-c)

## O que é NeoBIRL?

NeoBIRL (Neo-Bambam's "It's show time" Recursive Language) nada mais é do que uma linguagem humorística, OAG (Orientada a Gambiarra), Go Horse e baseada na semi-falecida [BIRL Language](https://github.com/birl-language/). NeoBIRL funciona do mesmo modo que sua antecessora, mas com algumas funcionalidades a mais. Pretendemos dar continuidade para a linguagem mais TREZE já criada!

## Quais são as novas funcionalidades?

NeoBIRL possui uma [CLI](https://github.com/neobirl/cli), enquanto a BIRL Language funciona através de um [servidor](https://github.com/birl-language/birl-server). Isso faz com que consigamos executar o nosso código BIRL sem a necessidade de ter conexão com a internet, ou até mesmo de ter um servidor rodando localmente.&#x20;

{% hint style="info" %}
No momento em que essa documentação é escrita (18/08/2023) o servidor da BIRL Language está fora do ar. Absolutamente ninguém liga, mas isso serviu de incentivo para a criação deste projeto.
{% endhint %}

NeoBIRL possui também novos recursos de:

* [Constantes](documentacao/variaveis-constantes-e-arrays.md);
* [Structs](documentacao/structs.md);
* [Switch-case](documentacao/controle-de-fluxo.md#switch-case);
* [Tipos de dados booleanos](documentacao/tipos.md#tipagem-mutante).

Tirando toda essa patifaria, funciona da mesma maneira. A CLI recebe um código BIRL e converte para C através de algumas expressões regulares gambiarrentas (pleonasmo, pois é um consenso acadêmico que toda regex é gambiarra), após isso, compilamos o código, executamos e recebemos a saída.

## BIRL vs C

C é uma linguagem amaldiçoada criada por programadores que gostam de subir em árvore (assista [isso ](https://www.youtube.com/watch?v=sf3EXZ0pL1w)para mais informações). Um dos objetivos da BIRL Language é se [afastar o máximo possível de C](https://github.com/birl-language/birl-language.github.io#to-do), e nós almejamos isso também, obviamente.

É perfeitamente possível (infelizmente) conciliar código C com código BIRL. Entretanto, isso é uma má prática (heresia) e deve ser evitada ao máximo. Quer usar alguma coisa de C que ainda não foi incluída na linguagem? Se vira, bonzão. [Vai fazer um PR e para de choramingar.](https://github.com/neobirl/cli)

### HERESIA:

{% code title="HERESIA.BIRL" %}
```c
HORA DO SHOW
    printf("Hello, World! Porra!\n");
    BORA CUMPADE 0;
BIRL
```
{% endcode %}

### BOA PRÁTICA:

```c
HORA DO SHOW
    CE QUER VER ESSA PORRA? ("Hello, World! Porra!\n");
    BORA CUMPADE 0;
BIRL
```
