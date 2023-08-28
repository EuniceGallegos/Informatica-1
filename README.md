# Informatica-1
<img src="Images/16805545425507.jpg" alt="I A" width="100%"/>


Correo: [estiviseguritos@gmail.com](mailto:estiviseguritos@gmail.com) 

Telegram: [Telegram](https://telegram.org/apps) 

Elementos del problema:

1.  Decisor: El propietario de la tienda.

2.  Cursos de acción:

    -   $a_1 \approx$ pedir 100 prendas posibles.\
    -   $a_1 \approx$ pedir 200 prendas.\
    -   $a_3 \approx$ pedir 300 prendas.

3.  Estados de la naturaleza:

    -   $\theta_1 \approx$ demanda de 100 prendas.\
    -   $\theta_2 \approx$ demanda de 150 prendas.\
    -   $\theta_3 \approx$ demanda de 200 prendas.

4.  Función de consecuencias:

    -   Pago asociado con cada par ($\theta_i$, $a_j$)

    La función de consecuencias depende de la cantidad de playeras
    pedidas y de la cantidad vendida:

    (a) Si la demanda es igual al pedido, el resultado está dado por:

        $$(demanda) \times (ganancia)$$

        donde:

        $$ganancia = precio\:de\:venta - precio\:de\:compra$$

        [Pag. 13]

    (b) Si la demanda es menor que el pedido, el resultado se obtiene al
        calcular:

        $$[(demanda)\:(ganancia)] + [(pedido - demanda)\:(precio\:de\:remate - precio\:de\:compra)]$$

    (c) Y si la demanda es mayor que el pedido:

        $$[(pedido)\:(ganancia)] - [(5)\:(demanda - pedido)]$$

5.  Matriz de resultados (matriz de pagos, matriz de consecuencias,
    matriz de decisión):


$$
\begin{equation}
\begin{matrix}
{Acción\:(pedido)\\Estado\:de\:la\:\\naturaleza\:(demanda)} & {a_1 \\ 100} & {a_2 \\ 200} & {a_3\\300} \\
{\theta_1\:=\:100} & \$2,000 & \$0     & \$-1,500 \\
{\theta_2\:=\:150} & \$1,750 & \$3,000 & \$1,500 \\
{\theta_3\:=\:200} & \$1,500 & \$6,000 & \$4,500
\end{matrix}
\end{equation} 
$$

\theta_1\:=\:100
