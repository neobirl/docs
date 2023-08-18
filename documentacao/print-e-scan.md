---
description: CE QUER VER ESSA PORRA?
---

# Print e Scan

{% hint style="info" %}
Este é um projeto humorístico. Não leve tudo o que for dito aqui a sério (ou leve, problema é seu).
{% endhint %}

\
Para escrevermos algo na tela precisamos usar `CE QUER VER ESSA PORRA?()` como no exemplo a seguir:

{% code title="2 - 1" %}
```
HORA DO SHOW
    CE QUER VER ESSA PORRA? ("Hello, World! Porra!\n");
    BORA CUMPADE 0;
BIRL
```
{% endcode %}

Saída:

{% code title="2 - 2" %}
```
Hello, World! Porra!
```
{% endcode %}

Para lermos uma entrada do usuário precisamos usar `QUE QUE CE QUER MONSTRAO?()`:

{% code title="2 - 3" lineNumbers="true" %}
```
HORA DO SHOW
    MONSTRO X;
    QUE QUE CE QUER MONSTRAO? ("%d", &X);
    CE QUER VER ESSA PORRA?("%d", X*2);
    BORA CUMPADE 0;
BIRL
```
{% endcode %}

Saída:

{% code title="2 - 4" %}
```c
// birl code.birl 2

4
```
{% endcode %}

Como você percebeu, quando exibimos ou lemos variáveis, fazemos uso de [especificadores](https://www.freecodecamp.org/news/format-specifiers-in-c/). No exemplo `2 - 3`, o especificador é `%d`. O especificador deve mudar de acordo com o tipo da variável. Eis uma tabela com cada especificador:

&#x20;

| TIPO                 | ESPECIFICADOR |
| -------------------- | ------------- |
| FRANGO               | %c            |
| MONSTRO              | %d            |
| MONSTRINHO           | %hd           |
| MONSTRAO             | %li           |
| TRAPEZIO             | %f            |
| TRAPEZIO DESCENDENTE | %lf           |
| BICEPS               | %u            |
| TREZE MEMO           | %d            |

Outra coisa a ser notada é que, na linha 3 do exemplo `2 - 3`, passamos o endereço da memória da variável `X` usando o operador `&`. Isso permite que a função escreva o valor lido diretamente na memória da variável `X`.

\
