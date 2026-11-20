# SI · UT2 — Ficha de taller: montaje y revisión de un ordenador

## 1. Orden de trabajo

**Fecha:** ____________________  **Puesto:** ____________________  **Equipo / etiqueta:** ____________________

**Integrantes del grupo (2 o 3):**

1. Nombre y apellidos: ______________________________________________
2. Nombre y apellidos: ______________________________________________
3. Nombre y apellidos (si procede): __________________________________

> **Equipo A:** ordenador de prácticas utilizado para el montaje o la revisión. Puede estar averiado; no se exige que arranque.
>
> **Equipo B:** vuestro propio ordenador funcional. Se utiliza a partir del apartado 9 para analizar el arranque y el hardware desde Linux.

## 2. Recepción e inspección visual · Equipo A

**Trabajo previsto:**

- [ ] Desmontaje y montaje
- [ ] Revisión / diagnóstico
- [ ] Otro: ___________________________________

**Estado al recibirlo:**

- [ ] Completo
- [ ] Faltan piezas
- [ ] Sucio
- [ ] Daños visibles

**Síntomas conocidos, piezas ausentes o daños observados:**

________________________________________________________________________

________________________________________________________________________

## 3. Seguridad y preparación · Equipo A

- [ ] Equipo desconectado de la corriente y de los periféricos.
- [ ] Botón de encendido pulsado tras desconectar.
- [ ] Superficie despejada y piezas organizadas.
- [ ] Estado inicial y conexiones fotografiados.

**Herramientas utilizadas:** _______________________________________________

**No abráis la fuente ni forcéis piezas.** Ante daños o baterías, avisad al profesor.

## 4. Componentes identificados · Equipo A

Anotad lo que podáis verificar. Si no se distingue, escribid «no identificado».

| Componente | Marca / modelo | Dato observado |
|---|---|---|
| Placa base | | |
| Procesador | | |
| RAM | | |
| Almacenamiento | | |
| Fuente | | |
| Disipador / ventilador | | |
| Tarjetas / otros | | |

## 5. Conexiones y observaciones · Equipo A

Identificad y marcad las conexiones presentes y comprobadas:

- [ ] Alimentación de la placa
- [ ] Alimentación de la CPU
- [ ] Ventilador de la CPU
- [ ] Datos de almacenamiento
- [ ] Alimentación del disco
- [ ] Panel frontal

**¿Hay algún cable suelto, conector dañado o conexión que no sepáis identificar?**

________________________________________________________________________

________________________________________________________________________

**Fotografías de referencia (nombre de archivo o ubicación):**

________________________________________________________________________

No retiréis la CPU ni el disipador sin indicación del profesor. Si se retira el disipador, consultad sobre limpieza y pasta térmica antes de volver a instalarlo.

## 6. Registro del trabajo · Equipo A

Registrad únicamente lo que hayáis hecho; marcad **N/P** si no procede.

| Operación | Hecho | N/P | Foto / observaciones |
|---|:---:|:---:|---|
| Apertura y fotos iniciales | ☐ | ☐ | |
| Desconexión y organización de cables | ☐ | ☐ | |
| Desmontaje / montaje de memoria | ☐ | ☐ | |
| Revisión / montaje de almacenamiento | ☐ | ☐ | |
| CPU y disipador, si se autoriza | ☐ | ☐ | |
| Tarjetas de expansión | ☐ | ☐ | |
| Reconexión y orden de cables | ☐ | ☐ | |
| Cierre y limpieza del puesto | ☐ | ☐ | |

## 7. Incidencia o reparación · Equipo A

**Problema encontrado / hipótesis** (si no hay, indicadlo):

________________________________________________________________________

________________________________________________________________________

**Acción realizada y resultado observado:**

________________________________________________________________________

________________________________________________________________________

________________________________________________________________________

## 8. Comprobación final · Equipo A

- [ ] Piezas sujetas.
- [ ] RAM encajada.
- [ ] Cables revisados.
- [ ] Sin tornillos sueltos.
- [ ] Ventilador de CPU conectado.
- [ ] Puesto recogido.

**¿Encendido autorizado?** ☐ Sí  ☐ No

**Resultado / motivo:** ___________________________________________________

________________________________________________________________________

Una observación no demuestra por sí sola la causa de una avería.

---

## 9. Identificación y arranque · Equipo B

Utilizad vuestro propio ordenador funcional para los siguientes apartados.

**Equipo:** ☐ Portátil  ☐ Sobremesa  ☐ Otro: ___________________________

**Linux:** ☐ Instalado directamente  ☐ Máquina virtual

**Sistema operativo y versión:** __________________________________________

**Si es virtual: sistema anfitrión y programa de virtualización:** ______________

**¿Arranca con normalidad? ¿Qué observáis desde el encendido hasta el inicio?**

________________________________________________________________________

________________________________________________________________________

**¿Qué es el POST y en qué se diferencia de la UEFI y del sistema operativo?**

________________________________________________________________________

________________________________________________________________________

**¿Habéis accedido a la UEFI o consultado información de ella? ¿Qué dato habéis visto?**

________________________________________________________________________

________________________________________________________________________

No cambiéis ajustes de UEFI sin indicación del profesor. Si no podéis acceder, indicadlo.

## 10. Linux: procesador · `lscpu`

Ejecutad `lscpu`. Adjuntad la salida revisada o indicad si el comando falla.

**Modelo / CPU presentada a Linux:** _______________________________________

**Arquitectura:** ____________________  **CPU lógicas visibles:** ______________

**¿Qué diferencia hay entre núcleo e hilo? ¿Qué podéis concluir de la salida?**

________________________________________________________________________

________________________________________________________________________

## 11. Linux: memoria · `free -h`

Adjuntad las salidas de los comandos. Si alguno falla o no está disponible, anotadlo. Antes de entregarlas, ocultad usuarios, nombres de equipo, números de serie y UUID. En una máquina virtual pueden mostrarse recursos virtuales, no el hardware físico completo.

**Memoria total:** ____________________  **Memoria disponible:** ______________

**¿Qué significa «disponible» y por qué puede diferir de «libre»?**

________________________________________________________________________

________________________________________________________________________

## 12. Linux: almacenamiento · `lsblk`

**Disco identificado:** ___________________________________________________

**Partición y punto de montaje, si aparecen:** ________________________________

**Explicad la diferencia entre disco, partición y punto de montaje:**

________________________________________________________________________

________________________________________________________________________

## 13. Linux: dispositivos · `lspci` y `lsusb`

**Dispositivo 1 y función:** ________________________________________________

**Dispositivo 2 y función:** ________________________________________________

**¿Por qué podría no aparecer un componente físico o mostrarse de otra forma en una máquina virtual?**

________________________________________________________________________

________________________________________________________________________

## 14. Duda técnica y uso crítico de IA

Podéis usar una IA de Internet. No compartáis datos personales ni información privada del centro. Sin acceso a IA, resolved la duda con una fuente técnica.

**Herramienta utilizada y fecha:** __________________________________________

**Pregunta planteada:**

________________________________________________________________________

**Respuesta resumida y afirmación concreta que decidisteis comprobar:**

________________________________________________________________________

________________________________________________________________________

**Fuente técnica o prueba utilizada y resultado:** confirmada / corregida / no verificada.

________________________________________________________________________

________________________________________________________________________

## 15. Valoración y entrega

**¿Qué paso fue más difícil y cómo lo resolvisteis?**

________________________________________________________________________

________________________________________________________________________

**¿Qué relación existe entre el montaje y la información de Linux? Recordad que son equipos distintos.**

________________________________________________________________________

________________________________________________________________________

**¿Qué haríais de otra manera en un próximo montaje?**

________________________________________________________________________

________________________________________________________________________

Antes de entregar:

- [ ] Ficha completa.
- [ ] Fotos identificadas.
- [ ] Salidas de Linux revisadas.
