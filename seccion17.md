# **17. Cabezal de llenado**

El cabezal de llenado recibe el producto de la válvula de tres vías y lo deposita en el envase. Está formado por la boquilla con cierre positivo, la lanza, la manguera, el carro vertical, la regulación de altura, el bastidor y los sensores.

Los dos envases son de PET; las Figuras 43 y 44 muestran sus medidas según la ficha del proveedor. El concepto de cierre, un vástago que corre por dentro del conducto y cierra la salida desde adentro, se tomó de la patente US5137187 [86]. Las medidas surgen de los requisitos y de los cálculos de esta sección.

![](data:image/png;base64...)

**Figura 43.** Envase de 250 ml (cotas en mm según la ficha del proveedor; forma del hombro, del cuello y del domo esquemática)

![](data:image/png;base64...)

**Figura 44.** Envase de 500 ml (cotas en mm según la ficha del proveedor; forma del hombro, del cuello y del domo esquemática)

El cabezal se monta sobre el tubo delantero de la bancada (Figura 45):

* Dos guías de Ø12 mm y dos montantes de tubo se sueldan al tubo, y una placa superior une sus extremos.
* Sobre las guías deslizan la placa soporte, que se fija a la altura de cada formato con un husillo, y el carro, que sube y baja en cada ciclo.
* El actuador del carro va sobre la placa soporte, 35 mm detrás del plano de las guías. El carro lleva la boquilla 80 mm por delante de ellas.

Así, solo la boquilla, la lanza y el envase quedan por delante del tubo.

La cinta transportadora está a 925 mm del piso. La bancada se fija en 1.090 mm, la máxima que admite la tolva: con el eje del cilindro dosificador 75 mm por encima (Sección 16.10), su boca de carga queda a 1.899 mm, dentro del límite de 1.900 mm (Sección 14.5). Con esta altura, la cinta queda 165 mm por debajo de la cara superior del tubo delantero, y la boca del envase de 250 ml, 37 mm.

![](data:image/png;base64...)

**Figura 45.** Cabezal de llenado sobre la bancada: (a) vista frontal; (b) vista lateral (cotas en mm, esquema sin escala)

El ciclo tiene cuatro etapas (Figura 46):

* **Bajada:** con el envase detenido bajo la boquilla, el carro baja y la lanza entra hasta cerca del fondo.
* **Llenado:** el obturador abre y el pistón inyecta. Mientras el envase se llena, la lanza sube lentamente sin salir de él.
* **Cierre:** al terminar la inyección, el obturador cierra y aspira la gota de la punta.
* **Subida:** la lanza sale rápido, la válvula conmuta hacia la tolva y el pistón aspira mientras la cinta cambia el envase.

![](data:image/png;base64...)

**Figura 46.** Secuencia de llenado: (a) llega el envase; (b) baja el cabezal; (c) llenado con la lanza subiendo; (d) cierra el obturador; (e) sube el cabezal y sale el envase (esquema sin escala)

Para cambiar de formato, el volante sube o baja la placa soporte 49 mm y una traba la fija en su lugar. La lanza es la misma para los dos formatos; solo cambia la velocidad de subida, que el PLC elige según el formato seleccionado.

## **17.1 Boquilla con cierre positivo**

La boquilla se arma sobre una T roscada de 1", el diámetro del circuito (Sección 12.2), con piezas torneadas que se enroscan en ella. Las Figuras 47 y 48 la muestran abierta, cerrada y en despiece, y la Tabla 27 reúne sus componentes con sus medidas y materiales.

![](data:image/png;base64...)

**Figura 47.** Boquilla con cierre positivo: (a) abierta durante la inyección; (b) cerrada (cotas en mm, esquema sin escala)

![](data:image/png;base64...)

**Figura 48.** Despiece de la boquilla; los números corresponden a las piezas del texto (esquema sin escala)

Las piezas, con su número en el despiece, son:

* **(1) Cuerpo:** T roscada de 1". La rama lateral recibe la manguera.
* **(2) Pieza de punta:** se enrosca abajo de la T. Tiene el asiento del obturador y la cámara donde queda alojada la cabeza cuando abre.
* **(3) Pieza de lanza:** se enrosca en la pieza de punta y lleva la lanza soldada.
* **(4) Obturador:** cabeza con junta, unida a un vástago. Cierra subiendo contra el asiento.
* **(5) Tapón-guía:** cierra la T por arriba y guía el vástago.
* **(6) Linterna:** une el actuador con la boquilla y deja la zona del producto separada del actuador.
* **(7) Actuador:** cilindro neumático que abre y cierra el obturador.

Abierta, la cabeza del obturador queda dentro de una cámara de Ø32 mm, fuera del paso del producto. Así, por la lanza no pasa ningún vástago, que triplicaría su pérdida de carga.

**Tabla 27.** Componentes de la boquilla

| **Componente** | **Especificación** | **Material** | **Cant.** |
| --- | --- | --- | --- |
| T roscada | 1" clase 150 según ISO 4144, Rp 1 en las tres bocas, 38 mm del eje a cada cara [87] | CF8 (304) o CF8M (316) [88] | 1 |
| Juntas tóricas de cara | En la cara de los hexágonos de 41 mm y en el resalto de la pieza de lanza, tamaño a definir [18] | FKM | 3 |
| Pieza de punta | Rosca G 1 × 18,5 mm, hexágono de 41 × 11 mm, asiento Ø16 × 3 mm, cámara Ø32 × 66 mm, rosca exterior M40 × 1,5 × 12 mm | AISI 304 | 1 |
| Pieza de lanza | Hexágono de 46 × 30 mm, rosca interior M40 × 1,5 × 12 mm, reducción de Ø32 a Ø14,48 mm en 15 mm | AISI 304 | 1 |
| Lanza | Tubo de 15,88 × 0,70 mm (5/8"), 113 mm de largo libre, soldado a la pieza de lanza | AISI 304 | 1 |
| Tapón-guía | Hexágono de 41 × 11 mm, rosca G 1 × 18,5 mm, cola de Ø26 × 6,5 mm, agujero de Ø4 mm | AISI 304 | 1 |
| Vástago del obturador | Ø4 mm, rosca M4 en ambos extremos | AISI 304 | 1 |
| Obturador | Cabeza de Ø20 × 8 mm, cierra subiendo contra el asiento | AISI 304 | 1 |
| Junta tórica del obturador | En la cara superior de la cabeza, tamaño a definir [18] | FKM | 1 |
| Juntas tóricas del vástago | Para vástago de Ø4 mm, tamaño a definir [18] | FKM | 2 |
| Adaptador R 1 × Tri-Clamp | Rosca macho R 1 a férula Tri-Clamp de 1" | AISI 316 | 1 |
| Cinta de sellado | Para la rosca R 1 del adaptador, conforme a 21 CFR 177.1550 [89] | PTFE | — |
| Abrazadera y junta Tri-Clamp | Para ala de 50,5 mm, entre el adaptador R 1 y el de la manguera | Ídem Tabla 20 | 1 + 1 |
| Adaptador Tri-Clamp × espiga | Extremo Tri-Clamp de 50,5 mm y espiga para manguera de 1¼" | Acero inoxidable | 1 |
| Abrazadera de manguera | Para manguera de 1¼" | Ídem Tabla 20 | 1 |
| Linterna | Tubo de Ø30 × 2 × 65 mm con discos de Ø40 × 4 mm, soldada al tapón-guía | AISI 304 | 1 |
| Manguito de unión | Rosca interior M4 en ambos extremos, con dos contratuercas M4 | AISI 304 | 1 + 2 |
| Actuador del obturador | SMC CJ5-S Ø10 × 45, doble efecto [90] | SUS304, juntas de FKM | 1 |

## **17.2 Lanza y manguera**

La lanza es un tubo de AISI 304 de 15,88 × 0,70 mm (5/8"), de 14,48 mm de diámetro interior, que entra por la boca libre de 19 mm del envase (Figura 49). Deja 1,56 mm de holgura por lado, por donde sale el aire desplazado.

![](data:image/png;base64...)

**Figura 49.** Lanza dentro del envase con el carro abajo y posición de la punta al final de la subida lenta (cotas en mm, esquema sin escala)

Como la lanza es la misma para los dos formatos y el cabezal se regula 49 mm entre ellos, se dimensiona para el envase de 250 ml. Con el carro abajo, la punta queda h = 20 mm sobre el fondo y la pieza de lanza, 5 mm sobre la boca, de donde el largo libre es 128 ? 20 + 5 = 113 mm. En el envase de 500 ml, con el cabezal 49 mm más arriba, la punta queda 69 mm sobre el fondo y la pieza de lanza vuelve a quedar 5 mm sobre la boca. Al comenzar el llenado, el producto cae así 20 mm en el envase de 250 ml y 69 mm en el de 500 ml.

La altura h se mide desde lo más alto del domo del fondo. Como su altura no se midió, en la puesta en marcha la punta se ajusta con el husillo, subiendo el cabezal la altura del domo. La lanza no toca el envase, que solo recibe el producto.

Se adopta una manguera de PVC cristal reforzada con malla de poliéster, de 1¼" (31,75 mm de diámetro interior), del mismo tipo que usa la PyME en su máquina actual (Figura 50), donde se emplea con los tres productos (perfume, alcohol en gel y jabón) sin inconvenientes. Tiene el interior liso, lo que facilita la limpieza. El diámetro de 1¼", mayor que el de 1" del circuito, surge del largo admisible calculado en la Sección 17.3.

Se une a la válvula y a la boquilla con adaptadores Tri-Clamp × espiga y abrazaderas de manguera, como prevé la Tabla 20 (Sección 15.3), con la espiga de 1¼". En la boquilla, el adaptador se une a la rama lateral de la T con un adaptador R 1 × Tri-Clamp.

![](data:image/jpeg;base64...)

**Figura 50.** Manguera de PVC cristal reforzada con malla de poliéster, sobre espiga Tri-Clamp, en la máquina actual de la PyME

## **17.3 Pérdida de carga en la boquilla**

La Sección 6.1 estimó la boquilla como un tubo de 12,75 × 25 mm. Con la boquilla definida, la pérdida se calcula tramo por tramo (Figura 51). Los tramos circulares se resuelven con Hagen-Poiseuille (Sección 6.1):

*?P = 128 × ? × L × Q / (? × d?)*

donde ? = 5 Pa·s es la viscosidad de diseño, L el largo del tramo, Q = 50 × 10?? m³/s el caudal de inyección y d el diámetro interior. Los anillos entre el vástago o la cabeza abierta y el conducto se resuelven con la expresión del flujo laminar entre cilindros concéntricos [91]:

*?P = 8 × ? × L × Q / (? × R? × [(1 ? k?) ? (1 ? k²)² / ln(1/k)])*

donde R es el radio del conducto y k = di / D la relación entre el diámetro del cilindro interior y el del conducto. La reducción, cuyo diámetro varía linealmente de d1 = 32 mm a d2 = 14,48 mm en L = 15 mm, se resuelve integrando Hagen-Poiseuille:

*?Pcono = (128 × ? × Q / ?) × L / [3 × (d1 ? d2)] × (1/d2³ ? 1/d1³)*

Al salir de la lanza, el producto se abre en forma radial entre la cara de la punta, de r1 = 7,24 a r2 = 7,94 mm, y el fondo del envase, a h = 20 mm. Se toma el flujo laminar radial entre placas paralelas:

*?Psalida = 6 × ? × Q × ln(r2 / r1) / (? × h³)*

![](data:image/png;base64...)

**Figura 51.** Pérdida de carga en la boquilla: (a) tramos de cálculo con la boquilla abierta; (b), (c) y (d) modelos de los tramos no circulares (esquema sin escala)

El régimen es laminar: Re = ?·v·d / ? ? 1,0 en la lanza (v = 0,30 m/s) y ? 0,47 en el anillo del vástago en la T, con diámetro hidráulico D ? di = 22 mm. El anillo del vástago se toma desde el tapón-guía hasta el asiento (13 + 38 + 11 = 62 mm), aunque sus 13 mm superiores no tienen caudal pasante, y la rama lateral con un paso de 26 mm en los 38 mm de la cara al eje, aunque el adaptador ocupa parte de ese largo. Las dos simplificaciones quedan del lado seguro (Tabla 28).

**Tabla 28.** Pérdida de carga en la boquilla abierta (Q = 50.000 mm³/s, ? = 5 Pa·s)

| **Tramo** | **Geometría** | **Modelo** | **?P (Pa)** |
| --- | --- | --- | --- |
| 1. Rama lateral de la T | Ø26 mm, L = 38 mm | Conducto circular | 847 |
| 2. Anillo del vástago en la T y la pieza de punta | Ø26 / Ø4 mm, L = 62 mm | Anillo concéntrico | 2.819 |
| 3. Asiento con el vástago | Ø16 / Ø4 mm, L = 3 mm | Anillo concéntrico | 1.288 |
| 4. Anillo del vástago en la cámara | Ø32 / Ø4 mm, L = 45 mm | Anillo concéntrico | 819 |
| 5. Anillo de la cabeza abierta | Ø32 / Ø20 mm, L = 8 mm | Anillo concéntrico | 1.355 |
| 6. Cámara libre bajo la cabeza | Ø32 mm, L = 13 mm | Conducto circular | 126 |
| 7. Reducción | Ø32 a Ø14,48 mm, L = 15 mm | Cono (integración) | 869 |
| 8. Lanza | Ø14,48 mm, L = 113 mm | Conducto circular | 26.182 |
| 9. Salida contra el fondo | h = 20 mm, cara de Ø14,48 a Ø15,88 mm | Flujo radial entre placas | 6 |
| **Total boquilla** |  |  | **34.311** |

La lanza concentra el 76 % de la pérdida de la boquilla, porque es el tramo más largo y angosto. Su largo y su diámetro los fijan el envase y la boca, por lo que es la pérdida que menos se puede reducir.

Con el balance de fuerzas de la Sección 6.1 (dosificador de 80 mm, A = 5.027 mm², y actuador CP96 Ø40 de 692 N) y CS = 3, el largo máximo de manguera es:

*Lmáx = [Factuador / (CS × A) ? ?Pboquilla] / ?Pmanguera/m*

donde ?Pmanguera/m es la pérdida por metro de manguera, que con Hagen-Poiseuille vale 24.472 Pa/m para la manguera de 1" de la Sección 6.1 y 10.024 Pa/m para una de 1¼" (31,75 mm). Con la de 1", el largo máximo es (45.886 ? 34.311) / 24.472 ? 0,47 m, que no alcanza para acompañar el recorrido de la boquilla, de 230 mm (80 mm de regulación y 150 mm de carrera), y llegar hasta la válvula. Con la de 1¼":

*Lmáx = (45.886 ? 34.311) / 10.024 ? 1,15 m*

Por eso se adopta la manguera de 1¼" (Sección 17.2), sin cambiar el actuador, el coeficiente de seguridad ni los tiempos del ciclo (Figura 52 y Tabla 29).

![](data:image/png;base64...)

**Figura 52.** Coeficiente de seguridad del actuador del dosificador en función del largo y del diámetro de la manguera

**Tabla 29.** Coeficiente de seguridad del actuador del dosificador según la manguera

| **Manguera** | **?P total (Pa)** | **Fresistencia (N)** | **CS (692 N)** |
| --- | --- | --- | --- |
| 1¼", 1,15 m (máximo admisible) | 45.879 | 230,6 | 3,00 |
| 1¼", 1,0 m (valor de trabajo de la Sección 6.1) | 44.335 | 222,9 | 3,10 |
| 1", 1,0 m | 58.783 | 295,5 | 2,34 (no verifica) |

La manguera armada debe medir como máximo 1,15 m. El largo real depende de la posición de la válvula respecto del cabezal y se verifica con el dibujo definitivo de la estación. La presión de diseño del dosificador (Sección 8.2) no cambia, porque corresponde al avance impedido.

## **17.4 Actuador del obturador**

Se usa un cilindro de doble efecto, para que la apertura y el cierre sean forzados por aire, con el criterio de la Sección 4: SMC CJ5-S de acero inoxidable en su diámetro menor, Ø10, con vástago de 4 mm y carrera estándar de 45 mm [90]. A p = 0,55 MPa:

*Favance = p × ? × D² / 4 ? 43,2 N; Fretroceso = p × ? × (D² ? dv²) / 4 ? 36,3 N*

donde D = 10 mm es el diámetro del pistón y dv = 4 mm el del vástago.

El avance abre y el retroceso cierra. Como la cabeza está debajo del asiento, la presión del producto la empuja hacia abajo, en el sentido de apertura. El caso exigente es el cierre, al terminar la inyección (Figura 53a): la presión sobre la cabeza es, como máximo, la pérdida de carga entre el asiento y la salida durante la inyección, 30.645 Pa (tramos 3 a 9 de la Tabla 28). Sobre el área sellada por la junta, tomada con el diámetro exterior de la cabeza, dj = 20 mm, del lado seguro:

*Fhidráulica = p × ? × (dj² ? dv²) / 4 = 0,0306 × ? × (20² ? 4²) / 4 ? 9,2 N*

donde se descuenta el área del vástago, que atraviesa el asiento. El factor de carga, ? = 9,2 / 36,3 ? 0,25, es menor que 0,5, el máximo recomendado por el fabricante para operación dinámica [9]. La masa móvil, de unos 45 g entre vástago, obturador, manguito y pistón, llega al final de la carrera a 300 mm/s con unos 0,002 J, menos que los 0,035 J admisibles para el Ø10 [90] (Tabla 30).

**Tabla 30.** Verificación del actuador del obturador SMC CJ5-S Ø10 × 45

| **Verificación** | **Valor calculado** | **Límite** | **Resultado** |
| --- | --- | --- | --- |
| Factor de carga en el cierre | ? = 9,2 / 36,3 = 0,25 | ? ? 0,5 [9] | Verifica |
| Presión de trabajo | 0,55 MPa | 0,1 a 0,7 MPa [90] | Verifica |
| Velocidad del pistón | 300 mm/s (45 mm en 0,15 s) | 50 a 750 mm/s [90] | Verifica |
| Energía cinética | 0,002 J | 0,035 J [90] | Verifica |

Al abrir, el vástago entra 45 mm en el conducto y desplaza 565 mm³, que salen por la lanza al envase. Al cerrar, sale los mismos 45 mm y aspira ese volumen por la punta: el producto retrocede 565 / 164,7 ? 3,4 mm dentro de la lanza y no queda una gota colgando (Figura 53b). Como el vástago entra y sale el mismo volumen en cada ciclo, cada envase recibe exactamente el volumen barrido por el pistón.

![](data:image/png;base64...)

**Figura 53.** Obturador: (a) fuerzas sobre la cabeza al cerrar; (b) retroceso del producto en la punta de la lanza (esquema sin escala)

En la puesta en marcha, la boquilla y la manguera se purgan con ciclos en vacío sobre un recipiente.

## **17.5 Carro vertical**

El carro es una chapa de SAE 1010 laminada en caliente de 12,70 mm [64], de 190 × 80 mm, galvanizada en caliente junto con la bancada (Secciones 13.1 y 13.2). Lleva dos bujes con brida, el soporte de la boquilla, la unión flotante del actuador y un agujero de paso de Ø20 mm para el extremo del husillo, que lo atraviesa cuando el carro sube. Las guías quedan a 25 mm del borde delantero, de modo que la brida de Ø42 mm de cada buje queda a 4 mm de los bordes de la chapa, y entre el carro y las caras de los montantes quedan 5 mm por lado (Figura 54a).

### **Soporte de la boquilla**

El soporte une la T al carro (Figura 54). Es una pieza de AISI 304 formada por un ala y un puente de 30 × 12 mm y una abrazadera partida de 12 mm de alto y 6 mm de pared, que toma el tramo recto de la T entre la rama lateral y la boca superior. El ala apoya sobre la cara superior del carro y se fija con dos tornillos M5 de acero inoxidable A2-70, ubicados 10 mm detrás del borde delantero; la tapa de la abrazadera cierra con otros dos M5, separados 54 mm. Las dos mitades de la abrazadera se cortan de una misma pieza y el agujero se mecaniza al diámetro exterior medido en la T comprada, porque esa medida cambia entre fabricantes (39,6 mm en la de la referencia [92]). El eje de la boquilla queda 55 mm por delante del borde del carro y 80 mm por delante del plano de las guías.

La cara inferior de la abrazadera apoya sobre el lomo de la rama lateral, y del lado de la rama cada mitad tiene una oreja de 6 × 11 mm que baja 17 mm por el costado de la rama. Así la rama queda encajada: la T no puede girar y una fuerza hacia arriba sobre la lanza pasa al soporte por contacto, sin depender del apriete. El apriete de la tapa sostiene el peso de la boquilla. El soporte inoxidable queda en contacto con el carro galvanizado, pero como es chico frente a la superficie de zinc el riesgo galvánico es bajo [61], [62], con el criterio de la Sección 16.1.

![](data:image/png;base64...)

**Figura 54.** Carro y soporte de la boquilla: (a) vista superior; (b) vista lateral en el plano de la boquilla (cotas en mm, esquema sin escala)

### **Masa del conjunto móvil**

La Tabla 31 reúne la masa del carro con todo lo que lleva, calculada con ? = 76,5 kN/m³ para el acero al carbono y 76,0 kN/m³ para el inoxidable [13] y con las masas de catálogo.

**Tabla 31.** Masa del conjunto móvil del carro

| **Componente** | **Origen** | **Masa (kg)** |
| --- | --- | --- |
| Carro (chapa de SAE 1010 de 12,70 mm, 190 × 80 mm) | Cálculo | 1,399 |
| Bujes igus FJUM-01-12 (2) | 42 g cada uno [93] | 0,084 |
| Soporte de la boquilla (AISI 304) | Cálculo | 0,221 |
| T roscada 1" clase 150 | Catálogo [87] | 0,256 |
| Pieza de punta | Cálculo | 0,383 |
| Pieza de lanza | Cálculo | 0,249 |
| Tubo de la lanza (15,88 × 0,70 × 113 mm) | Cálculo | 0,029 |
| Tapón-guía | Cálculo | 0,261 |
| Linterna | Cálculo | 0,162 |
| Actuador CJ5-S Ø10 × 45 | 52 g + 3 × 4 g [90] | 0,064 |
| Vástago y obturador | Cálculo | 0,030 |
| Producto dentro de la boquilla abierta (138 ml) | ? = 1.100 kg/m³ | 0,152 |
| **Total** |  | **3,290** |

El peso resulta Wcarro = 3,290 × 9,81 ? 32,3 N. Juntas, adaptadores, unión flotante, tornillería y la parte de la manguera que cuelga del carro quedan cubiertos por el margen del actuador.

### **Movimiento de la lanza durante el llenado**

La lanza no puede quedar abajo durante toda la inyección. En el envase de 250 ml, el espacio libre de 7 ml queda arriba, y con la lanza abajo quedarían sumergidos al menos los 88 mm que van de la punta al arranque del cuello, ? × 15,88² / 4 × 88 ? 17,4 ml, más del doble del espacio libre, y el envase rebalsaría.

Por eso la lanza sube a velocidad constante mientras se llena y no sale del envase hasta terminar el llenado. La subida lenta empieza con la inyección y termina con el obturador cerrado, en tiny + tcierre, con la punta 20 mm debajo del borde de la boca. El recorrido es el mismo en los dos formatos, 128 ? 20 ? 20 = 88 mm en el de 250 ml y 177 ? 20 ? 69 = 88 mm en el de 500 ml, pero el tiempo no:

*v250 = 88 / (5,0 + 0,15) ? 17,1 mm/s; v500 = 88 / (10,0 + 0,15) ? 8,7 mm/s*

Para verificar que el envase no rebalse, se calculó el nivel del producto en cada instante con el caudal de 50 ml/s, descontando el volumen de la lanza sumergida. Como la forma del hombro y del domo es esquemática, el perfil de cada envase se ajustó para que su volumen total coincida con el cubicaje de la ficha (257 y 520 ml), y se probaron distintas formas de hombro, con resultados prácticamente iguales (Figura 55).

![](data:image/png;base64...)

**Figura 55.** Altura de la punta de la lanza y del nivel del producto durante el llenado: (a) envase de 250 ml; (b) envase de 500 ml (perfil de los envases ajustado al cubicaje)

La punta queda siempre por encima del nivel. En el envase de 250 ml lo hace entre 8 y 20 mm, y al final del llenado alcanza el nivel con 1 mm sumergido como máximo; en el de 500 ml queda entre 50 y 70 mm por encima durante casi todo el llenado y termina 8 a 10 mm sobre el nivel. Ninguno de los dos envases rebalsa. En el de 500 ml, en cambio, la subida de la lanza casi no reduce la caída libre del producto.

### **Actuador del carro**

El actuador baja la lanza 150 mm, la sube a velocidad constante durante el llenado y después la saca rápido. La carrera de 150 mm cubre el recorrido de la punta dentro del envase, 108 mm, y deja la punta 42 mm sobre la boca con el carro arriba, holgura suficiente para el paso del envase.

Se adopta el cilindro de baja velocidad SMC CJ2X en Ø16, con imán para los detectores (versión CDJ2X) y carrera estándar de 150 mm [94]; la serie tiene tubo y vástago de acero inoxidable [95] y admite velocidades de 1 a 300 mm/s. Se pide en la versión con brida delantera, que se atornilla sobre la placa soporte con dos tornillos M5 [96]. A 0,55 MPa:

*Favance = p × ? × D² / 4 ? 110,6 N; Fretroceso = p × ? × (D² ? dv²) / 4 ? 99,8 N*

donde D = 16 mm y dv = 5 mm.

El retroceso sube el carro, con un factor de carga ? = 32,3 / 99,8 ? 0,32, menor que 0,5 [9]. En el avance el peso del carro ayuda, y el actuador solo vence la fricción, porque la lanza no apoya sobre nada: la carrera termina en el tope interno del cilindro, que fija la altura de la punta, y el envase no recibe ninguna fuerza. El vástago se une al carro con una unión flotante SMC JA15-5-080, para rosca M5 × 0,8 [97], que absorbe la excentricidad y el desalineamiento entre el actuador y las guías, ya que el fabricante pide no aplicar carga lateral al cilindro [96]. En los tramos rápidos, a 100 mm/s, la energía cinética del carro es ½ × 3,290 × 0,1² ? 0,016 J, menor que los 0,090 J admisibles para el Ø16 [96] (Tabla 32).

**Tabla 32.** Verificación del actuador del carro SMC CJ2X Ø16 × 150

| **Verificación** | **Valor calculado** | **Límite** | **Resultado** |
| --- | --- | --- | --- |
| Factor de carga en la subida | ? = 32,3 / 99,8 = 0,32 | ? ? 0,5 [9] | Verifica |
| Velocidad de subida lenta | 17,1 y 8,7 mm/s | 1 a 300 mm/s [96] | Verifica |
| Velocidad de los tramos rápidos | 100 mm/s | 1 a 300 mm/s [96] | Verifica |
| Energía cinética | 0,016 J | 0,090 J [96] | Verifica |
| Carrera | 150 mm (108 mm en el envase + 42 mm de paso) | Carrera estándar [94] | Verifica |

### **Control de velocidad**

La subida es el retroceso: entra aire en la cámara inferior y escapa el de la superior. La velocidad se fija regulando ese escape (Figura 56). Entre la válvula del carro y la cámara superior hay dos caminos en paralelo:

* **Camino rápido:** una electroválvula 2/2 normal cerrada, Y-rápido, que deja escapar el aire libremente. Está abierta en la bajada y en la subida rápida.
* **Camino lento:** una electroválvula 3/2 usada como selectora, Y-formato, que envía el escape al regulador A (envase de 250 ml) o al B (envase de 500 ml). Los dos tienen válvula antirretorno, de modo que en la bajada el aire entra libre.

Para la operación vertical, el fabricante recomienda reguladores de baja velocidad, montados lo más cerca posible del cilindro, y regular a la vez la entrada de aire, lo que reduce el stick-slip [96]. Por eso A y B son reguladores de baja velocidad de SMC, con un área efectiva controlada de 0,1 a 0,6 mm² según el tamaño, y la cámara inferior lleva un regulador doble de baja velocidad, que regula la entrada de aire durante la subida y la salida durante la bajada [96]. Los reguladores van sobre la placa soporte, junto al cilindro, de modo que las mangueras hasta las bocas son cortas.

![](data:image/png;base64...)

**Figura 56.** Circuito neumático del actuador del carro con dos velocidades de subida (esquema)

Los reguladores se ajustan una sola vez, en la puesta en marcha, y se traban con su contratuerca; el regulador doble se ajusta de modo que la subida rápida y la bajada se hagan a 100 mm/s. En el cambio de formato el operario no ajusta ningún regulador: el PLC conmuta Y-formato según el formato seleccionado.

### **Guías lineales**

El carro y la placa soporte deslizan sobre las dos guías de Ø12 mm, con un buje igus drylin R FJUM-01-12 por guía en cada placa: buje con brida de aluminio anodizado y liner de iglidur J, de 32 mm de largo, 960 N de carga dinámica (p = 5 MPa), 6.720 N de carga estática (p = 35 MPa) y 42 g [93].

La brida se atornilla a la placa con tornillos M4 y el cuerpo del buje entra en un agujero de Ø22 mm [93]. Con el carro y la placa soporte galvanizados, el contacto entre el aluminio y el zinc produce en ambiente atmosférico una corrosión adicional nula o leve [98].

Con una distribución lineal de presión en el buje, sus resultantes quedan separadas 2L/3 (Figura 57b) y la fuerza en cada extremo es:

*Fextremo = 3 × Mbuje / (2 × Lbuje)*

donde Mbuje es la mitad del momento total, porque hay un buje por guía, y Lbuje = 32 mm. Las guías solo reciben el peso del carro y la fuerza del actuador que lo sostiene. Los casos son:

* **Carro colgado del actuador:** el actuador sostiene el peso 35 mm al costado y 35 mm detrás del plano de las guías, y el centro de masa del carro está en el plano medio, 38,8 mm por delante (Figura 57a). Con una distancia de ?(35² + 73,8²) ? 81,7 mm: M = 32,3 × 81,7 ? 2.636 N·mm.
* **Placa soporte:** las reacciones del actuador y de la tuerca del husillo, separadas ?(70² + 35²) ? 78,3 mm, forman un par: M = 32,3 × 78,3 ? 2.527 N·mm.

![](data:image/png;base64...)

**Figura 57.** Cargas sobre las guías: (a) brazo del peso del carro respecto del actuador; (b) distribución de presión en el buje (cotas en mm, esquema sin escala)

**Tabla 33.** Verificación de las guías lineales

| **Caso** | **Momento total (N·mm)** | **Fextremo por buje (N)** | **Carga del buje (N)** | **Resultado** |
| --- | --- | --- | --- | --- |
| Carro colgado del actuador | 2.636 | 61,8 | 960 (dinámica) | Verifica |
| Placa soporte | 2.527 | 59,2 | 960 (dinámica) | Verifica |

Cada guía recibe el momento de un buje de la placa soporte, 1.264 N·mm, más la mitad del momento del carro, 1.318 N·mm. Tomando ambos sumados, del lado seguro:

*? = 32 × M / (? × d³) = 32 × (1.264 + 1.318) / (? × 12³) ? 15,2 MPa*

con CS = 180 / 15,2 ? 11,8 respecto del límite elástico del SAE 1010 (Sección 13.1). Los coeficientes altos cubren también las cargas de inercia en los finales de carrera, que no se evaluaron.

## **17.6 Regulación de altura**

La placa soporte es una chapa de SAE 1010 de 12,70 mm [64], de 190 × 80 mm, galvanizada como el carro, con un buje igual en cada guía. Lleva el actuador del carro, los reguladores de velocidad y la tuerca del husillo.

El husillo es de rosca trapecial Tr16 × 4 de una entrada, en acero inoxidable 1.4301 [99]. Se enrosca en una tuerca igus drylin de iglidur J para Tr16 × 4 [100], atornillada a la placa soporte 35 mm al costado del centro, y gira apoyado en la placa superior (Figura 58).

El extremo superior del husillo se tornea a Ø10 mm, el agujero del volante [101], y gira en un agujero de Ø10,5 mm de la placa superior. El peso del cabezal regulado lo toma el cubo del volante, fijado al husillo con un pasador elástico, que apoya sobre la cara superior de la placa con una arandela de acero inoxidable. Una carga hacia arriba la toma el escalón entre la rosca y el extremo torneado, que apoya contra la cara inferior de la placa con otra arandela. Como el volante solo se acciona en el cambio de formato, a mano y con pocas vueltas, el agujero de la placa basta como apoyo de giro, sin rodamientos.

![](data:image/png;base64...)

**Figura 58.** Apoyo del husillo en la placa superior (corte, esquema sin escala)

El recorrido, 80 mm, cubre los 49 mm entre formatos y deja 25 mm sobre la posición de 500 ml y 6 mm bajo la de 250 ml para el ajuste fino y las tolerancias de envases y cinta. El ajuste por el domo del fondo se hace subiendo el cabezal dentro de esos márgenes. Cambiar de formato lleva 49 / 4 = 12,25 vueltas, y el recorrido completo, 20.

### **Autobloqueo**

El fabricante indica que los husillos trapeciales de una entrada con sus tuercas son autoblocantes y que los de dos entradas no lo son [99]. Con el husillo de una entrada, el cabezal queda sostenido en cualquier posición sin freno.

### **Traba y escala**

Contra el giro por vibraciones, la placa soporte lleva un buje partido sobre una de las guías, que se aprieta con una palanca. Para repetir cada formato, un montante lleva una regla graduada en milímetros con un índice en la placa; cada vuelta del volante son 4 mm.

## **17.7 Bastidor**

El bastidor forma parte de la bancada y se galvaniza con ella una vez soldado (Sección 13.2). Está formado por (Figura 59):

* **Guías:** barras de SAE 1010 de Ø12 × 458 mm. Cada una entra por un agujero del tubo delantero, apoya en la pared inferior y se suelda arriba.
* **Montantes:** tubos de 25 × 25 × 1,25 mm [55] de 421,7 mm, soldados sobre el tubo a 225 mm entre ejes, con un tapón roscado M6 en el extremo.
* **Placa superior:** chapa de SAE 1010 de 6,35 mm [64], de 250 × 40 mm, atornillada a los montantes con tornillos M6 clase 4.8 (Sección 16.1). Va atornillada para poder montar el carro y la placa soporte en las guías.

Las soldaduras se hacen con el procedimiento para chapa delgada de la Sección 13.1 [67], con un dispositivo que mantiene vertical cada guía.

![](data:image/png;base64...)

**Figura 59.** Detalle del bastidor: (a) guía soldada al tubo de la bancada; (b) placa superior sobre el montante (cotas en mm, esquema sin escala)

### **Verificación**

El grupo de la boquilla pesa 17,7 N y su centro está 80 mm por delante del plano de los montantes (Figura 60a). El bastidor lleva ese momento, Mg = 17,7 × 80 ? 1.416 N·mm, al tubo de la bancada, repartido entre montantes y guías según su rigidez:

*fmontantes = 2 × It / (2 × It + 2 × Ig) = 11.195 / (11.195 + 1.018) ? 0,917*

donde It = [b? ? (b ? 2t)?] / 12 = 11.195 mm? es el momento de inercia del tubo (b = 25 mm, t = 1,25 mm) e Ig = ? × 12? / 64 = 1.018 mm? el de cada guía; como los dos son de SAE 1010, el módulo de elasticidad se simplifica.

En la base de cada montante, con todo el peso del cabezal regulado, F = 49,0 N:

*? = fmontantes × Mg / (2 × S) + F / (2 × A) = 0,917 × 1.416 / (2 × 895,6) + 49,0 / (2 × 118,75) ? 0,72 + 0,21 ? 0,93 MPa*

donde S = [b? ? (b ? 2t)?] / (6b) = 895,6 mm³ y A = b² ? (b ? 2t)² = 118,75 mm². Con Sy = 180 MPa (Sección 13.1), la tensión es despreciable.

Lo que importa es la rigidez, porque la lanza debe entrar en la boca con 1,56 mm de holgura por lado. Aplicando Mg en la placa superior, del lado seguro, el bastidor gira ? = Mg × h / (E × ?I) ? 1,2 × 10?? rad, con h = 428 mm, E = 200 GPa (Sección 13.1) y ?I = 2 × (11.195 + 1.018) = 24.426 mm?, y la punta, 573 mm por debajo de la placa superior con el carro abajo, se desplaza unos 0,07 mm. Las soldaduras de las guías al tubo toman solo la parte del momento que va por las guías, (1 ? 0,917) × 1.416 / 2 ? 59 N·mm cada una.

La placa superior recibe el peso del cabezal regulado a través del husillo y, en el peor caso, si el carro empujara contra un obstáculo, la fuerza de avance del actuador, 110,6 N, hacia arriba. Tomada como viga apoyada en los montantes, de 225 mm de luz, con la carga en el husillo, a 77,5 mm de un apoyo (Figura 60b):

*M = F × a × b / L = 110,6 × 77,5 × 147,5 / 225 ? 5.619 N·mm*

En esa sección está el agujero de Ø10,5 mm del husillo, por lo que se toma el ancho neto: S = (40 ? 10,5) × 6,35² / 6 ? 198 mm³, de donde ? = M / S ? 28,3 MPa y CS = 180 / 28,3 ? 6,4 (Tabla 34).

![](data:image/png;base64...)

**Figura 60.** Modelos de verificación del bastidor: (a) rigidez de montantes y guías; (b) placa superior como viga apoyada (cotas en mm, esquema sin escala)

**Tabla 34.** Verificación del bastidor

| **Verificación** | **Valor calculado** | **Límite** | **Resultado** |
| --- | --- | --- | --- |
| Montantes (base) | ? = 0,93 MPa | Sy = 180 MPa | Verifica |
| Desplazamiento de la punta | 0,07 mm | Holgura de 1,56 mm por lado | Verifica |
| Placa superior (flexión) | ? = 28,3 MPa; CS = 6,4 | Sy = 180 MPa | Verifica |

## **17.8 Sensores y tiempos del ciclo**

### **Sensores del cabezal**

El cabezal lleva los detectores del actuador del carro y el pulsador de parada (Tabla 35). Los detectores son de estado sólido, SMC D-M9, aplicables a la serie CJ2X en montaje con banda [96]. Van en el tubo del actuador, que sube y baja con la placa soporte, de modo que sirven para los dos formatos sin moverlos y ninguno lleva cable sobre el carro.

* **Pico arriba y pico abajo:** van en los finales de carrera. Pico arriba confirma la lanza fuera del envase; pico abajo confirma la lanza abajo, que es la condición para dosificar.
* **Fin de subida lenta:** va a 88 mm del final de carrera inferior, donde termina la subida lenta, y sirve para calibrar los reguladores y vigilar la velocidad.
* **Pulsador de parada de llenado:** va en el frente del montante opuesto a la manguera, al lado de la boquilla.

Además de la válvula del carro, Y-rápido e Y-formato, el obturador tiene su propia electroválvula monoestable, con reposo en cerrado: abre junto con el avance del pistón y cierra al terminar la inyección, antes de que la lanza salga rápido.

**Tabla 35.** Sensores del cabezal de llenado

| **Sensor** | **Tipo** | **Ubicación** | **Función** |
| --- | --- | --- | --- |
| Pico arriba | Detector de estado sólido SMC D-M9 | Tubo del CJ2X, final de la carrera de retroceso | Lanza fuera del envase |
| Pico abajo | Detector de estado sólido SMC D-M9 | Tubo del CJ2X, final de la carrera de avance | Lanza abajo; condición para dosificar |
| Fin de subida lenta | Detector de estado sólido SMC D-M9 | Tubo del CJ2X, a 88 mm del final de avance | Calibración y vigilancia de la velocidad de subida |
| Pulsador de parada de llenado | Pulsador | Frente del montante opuesto a la manguera | Parada del operario |

### **Tiempos del ciclo**

La Figura 61 muestra la secuencia para 250 ml, el caso más exigente (ciclo de 15 s, Sección 3). El carro baja 150 mm a 100 mm/s en 1,5 s; la lanza sube lento durante la inyección y el cierre del obturador, y después sale rápido los 62 mm restantes en 0,62 s. El obturador abre y cierra sus 45 mm en 0,15 s, y la apertura se superpone con el inicio de la inyección (Tabla 36).

![](data:image/png;base64...)

**Figura 61.** Diagrama de tiempos del cabezal de llenado para el envase de 250 ml

**Tabla 36.** Tiempos del cabezal de llenado

| **Etapa** | **250 ml (s)** | **500 ml (s)** |
| --- | --- | --- |
| Bajada del carro (150 mm a 100 mm/s) | 1,5 | 1,5 |
| Inyección, con la apertura del obturador en sus primeros 0,15 s y la lanza subiendo (Sección 3) | 5,0 | 10,0 |
| Cierre del obturador, con la lanza subiendo | 0,15 | 0,15 |
| Subida rápida (62 mm a 100 mm/s) | 0,62 | 0,62 |
| **Ocupación del cabezal** | **7,27** | **12,27** |
| Ciclo disponible (Sección 3) | 15 | 30 |
| **Tiempo libre para la cinta** | **7,73** | **17,73** |

La aspiración (2,5 s para 250 ml y 5 s para 500 ml, Sección 3) ocurre con la lanza saliendo y arriba, en paralelo con el cambio de envase. Las conmutaciones de la válvula y de las electroválvulas quedan dentro del tiempo libre para la cinta.

## **Fuentes técnicas consultadas (continuación)**

[86] Patente US5137187, "Anti-spray fluid dispensing nozzle", P. Nichols y R. Lapointe, 1992 (dos válvulas en el conducto de alimentación, accionadas por un vástago que corre por dentro del conducto; la válvula inferior cierra la salida desde adentro, contra un asiento en el extremo de descarga). https://patents.google.com/patent/US5137187A/en

[87] Hydraulic Megastore, "150lb Stainless Steel Fittings" (accesorios roscados de fundición de acero inoxidable CF8M (316); roscas según ISO 7-1, hembra paralela y macho cónico; T igual de 1": A = 38 mm y 0,256 kg; niple hexagonal de 1": 48 mm de largo, 18,5 mm de rosca y 11 mm de hexágono; presión máxima de trabajo de 20 bar entre ?20 y 40 °C). https://www.hydraulicmegastore.com/wp-content/uploads/2015/04/150lb-Stainless-Steel-Fittings.pdf

[88] Anzor, "1" BSP 316 Hex Nipple (NB25)" (accesorios roscados de 150 lb; material según ASTM A276 304 y ASTM A351 CF8 (304) o CF8M (316)). Fuente comercial. https://anzor.co.nz/bsp-npt-fittings/bsp-nipples/hex-nipple/1-bsp-316-hex-nipple-nb25

[89] Anti-Seize Technology, "Low Density PTFE Thread Seal Tape", serie 26100 (100 % PTFE virgen; conforme a 21 CFR 177.1550; de ?240 a +260 °C; apta para agua, productos químicos, etanol y solventes). https://res.cloudinary.com/tacoma-screw-products/image/upload/Documents/618-301\_tds.pdf

[90] SMC Corporation of America, catálogo "Series CJ5-S ø10, ø16 Stainless Steel Cylinder" (carreras estándar del ø10: 15, 30, 45, 60, 75, 100, 125 y 150 mm; presión de trabajo de 0,1 a 0,7 MPa; velocidad del pistón de 50 a 750 mm/s; energía cinética admisible de 0,035 J para el ø10; masa básica de 52 g más 4 g cada 15 mm de carrera; vástago de 4 mm con rosca M4 × 0,7; rosca de montaje delantera M10 × 1,0; tubo, tapas y vástago de acero inoxidable 304; juntas de NBR o FKM; no admite instalación en la zona de alimentos y sí en la zona de salpicaduras). https://www.smcpneumatics.com/pdfs/CJ5S.pdf

[91] F. M. White, "Fluid Mechanics", McGraw-Hill, Capítulo 6 (flujo laminar completamente desarrollado en conductos no circulares: anillo entre dos cilindros concéntricos).

[92] RS Components, "RS PRO Stainless Steel Circular Tee, 1in G(P) Female" (RS 499-3007; acero inoxidable 316, 150 lb; largo de 2,76 in y diámetro exterior de 1,56 in). Fuente comercial. https://static.chipdip.ru/lib/295/DOC041295755.pdf

[93] igus, "drylin® R flange bearings: closed, anodised aluminium adapter, round flange" (FJUM-01-12: d1 = 12 mm, d2 = 22 mm h7, brida de Ø42 mm con agujeros de 4,5 mm, largo de 32 mm; carga dinámica de 960 N con p = 5 MPa y estática de 6.720 N con p = 35 MPa; masa de 42 g; liner de iglidur® J). https://www.igus.eu/ContentData/Products/Downloads/drylin-r-anodised-aluminium-adapter-FJUM-01.pdf

[94] SMC Corporation of America, "C(D)J2X, Air Cylinder, Double Acting, Single Rod, Low Speed" (diámetros de 10 y 16 mm; carreras de 15, 30, 45, 60, 75, 100, 125, 150, 175 y 200 mm; versión CDJ2X con imán para detectores). https://elasticsearch.smcpneumatics.com/products/Actuators/Specialty-Actuators/Low-Speed-Low-Friction/Low-Speed/CJ2X/CDJ2X-Air-Cylinder-Double-Acting-Single-Rod-Low-Speed~20543

[95] SMC Corporation of America, ficha "CJ2XB16-15Z" (serie CJ2X: tubo y vástago de acero inoxidable; apta para detectores; montajes básico, con pie, con brida y con doble horquilla). Fuente comercial. https://www.smcpneumatics.com/CJ2XB16-15Z.html

[96] SMC, catálogo "Air Cylinder Series CJ2" (serie CJ2X de baja velocidad, ø10 y ø16: velocidad del pistón de 1 a 300 mm/s; energía cinética admisible de 0,090 J para el ø16; fuga interna de hasta 0,1 l/min (ANR) por su construcción; ø16: vástago de 5 mm con rosca M5 × 0,8, rosca de montaje M10 × 1,0 y estilo con brida delantera con agujeros de 5,5 mm; detectores de estado sólido D-M9 en montaje con banda; para operación vertical, control de velocidad por el escape con control simultáneo de la entrada para reducir el stick-slip, reguladores de baja velocidad lo más cerca posible del cilindro y ausencia de carga lateral; reguladores de baja velocidad serie AS-FM, con área efectiva controlada de 0,1 a 0,6 mm², y reguladores dobles serie ASD). https://docs.rs-online.com/e3ae/0900766b814145b3.pdf

[97] SMC Corporation of America, "JA15-5-080" (unión flotante de la serie JA con rosca M5 × 0,8). https://elasticsearch.smcpneumatics.com/JA15-5-080.html

[98] Galvanizers Association, "HDG Datasheet 10: Bimetallic Corrosion", 2024 (corrosión adicional del zinc en contacto con otros metales en ambiente atmosférico rural e industrial o urbano: aluminio, 0 y 0 a 1, nula o muy leve; acero inoxidable, 0 a 1; bronce, 0 a 1 y 1, con aislación recomendada para las aleaciones de cobre). https://wedge-galv.co.uk/wp-content/uploads/2024/10/10-Bimetallic-Corrosion-2024.pdf

[99] igus, "drylin® trapezoidal lead screw, 1.4301 (304) stainless steel" (husillos de acero inoxidable 1.4301 de 8 a 24 mm de diámetro y pasos de 1,5 a 5 mm; los de una entrada son autoblocantes y los de dos entradas no). https://www.igus.com/product/918

[100] igus, "drylin® injection-molded lead screw nuts with flange, JFRM" (tuerca con brida de iglide® J para rosca trapecial). https://www.igus.com/product/14988

[101] Halder, "Handwheels similar to DIN 950, stainless steel" (serie 24591, d1 = 100 mm: agujero de 10 mm H9, tres rayos, acero inoxidable A4; 431 g sin manija y 472 g con manija de máquina M6). https://halderusa.com/PM/Standard-Parts/Operating-Elements/Handwheels/Handwheels-similar-to-DIN-950-stainless-steel
