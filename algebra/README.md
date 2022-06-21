# Aplicando algebra linear


O estudo da Álgebra é sobre resolver equações como essa: <i>2x + 5 = 13</i>. Onde com base no contexto, precisamos descobrir qual o número, que substituindo a variável <strong>x</strong>, irá tornar a equação como verdadeira.

<img src="https://th.bing.com/th/id/R.5372c3f1e9e39f915122b5b84e9eb74d?rik=f4x5Wq1RQIvmGA&pid=ImgRaw&r=0" alt="algebra linear introdução">

<br>

## Resolvendo equações de primeiro grau

Podemos resolver este tipo de equação de várias maneiras, podendo ser muito eficaz ou com um custo muito alto.

 <img src="..\resources\algebra\find_x_value.png">

<br>

### Utilizando força bruta
<hr>


Dada a equação <i>2x + 5 = 13</i>. Precisamos encontrar o valor de <strong>x</strong>, que quando <i>multiplicado</i> por 2 e depois <i>somado</i> com 5, <strong>retorne 13</strong>.

#### Exemplo:
```python
# valor a ser encontrado x
# A valor inicial 100 é para fim estudantil
x = -100

while x < 100:
    # Equação de primeiro grau
    if 2 * x + 5 == 13: 
        # valor encontrado
        print("x =",x) 
        break
    # procura o próximo valor
    x +=1
```

>>x = 4


Vemos que o valor que procuramos é <strong>4</strong>.