# Caja y refrigeración

**Realizado por:** Sheila Muñoz Matías y Loli Joya

## 1. Qué es y qué función cumple el sistema

El ordenador genera calor, principalmente por la CPU, la GPU y otros componentes. El sistema de refrigeración sirve para evitar que las temperaturas superen los límites de funcionamiento.

Sus componentes principales son:

- **Caja (chasis):** protege los componentes y permite la entrada de aire frío y la salida del aire caliente.
- **Disipador:** bloque metálico con aletas que recoge el calor del procesador y lo reparte.
- **Pasta térmica:** se coloca entre la CPU y el disipador para mejorar la transferencia de calor. Se aplica una capa fina.
- **Ventiladores:** mueven el aire por el interior de la caja y ayudan a expulsar el calor.
- **Refrigeración líquida AIO:** utiliza una placa fría, una bomba, tubos y un radiador para transportar y eliminar el calor.

Si la refrigeración falla, el procesador puede calentarse demasiado, reducir su rendimiento y llegar a apagar el ordenador.

![Disipador de aire para procesador](img/disipador.jpg)

## 2. Cómo funciona

El calor pasa del chip al aire de la habitación mediante cuatro pasos:

1. **Conducción:** el chip transmite el calor al metal del disipador o a la placa fría mediante la pasta térmica.
2. **Transporte:** en los disipadores de aire, los heatpipes llevan el calor hasta las aletas. En una AIO, la bomba mueve el líquido hasta el radiador.
3. **Convección forzada:** los ventiladores mueven el aire por las aletas o el radiador y retiran el calor.
4. **Expulsión:** el aire caliente sale de la caja para evitar que aumente la temperatura del resto de componentes.

### Flujo de aire de la caja

Lo habitual es que el aire fresco entre por el frontal y la parte inferior, mientras que el aire caliente salga por la parte trasera y superior.

- **Presión positiva:** entra más aire del que sale y ayuda a reducir el polvo.
- **Presión negativa:** sale más aire del que entra.

![Esquema del flujo de aire dentro de una caja de ordenador](img/aire.jpeg)

## 3. Características y unidades

Para elegir una refrigeración hay que tener en cuenta la potencia que puede retirar, la temperatura que alcanza el procesador y el ruido que produce.

- **TDP (W):** potencia térmica de referencia indicada por el fabricante de la CPU.
- **PBT y MTP (W):** indican la potencia base sostenida y la potencia máxima en turbo.
- **PPT (W):** límite real de potencia del procesador. Se puede consultar en la BIOS o en Ryzen Master.
- **Temperatura de la CPU (ºC):** indica el estado térmico del procesador y se mide mediante sensores internos.
- **Resistencia térmica (ºC/W):** indica cuántos grados sube el chip por cada vatio disipado. Cuanto menor sea, mejor.
- **Velocidad de giro (RPM):** indica las vueltas por minuto del ventilador.
- **Ciclo de trabajo PWM (%):** controla la velocidad del ventilador mediante una señal regulada.
- **Dimensiones (mm):** indican el tamaño del disipador o radiador y permiten comprobar si cabe en la caja.

## 4. Tipos de refrigeración

### Disipador de aire

**Funcionamiento:** utiliza una base metálica, heatpipes, aletas y un ventilador para evacuar el calor.

**Ventajas:** no tiene bomba ni riesgo de fugas, es duradero y tiene un precio contenido.

**Inconvenientes:** puede ser grande y pesado, y chocar con la memoria RAM o la tapa de la caja.

### Refrigeración líquida AIO (120 a 420 mm)

**Funcionamiento:** utiliza una placa fría, una bomba y un radiador. El líquido transporta el calor desde el procesador hasta el radiador.

**Ventajas:** funciona bien con procesadores de mucha potencia y deja más espacio alrededor del socket.

**Inconvenientes:** es más cara que la refrigeración por aire, necesita espacio para el radiador y la bomba puede fallar.

![Refrigeración líquida AIO](img/liquida.jpeg)

### Refrigeración pasiva

**Funcionamiento:** utiliza únicamente las aletas del disipador y el flujo de aire de la caja.

**Ventajas:** es silenciosa porque no tiene partes móviles.

**Inconvenientes:** solo es eficaz con procesadores de muy bajo consumo.

### Circuito líquido personalizado

**Funcionamiento:** utiliza una bomba, un depósito y radiadores montados de forma personalizada.

**Ventajas:** ofrece una gran capacidad de refrigeración y permite una estética personalizada.

**Inconvenientes:** tiene un coste elevado, necesita mantenimiento y existe riesgo de fugas.

## 5. Modelo comercial real: Arctic Liquid Freezer III 360 A-RGB

![Arctic Liquid Freezer III 360 A-RGB](img/arctic.jpeg)

**Fabricante:** Arctic  
**Modelo:** Liquid Freezer III 360 A-RGB.

**Compatibilidad:**
- AMD: AM5 y AM4.
- Intel: LGA1851 y LGA1700.

**Ventiladores:**
- Modelo: ARCTIC P14 PWM A-RGB.
- Cantidad: 3.
- Velocidad: 200–2000 RPM.
- Dimensiones: 120 x 120 x 25 mm.
- Caudal de aire: 48,82 CFM.
- Presión estática: 1,85 mmH2O.

**Bomba:**
- Velocidad: 800–2800 RPM.
- Regulable mediante PWM.
- Consumo máximo: 4,2 W.

**Radiador:**
- Dimensiones: 398 x 120 x 38 mm.

Más información: https://www.guru3d.com/review/arctic-liquid-freezer-iii-360-argb-cooler-review/page-2/

## 6. Averías típicas y errores al elegir o instalar

La mayoría de los problemas se deben a un mal contacto, conexiones incorrectas o un flujo de aire insuficiente.

| Problema | Causa probable | Solución |
|---|---|---|
| La CPU llega a 90 ºC rápidamente | Mal contacto, soporte mal apretado o pasta térmica incorrecta | Revisar el montaje y aplicar correctamente la pasta |
| Temperatura alta y estable | Poco flujo de aire, polvo o radiador atascado | Limpiar filtros y comprobar la entrada y salida de aire |
| Temperaturas peores con los años | Pasta térmica reseca | Retirar la pasta antigua y aplicar nueva |
| Ventilador ruidoso o parado | Polvo, cable rozando o rodamiento desgastado | Limpiar, revisar el cable o sustituirlo |
| Ventilador no sigue la curva de la BIOS | Modo PWM/DC incorrecto | Configurar el modo adecuado |
| Error de ventilador al arrancar | Conexión incorrecta o RPM insuficientes | Revisar las conexiones |
| Gorgoteo en una AIO | Aire acumulado en la bomba | Colocar el radiador más alto que la bomba |
| AIO pierde rendimiento | Desgaste de la bomba o evaporación del líquido | Vigilar las RPM y las temperaturas |

### Errores al elegir

- **Subestimar el calor:** fijarse únicamente en el TDP y no en la potencia real.
- **Problemas de espacio:** no medir si el disipador o radiador cabe en la caja.
- **Incompatibilidad:** no comprobar el socket o los componentes cercanos.
- **Metal líquido:** utilizarlo sobre aluminio o cerca de circuitos expuestos.
- **Ventilador incorrecto:** elegir uno por su caudal y no por su presión estática para un radiador.

### Errores al instalar

- **Presión desigual:** apretar el soporte de golpe en lugar de hacerlo de forma gradual y cruzada.
- **Exceso de pasta térmica:** aplicar demasiada cantidad.
- **Efecto horno:** configurar los ventiladores sin dejar una salida de aire adecuada.
- **Obstrucción:** dejar cables que dificulten el flujo de aire o rocen las aspas.
- **Bomba mal conectada:** utilizar un conector que reduzca demasiado sus RPM.

## 7. Fuentes y uso de IA

### Fuentes

- https://www.profesionalreview.com/2024/08/25/ventiladores-3-pines-vs-4-pines/
- https://www.geeknetic.es/Guia/2717/Ventajas-de-los-Ventiladores-con-control-PWM-de-4-pines.html
- https://www.profesionalreview.com/2017/10/29/que-es-presion-positiva-y-negativa-de-aire-pc/amp/
- https://www.corsair.com/lm/es/explorer/diy-builder/blogs/positive-pressure-vs-negative-pressure-which-is-best-for-a-gaming-pc/
- https://www.guru3d.com/review/arctic-liquid-freezer-iii-360-argb-cooler-review/page-2/
- https://cdn.noctua.at/media/Noctua_PWM_specifications_white_paper.pdf
### Uso de IA

Hemos utilizado Claude como ayuda para buscar fuentes, proponer la estructura de los apartados y redactar un primer borrador. Después hemos revisado y corregido el contenido, eliminando partes innecesarias o demasiado complicadas.

## 8. Preguntas tipo test

### 1. ¿Qué función cumple la pasta térmica?

- A) Enfriar la CPU con líquidos.
- B) Rellenar el hueco de aire entre CPU y disipador.
- C) Eliminar los ventiladores.
- D) Proteger la caja del polvo.

- Respuesta correcta: B.
- Entre la CPU y el disipador quedan huecos microscópicos llenos de aire, y el aire conduce muy mal el calor. La pasta los rellena y mejora la transferencia. No enfría por sí sola (A), no sustituye a los ventiladores (C) y no tiene nada que ver con el polvo (D).

### 2. ¿Qué indica el PPT?

- A) Las RPM de la bomba.
- B) La temperatura de la CPU.
- C) El límite real de potencia del procesador.
- D) La resistencia térmica.

- Respuesta correcta: C.
- El PPT (Package Power Tracking) es el límite real de potencia del procesador, en W, y se ve en la BIOS o en Ryzen Master, el programa de AMD. La A habla de RPM, que son de los ventiladores y la bomba. La B es la temperatura, que se mide en °C. La D es la resistencia térmica (°C/W).

### 3. ¿Qué inconveniente tiene un disipador de aire?

- A) Tiene riesgo de fugas.
- B) Necesita una bomba.
- C) Es grande y puede chocar con la RAM.
- D) Requiere mantenimiento constante.

- Respuesta correcta: C.
- Su desventaja es el tamaño y el peso, que pueden chocar con la RAM o con la tapa de la caja. La A es un problema de las AIO y de los circuitos a medida, porque el aire no lleva líquido. La B es falsa: el disipador de aire no lleva bomba, solo ventilador. La D es falsa porque no necesita mantenimiento constante.

### 4. ¿Qué parámetro es importante en un ventilador de radiador?

- A) La presión estática.
- B) El color.
- C) El tamaño de la caja.
- D) La temperatura ambiente.

- Respuesta correcta: A.
- Un radiador tiene muchas aletas muy juntas que frenan el aire, y para empujarlo a través hace falta presión estática. El caudal importa más en espacios abiertos, y elegir por caudal es justo el error que se señala en "errores al elegir". La B, la C y la D no influyen en el rendimiento del radiador.


### 5. ¿Qué realiza el transporte en una AIO?

- A) La bomba mueve el líquido hasta el radiador.
- B) Los ventiladores expulsan el aire de la habitación.
- C) El chip transmite el calor al disipador.
- D) La caja elimina el polvo.

- Respuesta correcta: A. 
- El paso 2 del funcionamiento es el transporte, y en una AIO lo hace la bomba moviendo el líquido hasta el radiador. La B es la expulsión (paso 4). La C es la conducción (paso 1). La D no es un paso del funcionamiento.

### 6. Si la CPU llega a 90 ºC en segundos, ¿cuál puede ser la causa?

- A) Presión positiva.
- B) Mal contacto entre CPU y disipador.
- C) Polvo en los filtros.
- D) Evaporación lenta del líquido.

- Respuesta correcta: B.
- Una subida tan rápida indica que el calor no pasa del chip al disipador, es decir, falla la conducción. La A no es una causa: la presión positiva incluso reduce el polvo. La C (poco flujo de aire) hace que la temperatura suba despacio y se estabilice alta. La D ocurre con los años, no en segundos.

### 7. ¿Qué velocidad alcanza la bomba del Arctic Liquid Freezer III 360?

- A) 200–2000 RPM.
- B) 400–2500 RPM.
- C) 800–2800 RPM.
- D) 3000 RPM fijas.

- Respuesta correcta: C.
- Es el dato de la ficha técnica. La A corresponde a los ventiladores P12 (200–2000 RPM) y la B al ventilador de VRM (400–2500 RPM). La D es falsa porque la bomba es regulable por PWM.


### 8. ¿Qué puede ocurrir al conectar 12 V al pin de control de un ventilador PWM?

- A) Aumenta el caudal de forma segura.
- B) Se estropea inmediatamente.
- C) Reduce el ruido.
- D) Mejora la refrigeración.

- Respuesta correcta: B.
- El pin de control del PWM solo admite una señal de baja tensión. Meterle 12 V o 24 V daña el ventilador al instante, como advierte Noctua en su documento técnico. Las otras opciones son falsas: no aumenta el caudal, ni reduce el ruido, ni mejora la refrigeración.

