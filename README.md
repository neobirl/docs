# Documentação da NeoBIRL.


## Introdução
Essa documentação ainda está incompleta pois nós somos developers <b>cansados.</b> As novas implementações da NeoBIRL em relação a BIRL Language foram:
1. Constantes;
2. Bool;
3. Structs;
4. Switch.

para consultar a documentação das outras funções, acesse: https://birl-language.github.io/
### Constantes

Para declarar uma constante em NeoBIRL basta utilizar a palavra reservada <code>FIBRA</code>.

```C
HORA DO SHOW
  FIBRA MONSTRO X = 30; /* Cria uma constante do tipo inteiro que recebe o valor 30. */
BIRL
```

### Bool.
Para declarar um booleano em NeoBIRL basta utilizar a palavra(s?) reservada <code>TREZE MEMO</code>.
```C
HORA DO SHOW
  TREZE MEMO A = false;
BIRL
```

### Structs

Para declarar uma constante em NeoBIRL basta utilizar a palavra reservada <code>MUTANTE</code>.

```C
MUTANTE LUNATICO{
    MONSTRO Prop1;
    TRAPEZIO Prop2;
};

HORA DO SHOW
    struct LUNATICO X;
    X.Prop1 = 10;
    X.Prop2 = 3.14;
    CE QUER VER ESSA PORRA? ("Prop1: %d\n", X.Prop1);
    CE QUER VER ESSA PORRA? ("Prop2: %.2f\n", X.Prop2);
    BORA CUMPADE 0;
BIRL
```

### Switch-case

Iniciamos o switch com a função <code>DERRUBAR ARVORES (X)</code>, usamos o case com a palavra reservada <code>ARVORE</code> juntamente do valor. O default é representado pela palavra <code>IBIRAPUERA.</code> Já o <code>SAI FILHO DA PUTA</code> representa o break.

```C
HORA DO SHOW
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
    
    BORA CUMPADE 0;
BIRL
```
