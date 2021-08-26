---
title: "Trabajo Práctico 2"
---

### Actividad:

Dados los siguientes sistemas:


{{< tabs tabTotal="4" tabID="1" tabName1="Tema 1" tabName2="Tema 2" tabName3="Tema 3" tabName4="Tema 4" >}} 
{{< tab tabNum="1" >}}
1. \\( S(3) = \\{(1,3,3), (1,4,4), (1,6,6)\\} \\), \\(J(2)=\\{(3,1), (7,2)\\}\\)
2. \\( S(4) = \\{(1,4,4), (1,5,5), (2,7,7), (1,12,12)\\} \\), \\(J(4)=\\{(3,2), (9,3), (12,2), (14,1)\\}\\)
3. \\( S(4) = \\{(1,5,5), (1,7,7), (2,10,10), (1,20,20)\\} \\), \\(J(5)=\\{(0,2), (5,3), (11,2), (17,2), (21,4)\\}\\)
4. \\( S(5) = \\{(1,5,5), (1,6,6), (1,7,7), (1,10,10), (1,18,18)\\} \\), \\(J(5)=\\{(3,2), (5,4), (9,2), (17,2), (20,3)\\}\\)
{{< /tab >}}
{{< tab tabNum="2" >}}
1. \\( S(3) = \\{(1,3,3), (1,4,4), (1,6,6)\\} \\), \\(J(2)=\\{(3,1), (7,2)\\}\\)
2. \\( S(4) = \\{(1,4,4), (1,5,5), (2,7,7), (1,12,12)\\} \\), \\(J(4)=\\{(3,2), (9,3), (12,2), (14,1)\\}\\)
3. \\( S(4) = \\{(1,5,5), (1,7,7), (2,10,10), (1,20,20)\\} \\), \\(J(5)=\\{(0,2), (5,3), (11,2), (17,2), (21,4)\\}\\)
4. \\( S(5) = \\{(1,5,5), (1,6,6), (1,7,7), (1,10,10), (1,18,18)\\} \\), \\(J(5)=\\{(3,2), (5,4), (9,2), (17,2), (20,3)\\}\\)
{{< /tab >}}
{{< tab tabNum="3" >}}
1. \\( S(3) = \\{(1,3,3), (1,4,4), (1,6,6)\\} \\), \\(J(2)=\\{(3,1), (7,2)\\}\\)
2. \\( S(4) = \\{(1,4,4), (1,5,5), (2,7,7), (1,12,12)\\} \\), \\(J(4)=\\{(3,2), (9,3), (12,2), (14,1)\\}\\)
3. \\( S(4) = \\{(1,5,5), (1,7,7), (2,10,10), (1,20,20)\\} \\), \\(J(5)=\\{(0,2), (5,3), (11,2), (17,2), (21,4)\\}\\)
4. \\( S(5) = \\{(1,5,5), (1,6,6), (1,7,7), (1,10,10), (1,18,18)\\} \\), \\(J(5)=\\{(3,2), (5,4), (9,2), (17,2), (20,3)\\}\\)
{{< /tab >}}
{{< tab tabNum="4" >}}
1. \\( S(3) = \\{(1,3,3), (1,4,4), (1,6,6)\\} \\), \\(J(2)=\\{(3,1), (7,2)\\}\\)
2. \\( S(4) = \\{(1,4,4), (1,5,5), (2,7,7), (1,12,12)\\} \\), \\(J(4)=\\{(3,2), (9,3), (12,2), (14,1)\\}\\)
3. \\( S(4) = \\{(1,5,5), (1,7,7), (2,10,10), (1,20,20)\\} \\), \\(J(5)=\\{(0,2), (5,3), (11,2), (17,2), (21,4)\\}\\)
4. \\( S(5) = \\{(1,5,5), (1,6,6), (2,8,8), (1,10,10), (1,18,18)\\} \\), \\(J(5)=\\{(3,2), (5,4), (9,2), (17,2), (20,3)\\}\\)
{{< /tab >}}
{{< /tabs >}}

Calcular:

1. La capacidad de una tarea servidora **Polling Server (PS)**, cuyo periodo sea igual al de la tarea de mayor prioridad. Calcular la capacidad mediante el método de cotas.

1. La capacidad de una tarea servidora **Deferrable Server (DS)**, cuyo periodo sea igual al de la tarea de mayor prioridad. Emplear los métodos de cotas y mediante K. 

2. Diagramar la planificación hasta atender todas las tareas aperiódicas, para cada uno de los siguientes métodos: 
    - Background Server (BS), 
    - DS, 
    - PS, 
    - Dual Priority, 
    - K-diagramabilidad 
    - Slack Stealing (SS). 
   
   Emplear una heurística del tipo _greedy_ con respecto al slack disponible, capacidad del servidor, etc., para la atención de las tareas aperiódicas. Esto implica que cuando se instancie una tarea aperiódica, se haga el máximo esfuerzo para su atención, sin especular con que puede existir mayor cantidad de slack, tiempo de servidor, etc., en un instante posterior.

3. Calcular el tiempo de respuesta promedio de atención de las tareas aperiódicas para los distintos métodos.

4. Realizar una comparativa de los tiempos promedios de atención de cada método, indicando cual presentó el mejor desempeño y una breve justificación del por qué.

### Entrega:

- Formato: informe en formato PDF con los resultados (cálculos, planificación y comparativa). Se puede implementar los algoritmos en un programa (lenguaje a elección), como ayuda para realizar los ejercicios. En dicho caso, adjuntar también el código fuente del programa. 
- Enviar por email.
- Fecha límite: **16/9**.

