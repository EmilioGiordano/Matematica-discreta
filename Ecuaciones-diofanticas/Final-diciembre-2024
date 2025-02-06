### Ejercicios de final
Dada la ecuación diofántica $24x - 98y = 50$(con $x,y ∈ \mathbb{Z}$):  
    Hallar todas las soluciones del sistema.  
    <!-- b) Si es posible, hallar todos los pares $(x, y)$que son parte de la solución y cumplen que 3000 < x < 3101. -->


##### Pasos para resolver:  
1. __Algoritmo de Euclides__    
    $98 = 24 \times 4 + 2$    
    $24 = 2 \times 12 + 0$    
Obtenemos que $D(a,b) = 2|50$  

2. __A partir de punto 1, reescribir 2 como:__   
    $2 = 98 \times 1 - 24 \times 4$  

3. __Multiplicar por 25 para que 2 = 50, como en la ecuación:__    
    $2 \times 25 = 98 \times (1 \times 25) - 24 \times (4 \times 25)$  
    $50 = 98 \times 25 - 24 \times 100$  
   

4. Invertir la resta para tener una ecuación de la misma forma que $24x - 98y = 50$  
    $50 = 24 \times (-100) - 98 \times (-25)$  
    De este punto obtenemos que:  
    - $a = 24 $  
    - $x_0 = -100 $  
    - $b = -98 $  
    - $y_0 = -25$  

5. __Hallar $x_k,y_k$:__  

    $x_k = \frac{b}{D(a,b)}k = \frac{-98}{2}k = -49k$   
      
    $y_k = \frac{-a}{D(a,b)}k = \frac{-24}{2}k = -12k$  

6. __Hallar solución general:__  
    $x_g = x_0 + x_k = -100 - 49k$  
    $y_g = y_0 + y_k = -25 -12k$ 
