# Structs

{% hint style="info" %}
Este é um projeto humorístico. Não leve tudo o que for dito aqui a sério (ou leve, problema é seu).
{% endhint %}

Para declarar um `struct` em BIRL basta utilizar a palavra reservada `MUTANTE`.

<pre><code><strong>MUTANTE LUNATICO{
</strong>    MONSTRO Prop1;
    TRAPEZIO Prop2;
<strong>};
</strong>
HORA DO SHOW
    MUTANTE LUNATICO X;
<strong>    X.Prop1 = 10;
</strong><strong>    X.Prop2 = 3.14;
</strong>    CE QUER VER ESSA PORRA? ("Prop1: %d\n", X.Prop1);
    CE QUER VER ESSA PORRA? ("Prop2: %.2f\n", X.Prop2);
    BORA CUMPADE 0;
BIRL
</code></pre>

{% code title="Saída:" %}
```
Prop1: 10
Prop2: 3.14
```
{% endcode %}
