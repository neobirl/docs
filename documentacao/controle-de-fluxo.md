# Controle de Fluxo

{% hint style="info" %}
Este é um projeto humorístico. Não leve tudo o que for dito aqui a sério (ou leve, problema é seu).
{% endhint %}

## If, else, else if

Para controlarmos o fluxo do código através de `if`, `else if`, ou `else` basta usarmos, respectivamente, as palavras `ELE QUE A GENTE QUER?`, `QUE NAO VAI DAR O QUE?`, `NAO VAI DAR NAO`

{% code title="Usando If" %}
```c
ELE QUE A GENTE QUER? (3 > 2)
    CE QUER VER ESSA PORRA? ("A CONDIÇÃO PASSOU, CARALHO!");
BIRL
```
{% endcode %}

{% code title="Usando If else" %}
```c
ELE QUE A GENTE QUER? (1 > 2)
    CE QUER VER ESSA PORRA? ("AQUI NÃO CAI!");
NAO VAI DAR NAO
    CE QUER VER ESSA PORRA? ("QUE NUM VAI DAR RAPÁ?");
BIRL
```
{% endcode %}

{% code title="Usando If, else if e else" %}
```c
ELE QUE A GENTE QUER? (1 > 2)
    CE QUER VER ESSA PORRA? ("AQUI NÃO CAI!");
QUE NAO VAI DAR O QUE? (1 < 2)
    CE QUER VER ESSA PORRA? ("BIRL!");
NAO VAI DAR NAO
    CE QUER VER ESSA PORRA? ("AQUI NÃO CAI!");
BIRL
```
{% endcode %}

## Switch-case

Iniciamos o `switch` com a função `DERRUBAR ARVORES (X)`, usamos o `case` com a palavra reservada `ARVORE` juntamente do valor. O `default` é representado pela palavra `IBIRAPUERA.` Já o `SAI FILHO DA PUTA` representa o break.

{% code title="Usando switch-case" %}
```c
MONSTRO x = 13;
    
    DERRUBAR ARVORES (x)
        ARVORE 13
            CE QUER VER ESSA PORRA? ("É 13 MEMO");
            SAI FILHO DA PUTA;
        
        ARVORE 10
            CE QUER VER ESSA PORRA? ("NUM VAI DAR NAO");
            SAI FILHO DA PUTA;
        
        IBERAPUERA
            CE QUER VER ESSA PORRA? ("PADRAO");
            SAI FILHO DA PUTA;
    BIRL
```
{% endcode %}

## break/continue

Para usar o `break`, utilize `SAI FILHO DA PUTA;`

Para usar o `continue`, utilize `VAMO MONSTRO;`
