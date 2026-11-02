# Cambios para integrar el cabezal de llenado al informe (Ra3v8 → Ra3v9)

## 1. Resumen

Estructura final (solo lo nuevo, movido o renumerado):

- **Sección 3** pasa a llamarse "Cadencia de llenado y boquilla".
- **3.3 Boquilla de llenado** (reemplaza a "3.3 Verificación geométrica de la boquilla de llenado"): concepto, envases, boquilla, lanza y manguera de 1¼".
- **6.1** pasa a tener un único cálculo de pérdida de carga, tramo por tramo, con la boquilla de 3.3 y la manguera de 1¼". Cambian la Tabla de fuerzas (ex Tabla 6) y la columna de fuerza mínima de la selección del actuador (ex Tabla 7).
- **8.1** agrega el largo máximo de la manguera (1,15 m).
- **Nueva 19 Cabezal de llenado**, con las subsecciones 19.1 a 19.9.
- Renumeración: 19 Verificación de la bancada → **20**; 20 Fuentes → **21**; 21 Pendientes → **22**.
- **14.5** se rehace con la altura real de la bancada (1.090 mm) en lugar de la estimación de 1.000 mm; el diámetro mínimo de la tolva pasa a 399,6 mm y se mantiene D = 400 mm.
- Ajustes en 1, 2 (Tabla 1), 3.2, 8.1, 13.3, 15.3, 16.11, 17.2 a 17.7, 18.1, 20, 21 y 22. Fuentes nuevas: [90] a [104].

---

## 2. Cambios, en el orden del documento final

### Convenciones

- Las anclas («…») son texto literal y único de **Ra3v8.md**. Se verificó con un script que cada una aparece una sola vez. Ninguna contiene símbolos que el .md muestre como "?".
- En los textos finales, los símbolos se escriben como van en Word (Δ, μ, π, ≈, ≤, ≥, ⁴, etc.). Las fórmulas van en cursiva, como en el informe.
- **Los números de figura y tabla de este archivo ya son los finales.** En los títulos (que Word numera solo) se escriben como `**Figura [auto: 60].**`: se inserta el título con numeración automática y el número entre corchetes es solo para controlar. La tabla de correspondencias de la Sección 3 de este archivo se aplica **únicamente al texto original que no se reemplaza**. No se aplica a los textos de este archivo.
- `[IMAGEN: …]` indica qué imagen de **seccion17.md** se pega en ese lugar. La imagen se identifica por el título que la sigue en ese archivo.
- **Fuentes.** Las citas de los textos de este archivo ya llevan la numeración final. Se elimina el salto de la lista (no existen [52] a [54]): las fuentes existentes [55] a [92] pasan a ser [52] a [89] (cambio C56), y las de seccion17.md, [86] a [100], pasan a ser [90] a [104], en el mismo orden. La [101] de seccion17.md (volante Halder) se elimina, porque el husillo usa el mismo volante Elesa del ajuste de carrera ([87]). Las fuentes [9], [13] y [18] no cambian.
- **seccion17.md no se pega como bloque.** Todo su contenido entra a través de los cambios de este archivo, y de ese archivo solo se toman las imágenes.

---

### PORTADA E ÍNDICE

**C1**
- **Ubicación:** Portada, subtítulo. Ancla: «el mecanismo de ajuste de carrera, la caja de soporte y la bancada estructural»
- **Acción:** REEMPLAZAR
- **Texto final:** el mecanismo de ajuste de carrera, la caja de soporte, el cabezal de llenado y la bancada estructural

**C2**
- **Ubicación:** Índice ("Contenido").
- **Acción:** Actualizar el campo de tabla de contenido en Word (clic derecho → Actualizar campo → toda la tabla) después de aplicar todos los cambios. No se edita a mano.

### SECCIÓN 1

**C3**
- **Ubicación:** Sección 1. Ancla: «el soporte de la tolva y la verificación estructural de la bancada»
- **Acción:** REEMPLAZAR
- **Texto final:** el soporte de la tolva, el cabezal de llenado y la verificación estructural de la bancada

**C4**
- **Ubicación:** Sección 1. Ancla: «Los puntos pendientes se consolidan en la Sección 21.»
- **Acción:** REEMPLAZAR
- **Texto final:** Los puntos pendientes se consolidan en la Sección 22.

### SECCIÓN 2 (Tabla 1)

**C5**
- **Ubicación:** Tabla 1, fila que empieza con «Diámetros de la boquilla de llenado»
- **Acción:** ELIMINAR la fila completa.

**C6**
- **Ubicación:** Tabla 1, fila que empieza con «Manguera de conexión entre cilindro dosificador y boquilla»
- **Acción:** REEMPLAZAR la fila completa (3 celdas).
- **Texto final:**

| Mangueras del circuito | Ø int. 25,4 mm (1”) entre la tolva y la válvula de tres vías; Ø int. 31,75 mm (1¼”) entre la válvula y la boquilla | 1”: definición de diseño del proyecto. 1¼”: manguera que usa la PyME en su máquina actual (Sección 3.3). |

**C7**
- **Ubicación:** Tabla 1, fila que empieza con «Longitud de la manguera de conexión»
- **Acción:** REEMPLAZAR la fila completa.
- **Texto final:**

| Longitud de la manguera entre la válvula y la boquilla | 1 m | Valor de trabajo para poder avanzar con números concretos. El largo máximo admisible se calcula en la Sección 8.1; la distancia real depende del *layout* mecánico final. |

**C8**
- **Ubicación:** Tabla 1, inmediatamente **después** de la fila que empieza con «Diámetro interior de la boca del envase»
- **Acción:** AGREGAR fila.
- **Texto final:**

| Cubicaje de los envases | 257 ml (envase de 250 ml) y 520 ml (envase de 500 ml) | Ficha del proveedor [completar: referencia de la ficha del proveedor de los envases]. |

### SECCIÓN 3

**C9**
- **Ubicación:** Título de la Sección 3. Ancla: «3. Cadencia de llenado requerida» (el título de la sección, no la línea del índice).
- **Acción:** REEMPLAZAR
- **Texto final:** 3. Cadencia de llenado y boquilla

**C10**
- **Ubicación:** Sección 3.2. Desde «El tiempo restante queda como margen para el avance de la cinta transportadora» hasta «que corresponden a otra etapa de la línea (Figura 2).»
- **Acción:** REEMPLAZAR
- **Texto final:** El tiempo restante queda libre para los movimientos del cabezal de llenado, el avance de la cinta transportadora y el posicionamiento del envase bajo la boquilla, que corresponden a otra etapa de la línea (Figura 2). La secuencia completa del cabezal se desarrolla en la Sección 19.8.

  (La Figura 2 no se modifica: muestra inyección, aspiración y tiempo libre.)

**C11**
- **Ubicación:** Sección 3.3 completa: desde el título «3.3 Verificación geométrica de la boquilla de llenado» (el título de la sección, no la línea del índice) hasta el final del párrafo que termina en «la verificación vale para los dos.» (incluidas las dos fórmulas intermedias). Termina justo antes del título "4. Selección del tipo de accionamiento neumático".
- **Acción:** REEMPLAZAR todo el bloque.
- **Texto final:**

> ## **3.3 Boquilla de llenado**
>
> Al terminar cada inyección, la boquilla debe cortar el producto en la punta para que no gotee entre ciclos. Para eso se adopta una boquilla con cierre positivo: un vástago que corre por dentro del conducto cierra la salida desde adentro, junto a la punta, y al cerrar aspira la gota que queda en ella. El concepto se tomó de la patente US5137187 [90]. La boquilla termina en una lanza que entra en el envase, para acortar la caída del producto, y que sube durante el llenado, para que el envase no rebalse. Para eso, la boquilla va montada en un carro que sube y baja en cada ciclo, y su altura se regula para cada formato; el conjunto, el cabezal de llenado, se desarrolla en la Sección 19.
>
> ### **Envases**
>
> Los dos envases son de PET. Las Figuras 3 y 4 muestran sus medidas según la ficha del proveedor [completar: referencia de la ficha del proveedor de los envases].
>
> [IMAGEN: la que precede a «**Figura 43.** Envase de 250 ml» en seccion17.md]
>
> **Figura [auto: 3].** Envase de 250 ml (cotas en mm según la ficha del proveedor; forma del hombro, del cuello y del domo esquemática)
>
> [IMAGEN: la que precede a «**Figura 44.** Envase de 500 ml» en seccion17.md]
>
> **Figura [auto: 4].** Envase de 500 ml (cotas en mm según la ficha del proveedor; forma del hombro, del cuello y del domo esquemática)
>
> ### **Boquilla**
>
> La boquilla se arma sobre una T roscada de 1”, el diámetro de la manguera de succión (Sección 2, Tabla 1), con piezas torneadas que se enroscan en ella. Las Figuras 5 y 6 la muestran abierta, cerrada y en despiece, y la Tabla 4 reúne sus componentes con sus medidas y materiales.
>
> [IMAGEN: la que precede a «**Figura 47.** Boquilla con cierre positivo» en seccion17.md]
>
> **Figura [auto: 5].** Boquilla con cierre positivo: (a) abierta durante la inyección; (b) cerrada (cotas en mm, esquema sin escala)
>
> [IMAGEN: la que precede a «**Figura 48.** Despiece de la boquilla» en seccion17.md]
>
> **Figura [auto: 6].** Despiece de la boquilla; los números corresponden a las piezas del texto (esquema sin escala)
>
> Las piezas, con su número en el despiece, son:
>
> * **(1) Cuerpo:** T roscada de 1”. La rama lateral recibe la manguera.
> * **(2) Pieza de punta:** se enrosca abajo de la T. Tiene el asiento del obturador y la cámara donde queda alojada la cabeza cuando abre.
> * **(3) Pieza de lanza:** se enrosca en la pieza de punta y lleva la lanza soldada.
> * **(4) Obturador:** cabeza con *o-ring*, unida a un vástago. Cierra subiendo contra el asiento.
> * **(5) Tapón-guía:** cierra la T por arriba y guía el vástago.
> * **(6) Linterna:** une el actuador con la boquilla y deja la zona del producto separada del actuador.
> * **(7) Actuador:** cilindro neumático que abre y cierra el obturador; se selecciona en la Sección 19.2.
>
> Abierta, la cabeza del obturador queda dentro de una cámara de Ø32 mm, fuera del paso del producto. Así, por la lanza no pasa ningún vástago, que triplicaría su pérdida de carga.
>
> **Tabla [auto: 4].** Componentes de la boquilla
>
> | **Componente** | **Especificación** | **Material** | **Cant.** |
> | --- | --- | --- | --- |
> | T roscada | 1” clase 150 según ISO 4144, Rp 1 en las tres bocas, 38 mm del eje a cada cara [91] | CF8 (304) o CF8M (316) [92] | 1 |
> | *O-rings* de cara | En la cara de los hexágonos de 41 mm y en el resalto de la pieza de lanza, tamaño a definir [18] | FKM | 3 |
> | Pieza de punta | Rosca G 1 × 18,5 mm, hexágono de 41 × 11 mm, asiento Ø16 × 3 mm, cámara Ø32 × 66 mm, rosca exterior M40 × 1,5 × 12 mm | AISI 304 | 1 |
> | Pieza de lanza | Hexágono de 46 × 30 mm, rosca interior M40 × 1,5 × 12 mm, reducción de Ø32 a Ø14,48 mm en 15 mm | AISI 304 | 1 |
> | Lanza | Tubo de 15,88 × 0,70 mm (5/8”), 113 mm de largo libre, soldado a la pieza de lanza | AISI 304 | 1 |
> | Tapón-guía | Hexágono de 41 × 11 mm, rosca G 1 × 18,5 mm, cola de Ø26 × 6,5 mm, agujero de Ø4 mm | AISI 304 | 1 |
> | Vástago del obturador | Ø4 mm, rosca M4 en ambos extremos | AISI 304 | 1 |
> | Obturador | Cabeza de Ø20 × 8 mm, cierra subiendo contra el asiento | AISI 304 | 1 |
> | *O-ring* del obturador | En la cara superior de la cabeza, tamaño a definir [18] | FKM | 1 |
> | *O-rings* del vástago | Para vástago de Ø4 mm, tamaño a definir [18] | FKM | 2 |
> | Linterna | Tubo de Ø30 × 2 × 65 mm con discos de Ø40 × 4 mm, soldada al tapón-guía | AISI 304 | 1 |
> | Manguito de unión | Rosca interior M4 en ambos extremos, con dos contratuercas M4 | AISI 304 | 1 + 2 |
>
> Las uniones de la rama lateral con la manguera se incluyen en la Tabla 22 (Sección 15.3).
>
> ### **Lanza**
>
> La lanza es un tubo de AISI 304 de 15,88 × 0,70 mm (5/8”), de 14,48 mm de diámetro interior, que entra por la boca de 19 mm del envase (Sección 2, Figura 7). Deja 1,56 mm de holgura por lado, por donde sale el aire desplazado. Como el diámetro de la boca es el mismo en los dos envases, la holgura también lo es.
>
> [IMAGEN: la que precede a «**Figura 49.** Lanza dentro del envase» en seccion17.md]
>
> **Figura [auto: 7].** Lanza dentro del envase en su posición baja y posición de la punta al final de la subida lenta (cotas en mm, esquema sin escala)
>
> Como la lanza es la misma para los dos formatos, se dimensiona para el envase de 250 ml. Para el de 500 ml, el cabezal sube la diferencia de altura entre los dos envases, 177 − 128 = 49 mm (Figuras 3 y 4). Con la lanza en su posición baja, la punta queda h = 20 mm sobre el fondo y la pieza de lanza, 5 mm sobre la boca, de donde el largo libre es 128 − 20 + 5 = 113 mm. En el envase de 500 ml, con el cabezal 49 mm más arriba, la punta queda 69 mm sobre el fondo y la pieza de lanza vuelve a quedar 5 mm sobre la boca. Al comenzar el llenado, el producto cae así 20 mm en el envase de 250 ml y 69 mm en el de 500 ml.
>
> La altura h se mide desde el punto más alto del domo del fondo. Como la altura del domo no se midió, en la puesta en marcha la punta se ajusta subiendo el cabezal esa altura con la regulación de altura (Sección 19.6). La lanza no toca el envase, que solo recibe el producto.
>
> ### **Manguera**
>
> Entre la válvula de tres vías y la boquilla se adopta una manguera de PVC cristal reforzada con malla de poliéster, de 1¼” (31,75 mm de diámetro interior). Es la que usa la PyME en su máquina actual (Figura 8), donde se emplea con los tres productos (perfume, alcohol en gel y jabón) sin inconvenientes. Tiene el interior liso, lo que facilita la limpieza. En la boquilla, la manguera se une a la rama lateral de la T con un adaptador Tri-Clamp × espiga y un adaptador R 1 × Tri-Clamp (Tabla 22, Sección 15.3).
>
> [IMAGEN: la que precede a «**Figura 50.** Manguera de PVC cristal» en seccion17.md]
>
> **Figura [auto: 8].** Manguera de PVC cristal reforzada con malla de poliéster, sobre espiga Tri-Clamp, en la máquina actual de la PyME

### SECCIÓN 6.1

**C12**
- **Ubicación:** Sección 6.1, párrafo del número de Reynolds. Reemplazar desde «En la manguera (d = 25,4 mm) resulta Re» hasta «y la ecuación de Hagen-Poiseuille es aplicable.» (fin del párrafo).
- **Acción:** REEMPLAZAR
- **Texto final:** En la lanza de la boquilla (d = 14,48 mm, Sección 3.3), donde se da el mayor valor, resulta Re ≈ 1,0, y en la manguera de 1¼” (d = 31,75 mm), Re ≈ 0,44. Los dos están varios órdenes de magnitud por debajo del límite de transición a régimen turbulento (Re ≈ 2.300), por lo que el flujo es laminar con amplio margen y la ecuación de Hagen-Poiseuille es aplicable.

**C13**
- **Ubicación:** Sección 6.1. Reemplazar desde el párrafo que empieza con «Se calcula por separado la caída de presión en la boquilla final» hasta la fórmula de ΔPtotal que termina en «0,0341 MPa» (inclusive). El bloque incluye las fórmulas de Q, ΔPboquilla, ΔPmanguera y ΔPtotal. El párrafo siguiente, «Este valor no incluye las pérdidas de la válvula de bifurcación…», se conserva.
- **Acción:** REEMPLAZAR
- **Texto final:**

> El caudal es el mismo para ambos envases, por lo que las fuerzas calculadas son válidas para los dos:
>
> *Q = Vinyección / tinyección = 500.000 mm³ / 10 s = 50.000 mm³/s*
>
> La pérdida se calcula por separado en la boquilla de la Sección 3.3, tramo por tramo (Figura 10), y en la manguera de 1¼” entre la válvula y la boquilla (d = 31,75 mm, con L = 1 m, Sección 2). Los tramos circulares se resuelven con Hagen-Poiseuille. Los anillos entre el vástago o la cabeza abierta y el conducto se resuelven con la expresión del flujo laminar entre cilindros concéntricos [95]:
>
> *ΔP = 8 × μ × L × Q / (π × R⁴ × [(1 − k⁴) − (1 − k²)² / ln(1/k)])*
>
> donde R es el radio del conducto y k = di / D la relación entre el diámetro del cilindro interior y el del conducto. La reducción, cuyo diámetro varía linealmente de d1 = 32 mm a d2 = 14,48 mm en L = 15 mm, se resuelve integrando Hagen-Poiseuille:
>
> *ΔPcono = (128 × μ × Q / π) × L / [3 × (d1 − d2)] × (1/d2³ − 1/d1³)*
>
> [IMAGEN: la que precede a «**Figura 51.** Pérdida de carga en la boquilla» en seccion17.md, editada según la Sección 5 de este archivo]
>
> **Figura [auto: 10].** Pérdida de carga en la boquilla: (a) tramos de cálculo con la boquilla abierta; (b) y (c) modelos de los tramos no circulares (esquema sin escala)
>
> El anillo del vástago se toma desde el tapón-guía hasta el asiento (13 + 38 + 11 = 62 mm), aunque sus 13 mm superiores no tienen caudal pasante. La rama lateral se toma con un paso de 26 mm en los 38 mm de la cara al eje, aunque el adaptador ocupa parte de ese largo. Las dos simplificaciones quedan del lado seguro (Tabla 7).
>
> **Tabla [auto: 7].** Pérdida de carga en la boquilla abierta (Q = 50.000 mm³/s, μ = 5 Pa·s)
>
> | **Tramo** | **Geometría** | **Modelo** | **ΔP (Pa)** |
> | --- | --- | --- | --- |
> | 1. Rama lateral de la T | Ø26 mm, L = 38 mm | Conducto circular | 847 |
> | 2. Anillo del vástago en la T y la pieza de punta | Ø26 / Ø4 mm, L = 62 mm | Anillo concéntrico | 2.819 |
> | 3. Asiento con el vástago | Ø16 / Ø4 mm, L = 3 mm | Anillo concéntrico | 1.288 |
> | 4. Anillo del vástago en la cámara | Ø32 / Ø4 mm, L = 45 mm | Anillo concéntrico | 819 |
> | 5. Anillo de la cabeza abierta | Ø32 / Ø20 mm, L = 8 mm | Anillo concéntrico | 1.355 |
> | 6. Cámara libre bajo la cabeza | Ø32 mm, L = 13 mm | Conducto circular | 126 |
> | 7. Reducción | Ø32 a Ø14,48 mm, L = 15 mm | Cono (integración) | 869 |
> | 8. Lanza | Ø14,48 mm, L = 113 mm | Conducto circular | 26.182 |
> | 9. Salida contra el fondo | h = 20 mm, cara de Ø14,48 a Ø15,88 mm | Flujo radial entre placas | 6 |
> | **Total boquilla** |  |  | **34.311** |
>
> La salida contra el fondo del envase suma 6 Pa, un valor despreciable frente al resto. La lanza concentra el 76 % de la pérdida de la boquilla, porque es el tramo más largo y angosto. Su largo y su diámetro los fijan el envase y la boca, por lo que es la pérdida que menos se puede reducir.
>
> *ΔPmanguera = 128 × 5 Pa·s × 1 m × 50×10⁻⁶ m³/s / (π × (0,03175 m)⁴) ≈ 10.024 Pa*
>
> *ΔPtotal = ΔPboquilla + ΔPmanguera ≈ 34.311 + 10.024 ≈ 44.335 Pa ≈ 0,0443 MPa*
>
> Con una manguera de 1” del mismo largo, la pérdida total sería de 58.783 Pa.

**C14**
- **Ubicación:** Sección 6.1, justificación del CS = 3. Ancla: «la viscosidad de diseño y la longitud de la boquilla son estimadas»
- **Acción:** REEMPLAZAR
- **Texto final:** la viscosidad de diseño es estimada

**C15**
- **Ubicación:** Sección 6.1, tabla "Fuerza de resistencia del fluido y fuerza mínima requerida" (queda como Tabla 8). Las 5 filas de datos, desde la fila «| 40 | 1.257 | 42,9 | 128,6 |» hasta la fila «| 100 | 7.854 | 267,9 | 803,6 |».
- **Acción:** REEMPLAZAR las 5 filas (el encabezado no cambia).
- **Texto final:**

| 40 | 1.257 | 55,7 | 167,2 |
| 50 | 1.963 | 87,0 | 261,1 |
| 63 | 3.117 | 138,2 | 414,6 |
| 80 | 5.027 | 222,9 | 668,6 |
| 100 | 7.854 | 348,2 | 1.044,6 |

### SECCIÓN 6.2

**C16**
- **Ubicación:** Tabla "Selección del actuador SMC CP96 para cada candidato" (queda como Tabla 9), columna "F mínima (N)".
- **Acción:** REEMPLAZAR solo el valor de esa celda en cada fila. Las demás celdas no cambian; en particular, **no cambia ningún actuador**.
- **Texto final:** fila «| 40 | 397,9 | 400 |»: 128,6 → **167,2**; fila «| 50 | 254,6 | 320 |»: 200,9 → **261,1**; fila «| 63 | 160,4 | 200 |»: 319,0 → **414,6**; fila «| 80 | 99,5 | 100 |»: 514,3 → **668,6**; fila «| 100 | 63,7 | 80 |»: 803,6 → **1.044,6**.

### SECCIÓN 7.1

**C17**
- **Ubicación:** Sección 7.1. Origen: la imagen y el título «Columna de pandeo formada por los dos vástagos y modelo empotrado–libre (esquema sin escala)», que hoy están después del título de la figura de tensión crítica de pandeo. Destino: inmediatamente **después** del párrafo que termina en «en esta sección se determinan los límites entre los que debe quedar su valor real.»
- **Acción:** MOVER (imagen y título juntos)
- **Qué se ajusta:** nada en el texto de la figura. Con el cambio, la columna de pandeo se cita y aparece antes que la curva de Euler, y Word las numera 12 y 13. En el texto, la cita de la columna queda como «Figura 12» y la de la curva, como «Figura 13» (ver la Sección 3 de este archivo).

### SECCIÓN 8.1

**C18**
- **Ubicación:** Sección 8.1, **después** del párrafo que termina en «igual al del candidato de 40 mm.»
- **Acción:** AGREGAR
- **Texto final:**

> Con este actuador, y con CS = 3 en el balance de fuerzas de la Sección 6.1, el largo máximo de la manguera de 1¼” entre la válvula y la boquilla es:
>
> *Lmáx = [Factuador / (CS × A) − ΔPboquilla] / ΔPmanguera/m = [692 / (3 × 5.027) − 34.311] / 10.024 ≈ 1,15 m*
>
> donde Factuador / (CS × A) = 692 N / (3 × 5.027 mm²) ≈ 45.886 Pa y ΔPmanguera/m = 10.024 Pa/m es la pérdida por metro de la manguera (Sección 6.1). Con el valor de trabajo de 1 m (Sección 2), CS = 3,10.

**C19**
- **Ubicación:** Sección 8.1. Ancla: «los cinco candidatos verifican holgadamente»
- **Acción:** REEMPLAZAR
- **Texto final:** los cinco candidatos verifican

### SECCIÓN 9.2

**C20**
- **Ubicación:** Sección 9.2. Ancla: «quedan como pendiente (Sección 21)»
- **Acción:** REEMPLAZAR
- **Texto final:** quedan como pendiente (Sección 22)

### SECCIÓN 13

**C21**
- **Ubicación:** Sección 13.1. Ancla: «los precios por metro quedan pendientes de cotización (Sección 21)»
- **Acción:** REEMPLAZAR
- **Texto final:** los precios por metro quedan pendientes de cotización (Sección 22)

**C22**
- **Ubicación:** Sección 13.3, Tabla 15. Agregar una fila después de la fila «| 13 | 1 | 529,6 | 529,6 |» y reemplazar la fila del total, «| **Total** | **23** | **—** | **15.631,1** |».
- **Acción:** AGREGAR fila + REEMPLAZAR fila de total.
- **Texto final:**

| 14 | 2 | 421,7 | 843,4 |
| **Total** | **25** | **—** | **16.474,5** |

**C23**
- **Ubicación:** Sección 13.3. El párrafo que va desde «Con barras comerciales de 6 m, los 15.631 mm de tubo» hasta «que no se incluye en las longitudes.»
- **Acción:** REEMPLAZAR
- **Texto final:** Con barras comerciales de 6 m, los 16.475 mm de tubo requieren como mínimo 16.475 / 6.000 ≈ 2,7 barras, es decir, 3 barras. El ítem 14 corresponde a los montantes del cabezal de llenado (Sección 19.7). La Tabla 16 distribuye los cortes en esas 3 barras, con un montante en la barra 1 y otro en la barra 2, de modo que cada barra conserva al menos unos 359 mm para absorber el espesor de corte de la sierra, que no se incluye en las longitudes.

**C24**
- **Ubicación:** Sección 13.3, Tabla 16, filas de las barras 1 y 2 (anclas: «5.219,4» y «5.210,7»).
- **Acción:** REEMPLAZAR las dos filas. La barra 3 no cambia.
- **Texto final:**

| 1 | 2 (×2), 5, 10, 11, 12, 13, 14 | 8 | 5.641,1 | 358,9 |
| 2 | 2 (×3), 4, 5, 6, 9, 14 | 8 | 5.632,4 | 367,6 |

**C25**
- **Ubicación:** Sección 13.3, última frase. Ancla: «deben revisarse con el perfil adoptado de 25 × 25 × 1,25 mm (Sección 21)»
- **Acción:** REEMPLAZAR
- **Texto final:** deben revisarse con el perfil adoptado de 25 × 25 × 1,25 mm (Sección 22)

### SECCIÓN 14.5

**C26**
- **Ubicación:** Sección 14.5. Desde el párrafo que empieza con «Como estimación de trabajo, a falta del diseño definitivo de la bancada» hasta la fórmula de Hdisponible inclusive (la línea que termina en «= 900 mm»).
- **Acción:** REEMPLAZAR
- **Texto final:**

> La entrada de succión del cilindro dosificador fija el nivel inferior de la tolva, por estar ambos a la misma altura (Sección 9.1). La cara superior del tubo delantero de la bancada está a 1.090 mm del piso y el eje del cilindro dosificador queda 75 mm por encima, por la altura de la caja de soporte y de sus patas (Sección 17.9), es decir, a 1.165 mm:
>
> *Hdisponible = Hmáx,carga − Hentrada,dosificador = 1.900 − 1.165 = 735 mm*

**C27**
- **Ubicación:** Sección 14.5, Tabla 17, fila «| 340 | 272,5 | 628,8 | 901,3 | 66,0 |».
- **Acción:** REEMPLAZAR la fila. La fila de 400 mm no cambia.
- **Texto final:**

| 399,6 | 324,1 | 410,9 | 735,0 | 66,0 |

**C28**
- **Ubicación:** Sección 14.5. El párrafo que va desde «El diámetro de 340 mm es, en la práctica, el mínimo» hasta «sin revisar la geometría de la tolva.»
- **Acción:** REEMPLAZAR
- **Texto final:** El diámetro mínimo que permite contener los 66 L dentro de la altura disponible es de 399,6 mm. Se adopta D = 400 mm: con el mismo volumen total, la altura total resulta de 734,2 mm y la boca de carga queda a 1.165 + 734,2 ≈ 1.899 mm sobre el piso, dentro del límite ergonómico de 1.900 mm (Figura 25).

### SECCIÓN 15.3

**C29**
- **Ubicación:** Título de la Sección 15.3. Ancla: «15.3 Uniones de la válvula de tres vías» (el título de la sección, no la línea del índice).
- **Acción:** REEMPLAZAR
- **Texto final:** 15.3 Uniones de la válvula de tres vías y de las mangueras

**C30**
- **Ubicación:** Sección 15.3. El párrafo que va desde «Las otras dos bocas se conectan a las mangueras de 1» hasta «sin cortar ni soldar.»
- **Acción:** REEMPLAZAR
- **Texto final:** Las otras dos bocas se conectan a la manguera de 1” de la tolva y a la de 1¼” de la boquilla, ambas de PVC cristal reforzada con malla de poliéster (Sección 3.3). La unión se hace con adaptadores de acero inoxidable que se encuentran en el mercado, con un extremo Tri-Clamp de 50,5 mm y el otro en espiga para manguera de 1” [66] o de 1¼”, según la manguera. Cada adaptador se une a la boca de la válvula con abrazadera y junta, y la manguera se ajusta sobre la espiga con una abrazadera de manguera. Así, las tres bocas quedan con uniones desmontables, que permiten retirar la válvula sin cortar ni soldar.

**C31**
- **Ubicación:** Sección 15.3, **después** del párrafo que termina en «con el mismo criterio de la Sección 6.3.»
- **Acción:** AGREGAR
- **Texto final:** En la boquilla, la manguera de 1¼” se ajusta con una abrazadera de manguera sobre otro adaptador Tri-Clamp × espiga. Ese adaptador se une con abrazadera y junta a un adaptador R 1 × Tri-Clamp, enroscado en la rama lateral de la T y sellado con cinta de PTFE [93] (Sección 3.3).

**C32**
- **Ubicación:** Sección 15.3. Desde «La Tabla 20 resume los componentes de las tres uniones» hasta «con la boquilla de llenado.» (las dos frases del párrafo que precede a la tabla).
- **Acción:** REEMPLAZAR
- **Texto final:** La Tabla 22 resume los componentes de las tres uniones de la válvula, de la unión con la boquilla y de las dos mangueras, con un esquema de cada uno.

**C33**
- **Ubicación:** Sección 15.3, título de la tabla. Ancla: «Componentes de las uniones de la válvula de tres vías»
- **Acción:** REEMPLAZAR
- **Texto final:** Componentes de las uniones de la válvula de tres vías y de la boquilla

**C34**
- **Ubicación:** Sección 15.3, cuerpo de la tabla (queda como Tabla 22).
- **Acción:** REEMPLAZAR todas las filas de datos, desde «Ferrule Tri-Clamp para soldar» hasta la fila «Manguera», por las siguientes. En la columna "Imagen" se conservan las imágenes de las filas existentes; las filas nuevas o duplicadas llevan la imagen que se indica.
- **Texto final:**

| **Imagen** | **Componente** | **Especificación** | **Cantidad** | **Ubicación** |
| --- | --- | --- | --- | --- |
| (la actual) | Ferrule Tri-Clamp para soldar | DN25 según DIN 32676 (paso de 26 mm, ala de 50,5 mm, largo de 21,5 mm), AISI 304 [65] | 1 | Tapa delantera del cilindro dosificador |
| (la actual) | Abrazadera Tri-Clamp | Para ala de 50,5 mm | 4 | Una por boca de la válvula y una en la boquilla |
| (la actual) | Junta Tri-Clamp | Para ala de 50,5 mm | 4 | Una por boca de la válvula y una en la boquilla |
| (la actual) | Adaptador Tri-Clamp × espiga | Extremo Tri-Clamp de 50,5 mm y espiga para manguera de 1”, acero inoxidable [66] | 1 | Boca de la válvula hacia la tolva |
| (la misma del adaptador de 1”) | Adaptador Tri-Clamp × espiga | Extremo Tri-Clamp de 50,5 mm y espiga para manguera de 1¼”, acero inoxidable | 2 | Boca de la válvula hacia la boquilla y rama lateral de la boquilla |
| [completar: imagen] | Adaptador R 1 × Tri-Clamp | Rosca macho R 1 a férula Tri-Clamp de 1”, AISI 316 | 1 | Rama lateral de la T de la boquilla |
| [completar: imagen] | Cinta de sellado | PTFE, conforme a 21 CFR 177.1550 [93] | — | Rosca R 1 del adaptador de la boquilla |
| (la actual) | Espiga para soldar | Espiga para manguera de 1”, AISI 304 | 1 | Salida del cono de la tolva |
| (la actual) | Abrazadera de manguera | Para manguera de 1” | 2 | Sobre la espiga de la tolva y sobre el adaptador de la válvula hacia la tolva |
| (la misma de la abrazadera de 1”) | Abrazadera de manguera | Para manguera de 1¼” | 2 | Sobre el adaptador de la válvula hacia la boquilla y sobre el de la boquilla |
| (la actual) | Manguera | PVC cristal reforzada con malla de poliéster (Sección 3.3); 1” entre la tolva y la válvula y 1¼” entre la válvula y la boquilla, como máximo 1,15 m (Sección 8.1) | 2 tramos | Tolva–válvula y válvula–boquilla |

### SECCIÓN 16.11

**C35**
- **Ubicación:** Sección 16.11. Ancla: «punto pendiente general de la Tabla 28»
- **Acción:** REEMPLAZAR
- **Texto final:** punto pendiente general de la Tabla 38

### SECCIÓN 17 (caja de soporte)

**C36**
- **Ubicación:** Sección 17.2. Ancla: «171,4 N en inyección (Tabla 6)»
- **Acción:** REEMPLAZAR
- **Texto final:** 222,9 N en inyección (Tabla 8)

**C37**
- **Ubicación:** Sección 17.2. Ancla: «la fuerza de resistencia del fluido en operación, 171,4 N.»
- **Acción:** REEMPLAZAR
- **Texto final:** la fuerza de resistencia del fluido en operación, 222,9 N.

**C38**
- **Ubicación:** Sección 17.2. Ancla: «se escalan por 171,4 / 692»
- **Acción:** REEMPLAZAR
- **Texto final:** se escalan por 222,9 / 692

**C39**
- **Ubicación:** Sección 17.3, "Verificación a fatiga". Ancla: «los momentos Miny × 171,4 / 692 en inyección»
- **Acción:** REEMPLAZAR
- **Texto final:** los momentos Miny × 222,9 / 692 en inyección

**C40**
- **Ubicación:** Sección 17.3. Desde «es de 10,21 mm en la cara exterior del borde del puerto» hasta «9,57 mm en la raíz del voladizo.»
- **Acción:** REEMPLAZAR
- **Texto final:** es de 10,75 mm en la cara exterior del borde del puerto, 9,60 mm en el fondo del rebaje, 10,01 mm en las franjas de espesor completo y 9,59 mm en la raíz del voladizo.

**C41**
- **Ubicación:** Sección 17.3, tabla "Espesor mínimo de la pared delantera por criterio" (queda como Tabla 27). Las 6 filas de datos.
- **Acción:** REEMPLAZAR las 6 filas (quedan ordenadas de mayor a menor, como ahora).
- **Texto final:**

| Flexión en el centro de la pared | 2,5 | **11,54** |
| Fatiga, borde del puerto (cara exterior) | 3 | 10,75 |
| Flexión local junto a los tirantes | 2,5 | 10,30 |
| Fatiga, franjas de espesor completo | 3 | 10,01 |
| Fatiga, borde del puerto (fondo del rebaje) | 3 | 9,60 |
| Fatiga, raíz del voladizo junto a los tirantes | 3 | 9,59 |

  El párrafo siguiente («El espesor lo define la flexión en el centro de la pared, con 11,54 mm…») **no cambia**: el espesor lo sigue definiendo la flexión y 10,75 mm < 12,7 mm.

**C42**
- **Ubicación:** Sección 17.4. Ancla: «el espesor mínimo que cumple CS = 3 es de 14,98 mm»
- **Acción:** REEMPLAZAR
- **Texto final:** el espesor mínimo que cumple CS = 3 es de 15,21 mm

**C43**
- **Ubicación:** Sección 17.4. Ancla: «el espesor mínimo es de 14,43 mm»
- **Acción:** REEMPLAZAR
- **Texto final:** el espesor mínimo es de 14,57 mm

  (El espesor adoptado, 15,9 mm, sigue siendo el comercial inmediato superior: 15,21 < 15,875 mm. El resto de 17.4 no cambia.)

**C44**
- **Ubicación:** Sección 17.5, "Flexión de las pestañas". Ancla: «el espesor mínimo que cumple CS = 3 es de 2,35 mm»
- **Acción:** REEMPLAZAR
- **Texto final:** el espesor mínimo que cumple CS = 3 es de 2,44 mm

**C45**
- **Ubicación:** Sección 17.5, "Espesor adoptado". Ancla: «El espesor lo define la flexión de las pestañas en inyección, con 2,40 mm.»
- **Acción:** REEMPLAZAR
- **Texto final:** El espesor lo define la fatiga de las pestañas, con 2,44 mm, que supera al de flexión en inyección, 2,40 mm.

  (La frase siguiente, «Se adopta el espesor comercial inmediato superior… tlat = 2,5 mm», y las viñetas no cambian.)

**C46**
- **Ubicación:** Sección 17.7, tabla "Verificación a fatiga de la caja" (queda como Tabla 28). Las 7 filas de datos (el título y el encabezado no cambian).
- **Acción:** REEMPLAZAR las 7 filas.
- **Texto final:**

| Pared delantera, borde del agujero del puerto, cara exterior | +12,8 | −15,3 | 1,88 | 26,4 | −2,3 → 0 | 4,31 |
| Pared delantera, borde del agujero del puerto, fondo del rebaje | −10,8 | +12,8 | 1,88 | 22,2 | 1,9 | 4,97 |
| Pared delantera, franjas de espesor completo, cara interior | −18,1 | +21,5 | 1 | 19,8 | 1,7 | 5,58 |
| Pared delantera, raíz del voladizo junto a los tirantes | 25,6 (mín.) | 39,4 (máx.) | 1 | 6,9 | 32,5 | 6,18 |
| Pared del actuador, borde del agujero de Ø36 mm (EC4) | +3,7 | −28,6 | 2,16 | 34,9 | −27,0 → 0 | 3,22 |
| Pared del actuador, borde del agujero de la guía, Ø33 mm (EC4) | +2,0 | −27,4 | 2,22 | 32,6 | −28,1 → 0 | 3,46 |
| Pestañas de las laterales, pliegue | +21,4 | −50,7 | 1 | 36,1 | −14,7 → 0 | 3,16 |

**C47**
- **Ubicación:** Sección 17.7, párrafo posterior a la figura del diagrama de Goodman. Desde «El más exigido es el borde del agujero de Ø36 mm» hasta «mayor que la fuerza de operación que realmente las recorre (Sección 17.2).» La primera frase del párrafo («Todos los puntos verifican…») y las frases que siguen al fragmento («Los resultados surgen además…» y «Las laterales…») no cambian.
- **Acción:** REEMPLAZAR
- **Texto final:** El más exigido es el pliegue de las pestañas (CS = 3,16), seguido del borde del agujero de Ø36 mm de la pared del actuador (3,22) y del borde del agujero de la guía (3,46). En las pestañas, la amplitud se calcula con FIN = 581 N, mayor que la fuerza de operación que realmente las recorre (Sección 17.2); en la pared del actuador, la define el estado de carga del tope, con la fuerza de choque acotada de la Sección 16.5.

### SECCIÓN 18.1

**C48**
- **Ubicación:** Sección 18.1. Origen: las dos imágenes y el título «Soporte de la tolva: ménsulas, postes y voladizo de la bancada», que hoy están al final de "Voladizo de la bancada". Destino: inmediatamente **después** del primer párrafo de 18.1, que termina en «configuración de soporte por ménsulas sobre columnas [82].»
- **Acción:** MOVER (imágenes y título juntos)
- **Qué se ajusta:** nada en el texto. La figura pasa a ser la primera de la Sección 18 (Figura 51), que es también la primera que se cita.

**C49**
- **Ubicación:** Sección 18.1, "Voladizo de la bancada". Ancla: «se verifica junto con ella (Sección 19)»
- **Acción:** REEMPLAZAR
- **Texto final:** se verifica junto con ella (Sección 20)

### NUEVA SECCIÓN 19

**C50**
- **Ubicación:** Entre el final de la Sección 18 (el párrafo «[completar: resultados del análisis por elementos finitos de la pared de la tolva junto a las ménsulas.]») y el título «19. Verificación estructural de la bancada».
- **Acción:** AGREGAR (sección completa)
- **Texto final:**

> # **19. Cabezal de llenado**
>
> El cabezal de llenado recibe el producto de la válvula de tres vías y lo deposita en el envase. Está formado por la boquilla con su lanza y la manguera (Sección 3.3), el carro vertical, la regulación de altura, el bastidor y los sensores.
>
> ## **19.1 Función y configuración general**
>
> El cabezal se monta sobre el tubo delantero de la bancada (Figura 60):
>
> * Dos guías de Ø12 mm y dos montantes de tubo se sueldan al tubo, y una placa superior une sus extremos.
> * Sobre las guías deslizan la placa soporte, que se fija a la altura de cada formato con un husillo, y el carro, que sube y baja en cada ciclo.
> * El actuador del carro va sobre la placa soporte, 35 mm al costado del centro y 35 mm detrás del plano de las guías. La tuerca del husillo va en el plano de las guías, 35 mm al costado del centro, del lado opuesto. El carro lleva la boquilla 80 mm por delante de las guías.
>
> Así, solo la boquilla, la lanza y el envase quedan por delante del tubo.
>
> La cinta transportadora, diseñada en otra etapa del proyecto, está a 925 mm del piso, 165 mm por debajo de la cara superior del tubo delantero de la bancada (Sección 14.5).
>
> [IMAGEN: la que precede a «**Figura 45.** Cabezal de llenado sobre la bancada» en seccion17.md, editada según la Sección 5 de este archivo]
>
> **Figura [auto: 60].** Cabezal de llenado sobre la bancada: (a) vista frontal; (b) vista lateral (cotas en mm, esquema sin escala)
>
> El ciclo tiene cuatro etapas (Figura 61):
>
> * **Bajada:** con el envase detenido bajo la boquilla, el carro baja y la lanza entra hasta cerca del fondo.
> * **Llenado:** el obturador abre y el pistón inyecta. Mientras el envase se llena, la lanza sube lentamente sin salir de él.
> * **Cierre:** al terminar la inyección, el obturador cierra y aspira la gota de la punta.
> * **Subida:** la lanza sale del envase a 100 mm/s, la válvula conmuta hacia la tolva y el pistón aspira mientras la cinta cambia el envase.
>
> [IMAGEN: la que precede a «**Figura 46.** Secuencia de llenado» en seccion17.md]
>
> **Figura [auto: 61].** Secuencia de llenado: (a) llega el envase; (b) baja el cabezal; (c) llenado con la lanza subiendo; (d) cierra el obturador; (e) sube el cabezal y sale el envase (esquema sin escala)
>
> Para cambiar de formato, el volante sube o baja la placa soporte 49 mm (Sección 3.3) y una traba la fija en su lugar. La lanza es la misma para los dos formatos; solo cambia la velocidad de subida, que el PLC elige según el formato seleccionado.
>
> ### **Material**
>
> El carro y la placa soporte son de SAE 1010 laminado en caliente [61], galvanizados en caliente junto con la bancada (Secciones 13.1 y 13.2). Sobre ellos apoyan piezas de otros dos metales. El soporte de la boquilla, de AISI 304, es pequeño frente a la superficie de zinc, por lo que el riesgo galvánico es bajo [58], [59], con el criterio de la Sección 17.1. Las bridas de los bujes son de aluminio anodizado, y su contacto con el zinc produce en ambiente atmosférico una corrosión adicional nula o leve [102].
>
> ## **19.2 Actuador del obturador**
>
> Se usa un cilindro de doble efecto, para que la apertura y el cierre sean forzados por aire, con el criterio de la Sección 4: SMC CJ5-S de acero inoxidable en su diámetro menor, Ø10, con vástago de 4 mm y carrera estándar de 45 mm [94]. A p = 0,55 MPa:
>
> *Favance = p × π × D² / 4 ≈ 43,2 N ; Fretroceso = p × π × (D² − dv²) / 4 ≈ 36,3 N*
>
> donde D = 10 mm es el diámetro del pistón y dv = 4 mm el del vástago.
>
> El avance abre y el retroceso cierra. Como la cabeza está debajo del asiento, la presión del producto la empuja hacia abajo, en el sentido de apertura. El caso exigente es el cierre, al terminar la inyección (Figura 62a). La presión sobre la cabeza es, como máximo, la pérdida de carga entre el asiento y la salida durante la inyección, 30.645 Pa (tramos 3 a 9 de la Tabla 7). Se aplica sobre el área sellada por el *o-ring*, tomada del lado seguro con el diámetro exterior de la cabeza, dj = 20 mm:
>
> *Fhidráulica = p × π × (dj² − dv²) / 4 = 0,0306 × π × (20² − 4²) / 4 ≈ 9,2 N*
>
> donde se descuenta el área del vástago, que atraviesa el asiento. La Tabla 30 resume las verificaciones del actuador: el factor de carga en el cierre, frente al máximo recomendado por el fabricante para operación dinámica [9], la presión, la velocidad y la energía cinética de la masa móvil, de unos 45 g entre vástago, obturador, manguito y pistón.
>
> **Tabla [auto: 30].** Verificación del actuador del obturador SMC CJ5-S Ø10 × 45
>
> | **Verificación** | **Valor calculado** | **Límite** | **Resultado** |
> | --- | --- | --- | --- |
> | Factor de carga en el cierre | φ = 9,2 / 36,3 = 0,25 | φ ≤ 0,5 [9] | Verifica |
> | Presión de trabajo | 0,55 MPa | 0,1 a 0,7 MPa [94] | Verifica |
> | Velocidad del pistón | 300 mm/s (45 mm en 0,15 s) | 50 a 750 mm/s [94] | Verifica |
> | Energía cinética | 0,002 J | 0,035 J [94] | Verifica |
>
> Al abrir, el vástago entra 45 mm en el conducto y desplaza 565 mm³, que salen por la lanza al envase. Al cerrar, sale los mismos 45 mm y aspira ese volumen por la punta: el producto retrocede 565 / 164,7 ≈ 3,4 mm dentro de la lanza y no queda una gota colgando (Figura 62b). Como el vástago entra y sale el mismo volumen en cada ciclo, cada envase recibe exactamente el volumen barrido por el pistón.
>
> [IMAGEN: la que precede a «**Figura 53.** Obturador» en seccion17.md]
>
> **Figura [auto: 62].** Obturador: (a) fuerzas sobre la cabeza al cerrar; (b) retroceso del producto en la punta de la lanza (esquema sin escala)
>
> En la puesta en marcha, la boquilla y la manguera se purgan con ciclos en vacío sobre un recipiente.
>
> ## **19.3 Subida de la lanza durante el llenado**
>
> La lanza no puede quedar abajo durante toda la inyección. En el envase de 250 ml, el espacio libre de 7 ml queda arriba. Con la lanza abajo quedarían sumergidos al menos los 88 mm que van de la punta al arranque del cuello, π × 15,88² / 4 × 88 ≈ 17,4 ml, más del doble del espacio libre, y el envase rebalsaría.
>
> Por eso la lanza sube a velocidad constante mientras se llena y no sale del envase hasta terminar el llenado. La subida lenta empieza con la inyección y termina con el obturador cerrado, en tiny + tcierre, con la punta 20 mm debajo del borde de la boca. El recorrido es el mismo en los dos formatos, 128 − 20 − 20 = 88 mm en el de 250 ml y 177 − 20 − 69 = 88 mm en el de 500 ml, pero el tiempo no (Sección 3.2 y Tabla 30):
>
> *v250 = 88 / (5,0 + 0,15) ≈ 17,1 mm/s ; v500 = 88 / (10,0 + 0,15) ≈ 8,7 mm/s*
>
> Para verificar que el envase no rebalse, se calculó el nivel del producto en cada instante con el caudal de 50 ml/s, descontando el volumen de la lanza sumergida. Como la forma del hombro y del domo es esquemática, el perfil de cada envase se ajustó para que su volumen total coincida con el cubicaje de la ficha (257 y 520 ml, Sección 2). Se probaron distintas formas de hombro, con resultados prácticamente iguales (Figura 63).
>
> [IMAGEN: la que precede a «**Figura 55.** Altura de la punta de la lanza» en seccion17.md]
>
> **Figura [auto: 63].** Altura de la punta de la lanza y del nivel del producto durante el llenado: (a) envase de 250 ml; (b) envase de 500 ml (perfil de los envases ajustado al cubicaje)
>
> La punta queda siempre por encima del nivel. En el envase de 250 ml lo hace entre 8 y 20 mm, y al final del llenado alcanza el nivel con 1 mm sumergido como máximo. En el de 500 ml queda entre 50 y 70 mm por encima durante casi todo el llenado y termina 8 a 10 mm sobre el nivel. Ninguno de los dos envases rebalsa. En el de 500 ml, en cambio, la subida de la lanza casi no reduce la caída libre del producto.
>
> ## **19.4 Carro vertical**
>
> El carro es una chapa de SAE 1010 laminada en caliente de 6,35 mm [61], de 190 × 80 mm (Figura 64). Lleva dos bujes con brida, el soporte de la boquilla, la unión flotante del actuador y un agujero de paso de Ø20 mm para el extremo del husillo, que lo atraviesa cuando el carro sube.
>
> La resistencia no define el espesor (Sección 19.5). Se adopta 6,35 mm, el mismo espesor de la placa superior del bastidor (Sección 19.7), para que los agujeros roscados M4 de los bujes y M5 del soporte de la boquilla tengan un largo de rosca de al menos un diámetro.
>
> ### **Soporte de la boquilla**
>
> El soporte une la T al carro (Figura 64). Es una pieza de AISI 304 formada por un ala, un puente y una abrazadera partida que toma el tramo recto de la T entre la rama lateral y la boca superior. El ala apoya sobre la cara superior del carro y se fija con dos tornillos M5 de acero inoxidable A2-70; la tapa de la abrazadera cierra con otros dos M5. Las dos mitades de la abrazadera se cortan de una misma pieza y el agujero se mecaniza al diámetro exterior medido en la T comprada, porque esa medida cambia entre fabricantes (39,6 mm en la de la referencia [96]). El eje de la boquilla queda 80 mm por delante del plano de las guías.
>
> La cara inferior de la abrazadera apoya sobre el lomo de la rama lateral, y del lado de la rama cada mitad tiene una oreja que baja por el costado de la rama. Así la rama queda encajada: la T no puede girar y una fuerza hacia arriba sobre la lanza pasa al soporte por contacto, sin depender del apriete. El apriete de la tapa sostiene el peso de la boquilla.
>
> [IMAGEN: la que precede a «**Figura 54.** Carro y soporte de la boquilla» en seccion17.md, editada según la Sección 5 de este archivo]
>
> **Figura [auto: 64].** Carro y soporte de la boquilla: (a) vista superior; (b) vista lateral en el plano de la boquilla (cotas en mm, esquema sin escala)
>
> ### **Masa del conjunto móvil**
>
> La Tabla 31 reúne la masa del carro con todo lo que lleva. Se calcula con γ = 76,5 kN/m³ para el acero al carbono y 76,0 kN/m³ para el inoxidable [13], y con las masas de catálogo.
>
> **Tabla [auto: 31].** Masa del conjunto móvil del carro
>
> | **Componente** | **Origen** | **Masa (kg)** |
> | --- | --- | --- |
> | Carro (chapa de SAE 1010 de 6,35 mm, 190 × 80 mm) | Cálculo | 0,700 |
> | Bujes igus FJUM-01-12 (2) | 42 g cada uno [97] | 0,084 |
> | Soporte de la boquilla (AISI 304) | Cálculo | 0,221 |
> | T roscada 1” clase 150 | Catálogo [91] | 0,256 |
> | Pieza de punta | Cálculo | 0,383 |
> | Pieza de lanza | Cálculo | 0,249 |
> | Tubo de la lanza (15,88 × 0,70 × 113 mm) | Cálculo | 0,029 |
> | Tapón-guía | Cálculo | 0,261 |
> | Linterna | Cálculo | 0,162 |
> | Actuador CJ5-S Ø10 × 45 | 52 g + 3 × 4 g [94] | 0,064 |
> | Vástago y obturador | Cálculo | 0,030 |
> | Producto dentro de la boquilla abierta (138 ml) | ρ = 1.100 kg/m³ | 0,152 |
> | **Total** |  | **2,591** |
>
> El peso resulta W = 2,591 × 9,81 ≈ 25,4 N. Sin el carro ni los bujes, el grupo de la boquilla (soporte, boquilla con su actuador y producto) tiene una masa de 1,807 kg y pesa 17,7 N. Juntas, adaptadores, unión flotante, tornillería y la parte de la manguera que cuelga del carro quedan cubiertos por el margen del actuador.
>
> ### **Bujes y guías**
>
> El carro y la placa soporte deslizan sobre las dos guías de Ø12 mm, con un buje igus drylin R FJUM-01-12 por guía en cada placa: buje con brida de aluminio anodizado y liner de iglidur J, de 32 mm de largo, 960 N de carga dinámica (p = 5 MPa), 6.720 N de carga estática (p = 35 MPa) y 42 g [97]. La brida se atornilla a la placa con tornillos M4 y el cuerpo del buje entra en un agujero de Ø22 mm [97].
>
> Con una distribución lineal de presión en el buje, sus resultantes quedan separadas 2L/3 (Figura 65b) y la fuerza en cada extremo es:
>
> *Fextremo = 3 × Mbuje / (2 × Lbuje)*
>
> donde Mbuje es la mitad del momento total, porque hay un buje por guía, y Lbuje = 32 mm. Las guías solo reciben el peso del carro y la fuerza del actuador que lo sostiene. Los casos son:
>
> * **Carro colgado del actuador:** el actuador sostiene el peso 35 mm al costado y 35 mm detrás del plano de las guías (Sección 19.1). El centro de masa del conjunto se toma, del lado seguro, sobre el eje de la boquilla, 80 mm por delante (Figura 65a). Con una distancia de √(35² + 115²) ≈ 120,2 mm: M = 25,4 × 120,2 ≈ 3.053 N·mm.
> * **Placa soporte:** las reacciones del actuador y de la tuerca del husillo, separadas √(70² + 35²) ≈ 78,3 mm (Sección 19.1), forman un par: M = 25,4 × 78,3 ≈ 1.989 N·mm.
>
> [IMAGEN: la que precede a «**Figura 57.** Cargas sobre las guías» en seccion17.md, editada según la Sección 5 de este archivo]
>
> **Figura [auto: 65].** Cargas sobre las guías: (a) brazo del peso del carro respecto del actuador; (b) distribución de presión en el buje (cotas en mm, esquema sin escala)
>
> **Tabla [auto: 32].** Verificación de las guías lineales
>
> | **Caso** | **Momento total (N·mm)** | **Fextremo por buje (N)** | **Carga del buje (N)** | **Resultado** |
> | --- | --- | --- | --- | --- |
> | Carro colgado del actuador | 3.053 | 71,6 | 960 (dinámica) | Verifica |
> | Placa soporte | 1.989 | 46,6 | 960 (dinámica) | Verifica |
>
> Cada guía recibe el momento de un buje de la placa soporte, 995 N·mm, más la mitad del momento del carro, 1.527 N·mm. Tomando ambos sumados, del lado seguro:
>
> *σ = 32 × M / (π × d³) = 32 × (995 + 1.527) / (π × 12³) ≈ 14,9 MPa*
>
> con CS = 180 / 14,9 ≈ 12,1 respecto del límite elástico del SAE 1010 (Sección 13.1). Los coeficientes altos cubren también las cargas de inercia en los finales de carrera, que no se evaluaron.
>
> ## **19.5 Actuador del carro y control de velocidad**
>
> El actuador baja la lanza 150 mm, la sube a velocidad constante durante el llenado y después la retira del envase en la subida rápida. La carrera de 150 mm cubre el recorrido de la punta dentro del envase, 108 mm, y deja la punta 42 mm sobre la boca con el carro arriba, holgura suficiente para el paso del envase.
>
> Se adopta el cilindro de baja velocidad SMC CJ2X en Ø16, con imán para los detectores (versión CDJ2X) y carrera estándar de 150 mm [98], en la designación CDJ2XF16-150-B: brida delantera y detectores en montaje con banda [100]. La serie tiene tubo y vástago de acero inoxidable [99] y admite velocidades de 1 a 300 mm/s. Se pide en la versión con brida delantera, que se atornilla sobre la placa soporte con dos tornillos M5 [100]. A 0,55 MPa:
>
> *Favance = p × π × D² / 4 ≈ 110,6 N ; Fretroceso = p × π × (D² − dv²) / 4 ≈ 99,8 N*
>
> donde D = 16 mm y dv = 5 mm.
>
> El retroceso sube el carro con el peso del conjunto móvil (Sección 19.4). En el avance el peso del carro ayuda, y el actuador solo vence la fricción, porque la lanza no apoya sobre nada: la carrera termina en el tope interno del cilindro, que fija la altura de la punta, y el envase no recibe ninguna fuerza. El vástago se une al carro con una unión flotante SMC JA15-5-080, para rosca M5 × 0,8 [101]. La unión absorbe la excentricidad y el desalineamiento entre el actuador y las guías, ya que el fabricante pide no aplicar carga lateral al cilindro [100]. La Tabla 33 resume las verificaciones: el factor de carga en la subida, frente al máximo de 0,5 [9], las velocidades y la energía cinética del conjunto móvil en los tramos rápidos.
>
> **Tabla [auto: 33].** Verificación del actuador del carro SMC CJ2X Ø16 × 150
>
> | **Verificación** | **Valor calculado** | **Límite** | **Resultado** |
> | --- | --- | --- | --- |
> | Factor de carga en la subida | φ = 25,4 / 99,8 = 0,25 | φ ≤ 0,5 [9] | Verifica |
> | Velocidad de subida lenta | 17,1 y 8,7 mm/s | 1 a 300 mm/s [100] | Verifica |
> | Velocidad de los tramos rápidos | 100 mm/s | 1 a 300 mm/s [100] | Verifica |
> | Energía cinética | ½ × 2,591 × 0,1² ≈ 0,013 J | 0,090 J [100] | Verifica |
> | Carrera | 150 mm (108 mm en el envase + 42 mm de paso) | Carrera estándar [98] | Verifica |
>
> Si el carro empujara contra un obstáculo, la fuerza de avance quedaría aplicada en el eje de la boquilla, a 80 mm del plano de las guías. La sección de las guías tiene un ancho neto de 190 − 2 × 22 − 20 = 126 mm, descontando los agujeros de los bujes y del husillo:
>
> *M = 110,6 × 80 ≈ 8.850 N·mm ; σ = 6 × M / (126 × 6,35²) ≈ 10,4 MPa*
>
> con CS = 180 / 10,4 ≈ 17 respecto del límite elástico del SAE 1010 (Sección 13.1).
>
> La subida es el retroceso: entra aire en la cámara inferior y escapa el de la superior. La velocidad se fija regulando ese escape (Figura 66). Entre la válvula del carro y la cámara superior hay dos caminos en paralelo:
>
> * **Camino rápido:** una electroválvula 2/2 normal cerrada, Y-rápido, que deja escapar el aire libremente. Está abierta en la bajada y en la subida rápida.
> * **Camino lento:** una electroválvula 3/2 usada como selectora, Y-formato, que envía el escape al regulador A (envase de 250 ml) o al B (envase de 500 ml). Los dos tienen válvula antirretorno, de modo que en la bajada el aire entra libre.
>
> Para la operación vertical, el fabricante recomienda reguladores de baja velocidad, montados lo más cerca posible del cilindro, y regular a la vez la entrada de aire, lo que reduce el stick-slip [100]. Por eso A y B son reguladores de baja velocidad de SMC, con un área efectiva controlada de 0,1 a 0,6 mm² según el tamaño, y la cámara inferior lleva un regulador doble de baja velocidad, que regula la entrada de aire durante la subida y la salida durante la bajada [100]. Los reguladores van sobre la placa soporte, junto al cilindro, de modo que las mangueras hasta las bocas son cortas.
>
> [IMAGEN: la que precede a «**Figura 56.** Circuito neumático del actuador del carro» en seccion17.md]
>
> **Figura [auto: 66].** Circuito neumático del actuador del carro con dos velocidades de subida (esquema)
>
> Los reguladores se ajustan una sola vez, en la puesta en marcha, y se traban con su contratuerca; el regulador doble se ajusta de modo que la subida rápida y la bajada se hagan a 100 mm/s. En el cambio de formato el operario no ajusta ningún regulador: el PLC conmuta Y-formato según el formato seleccionado.
>
> ## **19.6 Regulación de altura**
>
> La placa soporte es una chapa de SAE 1010 laminada en caliente de 6,35 mm [61], de 190 × 80 mm, con un buje igual en cada guía. Lleva el actuador del carro, los reguladores de velocidad y la tuerca del husillo. Su espesor se adopta con el mismo criterio del carro (Sección 19.4): un largo de rosca de al menos un diámetro en los agujeros roscados M4 de los bujes y M5 de la brida del actuador.
>
> El husillo es de rosca trapecial Tr16 × 4 de una entrada, en acero inoxidable 1.4301 [103]. Se enrosca en una tuerca igus drylin de iglidur J para Tr16 × 4 [104], atornillada a la placa soporte, y gira apoyado en la placa superior (Figura 67).
>
> El cabezal regulado es el conjunto que cuelga del husillo: el conjunto móvil del carro (Tabla 31), la placa soporte con sus dos bujes, el actuador del carro, sus reguladores y la tuerca del husillo. La placa soporte tiene una masa de 0,715 kg, descontando del lado seguro solo los agujeros de Ø22 mm de los bujes. Los dos bujes suman 0,084 kg [97], y el actuador CDJ2XF16-150-B, 55 + 6,5 × 150 / 15 + 15 = 135 g [100]. Las masas de los reguladores y de la tuerca no figuran en los catálogos consultados y quedan cubiertas, como las de los detectores y las mangueras de aire, por el margen de las verificaciones:
>
> *Wregulado = (2,591 + 0,715 + 0,084 + 0,135) × 9,81 ≈ 34,6 N*
>
> El husillo se gira con el mismo volante del ajuste de carrera, Elesa VRTP.80 A-10-K, sin manija [87] (Sección 16.7). Su extremo superior se tornea a Ø10 h9, con un chavetero para la chaveta DIN 6885 A 3 × 3 × 14 y un agujero roscado M4 en la punta, y gira en un agujero de Ø10,5 mm de la placa superior. El tramo torneado sobresale de la placa lo justo para que la arandela GN 184.5-20, fijada con un tornillo DIN 7991 M4 [88], apoye sobre la punta del husillo y retenga el buje del volante con un pequeño juego axial, sin apretar la placa. El peso del cabezal regulado pasa así de la arandela al buje del volante, que apoya sobre la cara superior de la placa con una arandela de acero inoxidable. Una carga hacia arriba la toma el escalón entre la rosca y el extremo torneado, que apoya contra la cara inferior de la placa con otra arandela. El volante solo se acciona en el cambio de formato, a mano, por lo que el agujero de la placa basta como apoyo de giro, sin rodamientos.
>
> [IMAGEN: la que precede a «**Figura 58.** Apoyo del husillo en la placa superior» en seccion17.md]
>
> **Figura [auto: 67].** Apoyo del husillo en la placa superior (corte, esquema sin escala)
>
> El recorrido, 80 mm, cubre los 49 mm entre formatos y deja 25 mm sobre la posición de 500 ml y 6 mm bajo la de 250 ml para el ajuste fino y las tolerancias de envases y cinta. El ajuste por el domo del fondo (Sección 3.3) se hace subiendo el cabezal dentro de esos márgenes.
>
> El fabricante indica que los husillos trapeciales de una entrada con sus tuercas son autoblocantes y que los de dos entradas no lo son [103]. Con el husillo de una entrada, el cabezal queda sostenido en cualquier posición sin freno.
>
> Contra el giro por vibraciones, la placa soporte lleva un buje partido sobre una de las guías, que se aprieta con una palanca. Para repetir cada formato, un montante lleva una regla graduada en milímetros con un índice en la placa.
>
> ## **19.7 Bastidor**
>
> El bastidor forma parte de la bancada y se galvaniza con ella una vez soldado (Sección 13.2). Está formado por (Figura 68):
>
> * **Guías:** barras de SAE 1010 de Ø12 × 458 mm. Cada una entra por un agujero del tubo delantero, apoya en la pared inferior y se suelda arriba.
> * **Montantes:** tubos de 25 × 25 × 1,25 mm [52] de 421,7 mm, soldados sobre el tubo a 225 mm entre ejes, con un tapón roscado M6 en el extremo.
> * **Placa superior:** chapa de SAE 1010 de 6,35 mm [61], de 250 × 40 mm, atornillada a los montantes con tornillos M6 clase 4.8 (Sección 17.1). Va atornillada para poder montar el carro y la placa soporte en las guías.
>
> Las soldaduras se hacen con el procedimiento para chapa delgada de la Sección 13.1 [64], con un dispositivo que mantiene vertical cada guía.
>
> [IMAGEN: la que precede a «**Figura 59.** Detalle del bastidor» en seccion17.md]
>
> **Figura [auto: 68].** Detalle del bastidor: (a) guía soldada al tubo de la bancada; (b) placa superior sobre el montante (cotas en mm, esquema sin escala)
>
> ### **Verificación**
>
> El grupo de la boquilla pesa 17,7 N (Sección 19.4) y su centro está 80 mm por delante del plano de los montantes (Figura 69a). El bastidor lleva ese momento, Mg = 17,7 × 80 ≈ 1.416 N·mm, al tubo de la bancada, repartido entre montantes y guías según su rigidez:
>
> *fmontantes = 2 × It / (2 × It + 2 × Ig) = 11.195 / (11.195 + 1.018) ≈ 0,917*
>
> donde It = [b⁴ − (b − 2t)⁴] / 12 = 11.195 mm⁴ es el momento de inercia del tubo (b = 25 mm, t = 1,25 mm) e Ig = π × 12⁴ / 64 = 1.018 mm⁴ el de cada guía; como los dos son de SAE 1010, el módulo de elasticidad se simplifica.
>
> En la base de cada montante, con todo el peso del cabezal regulado, F = 34,6 N (Sección 19.6):
>
> *σ = fmontantes × Mg / (2 × S) + F / (2 × A) = 0,917 × 1.416 / (2 × 895,6) + 34,6 / (2 × 118,75) ≈ 0,72 + 0,15 ≈ 0,87 MPa*
>
> donde S = [b⁴ − (b − 2t)⁴] / (6b) = 895,6 mm³ y A = b² − (b − 2t)² = 118,75 mm², con Sy = 180 MPa (Sección 13.1).
>
> Lo que importa es la rigidez, porque la lanza debe entrar en la boca con 1,56 mm de holgura por lado (Sección 3.3). Se aplica Mg en la placa superior, del lado seguro, con h = 428 mm, E = 200 GPa (Sección 13.1) y ΣI = 2 × (11.195 + 1.018) = 24.426 mm⁴. La punta está 573 mm por debajo de la placa superior con el carro abajo:
>
> *θ = Mg × h / (E × ΣI) ≈ 1,2 × 10⁻⁴ rad ; δ = θ × 573 ≈ 0,07 mm*
>
> Las soldaduras de las guías al tubo toman solo la parte del momento que va por las guías, (1 − 0,917) × 1.416 / 2 ≈ 59 N·mm cada una.
>
> La placa superior recibe el peso del cabezal regulado a través del husillo. En el peor caso, si el carro empujara contra un obstáculo, recibe hacia arriba la fuerza de avance del actuador, 110,6 N (Sección 19.5). Se toma como viga apoyada en los montantes, de 225 mm de luz, con la carga en el husillo, a 77,5 mm de un apoyo (Figura 69b):
>
> *M = F × a × b / L = 110,6 × 77,5 × 147,5 / 225 ≈ 5.619 N·mm*
>
> En esa sección está el agujero de Ø10,5 mm del husillo, por lo que se toma el ancho neto:
>
> *S = (40 − 10,5) × 6,35² / 6 ≈ 198 mm³ ; σ = M / S ≈ 28,3 MPa*
>
> La Tabla 34 resume la verificación del bastidor.
>
> [IMAGEN: la que precede a «**Figura 60.** Modelos de verificación del bastidor» en seccion17.md, editada según la Sección 5 de este archivo]
>
> **Figura [auto: 69].** Modelos de verificación del bastidor: (a) rigidez de montantes y guías; (b) placa superior como viga apoyada (cotas en mm, esquema sin escala)
>
> **Tabla [auto: 34].** Verificación del bastidor
>
> | **Verificación** | **Valor calculado** | **Límite** | **Resultado** |
> | --- | --- | --- | --- |
> | Montantes (base) | σ = 0,87 MPa | Sy = 180 MPa | Verifica |
> | Desplazamiento de la punta | 0,07 mm | Holgura de 1,56 mm por lado | Verifica |
> | Placa superior (flexión) | σ = 28,3 MPa; CS = 6,4 | Sy = 180 MPa | Verifica |
>
> ## **19.8 Sensores y tiempos del ciclo**
>
> ### **Sensores del cabezal**
>
> El cabezal lleva los detectores del actuador del carro y el pulsador de parada (Tabla 35). Los detectores son de estado sólido, SMC D-M9, aplicables a la serie CJ2X en montaje con banda [100]. Van en el tubo del actuador, que sube y baja con la placa soporte, de modo que sirven para los dos formatos sin moverlos y ninguno lleva cable sobre el carro.
>
> Además de la válvula del carro, Y-rápido e Y-formato, el obturador tiene su propia electroválvula monoestable, con reposo en cerrado: abre junto con el avance del pistón y cierra al terminar la inyección, antes de la subida rápida.
>
> **Tabla [auto: 35].** Sensores del cabezal de llenado
>
> | **Sensor** | **Tipo** | **Ubicación** | **Función** |
> | --- | --- | --- | --- |
> | Carro arriba | Detector de estado sólido SMC D-M9 | Tubo del CJ2X, final de la carrera de retroceso | Lanza fuera del envase |
> | Carro abajo | Detector de estado sólido SMC D-M9 | Tubo del CJ2X, final de la carrera de avance | Lanza abajo; condición para dosificar |
> | Fin de subida lenta | Detector de estado sólido SMC D-M9 | Tubo del CJ2X, a 88 mm del final de avance | Calibración y vigilancia de la velocidad de subida |
> | Pulsador de parada de llenado | Pulsador | Frente del montante opuesto a la manguera | Parada del operario |
>
> ### **Tiempos del ciclo**
>
> La Figura 70 muestra la secuencia para 250 ml, el caso más exigente (ciclo de 15 s, Sección 3.2). El carro baja 150 mm a 100 mm/s en 1,5 s. La lanza sube lento durante la inyección y el cierre del obturador, y después hace la subida rápida de los 62 mm restantes en 0,62 s. El obturador abre y cierra sus 45 mm en 0,15 s, y la apertura se superpone con el inicio de la inyección (Tabla 36).
>
> [IMAGEN: la que precede a «**Figura 61.** Diagrama de tiempos del cabezal de llenado» en seccion17.md]
>
> **Figura [auto: 70].** Diagrama de tiempos del cabezal de llenado para el envase de 250 ml
>
> **Tabla [auto: 36].** Tiempos del cabezal de llenado
>
> | **Etapa** | **250 ml (s)** | **500 ml (s)** |
> | --- | --- | --- |
> | Bajada del carro (150 mm a 100 mm/s) | 1,5 | 1,5 |
> | Inyección, con la apertura del obturador en sus primeros 0,15 s y la lanza subiendo (Sección 3.2) | 5,0 | 10,0 |
> | Cierre del obturador, con la lanza subiendo | 0,15 | 0,15 |
> | Subida rápida (62 mm a 100 mm/s) | 0,62 | 0,62 |
> | **Ocupación del cabezal** | **7,27** | **12,27** |
> | Ciclo disponible (Sección 3.2) | 15 | 30 |
> | **Tiempo libre para la cinta** | **7,73** | **17,73** |
>
> La aspiración (2,5 s para 250 ml y 5 s para 500 ml, Sección 3.2) ocurre con la lanza saliendo y arriba, en paralelo con el cambio de envase. Las conmutaciones de la válvula y de las electroválvulas quedan dentro del tiempo libre para la cinta.
>
> ## **19.9 Piezas del cabezal de llenado**
>
> La Tabla 37 resume las piezas del cabezal de llenado, con su material, su fabricación y su función. Las piezas de la boquilla están en la Tabla 4, y la manguera y sus uniones, en la Tabla 22.
>
> **Tabla [auto: 37].** Piezas del cabezal de llenado
>
> | **Pieza** | **Cant.** | **Material / especificación** | **Fabricación** | **Función** |
> | --- | --- | --- | --- | --- |
> | Actuador del obturador | 1 | SMC CJ5-S Ø10 × 45, doble efecto, SUS304, juntas de FKM [94] | Comercial | Abre y cierra el obturador |
> | Soporte de la boquilla | 1 | AISI 304: ala, puente y abrazadera partida mecanizada al diámetro exterior de la T | Mecanizado; las dos mitades de la abrazadera se cortan de una misma pieza | Une la T al carro e impide su giro |
> | Tornillos del soporte | 4 | M5, acero inoxidable A2-70 | Comerciales | Fijan el ala al carro y cierran la abrazadera |
> | Carro | 1 | Chapa de SAE 1010 laminada en caliente de 190 × 80 × 6,35 mm [61], galvanizada | Corte; agujeros de Ø22 y Ø20 mm; roscas M4 y M5; galvanizado con la bancada | Lleva la boquilla en la carrera vertical |
> | Placa soporte | 1 | Chapa de SAE 1010 laminada en caliente de 190 × 80 × 6,35 mm [61], galvanizada | Corte; agujeros de Ø22 mm; roscas M4 y M5; galvanizado con la bancada | Lleva el actuador del carro, los reguladores y la tuerca; fija la altura del cabezal |
> | Bujes con brida | 4 | igus drylin R FJUM-01-12, aluminio anodizado y liner de iglidur J [97] | Comerciales | Deslizamiento del carro y de la placa soporte sobre las guías |
> | Tornillos de los bujes | [completar: cantidad] | M4 [completar: norma, largo y material] | Comerciales | Fijan las bridas de los bujes |
> | Actuador del carro | 1 | SMC CDJ2X Ø16 × 150, con imán y brida delantera [98], [100] | Comercial | Baja y sube el carro |
> | Tornillos de la brida del actuador | 2 | M5 [100] [completar: norma, largo y material] | Comerciales | Fijan el actuador a la placa soporte |
> | Unión flotante | 1 | SMC JA15-5-080, M5 × 0,8 [101] | Comercial | Une el vástago del actuador con el carro; absorbe excentricidad y desalineamiento |
> | Reguladores de baja velocidad A y B | 2 | SMC, con antirretorno, área efectiva controlada de 0,1 a 0,6 mm² [100] | Comerciales | Velocidad de subida lenta de cada formato |
> | Regulador doble de baja velocidad | 1 | SMC [100] | Comercial | Regula la entrada en la subida y la salida en la bajada |
> | Electroválvulas del cabezal | 4 | Válvula del carro; Y-rápido, 2/2 normal cerrada; Y-formato, 3/2; del obturador, monoestable con reposo en cerrado. Modelos a definir con el circuito neumático (Tabla 38) | Comerciales | Mando del carro, de sus velocidades y del obturador |
> | Detectores | 3 | SMC D-M9, de estado sólido, en montaje con banda [100] | Comerciales | Carro arriba, carro abajo y fin de subida lenta |
> | Pulsador de parada de llenado | 1 | [completar: modelo] | Comercial | Parada del operario |
> | Husillo | 1 | Tr16 × 4 de una entrada, acero inoxidable 1.4301 [103]; largo [completar] | Corte a medida; extremo superior torneado a Ø10 h9 con chavetero y agujero roscado M4 | Regula la altura del cabezal |
> | Tuerca del husillo | 1 | igus drylin, iglidur J, para Tr16 × 4 [104] | Comercial | Une el husillo con la placa soporte |
> | Volante | 1 | Elesa VRTP.80 A-10-K, Ø80 mm, tecnopolímero, sin manija [87] | Comercial | Gira el husillo en el cambio de formato |
> | Chaveta del volante | 1 | DIN 6885 A 3 × 3 × 14 | Comercial | Transmite el giro del volante al husillo |
> | Arandela de retención y tornillo del volante | 1 + 1 | GN 184.5-20 inoxidable; DIN 7991 M4 A2 [88] | Comerciales | Retienen el volante sobre el husillo |
> | Arandelas del husillo | 2 | Acero inoxidable [completar: medida] | Comerciales | Apoyo del cubo del volante y del escalón del husillo en la placa superior |
> | Traba | 1 | Buje partido con palanca [completar: material o modelo] | [completar] | Traba la placa soporte sobre una guía |
> | Regla graduada e índice | 1 + 1 | Regla en milímetros [completar: material] | [completar] | Repetir la altura de cada formato |
> | Guías | 2 | Barra de SAE 1010 de Ø12 × 458 mm | Corte; soldadas al tubo delantero; galvanizadas con la bancada | Guían el carro y la placa soporte |
> | Montantes | 2 | Tubo de 25 × 25 × 1,25 mm [52], 421,7 mm, con tapón roscado M6 | Corte; soldados al tubo delantero; galvanizados con la bancada | Sostienen la placa superior |
> | Placa superior | 1 | Chapa de SAE 1010 de 250 × 40 × 6,35 mm [61], agujero de Ø10,5 mm | Corte y agujereado | Apoyo del husillo; une los montantes |
> | Tornillos de la placa superior | 2 | M6 clase 4.8, zincados (Sección 17.1) | Comerciales | Fijan la placa superior a los montantes |

### SECCIÓN 20 (ex 19, verificación de la bancada)

**C51**
- **Ubicación:** Ancla: «19. Verificación estructural de la bancada» (el título de la sección, no la línea del índice).
- **Acción:** REEMPLAZAR
- **Texto final:** 20. Verificación estructural de la bancada

**C52**
- **Ubicación:** Primera frase de la sección. Ancla: «y el peso de la tolva llena sobre su soporte (Sección 18.2).»
- **Acción:** REEMPLAZAR
- **Texto final:** el peso de la tolva llena sobre su soporte (Sección 18.2) y el del cabezal de llenado sobre el tubo delantero (Sección 19).

**C53**
- **Ubicación:** Última frase de la sección. Ancla: «sus resultados deben actualizarse con el perfil definitivo (Sección 21)»
- **Acción:** REEMPLAZAR
- **Texto final:** sus resultados deben actualizarse con el perfil definitivo (Sección 22)

### SECCIÓN 21 (ex 20, fuentes)

**C54**
- **Ubicación:** Ancla: «20. Fuentes técnicas consultadas» (el título de la sección).
- **Acción:** REEMPLAZAR
- **Texto final:** 21. Fuentes técnicas consultadas

**C55**
- **Ubicación:** Frase inicial. Ancla: «caja de soporte y soporte de la tolva).»
- **Acción:** REEMPLAZAR
- **Texto final:** caja de soporte, soporte de la tolva y cabezal de llenado).

**C56**
- **Ubicación:** Lista de fuentes y todo el texto del informe que no se reemplaza con este archivo.
- **Acción:** REEMPLAZAR números de cita. Se elimina el salto de la lista ([52] a [54] no existen): cada fuente desde la [55] hasta la [92] baja 3 números, tanto en la lista como en todas sus citas del texto.
- **Texto final:** [55] → [52], [56] → [53], [57] → [54], …, [91] → [88], [92] → [89]. Las fuentes [1] a [51] no cambian. **Hacer los reemplazos en orden creciente**, de la [55] a la [92], para no pisar números ya cambiados. No aplicarlo a los textos de este archivo, que ya llevan la numeración final.

**C57**
- **Ubicación:** **Después** de la última fuente de la lista, la que empieza con «[92] Ternium» (pasa a ser [89] con el cambio de renumeración de esta misma sección).
- **Acción:** AGREGAR. El título "Fuentes técnicas consultadas (continuación)" de seccion17.md **no** se agrega.
- **Texto final:**

> [90] Patente US5137187, "Anti-spray fluid dispensing nozzle", P. Nichols y R. Lapointe, 1992 (dos válvulas en el conducto de alimentación, accionadas por un vástago que corre por dentro del conducto; la válvula inferior cierra la salida desde adentro, contra un asiento en el extremo de descarga). https://patents.google.com/patent/US5137187A/en
>
> [91] Hydraulic Megastore, "150lb Stainless Steel Fittings" (accesorios roscados de fundición de acero inoxidable CF8M (316); roscas según ISO 7-1, hembra paralela y macho cónico; T igual de 1": A = 38 mm y 0,256 kg; niple hexagonal de 1": 48 mm de largo, 18,5 mm de rosca y 11 mm de hexágono; presión máxima de trabajo de 20 bar entre −20 y 40 °C). https://www.hydraulicmegastore.com/wp-content/uploads/2015/04/150lb-Stainless-Steel-Fittings.pdf
>
> [92] Anzor, "1" BSP 316 Hex Nipple (NB25)" (accesorios roscados de 150 lb; material según ASTM A276 304 y ASTM A351 CF8 (304) o CF8M (316)). Fuente comercial. https://anzor.co.nz/bsp-npt-fittings/bsp-nipples/hex-nipple/1-bsp-316-hex-nipple-nb25
>
> [93] Anti-Seize Technology, "Low Density PTFE Thread Seal Tape", serie 26100 (100 % PTFE virgen; conforme a 21 CFR 177.1550; de −240 a +260 °C; apta para agua, productos químicos, etanol y solventes). https://res.cloudinary.com/tacoma-screw-products/image/upload/Documents/618-301_tds.pdf
>
> [94] SMC Corporation of America, catálogo "Series CJ5-S Ø10, Ø16 Stainless Steel Cylinder" (carreras estándar del Ø10: 15, 30, 45, 60, 75, 100, 125 y 150 mm; presión de trabajo de 0,1 a 0,7 MPa; velocidad del pistón de 50 a 750 mm/s; energía cinética admisible de 0,035 J para el Ø10; masa básica de 52 g más 4 g cada 15 mm de carrera; vástago de 4 mm con rosca M4 × 0,7; rosca de montaje delantera M10 × 1,0; tubo, tapas y vástago de acero inoxidable 304; juntas de NBR o FKM; no admite instalación en la zona de alimentos y sí en la zona de salpicaduras). https://www.smcpneumatics.com/pdfs/CJ5S.pdf
>
> [95] F. M. White, "Fluid Mechanics", McGraw-Hill, Capítulo 6 (flujo laminar completamente desarrollado en conductos no circulares: anillo entre dos cilindros concéntricos).
>
> [96] RS Components, "RS PRO Stainless Steel Circular Tee, 1in G(P) Female" (RS 499-3007; acero inoxidable 316, 150 lb; largo de 2,76 in y diámetro exterior de 1,56 in). Fuente comercial. https://static.chipdip.ru/lib/295/DOC041295755.pdf
>
> [97] igus, "drylin® R flange bearings: closed, anodised aluminium adapter, round flange" (FJUM-01-12: d1 = 12 mm, d2 = 22 mm h7, brida de Ø42 mm con agujeros de 4,5 mm, largo de 32 mm; carga dinámica de 960 N con p = 5 MPa y estática de 6.720 N con p = 35 MPa; masa de 42 g; liner de iglidur® J). https://www.igus.eu/ContentData/Products/Downloads/drylin-r-anodised-aluminium-adapter-FJUM-01.pdf
>
> [98] SMC Corporation of America, "C(D)J2X, Air Cylinder, Double Acting, Single Rod, Low Speed" (diámetros de 10 y 16 mm; carreras de 15, 30, 45, 60, 75, 100, 125, 150, 175 y 200 mm; versión CDJ2X con imán para detectores). https://elasticsearch.smcpneumatics.com/products/Actuators/Specialty-Actuators/Low-Speed-Low-Friction/Low-Speed/CJ2X/CDJ2X-Air-Cylinder-Double-Acting-Single-Rod-Low-Speed~20543
>
> [99] SMC Corporation of America, ficha "CJ2XB16-15Z" (serie CJ2X: tubo y vástago de acero inoxidable; apta para detectores; montajes básico, con pie, con brida y con doble horquilla). Fuente comercial. https://www.smcpneumatics.com/CJ2XB16-15Z.html
>
> [100] SMC, catálogo "Air Cylinder Series CJ2" (serie CJ2X de baja velocidad, Ø10 y Ø16: velocidad del pistón de 1 a 300 mm/s; energía cinética admisible de 0,090 J para el Ø16; fuga interna de hasta 0,1 l/min (ANR) por su construcción; Ø16: vástago de 5 mm con rosca M5 × 0,8, rosca de montaje M10 × 1,0 y estilo con brida delantera con agujeros de 5,5 mm; detectores de estado sólido D-M9 en montaje con banda; para operación vertical, control de velocidad por el escape con control simultáneo de la entrada para reducir el stick-slip, reguladores de baja velocidad lo más cerca posible del cilindro y ausencia de carga lateral; reguladores de baja velocidad serie AS-FM, con área efectiva controlada de 0,1 a 0,6 mm², y reguladores dobles serie ASD; designación CDJ2X□16-carrera, con F para el estilo con brida delantera y sufijo -B para detectores en montaje con banda; serie CJ2 de doble efecto y simple vástago, Ø16: masa básica de 55 g, 6,5 g adicionales cada 15 mm de carrera y 15 g de la brida delantera). https://docs.rs-online.com/e3ae/0900766b814145b3.pdf
>
> [101] SMC Corporation of America, "JA15-5-080" (unión flotante de la serie JA con rosca M5 × 0,8). https://elasticsearch.smcpneumatics.com/JA15-5-080.html
>
> [102] Galvanizers Association, "HDG Datasheet 10: Bimetallic Corrosion", 2024 (corrosión adicional del zinc en contacto con otros metales en ambiente atmosférico rural e industrial o urbano: aluminio, 0 y 0 a 1, nula o muy leve; acero inoxidable, 0 a 1; bronce, 0 a 1 y 1, con aislación recomendada para las aleaciones de cobre). https://wedge-galv.co.uk/wp-content/uploads/2024/10/10-Bimetallic-Corrosion-2024.pdf
>
> [103] igus, "drylin® trapezoidal lead screw, 1.4301 (304) stainless steel" (husillos de acero inoxidable 1.4301 de 8 a 24 mm de diámetro y pasos de 1,5 a 5 mm; los de una entrada son autoblocantes y los de dos entradas no). https://www.igus.com/product/918
>
> [104] igus, "drylin® injection-molded lead screw nuts with flange, JFRM" (tuerca con brida de iglide® J para rosca trapecial). https://www.igus.com/product/14988

  (Copiar las URL de seccion17.md tal cual; acá se quitaron las barras invertidas que el .md agrega antes de "_".)

### SECCIÓN 22 (ex 21, pendientes)

**C58**
- **Ubicación:** Ancla: «21. Información pendiente de relevar o definir (consolidado general)» (el título de la sección).
- **Acción:** REEMPLAZAR
- **Texto final:** 22. Información pendiente de relevar o definir (consolidado general)

**C59**
- **Ubicación:** Tabla de pendientes (queda como Tabla 38), fila que empieza con «| 6.1 | Longitud real de la manguera de conducción».
- **Acción:** REEMPLAZAR la fila.
- **Texto final:**

| 6.1 / 8.1 | Longitud real de la manguera entre la válvula y la boquilla | Se usó 1 m como valor de trabajo; debe medir como máximo 1,15 m (Sección 8.1). | Verificar con el dibujo definitivo de la estación. |

**C60**
- **Ubicación:** Misma tabla, fila que empieza con «| 13.3 / 19 | Actualización del análisis estructural de la bancada».
- **Acción:** REEMPLAZAR la fila.
- **Texto final:**

| 13.3 / 20 | Actualización del análisis estructural de la bancada | El análisis se hizo con pared de 0,035" (0,89 mm), menor que la adoptada (1,25 mm). Faltan además el material asignado, las cargas aplicadas (reacciones de las patas de la caja de soporte, Sección 17.8, y peso del cabezal de llenado sobre el tubo delantero, Sección 19), el voladizo de soporte de la tolva y los tres postes (Sección 18.1). | Repetir el análisis y la lista de cortes (Sección 13.3) con el perfil 25 × 25 × 1,25 mm, incluidos el voladizo y los postes de la tolva y el bastidor del cabezal. |

**C61**
- **Ubicación:** Misma tabla, fila que empieza con «| 14.5 | Altura de la entrada de succión del cilindro dosificador».
- **Acción:** ELIMINAR la fila.

**C62**
- **Ubicación:** Misma tabla, **después** de la fila «| 1 / general | Sistema CIP completo y circuito neumático completo |».
- **Acción:** AGREGAR 3 filas.
- **Texto final:**

| 2 / 3.3 | Referencia de la ficha técnica de los envases | Respalda las cotas de las Figuras 3 y 4 y el cubicaje de la Tabla 1. | Ficha del proveedor de los envases. |
| 3.3 | Tamaño de los *o-rings* de la boquilla | Los *o-rings* de cara, el del obturador y los del vástago quedaron a definir (Tabla 4). | Selección con el catálogo Parker [18]. |
| 3.3 | Altura del domo del fondo de los envases | La altura h de la punta de la lanza se mide desde el punto más alto del domo, cuya altura no se midió. | Medición en los envases; mientras tanto, ajuste con la regulación de altura en la puesta en marcha (Sección 19.6). |

**C63**
- **Ubicación:** Misma tabla, **después** de la última fila («| 18.2 | Verificación de la pared de la tolva junto a las ménsulas |»).
- **Acción:** AGREGAR fila.
- **Texto final:**

| 19.9 | Modelos del pulsador y de las electroválvulas del cabezal, largo del husillo y medidas de la tornillería menor, de las arandelas, de la traba y de la regla | Completan la lista de piezas del cabezal (Tabla 37). | Con el circuito neumático y el dibujo definitivo del cabezal. |

---

## 3. Figuras y tablas: numeración final

Las referencias escritas a mano en el texto original que no se reemplaza ("Figura N", "Tabla N", "Figuras N y M") se cambian según estas tablas.

### Figuras

| Origen | Número anterior | Número final | Descripción |
| --- | --- | --- | --- |
| Ra3v8 | 1 y 2 | 1 y 2 | Sin cambio |
| seccion17 | 43 | 3 | Envase de 250 ml |
| seccion17 | 44 | 4 | Envase de 500 ml |
| seccion17 | 47 | 5 | Boquilla abierta y cerrada |
| seccion17 | 48 | 6 | Despiece de la boquilla |
| seccion17 | 49 | 7 | Lanza dentro del envase |
| seccion17 | 50 | 8 | Manguera de PVC cristal en la máquina actual |
| Ra3v8 | 3 | 9 | Simple y doble efecto |
| seccion17 | 51 | 10 | Tramos de pérdida de carga de la boquilla |
| Ra3v8 | 4 | 11 | Tramos del circuito de inyección y perfil de presión |
| Ra3v8 | 5 | 13 | Tensión crítica de pandeo en función de la esbeltez (se corre por el cambio de 7.1) |
| Ra3v8 | 6 | 12 | Columna de pandeo de los dos vástagos (se mueve en 7.1) |
| Ra3v8 | 7 a 43 | 14 a 50 | Todas +7 (por ejemplo, Goodman de la caja 41 → 48; pata de la caja 43 → 50) |
| Ra3v8 | 49 | 51 | Soporte de la tolva: ménsulas, postes y voladizo (se mueve al comienzo de 18.1) |
| Ra3v8 | 44 a 48 | 52 a 56 | Ubicación de la ménsula, ménsula en ángulo, unión del poste, placa base y voladizo de la bancada |
| Ra3v8 | 50 a 52 | 57 a 59 | Pandeo del poste, ala de la ménsula y placas del poste |
| seccion17 | 45 | 60 | Cabezal sobre la bancada |
| seccion17 | 46 | 61 | Secuencia de llenado |
| seccion17 | 53 | 62 | Obturador |
| seccion17 | 55 | 63 | Punta de la lanza y nivel del producto |
| seccion17 | 54 | 64 | Carro y soporte de la boquilla |
| seccion17 | 57 | 65 | Cargas sobre las guías |
| seccion17 | 56 | 66 | Circuito neumático del actuador del carro |
| seccion17 | 58 | 67 | Apoyo del husillo |
| seccion17 | 59 | 68 | Detalle del bastidor |
| seccion17 | 60 | 69 | Modelos de verificación del bastidor |
| seccion17 | 61 | 70 | Diagrama de tiempos |
| seccion17 | 52 | — | Eliminada (CS en función del largo de la manguera) |
| Ra3v8 | 53, 54 y 55 | 71, 72 y 73 | Bancada (desplazamiento y von Mises) |

### Tablas

| Origen | Número anterior | Número final | Descripción |
| --- | --- | --- | --- |
| Ra3v8 | 1 a 3 | 1 a 3 | Sin cambio |
| seccion17 | 27 | 4 | Componentes de la boquilla |
| Ra3v8 | 4 | 5 | Matriz de decisión del accionamiento |
| Ra3v8 | 5 | 6 | Carrera por diámetro |
| seccion17 | 28 | 7 | Pérdida de carga en la boquilla abierta |
| Ra3v8 | 6 a 27 | 8 a 29 | Todas +2 (por ejemplo, fuerza de resistencia 6 → 8; selección CP96 7 → 9; Tabla 20 de uniones → 22; Tabla 22 de piezas del ajuste → 24; espesores de la pared delantera 25 → 27; fatiga de la caja 26 → 28; pesos de la caja 27 → 29) |
| seccion17 | 30 | 30 | Verificación del actuador del obturador |
| seccion17 | 31 | 31 | Masa del conjunto móvil |
| seccion17 | 33 | 32 | Verificación de las guías |
| seccion17 | 32 | 33 | Verificación del actuador del carro |
| seccion17 | 34 | 34 | Verificación del bastidor |
| seccion17 | 35 | 35 | Sensores del cabezal |
| seccion17 | 36 | 36 | Tiempos del cabezal |
| nueva | — | 37 | Piezas del cabezal de llenado |
| seccion17 | 29 | — | Eliminada (CS según la manguera) |
| Ra3v8 | 28 | 38 | Pendientes |

---

## 4. Cálculos nuevos o recalculados

Todos se rehicieron con un script. Al final de cada bloque se indica dónde difieren de tus valores.

### 4.1 Pérdida de carga (6.1)

- Tramos de la boquilla, con μ = 5 Pa·s y Q = 50 × 10⁻⁶ m³/s: 847 + 2.819 + 1.288 + 819 + 1.355 + 126 + 869 + 26.182 + 6 = **34.311 Pa**. Coinciden todos los tramos. Los tramos 3 a 9 suman 30.645 Pa. La lanza es el 76,3 % del total.
- Manguera de 1¼”: 128 × 5 × 1 × 50 × 10⁻⁶ / (π × 0,03175⁴) = **10.024 Pa/m**. La de 1”, 24.472 Pa/m.
- ΔPtotal = 34.311 + 10.024 = **44.335 Pa**. Con la manguera de 1”: 34.311 + 24.472 = 58.783 Pa.
- Reynolds, Re = ρ·v·d/μ con ρ = 1.100 kg/m³. En la lanza, v = Q / (π·0,01448²/4) = 0,304 m/s, de donde Re = 1.100 × 0,304 × 0,01448 / 5 = **0,97 ≈ 1,0**. En la manguera de 1¼”, v = 0,0632 m/s y Re = **0,44**. Los anillos dan valores menores (0,47 en el anillo de la T y 0,70 en el asiento).
- Tabla 8: F = ΔPtotal × A, con las áreas redondeadas de la tabla, y Fmín = 3 × F. Resulta 55,7 / 167,2; 87,0 / 261,1; 138,2 / 414,6; 222,9 / 668,6; 348,2 / 1.044,6. **Coincide con tus valores.**
- Comparación con la Tabla 9: Ø32 (442 N) ≥ 167,2, 261,1 y 414,6 → sin cambio. Ø32 < 668,6 ≤ Ø40 (692 N) → sin cambio. Ø40 < 1.044,6 ≤ Ø50 (1.080 N) → sin cambio. **Ningún candidato cambia de actuador.** Los márgenes de los candidatos de 63, 80 y 100 mm quedan entre el 3 y el 7 % (ver duda D1).

### 4.2 Largo máximo (8.1)

Factuador / (CS × A) = 692 / (3 × 5.027) = 0,045886 MPa = 45.886 Pa. Lmáx = (45.886 − 34.311) / 10.024 = **1,155 ≈ 1,15 m**. Con 1 m: F = 0,044335 × 5.027 = 222,9 N y CS = 692 / 222,9 = **3,10**. Con la manguera de 1” daría 0,47 m.

### 4.3 Masas del cabezal (19.4 y 19.6)

- γ / g = 76.500 / 9,81 = 7.798 kg/m³.
- Carro de 6,35 mm: (190 × 80 − 2·π·11² − π·10²) × 6,35 × 7,798 × 10⁻⁶ = **0,700 kg**. Se descuentan los dos agujeros de Ø22 y el de Ø20, igual que en el valor anterior de 1,399 kg a 12,70 mm.
- Conjunto móvil: 3,290 − 1,399 + 0,700 = **2,591 kg**; W = **25,4 N**.
- Grupo de la boquilla: 2,591 − 0,700 − 0,084 = **1,807 kg → 17,7 N**.
- Placa soporte de 6,35 mm: (190 × 80 − 2·π·11²) × 6,35 × 7,798 × 10⁻⁶ = **0,715 kg**. Se descuentan solo los agujeros de los bujes, porque no hay cotas de los agujeros del actuador ni de la tuerca; queda del lado seguro.
- Actuador CDJ2X Ø16 × 150 con brida: 55 + 6,5 × 150/15 + 15 = **135 g**. Son los valores de la tabla de masas de la serie CJ2 Ø16 del catálogo [100] (la [96] de seccion17.md), porque las páginas de la CJ2X no traen tabla de masas (ver duda D3).
- Cabezal regulado: 2,591 + 0,715 + 0,084 + 0,135 = **3,525 kg → 34,6 N**. Antes figuraba 49,0 N sin cálculo. Con las piezas de 12,70 mm, la misma suma da 4,94 kg (48,5 N), así que el 49,0 N anterior era probablemente este mismo conjunto con las chapas viejas.
- No se incluyeron los reguladores, la tuerca JFRM, los detectores ni las mangueras de aire: no encontré sus masas en un catálogo citable. Un listado comercial de distribuidor da unos 7 g para un AS1201FM-M5, pero no pude abrir la página para verificarlo, así que no se usa.

### 4.4 Guías y carro (19.4 y 19.5)

- Carro colgado: √(35² + 115²) = 120,2 mm; M = 25,4 × 120,2 = **3.053 N·mm**; Fextremo = 3 × (3.053/2) / (2 × 32) = **71,6 N**.
- Placa soporte: M = 25,4 × 78,3 = **1.989 N·mm**; Fextremo = **46,6 N**.
- Guía: σ = 32 × (995 + 1.527) / (π × 12³) = **14,9 MPa**; CS = 180/14,9 = **12,1**.
- Para comparar: el centro de masa real del conjunto queda a unos 52 mm por delante de las guías (carro a −15 mm, bujes a 0 y grupo de la boquilla a +80 mm). Tomarlo a 80 mm queda del lado seguro.
- Factor de carga: 25,4 / 99,8 = **0,25**. Energía: ½ × 2,591 × 0,1² = **0,013 J**.
- Flexión del carro: M = 110,6 × 80 = 8.848 ≈ **8.850 N·mm**; S = 126 × 6,35² / 6 = 846,8 mm³; σ = **10,4 MPa**; CS = **17,2**.
- **Coinciden todos tus números.**

### 4.5 Bastidor (19.7)

σ = 0,917 × 1.416 / (2 × 895,6) + 34,6 / (2 × 118,75) = 0,725 + 0,146 = **0,87 MPa** (antes 0,93 MPa). Rigidez y placa superior sin cambio: θ = 1.416 × 428 / (200.000 × 24.426) = 1,24 × 10⁻⁴ rad, δ = 0,071 mm, σ = 28,3 MPa y CS = 6,4.

### 4.6 Bancada (13.3)

15.631,1 + 2 × 421,7 = **16.474,5 mm** en 25 piezas. Barra 1: 5.219,4 + 421,7 = 5.641,1 mm (sobrante 358,9 mm). Barra 2: 5.210,7 + 421,7 = 5.632,4 mm (sobrante 367,6 mm).

### 4.7 Tolva (14.5)

Hdisponible = 1.900 − (1.090 + 75) = 735 mm. Con V = 66 L, cono a 60° y d = 25,4 mm: Hcono = (D − d)/2 × tan 60°, Vcono = π·Hcono/12 × (D² + D·d + d²) y Hcil = (V − Vcono) / (π·D²/4). Resolviendo Hcono + Hcil = 735 mm por bisección se obtiene **D = 399,6 mm**, con Hcono = 324,1 mm, Hcil = 410,9 mm y altura total de 735,0 mm. Para D = 400 mm no cambia nada (324,4 + 409,8 = 734,2 mm), por lo que tampoco cambian 14.7 ni la 18.

### 4.8 Caja de soporte (17.2 a 17.7)

Se aplica el método del informe con el factor 222,9 / 692 = 0,3221. El script reproduce los valores anteriores con 171,4 N: 10,21 / 9,22 / 9,75 / 9,56 mm (el informe dice 9,57) y 14,98 / 14,43 / 2,35 mm.

- **Pared delantera** (tdel = 12,7 mm: A = 498,6 mm², yc = 5,27 mm, I = 4.918 mm⁴, Kf = 1,88). Miny,f = 37.195 × 0,3221 = 11.981 N·mm.
  - Cara exterior del borde del puerto: σiny = 11.981 × 5,27 / 4.918 = +12,84; σasp = −15,25. σa = 1,88 × 28,09 / 2 = 26,4; σm = −2,3 → 0; CS = 113,9 / 26,4 = **4,31**.
  - Fondo del rebaje: σiny = −10,79; σasp = +12,82. σa = 22,2; σm = 1,9; CS = **4,97**.
  - Franjas: σiny = −18,10; σasp = +21,50. σa = 19,8; σm = 1,7; CS = **5,58**.
  - Raíz del voladizo: la tensión local de la precarga es 6 × 1.508 × 4 / (13,62 × 9,7²) = 28,24, y la flexión global de inyección, 6 × 20.414 × 0,3221 / (93,4 × 12,7²) = 2,62, de donde σmín = **25,6**. σmáx = 33,69 + 5,67 = **39,4**. σa = 6,9; σm = 32,5; CS = 1 / (6,9/113,9 + 32,5/320) = **6,18**.
  - Espesores mínimos por fatiga (bisección, CS = 3): **10,75 / 9,60 / 10,01 / 9,59 mm**, todos menores que 12,7 mm.
- **Pared del actuador** (t = 15,875 mm, Se = 112,6 MPa).
  - Agujero de Ø36: σiny = 6 × 30.621 × 0,3221 / (64 × 15,875²) = +3,67; σtope = −28,64; Kf = 2,16; σa = 34,9; CS = **3,22**.
  - Agujero de la guía: σiny = +2,00; σtope = −27,36; Kf = 2,22; σa = 32,6; CS = **3,46**.
  - Espesores mínimos (con kb variable): **15,21 y 14,57 mm**, menores que 15,875 mm.
- **Pestañas**: σiny = 66,43 × 0,3221 = +21,40; σasp = −50,72; σa = 36,1; CS = **3,16**. Espesor mínimo: t² = 3 × (133,7 + 317,0) / 2 / 113,9 → t = **2,44 mm**, mayor que 2,40 mm. Lo define la fatiga y se mantienen los 2,5 mm.

**Diferencias con tus valores** (todas en el primer decimal; usé los míos):
- cara exterior: σiny 12,8 (no 12,9), σa 26,4 (no 26,5) y CS 4,31 (no 4,30);
- fondo del rebaje: CS 4,97 (no 4,99);
- raíz del voladizo: CS 6,18 (no 6,17);
- agujero de Ø36: σiny 3,7 (no 3,6), σa 34,9 (no 34,8) y CS 3,22 (no 3,23);
- pestañas: σiny 21,4 (no 21,5);
- espesores de 17.3: 10,75 / 9,60 / 10,01 / 9,59 (no 10,8 / 9,5 / 10,1 / 9,6).

En la columna σm conservé el formato del informe ("−27,0 → 0").

---

## 5. Figuras que hay que rehacer o editar

| Figura (número final) | Qué cambia |
| --- | --- |
| **11** (ex 4), tramos del circuito y perfil de presión | Rehacer. Los tramos pasan a ser: boquilla de la Sección 3.3 (34.311 Pa, con la lanza como escalón principal de 26.182 Pa) y manguera de 1¼” de 1 m (10.024 Pa). Total: 44.335 Pa = 0,0443 MPa (antes 0,0341). Eliminar el tramo "boquilla 12,75 × 25 mm" y el diámetro de 1” de la manguera de inyección. |
| **48** (ex 41), Goodman de la caja | Rehacer con los puntos de la Tabla 28 nueva (σm, σa): (0; 26,4), (1,9; 22,2), (1,7; 19,8), (32,5; 6,9), (0; 34,9), (0; 32,6) y (0; 36,1). El punto más cercano a la recta de CS = 3 pasa a ser el de las pestañas. |
| **10** (ex 51), tramos de la boquilla | Si el panel (d) es el modelo de flujo radial de la salida contra el fondo, eliminarlo, porque se borró su fórmula; el título nuevo ya dice "(b) y (c)". Si (d) es otro tramo no circular, conservarlo y volver a "(b), (c) y (d)" en el título. |
| **64** (ex 54), carro y soporte | Espesor del carro de 12,70 a **6,35 mm**. Agregar a la figura, si no están, las cotas que salieron del texto: puente de 30 × 12 mm; abrazadera de 12 mm de alto y 6 mm de pared; orejas de 6 × 11 mm que bajan 17 mm; tornillos del ala a 10 mm del borde delantero; tornillos de la tapa separados 54 mm; eje de la boquilla 55 mm por delante del borde del carro; guías a 25 mm del borde; brida de Ø42 a 4 mm de los bordes y 5 mm por lado entre el carro y los montantes. |
| **65** (ex 57), cargas sobre las guías | Panel (a): el centro de masa pasa del plano medio (38,8 mm por delante; brazo de 73,8 mm) al **eje de la boquilla, 80 mm por delante**, con brazo de **115 mm** en la dirección de avance y distancia de **120,2 mm**. Peso de 32,3 a **25,4 N** si está acotado. |
| **60** (ex 45), cabezal sobre la bancada | Si están acotados, espesores del carro y de la placa soporte de 12,70 a 6,35 mm. Revisar que la vista lateral muestre la tuerca del husillo en el plano de las guías, como dice 19.1. |
| **69** (ex 60), modelos del bastidor | Si figura la carga del cabezal regulado, cambiar 49,0 N por **34,6 N**. |
| **67** (ex 58), apoyo del husillo | Reemplazar el volante Halder y el pasador elástico por el volante Elesa VRTP.80 sin manija, con la chaveta DIN 6885 A 3 × 3 × 14 y la arandela GN 184.5-20 con su tornillo DIN 7991 M4 apoyada en la punta del husillo. Mostrar el extremo torneado a Ø10 h9 con chavetero y el pequeño juego axial entre la arandela GN y el buje del volante. |
| **61, 62, 66, 68, 70** | Sin cambios de valores. Solo cambia "Pico arriba / Pico abajo" por "Carro arriba / Carro abajo" donde aparezca (sobre todo en 66 y 70). |
| **25** (ex 18), alzado de la tolva | Entrada de succión de 1.000 → **1.165 mm**; boca de carga de 1.734 → **1.899 mm**; altura disponible de 900 → **735 mm** si está acotada. Si se quiere, acotar la bancada a 1.090 mm. |
| **17**, bancada | Opcional: no muestra los montantes del cabezal (ítem 14 de la lista de cortes). |

---

## 6. [completar], decisiones aplicadas y estilo

### [completar] que quedan en el informe

1. Referencia de la ficha del proveedor de los envases (Tabla 1 y Sección 3.3, cambios C8 y C11).
2. Imágenes de las filas nuevas de la Tabla 22 (adaptador R 1 × Tri-Clamp y cinta de PTFE).
3. En la Tabla 37: cantidad y especificación de los tornillos M4 de los bujes y M5 de la brida, modelo del pulsador, largo del husillo, medida de las arandelas del husillo y material o modelo de la traba y de la regla. Quedan cubiertos por la fila nueva de pendientes de la Sección 19.9.
4. Fuente del adaptador Tri-Clamp × espiga de 1¼” (la [66] es de 1”). Si la conseguís, se agrega como [105] en la fila correspondiente de la Tabla 22.

### Decisiones de esta versión (ya incluidas en los cambios)

- La boquilla queda como 3.3, y la Sección 3 pasa a llamarse "Cadencia de llenado y boquilla".
- La 14.5 se calcula directamente con la bancada a 1.090 mm. El diámetro mínimo pasa a 399,6 mm, se mantiene D = 400 mm y desaparecen la estimación de 1.000 mm y el margen de 165,8 mm.
- La frase de 3.2 sobre el tiempo libre ahora incluye los movimientos del cabezal y remite a la 19.8. La Figura 2 no cambia.
- En 3.3 se agrega una frase que presenta el carro y el cabezal, y se elimina la frase de "holgura similar".
- En 8.1, «verifican holgadamente» pasa a «verifican».
- La cinta se presenta en una sola línea en la 19.1, como dato del diseño de la cinta, a cargo de otra etapa del proyecto.
- El título de 15.3 pasa a ser "Uniones de la válvula de tres vías y de las mangueras".
- El husillo usa el volante Elesa del ajuste de carrera, retenido con la arandela GN apoyada en la punta y un pequeño juego axial. Se elimina la fuente Halder, así que las nuevas quedan de la [90] a la [104].
- Se eliminan las cuentas de vueltas del volante del husillo. En 16.3 se mantiene la frase de 10,05 ml por vuelta del tornillo de tope, porque el texto la usa para la corrección fina.
- El actuador del carro es el CDJ2XF16-150-B. Los detectores se nombran "SMC D-M9", como en el resto del informe, sin datos eléctricos.

### Remisiones hacia secciones posteriores que quedan

Son remisiones de texto, sin datos que el lector necesite antes:
- 3.2 → 19.8 (secuencia del cabezal);
- 3.3 → 19 y 19.2 (cabezal y actuador del obturador), 19.6 (ajuste por el domo) y 15.3 (Tabla 22, uniones);
- 19.4 → 19.5 y 19.7 (resistencia del carro y espesor de la placa superior).

La única que trae un número es la de **14.5 → 17.9**, por los 75 mm entre la bancada y el eje, y queda explicada en el texto.

### Problemas de estilo del informe original (no aplicados)

1. **Juntas.** El informe usa *o-ring*, en cursiva, 29 veces, y la sección nueva dice "junta tórica" (Tabla 4, Tabla 37 y pendientes). Conviene unificar en *o-ring* en los textos nuevos.
2. **Comillas de pulgada.** El informe usa ” (1”). En las fuentes [91] y [92] quedan comillas rectas (1"), copiadas del título del proveedor; se pueden dejar porque son citas textuales.
3. **Fuentes [52] a [54].** Resuelto: se renumera la lista (cambio de la Sección 21).
4. **Orden de las figuras.** Resuelto en 18.1 y también en 7.1, donde la columna de pandeo se citaba antes que la curva de Euler. Quedan dos casos menores en los que el título de la figura aparece antes de su primera cita: el Goodman de la caja (17.7) y las tres figuras de la bancada (20). Se pueden dejar.
5. **"Fuente comercial."** Aparece en 13 fuentes, pero no en todas las que son comerciales (por ejemplo, [50] y [46]). Conviene aplicarlo a todas o a ninguna.
6. **Sección 20.** Mantiene dos [completar] (material y cargas del modelo). Con el cabezal, la lista de cargas crece, así que conviene completarla junto con el análisis.
7. **Párrafos largos.** Los de 5.1, 6.3, 7.1 y 14.2 superan las 6 líneas y mezclan justificación y resultado. Están en el estilo general del informe, así que no los tocaría salvo que quieras acortar.
