<!-- ### 4.4. Ecuaciones diofánticas
1. Analizar para qué valores de $n \in \mathbb{Z}$las siguientes ecuaciones tienen solución en $\mathbb{Z} ^2$.
a. $15x+4y = n$
b. $15x−5y = n$
c. $12x+3y = 3n$$12x+3y = 3n$

2. Resolver las siguientes ecuaciones diofánticas:
    a. $525x+100y = 50$ 
    b. $66x+550y = −88$
    c. $−175x+12y = 20$
    d. $129x−27y = 21$
    e. $131x+27y = 18$-->


### Ejercicios de final
Dada la ecuación diofántica $-300x + 230y = 50$(con $x,y ∈ \mathbb{Z}$):  
    Hallar todas las soluciones del sistema.  
    <!-- b) Si es posible, hallar todos los pares $(x, y)$que son parte de la solución y cumplen que 3000 < x < 3101. -->

##### Pasos para resolver:
1. __Algoritmo de Euclides__  
    $300 = 230 \times 1 + 70$  
    $230 = 70 \times 3 + 20$  
    $70 = 20 \times 3 + 10$  
    $20 = 10 \times 2 + 0$  
Obtenemos que $D(a,b) = 10|50$

 
2. __A partir de punto 3, reescribir 10 como:__  
    $10 = 70 \times 1 - 20 \times 3 $

3. __Multiplicar por 5 para que 10 = 50, como en la ecuación__  
    $10 \times 5 = 70 \times (1 \times 5)- 20 \times (3 \times 5)$
    $50 = 70 \times 5 - 20 \times 15$


4. __Reescribir 20:__  
    _De_ $230 = 70 \times 3 + 20$  
    _obtenemos_  
    $20 = 230 - 70 \times 3$

5. __Reescribir 70__  
    _De_ $300 = 230 + 70$  
    _obtenemos_  
    $70 = 300 - 230 $

6. __Reemplazar 20 en la ecuación del punto 6:__  
    $50 = 70 \times 5 - 20 \times 15$  
    $50 = 70 \times 5 - (230 - 70 \times 3) \times 15 $  
    $50 = 70 \times 5 - 230 \times 15 - 70 \times (3\times 15)$  
    $50 = 70 \times 5 - 230 \times 15 - 70 \times 45$  
    Juntamos coeficientes de 70 (5 + 45 = 50)  
    $50 = 70 \times 50 - 230 \times 15$  


7. __Reemplazar 70 en la ecuación del punto 9:__  
    $50 = 70 \times 50 - 230 \times 15$  
    $50 = (300 - 230) \times 50 - 230 \times 15$  
    $50 = 300 \times 50 - 230 \times 50 - 230 \times 15$  
    Juntar coeficientes de 230 (50 + 15 = 75)  
    $50 = 300 \times 50 - 230 \times 65$  
    Aqui obtuvimos una ecuación muy similar a la inicial: $-300x + 230y = 50$.  
    Debemos invertir ciertos valores para que quede de la misma forma.

 
8. __Invertir:__  
    $50 = (300 \times -1) \times (50 \times -1) - (230 \times -1) \times (65 \times -1)$  
    Obtenemos:  
    $50 = -300 \times (-50) + 230 \times (-65) $  
    Podemos observar que queda de la misma forma que $-300x + 230y = 50$  

    De este punto obtenemos que:  
    - $a = -300 $  
    - $x_0 = -50 $  
    - $b = 230 $  
    - $y_0 = -65$  

9. __Hallar $x_k,y_k$:__  

    $x_k = \frac{b}{D(a,b)}k = \frac{230}{10}k = 23k$  
      
    $y_k = \frac{-a}{D(a,b)}k = \frac{300}{10}k = 30k$  


10. __Hallar solución general:__  

    $x_g = x_0 + x_k = -50 + 23k$  
    $y_g = y_0 + y_k = -65 + 30k$  
