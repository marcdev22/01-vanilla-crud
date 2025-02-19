### Características principales:
1. **Configuración básica**: Se utiliza un amplificador operacional con una resistencia de entrada conectada a la señal de entrada y una resistencia de retroalimentación (feedback) conectada entre la salida y la entrada inversora del op-amp.
2. **Ganancia**: La ganancia de un amplificador inversor se calcula como la relación de las resistencias en el circuito:
   
   \[
   \text{Ganancia} = - \frac{R_f}{R_{in}}
   \]

   Donde:
   - \( R_f \) es la resistencia de retroalimentación (entre la salida y la entrada inversora).
   - \( R_{in} \) es la resistencia conectada entre la señal de entrada y la entrada inversora del op-amp.

3. **Inversión de señal**: El signo negativo en la fórmula indica que la señal de salida estará invertida con respecto a la de entrada. Es decir, si la entrada es \( V_{in} \), la salida será \( V_{out} = - (V_{in} \times \text{Ganancia}) \).

### Ejemplo de uso:
- Si el amplificador tiene una ganancia de -10 y la señal de entrada es 1 V, la salida será -10 V.
  
### Aplicaciones:
Los amplificadores inversores se utilizan en aplicaciones como:
- **Filtros activos**: Para la creación de filtros con una cierta frecuencia de corte.
- **Inversión de fase**: En sistemas donde se necesita invertir la fase de una señal sin alterar su amplitud demasiado.
- **Procesamiento de señales**: Como parte de sistemas de procesamiento de audio, vídeo o señales de comunicación.

Es un circuito simple pero muy útil para diversas tareas dentro de la electrónica analógica.
