# 625 Ejercicios de Programación en Python

### Ejercicio 1: Costo por mes de plan de datos
**Enunciado:** Una compañía de telefonía ofrece tres planes de datos: Básico (2 GB, $150), Estándar (5 GB, $280), Premium (12 GB, $520). Escribe un programa que pregunte al usuario cuántos GB necesita al mes y recomiende el plan más económico que cubra esa necesidad, calculando también el costo por GB de cada plan.
**Entrada:** Un número flotante: GB necesarios al mes.
**Salida:** Nombre del plan recomendado, su costo mensual, y el costo por GB de los tres planes.

### Ejercicio 2: Simulador de propinas escalonadas
**Enunciado:** En un restaurante la propina se calcula de forma escalonada: si el consumo es menor a $500, la propina es 10%; entre $500 y $1500, es 12%; entre $1500 y $3000, es 15%; mayor a $3000, es 18%. El programa debe mostrar el total a pagar incluyendo propina y el monto exacto de la propina.
**Entrada:** Consumo del restaurante en pesos (float).
**Salida:** Propina calculada, total a pagar, y porcentaje aplicado.

### Ejercicio 3: Conversor de divisas con tipo de cambio dinámico
**Enunciado:** El usuario ingresa una cantidad en pesos mexicanos (MXN), el tipo de cambio actual del dólar estadounidense (USD → MXN), y el tipo de cambio del euro (EUR → MXN). El programa convierte la cantidad a USD y EUR por separado, redondeando a 2 decimales, e indica cuál divisa le daría más valor si quisiera cambiar.
**Entrada:** Cantidad MXN (float), tasa USD/MXN (float), tasa EUR/MXN (float).
**Salida:** Equivalente en USD, equivalente en EUR, y divisa con mayor valor.

### Ejercicio 4: Retención impositiva simulada
**Enunciado:** Un empleado percibe un salario mensual. La retención impositiva se calcula en escalones: hasta $3000 no se retiene; de $3000.01 a $8000 se retiene el 2% del excedente sobre $3000; de $8000.01 a $15000 se retiene el 5% del excedente sobre $8000 más $100 fijos; mayor a $15000 se retiene el 8% del excedente sobre $15000 más $450 fijos. Escribe un programa que muestre el salario bruto, la retención y el salario neto.
**Entrada:** Salario bruto mensual (float).
**Salida:** Salario bruto, retención, salario neto, porcentaje efectivo retenido.

### Ejercicio 5: Calcular el precio de un terreno
**Enunciado:** Un terreno rectangular tiene lados ingresados en metros. El precio por metro cuadrado varía según la zona: zona A $8500/m², zona B $6200/m², zona C $4100/m². Si el terreno es cuadrado se aplica un descuento del 3% sobre el total. Calcula el precio final del terreno, el descuento aplicado, y el precio por lado (lado mayor).
**Entrada:** Lado 1 (float), Lado 2 (float), Zona (str: 'A', 'B', o 'C').
**Salida:** Área en m², precio antes de descuento, descuento aplicado, precio final.

### Ejercicio 6: Calculadora de rendimiento de paneles solares
**Enunciado:** Un panel solar de 360 W genera energía según las horas de sol diarias y su eficiencia (por defecto 0.85). En la zona norte se añade un 10% extra de generación. Calcula la energía generada por panel en kWh al día, por semana, por mes (30 días), y el ahorro esperado si cada kWh cuesta $1.20. Considera fracción de panel (ej. 2.5 paneles).
**Entrada:** Horas de sol diarias (float), nº de paneles (float), zona ('norte' o otro).
**Salida:** Energía diaria, semanal, mensual en kWh; costo energético mensual; ahorro estimado con y sin bono zona norte.

### Ejercicio 7: Porcentaje de grasa corporal (cuarenta y dos)
**Enunciado:** Implementa una estimación del porcentaje de grasa corporal usando la fórmula de nadadores enángulo: para hombres: 86.010 × log10(abdomen - cuello) - 70.041 × log10(altura) + 36.76; para mujeres: 163.205 × log10(altura) - 97.684 × log10(cadera + abdomen - cuello) - 78.387. El programa solicita género, medidas en cm y muestra el porcentaje y categoría (bajo, saludable, sobrepeso, obeso).
**Entrada:** Género ('H'/'M'), altura (float cm), abdomen (float cm), cuello (float cm), cadera (float cm, solo si mujer).
**Salida:** Porcentaje de grasa estimado y categoría.

### Ejercicio 8: Calculador de impuestos municipales predial
**Enunciado:** El impuesto predial se calcula sobre el valor de tasación: hasta $500000 no hay impuesto; $500000.01 a $1500000 se cobra el 0.5% sobre el excedente; $1500000.01 a $3000000 el 0.8% sobre el excedente más $5000; mayor a $3000000 el 1.2% sobre el excedente más $17000. Además, si el inmueble está en resultado zona de alto riesgo se añade un recargo del 15% sobre el impuesto total. Muestra desglose completo.
**Entrada:** Valor de tasación (float), zona de riesgo ('sí'/'no').
**Salida:** Impuesto base, recargo, impuesto total, tasación, porcentaje efectivo.

### Ejercicio 9: Simulador de consumo de batería en viaje
**Enunciado:** Un vehículo eléctrico tiene una batería de capacidad dada (kWh). El consumo por km depende de la velocidad promedio: a 60 km/h consume 0.15 kWh/km, a 90 km/h consume 0.22 kWh/km, a 120 km/h consume 0.30 kWh/km. El viaje tiene tramos con diferentes velocidades. Calcula la energía total gastada, el porcentaje de batería consumido, y los km que podría recorrer aún con la batería restante al menor consumo.
**Entrada:** Capacidad batería (float kWh), lista de velocidades y km por tramo (ej. 5 tramos).
**Salida:** Energía gastada total, % batería usado, distancia restante estimada.

### Ejercicio 10: Comparador de planes de internet
**Enunciado:** Tres operadores ofrecen internet: Op1: 50 Mbps, $450/mes, activación $200; Op2: 100 Mbps, $680/mes, activación $100; Op3: 200 Mbps, $1050/mes, activación gratis. Un usuario planea contratar internet por N meses. El programa calcula el costo total por operador (mensualidad × meses + activación) y el costo por Mbps-mes, y recomienda el más económico en costo total y en costo por Mbps.
**Entrada:** Número de meses (int).
**Salida:** Tabla comparativa con costo total, costo por Mbps-mes, y operador recomendado en cada criterio.

### Ejercicio 11: Detector de palíndromos simples
**Enunciado:** Pide al usuario una palabra o frase (sin espacios, todo en minúsculas) y determina si es un palíndromo (se lee igual al revés). Muestra la palabra original, la invertida, y un mensaje indicando si es palíndromo o no, junto con la primera y última letra.
**Entrada:** Cadena de texto (palabra o frase sin espacios).
**Salida:** Palabra original, palabra invertida, es palíndromo (bool), primera y última letra.

### Ejercicio 12: Generador de contraseñas de un solo uso
**Enunciado:** Crea un generador simple que toma una palabra base (str) y genera una "contraseña" aplicando las siguientes reglas en orden: a) convertir a mayúsculas; b) reemplazar todas las 'A' por '@'; c) reemplazar todas las 'E' por '3'; d) agregar al inicio la longitud de la palabra original como dígito; e) agregar al final un signo '-'. Muestra el resultado paso a paso y el password final.
**Entrada:** Palabra base (str).
**Salida:** Pasos intermedios y password final generado.

### Ejercicio 13: Conversor de escalas de temperatura extendido
**Enunciado:** Pide una temperatura y su escala actual (C, F, o K). Luego pide la escala de destino. Convierte entre todas las combinaciones (C↔F, C↔K, F↔K). Además, clasifica la temperatura resultante: 'helada' si está bajo 0°C, 'fría' 0-15°C, 'templada' 15-25°C, 'caliente' 25-35°C, 'muy caliente' sobre 35°C (usando la temperatura convertida en Celsius para la clasificación).
**Entrada:** Temperatura (float), escala actual (str C/F/K), escala destino (str C/F/K).
**Salida:** Temperatura convertida, escala, clasificación de calor, fórmula usada.

### Ejercicio 14: Descomposición de un número de segundos a formato legible
**Enunciado:** Dado un número entero de segundos, lo convierte a una representación del tipo "X semanas, Y días, Z horas, W minutos, V segundos". Maneja casos donde algunas unidades son cero (no mostrarlas). Además calcula el total de días decimales.
**Entrada:** Segundos totales (int, positivo).
**Salida:** Cadena formateada con unidades no nulas y total de días decimales.

### Ejercicio 15: Calculadora de IMC con gráficos de texto
**Enunciado:** Calcula el IMC usual (peso / altura²) e imprime además una "barra de progreso" ASCII representando el IMC en relación al rango saludable (18.5 a 24.9). La barra tiene 20 caracteres de ancho donde cada carácter representa 1.5 unidades de IMC, mostrando guion bajo para vacío y '#' para el peso alcanzado. Indica si está bajo, saludable, sobrepeso u obesidad.
**Entrada:** Peso (float kg), Altura (float m).
**Salida:** IMC, categoría, barra visual de 20 caracteres, peso ideal rango mínimo y máximo.

### Ejercicio 16: Simulador de semáforo peatonal por edad y tiempo
**Enunciado:** Un semáforo para peatones muestra "caminar" cuando el tiempo restante para vehículos es mayor a 30 s; "parar" cuando está bajo 5 s; "cuidado" para el resto. El programa recibe el tiempo actual del semáforo en segundos (int, ciclo de 60s) y calcula en qué fase está el peatón. Además, si el usuario ingresa su edad, si es mayor de 65 años recibe un mensaje de "tiempo extra recomendado".
**Entrada:** Tiempo semáforo vehículo (int 0-60), edad del peatón (int).
**Salida:** Estado del semáforo peatón, mensaje de seguridad, si aplica tiempo extra.

### Ejercicio 17: Convertidor de unidades de datos digitales
**Enunciado:** El usuario ingresa un número de bytes y una unidad destino ('B', 'KB', 'MB', 'GB', 'TB'). Convierte usando el estándar decimal (1 KB = 1000 B) y también muestra el equivalente en el estándar binario (1 KiB = 1024 B) hasta la unidad destino equivalente. Indica cuántos bytes exactos representa.
**Entrada:** Cantidad (float) en bytes, unidad destino (str entre B,KB,MB,GB,TB).
**Salida:** Valor en unidad destino decimal, valor en unidad destino binaria equivalente, bytes totales exactos.

### Ejercicio 18: Calculador de propinas con sistema de "rosca"
**Enunciado:** En un sistema de propinas "de rosca", cada comensal aporta una cantidad que depende de su posición en la mesa: el primero paga el 20% de la cuenta, el segundo el 18%, el tercero 16%, y así decreciendo 2% por posición hasta el séptimo. Si son más de 7, los adicionales pagan 5% cada uno. Dada la cuenta total y el nº de comensales, calcula el aporte de cada uno y el total, verificando que sumen la cuenta.
**Entrada:** Cuenta total (float), número de comensales (int, 1-12).
**Salida:** Lista de aportes por comensal, total sumado, diferencia con cuenta real.

### Ejercicio 19: Evaluador de riesgo sísmico simulado
**Enunciado:** Dado un sismo con magnitud en escala Richter y una distancia al epicentro en km, se estima la intensidad percibida según: si magnitud < 4.0 → 'Leve'; 4.0-4.9 → 'Moderado'; 5.0-5.9 → 'Fuerte'; 6.0-6.9 → 'Muy fuerte'; >= 7.0 → 'Catastrófico'. Si la distancia es menor a 50 km, se añade '+ cercano' al nivel. Si la magnitud es mayor o igual a 6.5 y distancia menor a 100 km, se emite alerta de tsunami. Muestra nivel, distancia, y alerta si corresponde.
**Entrada:** Magnitud (float), distancia al epicentro (float km).
**Salida:** Nivel de intensidad percibida, distancia, alerta de tsunami (sí/no), recomendación de seguridad.

### Ejercicio 20: Simulador de descuento por volumen de compra
**Enunciado:** Una ferretería ofrece descuentos por volumen en tornillos: 1-10 tornillos: precio unitario $5.50; 11-50: $5.00 c/u; 51-200: $4.20 c/u; más de 200: $3.50 c/u. Además, si la compra supera $800 en total, se aplica un descuento adicional del 5% sobre el total. Calcula el total a pagar, el descuento por volumen aplicado y el adicional si corresponde, y el precio promedio por unidad.
**Entrada:** Cantidad de tornillos (int).
**Salida:** Precio unitario aplicado, subtotal, descuento volumen (cantidad), descuento adicional (monto), total final, precio promedio por unidad.

---

### Ejercicio 21: Contador de palabras cíclico con centinela
**Enunciado:** El usuario ingresa palabras una por una (input). El programa cuenta cuántas palabras ingresó, cuántas tienen más de 5 letras, y cuántas son exactamente igual a la palabra "stop" (centinela para terminar). Al ingresar "stop" en cualquier caso (mayúsculas/minúsculas), el programa deja de pedir y muestra los tres conteos. No cuenta la palabra "stop" en los totales.
**Entrada:** Múltiples palabras (str), una por línea, terminando con "stop" (en cualquier caso).
**Salida:** Total de palabras ingresadas (sin contar stop), palabras con >5 letras, palabras con ≤5 letras, confirmación de centinela recibida.

### Ejercicio 22: Validador de código de producto con ciclo while
**Enunciado:** Un código de producto debe ser un número entero de exactamente 6 dígitos que no empiece con cero. El programa pide códigos al usuario repetidamente hasta que ingrese uno válido. Si ingresa un valor no numérico, muestra "error: debe ser numérico". Si ingresa un número de menos o más de 6 dígitos, muestra "error: debe tener 6 dígitos". Si el primer dígito es 0, muestra "error: no debe empezar con cero". Al obtener un código válido, muestra "código aceptado: XXXX" y termina.
**Entrada:** Múltiples intentos de código (str o int).
**Salida:** Mensajes de error sobre cada intento fallido, y mensaje de aceptación con el código válido.

### Ejercicio 23: Sumador de temperaturas con validación por rango
**Enunciado:** Crea un programa que pida al usuario temperaturas diarias (en °C) y las vaya sumando. El usuario ingresa temperaturas dentro del rango -50 a 60 (inclusive). Si ingresa un valor fuera de rango, muestra un mensaje de error y no la suma (pero cuenta como intento fallido). El programa termina cuando el usuario ingresa "fin" (centinela) o después de 10 temperaturas válidas, cualquiera primero. Muestra: total sumado, promedio, nº de temperaturas válidas, nº de intentos fallidos, y la temperatura máxima y mínima válidas ingresadas.
**Entrada:** Temperaturas (float) o "fin" para terminar.
**Salida:** Total suma, promedio, conteo válido, conteo fallidos, máxima, mínima.

### Ejercicio 24: Simulador de semáforo cíclico con cambio manual
**Enunciado:** Un semáforo cicla en cada iteración del while entre los estados: Verde (3 s conceptuales) → Amarillo (2 s) → Rojo (4 s) → y vuelve a Verde. El programa permite al usuario pulsar Enter para avanzar una fase, o escribir "s" para salir. Muestra el estado actual del semáforo en cada paso y cuántas veces pasó por cada color. Al salir, muestra un resumen de cuántas fases completó y tiempos conceptuales totales por color.
**Entrada:** Enter para avanzar, 's' para salir.
**Salida:** Estado del semáforo en cada paso, total de ciclos por color, resumen al final.

### Ejercicio 25: Adivinanza de número en rango con pistas de dirección
**Enunciado:** El programa selecciona aleatoriamente un número entero entre 1 y 100 (sin mostrar al usuario). El usuario tiene 7 intentos para adivinarlo. En cada intento incorrecto, el programa indica si el número es "más alto" o "más bajo" que el ingresado, y también muestra cuántos intentos restan. Si adivina correctamente, muestra felicitaciones y cuántos intentos usó. Si se agotan los 7 intentos sin acierto, muestra el número secreto y un mensaje de derrota. Al final, pregunta si quiere jugar otra vez (solo una más).
**Entrada:** Número entero del 1 al 100 en cada intento, y 's'/'n' al final.
**Salida:** Pistas (más alto/más bajo), intentos restantes, resultado final, y si se juega de nuevo.

### Ejercicio 26: Acumulador de gastos con categorías
**Enunciado:** El usuario registra gastos diarios ingresando importe y categoría (alimentos, transporte, ocio, otros). El programa acumula el total por categoría y el total general. Si el gasto ingresado es negativo, lo toma como señal de fin (centinela) sin contarlo. Si el importe es cero, pide reingreso sin contar. Si la categoría no es una de las válidas, muestra error y vuelve a pedir el mismo registro. Al terminar, muestra el total por categoría, el total general, el porcentaje que cada categoría representa del total, y la categoría con mayor gasto.
**Entrada:** Importe (float) y categoría (str) por gasto, centinela con importe negativo.
**Salida:** Totales por categoría, total general, porcentajes, categoría mayoritaria, número de gastos registrados.

### Ejercicio 27: Números romanos en bucle
**Enunciado:** Pide al usuario números enteros positivos del 1 al 3999. Por cada uno, convierte el número a su representación en números romanos (uso de I, V, X, L, C, D, M) e imprime el resultado. El programa se repite indefinidamente hasta que el usuario ingresa "salir". Si el número está fuera de rango (0, negativo o >3999), muestra un mensaje de error y vuelve a pedir. Implementa la conversión manualmente (no uses librerias).
**Entrada:** Números enteros (1-3999) o "salir".
**Salida:** Número original, su equivalente en romanos, y acumulado de cuántos números se convirtieron.

### Ejercicio 28: Validación de contraseña con intentos limitados
**Enunciado:** La contraseña correcta es "python2025" (fija). El usuario tiene máximo 3 intentos para ingresarla. En cada intento incorrecto, muestra cuántos intentos restan. Si ingresa la contraseña correcta en cualquier intento, muestra "Bienvenido" y termina. Si se agotan los 3 intentos, muestra "Cuenta bloqueada temporalmente" y el programa termina sin más intentos. La comparación debe ser exacta (case-sensitive).
**Entrada:** Cadena de texto en cada intento (máximo 3).
**Salida:** Mensaje de intento fallido con restantes, mensaje de éxito, o mensaje de bloqueo.

### Ejercicio 29: Contador de vocales en frases cíclico
**Enunciado:** El programa pide al usuario frases indefinidamente. Por cada frase ingresada, cuenta cuántas vocales (a, e, i, o, u) contiene, sin distinguir mayúsculas/minúsculas, y muestra el conteo por cada vocal. Si la frase es exactamente "fin" (en minúsculas), el programa termina. Muestra al final el total de vocales encontradas en todas las frases, la frase más larga ingresada y su conteo de vocales, y la frase con más vocales 'a'.
**Entrada:** Frases (str), terminando con "fin".
**Salida:** Conteos de vocales por frase, totales acumulados, frase más larga, frase con más 'a'.

### Ejercicio 30: Tabla de operadores con while y centinela
**Enunciado:** Pide al usuario un número base (entero positivo). Genera una tabla que muestra para cada operador (+, -, *, /, //, %, **): el resultado de aplicar ese operador entre el número base y todos los números del 1 al 10. Deja que el usuario pueda ingresar otro número base para generar otra tabla. El centinela para terminar es ingresar 0 o negativo como número base. Para la división, si el número del 1 al 10 es 0 (no sucede aquí, pero considera que en versión extendida podría ser), manejaría ZeroDivisionError (aquí no, pero muestra comprensión del tema). Muestra la tabla con formato alineado.
**Entrada:** Número base entero positivo, centinela 0 o negativo para terminar.
**Salida:** Tabla alineada con 7 filas (operadores) x 10 columnas (operandos), y resumen de cuántas tablas se generaron.

### Ejercicio 31: Emulación de juego de mesa con dados
**Enunciado:** Simula un juego simple donde un jugador tira un dado (número aleatorio 1-6) hasta obtener un 6. El programa muestra cada tirada y el número de intentos que le llevó obtener el primer 6. Luego, segundo jugador lanza dados hasta obtener un 6, y se compara quién obtuvo el 6 en menos tiradas. Si hay empate, declararlo. Al final, muestra el ganador y el historial de tiradas de ambos. Usa un ciclo while para cada jugador.
**Entrada:** No requiere entrada (el dado es simulado con random).
**Salida:** Tiradas del jugador 1, tiradas del jugador 2, ganador, empate o no, total de tiradas.

### Ejercicio 32: Calificaciones con reprobación iterativa
**Enunciado:** Un profesor ingresa calificaciones de alumnos (notas de 0 a 10, float). El programa calcula el promedio del grupo, la cantidad de aprobados (≥6.0) y reprobados (<6.0). El ciclo termina cuando el profesor ingresa -1 como calificación (centinela). Si ingresa una calificación inválida (fuera de 0-10, no sea -1), muestra error y vuelve a pedir sin contar. Al final muestra: promedio, aprobados, reprobados, % de aprobación, nota máxima, nota mínima, y si el promedio del grupo es considerado "excelente" (≥9.0), "bueno" (7.0-8.9), "regular" (5.0-6.9), o "bajo" (<5.0).
**Entrada:** Calificaciones (float) o -1 para terminar.
**Salida:** Estadísticas completas del grupo con clasificación de calidad.

### Ejercicio 33: Búsqueda de número perfecto en rango con while
**Enunciado:** El usuario ingresa un número entero positivo N. El programa busca todos los números perfectos desde 1 hasta N (inclusive) usando un ciclo while. Un número perfecto es aquel igual a la suma de sus divisores propios (excluyéndose a sí mismo). Muestra cada número perfecto hallado y su suma de divisores. Si no encuentra ninguno en el rango, muestra mensaje adecuado. Al final, muestra cuántos números perfectos se encontraron y el mayor de ellos (o ninguno).
**Entrada:** Límite superior N (int, positivo).
**Salida:** Lista de números perfectos encontrados, sus sumas de divisores, cantidad hallada, mayor hallado.

### Ejercicio 34: Descomposición de número en factores primos interactiva con while
**Enunciado:** Pide al usuario un número entero mayor a 1. Muestra la descomposición en factores primos usando un esquema visual, por ejemplo: 60 = 2 × 2 × 3 × 5. El programa sigue pidiendo números y descomponiendo hasta que el usuario ingresa "fin". Maneja el caso especial del número 1 (no tiene descomposición, muestra mensaje). El algoritmo usa un ciclo while que prueba divisores desde 2 hacia arriba, dividiendo repetidamente mientras sea divisible.
**Entrada:** Números enteros >1 o "fin" para terminar.
**Salida:** Descomposición en factores primos visual, y acumulador de números procesados.

### Ejercicio 35: Simulador de caída libre con resistencia
**Enunciado:** Simula la caída de un objeto desde una altura H metros. En cada segundo, la velocidad aumenta 9.8 m/s (gravedad) pero hay una resistencia del aire que reduce la velocidad en 0.5 m/s cada segundo (velocidad = velocidad + 9.8 - 0.5). El objeto se mueve velocidad × 1 segundo de distancia cada iteración. El programa muestra la distancia caída, velocidad actual, y tiempo transcurrido en cada segundo. Termina cuando el objeto ha caído la altura total o más. Muestra el tiempo total de caída, velocidad final y distancia recorrida. (Usa while con condición de altura restante > 0).
**Entrada:** Altura inicial H (float, mayor a 0).
**Salida:** Tabla de tiempo, distancia acumulada, velocidad, y resumen de tiempo total, velocidad final, distancia recorrida.

---

### Ejercicio 36: Detector de error de sintaxis por olvido de paréntesis
**Enunciado:** Explica (como texto) y demuestra con un ejemplo corregido: el error que ocurre cuando se escribe `print("Hola mundo"` sin cerrar el paréntesis. El programa debe tener una cadena con el código erróneo, mostrarla, indicar en qué columna está el error (el paréntesis que falta), y show the versión corregida. Además, pide al usuario una expresión matemática simple (como 2+3) y la evalúa con eval() seguro, manejando con try-except si la cadena no es válida.
**Entrada:** Expresión matemática como cadena (str) para evaluar.
**Salida:** Código erróneo con marcador de error, código corregido, resultado de la evaluación o mensaje de error si la expresión no es válida.

### Ejercicio 37: Rastreador de variable con PDB tutorial
**Enunciado:** Escribe un programa Python que calcule el promedio de tres números, pero inserta manualmente el comando `breakpoint()` (o pdb.set_trace()) en medio del cálculo. El programa debe imprimir instrucciones sobre qué comandos de PDB usar: `n` (next), `p` (print variable), `l` (list), `c` (continue). Incluye comentarios que guíen al usuario paso a paso. La ejecución del programa muestra los valores intermedios y el resultado final, demostrando el rastreo.
**Entrada:** Tres números ingresados por usuario (float).
**Salida:** Instrucciones PDB, valores paso a paso, resultado final, y explicación de qué hace cada comando.

### Ejercicio 38: Depurador de lista_por_indice fuera de rango
**Enunciado:** Escribe un código que intencionalmente produzca un IndexError al intentar acceder a un índice fuera de una lista (ej. lista de 3 elementos, intentar índice 5). El programa debe capturar la excepción con try-except, mostrar el tipo de error, el mensaje de error, y además mostrar la lista con sus índices válidos usando enumerate. Luego permite al usuario ingresar un índice válido (validando que esté dentro del rango) y muestra el elemento correspondiente. Finalmente, pregunta si quiere ingresar otra índice (bucle while).
**Entrada:** Índice entero para acceder a la lista (válido o inválido).
**Salida:** Manejo del IndexError, lista con índices, elemento accedido con índice válido, y posibilidad de probar más índices.

### Ejercicio 39: Depuración de error de división por cero en función
**Enunciado:** Define una función `dividir(a, b)` que realiza a / b. El programa principal pide al usuario dos números (numerador y denominador). Si el denominador es cero, la función lanza una excepción ZeroDivisionError que es capturada en el programa principal, mostrando un mensaje claro y pidiendo al usuario que ingrese un denominador distinto de cero (bucle while hasta que sea válido). Una vez válido, muestra el resultado. Además, maneja el caso de que el usuario ingrese texto en lugar de número (ValueError) en la captura.
**Entrada:** Numerador (float), denominador (float, debe ser ≠ 0 a través de reintentos).
**Salida:** Resultado de la división con denominador validado, número de intentos usados, detalles de errores si los hubo.

### Ejercicio 40: Error lógico común: acumulador no inicializado
**Enunciado:** Escribe un programa que tenga un error lógico intencional: suma los números ingresados sin inicializar la variable acumulador (usa una variable que no existe previamente), captura el error con try-except (NameError), explica qué pasó, y corrígelo inicializando la variable en 0. Luego pide 5 números, los suma correctamente mostrando el acumulado paso a paso, y al final muestra el total y el promedio. Comenta el código explicando cada corrección. (Incluye rastro de ejecución simulado con prints).
**Entrada:** 5 números (float), uno por línea.
**Salida:** Demostración del error (NameError), explicación, corrección, y resultado correcto con paso a paso.

### Ejercicio 41: Localizador de error de sintaxis en condicional anidado
**Enunciado:** Dado este código con error: `if x > 10 print("mayor") else: print("menor o igual")` (falta los dos puntos en el if), detecta y corrige el error, muestra el código original con línea y columna del error, y el código corregido. Además, ejecuta ambas versiones (la errónea capturada con try-except SyntaxError, y la corregida) con x = 15 y x = 5, mostrando los resultados esperados.
**Entrada:** No requiere entrada externa (usa valores fijos para demostrar).
**Salida:** Código original con error marcado, código corregido, resultados de ejecución para x=15 y x=5.

### Ejercicio 42: Debugging de ciclo infinito con break faltante
**Enunciado:** Escribe un programa que intente imprimir números del 1 al 10 pero accidentalmente olvida el incremento de la variable de control (ciclo while infinito). Captura el problema mediante un mecanismo de seguridad: si el ciclo ejecuta más de 15 iteraciones, utiliza break forzado y muestra mensaje de advertencia "ciclo posiblemente infinito detectado". Luego muestra la versión corregida del código que imprime correctamente del 1 al 10. Discute la diferencia entre while True con break y while con condición de surpassing.
**Entrada:** No requiere entrada externa.
**Salida:** Código erróneo detectado, versión corregida, números 1-10 impresos, y explicación de la diferencia de estructuras.

### Ejercicio 43: Manejo de ValueError en conversión de temperatura
**Enunciado:** El usuario ingresa una temperatura en grados Celsius como cadena de texto. El programa intenta convertirla a float para realizar cálculos. Si el usuario ingresa algo no convertible (ej. "treinta"), captura ValueError, muestra un mensaje "Entrada no válida, debe ser un número", y pide reingresar (bucle while hasta que sea válido). Una vez válida, convierte a Fahrenheit y muestra el resultado con 2 decimales. Cuenta cuántos intentos fallidos se realizaron.
**Entrada:** Temperatura Celsius como cadena (str), puede ser inválida inicialmente.
**Salida:** Temperatura en Fahrenheit, número de intentos fallidos, y validación exitosa.

### Ejercicio 44: ZeroDivisionError en calculadora de medios
**Enunciado:** Crea un programa que calcule el promedio de N números ingresados por el usuario. Si el usuario ingresa 0 como cantidad de números (N=0), captura ZeroDivisionError al intentar dividir por cero, muestra "No se puede calcular promedio de cero números", y pide reingresar N (debe ser >0). Si ingresa un valor no numérico para N, captura ValueError. Una vez N válido, pide N números, calcula el promedio, y muestra resultado con 2 decimales. Muestra el número de intentos de N fallidos.
**Entrada:** N (int, debe ser >0), luego N números (float).
**Salida:** Promedio calculado, número de intentos de N fallidos, manejo de errores.

### Ejercicio 45: TypeError al concatenar string con número
**Enunciado:** El programa intenta crear un saludo concatenando "Tu edad es " + edad, donde edad es un número ingresado por el usuario. Esto produce TypeError. Captura la excepción, muestra un mensaje explicativo "No puedes concatenar string con número directamente", y demuestra la corrección usando str(edad) o f-string. Luego pide nombre y edad al usuario, y muestra el saludo correctamente formado. Si el usuario ingresa texto en edad, captura ValueError y pide reingreso.
**Entrada:** Nombre (str), edad (int o str que debe convertirse).
**Salida:** Manejo del TypeError, saludo corregido con f-string, y Cuenta de intentos fallidos si edad fue inválida.

### Ejercicio 46: IndexError al acceder a posición vacía en lista
**Enunciado:** Dada una lista con 5 elementos (índices 0-4), el programa pide al usuario un índice para acceder. Si el usuario ingresa un índice fuera del rango (-6 o 5 o más), captura IndexError, muestra "Índice fuera de rango: la lista tiene 5 elementos (índices 0-4)", y muestra los índices válidos usando enumerate. Luego permite al usuario probar otro índice (bucle while) hasta que ingrese -1 para salir. Si ingresa un valor no numérico, captura ValueError y pide reingreso.
**Entrada:** Índice entero para acceder a la lista, -1 para salir.
**Salida:** Manejo de IndexError, lista de índices válidos, elemento accedido si índice válido, y resumen de accesos realizados.

### Ejercicio 47: Excepción Exception general como respaldo
**Enunciado:** Crea un programa que evalúe expresiones matemáticas ingresadas por el usuario como cadena (ej. "2+3*4"). Usa eval() en un try-except. Primero captura específicamente SyntaxError (para expresiones mal formadas), luego ZeroDivisionError, y finalmente Exception como captura general para cualquier otro error inesperado. Muestra el tipo de error capturado y un mensaje amigable. Pide expresiones indefinidamente hasta que el usuario ingresa "salir". Muestra al final cuántas expresiones se evaluaron con éxito y cuántas fallaron por tipo de error.
**Entrada:** Expresiones matemáticas como cadena (str), o "salir" para terminar.
**Salida:** Resultado de cada evaluación o mensaje de error con tipo, y resumen final de éxitos y fallas por categoría.

### Ejercicio 48: Bloque else en división exitosa
**Enunciado:** Define una función `dividir_segura(a, b)` que intenta a / b. Si la división es exitosa (no hay excepción), el bloque else imprime "División exitosa: resultado = X". Si hay ZeroDivisionError, captura y muestra "Error: división por cero". Si hay TypeError (alguien pasó un string), captura y muestra "Error: tipos no compatibles". Si hay cualquier otra excepción, captura Exception y muestra "Error inesperado: X". El bloque finally siempre imprime "Operación de división finalizada". Prueba la función con varios casos: (10, 2), (5, 0), ("10", 2), (10, "2"), y muestra resultados.
**Entrada:** No requiere entrada externa (pruebas automáticas con casos pre definidos).
**Salida:** Resultado de cada caso de prueba con los mensajes de bloques else, except, y finally.

### Ejercicio 49: Bloque finally en conexión de base de datos simulada
**Enunciado:** Simula una "conexión" a base de datos: abre una "conexión" (imprime "Conexión establecida"), luego intenta realizar una "operación" que puede fallar. Si el usuario ingresa "fail" como nombre de operación, lanza una excepción Exception("Error en operación"). Si ingresa cualquier otra cosa, la operación es exitosa. En todos los casos, el bloque finally imprime "Conexión cerrada" (simulando cierre de conexión). Usa try-except-finally. El programa pide el nombre de la operación al usuario y muestra el flujo completo. Si la operación falla, captura Exception y muestra el error, pero siempre cierra la conexión.
**Entrada:** Nombre de operación (str), "fail" para simular error.
**Salida:** Flujo completo: apertura, operación (éxito o error capturado), y cierre en finally.

### Ejercicio 50: Validación de entrada con while y excepciones anidadas
**Enunciado:** El programa pide al usuario un número entero positivo para usar como límite en un contador. Valida la entrada con un while: si el usuario ingresa un valor no numérico, captura ValueError, muestra "Error: debe ingresar un número entero", y pide reingreso. Si ingresa un número pero es negativo o cero, muestra "Error: debe ser positivo", y pide reingreso sin capturar excepción (validación lógica). Si ingresa un número flotante válido pero con decimal, redondea y acepta. Al obtener un número válido, genera e imprime la cuenta del 1 al N. Muestra cuántos reintentos de entrada fueron necesarios.
**Entrada:** Número para ser validado (puede ser inválido inicialmente).
**Salida:** Cuenta del 1 al N, número de reintentos de entrada, tipos de errores encontrados.

---

### Ejercicio 51: Cadena de texto con operaciones de mayúsculas y minúsculas
**Enunciado:** Pide al usuario una frase. Muestra la frase original, su versión en mayúsculas (upper), su versión en minúsculas (lower), y una versión capitalizada (primera letra mayúscula, resto minúsculas) usando capitalize(). Además, cuenta cuántas letras mayúsculas y minúsculas tiene la frase original (sin usar métodos directos de conteo de mayúsculas, solo recorriendo carácter por carácter y usando isupper/islower). Muestra los conteos por separado.
**Entrada:** Una frase (str).
**Salida:** Frase original, versión upper, versión lower, versión capitalize, conteo de mayúsculas, conteo de minúsculas.

### Ejercicio 52: Longitud de cadena y comparación de palabras
**Enunciado:** Pide al usuario dos palabras. Muestra la longitud de cada palabra usando len(), indica cuál palabra es más larga (o si son iguales), y calcula la diferencia en número de caracteres. Además, concatena las dos palabras con un espacio entre ellas, y muestra la nueva cadena y su longitud. Luego, usando slicing, extrae los primeros 3 caracteres de la palabra más larga y los últimos 3 de la más corta, e imprime ambos resultados. Si alguna palabra tiene menos de 3 caracteres, maneja el caso mostrando solo los caracteres disponibles sin error.
**Entrada:** Dos palabras (str), una por input.
**Salida:** Longitudes, palabra más larga, diferencia, concatenación, longitudes de substrings extraídos.

### Ejercicio 53: Reemplazo de substrings en texto
**Enunciado:** Pide al usuario un párrafo de al menos una línea. Luego pide una palabra a reemplazar y la nueva palabra de reemplazo. Usa replace() para realizar el reemplazo en todo el párrafo. Muestra el párrafo original, el párrafo modificado, y cuántas veces se realizó el reemplazo (usa count() de la palabra original para estimar, aunque replace no lo devuelve directamente). Si la palabra a reemplazar no está en el texto, muestra "La palabra no se encuentra en el texto" y no modifica nada. El reemplazo debe ser exacto (no parcial, usa la cadena completa con espacios).
**Entrada:** Párrafo (str), palabra a reemplazar (str), nueva palabra (str).
**Salida:** Párrafo original, párrafo modificado (o mensaje si no se encontró), número de reemplazos estimado.

### Ejercicio 54: División de cadena en palabras y conteo
**Enunciado:** Pide al usuario una oración o párrafo. Usa split() para dividir la cadena en palabras (separador por espacios en blanco). Muestra la lista de palabras resultante, el número total de palabras, y luego identifica cuántas palabras tienen más de 5 caracteres, cuántas tienen exactamente 5, y cuántas tienen menos de 5. Además, muestra la palabra más larga y la más corta de la lista. Si el párrafo está vacío (solo espacios), muestra un mensaje adecuado.
**Entrada:** Un párrafo u oración (str).
**Salida:** Lista de palabras, total de palabras, conteos por longitud, palabra más larga, palabra más corta.

### Ejercicio 55: Búsqueda de subcadena con find
**Enunciado:** Pide al usuario una cadena principal y una subcadena a buscar. Usa find() para encontrar la posición de la primera ocurrencia de la subcadena en la cadena principal. Si se encuentra, muestra la posición inicial (índice), la posición final (índice + longitud de subcadena - 1), y extrae e imprime la subcadena encontrada usando slicing. Si no se encuentra (find devuelve -1), muestra "Subcadena no encontrada en la cadena principal". Además, usando find con argumento de inicio, busca si la subcadena aparece después de la primera posición (segunda ocurrencia) y muestra su ubicación si existe.
**Entrada:** Cadena principal (str), subcadena a buscar (str).
**Salida:** Posición de primera ocurrencia o mensaje de no encontrado, posición de segunda ocurrencia si existe, extracción con slicing.

### Ejercicio 56: Slicing avanzado de cadenas
**Enunciado:** Pide al usuario una cadena de texto de al menos 10 caracteres. Realiza los siguientes slicing y muestra cada resultado: a) Los primeros 5 caracteres; b) Los últimos 5 caracteres; c) Cada segundo carácter de toda la cadena; d) La cadena invertida (slicing con paso -1); e) Desde el índice 3 hasta el 7 (inclusive de inicio, exclusive de fin); f) Desde el índice 2 hasta el 8 con paso 2; g) Los caracteres desde el tercer último hasta el último. Si la cadena es muy corta para algunos slicing, maneja mostrando solo lo que es posible sin error. Explica brevemente qué hace cada slicing en comentarios o prints.
**Entrada:** Una cadena de texto (mínimo 10 caracteres recomendado).
**Salida:** Resultados de los 7 slicings con explicación de cada uno.

### Ejercicio 57: Formateo de texto con f-strings avanzado
**Enunciado:** Crea un programa que muestre una "ficha de personal" formateada usando f-strings. Pide al usuario nombre, cargo, salario (float), y antigüedad en años (int). Muestra una ficha con: nombre alineado a la izquierda en 20 caracteres, cargo alineado a la derecha en 15 caracteres, salario formateado con 2 decimales y con separador de miles (usa :,), y antigüedad como entero. Además, muestra una línea de separación usando caracteres repetidos con f-string (ej. f"{'-'*40}"). Finalmente, calcula y muestra el promedio de salario anual si tuviera bonificación del 5% por antigüedad (solo si antigüedad > 3 años).
**Entrada:** Nombre (str), cargo (str), salario (float), antigüedad (int).
**Salida:** Ficha formateada con f-strings, línea separadora, cálculo de bonificación si aplica.

### Ejercicio 58: Contador de palabras en frase con función
**Enunciado:** Define una función `contar_palabras(frase)` que toma una cadena, usa split() para dividirla en palabras, y devuelve el número de palabras (len de la lista). El programa principal pide al usuario una frase, llama a la función, y muestra el resultado. Luego, sin usar la función, también cuenta las palabras usando un bucle for que recorre los caracteres y cuenta espacios (un espacio indica cambio de palabra), y compara ambos resultados. Si el usuario ingresa una frase vacía o solo espacios, ambos métodos deben devolver 0.
**Entrada:** Una frase (str).
**Salida:** Número de palabras usando la función, número usando el bucle manual, y comparación de resultados.

### Ejercicio 59: Combinación de replace, upper, y split
**Enunciado:** Pide al usuario un texto que contenga varias palabras. Realiza las siguientes operaciones en secuencia: a) Convierte todo el texto a mayúsculas usando upper(); b) Reemplaza todas las ocurrencias de una letra específica (que el usuario elige) por otra letra (también elegida por el usuario) usando replace(); c) Divide el texto resultante en una lista de palabras usando split(); d) Muestra la lista final y el número de palabras. Luego, usando la lista original (antes de replace), cuenta cuántas palabras contenían la letra original usando un bucle y in, y muestra ese conteo también.
**Entrada:** Texto (str), letra a reemplazar (str de 1 carácter), letra nueva (str de 1 carácter).
**Salida:** Lista final de palabras después de las transformaciones, número de palabras, conteo de palabras originales que contenían la letra.

### Ejercicio 60: Combinación de strip, len, y slicing
**Enunciado:** Pide al usuario un texto que pueda tener espacios al inicio y al final (intencionalmente con espacios extra). Usa strip() para eliminar espacios al inicio y final. Muestra la cadena original, la cadena sin espacios, y la diferencia de longitud (len original - len stripada). Luego, con la cadena stripada, extrae y muestra: a) Los primeros 5 caracteres (o menos si la cadena es corta); b) Los últimos 5 caracteres; c) La cadena completa desde el índice 2 hasta el índice len-3 (excluyendo extremos). Si la cadena es muy corta para alguno de estos, muestra solo lo disponible. Finalmente, verifica si la cadena stripada está vacía y muestra mensaje si lo está.
**Entrada:** Texto con espacios extra al inicio/final (str).
**Salida:** Cadena original, cadena stripada, diferencia de longitud, resultados de los tres slicings, verificación de vacía.

### Ejercicio 61: Identificar el tercer elemento de una tupla
**Enunciado:** Dada una tupla con al menos 5 elementos de tipos mixtos (int, str, float, bool), escribe un programa que acceda e imprima el tercer elemento (índice 2). Luego, usando un bucle for, recorre e imprime todos los elementos de la tupla con su índice correspondiente (usando enumerate o range). Finalmente, verifica si el tercer elemento es de tipo string e imprime "El tercer elemento es texto" o "El tercer elemento no es texto" según corresponda.
**Entrada:** No requiere entrada externa (tupla definida en el código).
**Salida:** El tercer elemento, recorrido completo con índices, y verificación del tipo del tercer elemento.

### Ejercicio 62: Longitud de tupla con elementos duplicados
**Enunciado:** Crea una tupla que contenga nombres de frutas, donde algunas frutas pueden aparecer más de una vez (ej. ("manzana", "banana", "manzana", "naranja", "banana", "manzana")). Calcula y muestra la longitud de la tupla usando len(). Luego muestra cuántas veces aparece cada fruta usando count() para cada elemento único (usa un bucle y un conjunto de elementos únicos para evitar repeticiones en el conteo). Finalmente, muestra la tupla ordenada (convertida a lista, ordenada, y vuelva a tupla) y compara su longitud con la original (deben ser iguales).
**Entrada:** No requiere entrada externa (tupla predefinida).
**Salida:** Longitud de la tupla, conteo de cada elemento único, tupla ordenada, comparación de longitudes.

### Ejercicio 63: Acceso con índices negativos en tupla
**Enunciado:** Define una tupla de 7 elementos (pueden ser números enteros). Muestra cómo acceder a los elementos usando índices negativos: el último elemento (-1), el penúltimo (-2), el antepenúltimo (-3), y el primero desde el final (-7 o equivalente). Luego, usando un bucle con range que genere índices negativos desde -1 hasta -len(tupla) en orden decreciente, imprime cada elemento con su índice negativo correspondiente. Finalmente, verifica que el elemento en índice -3 es igual al elemento en índice len(tupla)-3 usando una comparación e imprime el resultado.
**Entrada:** No requiere entrada externa.
**Salida:** Accesos con índices negativos individuales, recorrido completo con índices negativos, verificación de equivalencia de índices.

### Ejercicio 64: Intentar modificar una tupla (inmutabilidad)
**Enunciado:** Crea una tupla con 4 elementos (ej. tupla = (10, 20, 30, 40)). El programa intenta modificar el segundo elemento asignándole un nuevo valor (tupla[1] = 99). Esto debe generar un TypeError. Captura la excepción con try-except, muestra el tipo de error (TypeError) y un mensaje "Las tuplas son inmutables: no se pueden modificar sus elementos". Luego, muestra la tupla original intacta e imprime sus elementos para confirmar que no hubo cambios. Finalmente, demuestra cómo "modificar" una tupla creando una nueva tupla que reemplace el elemento deseado usando slicing y concatenación, y muestra la nueva tupla.
**Entrada:** No requiere entrada externa.
**Salida:** Manejo del TypeError, tupla original intacta, nueva tupla creada por concatenación.

### Ejercicio 65: Desempaquetado de tupla en variables
**Enunciado:** Define una tupla con exactamente 5 elementos de diferentes tipos (ej. ("Ana", 25, 1.65, True, " Ingeniería")). Desempaqueta la tupla en 5 variables con nombres descriptivos (nombre, edad, altura, es_estudiante, carrera). Imprime cada variable individualmente. Luego, imprime una frase usando f-string que combine todas las variables: "Ana tiene 25 años, mide 1.65 m, es estudiante: True, y estudia Ingeniería". Finalmente, intenta desempaqueta la tupla en 4 variables (en vez de 5) y captura el ValueError que ocurre, mostrando el mensaje de error "demasiados valores para desempaquetar" o similar.
**Entrada:** No requiere entrada externa.
**Salida:** Variables desempaquetadas individuales, frase combinada, manejo del ValueError al desempaquetar en número incorrecto de variables.

### Ejercicio 66: Concatenación de tuplas
**Enunciado:** Crea dos tuplas: tupla1 con 3 elementos (ej. (1, 2, 3)) y tupla2 con 2 elementos (ej. ("a", "b")). Concatena las dos tuplas usando el operador + y asigna el resultado a una nueva variable tupla3. Muestra las tres tuplas (tupla1, tupla2, tupla3) y sus longitudes respectivas. Luego, multiplica tupla1 por 3 usando el operador * y muestra el resultado (tupla1_repetida). Finalmente, verifica si tupla1 está contenida dentro de tupla3 usando el operador in y muestra el resultado (debe ser True si los elementos son iguales).
**Entrada:** No requiere entrada externa.
**Salida:** Las tres tuplas con sus longitudes, tupla1 repetida 3 veces, verificación de contención.

### Ejercicio 67: Convertir lista a tupla y viceversa
**Enunciado:** Define una lista con 6 elementos (pueden ser strings de colores). Convierte la lista a tupla usando tuple() y muestra la tupla resultante y su longitud. Luego convierte la tupla de vuelta a lista usando list() y muestra la lista resultante. Verifica que la longitud se mantenga igual en ambas conversiones. Finalmente, agrega un elemento nuevo a la lista convertida (usando append, ya que las listas son mutables), muestra la lista modificada, y vuelve a convertir a tupla para mostrar que ahora la tupla tiene un elemento más.
**Entrada:** No requiere entrada externa (lista predefinida).
**Salida:** Lista original, tupla convertida, lista convertida de vuelta, lista modificada, tupla final con elemento adicional.

### Ejercicio 68: Contar ocurrencias e índice en tupla
**Enunciado:** Crea una tupla con números enteros donde algunos números se repiten (ej. (5, 3, 7, 5, 9, 3, 5, 2, 7)). Pide al usuario un número a buscar (debe ser uno de los que están en la tupla para este ejercicio). Usa count() para mostrar cuántas veces aparece el número en la tupla. Usa index() para mostrar la posición de la primera ocurrencia del número. Luego, usa un bucle para encontrar y mostrar todas las posiciones donde aparece el número (pueden haber múltiples índices). Finalmente, pide otro número que NO esté en la tupla e intenta usar index() sobre él, capturando el ValueError que surge e indicando que el número no se encuentra.
**Entrada:** Número a buscar (int, preferiblemente uno que esté en la tupla).
**Salida:** Conteo de ocurrencias, primera posición, todas las posiciones, manejo del ValueError para número no existente.

### Ejercicio 69: Sumar elementos de una tupla usando función
**Enunciado:** Define una función `sumar_tupla(tupla)` que recibe una tupla de números y devuelve la suma de todos sus elementos usando un bucle for (no usar la función built-in sum()). El programa principal define una tupla con 5 números, llama a la función, y muestra el resultado. Luego, define otra función `promedio_tupla(tupla)` que usa la primera función para calcular el promedio (suma / longitud). Muestra el promedio de la tupla. Finalmente, prueba ambas funciones con una tupla vacía y maneja la división por cero en el promedio usando try-except ZeroDivisionError.
**Entrada:** No requiere entrada externa (tuplas predefinidas).
**Salida:** Suma calculada por la función, promedio calculado, manejo de excepción para tupla vacía.

### Ejercicio 70: Tupla de tuplas anidadas (matrices estilo tupla)
**Enunciado:** Define una tupla que contiene 3 tuplas internas, cada una con 3 números (una "matriz" 3x3 usando tuplas). Accede e imprime el elemento en la fila 1, columna 2 (índice [0][1] si usamos indexing normal). Luego recorre toda la estructura usando un bucle for anidado e imprime todos los elementos con su posición (fila, columna). Calcula la suma de todos los elementos usando un bucle. Finalmente, intenta modificar un elemento de la tupla interna (ej. matriz[0][1] = 99), captura el TypeError resultante, y muestra que las tuplas anidadas también son inmutables.
**Entrada:** No requiere entrada externa.
**Salida:** Acceso a elemento específico, recorrido completo, suma total, manejo del TypeError al intentar modificar.

---

### Ejercicio 71: Acceso a diccionario con clave y valor
**Enunciado:** Crea un diccionario que represente las calificaciones de un estudiante en 5 materias (ej. {"Matemáticas": 9.5, "Física": 8.0, "Química": 7.5, "Historia": 6.5, "Literatura": 8.5}). Accede e imprime la calificación de "Física" usando la clave. Luego, muestra todas las materias (claves) usando keys(), todas las calificaciones (valores) usando values(), y los pares clave-valor usando items(). Finalmente, verifica si la clave "Biología" está en el diccionario usando in, y muestra "La materia Biología está registrada" o "La materia Biología no está registrada" según el resultado.
**Entrada:** No requiere entrada externa (diccionario predefinido).
**Salida:** Calificación de Física, lista de claves, lista de valores, lista de items, verificación de presencia de Biología.

### Ejercicio 72: Agregar contactos a diccionario
**Enunciado:** Crea un diccionario vacío llamado `contactos`. Pide al usuario ingresar 3 contactos, cada uno con nombre y número de teléfono. Para cada contacto, agrega una entrada al diccionario donde la clave es el nombre y el valor es el teléfono. Después de agregar los 3, muestra el diccionario completo. Luego, pide al usuario un nombre para buscar, y si existe en el diccionario, muestra el teléfono; si no existe, muestra "Contacto no encontrado". Finalmente, muestra la cantidad de contactos almacenados usando len().
**Entrada:** 3 pares de nombre y teléfono (str), y un nombre para buscar.
**Salida:** Diccionario completo de contactos, resultado de búsqueda, cantidad de contactos.

### Ejercicio 73: Actualizar población de ciudades
**Enunciado:** Crea un diccionario con poblaciones de 4 ciudades (ej. {"CDMX": 9200000, "Guadalajara": 5500000, "Monterrey": 5000000, "Puebla": 1700000}). Pide al usuario el nombre de una ciudad y un nuevo valor de población. Si la ciudad existe en el diccionario, actualiza su población con el nuevo valor. Si no existe, agrega la ciudad nueva con su población (usando la misma sintaxis de asignación). Después de la operación, muestra el diccionario completo. Luego, muestra la ciudad con la mayor población (usa max() con key=lambda x: diccionario[x] o recorre manualmente) y la ciudad con la menor población. Finalmente, elimina la ciudad con menor población usando pop() y muestra el diccionario resultante.
**Entrada:** Ciudad a actualizar/agregar (str), nueva población (int).
**Salida:** Diccionario actualizado, ciudad mayor y menor población, diccionario después de eliminar la menor.

### Ejercicio 74: Obtener claves de diccionario de contactos
**Enunciado:** Dado un diccionario de contactos (nombre → teléfono) con al menos 5 entradas, muestra todas las claves (nombres de contactos) usando keys(). Convierte las claves a una lista y muestra la lista. Luego, ordena las claves alfabéticamente (usando sorted() sobre la lista de claves) y muestra la lista ordenada. Finalmente, pide al usuario ingresar un nombre de contacto y verifica si está entre las claves usando in; si está, muestra "Contacto encontrado en el diccionario"; si no, muestra "Contacto no existe en el diccionario". No muestra el teléfono, solo verifica existencia.
**Entrada:** Diccionario predefinido de al menos 5 contactos, y un nombre para buscar.
**Salida:** Claves del diccionario, lista de claves, lista de claves ordenada, resultado de verificación de existencia.

### Ejercicio 75: Obtener valores de diccionario y estadísticas
**Enunciado:** Dado un diccionario con ventas diarias de una tienda (día → monto vendido, ej. {"Lunes": 1200, "Martes": 1500, "Miércoles": 900, "Jueves": 2000, "Viernes": 1800}), obtén todos los valores (montos) usando values(). Muestra la lista de valores. Calcula y muestra: el total de ventas de la semana (suma de valores), el promedio de ventas diarias (total / número de días), la venta máxima (usa max() sobre los valores), y la venta mínima (usa min() sobre los valores). Finalmente, muestra el día con la máxima venta ( Busca la clave cuyo valor es el máximo usando un bucle).
**Entrada:** No requiere entrada externa (diccionario predefinido).
**Salida:** Lista de valores, total de ventas, promedio, venta máxima, venta mínima, día con máxima venta.

### Ejercicio 76: Iterar sobre items de diccionario
**Enunciado:** Crea un diccionario que represente un inventario de productos (producto → cantidad en stock, ej. {"Laptop": 15, "Mouse": 50, "Teclado": 30, "Monitor": 12, "USB": 100}). Usa un bucle for que itere sobre los items del diccionario (using items()) y para cada producto, muestre: "Producto: X, Stock: Y". Si la cantidad es menor a 20, agrega el mensaje " - Stock bajo, reordenar". Si la cantidad es mayor o igual a 20, agrega " - Stock suficiente". Al final, muestra el total de productos en el inventario (suma de todas las cantidades) usando un acumulador durante el bucle.
**Entrada:** No requiere entrada externa (diccionario predefinido).
**Salida:** Lista de productos con su estado de stock, y total de unidades en inventario.

### Ejercicio 77: Verificar existencia de clave con 'in'
**Enunciado:** Crea un diccionario de precios de productos (producto → precio, ej. {"Arroz": 50, "Frijol": 45, "Azúcar": 60, "Aceite": 120, "Sal": 30}). Pide al usuario ingresar nombres de productos uno por uno (input). Para cada producto ingresado, verifica si la clave existe en el diccionario usando in. Si existe, muestra el precio. Si no existe, muestra "Producto no encontrado, ¿desea agregarlo? (s/n)". Si el usuario responde "s", pide el precio y agrega el producto nuevo al diccionario. El programa termina cuando el usuario ingresa "fin" como nombre de producto. Al final, muestra el diccionario completo y la cantidad de productos.
**Entrada:** Nombres de productos (str), "fin" para terminar. Si se agrega, también precio (float).
**Salida:** Respuestas de precios para productos existentes, agregados nuevos si corresponde, diccionario final con cantidad.

### Ejercicio 78: Obtener valor con get y valor por defecto
**Enunciado:** Crea un diccionario con información de un libro (titulo, autor, año, genero, paginas). Pide al usuario ingresar una clave a buscar (ej. "autor", "editorial", "precio", etc.). Usa get() para obtener el valor: si la clave existe, muestra el valor; si no existe, get() devuelve un valor por defecto que tú estableces (ej. "Desconocido" o 0). Muestra el resultado de get() para la clave solicitada. Luego, muestra la diferencia entre usar get() y usar acceso directo con corchetes: intenta acceder a una clave que no existe con diccionario[clave] y captura el KeyError, mostrando el mensaje de error. Finalmente, usa get() con una clave que sí existe para demostrar que funciona igual que el acceso directo cuando la clave existe.
**Entrada:** Clave a buscar (str).
**Salida:** Resultado de get() con valor por defecto, demostración de KeyError con acceso directo, comparación de ambos métodos.

### Ejercicio 79: Búsqueda de teléfono en diccionario con función
**Enunciado:** Define una función `buscar_telefono(contactos, nombre)` que recibe un diccionario de contactos y un nombre, y devuelve el teléfono si el nombre existe en el diccionario, o "Contacto no encontrado" si no existe (usa get() con valor por defecto). El programa principal crea un diccionario de al menos 5 contactos, pide al usuario un nombre para buscar, llama a la función, y muestra el resultado. Luego, pide otro nombre y busca nuevamente. Después de 2 búsquedas, muestra el diccionario completo con todos los contactos usando un bucle for sobre items().
**Entrada:** 2 nombres para buscar en el diccionario.
**Salida:** Resultado de cada búsqueda (teléfono o mensaje de no encontrado), y diccionario completo mostrado al final.

### Ejercicio 80: Manejar ValueError al convertir entrada a entero
**Enunciado:** El programa pide al usuario ingresar su edad como número entero. Si el usuario ingresa algo que no puede convertirse a int (ej. "veinte", "15.5", "abc"), captura ValueError, muestra "Error: debe ingresar un número entero válido" y pide reingresar (bucle while hasta que sea válido). Una vez obtenida una edad válida, si la edad es menor a 0, muestra "Error: la edad no puede ser negativa" y vuelve a pedir (sin excepción, validación lógica). Si la edad es = 0, muestra "Edad registrada: X años" y el programa termina. Muestra cuántos intentos fallidos se realizaron.
**Entrada:** Edad como cadena (puede ser inválida inicialmente).
**Salida:** Edad registrada válida, número de intentos fallidos, tipos de errores encontrados (ValueError o edad negativa).

### Ejercicio 81: Manejar ZeroDivisionError en calculadora simple
**Enunciado:** Crea un programa que pida al usuario dos números (numerador y denominador). Si el denominador es 0, captura ZeroDivisionError, muestra "Error: no se puede dividir entre cero", y pide al usuario ingresar un denominador diferente (bucle while hasta que sea distinto de cero). Si el usuario ingresa un texto en vez de número en cualquiera de los dos campos, captura ValueError y pide reingreso. Una vez ambos números válidos y denominador ≠ 0, muestra el resultado de la división con 2 decimales. También calcula y muestra la división inversa (denominador / numerador) con el mismo manejo de errores. Muestra el número de intentos fallidos por ValueError y por ZeroDivisionError.
**Entrada:** Numerador (float o str), denominador (float o str).
**Salida:** Resultado de división, división inversa, número de intentos fallidos por cada tipo de error.

### Ejercicio 82: Suma protegida con try-except
**Enunciado:** Define una función `sumar_protegido(a, b)` que intenta sumar dos valores. Si los valores son numéricos (int o float), la suma funciona. Si alguno de los valores es una cadena que no representa un número, captura ValueError al intentar convertir a float, y devuelve "Error: uno de los valores no es numérico". Si los tipos no son compatibles para suma (ej. str + int sin conversión), captura TypeError. El programa principal prueba la función con varios casos: (5, 3), (5, "3"), ("5", "3"), (5, "abc"), (5, "hola"), y muestra el resultado de cada caso. Usa un bucle para probar todos los casos y mostrar resultados en formato tabla.
**Entrada:** No requiere entrada externa (pruebas automáticas).
**Salida:** Tabla con los casos de prueba y sus resultados (suma exitosa o mensaje de error).

### Ejercicio 83: División con manejo de ValueError y ZeroDivisionError
**Enunciado:** Crea una función `dividir_seguro(a, b)` que maneja dos tipos de excepciones: si b es 0, captura ZeroDivisionError y devuelve "Error: división por cero". Si a o b no son numéricos (ej. strings que no se pueden convertir), captura ValueError al intentar convertir a float, y devuelve "Error: valor no numérico". Si no hay excepciones, devuelve el resultado de a / b. El programa principal pide al usuario dos valores (pueden ser números o texto), pasa los valores crudos (como strings) a la función, y muestra el resultado. Luego, pide al usuario si desea realizar otra división (centinela "fin" para terminar). Muestra el número total de divisiones exitosas y fallidas.
**Entrada:** Dos valores (str, pueden ser numéricos o texto), "fin" para terminar.
**Salida:** Resultado de cada división, y resumen final de éxitos y fallas.

### Ejercicio 84: Manejar TypeError al concatenar tipos incompatibles
**Enunciado:** Pide al usuario ingresar dos valores (pueden ser números o texto). El programa intenta concatenar los dos valores usando el operador + (ej. valor1 + valor2). Si ambos son strings, la concatenación funciona. Si uno es string y el otro es int/float, produce TypeError. Captura TypeError, muestra "Error: no se pueden concatenar tipos diferentes (string y número)", y demuestra cómo corregirlo convirtiendo ambos a string (str(valor1) + str(valor2)). Luego muestra el resultado concatenado correctamente. Si el usuario ingresa valores que no son ni string ni número (ej. lista), captura el error general Exception. Finalmente, verifica los tipos de los valores ingresados usando type() e imprime cada tipo.
**Entrada:** Dos valores (str, el usuario puede ingresar texto o números como texto).
**Salida:** Manejo del TypeError, concatenación corregida, tipos de los valores ingresados.

### Ejercicio 85: Manejar IndexError en acceso a lista por índice
**Enunciado:** Define una lista con 5 colores (ej. ["rojo", "verde", "azul", "amarillo", "morado"]). Pide al usuario ingresar un índice para acceder a la lista. Si el índice está dentro del rango válido (0 a 4), muestra el color correspondiente. Si el índice está fuera de rango (≥5 o < -5), captura IndexError, muestra "Error: índice fuera de rango. La lista tiene 5 elementos (índices 0-4 o -5 a -1)", y muestra los índices válidos usando un bucle. Luego, pide al usuario otro índice (bucle while) hasta que ingrese -1 para salir. Si ingresa un valor no numérico, captura ValueError y pide reingreso. Muestra el color accedido en cada intento válido.
**Entrada:** Índice entero para acceder a la lista, -1 para salir.
**Salida:** Color accedido si índice válido, manejo de IndexError para índice inválido, lista de índices válidos, resumen de accesos.

### Ejercicio 86: Excepción general Exception como captura final
**Enunciado:** Crea un programa que pida al usuario ingresar una expresión matemática como cadena (ej. "2+3*4"). Usa eval() para evaluar la expresión dentro de un try-except. Primero intenta capturar específicamente SyntaxError (para expresiones mal formadas), luego ZeroDivisionError, luego NameError (para variables no definidas), y finalmente Exception como captura general para cualquier otro error inesperado. Muestra el tipo de error y un mensaje amigable para cada caso. Pide expresiones indefinidamente hasta que el usuario ingrese "salir". Al final, muestra un resumen: cuántas expresiones se evaluaron con éxito, cuántas fallaron por SyntaxError, por ZeroDivisionError, por NameError, y por otros errores.
**Entrada:** Expresiones matemáticas como cadena (str), "salir" para terminar.
**Salida:** Resultado de cada evaluación o mensaje de error con tipo, y resumen final estadístico.

### Ejercicio 87: Bloque else en división exitosa (demostración)
**Enunciado:** Define una función `dividir_con_else(a, b)` que intenta a / b. Estructura el manejo con: try (la división), except ZeroDivisionError (maneja división por cero), except TypeError (maneja tipos incompatibles), else (se ejecuta solo si NO hay excepción: imprime "La división fue exitosa y el resultado es X"), finally (siempre se ejecuta: imprime "Operación finalizada"). El programa principal prueba la función con 4 casos: (10, 2) → debe mostrar else ejecutándose; (5, 0) → debe mostrar except ZeroDivisionError; (10, "2") → debe mostrar except TypeError; (10, 2) nuevamente para confirmar. Muestra el flujo completo para cada caso.
**Entrada:** No requiere entrada externa (pruebas automáticas).
**Salida:** Flujo de ejecución para cada caso, demostrando cuándo se ejecuta else y finally.

### Ejercicio 88: Bloque finally en operación de archivo simulada
**Enunciado:** Simula una operación de "archivo": imprime "Abriendo archivo...". Luego, en el try, pide al usuario ingresar un número. Si el número es mayor a 10, lanza una excepción Exception("Número demasiado grande") manualmente. Si es menor o igual a 10, la operación es exitosa. El bloque except captura la Exception y muestra el mensaje de error. El bloque finally siempre imprime "Cerrando archivo..." (simulando cierre de recurso). El programa permite al usuario probar varios números (bucle while) hasta que ingrese -1 para salir. Muestra el flujo completo de apertura, operación, y cierre en cada iteración.
**Entrada:** Número entero para probar, -1 para salir.
**Salida:** Flujo de apertura, operación (éxito o error capturado), y cierre en finally en cada iteración.

### Ejercicio 89: Validación de entrada con while y excepciones anidadas
**Enunciado:** El programa pide al usuario un número entero positivo para usarlo como límite en un contador. Valida la entrada con un while: si el usuario ingresa un valor no numérico, captura ValueError, muestra "Error: debe ingresar un número entero", y pide reingreso. Si ingresa un número pero es negativo o cero, muestra "Error: debe ser positivo", y pide reingreso sin capturar excepción (validación lógica). Si ingresa un número flotante válido pero con decimal, redondea y acepta. Al obtener un número válido, genera e imprime la cuenta del 1 al N. Muestra cuántos reintentos de entrada fueron necesarios.
**Entrada:** Número para ser validado (puede ser inválido inicialmente).
**Salida:** Cuenta del 1 al N, número de reintentos de entrada, tipos de errores encontrados.

### Ejercicio 90: Excepción personalizada: edad no válida
**Enunciado:** Define una excepción personalizada llamada `EdadNoValidaException` que hereda de Exception. El programa pide al usuario ingresar su edad. Si la edad es menor a 0 o mayor a 120, lanza la excepción personalizada con un mensaje "Edad no válida: X (debe estar entre 0 y 120)". Captura la excepción personalizada y muestra el mensaje. Si la edad es válida (0-120), muestra "Edad registrada correctamente: X años". El programa permite al usuario probar varias edades (bucle while) hasta que ingrese -1 para salir. Muestra el número de veces que se lanzó la excepción personalizada.
**Entrada:** Edades para probar (int), -1 para salir.
**Salida:** Manejo de la excepción personalizada para edades inválidas, registro de edades válidas, conteo de excepciones lanzadas.

---

### Ejercicio 91: Convertir texto a mayúsculas y minúsculas
**Enunciado:** Pide al usuario una frase. Muestra la frase original, su versión en mayúsculas usando upper(), y su versión en minúsculas usando lower(). Luego, cuenta y muestra cuántas letras hay en mayúsculas y cuántas en minúsculas en la frase original (recorriendo carácter por carácter y usando isupper() e islower()). Si la frase contiene números o símbolos, no los cuenta como mayúsculas ni minúsculas. Finalmente, usa capitalize() para mostrar la frase con solo la primera letra en mayúscula y el resto en minúsculas, e compara con la frase original.
**Entrada:** Una frase (str).
**Salida:** Frase original, versión upper, versión lower, conteos de mayúsculas y minúsculas, versión capitalize, comparación.

### Ejercicio 92: Longitud de cadena y manipulación básica
**Enunciado:** Pide al usuario ingresar su nombre completo. Calcula y muestra la longitud del nombre usando len(). Luego, muestra el nombre invertido usando slicing con paso -1. Extrae e imprime el primer nombre (primera palabra antes del espacio) usando split() y accediendo al primer elemento. Extrae e imprime el apellido (última palabra) usando split() y accediendo al último elemento con índice -1. Si el nombre tiene solo una palabra (sin apellido), muestra un mensaje "Solo hay un nombre, sin apellido". Finalmente, muestra el nombre con la primera letra de cada palabra en mayúsculas usando title().
**Entrada:** Nombre completo (str).
**Salida:** Longitud del nombre, nombre invertido, primer nombre, apellido (o mensaje si no hay), nombre con title().

### Ejercicio 93: Reemplazar palabras en una frase
**Enunciado:** Pide al usuario una frase. Luego pide una palabra que existe en la frase y la nueva palabra que la reemplazará. Usa replace() para reemplazar todas las ocurrencias de la palabra original por la nueva. Muestra la frase original, la frase modificada, y el número de reemplazos realizados (usa count() de la palabra original en la frase original para obtener el número). Si la palabra original no está en la frase, muestra "La palabra no se encuentra en la frase" y no realiza cambios. El reemplazo debe ser exacto (reemplaza la palabra completa, no parcial). Si la palabra original aparece como parte de otra palabra (ej. "cat" en "category"), el replace la reemplaza igual (comportamiento esperado de replace).
**Entrada:** Frase (str), palabra a reemplazar (str), nueva palabra (str).
**Salida:** Frase original, frase modificada, número de reemplazos, o mensaje si palabra no encontrada.

### Ejercicio 94: Dividir cadena en palabras y contar
**Enunciado:** Pide al usuario un párrafo de al menos 2 líneas o una oración larga. Usa split() para dividir el párrafo en palabras (separador por espacios en blanco). Muestra la lista de palabras resultante y el número total de palabras. Luego, usando un bucle for, cuenta cuántas palabras tienen más de 5 letras, cuántas tienen entre 3 y 5 letras inclusive, y cuántas tienen menos de 3 letras. Muestra estos tres conteos. Además, identifica y muestra la palabra más larga de la lista y la palabra más corta. Si el párrafo está vacío o solo contiene espacios, muestra "El párrafo no contiene palabras".
**Entrada:** Un párrafo u oración (str).
**Salida:** Lista de palabras, número total de palabras, conteos por longitud, palabra más larga, palabra más corta.

### Ejercicio 95: Buscar posición de subcadena con find
**Enunciado:** Pide al usuario una cadena principal (ej. un párrafo) y una subcadena a buscar (puede ser una palabra o frase). Usa find() para encontrar la primera posición donde aparece la subcadena. Si se encuentra (find no devuelve -1), muestra la posición inicial, extrae la subcadena usando slicing desde esa posición con la longitud de la subcadena, e imprime la extracción para confirmar. Luego, usando find con un argumento de inicio (desde la posición siguiente a la primera aparición), busca la segunda ocurrencia y muestra su posición si existe. Si no hay segunda ocurrencia, muestra "Solo existe una ocurrencia". Si la subcadena no está en absoluto, muestra "Subcadena no encontrada".
**Entrada:** Cadena principal (str), subcadena a buscar (str).
**Salida:** Posición de primera ocurrencia, extracción confirmada, posición de segunda ocurrencia o mensaje, o mensaje de no encontrado.

### Ejercicio 96: Extraer partes de cadena con slicing
**Enunciado:** Pide al usuario una cadena de texto de al menos 15 caracteres. Realiza los siguientes slicing y muestra cada resultado con una descripción: a) Los primeros 5 caracteres (cadena[:5]); b) Los últimos 5 caracteres (cadena[-5:]); c) Desde el índice 3 hasta el índice 8 (cadena[3:8]); d) Cada tercer carácter de toda la cadena (cadena[::3]); e) La cadena invertida (cadena[::-1]); f) Desde el segundo carácter hasta el penúltimo (cadena[1:-1]); g) Los caracteres en posiciones pares (índices 0, 2, 4,... usando cadena[::2]). Si la cadena es muy corta para alguno de estos slicing, muestra solo lo que es posible. Explica brevemente cada slicing en el output.
**Entrada:** Una cadena de texto (mínimo 15 caracteres recomendado).
**Salida:** Resultados de los 7 slicings con explicaciones.

### Ejercicio 97: Formatear texto con f-strings
**Enunciado:** Crea un programa que muestre una "receta de cocina" formateada usando f-strings. Pide al usuario: nombre de la receta, cantidad de porciones (int), tiempo de preparación en minutos (int), y una lista de 3 ingredientes (strings). Muestra la siguiente ficha usando f-strings con alineación: nombre de receta alineado a la izquierda en 25 caracteres, porciones alineados a la derecha en 5 caracteres, tiempo alineado a la derecha en 5 caracteres. Luego, muestra los ingredientes numerados (1. ..., 2. ..., 3. ...). Finalmente, calcula y muestra el tiempo por porción (tiempo / porciones) con 2 decimales, y si el tiempo total es mayor a 60 minutos, muestra "Esta receta requiere paciencia" usando una condicional.
**Entrada:** Nombre de receta (str), porciones (int), tiempo (int), 3 ingredientes (str).
**Salida:** Ficha de receta formateada con f-strings, ingredientes numerados, tiempo por porción, y posible mensaje de paciencia.

### Ejercicio 98: Función que cuenta palabras en una cadena
**Enunciado:** Define una función `contar_palabras(cadena)` que recibe una cadena, usa split() para dividirla en palabras, y devuelve el número de palabras (len de la lista). El programa principal pide al usuario una frase, llama a la función, y muestra el resultado con un mensaje "La frase tiene X palabras". Luego, pide al usuario otra frase más larga (un párrafo de al menos 20 palabras) y cuenta las palabras también. Finalmente, compara las dos frases e indica cuál tiene más palabras, o si son iguales. Si el usuario ingresa una cadena vacía, la función debe devolver 0.
**Entrada:** Dos frases (str), la segunda preferiblemente más larga.
**Salida:** Número de palabras de cada frase, comparación de cual tiene más palabras.

### Ejercicio 99: Combinación de replace, upper, y split
**Enunciado:** Pide al usuario un texto que contenga varias palabras y al menos una letra específica que se repetirá (ej. el usuario puede elegir la letra 'a' o 'e'). Realiza las siguientes operaciones en secuencia y muestra cada paso: a) Convierte todo el texto a mayúsculas usando upper(); b) Pide al usuario una letra para reemplazar (ej. 'A') y una letra de reemplazo (ej. '@'), y usa replace() para reemplazar todas las ocurrencias; c) Usa split() para dividir el texto resultante en una lista de palabras; d) Muestra la lista final de palabras y el número de palabras. Luego, con el texto original (antes de las transformaciones), cuenta cuántas palabras contenían la letra original usando un bucle y in, e imprime este conteo. Finalmente, muestra el texto original y el texto transformado lado a lado para comparación.
**Entrada:** Texto (str), letra a reemplazar (str de 1 carácter), letra de reemplazo (str de 1 carácter).
**Salida:** Lista final de palabras, número de palabras, conteo de palabras originales que contenían la letra, y comparación de textos.

### Ejercicio 100: Combinación de strip, len, y slicing
**Enunciado:** Pide al usuario un texto que pueda tener espacios al inicio y al final (intencionalmente con espacios extra, ej. "   Hola mundo   "). Usa strip() para eliminar espacios al inicio y final. Muestra la cadena original, la cadena sin espacios, y la diferencia de longitud (len original - len stripada). Luego, con la cadena stripada, extrae y muestra: a) Los primeros 3 caracteres (o menos si la cadena es corta); b) Los últimos 3 caracteres; c) La cadena desde el índice 1 hasta el índice len-2 (excluyendo el primer y último carácter). Si la cadena stripada tiene menos de 3 caracteres, muestra un mensaje "La cadena es muy corta para algunos slicing" y solo hace los que sean posibles. Finalmente, verifica si la cadena stripada está vacía después de strip() y muestra "La cadena está vacía" o "La cadena no está vacía".
**Entrada:** Texto con espacios extra al inicio/final (str).
**Salida:** Cadena original, cadena stripada, diferencia de longitud, resultados de los slicing, verificación de vacía.

---

### Ejercicio 101: Dado un tuple de 5 elementos, acceder al índice 2
**Enunciado:** Define una tupla con 5 elementos de tipos diferentes (ej. (10, "hola", 3.14, True, [1,2,3])). Accede e imprime el elemento en el índice 2 (el tercer elemento). Luego, usando un bucle for con range(len(tupla)), imprime cada elemento con su índice correspondiente en el formato "Índice i: valor". Finalmente, verifica si el elemento en el índice 2 es de tipo float e imprime "El elemento índice 2 es float" o "El elemento índice 2 no es float" según corresponda.
**Entrada:** No requiere entrada externa (tupla predefinida).
**Salida:** Elemento índice 2, recorrido completo con índices, verificación del tipo del elemento índice 2.

### Ejercicio 102: Calcular la longitud de una tupla
**Enunciado:** Crea una tupla con nombres de animales (al menos 6 elementos, algunos pueden repetirse). Calcula la longitud de la tupla usando len() e imprime el resultado. Luego, convierte la tupla a una lista usando list(), agrega un nuevo animal a la lista usando append(), convierte la lista de vuelta a tupla, y calcula la nueva longitud. Muestra ambas longitudes (antes y después de agregar). Finalmente, verifica que la nueva tupla tiene exactamente un elemento más que la original usando una comparación e imprime "La nueva tupla tiene un elemento más" o "Las longitudes son iguales" según corresponda.
**Entrada:** No requiere entrada externa.
**Salida:** Longitud original, longitud después de agregar, y verificación de diferencia de longitud.

### Ejercicio 103: Acceder a elementos de tupla con índices negativos
**Enunciado:** Define una tupla de 6 elementos (pueden ser números enteros del 1 al 6). Accede e imprime el último elemento usando índice -1, el penúltimo usando -2, y el antepenúltimo usando -3. Luego, usando un bucle for que recorra índices desde -1 hasta -6 (inclusive) en orden decreciente, imprime cada elemento con su índice negativo en el formato "Índice -i: valor". Finalmente, verifica que el elemento en índice -1 es igual al elemento en índice len(tupla)-1 e imprime "Los índices -1 y len-1 son equivalentes" o "No son equivalentes" según el resultado.
**Entrada:** No requiere entrada externa.
**Salida:** Accesos individuales con índices negativos, recorrido completo con índices negativos, verificación de equivalencia.

### Ejercicio 104: Intentar modificar tupla (inmutabilidad)
**Enunciado:** Crea una tupla con 4 elementos (ej. ("rojo", "verde", "azul", "amarillo")). Intenta cambiar el segundo elemento asignándole un nuevo valor (tupla[1] = "naranja"). Esto debe generar un TypeError. Captura la excepción con try-except, muestra el tipo de error (TypeError) y un mensaje "Las tuplas son inmutables: no se pueden modificar sus elementos individualmente". Luego, imprime la tupla original para confirmar que no hubo cambios. Finalmente, crea una nueva tupla reemplazando el segundo elemento usando concatenación de tuplas (tupla[:1] + ("naranja",) + tupla[2:]) y muestra la nueva tupla resultante.
**Entrada:** No requiere entrada externa.
**Salida:** Manejo del TypeError, tupla original intacta, nueva tupla con el elemento modificado.

### Ejercicio 105: Desempaquetar tupla en variables individuales
**Enunciado:** Define una tupla con exactamente 4 elementos (ej. ("Juan", 25, "Ingeniero", "Ciudad de México")). Desempaqueta la tupla en 4 variables con nombres descriptivos (nombre, edad, profesion, ciudad). Imprime cada variable individualmente con su nombre. Luego, imprime una frase combinada usando f-string: "Juan, de 25 años, es Ingeniero y vive en Ciudad de México". Finalmente, intenta desempaquetar la tupla en 3 variables (en vez de 4) y captura el ValueError que ocurre, mostrando el mensaje de error y explicando que el número de variables debe coincidir con la cantidad de elementos de la tupla.
**Entrada:** No requiere entrada externa.
**Salida:** Variables desempaquetadas, frase combinada, y manejo del ValueError al desempaquetar con número incorrecto de variables.

### Ejercicio 106: Concatenar dos tuplas
**Enunciado:** Crea dos tuplas: tupla1 con 3 elementos (números enteros) y tupla2 con 2 elementos (strings). Concatena las dos tuplas usando el operador + y guarda el resultado en una nueva variable tupla3. Muestra las tres tuplas (tupla1, tupla2, tupla3) y sus longitudes respectivas. Luego, multiplica tupla1 por 3 usando el operador * y muestra el resultado (tupla1 repetida 3 veces). Finalmente, verifica si todos los elementos de tupla1 están en tupla3 usando el operador in en un bucle, e imprime "Todos los elementos de tupla1 están en tupla3" si es verdad, o "Algunos elementos no están" si no lo son.
**Entrada:** No requiere entrada externa.
**Salida:** Las tres tuplas con longitudes, tupla1 repetida 3 veces, y verificación de contención de elementos.

### Ejercicio 107: Convertir lista a tupla y tupla a lista
**Enunciado:** Define una lista con 5 elementos (ej. ["apple", "banana", "cherry", "date", "elderberry"]). Convierte la lista a tupla usando tuple() e imprime la tupla resultante y su tipo (usando type()). Luego, convierte la tupla de vuelta a lista usando list() e imprime la lista resultante. Verifica que ambas conversiones mantengan la misma cantidad de elementos usando len() en ambos. Finalmente, agrega un nuevo elemento a la lista convertida (usando append), convierte de nuevo a tupla, e imprime la tupla final mostrando que ahora tiene un elemento más que la tupla original.
**Entrada:** No requiere entrada externa.
**Salida:** Lista original, tupla convertida, lista convertida de vuelta, y tupla final con elemento adicional.

### Ejercicio 108: Usar count e index en tupla
**Enunciado:** Crea una tupla con números donde algunos se repiten (ej. (5, 3, 8, 5, 9, 3, 5, 2, 7, 3)). Pide al usuario ingresar un número. Usa count() para mostrar cuántas veces aparece el número en la tupla. Usa index() para mostrar la posición de la primera ocurrencia del número. Luego, usando un bucle for con enumerate, encuentra y muestra todas las posiciones donde aparece el número. Finalmente, pide otro número que NO esté en la tupla e intenta usar index() sobre él; captura el ValueError que surge e imprime "El número X no se encuentra en la tupla" (usando el manejo de excepción).
**Entrada:** Número a buscar (int), y otro número que no esté en la tupla.
**Salida:** Conteo de ocurrencias, primera posición, todas las posiciones, y manejo del ValueError para número no existente.

### Ejercicio 109: Sumar elementos de tupla con función definida
**Enunciado:** Define una función `sumar_tupla(tupla)` que recibe una tupla de números y devuelve la suma de todos sus elementos usando un bucle for (no usar la función built-in sum()). El programa principal define una tupla con 5 números, llama a la función, y muestra el resultado. Luego, define otra función `promedio_tupla(tupla)` que calcula el promedio usando la primera función (suma / número de elementos). Muestra el promedio de la tupla. Finalmente, prueba ambas funciones con una tupla vacía y maneja la división por cero en el promedio usando try-except ZeroDivisionError, mostrando "No se puede calcular el promedio de una tupla vacía".
**Entrada:** No requiere entrada externa.
**Salida:** Suma calculada, promedio calculado, y manejo de excepción para tupla vacía.

### Ejercicio 110: Tupla de tuplas (matriz inmutable)
**Enunciado:** Define una tupla que contiene 3 tuplas internas, cada una con 3 números (una "matriz" 3x3 inmutable). Accede e imprime el elemento en la fila 2, columna 3 (índice [1][2]). Luego, recorre toda la estructura usando un bucle for anidado e imprime todos los elementos con su posición (fila, columna) en el formato "Fila i, Columna j: valor". Calcula la suma de todos los elementos usando un bucle acumulador. Finalmente, intenta modificar un elemento de la tupla interna (ej. matriz[0][1] = 99), captura el TypeError resultante, y muestra "Las tuplas anidadas también son inmutables y no se pueden modificar".
**Entrada:** No requiere entrada externa.
**Salida:** Acceso a elemento específico, recorrido completo, suma total, y manejo del TypeError al intentar modificar elemento anidado.

---

### Ejercicio 111: Crear y acceder a diccionario de ventas
**Enunciado:** Crea un diccionario que represente las ventas de una tienda (producto → cantidad vendida en el mes, ej. {"Laptop": 12, "Mouse": 45, "Teclado": 30, "Monitor": 8, "USB": 100}). Accede e imprime la cantidad vendida de "Mouse" usando la clave. Luego, muestra todas las claves (productos) usando keys() e imprime la lista. Muestra todos los valores (cantidades) usando values() e imprime la lista. Finalmente, muestra los pares clave-valor usando items() e imprime cada par en el formato "Producto: X, Vendido: Y".
**Entrada:** No requiere entrada externa (diccionario predefinido).
**Salida:** Acceso específico a Mouse, lista de claves, lista de valores, y recorrido de items con formato.

### Ejercicio 112: Agregar y modificar entradas en diccionario
**Enunciado:** Crea un diccionario vacío llamado `estudiantes`. Pide al usuario ingresar 3 estudiantes, cada uno con nombre y calificación (float). Agrega cada estudiante al diccionario donde la clave es el nombre y el valor es la calificación. Después de agregar los 3, muestra el diccionario completo. Luego, pide al usuario el nombre de un estudiante para modificar su calificación; si existe, actualiza la calificación; si no existe, muestra "Estudiante no encontrado". Finalmente, muestra el diccionario actualizado y la calificación promedio de todos los estudiantes (usando sum() y len()).
**Entrada:** 3 pares de nombre y calificación, y un nombre para modificar con nueva calificación.
**Salida:** Diccionario de estudiantes, resultado de modificación, y promedio de calificaciones.

### Ejercicio 113: Obtener lista de claves y ordenarlas
**Enunciado:** Crea un diccionario con palabras en español y su traducción al inglés (al menos 5 pares, ej. {"casa": "house", "perro": "dog", "gato": "cat", "árbol": "tree", "libro": "book"}). Obtén la lista de todas las claves (palabras en español) usando keys() y convierte a lista. Muestra la lista de claves original. Luego, ordénala alfabéticamente usando sorted() y muestra la lista ordenada. Finalmente, pide al usuario ingresar una palabra en español y verifica si está en las claves del diccionario usando in; si está, muestra "La palabra existe en el diccionario"; si no, muestra "La palabra no existe en el diccionario". No muestra la traducción, solo verifica existencia.
**Entrada:** Palabra en español para verificar existencia.
**Salida:** Lista de claves original, lista de claves ordenada, y resultado de verificación de existencia.

### Ejercicio 114: Obtener valores y calcular estadísticas
**Enunciado:** Dado un diccionario con temperaturas diarias de una semana (día → temperatura en °C, ej. {"Lunes": 22, "Martes": 24, "Miércoles": 19, "Jueves": 21, "Viernes": 25, "Sábado": 23, "Domingo": 20}), obtén todos los valores (temperaturas) usando values(). Calcula y muestra: la temperatura promedio de la semana (suma de valores / número de días), la temperatura máxima (usa max() sobre los valores), la temperatura mínima (usa min() sobre los valores), y el rango de temperaturas (máxima - mínima). Finalmente, muestra el día con la temperatura más alta (busca la clave cuyo valor es el máximo usando un bucle sobre items()).
**Entrada:** No requiere entrada externa (diccionario predefinido).
**Salida:** Temperatura promedio, máxima, mínima, rango, y día con temperatura más alta.

### Ejercicio 115: Iterar sobre items de diccionario
**Enunciado:** Crea un diccionario que represente un inventario de productos (producto → precio en pesos, ej. {"Arroz": 50, "Frijol": 45, "Azúcar": 60, "Aceite": 120, "Sal": 30}). Usa un bucle for que itere sobre los items del diccionario (usando items()) y para cada producto, muestra: "Producto: X, Precio: $Y". Si el precio es mayor a $100, agrega el mensaje " - Producto costoso". Si el precio es menor o igual a $100, agrega " - Producto económico". Al final, muestra el costo total de comprar una unidad de cada producto (suma de todos los precios) usando un acumulador durante el bucle.
**Entrada:** No requiere entrada externa (diccionario predefinido).
**Salida:** Lista de productos con su categoría de precio, y costo total de una unidad de cada producto.

### Ejercicio 116: Verificar existencia de clave con 'in'
**Enunciado:** Crea un diccionario de accesos (usuario → contraseña, ej. {"admin": "1234", "usuario1": "pass1", "usuario2": "pass2", "prueba": "test"}). Pide al usuario ingresar nombres de usuario uno por uno. Para cada uno, verifica si la clave existe en el diccionario usando in. Si existe, muestra "Usuario encontrado en el sistema". Si no existe, muestra "Usuario no registrado" y pregunta "¿Desea agregarlo? (s/n)". Si el usuario responde "s", pide una contraseña y agrega el nuevo usuario al diccionario. El programa termina cuando el usuario ingresa "salir" como nombre. Al final, muestra el diccionario completo y la cantidad de usuarios registrados usando len().
**Entrada:** Nombres de usuario (str), "salir" para terminar. Si se agrega, también contraseña (str).
**Salida:** Respuestas de existencia para cada usuario, agregados nuevos si corresponde, diccionario final con cantidad.

### Ejercicio 117: Usar get con valor por defecto
**Enunciado:** Crea un diccionario con información de una película (titulo, director, año, género, duración_minutos). Pide al usuario ingresar una clave a buscar (ej. "director", "guión", "presupuesto", etc.). Usa get() para obtener el valor: si la clave existe, muestra el valor; si no existe, get() devuelve un valor por defecto que tú estableces (ej. "No disponible" o 0). Muestra el resultado de get() para la clave solicitada. Luego, muestra la diferencia entre usar get() y usar acceso directo con corchetes: intenta acceder a una clave que no existe con diccionario[clave] y captura el KeyError, mostrando el mensaje de error "KeyError: la clave X no existe en el diccionario". Finalmente, usa get() con una clave que sí existe para demostrar que funciona igual que el acceso directo cuando la clave existe.
**Entrada:** Clave a buscar (str).
**Salida:** Resultado de get() con valor por defecto, demostración de KeyError con acceso directo, comparación de ambos métodos.

### Ejercicio 118: Función que busca y devuelve valor de diccionario
**Enunciado:** Define una función `buscar_en_diccionario(diccionario, clave)` que recibe un diccionario y una clave, y devuelve el valor asociado si la clave existe, o "Clave no encontrada" si no existe (usa get() con valor por defecto). El programa principal crea un diccionario de al menos 5 elementos (ej. precios de productos), pide al usuario una clave para buscar, llama a la función, y muestra el resultado. Luego, pide otra clave y busca nuevamente. Después de 2 búsquedas, muestra el diccionario completo usando un bucle for sobre items() en el formato "Clave: X, Valor: Y". Finalmente, muestra cuántas búsquedas tuvieron éxito y cuántas fallaron.
**Entrada:** 2 claves para buscar en el diccionario.
**Salida:** Resultado de cada búsqueda, diccionario completo mostrado al final, y resumen de búsquedas exitosas vs fallidas.

### Ejercicio 119: Manejar ValueError al convertir entrada a número
**Enunciado:** El programa pide al usuario ingresar la cantidad de productos a comprar (debe ser un número entero positivo). Si el usuario ingresa algo que no puede convertirse a int (ej. "tres", "2.5", "abc"), captura ValueError, muestra "Error: debe ingresar un número entero válido" y pide reingresar (bucle while hasta que sea válido). Una vez obtenido un número válido, si el número es menor o igual a 0, muestra "Error: la cantidad debe ser positiva" y vuelve a pedir (sin excepción, validación lógica). Si el número es positivo, muestra "Cantidad registrada: X productos" y el programa termina. Muestra cuántos intentos fallidos se realizaron por ValueError y cuántos por cantidad no positiva.
**Entrada:** Cantidad de productos como cadena (puede ser inválida inicialmente).
**Salida:** Cantidad registrada válida, número de intentos fallidos por ValueError, número de intentos por cantidad no positiva.

### Ejercicio 120: Manejar ZeroDivisionError al calcular promedio
**Enunciado:** Crea un programa que pida al usuario ingresar una serie de números (puede ingresar varios, separados por comas en un solo input, o uno por uno). El programa calcula el promedio de los números ingresados. Si el usuario no ingresa ningún número (lista vacía o string vacío), captura ZeroDivisionError al intentar dividir por cero (len=0), muestra "Error: no se puede calcular el promedio de una lista vacía", y pide reingresar los números. Si el usuario ingresa valores que no son numéricos, captura ValueError al intentar convertir a float, muestra "Error: valor no numérico encontrado", y pide reingresar solo los valores no numéricos (o todos, a elección). Una vez válidos, muestra el promedio con 2 decimales. Muestra el número de intentos por ZeroDivisionError y por ValueError.
**Entrada:** Números separados por comas (str), o input individuales.
**Salida:** Promedio calculado, número de intentos por cada tipo de error, y manejo de lista vacía.

### Ejercicio 121: Manejar TypeError al combinar tipos en operación
**Enunciado:** Pide al usuario ingresar dos valores (pueden ser números o texto). El programa intenta sumar los dos valores usando el operador +. Si ambos son numéricos (int o float), la suma funciona. Si uno es string y el otro es int/float, produce TypeError. Captura TypeError, muestra "Error: no se pueden sumar tipos diferentes (string y número)", y demuestra cómo corregirlo: si ambos pueden ser convertidos a float, hacer la suma numérica; si no, convertir ambos a string y concatenar. Muestra el resultado correcto. Si el usuario ingresa valores que no son ni string ni número (ej. una lista como string "[1,2]"), captura Exception general y muestra "Error inesperado". Finalmente, muestra los tipos originales de los valores usando type().
**Entrada:** Dos valores (str, el usuario puede ingresar texto o números como texto).
**Salida:** Manejo del TypeError, resultado corregido, tipos originales de los valores, y posible manejo de Exception general.

### Ejercicio 122: Manejar IndexError al acceder a lista
**Enunciado:** Define una lista con 4 elementos (ej. ["lunes", "martes", "miércoles", "jueves"]). Pide al usuario ingresar un índice para acceder a la lista. Si el índice está dentro del rango válido (0 a 3 o -4 a -1), muestra el elemento correspondiente. Si el índice está fuera de rango (≥4 o < -4), captura IndexError, muestra "Error: índice fuera de rango. La lista tiene 4 elementos (índices 0-3 o -4 a -1)", y muestra los índices válidos usando un bucle for que recorra range(len(lista)) e imprime cada índice con su elemento. Luego, pide al usuario otro índice (bucle while) hasta que ingrese -99 para salir. Si ingresa un valor no numérico, captura ValueError y pide reingreso. Muestra el elemento accedido en cada intento válido.
**Entrada:** Índice entero para acceder a la lista, -99 para salir.
**Salida:** Elemento accedido si índice válido, manejo de IndexError para índice inválido, lista de índices válidos, resumen de accesos.

### Ejercicio 123: Excepción Exception como captura general
**Enunciado:** Crea un programa que pida al usuario ingresar una expresión matemática como cadena (ej. "2+3*4"). Usa eval() para evaluar la expresión dentro de un try-except. Estructura los manejadores de excepción en orden: primero SyntaxError (para expresiones mal formadas), luego ZeroDivisionError, luego NameError (para variables no definidas como "x+1"), luego TypeError, y finalmente Exception como captura general para cualquier otro error inesperado. Muestra el tipo de error y un mensaje amigable para cada caso. Pide expresiones indefinidamente hasta que el usuario ingrese "salir". Al final, muestra un resumen estadístico: cuántas expresiones se evaluaron con éxito, cuántas fallaron por cada tipo de error específico, y cuántas por errores generales.
**Entrada:** Expresiones matemáticas como cadena (str), "salir" para terminar.
**Salida:** Resultado de cada evaluación o mensaje de error con tipo, y resumen final estadístico detallado.

### Ejercicio 124: Bloque else ejecutándose cuando no hay excepción
**Enunciado:** Define una función `procesar_division(a, b)` que intenta a / b. Estructura el manejo: try (la división), except ZeroDivisionError (maneja división por cero), except ValueError (maneja si los valores no son numéricos), else (se ejecuta solo si NO hay excepción: calcula y muestra el doble del resultado, es decir, resultado * 2, e imprime "Procesamiento exitoso: el doble del resultado es X"), finally (siempre se ejecuta: imprime "Operación de división finalizada"). El programa principal prueba la función con 3 casos: (10, 2) → debe mostrar else ejecutándose y el doble; (5, 0) → debe mostrar except ZeroDivisionError; (10, "2") → debe mostrar except ValueError. Muestra el flujo completo para cada caso.
**Entrada:** No requiere entrada externa (pruebas automáticas).
**Salida:** Flujo de ejecución para cada caso, demostrando cuándo se ejecuta else y finally, y el cálculo del doble en el caso exitoso.

### Ejercicio 125: Bloque finally cerrando recurso simulado
**Enunciado:** Simula una "conexión a base de datos": imprime "Conectando a la base de datos...". Luego, en el try, pide al usuario ingresar un comando (str). Si el comando es "SELECT * FROM usuarios", la operación es exitosa e imprime "Operación ejecutada correctamente". Si el comando es "DROP TABLE", lanza una excepción Exception("Operación peligrosa no permitida") manualmente. Si el comando es cualquier otra cosa, lanza Exception("Comando no reconocido"). El bloque except captura la Exception y muestra el mensaje de error correspondiente. El bloque finally siempre imprime "Desconectando de la base de datos..." (simulando cierre de conexión). El programa permite al usuario probar varios comandos (bucle while) hasta que ingrese "exit" para salir. Muestra el flujo completo de conexión, operación, y desconexión en cada iteración.
**Entrada:** Comando SQL como cadena (str), "exit" para salir.
**Salida:** Flujo de conexión, operación (éxito o error capturado), y desconexión en finally en cada iteración, y resumen de comandos ejecutados.

### Ejercicio 126: Algoritmo para encender una computadora
**Enunciado:** Escribe en lenguaje natural los pasos precisos, definidos y finitos para encender una computadora desde que está apagada hasta que el sistema operativo está listo.
**Entrada:** Ninguna.
**Salida:** Secuencia de pasos que finaliza con la computadora lista para usar.

### Ejercicio 127: EPS para calcular el perímetro de un triángulo
**Enunciado:** Plantea el modelo Entrada-Proceso-Salida para calcular el perímetro de un triángulo dados sus tres lados.
**Entrada:** lado1=3, lado2=4, lado3=5
**Salida:** El perímetro del triángulo es: 12

### Ejercicio 128: Algoritmo para saber si un año es bisiesto
**Enunciado:** Escribe los pasos del algoritmo que reciba un año y determine si es bisiesto (divisible entre 4, pero no entre 100 salvo que sea divisible entre 400).
**Entrada:** año=2024
**Salida:** 2024 es un año bisiesto

### Ejercicio 129: Pseudocódigo: saludo con nombre y edad
**Enunciado:** Escribe pseudocódigo que pida nombre y edad e imprima un mensaje personalizado indicando si la persona es mayor o menor de edad.
**Entrada:** Nombre: Luis, Edad: 30
**Salida:** Hola Luis, eres mayor de edad

### Ejercicio 130: Pseudocódigo: días de la semana
**Enunciado:** Escribe pseudocódigo que reciba un número del 1 al 7 y muestre el día de la semana correspondiente usando estructura Si-Entonces-Sino.
**Entrada:** 3
**Salida:** Miércoles

### Ejercicio 131: Pseudocódigo: sueldo con bono
**Enunciado:** Escribe pseudocódigo que calcule el sueldo final de un empleado: sueldo base + bono del 5% si el empleado lleva más de 5 años en la empresa.
**Entrada:** sueldo_base=12000, años=7
**Salida:** Sueldo final: 12600

### Ejercicio 132: Tipos de datos con input()
**Enunciado:** Indica el tipo de dato en Python de cada valor recibido por input(): '42', '3.50', 'True', 'Hola'. Luego indica el tipo después de convertir cada uno con su casting adecuado.
**Entrada:** Ninguna (ejercicio de análisis).
**Salida:** 42→str→int; 3.50→str→float; True→str→bool; Hola→str→str

### Ejercicio 133: Resultado de expresiones con // y %
**Enunciado:** Calcula mentalmente las siguientes expresiones: 17 // 5, 17 % 5, 20 // 4, 20 % 4, 23 // 7, 23 % 7.
**Entrada:** Ninguna.
**Salida:** 3, 2, 5, 0, 3, 2

### Ejercicio 134: Precedencia: operadores aritméticos y relacionales combinados
**Enunciado:** Evalúa paso a paso la expresión: 3 + 4 * 2 > 10 and 5 ** 2 == 25. Indica el valor booleano final.
**Entrada:** Ninguna.
**Salida:** True

### Ejercicio 135: Rastreo de variable con operador de asignación aumentada
**Enunciado:** Sigue el rastro de x en: x = 10; x += 3; x *= 2; x -= 5. ¿Cuál es el valor final?
**Entrada:** Ninguna.
**Salida:** x = 21

### Ejercicio 136: Programa que pide 3 palabras y las reúne
**Enunciado:** Crea un programa que pida tres palabras separadas y las imprima en una sola línea con espacios, usando f-strings.
**Entrada:** Sol, Luna, Estrella
**Salida:** Sol Luna Estrella

### Ejercicio 137: Calculadora de área de un triángulo con input
**Enunciado:** Crea un programa que pida la base y la altura de un triángulo y calcule su área (base * altura / 2), mostrando el resultado con dos decimales.
**Entrada:** base=6.5, altura=4.2
**Salida:** El área del triángulo es: 13.65

### Ejercicio 138: Conversor de grados a radianes
**Enunciado:** Crea un programa que pida un ángulo en grados y lo convierta a radianes (rad = grad * π / 180), usando math.pi.
**Entrada:** 180
**Salida:** 180 grados = 3.141592653589793 radianes

### Ejercicio 139: Cálculo de la hipotenusa con input
**Enunciado:** Crea un programa que pida los dos catetos de un triángulo rectángulo y calcule la hipotenusa con (a**2 + b**2)**0.5.
**Entrada:** cateto_a=3, cateto_b=4
**Salida:** La hipotenusa es: 5.0

### Ejercicio 140: Comparador de dos números con input
**Enunciado:** Crea un programa que pida dos números y diga cuál es mayor, cuál es menor, o si son iguales, usando comparaciones y print.
**Entrada:** a=8, b=8
**Salida:** Los números son iguales (8 y 8)

### Ejercicio 141: Ticket de compra con impuestos variables
**Enunciado:** Crea un programa que pida precio de 3 artículos y un porcentaje de impuesto, calcule subtotal, impuesto y total, y muestre un ticket con f-strings.
**Entrada:** Precios: 20, 15, 10; Impuesto: 19%
**Salida:** Subtotal: $45.00; Impuesto (19%): $8.55; Total: $53.55

### Ejercicio 142: Promedio de 5 números con casting
**Enunciado:** Crea un programa que pida 5 números enteros y calcule el promedio como float, mostrándolo con un decimal.
**Entrada:** 5, 7, 8, 6, 9
**Salida:** El promedio es: 7.0

### Ejercicio 143: Clasificación de triángulo por ángulos
**Enunciado:** Crea un programa que pida tres ángulos de un triángulo y determine si es acutángulo (todos < 90), rectángulo (uno = 90) u obtusángulo (uno > 90).
**Entrada:** ángulos: 60, 60, 60
**Salida:** El triángulo es acutángulo

### Ejercicio 144: Descuento por categoría y monto
**Enunciado:** Crea un programa que aplique descuentos combinados: si el cliente es 'estudiante' tiene 10% adicionales; si el monto es mayor a $200 hay 5% extra. Muestra el precio final.
**Entrada:** tipo=estudiante, monto=250
**Salida:** Precio final: $202.50

### Ejercicio 145: Validación de contraseña con longitud y mayúscula
**Enunciado:** Crea un programa que pida una contraseña y valide que tenga al menos 8 caracteres y al menos una mayúscula; usa len() y un if anidado.
**Entrada:** contraseña='Hola123'
**Salida:** Contraseña inválida: debe tener al menos una mayúscula

### Ejercicio 146: Calificación con cinco categorías y elif
**Enunciado:** Crea un programa que convierta una calificación numérica a Letra: A(≥9), B(≥8), C(≥7), D(≥6), E(≥5), F(<5).
**Entrada:** calificación=7.5
**Salida:** Calificación: C

### Ejercicio 147: ¿Es múltiplo de 3 y de 5 a la vez?
**Enunciado:** Crea un programa que pida un número y determine si es múltiplo de 3, de 5, de ambos, o de ninguno, usando operadores lógicos and/or.
**Entrada:** número=15
**Salida:** El número 15 es múltiplo de 3 y de 5

### Ejercicio 148: Aprobación de crédito bancario
**Enunciado:** Crea un programa que evalúe si se aprueba un crédito: Ingresos > $3000 Y historial = 'bueno' → aprobado; Ingresos > $5000 Y historial = 'regular' → aprobado; caso contrario → rechazado.
**Entrada:** ingresos=4000, historial='bueno'
**Salida:** Crédito aprobado

### Ejercicio 149: Descuento por estacionalidad
**Enunciado:** Crea un programa que aplique descuento según la temporada: verano 15%, invierno 20%, otras 5%. Pide estación y precio.
**Entrada:** estación=invierno, precio=1000
**Salida:** Precio final con descuento invierno (20%): $800.00

### Ejercicio 150: Verificación de rebaño de ovejas
**Enunciado:** Crea un programa que pida la cantidad de ovejas y determine si el rebaño es pequeño (<50), mediano (50-200) o grande (>200).
**Entrada:** cantidad=150
**Salida:** El rebaño es mediano (150 ovejas)

### Ejercicio 151: Verificación de acceso a zona restringida con tupla y if
**Enunciado:** Crea un programa que tenga una tupla con los nombres de usuarios autorizados. Pida un nombre con input e indique si está autorizado o no usando 'in' sobre la tupla.
**Entrada:** usuarios=('admin','juan','maria'); ingreso: 'luis'
**Salida:** Acceso denegado: luis no está autorizado

### Ejercicio 152: Contador de 10 al 1 con while
**Enunciado:** Escribe un programa que imprima los números del 10 al 1 usando un while con decremento.
**Entrada:** Ninguna.
**Salida:** 10, 9, 8, …, 1

### Ejercicio 153: Acumulador de números con centinela negativo
**Enunciado:** Crea un programa que sume números ingresados con while; se detiene cuando el usuario ingresa un número negativo y muestra el total de positivos.
**Entrada:** 4, 8, 12, -1
**Salida:** La suma de los positivos es: 24

### Ejercicio 154: Tabla de multiplicar al revés con while
**Enunciado:** Crea un programa que pida un número y muestre su tabla de multiplicar del 10 al 1 en orden descendente usando while.
**Entrada:** número=4
**Salida:** 4x10=40, 4x9=36, …, 4x1=4

### Ejercicio 155: Secuencia de Collatz con while
**Enunciado:** Crea un programa que reciba un número entero positivo y genere la secuencia de Collatz: si es par se divide entre 2, si es impar se multiplica por 3 y suma 1; se repite hasta llegar a 1.
**Entrada:** n=6
**Salida:** Secuencia: 6, 3, 10, 5, 16, 8, 4, 2, 1

### Ejercicio 156: Suma de dígitos de un número con while
**Enunciado:** Crea un programa que descomponga un número entero positivo en sus dígitos y sume sus valores usando while y %10 //10.
**Entrada:** número=1234
**Salida:** La suma de los dígitos de 1234 es: 10

### Ejercicio 157: Promedio de gastos con centinela 'fin'
**Enunciado:** Crea un programa que capture montos de gastos; cuando el usuario escriba 'fin', muestra el promedio de los montos ingresados con dos decimales.
**Entrada:** 100, 200, 150, fin
**Salida:** El promedio de gastos es: 150.00

### Ejercicio 158: Mayor y menor con while
**Enunciado:** Crea un programa que capture números indefinidamente; al escribir 'parar', muestra el mayor y el menor capturado.
**Entrada:** 5, 12, 3, 8, parar
**Salida:** Mayor: 12; Menor: 3

### Ejercicio 159: Conteo de vocales en palabra con while
**Enunciado:** Crea un programa que pida una palabra y recorra sus caracteres con while para contar cuántas vocales (a, e, i, o, u) contiene.
**Entrada:** palabra='programacion'
**Salida:** La palabra 'programacion' tiene 5 vocales

### Ejercicio 160: Validación de edad con while hasta que sea válida
**Enunciado:** Crea un programa que pida la edad; si está fuera de rango (0-120) vuelve a pedirla; cuando es válida, muestra un mensaje de confirmación.
**Entrada:** Intentos: -5, 150, 25
**Salida:** Edad válida capturada: 25 años

### Ejercicio 161: Error de sintaxis por paréntesis de cierre faltante
**Enunciado:** El código es: print('Hola' . Indica qué tipo de error es, cuál es la causa exacta y cómo corregirlo.
**Entrada:** Ninguna.
**Salida:** SyntaxError: faltan cerrar paréntesis; corregir a print('Hola')

### Ejercicio 162: Error de lógica en cálculo de descuento
**Enunciado:** El código aplica descuento = precio * 0.10 y luego total = precio - 0.10. Identifica el error lógico y escribe la corrección.
**Entrada:** precio=200
**Salida:** Error: se resta 0.10 en lugar del descuento calculado; corregir a total = precio - descuento

### Ejercicio 163: Depurar con breakpoint() dentro de un for
**Enunciado:** ¿En qué línea colocarías breakpoint() para inspeccionar la variable acumuladora en un ciclo for que calcula la suma de una lista? Describe el procedimiento.
**Entrada:** Ninguna.
**Salida:** Agregar breakpoint() dentro del for, antes o después de la acumulación; usar comando 'p acumulador' en PDB

### Ejercicio 164: Error de ejecución por división entre cero en función
**Enunciado:** El código define: def dividir(a, b): return a / b. Luego llama dividir(5, 0). Indica el tipo de error y cómo capturarlo.
**Entrada:** Ninguna.
**Salida:** ZeroDivisionError; capturar con try-except ZeroDivisionError

### Ejercicio 165: Rastreo de variable en ciclo anidado
**Enunciado:** Dado: for i in range(3): for j in range(2): print(i+j). Sigue el rastro e indica cuántas veces se ejecuta el print y el valor de la última impresión.
**Entrada:** Ninguna.
**Salida:** Se ejecuta 6 veces; última impresión: 3 (i=2, j=1, 2+1=3)

### Ejercicio 166: Desde 0 hasta N con paso 2 usando for
**Enunciado:** Escribe un programa que imprima los números pares del 0 al 20 usando for con range(0, 21, 2).
**Entrada:** Ninguna.
**Salida:** 0, 2, 4, …, 20

### Ejercicio 167: Suma de los primeros N impares con for
**Enunciado:** Crea un programa que pida N e imprima los primeros N números impares (1, 3, 5, …) usando for.
**Entrada:** N=5
**Salida:** Primeros 5 impares: 1, 3, 5, 7, 9

### Ejercicio 168: Tabla de potencias con for descendente
**Enunciado:** Crea un programa que pida un número y genere su tabla de potencias desde la 5 hasta la 1 usando for con range descendente.
**Entrada:** base=3
**Salida:** 3^5=243, 3^4=81, 3^3=27, 3^2=9, 3^1=3

### Ejercicio 169: Producto acumulado con for
**Enunciado:** Crea un programa que calcule el producto de los números del 1 al N usando for y un acumulador.
**Entrada:** N=5
**Salida:** El producto es: 120

### Ejercicio 170: Números divisibles por 4 del 1 al 50 con for
**Enunciado:** Crea un programa que imprima todos los números del 1 al 50 que son divisibles por 4, usando for y una condición if.
**Entrada:** Ninguna.
**Salida:** 4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48

### Ejercicio 171: Factorial de un número con for y acumulador
**Enunciado:** Crea un programa que pida un número entero positivo y calcule su factorial con un ciclo for.
**Entrada:** n=6
**Salida:** El factorial de 6 es: 720

### Ejercicio 172: Impresión de pirámide numérica con for anidados
**Enunciado:** Crea un programa que pida un número de filas y dibuje una pirámide centrada de números: fila 1: '1', fila 2: '121', fila 3: '12321'.
**Entrada:** filas=3
**Salida:**   1
 121
12321

### Ejercicio 173: Conteo de caracteres en varias palabras con for
**Enunciado:** Crea un programa que capture 5 palabras con un for y, al final, muestre la palabra más larga y su longitud.
**Entrada:** palabras: perro, gato, elefante, raton, loro
**Salida:** La palabra más larga es 'elefante' con 8 caracteres

### Ejercicio 174: Suma de columnas de una matriz 3x4 con for
**Enunciado:** Crea un programa que defina una matriz 3x4 y sume cada columna usando for anidados, imprimiendo el resultado por columna.
**Entrada:** matriz=[[1,2,3,4],[5,6,7,8],[9,10,11,12]]
**Salida:** Suma columna 0: 15; columna 1: 18; columna 2: 21; columna 3: 24

### Ejercicio 175: Crear lista de estaciones del año
**Enunciado:** Crea una lista llamada 'estaciones' con las 4 estaciones en orden, y muestra el primer y último elemento con índices 0 y -1.
**Entrada:** Ninguna.
**Salida:** Primavera (índice 0) y Invierno (índice -1)

### Ejercicio 176: Usar insert() para agregar en posición específica
**Enunciado:** Dada lista = ['a','b','c','d'], inserta 'x' en la posición 1 e imprime la lista resultante.
**Entrada:** Ninguna.
**Salida:** ['a', 'x', 'b', 'c', 'd']

### Ejercicio 177: Eliminar elemento por índice con pop()
**Enunciado:** Dada lista = ['rojo','verde','azul','amarillo'], elimina el elemento en índice 2 con pop() e imprime qué se eliminó y la lista final.
**Entrada:** Ninguna.
**Salida:** Se eliminó 'azul'; lista final: ['rojo', 'verde', 'amarillo']

### Ejercicio 178: Operador de concatenación de listas +
**Enunciado:** Dadas listas a = [1,2,3] y b = [4,5,6], crea c = a + b e imprime el resultado. ¿Se modifican a o b?
**Entrada:** Ninguna.
**Salida:** c = [1,2,3,4,5,6]; a y b no se modifican

### Ejercicio 179: Slicing para obtener sublista
**Enunciado:** Dada lista = [10,20,30,40,50], extrae con slicing la sublista de índice 1 a 3 (sin incluir 3) e imprime.
**Entrada:** Ninguna.
**Salida:** Sublista: [20,30]

### Ejercicio 180: Invertir lista con slicing
**Enunciado:** Dada lista = ['manzana','banana','cereza'], crea una nueva lista con el orden invertido usando slicing [::-1] e imprímela.
**Entrada:** Ninguna.
**Salida:** ['cereza', 'banana', 'manzana']

### Ejercicio 181: Recorrido con for e índice usando enumerate
**Enunciado:** Dada lista = ['lunes','martes','miercoles','jueves'], recórrela con un for usando enumerate e imprime cada día con su posición.
**Entrada:** Ninguna.
**Salida:** 0: lunes, 1: martes, 2: miercoles, 3: jueves

### Ejercicio 182: Buscar el valor máximo de una lista manualmente
**Enunciado:** Crea un programa que recorra una lista de números con for y determine el valor máximo sin usar max(); imprime el resultado.
**Entrada:** lista=[3,7,2,9,4]
**Salida:** El valor máximo es: 9

### Ejercicio 183: Eliminar elementos duplicados de una lista
**Enunciado:** Crea un programa que recibe una lista con duplicados y genera una nueva lista sin duplicados recorriéndola con for y usando 'not in'.
**Entrada:** lista=[1,2,2,3,1,4,3]
**Salida:** Lista sin duplicados: [1,2,3,4]

### Ejercicio 184: Lista de compras interactiva con append
**Enunciado:** Crea un programa que pida productos con un ciclo while hasta que el usuario escriba 'listo', los vaya agregando a una lista con append(), y al final imprima la lista completa.
**Entrada:** Productos: leche, huevos, pan, listo
**Salida:** Lista de compras: ['leche', 'huevos', 'pan']

### Ejercicio 185: Crear matriz 2x4 y mostrar filas
**Enunciado:** Crea una lista de listas que represente una matriz de 2 filas y 4 columnas con los valores dados, e imprime cada fila en una línea.
**Entrada:** matriz=[[10,20,30,40],[50,60,70,80]]
**Salida:** Fila 0: [10,20,30,40]; Fila 1: [50,60,70,80]

### Ejercicio 186: Acceder a elemento específico de matriz 4x4
**Enunciado:** Dada una matriz 4x4 con números del 1 al 16 dispuestos por filas, imprime el elemento en fila 3, columna 2 (índice base 0).
**Entrada:** Ninguna.
**Salida:** Elemento fila 3, columna 2: 14

### Ejercicio 187: Suma de todos los elementos de una matriz
**Enunciado:** Crea un programa que calcule la suma total de todos los elementos de una matriz 3x3 recorrida con ciclos anidados.
**Entrada:** matriz=[[1,2,3],[4,5,6],[7,8,9]]
**Salida:** Suma total de la matriz: 45

### Ejercicio 188: Transponer una matriz 2x3
**Enunciado:** Crea un programa que tome una matriz 2x3 y genere su transpuesta (3x2) usando ciclos anidados.
**Entrada:** matriz=[[1,2,3],[4,5,6]]
**Salida:** Matriz transpuesta: [[1,4],[2,5],[3,6]]

### Ejercicio 189: Buscar un valor en matriz y reportar posición
**Enunciado:** Crea un programa que busque un valor dado en una matriz 3x3 y, si lo encuentra, imprima su fila y columna; si no, 'no encontrado'.
**Entrada:** valor=5, matriz=[[1,2,3],[4,5,6],[7,8,9]]
**Salida:** Valor 5 encontrado en fila 1, columna 1

### Ejercicio 190: Suma de la diagonal secundaria de una matriz cuadrada
**Enunciado:** Crea un programa que sume los elementos de la diagonal secundaria de una matriz 3x3 (donde fila+columna=n-1).
**Entrada:** matriz=[[1,2,3],[4,5,6],[7,8,9]]
**Salida:** Suma diagonal secundaria: 15 (3+5+7)

### Ejercicio 191: Multiplicación escalar de una matriz
**Enunciado:** Crea un programa que reciba una matriz 2x2 y un número escalar, y genere una nueva matriz con cada elemento multiplicado por el escalar.
**Entrada:** matriz=[[1,2],[3,4]], escalar=3
**Salida:** Matriz resultante: [[3,6],[9,12]]

### Ejercicio 192: Matriz de suma de filas
**Enunciado:** Crea un programa que calcule la suma de cada fila de una matriz 3x3 y la almacene en una lista, imprimiendo el resultado.
**Entrada:** matriz=[[1,0,0],[0,1,0],[0,0,1]]
**Salida:** Suma filas: [1,1,1]

### Ejercicio 193: Comparar dos matrices elemento a elemento
**Enunciado:** Crea un programa que compare dos matrices 2x2 y determine cuántos elementos son iguales en la misma posición.
**Entrada:** m1=[[1,2],[3,4]], m2=[[1,5],[3,4]]
**Salida:** Elementos iguales en posición: 3 de 4

### Ejercicio 194: Matriz como grilla de juego: contar celdas con valor 1
**Enunciado:** Crea un programa que recorra una matriz 4x4 que representa una grilla (0=vacío, 1=obstáculo) y cuente cuántos obstáculos hay.
**Entrada:** grilla=[[0,1,0,0],[1,0,1,0],[0,0,0,1],[1,1,0,0]]
**Salida:** Cantidad de obstáculos (1s): 5

### Ejercicio 195: Procedimiento que imprime un mensaje de bienvenida
**Enunciado:** Define una función saludar_curso() que no recibe parámetros ni regresa valor, e imprima 'Bienvenido al curso de Fundamentos de Programación'.
**Entrada:** Ninguna.
**Salida:** Bienvenido al curso de Fundamentos de Programación

### Ejercicio 196: Procedimiento que recibe precio y muestra descuento del 20%
**Enunciado:** Define una función mostrar_precio_descuento(precio) que no regresa valor, calcula el 20% de descuento e imprime el precio final.
**Entrada:** precio=500
**Salida:** Precio con 20% de descuento: $400.00

### Ejercicio 197: Procedimiento que imprime la tabla de suma de un número
**Enunciado:** Define una función tabla_suma(n) que no regresa valor e imprime la suma de n con los números del 1 al 10.
**Entrada:** n=7
**Salida:** 7+1=8, 7+2=9, …, 7+10=17

### Ejercicio 198: Procedimiento que recorre e imprime lista con índice
**Enunciado:** Define una función imprimir_con_indices(lista) que no regresa valor e imprime cada elemento con su posición, usando un ciclo for y range(len(lista)).
**Entrada:** lista=['a','b','c']
**Salida:** 0: a, 1: b, 2: c

### Ejercicio 199: Procedimiento que calcula y muestra el área de un rectángulo
**Enunciado:** Define una función area_rectangulo(base, altura) que no regresa valor e imprime el área calculada.
**Entrada:** base=5, altura=8
**Salida:** El área del rectángulo es: 40

### Ejercicio 200: Procedimiento que valida y muestra si número es primo
**Enunciado:** Define una función verificar_primo(n) que no regresa valor e imprime si el número es primo o no, usando un ciclo for para probar divisores.
**Entrada:** n=17
**Salida:** 17 es un número primo

### Ejercicio 201: Procedimiento que concatena elementos de una lista con un separador
**Enunciado:** Define una función unir_lista(lista, separador) que no regresa valor e imprime la cadena resultante de unir los elementos con el separador.
**Entrada:** lista=['hola','mundo','python'], separador='-'
**Salida:** hola-mundo-python

### Ejercicio 202: Procedimiento que imprime un histograma de asteriscos
**Enunciado:** Define una función histograma(lista) que no regresa valor e imprima para cada número de la lista una línea con tantos asteriscos como indique el número.
**Entrada:** lista=[3,5,2]
**Salida:** ***
*****
**

### Ejercicio 203: Procedimiento que muestra divisores de un número
**Enunciado:** Define una función mostrar_divisores(n) que no regresa valor e imprima todos los divisores de n encontrados con un for.
**Entrada:** n=12
**Salida:** Divisores de 12: 1, 2, 3, 4, 6, 12

### Ejercicio 204: Procedimiento que imprime la fecha de hoy formateada
**Enunciado:** Define una función mostrar_fecha_hoy() que no recibe parámetros ni regresa valor, use el módulo datetime para obtener la fecha actual e imprima en formato 'dd/mm/aaaa'.
**Entrada:** Ninguna.
**Salida:** La fecha de hoy es: (fecha actual formateada)

### Ejercicio 205: Función que regresa el perímetro de un círculo
**Enunciado:** Define una función perimetro_circulo(radio) que retorne el perímetro calculado con 2 * π * radio.
**Entrada:** radio=7
**Salida:** El perímetro es: 43.982297150257104

### Ejercicio 206: Función que regresa True si el número es perfecto
**Enunciado:** Define una función es_perfecto(n) que retorne True si la suma de sus divisores propios (sin contar n) es igual a n, False en caso contrario.
**Entrada:** n=6
**Salida:** Es número perfecto: True (1+2+3=6)

### Ejercicio 207: Función que regresa el mínimo de una lista
**Enunciado:** Define una función minimo(lista) que retorne el valor mínimo de una lista de números usando un for, sin usar min().
**Entrada:** lista=[12,5,8,3,15]
**Salida:** El mínimo es: 3

### Ejercicio 208: Función que regresa una lista con los números primos del 1 al N
**Enunciado:** Define una función primos_hasta(n) que retorne una lista con los números primos entre 1 y n.
**Entrada:** n=20
**Salida:** Primos hasta 20: [2,3,5,7,11,13,17,19]

### Ejercicio 209: Función que regresa el promedio ponderado
**Enunciado:** Define una función promedio_ponderado(notes, weights) que retorne el promedio considerando los pesos dados como listas del mismo tamaño.
**Entrada:** notes=[8,9,7], weights=[0.3,0.4,0.3]
**Salida:** Promedio ponderado: 8.1

### Ejercicio 210: Función que regresa el valor intercambiado de dos variables como tupla
**Enunciado:** Define una función intercambiar(a, b) que retorne una tupla (b, a) con los valores intercambiados.
**Entrada:** a=10, b=25
**Salida:** Resultado: (25, 10)

### Ejercicio 211: Función que regresa la cantidad de dígitos de un entero
**Enunciado:** Define una función contar_digitos(n) que retorne cuántos dígitos tiene un número entero positivo (puede usar str o división).
**Entrada:** n=12345
**Salida:** Cantidad de dígitos: 5

### Ejercicio 212: Función que regresa lista de cuadrados
**Enunciado:** Define una función cuadrados_lista(lista) que retorne una nueva lista con el cuadrado de cada elemento.
**Entrada:** lista=[1,2,3,4]
**Salida:** Cuadrados: [1,4,9,16]

### Ejercicio 213: Función que regresa la distancia entre dos puntos 2D
**Enunciado:** Define una función distancia(p1, p2) que reciba dos tuplas (x, y) y retorne la distancia euclidiana.
**Entrada:** p1=(1,2), p2=(4,6)
**Salida:** Distancia: 5.0

### Ejercicio 214: Composición: función que regresa el área de dos triángulos
**Enunciado:** Define una función area_triangulo(base, altura) que retorne (base * altura / 2). Luego define otra función que use area_triangulo para calcular el área de dos triángulos y sumarlos.
**Entrada:** base1=5,altura1=4,base2=3,altura2=6
**Salida:** Área total de ambos triángulos: 19.0 (10 + 9)

### Ejercicio 215: Tupla de meses y acceso por índice
**Enunciado:** Dada tupla meses = ('enero','febrero','marzo','abril','mayo'), imprime el mes en índice 3 y el último mes usando índice negativo.
**Entrada:** Ninguna.
**Salida:** mes índice 3: abril; último mes: mayo

### Ejercicio 216: Concatenar tuplas de notas
**Enunciado:** Dadas t1 = (8,9) y t2 = (10,7), crea t3 = t1 + t2 e imprime la tupla resultante y su longitud.
**Entrada:** Ninguna.
**Salida:** t3 = (8,9,10,7); longitud: 4

### Ejercicio 217: Desempaquetado de tupla con 5 elementos
**Enunciado:** Desempaqueta la tupla (10,20,30,40,50) en 5 variables a, b, c, d, e e imprime cada una.
**Entrada:** Ninguna.
**Salida:** a=10, b=20, c=30, d=40, e=50

### Ejercicio 218: Tupla de tuplas: acceder a elemento anidado
**Enunciado:** Dada tupla anidada = ((1,2),(3,4),(5,6)), imprime el elemento 4 accediendo con índices dobles.
**Entrada:** Ninguna.
**Salida:** Elemento 4: (3,4) → índice [1][1]

### Ejercicio 219: Convertir tupla a lista, modificar y volver a tupla
**Enunciado:** Dada tupla = (5,3,9,1), convierte a lista, ordena, agrega el valor 10, y convierte de nuevo a tupla; imprime la tupla resultante.
**Entrada:** Ninguna.
**Salida:** Tupla resultante: (1,3,5,9,10)

### Ejercicio 220: Operador in con tupla
**Enunciado:** Dada tupla = (10,20,30,40), evalúa con 'in' si el número 25 está en la tupla e imprime el resultado booleano.
**Entrada:** Ninguna.
**Salida:** 25 in tupla: False

### Ejercicio 221: Método count() en tupla de resultados de exámenes
**Enunciado:** Dada tupla = (7,8,7,9,7,10,7), usa count() para contar cuántas veces aparece el 7 e imprime el resultado.
**Entrada:** Ninguna.
**Salida:** El 7 aparece 4 veces en la tupla

### Ejercicio 222: Método index() para encontrar posición de un elemento
**Enunciado:** Dada tupla = ('rojo','verde','azul','amarillo'), usa index() para encontrar la posición de 'azul' e imprime el índice.
**Entrada:** Ninguna.
**Salida:** Índice de 'azul': 2

### Ejercicio 223: Tupla inmutable: intentar modificar genera error
**Enunciado:** Intenta asignar un nuevo valor al primer elemento de la tupla (5,10,15). Indica qué mensaje de error genera Python.
**Entrada:** Ninguna.
**Salida:** TypeError: 'tuple' object does not support item assignment

### Ejercicio 224: Función que regresa una tupla con el mínimo y máximo de una lista
**Enunciado:** Define una función min_max(lista) que retorne una tupla (minimo, maximo) calculados con un for.
**Entrada:** lista=[5,2,8,1,9]
**Salida:** Mínimo y máximo: (1,9)

### Ejercicio 225: Diccionario de población por país
**Enunciado:** Dado diccionario = {'México':126, 'España':47, 'Argentina':45}, imprime la población de España y agrega 'Colombia':50.
**Entrada:** Ninguna.
**Salida:** España: 47; diccionario actualizado con Colombia: 50

### Ejercicio 226: Iterar sobre items() e imprimir población formateada
**Enunciado:** Con el diccionario anterior, recorre items() e imprime cada país con su población en formato 'País: Población millones'.
**Entrada:** Ninguna.
**Salida:** México: 126 millones; España: 47 millones; Argentina: 45 millones

### Ejercicio 227: Actualizar población con valor nuevo y verificar existencia
**Enunciado:** Actualiza la población de 'México' a 128 en el diccionario anterior. Luego verifica con 'in' si 'Brasil' está en el diccionario e imprime el resultado.
**Entrada:** Ninguna.
**Salida:** México actualizado a 128; 'Brasil' en diccionario: False

### Ejercicio 228: Usar get() con valor por defecto para país ausente
**Enunciado:** Con el diccionario de países, usa get('Perú', 'No encontrado') e imprime el resultado.
**Entrada:** Ninguna.
**Salida:** No encontrado (Perú no está en el diccionario)

### Ejercicio 229: Eliminar elemento de diccionario con pop()
**Enunciado:** Elimina la clave 'Argentina' del diccionario de países usando pop() e imprime el valor eliminado y el diccionario restante.
**Entrada:** Ninguna.
**Salida:** Valor eliminado: 45; Diccionario restante: {'México':126, 'España':47, 'Colombia':50}

### Ejercicio 230: Diccionario de frecuencias de letras en una palabra
**Enunciado:** Crea un programa que capture una palabra e genere un diccionario donde cada clave es una letra y su valor es la cantidad de veces que aparece.
**Entrada:** palabra='programacion'
**Salida:** Frecuencias: {'p':1,'r':2,'o':1,'g':1,'a':2,'m':1,'c':1,'i':1,'n':1}

### Ejercicio 231: Diccionario de ventas por producto
**Enunciado:** Crea un programa que permita registrar ventas de productos: pide producto y cantidad, y almacena en un diccionario; cuando el usuario escribe 'fin', muestra el diccionario completo.
**Entrada:** Producto A: 10, Producto B: 5, fin
**Salida:** Ventas: {'Producto A': 10, 'Producto B': 5}

### Ejercicio 232: Función que busca en diccionario y retorna valor o None
**Enunciado:** Define una función buscar(dic, clave) que retorne el valor asociado o None si la clave no existe.
**Entrada:** dic={'a':1,'b':2}, clave='c'
**Salida:** buscar(dic,'c'): None

### Ejercicio 233: Ordenar diccionario por valores
**Enunciado:** Dado diccionario calificaciones = {'Ana':9,'Luis':7,'Mía':10,'Carlos':8}, ordena e imprime los nombres de mayor a menor calificación.
**Entrada:** Ninguna.
**Salida:** Orden: Mía (10), Ana (9), Carlos (8), Luis (7)

### Ejercicio 234: Diccionario anidado: datos de estudiantes
**Enunciado:** Crea un diccionario anidado donde cada clave es un nombre y el valor es otro diccionario con 'edad' y 'calificación'. Imprime la calificación de 'Ana'.
**Entrada:** Ninguna.
**Salida:** Calificación de Ana: 9.5

### Ejercicio 235: Capturar ValueError al intentar convertir 'abc' a entero
**Enunciado:** Escribe un try-except que capture ValueError al ejecutar int('abc') e imprima 'Error: entrada no numérica'.
**Entrada:** Ninguna.
**Salida:** Error: entrada no numérica

### Ejercicio 236: Capturar ZeroDivisionError en función de división
**Enunciado:** Define una función dividir(a, b) y captura ZeroDivisionError cuando b es 0, imprimiendo 'No se puede dividir entre cero'.
**Entrada:** a=10, b=0
**Salida:** No se puede dividir entre cero

### Ejercicio 237: Capturar TypeError al sumar str + int
**Enunciado:** Escribe un try-except que capture TypeError al ejecutar '20' + 5 e imprima un mensaje controlado.
**Entrada:** Ninguna.
**Salida:** Error: No se puede sumar texto con número

### Ejercicio 238: Capturar IndexError al acceder a índice no existente
**Enunciado:** Escribe un try-except que capture IndexError al intentar acceder a lista[10] donde lista = [1,2,3] e imprima 'Índice fuera de rango'.
**Entrada:** Ninguna.
**Salida:** Índice fuera de rango

### Ejercicio 239: Capturar KeyError al consultar clave inexistente en diccionario
**Enunciado:** Escribe un try-except que capture KeyError al intentar acceder a dic['edad'] donde dic = {'nombre':'Ana'} e imprima 'Clave no encontrada'.
**Entrada:** Ninguna.
**Salida:** Clave no encontrada

### Ejercicio 240: Capturar Exception general con mensaje del error
**Enunciado:** Escribe un try-except con except Exception as e que capture cualquier error al dividir 5/0 e imprima 'Ocurrió un error: ' + str(e).
**Entrada:** Ninguna.
**Salida:** Ocurrió un error: division by zero

### Ejercicio 241: Bloque else en división exitosa
**Enunciado:** Escribe un try-except-else que divida 10/2 e imprima en el bloque else 'División realizada correctamente: resultado'.
**Entrada:** Ninguna.
**Salida:** División realizada correctamente: 5.0

### Ejercicio 242: Bloque finally que siempre se ejecuta
**Enunciado:** Escribe un try-except-finally donde se intenta dividir 8/0; el finally debe imprimir 'Cálculo finalizado'.
**Entrada:** Ninguna.
**Salida:** Error de división; 'Cálculo finalizado'

### Ejercicio 243: Validación de entrada numérica con while y try-except
**Enunciado:** Crea un programa que pida un número entero; si el usuario ingresa texto inválido, captura ValueError y vuelve a pedirlo; cuando es válido, imprime el número al cuadrado.
**Entrada:** Intentos: 'hola', '3.5', '7'
**Salida:** Número válido: 7; su cuadrado es: 49

### Ejercicio 244: Función que retorna valor por defecto ante excepción
**Enunciado:** Define una función segura_division(a, b) que intente retornar a/b, y si ocurre cualquier error, retorne 0.
**Entrada:** a=10, b=0
**Salida:** Resultado seguro: 0 (por división entre cero)

### Ejercicio 245: Capturar ZeroDivisionError en función de división con finally
**Enunciado:** Define una función dividir_con_finally(a, b) que intente retornar a/b; si hay ZeroDivisionError, imprima error y retorne None; el finally siempre imprima 'División terminada'.
**Entrada:** a=10, b=0
**Salida:** Error: división entre cero; 'División terminada'; Retorno: None

### Ejercicio 246: Capturar excepción al acceder a índice de tupla con try-except
**Enunciado:** Escribe un try-except que capture IndexError al intentar acceder a tupla[10] donde tupla = (1,2,3) e imprima 'Índice de tupla fuera de rango'.
**Entrada:** Ninguna.
**Salida:** Índice de tupla fuera de rango

### Ejercicio 247: Convertir texto a mayúsculas y contar vocales mayúsculas
**Enunciado:** Dado texto = 'Aprender Python es divertido', convierte a mayúsculas con upper() e imprime el resultado y la cantidad de vocales (A,E,I,O,U) que contiene.
**Entrada:** Ninguna.
**Salida:** MAYÚSCULAS: APRENDER PYTHON ES DIVERTIDO; vocales: 10

### Ejercicio 248: Extraer palabra del medio con slicing
**Enunciado:** Dado texto = 'Hola como estas', extrae la palabra 'como' usando slicing ([5:9]) e imprime.
**Entrada:** Ninguna.
**Salida:** Palabra extraída: 'como'

### Ejercicio 249: Verificar si una palabra empieza con cierta letra
**Enunciado:** Escribe un programa que pida una palabra e indique si empieza con la letra 'P' usando startswith().
**Entrada:** palabra='Python'
**Salida:** La palabra empieza con P: True

### Ejercicio 250: Reemplazar palabra con replace() y mostrar el nuevo texto
**Enunciado:** Dado texto = 'El gato es pequeño', reemplaza 'gato' por 'perro' e imprime el texto resultante.
**Entrada:** Ninguna.
**Salida:** El perro es pequeño



Resuelve los ejercicios conforme avances en los temas. Cada ejercicio incluye el **enunciado**, un **ejemplo de entrada** y la **salida esperada**. Se recomienda resolverlos en un Jupyter Notebook y subirlos a tu repositorio de GitHub.

---

## BLOQUE 1 · T1-T2: ALGORITMOS, EPS Y PSEINT

### Ejercicio 251: Algoritmo para lavar ropa
**Enunciado:** Escribe en lenguaje natural los pasos (algoritmo) para lavar una carga de ropa en una lavadora automática. Deben incluir: clasificación de ropa, carga, selección de programa, inicio y despacho. Deben ser precisos, definidos y finitos.
**Entrada:** Cantidad de ropa, tipo de tela dominante (algodón/seda/mezcla).
**Salida:** Lista ordenada de al menos 7 pasos que termina con la ropa lista para secar.

---

### Ejercicio 252: EPS para calcular el área de un trapecio
**Enunciado:** Plantea el modelo Entrada-Proceso-Salida para calcular el área de un trapecio (`area = (base_mayor + base_menor) * altura / 2`). Indica qué datos son entrada, qué operaciones son el proceso y qué resultado es la salida.
**Entrada:** `base_mayor = 10`, `base_menor = 6`, `altura = 4`
**Proceso:** `area = (10 + 6) * 4 / 2`
**Salida:** `El área del trapecio es: 32.0`

---

### Ejercicio 253: Algoritmo para organizar una mochila
**Enunciado:** Diseña el algoritmo paso a paso para organizar una mochila escolar: ordenar libros por materia, colocar materiales grande abajo, pequeños arriba, verificar que todo quepa. Deben ser al menos 8 pasos.
**Entrada:** Lista de objetos con sus dimensiones aproximadas.
**Salida:** Secuencia de pasos ordenados que termina con la mochila organizada.

---

### Ejercicio 254: Pseudocódigo PSeInt: calcular la longitud de una circunferencia
**Enunciado:** Escribe el pseudocódigo en PSeInt que calcule la longitud de una circunferencia (`longitud = 2 * pi * radio`) usando `pi = 3.1416`.
**Entrada:** `radio = 7`
**Salida:** `La longitud de la circunferencia es: 43.9824`

---

### Ejercicio 255: EPS para calcular el volumen de un cilindro
**Enunciado:** Identifica las fases del modelo EPS para calcular el volumen de un cilindro (`volumen = pi * radio² * altura`).
**Entrada:** `radio = 3`, `altura = 10`
**Proceso:** `volumen = 3.1416 * 9 * 10`
**Salida:** `El volumen del cilindro es: 282.744`

---

### Ejercicio 256: Algoritmo para preparar una presentación
**Enunciado:** Escribe el algoritmo (lenguaje natural) para preparar una presentación oral de 10 minutos: investigar tema, hacer guion, preparar diapositivas, ensayar, ajustar tiempos, presentar.
**Entrada:** Tema de la presentación, tiempo disponible.
**Salida:** Lista de pasos que termina con la presentación expuesta.

---

### Ejercicio 257: Pseudocódigo PSeInt: promedio ponderado
**Enunciado:** Escribe el pseudocódigo en PSeInt que calcule el promedio ponderado de 3 calificaciones con pesos diferentes: primera peso 30%, segunda 30%, tercera 40%.
**Entrada:** `cal1 = 8`, `cal2 = 9`, `cal3 = 7`
**Proceso:** `promedio = (8*0.30) + (9*0.30) + (7*0.40)`
**Salida:** `El promedio ponderado es: 7.9`

---

### Ejercicio 258: Algoritmo para tomar una decisión de compra
**Enunciado:** Escribe el algoritmo paso a paso para decidir si comprar un producto: comparar precio con presupuesto, revisar reseñas, verificar disponibilidad, comparar con alternativas. Incluye al menos 6 pasos.
**Entrada:** Precio del producto, presupuesto disponible, reseñas, existencia de alternativas.
**Salida:** Decisión final (comprar/no comprar) con justificación.

---

## BLOQUE 2 · T3-T4: VARIABLES, TIPOS DE DATOS, OPERADORES, ENTRADA/SALIDA

### Ejercicio 259: Calcular el volumen de una esfera
**Enunciado:** Crea un programa que pida el radio de una esfera (float) y calcule su volumen con la fórmula `V = (4/3) * pi * radio³`. Usa `pi = 3.1416` y muestra el resultado con 2 decimales.
**Entrada:** `radio = 5`
**Proceso:** `V = (4/3) * 3.1416 * 125`
**Salida:** `El volumen de la esfera es: 523.60`

---

### Ejercicio 260: Calcular la velocidad final con aceleración constante
**Enunciado:** Crea un programa que pida la velocidad inicial (m/s), la aceleración (m/s²) y el tiempo (s), y calcule la velocidad final con `v_final = v_inicial + aceleracion * tiempo`.
**Entrada:** `v_inicial = 10`, `aceleracion = 2`, `tiempo = 5`
**Salida:** `La velocidad final es: 20.0 m/s`

---

### Ejercicio 261: Calcular el perímetro de un círculo
**Enunciado:** Crea un programa que pida el radio de un círculo y calcule su perímetro (longitud de la circunferencia) con `perimetro = 2 * 3.1416 * radio`. Muestra con 2 decimales.
**Entrada:** `radio = 10`
**Salida:** `El perímetro del círculo es: 62.83`

---

### Ejercicio 262: Calcular el área superficial de un cubo
**Enunciado:** Crea un programa que pida la arista de un cubo y calcule su área superficial total (`6 * arista²`).
**Entrada:** `arista = 4`
**Salida:** `El área superficial del cubo es: 96`

---

### Ejercicio 263: Convertir minutos a horas y minutos
**Enunciado:** Crea un programa que pida una cantidad de minutos (entero) y la convierta a horas y minutos restantes. Por ejemplo, 150 minutos = 2 horas y 30 minutos.
**Entrada:** `150`
**Salida:** `150 minutos = 2 horas y 30 minutos`

---

### Ejercicio 264: Calcular el interés compuesto total
**Enunciado:** Crea un programa que pida un capital inicial, una tasa de interés anual (en porcentaje) y un número de años, y calcule el monto final con interés compuesto: `monto = capital * (1 + tasa/100) ** años`.
**Entrada:** `capital = 1000`, `tasa = 5`, `años = 3`
**Salida:** `El monto final con interés compuesto es: $1157.63`

---

### Ejercicio 265: Calcular la distancia entre dos puntos 2D
**Enunciado:** Crea un programa que pida las coordenadas (x1, y1) y (x2, y2) de dos puntos y calcule la distancia euclidiana: `distancia = sqrt((x2-x1)² + (y2-y1)²)`. Puedes usar `** 0.5` para la raíz cuadrada.
**Entrada:** `x1 = 0`, `y1 = 0`, `x2 = 3`, `y2 = 4`
**Salida:** `La distancia entre los puntos es: 5.0`

---

### Ejercicio 266: Calcular el área de un rombo por diagonales
**Enunciado:** Crea un programa que pida las dos diagonales de un rombo y calcule su área: `area = (diagonal_mayor * diagonal_menor) / 2`.
**Entrada:** `diag_mayor = 10`, `diag_menor = 6`
**Salida:** `El área del rombo es: 30.0`

---

### Ejercicio 267: Calcular la fuerza de atracción gravitacional simple
**Enunciado:** Crea un programa que pida dos masas (en kg) y la distancia entre ellas (en metros), y calcule la fuerza gravitacional usando `F = G * m1 * m2 / d²`, donde `G = 6.674e-11`. Muestra el resultado en notación científica o con muchos decimales.
**Entrada:** `m1 = 1000`, `m2 = 2000`, `d = 5`
**Salida:** `La fuerza gravitacional es: 5.3392e-07 N`

---

### Ejercicio 268: Calcular potencia eléctrica
**Enunciado:** Crea un programa que pida el voltaje (V) y la corriente (I) y calcule la potencia eléctrica con `P = V * I`. Muestra el resultado en vatios.
**Entrada:** `voltaje = 12`, `corriente = 2.5`
**Salida:** `La potencia es: 30.0 vatios`

---

## BLOQUE 3 · T5: ESTRUCTURAS DE DECISIÓN (if, elif, else, operadores lógicos)

### Ejercicio 269: Clasificar un ángulo por su magnitud
**Enunciado:** Crea un programa que pida un ángulo en grados (0 a 360) y clasifique el tipo de ángulo: nulo (0°), agudo (0° < x < 90°), recto (90°), obtuso (90° < x < 180°), llano (180°), o ángulo completo (360°). Usa `if-elif-else`.
**Entrada:** `45`
**Salida:** `Ángulo agudo`

---

### Ejercicio 270: Determinar tipo de triángulo por sus ángulos
**Enunciado:** Crea un programa que pida tres ángulos (suma debe ser 180°) y determine si el triángulo es acutángulo (todos < 90°), rectángulo (uno = 90°) u obtusángulo (uno > 90°).
**Entrada:** `60`, `60`, `60`
**Salida:** `Triángulo acutángulo`

---

### Ejercicio 271: Sistemas de parking por tiempo
**Enunciado:** Un estacionamiento cobra: hasta 1 hora $5, hasta 3 horas $12, más de 3 horas $25 (tarifa máxima del día). Crea un programa que pida las horas (float) y muestre el precio a pagar.
**Entrada:** `2.5`
**Salida:** `Precio a pagar: $12.00`

---

### Ejercicio 272: Calcular el día de la semana de nacimiento (simplificado)
**Enunciado:** Crea un programa que pida un número de día del año (1 a 365) y determine el día de la semana asumiendo que el día 1 es lunes. Muestra el día correspondiente.
**Entrada:** `10`
**Salida:** `El día 10 del año cae en jueves`

---

### Ejercicio 273: Categoría de peso en gimnasio
**Enunciado:** Crea un programa que pida el peso de un atleta (float) y determine su categoría de pesas: flyweight (< 52), bantamweight (52-61), featherweight (61-70), lightweight (70-84), middleweight (84-99), heavyweight (>= 100). Usa `if-elif-else`.
**Entrada:** `75.5`
**Salida:** `Categoría: lightweight`

---

### Ejercicio 274: Determinar temporada del año por mes
**Enunciado:** Crea un programa que pida un número de mes (1-12) y determine la temporada: Primavera (3-5), Verano (6-8), Otoño (9-11), Invierno (12,1,2). Usa `if-elif-else`.
**Entrada:** `9`
**Salida:** `Estación: Otoño`

---

### Ejercicio 275: Promoción de compra con múltiples condiciones
**Enunciado:** Una tienda ofrece: 5% de descuento si se compra más de $100, 10% adicional si se es miembro (sí/no), y 5% extra si se usa tarjeta de la tienda. Crea un programa que pida el monto, el estado de miembro y el uso de tarjeta, y calcule el descuento total y el precio final.
**Entrada:** `monto = 200`, `miembro = si`, `tarjeta_tienda = no`
**Proceso:** 5% por monto + 10% por miembro = 15% total
**Salida:** `Descuento: 15%. Precio final: $170.00`

---

### Ejercicio 276: Calificar el servicio en un restaurante
**Enunciado:** Crea un programa que pida una calificación del servicio del 1 al 5 y determine: 1-2 "Servicio deficiente", 3 "Servicio regular", 4 "Servicio bueno", 5 "Servicio excelente". Además, si la calificación es 4 o 5 y la propina sugerida es del 15% o más, muestra "Propina sugerida: 20%".
**Entrada:** `4`
**Salida:** `Servicio bueno. Propina sugerida: 20%`

---

### Ejercicio 277: Determinar si un número es múltiplo de otro
**Enunciado:** Crea un programa que pida dos números enteros y determine si el primero es múltiplo del segundo usando el operador `%`. Si lo es, muestra el factor de multiplicación.
**Entrada:** `24`, `6`
**Salida:** `24 es múltiplo de 6 (factor: 4)`

---

### Ejercicio 278: Validar si una fecha es válida (simplificado)
**Enunciado:** Crea un programa que pida día, mes y año (números enteros) y valide si la fecha es posible: mes entre 1-12, día entre 1-31 (sin validar días por mes específicos, pero considera que febrero no puede tener más de 29). Muestra "Fecha válida" o "Fecha inválida".
**Entrada:** `29`, `2`, `2024`
**Salida:** `Fecha válida`

---

### Ejercicio 279: Determinar el signo zodiacal básico
**Enunciado:** Crea un programa que pida el día y mes de nacimiento y determine el signo zodiacal (simplificado, solo los 12 signos básicos considerando los límites estándar). Usa comparaciones múltiples con `if-elif`.
**Entrada:** `dia = 15`, `mes = 8`
**Salida:** `Signo zodiacal: Leo`

---

### Ejercicio 280: Sistema de descuento por cantidad y tipo de cliente
**Enunciado:** Una librería aplica: 5% de descuento para estudiantes, 10% para profesores, y un descuento adicional del 5% si se compran más de 5 libros. Crea un programa que pida el tipo de cliente, el número de libros y el precio unitario, y calcule el total a pagar.
**Entrada:** `tipo = estudiante`, `libros = 6`, `precio_unitario = 100`
**Proceso:** 5% estudiantes + 5% cantidad = 10% total. Subtotal: 600. Descuento: 60. Total: 540.
**Salida:** `Total a pagar: $540.00`

---

### Ejercicio 281: Verificar si una persona puede votar en elecciones locales
**Enunciado:** Crea un programa que pida la edad y el país de residencia (string). Una persona puede votar si tiene entre 18 y 70 años y reside en "México". Considera también que entre 70 y 75 puede votar si lo desea (preguntar con input). Usa decisiones anidadas.
**Entrada:** `edad = 25`, `pais = Mexico`
**Salida:** `Eres elegible para votar`

---

### Ejercicio 282: Sistema de puntuación para un juego
**Enunciado:** En un juego, los jugadores ganan insignias según su puntuación: Bronce (100-299), Plata (300-599), Oro (600-899), Platino (900-1199), Diamante (1200+). Crea un programa que pida la puntuación y muestre la insignia corresponding.
**Entrada:** `750`
**Salida:** `Insignia: Oro`

---

### Ejercicio 283: Clasificar nivel de azúcar en sangre
**Enunciado:** Crea un programa que pida el nivel de glucosa en sangre (mg/dL) y clasifique: < 70 "Hipoglucemia", 70-99 "Normal", 100-125 "Pre-diabetes", >= 126 "Diabetes". Usa `if-elif-else`.
**Entrada:** `110`
**Salida:** `Nivel: Pre-diabetes`

---

## BLOQUE 4 · T6: CICLO WHILE — CONTADORES, ACUMULADORES, BREAK, CONTINUE

### Ejercicio 284: Validador de edad con reintento
**Enunciado:** Crea un programa que pida la edad del usuario repetidamente mientras la edad ingresada sea negativa o mayor de 120. Cuando sea válida, muestra "Edad registrada: X años".
**Entrada:** `-5`, `150`, `25`
**Salida:** `Edad registrada: 25 años`

---

### Ejercicio 285: Contar vocales en una frase hasta espacio
**Enunciado:** Crea un programa que pida caracteres uno por uno dentro de un `while True`; cuenta cuántas vocales (a, e, i, o, u) se han ingresado hasta que el usuario escriba un espacio o la letra 'q' para salir. Muestra el contador al final.
**Entrada:** `a`, `b`, `e`, `i`, ` ` (espacio)
**Salida:** `Vocales encontradas: 3`

---

### Ejercicio 286: Suma de números positivos con centinela -99
**Enunciado:** Crea un programa que sume números ingresados por el usuario y se detenga cuando el usuario ingrese `-99` (que no debe sumarse). Muestra la suma total y cuántos números se sumaron.
**Entrada:** `10`, `20`, `30`, `-99`
**Salida:** `Suma total: 60. Cantidad de números: 3`

---

### Ejercicio 287: Búsqueda del número más cercano a 100
**Enunciado:** Crea un programa que capture números continuamente y, en cada iteración, compare con el número "más cercano a 100" visto hasta el momento (el que tenga menor diferencia absoluta con 100). Al escribir `-1`, muestra el número más cercano y su diferencia con 100.
**Entrada:** `80`, `95`, `110`, `90`, `-1`
**Salida:** `Número más cercano a 100: 95 (diferencia: 5)`

---

### Ejercicio 288: Contador de intentos de login fallidos
**Enunciado:** Simula un sistema de login donde la contraseña correcta es "python123". El usuario tiene máximo 3 intentos; si falla los 3, el programa muestra "Cuenta bloqueada" y termina. Si acierta, muestra "Acceso concedido" con el número de intentos usados.
**Entrada:** `1234`, `python321`, `python123`
**Salida:** `Acceso concedido en 3 intentos`

---

### Ejercicio 289: Productoria con while
**Enunciado:** Crea un programa que pida un número entero positivo N y calcule la productoria de los números del 1 al N (similar al factorial) usando `while`.
**Entrada:** `4`
**Salida:** `La productoria de 1 a 4 es: 24`

---

### Ejercicio 290: Simulador de ascensor
**Enunciado:** Un ascensor sube pisos cada segundo. Inicia en el piso 0 y sube 1 piso por segundo. Con un `while`, muestra el piso actual cada iteración. Si el usuario presiona 'p' en vez de un número, el ascensor se detiene y muestra el piso final.
**Entrada:** `s` (subir), `s`, `p` (parar)
**Salida:** `Piso 0 -> Piso 1 -> Piso 2. Ascensor detenido en piso 2.`

---

### Ejercicio 291: Promedio de números hasta que el promedio sea >= 10
**Enunciado:** Crea un programa que capture números uno por uno y calcula el promedio en cada paso. El ciclo continúa hasta que el promedio alcance o supere 10. Muestra el promedio final y cuántos números se capturaron.
**Entrada:** `5`, `12`, `15`, `20`
**Proceso:** promedios secuenciales: 5, 8.5, 10.66...
**Salida:** `Promedio final: 13.0. Números capturados: 4`

---

### Ejercicio 292: Contador de palabras hasta punto
**Enunciado:** Crea un programa que capture palabras una por una con `input()` dentro de un `while True`. Cuenta las palabras hasta que el usuario escriba un punto "." (que no cuenta como palabra). Muestra el total.
**Entrada:** `Hola`, `mundo`, `.`
**Salida:** `Palabras capturadas: 2`

---

### Ejercicio 293: Validador de números primos con while
**Enunciado:** Crea un programa que pida números repetidamente y, para cada uno, determina si es primo usando un ciclo `while` interno que revisa divisores desde 2 hasta n-1. El programa termina cuando el usuario escribe "salir".
**Entrada:** `7`, `10`, `salir`
**Salida:** `7 es primo. 10 no es primo.`

---

### Ejercicio 294: Contador de números ascendentes
**Enunciado:** Crea un programa que capture números uno por uno. Cuenta cuántas veces un número es mayor que el anterior (secuencia ascendente). Si el número es menor o igual, reinicia el contador de ascendencia. Termina cuando el usuario escribe "fin". Muestra el conteo máximo de ascendencia consecutiva.
**Entrada:** `3`, `5`, `8`, `6`, `9`, `10`, `fin`
**Proceso:** secuencia: 3->5 (asc), 5->8 (asc), 8->6 (no asc, reinicia), 6->9 (asc), 9->10 (asc). Máximo: 3 ascendientes consecutivos.
**Salida:** `Máximo de ascendientes consecutivos: 3`

---

### Ejercicio 295: Adivina el número con rango dinámico
**Enunciado:** El programa define un número secreto entre 1 y 100. El jugador adivina; si su número es menor, se le dice "Muy bajo" y se ajusta el límite inferior; si es mayor, "Muy alto" y se ajusta el límite superior. El juego termina al acertar, mostrando cuántos intentos tomó.
**Entrada:** `50`, `75`, `85`, `80`
**Salida:** `¡Correcto! Lo lograste en 4 intentos`

---

### Ejercicio 296: Suma de cubos con while
**Enunciado:** Crea un programa que pida un número N y calcule la suma de los cubos de los números del 1 al N (`1³ + 2³ + ... + N³`) usando `while`.
**Entrada:** `3`
**Proceso:** `1 + 8 + 27 = 36`
**Salida:** `La suma de los cubos del 1 al 3 es: 36`

---

### Ejercicio 297: Secuencia de Collatz (conjetura)
**Enunciado:** La conjetura de Collatz dice: toma un número positivo. Si es par, divídelo entre 2; si es impar, multiplícalo por 3 y súmale 1. Repite hasta llegar a 1. Crea un programa que pida un número y muestre la secuencia completa hasta llegar a 1, con un `while`.
**Entrada:** `10`
**Proceso:** 10 -> 5 -> 16 -> 8 -> 4 -> 2 -> 1
**Salida:** `Secuencia Collatz: 10, 5, 16, 8, 4, 2, 1`

---

### Ejercicio 298: Mayor y menor de una serie con while
**Enunciado:** Crea un programa que capture números continuamente; en cada vuelta muestra el mayor y el menor de los números capturados hasta ese momento. Termina cuando el usuario escribe "fin". No use listas, solo variables de seguimiento.
**Entrada:** `10`, `5`, `15`, `fin`
**Salida:** Después de cada entrada: `Mayor: X, Menor: Y`
**Ejemplo: `Mayor: 10, Menor: 10` -> `Mayor: 10, Menor: 5` -> `Mayor: 15, Menor: 5`**

---

### Ejercicio 299: Contador de dígitos pares e impares
**Enunciado:** Crea un programa que pida un número entero positivo y cuente cuántos dígitos pares e impares tiene usando `while` y operaciones de módulo y división entera. Muestra ambos conteos.
**Entrada:** `2024`
**Proceso:** dígitos: 2 (par), 0 (par), 2 (par), 4 (par)
**Salida:** `Dígitos pares: 4, Dígitos impares: 0`

---

## BLOQUE 5 · T7: DEBUGGING CON PDB

### Ejercicio 300: Depurar un ciclo while infinito
**Enunciado:** Este código debería imprimir los números del 1 al 5 pero entra en ciclo infinito:
```python
i = 1
while i <= 5:
    print(i)
```
¿Qué falta? Inserta el punto de interrupción correcto con `breakpoint()` y corrige el código para que funcione.
**Entrada:** Ninguna (ejercicio de análisis y depuración).
**Salida:** `Falta "i = i + 1" dentro del ciclo. Con breakpoint() entre las líneas se observa que i nunca cambia de valor. Corrección: agregar i = i + 1 antes o después del print.`

---

### Ejercicio 301: Depurar error de división por cero en cálculo de promedio
**Enunciado:** Este código falla cuando no se ingresan calificaciones válidas:
```python
suma = 0
contador = 0
# ... código de captura que no incrementa contador ...
promedio = suma / contador
```
¿Qué tipo de error se produce? ¿Cómo te ayuda `breakpoint()` a detectarlo? Propone una corrección con un `if` que verifique que `contador > 0` antes de dividir.
**Entrada:** Sin calificaciones válidas.
**Salida:** `ZeroDivisionError. breakpoint() detiene la ejecución antes de la línea problemática, permitiendo inspeccionar que contador = 0. Corrección: if contador > 0: promedio = suma / contador else: print("No hay datos")`

---

### Ejercicio 302: Depurar un acumulador mal inicializado
**Enunciado:** Este código intenta sumar los números del 1 al 10 pero imprime un resultado incorrecto:
```python
for i in range(1, 11):
    total = 0
    total = total + i
print(total)
```
¿Por qué el resultado es incorrecto? Usa `breakpoint()` para inspeccionar el valor de `total` en cada iteración y explica el error.
**Entrada:** Ninguna.
**Salida:** `El total se reinicia a 0 en cada iteración del for. Debe inicializarse total = 0 ANTES del ciclo. Con breakpoint() se observa que total vuelve a 0 en cada vuelta. Corrección: inicializar total antes del for.`

---

### Ejercicio 303: Depurar conversión de tipos con pdb
**Enunciado:** Este código a veces falla:
```python
edad = input("Edad: ")
proximo_anio = edad + 1
print(f"El próximo año tendrás {proximo_anio} años")
```
¿Qué tipo de error se produce si el usuario escribe "veinte"? ¿Cuál es la solución? Demuestra cómo usar `pdb.set_trace()` para inspeccionar el tipo de `edad` antes de la operación problemática.
**Entrada:** `veinte`
**Salida:** `TypeError: no se puede sumar str + int. La solución es convertir edad = int(edad) después de input(). Con pdb.set_trace() antes de la suma se puede ver que type(edad) es str.`

---

### Ejercicio 304: Depurar lógica de descuento
**Enunciado:** Este código aplica un descuento pero el resultado es incorrecto:
```python
precio = 200
descuento = 0.10
precio_final = precio - descuento
print(f"Precio final: ${precio_final}")
```
¿Cuál es el error de lógica? ¿Qué valor imprime? Corrija usando breakpoint() para verificar el valor de `descuento`.
**Entrada:** Ninguna.
**Salida:** `El error es que se resta 0.10 en vez de 10% de 200 (que es 20). Imprime $199.90 en vez de $180.00. Corrección: precio_final = precio - (precio * descuento). Con breakpoint() se puede inspeccionar descuento = 0.10 y ver que no representa el porcentaje aplicado al precio.`

---

### Ejercicio 305: Depurar ciclo for con rango incorrecto
**Enunciado:** Este código debe imprimir del 1 al 10 pero solo imprime hasta el 9:
```python
for i in range(1, 10):
    print(i)
```
¿Por qué? ¿Cómo se corrige el rango? Usa `breakpoint()` para ver los valores que toma `i`.
**Entrada:** Ninguna.
**Salida:** `range(1, 10) genera del 1 al 9 (el límite superior no se incluye). Para llegar al 10 se necesita range(1, 11). Con breakpoint() se puede observar que i nunca llega a 10.`

---

### Ejercicio 306: Depurar función con return faltante
**Enunciado:** Esta función debería retornar el cuadrado de un número pero no lo hace:
```python
def cuadrado(n):
    n * n
    print("Calculado")
resultado = cuadrado(5)
print(resultado)
```
¿Qué valor imprime `resultado`? ¿Por qué? Inserta `breakpoint()` dentro de la función y explica qué falta.
**Entrada:** Ninguna.
**Salida:** `resultado es None porque la función no tiene return. El cálculo n * n se realiza pero su valor se pierde. Debe ser return n * n. Con breakpoint() dentro de la función se puede ver que el valor de retorno es None.`

---

### Ejercicio 307: Depurar variable fuera de scope
**Enunciado:** Este código da error al intentar usar una variable fuera del ciclo:
```python
for i in range(5):
    suma = suma + i
print(suma)
```
¿Qué error se produce? ¿Por qué? Corrija inicializando la variable antes del ciclo.
**Entrada:** Ninguna.
**Salida:** `UnboundLocalError o NameError: 'suma' no está definida. La variable suma debe inicializarse antes del ciclo con suma = 0. Con breakpoint() se puede ver que en la primera iteración suma no existe todavía.`

---

## BLOQUE 6 · T8: CICLO FOR — RANGE, SUMAS, ACUMULADORES, PATRONES

### Ejercicio 308: Tabla de potencias
**Enunciado:** Crea un programa que pida un número base y muestre sus potencias desde la 0 hasta la 10 (base⁰, base¹, ..., base¹⁰) usando un `for` con `range(11)`.
**Entrada:** `2`
**Salida:** `2^0=1, 2^1=2, 2^2=4, 2^3=8, 2^4=16, 2^5=32, 2^6=64, 2^7=128, 2^8=256, 2^9=512, 2^10=1024`

---

### Ejercicio 309: Suma de múltiplos de 3 y 5
**Enunciado:** Crea un programa que calcule la suma de todos los números del 1 al 100 que son múltiplos de 3 o de 5 (o de ambos) usando un `for` y el operador `%`.
**Entrada:** Ninguna (rango fijo 1-100).
**Proceso:** Múltiplos de 3: 3,6,9,...,99. Múltiplos de 5: 5,10,...,100. Sin duplicados.
**Salida:** `La suma de múltiplos de 3 o 5 del 1 al 100 es: 2418`

---

### Ejercicio 310: Secuencia de números primos hasta N
**Enunciado:** Crea un programa que pida un número N e imprima todos los números primos del 1 al N usando un `for` anidado para verificar primalidad. Muestra cada primo en una línea.
**Entrada:** `20`
**Salida:** `2, 3, 5, 7, 11, 13, 17, 19`

---

### Ejercicio 311: Promedio de los primeros N términos de la serie armónica
**Enunciado:** Crea un programa que pida N e imprima el promedio (no la suma) de los primeros N términos de la serie armónica: `1, 1/2, 1/3, ..., 1/N`.
**Entrada:** `4`
**Proceso:** términos: 1, 0.5, 0.333..., 0.25. Suma: 2.0833... Promedio: 2.0833/4 = 0.5208...
**Salida:** `El promedio de los primeros 4 términos de la serie armónica es: 0.52`

---

### Ejercicio 312: Contador de números perfectos hasta N
**Enunciado:** Un número perfecto es igual a la suma de sus divisores propios (sin contarse a sí mismo). Crea un programa que pida N e imprima todos los números perfectos del 1 al N usando un `for` anidado.
**Entrada:** `30`
**Proceso:** El 6 es perfecto (1+2+3=6), el 28 es perfecto (1+2+4+7+14=28).
**Salida:** `Números perfectos hasta 30: 6, 28`

---

### Ejercicio 313: Serie de potencias alternadas
**Enunciado:** Crea un programa que pida un número N e imprima la serie: `1 - 1/2 + 1/3 - 1/4 + ... ± 1/N`. Usa un `for` y decide el signo según si el índice es par o impar.
**Entrada:** `5`
**Proceso:** `1 - 0.5 + 0.333... - 0.25 + 0.2 = 0.7833...`
**Salida:** `Resultado de la serie alternada: 0.78`

---

### Ejercicio 314: Triángulo de Fibonacci en patrón
**Enunciado:** Crea un programa que pida un número de filas y dibuje un triángulo donde cada fila i muestra los primeros i términos de la sucesión de Fibonacci. Usa ciclos `for` anidados.
**Entrada:** `5`
**Proceso:** 
Fila 1: 0
Fila 2: 0, 1
Fila 3: 0, 1, 1
Fila 4: 0, 1, 1, 2
Fila 5: 0, 1, 1, 2, 3
**Salida:**
```
0
0 1
0 1 1
0 1 1 2
0 1 1 2 3
```

---

### Ejercicio 315: Tabla de conversión de grados a radianes
**Enunciado:** Crea un programa que imprima una tabla de conversión de grados a radianes para los ángulos 0°, 30°, 60°, ..., 360° usando la fórmula `radianes = grados * pi / 180`. Usa `for` con `range(0, 361, 30)`.
**Entrada:** Ninguna.
**Salida:**
```
0° = 0.0000 rad
30° = 0.5236 rad
60° = 1.0472 rad
...
360° = 6.2832 rad
```

---

### Ejercicio 316: Contador de términos en una serie geométrica
**Enunciado:** Una serie geométrica comienza con 1 y cada término siguiente se multiplica por una razón r. Crea un programa que pida la razón r y un límite L, y muestre cuántos términos de la serie (1, r, r², ...) se necesitan para que el término supere L por primera vez. Usa `for` con `range` suficientemente grande.
**Entrada:** `r = 2`, `L = 100`
**Proceso:** términos: 1, 2, 4, 8, 16, 32, 64, 128 (supera 100 en el término 7)
**Salida:** `Se necesitan 8 términos para superar 100 (el término 128 es el primero que lo hace)`

---

### Ejercicio 317: Cálculo de e aproximado con serie de Taylor
**Enunciado:** El número e se puede aproximar con la serie: `e = 1 + 1/1! + 1/2! + 1/3! + ... + 1/n!`. Crea un programa que pida n y calcule la aproximación de e usando un `for` que compute cada factorial y lo sume.
**Entrada:** `10`
**Proceso:** Suma de 1 + 1 + 0.5 + 0.1667 + ...
**Salida:** `Aproximación de e con 10 términos: 2.7183`

---

### Ejercicio 318: Pirámide de números crecientes
**Enunciado:** Crea un programa que pida un número de filas y dibuje una pirámide donde la fila i contiene i copias del número i, separadas por espacios. Usa `for` anidados.
**Entrada:** `4`
**Salida:**
```
1
2 2
3 3 3
4 4 4 4
```

---

### Ejercicio 319: Suma de los cuadrados de los primeros N números
**Enunciado:** Crea un programa que pida N y calcule la suma de los cuadrados de los números del 1 al N (`1² + 2² + ... + N²`) usando `for`.
**Entrada:** `5`
**Proceso:** `1 + 4 + 9 + 16 + 25 = 55`
**Salida:** `La suma de los cuadrados del 1 al 5 es: 55`

---

### Ejercicio 320: Contador de números capicúas en un rango
**Enunciado:** Crea un programa que pida dos números a y b (a <= b) y cuente cuántos números capicúas (se leen igual de izquierda a derecha y de derecha a izquierda) hay en ese rango, usando `for` y conversión a string para verificar capicúa.
**Entrada:** `10`, `50`
**Proceso:** Capicúas entre 10 y 50: 11, 22, 33, 44
**Salida:** `Hay 4 números capicúas entre 10 y 50`

---

### Ejercicio 321: Tabla de valores de una función cuadrática
**Enunciado:** Crea un programa que pida los coeficientes a, b, c de una función cuadrática `f(x) = ax² + bx + c` y muestre una tabla de valores de x de -5 a 5 (paso 1) con su valor f(x) calculado. Usa `for` con `range(-5, 6)`.
**Entrada:** `a = 1`, `b = 0`, `c = 0`
**Salida:** Tabla: `x=-5 -> f(x)=25`, `x=-4 -> f(x)=16`, ..., `x=5 -> f(x)=25`

---

### Ejercicio 322: Descomposición de un número en factores primos
**Enunciado:** Crea un programa que pida un número entero positivo N y muestre su descomposición en factores primos (por ejemplo, 12 = 2×2×3). Usa un `for` que pruebe divisores desde 2 en adelante e imprime cada factor encontrado.
**Entrada:** `12`
**Proceso:** 12 ÷ 2 = 6, 6 ÷ 2 = 3, 3 ÷ 3 = 1. Factores: 2, 2, 3.
**Salida:** `12 = 2 × 2 × 3`

---

### Ejercicio 323: Serie de aproximación de π (Leibniz)
**Enunciado:** La serie de Leibniz para aproximar π es: `π/4 = 1 - 1/3 + 1/5 - 1/7 + 1/9 - ...`. Crea un programa que pida n (número de términos) y calcule la aproximación de π usando un `for`.
**Entrada:** `100000`
**Proceso:** Suma de 1 - 1/3 + 1/5 - 1/7 + ... (100000 términos)
**Salida:** `Aproximación de π con 100000 términos: 3.1416` (aprox.)

---

### Ejercicio 324: Contador de términos entre dos valores
**Enunciado:** Crea un programa que pida un número N y dos valores vmin y vmax, y cuente con un `for` cuántos números del 1 al N están entre vmin y vmax (inclusive).
**Entrada:** `N = 20`, `vmin = 5`, `vmax = 15`
**Salida:** `Hay 11 números entre 5 y 15 en el rango 1-20`

---

## BLOQUE 7 · T9: LISTAS

### Ejercicio 325: Inicializar y recorrer una lista de temperaturas
**Enunciado:** Crea una lista `temperaturas = [22.5, 19.0, 25.3, 18.7, 21.0]` y recórrela con un `for` para imprimir cada temperatura seguida de "°C".
**Entrada:** Ninguna (lista fija).
**Salida:**
```
22.5°C
19.0°C
25.3°C
18.7°C
21.0°C
```

---

### Ejercicio 326: Insertar un elemento en posición específica
**Enunciado:** Dada la lista `numeros = [10, 20, 30, 40]`, inserta el valor `15` en la posición índice 1 usando `insert()` y muestra la lista resultante.
**Entrada:** Ninguna (valores fijos).
**Salida:** `[10, 15, 20, 30, 40]`

---

### Ejercicio 327: Eliminar el último elemento y mostrar
**Enunciado:** Dada la lista `colores = ["rojo", "verde", "azul", "amarillo"]`, elimina el último elemento con `pop()` y muestra tanto el elemento eliminado como la lista resultante.
**Entrada:** Ninguna (valores fijos).
**Salida:** `Elemento eliminado: amarillo. Lista resultante: ['rojo', 'verde', 'azul']`

---

### Ejercicio 328: Contar elementos repetidos en una lista
**Enunciado:** Dada la lista `votos = ["Ana", "Luis", "Ana", "Mía", "Ana", "Luis"]`, cuenta cuántas veces aparece cada nombre usando un ciclo `for` y un diccionario auxiliar. Muestra el conteo de cada uno.
**Entrada:** Ninguna (valores fijos).
**Salida:** `Ana: 3, Luis: 2, Mía: 1`

---

### Ejercicio 329: Filtrar números positivos de una lista
**Enunciado:** Dada la lista `numeros = [5, -3, 8, -1, 0, 12, -7, 4]`, crea una nueva lista que contenga únicamente los números positivos (mayores a 0) usando un ciclo `for` y `append()`. Muestra la lista filtrada.
**Entrada:** Ninguna (valores fijos).
**Salida:** `[5, 8, 12, 4]`

---

### Ejercicio 330: Sumar elementos de dos listas posición por posición
**Enunciado:** Dadas las listas `a = [1, 2, 3]` y `b = [4, 5, 6]`, crea una nueva lista `c` donde cada elemento es la suma de los elementos en la misma posición de `a` y `b` (c[0]=1+4, c[1]=2+5, etc.).
**Entrada:** Ninguna (valores fijos).
**Salida:** `[5, 7, 9]`

---

### Ejercicio 331: Invertir una lista sin slicing
**Enunciado:** Dada la lista `original = [1, 2, 3, 4, 5]`, crea una nueva lista `invertida` que contenga los elementos en orden inverso, recorriendo la lista original desde el último índice hacia el primero con un `for` usando `range(len(original)-1, -1, -1)`.
**Entrada:** Ninguna (valores fijos).
**Salida:** `[5, 4, 3, 2, 1]`

---

### Ejercicio 332: Encontrar el segundo mayor de una lista
**Enunciado:** Dada la lista `numeros = [15, 3, 9, 7, 20, 11]`, encuentra el segundo mayor valor sin usar `sort()` ni `max()`. Usa dos variables: `mayor` y `segundo_mayor`, recorriendo la lista una sola vez con `for`.
**Entrada:** Ninguna (valores fijos).
**Salida:** `El segundo mayor es: 15`

---

### Ejercicio 333: Combinar dos listas alternando elementos
**Enunciado:** Dadas las listas `lista1 = [1, 3, 5]` y `lista2 = [2, 4, 6]`, crea una nueva lista que combine los elementos alternando: primero de lista1, luego de lista2, luego de lista1, etc.
**Entrada:** Ninguna (valores fijos).
**Salida:** `[1, 2, 3, 4, 5, 6]`

---

### Ejercicio 334: Promedio móvil de una lista
**Enunciado:** Dada la lista `ventas = [100, 150, 200, 250, 300]`, calcula el promedio móvil de 3 elementos: para cada posición i (desde 2 hasta el final), calcula el promedio de ventas[i-2], ventas[i-1], ventas[i]. Muestra cada promedio en una línea.
**Entrada:** Ninguna (valores fijos).
**Salida:** `Promedio [100,150,200]: 150.0`, `Promedio [150,200,250]: 200.0`, `Promedio [200,250,300]: 250.0`

---

### Ejercicio 335: Rotar una lista hacia la izquierda
**Enunciado:** Dada la lista `numeros = [1, 2, 3, 4, 5]`, rota la lista 2 posiciones hacia la izquierda (el primer elemento pasa al final, repetidamente). Muestra la lista resultante.
**Entrada:** Ninguna (valores fijos).
**Proceso:** Rotación 1: [2,3,4,5,1]. Rotación 2: [3,4,5,1,2].
**Salida:** `[3, 4, 5, 1, 2]`

---

## BLOQUE 8 · T10: LISTAS DE LISTAS (MATRICES)

### Ejercicio 336: Matriz de un tablero de ajedrez (1 y 0)
**Enunciado:** Crea una matriz 8x8 que represente un tablero de ajedrez usando 1 para casillas negras y 0 para casillas blancas, donde la casilla (0,0) es blanca (0). El patrón alterna. Muestra la matriz con dos ciclos `for` anidados.
**Entrada:** Ninguna.
**Salida:**
```
0 1 0 1 0 1 0 1
1 0 1 0 1 0 1 0
0 1 0 1 0 1 0 1
...
```

---

### Ejercicio 337: Sumar dos matrices 2x2
**Enunciado:** Dadas las matrices `A = [[1, 2], [3, 4]]` y `B = [[5, 6], [7, 8]]`, crea una matriz `C` que sea la suma de A y B (C[i][j] = A[i][j] + B[i][j]).
**Entrada:** Ninguna (valores fijos).
**Salida:** `[[6, 8], [10, 12]]`

---

### Ejercicio 338: Transponer una matriz 3x3
**Enunciado:** Dada la matriz `M = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]`, crea una nueva matriz `T` que sea la transpuesta de M (las filas se convierten en columnas). Muestra ambas matrices.
**Entrada:** Ninguna (valores fijos).
**Salida:** 
```
Matriz original:
1 2 3
4 5 6
7 8 9
Matriz transpuesta:
1 4 7
2 5 8
3 6 9
```

---

### Ejercicio 339: Contar elementos pares en una matriz
**Enunciado:** Dada la matriz `[[3, 8, 5], [2, 7, 10], [6, 1, 9]]`, recórrela con ciclos anidados y cuenta cuántos elementos son pares (divisible entre 2).
**Entrada:** Ninguna (valores fijos).
**Proceso:** Pares: 8, 2, 10, 6 → total 4.
**Salida:** `La matriz tiene 4 elementos pares`

---

### Ejercicio 340: Buscar un valor en una matriz
**Enunciado:** Dada la matriz `[[10, 20, 30], [40, 50, 60], [70, 80, 90]]`, pide un número al usuario y busca si existe en la matriz recorriéndola con ciclos anidados. Si lo encuentra, muestra la posición (fila, columna). Si no, muestra "No encontrado".
**Entrada:** `50`
**Salida:** `50 encontrado en fila 1, columna 1`

---

### Ejercicio 341: Sumar los elementos de la diagonal secundaria
**Enunciado:** Dada la matriz `[[1, 2, 3], [4, 5, 6], [7, 8, 9]]`, calcula la suma de los elementos de la diagonal secundaria (donde fila + columna = tamaño - 1, es decir, posición [0][2], [1][1], [2][0]).
**Entrada:** Ninguna (valores fijos).
**Proceso:** 3 + 5 + 7 = 15.
**Salida:** `La suma de la diagonal secundaria es: 15`

---

### Ejercicio 342: Matriz de multiplicación escalar
**Enunciado:** Dada la matriz `M = [[2, 4, 6], [8, 10, 12]]`, multiplica todos sus elementos por un escalar k = 3 y muestra la matriz resultante.
**Entrada:** Ninguna (valores fijos).
**Salida:** `[[6, 12, 18], [24, 30, 36]]`

---

### Ejercicio 343: Identificar filas que contienen un valor específico
**Enunciado:** Dada la matriz `[[1, 5, 3], [7, 5, 2], [4, 6, 5]]`, identifica y muestra los índices de las filas que contienen el número 5 al menos una vez.
**Entrada:** Ninguna (valores fijos).
**Salida:** `Las filas que contienen 5 son: 0, 1, 2`

---

## BLOQUE 9 · T11: FUNCIONES QUE NO REGRESAN VALOR

### Ejercicio 344: Procedimiento que imprime un rectángulo de asteriscos
**Enunciado:** Define una función `dibujar_rectangulo(alto, ancho)` que no regrese valor e imprima un rectángulo de asteriscos con el alto y ancho dados usando ciclos `for` anidados.
**Entrada:** `alto = 3`, `ancho = 5`
**Salida:**
```
*****
*****
*****
```

---

### Ejercicio 345: Procedimiento que imprime la secuencia de Collatz
**Enunciado:** Define una función `collatz(n)` que no regrese valor e imprima la secuencia de Collatz partiendo desde n hasta llegar a 1, usando un `while`.
**Entrada:** `n = 10`
**Salida:** `10 -> 5 -> 16 -> 8 -> 4 -> 2 -> 1`

---

### Ejercicio 346: Procedimiento que registra y muestra ventas
**Enunciado:** Define una función `registrar_ventas(lista)` que no regrese valor, pida al usuario montos de ventas continuamente (con `input()`), los agregue a la lista con `append()`, y termine cuando el usuario escriba "fin". Al final, imprime la lista completa y el total de ventas.
**Entrada:** `100`, `200`, `fin`
**Salida:** `Ventas: [100, 200]. Total: $300`

---

### Ejercicio 347: Procedimiento que imprime un menú de opciones
**Enunciado:** Define una función `mostrar_menu(opciones)` que no regrese valor, reciba una lista de opciones (strings) y las imprima numeradas (1. Opción 1, 2. Opción 2, ...).
**Entrada:** `opciones = ["Sumar", "Restar", "Salir"]`
**Salida:**
```
1. Sumar
2. Restar
3. Salir
```

---

### Ejercicio 348: Procedimiento que imprime una tabla formateada
**Enunciado:** Define una función `imprimir_tabla(lista1, lista2)` que no regrese valor y reciba dos listas del mismo tamaño. Imprima una tabla con encabezados "Índice | Valor1 | Valor2" y cada fila con los valores correspondientes.
**Entrada:** `lista1 = [1, 2, 3]`, `lista2 = [10, 20, 30]`
**Salida:**
```
Índice | Valor1 | Valor2
0      | 1      | 10
1      | 2      | 20
2      | 3      | 30
```

---

### Ejercicio 349: Procedimiento que valida y muestra datos
**Enunciado:** Define una función `procesar_datos(lista_numeros)` que no regrese valor, reciba una lista de números, imprima cuántos son positivos, cuántos negativos y cuántos cero, y el promedio de los positivos.
**Entrada:** `lista_numeros = [5, -3, 0, 8, -1, 12]`
**Salida:** `Positivos: 3, Negativos: 2, Ceros: 1. Promedio de positivos: 8.33`

---

### Ejercicio 350: Procedimiento que recorre una matriz e imprime suma por fila
**Enunciado:** Define una función `suma_filas(matriz)` que no regrese valor, recorra una matriz (lista de listas) y para cada fila imprima "Fila X: suma = Y".
**Entrada:** `matriz = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]`
**Salida:**
```
Fila 0: suma = 6
Fila 1: suma = 15
Fila 2: suma = 24
```

---

## BLOQUE 10 · T12: FUNCIONES QUE REGRESAN VALOR

### Ejercicio 351: Función que retorna el máximo de una lista
**Enunciado:** Define una función `maximo_lista(lista)` que regrese el valor máximo de una lista de números, recorriéndola con un `for` (sin usar `max()`).
**Entrada:** `[7, 3, 9, 2, 15, 8]`
**Salida:** `El máximo es: 15`

---

### Ejercicio 352: Función que retorna si una lista está ordenada
**Enunciado:** Define una función `esta_ordenada(lista)` que regrese `True` si los elementos de la lista están en orden ascendente (cada elemento <= siguiente) y `False` en caso contrario.
**Entrada:** `[1, 2, 3, 5, 8]`
**Salida:** `True`

---

### Ejercicio 353: Función que retorna la media y mediana de una lista
**Enunciado:** Define una función `media_y_mediana(lista)` que regrese una tupla `(media, mediana)` calculada de una lista de números. La media es el promedio; la mediana es el valor central (o el promedio de los dos centrales si la lista tiene longitud par).
**Entrada:** `[1, 3, 5, 7, 9]`
**Proceso:** media = 25/5 = 5.0; mediana = 5 (el elemento central).
**Salida:** `(5.0, 5)`

---

### Ejercicio 354: Función que retorna el factorial recursivo
**Enunciado:** Define una función `factorial_recursivo(n)` que regrese el factorial de n usando recursividad (si n == 0, regresa 1; sino, regresa n * factorial_recursivo(n-1)).
**Entrada:** `5`
**Salida:** `El factorial de 5 es: 120`

---

### Ejercicio 355: Función que retorna una lista de primos hasta N
**Enunciado:** Define una función `primos_hasta(n)` que regrese una lista con todos los números primos del 1 al n. Usa un ciclo `for` y una función auxiliar (o lógica interna) para verificar primalidad.
**Entrada:** `20`
**Salida:** `[2, 3, 5, 7, 11, 13, 17, 19]`

---

### Ejercicio 356: Función que retorna el MCD (máximo común divisor)
**Enunciado:** Define una función `mcd(a, b)` que regrese el máximo común divisor de a y b usando el algoritmo de Euclides (mientras b != 0: a, b = b, a % b; al final regresa a).
**Entrada:** `a = 48`, `b = 18`
**Proceso:** 48 % 18 = 12, 18 % 12 = 6, 12 % 6 = 0 → MCD = 6.
**Salida:** `El MCD de 48 y 18 es: 6`

---

### Ejercicio 357: Función que retorna el inverso de un número entero
**Enunciado:** Define una función `invertir_numero(n)` que regrese el número entero con los dígitos en orden inverso (por ejemplo, invertir_numero(1234) devuelve 4321). Usa operaciones de módulo y división entera dentro de un `while`.
**Entrada:** `1234`
**Salida:** `El número invertido es: 4321`

---

### Ejercicio 358: Función que retorna el período de una secuencia
**Enunciado:** Define una función `periodo_collatz(n)` que regrese la cantidad de pasos que la secuencia de Collatz (ver Ejercicio 297) toma para llegar a 1, partiendo desde n.
**Entrada:** `10`
**Proceso:** 10->5->16->8->4->2->1 = 6 pasos.
**Salida:** `El período de Collatz de 10 es: 6 pasos`

---

## BLOQUE 11 · T13: TUPLAS

### Ejercicio 359: Desempaquetado de una tupla de longitud variable
**Enunciado:** Dada la tupla `coordenadas = (10, 20, 30, 40)`, desempaqueta los dos primeros valores en `x` y `y`, y el resto en una lista `resto` usando la sintaxis `x, y, *resto = coordenadas`. Imprime cada variable.
**Entrada:** `coordenadas = (10, 20, 30, 40)`
**Salida:** `x = 10, y = 20, resto = [30, 40]`

---

### Ejercicio 360: Tupla de conteo de frecuencias
**Enunciado:** Dada la tupla `datos = (5, 3, 8, 5, 2, 8, 5, 3)`, cuenta cuántas veces aparece cada número usando un diccionario auxiliar y al final convierte el diccionario a una tupla de tuplas `(numero, frecuencia)` ordenada por el número.
**Entrada:** Ninguna (valores fijos).
**Salida:** `((2, 1), (3, 2), (5, 3), (8, 2))`

---

### Ejercicio 361: Concatenar tuplas de nombres
**Enunciado:** Dadas las tuplas `grupoA = ("Ana", "Luis")` y `grupoB = ("Mía", "Carlos", "Pedro")`, crea una nueva tupla `todos` que concatene a los dos grupos. Luego cuenta cuántos alumnos hay en total con `len()`.
**Entrada:** Ninguna (valores fijos).
**Salida:** `Todos los alumnos: ('Ana', 'Luis', 'Mía', 'Carlos', 'Pedro'). Total: 5`

---

### Ejercicio 362: Tupla como clave de diccionario
**Enunciado:** Un sistema de ubicaciones usa tuplas (x, y) como claves de un diccionario que guarda la descripción del lugar. Crea un diccionario `mapa = {(0, 0): "Origen", (10, 5): "Parque", (3, 7): "Biblioteca"}`. Pide al usuario un par de coordenadas (x, y) e imprime la descripción correspondiente si existe, o "Lugar no registrado" si no existe.
**Entrada:** `x = 10`, `y = 5`
**Salida:** `Ubicación: Parque`

---

### Ejercicio 363: Desempaquetado de tupla en función
**Enunciado:** Define una función `sumar_coordenadas(punto)` que reciba una tupla de 3 elementos (x, y, z) y regrese la suma de sus coordenadas. Prueba con `punto = (3, 4, 5)`.
**Entrada:** `punto = (3, 4, 5)`
**Salida:** `La suma de las coordenadas es: 12`

---

### Ejercicio 364: Comparar tuplas lexicográficamente
**Enunciado:** Dadas las tuplas `t1 = (5, 10, 15)` y `t2 = (5, 10, 12)`, compara las tuplas usando el operador `<` e imprime el resultado. Explica que Python compara tuplas elemento por elemento de izquierda a derecha.
**Entrada:** Ninguna (valores fijos).
**Salida:** `t1 < t2 es False, porque en el tercer elemento 15 > 12`

---

## BLOQUE 12 · T14: DICCIONARIOS

### Ejercicio 365: Diccionario de precios de productos
**Enunciado:** Crea un diccionario `precios = {"manzana": 20, "pera": 25, "uva": 35, "naranja": 18}`. Pide al usuario el nombre de un producto y la cantidad deseada, e imprime el costo total (precio * cantidad). Si el producto no existe, muestra "Producto no disponible".
**Entrada:** `producto = uva`, `cantidad = 3`
**Salida:** `Costo total: $105`

---

### Ejercicio 366: Diccionario de frecuencias de letras
**Enunciado:** Crea un programa que pida una palabra y genere un diccionario donde cada clave es una letra y el valor es la cantidad de veces que aparece en la palabra. Usa un ciclo `for` sobre los caracteres de la palabra.
**Entrada:** `paralelepipedo`
**Salida:** `{'p': 3, 'a': 1, 'r': 1, 'l': 2, 'e': 3, 'i': 1, 'd': 1, 'o': 1}`

---

### Ejercicio 367: Diccionario de estudiantes y sus calificaciones finales
**Enunciado:** Dado el diccionario `estudiantes = {"Ana": [8, 9, 10], "Luis": [7, 8, 6], "Mía": [9, 10, 9]}`, donde cada valor es una lista de calificaciones, crea un nuevo diccionario `promedios` donde cada clave es el nombre y el valor es el promedio redondeado a 2 decimales.
**Entrada:** Ninguna (valores fijos).
**Salida:** `{'Ana': 9.0, 'Luis': 7.0, 'Mía': 9.33}`

---

### Ejercicio 368: Diccionario de conteo de palabras en frase
**Enunciado:** Crea un programa que pida una frase (varias palabras), divida la frase en palabras con `split()`, y genere un diccionario donde cada clave es una palabra y el valor es la cantidad de veces que aparece. Ignora mayúsculas/minúsculas convirtiendo todo a minúsculas primero.
**Entrada:** `El gato y el perro jugando en el jardín`
**Salida:** `{'el': 2, 'gato': 1, 'y': 1, 'perro': 1, 'jugando': 1, 'en': 1, 'jardín': 1}`

---

### Ejercicio 369: Diccionario de opciones de menú con funciones
**Enunciado:** Crea un diccionario `operaciones = {"1": "Sumar", "2": "Restar", "3": "Multiplicar", "4": "Dividir"}`. Usa un ciclo `while True` que muestre el menú, pida la opción, y si la opción es 1-4 pida dos números y realice la operación correspondiente, imprimiendo el resultado. Termina cuando se elige opción 5 "Salir".
**Entrada:** opción `1`, números `10` y `5`, luego opción `4`, números `20` y `4`, luego opción `5`.
**Salida:** `Resultado: 15.0`, `Resultado: 5.0`, `Fin del programa`

---

### Ejercicio 370: Diccionario de traducción simple
**Enunciado:** Crea un diccionario `traductor = {"hello": "hola", "world": "mundo", "goodbye": "adiós", "friend": "amigo", "thank": "gracias"}`. Pide al usuario una palabra en inglés e imprime la traducción al español si existe en el diccionario; si no, imprime "No traducido".
**Entrada:** `friend`
**Salida:** `amigo`

---

### Ejercicio 371: Diccionario de agenda telefónica con búsqueda
**Enunciado:** Crea un diccionario `agenda = {"Ana": "555-0101", "Luis": "555-0102", "Mía": "555-0103", "Pedro": "555-0104"}`. Permite al usuario buscar un nombre; si existe, muestra el teléfono; si no, pregunta si desea agregarla (s/n). Si responde s, pide el número y lo agrega al diccionario. Continúa en un ciclo hasta que el usuario escriba "salir".
**Entrada:** `Buscado: Sofia`, `¿Agregar? s`, `Número: 555-0200`, `Buscado: salir`
**Salida:** `Sofia no está en la agenda. ¿Agregar? (s/n): s. Contacto agregado: Sofia -> 555-0200. Fin de la agenda.`

---

### Ejercicio 372: Diccionario con valores porcentuales
**Enunciado:** Dado el diccionario `votos = {"Partido A": 35, "Partido B": 25, "Partido C": 20, "Partido D": 20}` (porcentajes), crea un programa que muestre la lista de partidos ordenados de mayor a menor porcentaje usando `sorted()` sobre los `items()` del diccionario.
**Entrada:** Ninguna (valores fijos).
**Salida:** `Ranking: Partido A (35%), Partido B (25%), Partido C (20%), Partido D (20%)`

---

## BLOQUE 13 · T15: EXCEPCIONES

### Ejercicio 373: Validación de entrada numérica con reintento
**Enunciado:** Crea un programa que pida un número entero al usuario; si el usuario ingresa algo que no es un número, captura `ValueError` y vuelve a pedir el número dentro de un ciclo `while True` hasta que sea válido. Muestra el número capturado al final.
**Entrada:** `abc`, `12.5`, `7`
**Salida:** `Error: Debes ingresar un número entero. Error: Debes ingresar un número entero. Número capturado: 7`

---

### Ejercicio 374: División segura con bloques múltiples
**Enunciado:** Crea un programa que pida dos números (numerador y denominador) y realice la división, capturando `ValueError` si no son números, `ZeroDivisionError` si el denominador es 0, y mostrando mensajes específicos para cada caso. Si la división es exitosa, muestra el resultado redondeado a 2 decimales.
**Entrada:** `10`, `3`
**Salida:** `El resultado es: 3.33`

---

### Ejercicio 375: Sistema de cálculo con manejo de excepciones específicas
**Enunciado:** Crea un programa que pida el radio de una circunferencia y calcule su área (`pi * radio²`). El programa debe:
- Capturar `ValueError` si el radio no es numérico.
- Capturar `NegativeValueError` si el radio es negativo (crea esta excepción personalizada heredando de `Exception`).
- Capturar `KeyboardInterrupt` si el usuario presiona Ctrl+C (muestra "Operación cancelada").
- Si todo es válido, muestra el área redondeada a 2 decimales.
**Entrada:** `-5`
**Salida:** `Error: El radio no puede ser negativo`

---

Resuelve los ejercicios conforme avances en los temas. Cada ejercicio incluye el **enunciado**, un **ejemplo de entrada** y la **salida esperada**. Se recomienda resolverlos en un Jupyter Notebook y subirlos a tu repositorio de GitHub.

---

## BLOQUE 1 · T1-T4: FUNDAMENTOS CON INTEGRACIÓN (VARIABLES, TIPOS, ENTRADA/SALIDA, MODELO EPS)

### Ejercicio 376: Conversor de unidades múltiple
**Enunciado:** Crea un programa que pida una distancia en metros y la convierta a kilómetros, centímetros y pulgadas (1 pulgada = 2.54 cm). Muestra todas las conversiones en una misma línea usando f-strings.
**Entrada:** `500`
**Salida:** `500 m = 0.5 km = 50000 cm = 196.85 pulgadas`

---

### Ejercicio 377: Calculadora de propinas por región
**Enunciado:** Crea un programa que pida el monto de una cuenta y la región del restaurante (México, España, EE.UU.). Aplica porcentajes de propina: México 15%, España 10%, EE.UU. 20%. Muestra el monto original, la propina y el total. Si la región no es válida, muestra "Región no válida".
**Entrada:** `1500` y `México`
**Salida:** `Cuenta: $1500.00 | Propina: $225.00 | Total: $1725.00`

---

### Ejercicio 378: Validador de nombre de usuario
**Enunciado:** Crea un programa que pida un nombre de usuario y verifique: longitud entre 5 y 12 caracteres, no empieza con número, y solo contiene letras y números. Usa un `while` que repita la solicitud hasta obtener un nombre válido. Muestra el nombre validado.
**Entrada:** `ab1`, `123456`, `JuanPerez2026`
**Salida:** `Nombre de usuario válido: JuanPerez2026`

---

### Ejercicio 379: Calculadora de IMC con categorías
**Enunciado:** Crea un programa que pida peso (kg) y altura (m), calcule el IMC (peso / altura²) y clasifique: < 18.5 "Bajo peso", 18.5-24.9 "Normal", 25-29.9 "Sobrepeso", ≥ 30 "Obesidad". Muestra IMC y categoría.
**Entrada:** `80` y `1.75`
**Salida:** `IMC: 26.12 - Sobrepeso`

---

### Ejercicio 380: Descomposición de tiempo con validación
**Enunciado:** Crea un programa que pida segundos (positivo, menor a 1 millón) y los convierta a días, horas, minutos, segundos usando // y %. Valida con try-except y while hasta obtener un entero positivo válido.
**Entrada:** `-10`, `abc`, `90061`
**Salida:** `90061 segundos = 1 día, 1 hora, 1 minuto, 1 segundo`

---

### Ejercicio 381: Ticket de compra con impuestos regionales
**Enunciado:** Crea un programa que pida precio base, región (Canadá con IVA 5%, México con IVA 16%, Brasil con 17%) y calcule el total con impuestos y formas de pago (efectivo descuento 2%, tarjeta 3% de recargo). Valida región con elif.
**Entrada:** `500`, `México`, `tarjeta`
**Salida:** `Subtotal: $500.00 | IVA: $80.00 | Tipo: tarjeta (+3%) | Total: $597.00`

---

### Ejercicio 382: Generador de contraseñas básicas
**Enunciado:** Pide un nombre de usuario, extrae 3 letras (primera, del medio, última), concatena con un número aleatorio del 100 al 999 y dos caracteres especiales (#, !, @) en posiciones fijas. Muestra la contraseña generada sin usar random, solo operaciones matemáticas con el hash interno.
**Entrada:** `Ana`
**Salida:** `Contraseña generada: An321#!a` (ejemplo ilustrativo)

---

### Ejercicio 383: Calculadora de edad futura con proyección
**Enunciado:** Pide año de nacimiento, año actual, y años futuros a proyectar. Muestra edad actual, edad en el futuro, y los múltiplos de 5 que alcanzará (cada vez que la edad es múltiplo de 5). Usa for con range y f-strings.
**Entrada:** `2000`, `2026`, `10`
**Salida:** `Edad actual: 26 años | En 2036 tendrás 36 años | Multiplos de 5: 30, 35, 40`

---

### Ejercicio 384: Sistema de descuentos por lealtad
**Enunciado:** Un supermercado aplica descuentos escalonados según compras acumuladas: < $500, 0%; $500-$999, 5%; $1000-$1999, 10%; ≥ $2000, 15%. Pide compra actual y total acumulado anual, calcula el descuento dela compra actual e imprime el total a pagar.
**Entrada:** `1200` y `8000`
**Salida:** `Descuento aplicado: 10% | Total a pagar: $1080.00`

---

### Ejercicio 385: Conversor de divisas con actualización automática
**Enunciado:** Pide un monto en pesos mexicanos y lo convierte a dólares (1 USD = 17.50 MXN), euros (1 EUR = 19.20 MXN) y yenes (1 JPY = 0.12 MXN). Si el monto es negativo, repite con while. Muestra todas las conversiones con formato de 2 decimales.
**Entrada:** `-200`, `500`
**Salida:** `USD: 28.57 | EUR: 26.04 | JPY: 4166.67`

---

### Ejercicio 386: Calculadora de pago por horas extra
**Enunciado:** Pide horas trabajadas (semanal) y pago por hora. Si horas > 40, las extra se pagan al doble. Valida con try-except que las horas sean ≥ 0 y el pago > 0. Muestra pago normal, pago extra, total.
**Entrada:** `45` y `200`
**Salida:** `Pago normal: $8000.00 | Horas extra: 5 | Pago extra: $2000.00 | Total: $10000.00`

---

### Ejercicio 387: Formateador de fechas
**Enunciado:** Pide día, mes y año como enteros. Valida que sean coherentes (día 1-31 según mes, mes 1-12, año > 1900). Usa if/elif para meses con días distintos (febrero con 28, meses de 30 y 31 días). Muestra fecha formateada con f-strings.
**Entrada:** `29`, `2`, `2024`
**Salida:** `Fecha: 29/02/2024 (Año bisiesto)`
**Entrada:** `32`, `1`, `2024`
**Salida:** `Error: Día inválido para el mes`
**Entrada:** `2024` (bisiesto)
**Salida:** `El año 2024 es bisiesto`

---

### Ejercicio 388: Sistema de alertas de temperatura
**Enunciado:** Dado un registro de 7 temperaturas diarias (capturadas con input), clasifica cada día: < 0 "Congelante", 0-15 "Frío", 16-25 "Templado", 26-35 "Cálido", > 35 "Extremo". Al final, cuenta cuántos días de cada tipo. Usa while para captura y diccionario para conteo.
**Entrada:** `-5`, `5`, `18`, `28`, `37`, `10`, `22`
**Salida:** `Congelante: 1 | Frío: 2 | Templado: 2 | Cálido: 1 | Extremo: 1`

---

## BLOQUE 2 · T5-T8: DECISIONES ANIDADAS, CICLOS COMPLEJOS, DEBUGGING

### Ejercicio 389: Sistema de calificaciones numéricas a palabras con rangos superpuestos
**Enunciado:** Convierte calificaciones 0-10 a descripción: 0-5 "Reprobado", 6 "Regular", 7 "Aprobado", 8 "Bueno", 9 "Muy bueno", 10 "Excelente". Usa if-elif con validación: si la calificación está fuera del rango, muestra error y pide de nuevo con while.
**Entrada:** `11`, `-2`, `7`
**Salida:** `Calificación inválida. Reintenta. | Calificación inválida. Reintenta. | Calificación: 7 → Aprobado`

---

### Ejercicio 390: Calculadora de costo por impulso telefónico
**Enunciado:** Una compañía cobra: primeros 300 impulsos $0.15 cada uno, siguientes 300 (301-600) $0.10, restantes $0.08. Pide impulsos del mes y calcula el costo total. Si el número es negativo o 0, muestra mensaje especial.
**Entrada:** `750`
**Salida:** `Costo: $95.00 (300*0.15 + 300*0.10 + 150*0.08)`

---

### Ejercicio 391: Ruteador de operaciones matemáticas
**Enunciado:** Un menú con while muestra opciones: 1) Sumar, 2) Restar, 3) Multiplicar, 4) Dividir, 5) Potencia (sin **), 6) Módulo, 7) Salir. Para cada opción pide dos números, valida con try-except, ejecuta la operación y muestra el resultado. Si división por cero, captura ZeroDivisionError.
**Entrada:** opción `4`, números `10` y `0`
**Salida:** `Error: No se puede dividir entre cero`
**Entrada:** opción `5`, números `3` y `4`
**Salida:** `3 elevado a 4 = 81`

---

### Ejercicio 392: Generador de secuencias numéricas con patrón
**Enunciado:** Pide un número N. Genera la secuencia: 1, -2, 3, -4, 5, -6... hasta N, alternando signos. Muestra la secuencia en una línea y la suma total. Usa for con range y condicional.
**Entrada:** `6`
**Salida:** `Secuencia: 1, -2, 3, -4, 5, -6 | Suma: -3`

---

### Ejercicio 393: Ordenamiento de tres números con lógica anidada
**Enunciado:** Pide tres números y los ordena de mayor a menor usando solo decisiones anidadas (no listas, no sort). Muestra los tres en orden descendente.
**Entrada:** `15`, `7`, `22`
**Salida:** `22 > 15 > 7`

---

### Ejercicio 394: Contador de caracteres específicos en texto
**Enunciado:** Pide un texto e indica cuántas vocales (a, e, i, o, u, mayúsculas y minúsculas), mayúsculas, dígitos y espacios contiene. Usa for sobre el string, no métodos de conteo directos (no count).
**Entrada:** `Hola Mundo 2024!`
**Salida:** `Vocales: 4 | Mayúsculas: 1 | Dígitos: 4 | Espacios: 2`

---

### Ejercicio 395: Calculadora de interés con límites de tiempo
**Enunciado:** Un banco ofrece interés simple anual del 6% pero con límite de capital: si el capital es < $1000, solo 1 año de interés; $1000-$4999, hasta 2 años; ≥ $5000, hasta 5 años. Pide capital e importe, valida el rango de años según el capital, calcula interés y monto final.
**Entrada:** `1500`, `2`
**Salida:** `Capital: $1500 | Interés: $180.00 (2 años) | Total: $1680.00`

---

### Ejercicio 396: Sistema de turnos con prioridad
**Enunciado:** Una clínica asigna turnos según el tipo de paciente y su orden de llegada. Pide N pacientes, para cada uno: nombre, tipo (emergencia, urgente, normal). Emergencias se atienden primero, luego urgentes, luego normales. Muestra lista de atención ordenada sin usar sort, solo ciclos y listas.
**Entrada:** `3`, `Juan (urgente)`, `Ana (emergencia)`, `Luis (normal)`
**Salida:** `1. Ana (emergencia) | 2. Juan (urgente) | 3. Luis (normal)`

---

### Ejercicio 397: Verificador de contraseña con historial
**Enunciado:** Define una contraseña válida predefinida (ej. "Abc123!"). Pide contraseña al usuario. Cada intento fallido, registra en una lista el intento. Si acierta, muestra "Acceso concedido" con el número de intentos. Si falla 3 veces, muestra "Cuenta bloqueada" y termina con break. Registra cada intento.
**Entrada:** `123`, `abc`, `Abc123!`
**Salida:** `Intento 1 fallido (guardado: 123) | Intento 2 fallido (guardado: abc) | ¡Acceso concedido! Intentos: 3`

---

### Ejercicio 398: Calculadora de descuento por volumen con tablas escalonadas
**Enunciado:** Una fábrica vende unidades a $120 c/u. Descuentos: 1-50 unidades, 0%; 51-100, 5%; 101-200, 10%; >200, 15%. Además cada 50 unidades hay un bono extra de $100 de descuento. Pide unidades compradas, calcula costo sin descuento, descuento porcentual, bono, total.
**Entrada:** `150`
**Salida:** `Costo base: $18000 | Descuento 10%: $1800 | Bono: $300 (3 bonos) | Total: $15900`

---

### Ejercicio 399: Análisis de números primos en rango
**Enunciado:** Pide dos números (inicio y fin, inicio < fin). Usa for con range para encontrar todos los números primos en ese rango. Un número es primo si solo es divisible por 1 y sí mismo. Muestra los primos y cuántos hay.
**Entrada:** `10` y `30`
**Salida:** `Primos: 11, 13, 17, 19, 23, 29 | Cantidad: 6`

---

### Ejercicio 400: Simulador de ruleta simple
**Enunciado:** Una ruleta tiene números del 1 al 36. El usuario apuesta a un número. Genera un número aleatorio (simulado con datetime/hora actual: número = minuto * 36 + segundo, módulo 36 + 1). Si coincide, gana 35 veces su apuesta; si no, pierde la apuesta. Pide apuesta, número apostado, muestra resultado. ¿Adivina la paridad (par/impar) con bonus del 50% si acierta la paridad pero no el número?
**Entrada:** apuesta `100`, número `15`, número ganador `15`
**Salida:** `¡Número exacto! Ganas: $3500`
**Entrada:** apuesta `100`, número `15`, número ganador `16`
**Salida:** `Número incorrecto. Apuesta perdida: $100 | Pero acertaste paridad (impar) → Bonus 50%: $50 | Total ganado: $-50`

---

### Ejercicio 401: Generador de tablas de verdad lógicas
**Enunciado:** Dado dos valores booleanos A y B (ingresados como "True" o "False"), genera la tabla de verdad de las operaciones: A and B, A or B, not A, not B, A != B (xor). Muestra en formato tabular con f-strings.
**Entrada:** `True` y `False`
**Salida:**
```
A       B       AND     OR      NOT A   NOT B   XOR
True    False   False   True    False   True    True
```
**Entrada:** `False`, `False`
**Salida:**
```
A       B       AND     OR      NOT A   NOT B   XOR
False   False   False   False   True    True    False
```

---

### Ejercicio 402: Contador de palabras con longitud mínima
**Enunciado:** Pide un párrafo. Cuenta cuántas palabras tienen longitud ≥ 5, longitud 3-4, y longitud 1-2. Muestra con for sobre split(). Además, muestra la palabra más larga y su longitud.
**Entrada:** `La programación es divertida y desafiante`
**Salida:** `Longitud ≥5: 4 palabras | Longitud 3-4: 3 palabras | Longitud 1-2: 0 | Palabra más larga: "programación" (12 caracteres)`

---

### Ejercicio 403: Calculadora de descuento por lealtad acumulada con historial
**Enunciado:** Un programa que pida 10 compras (monto de cada una). Cada compra: si ≥ $500, descuento 5%; si ≥ $1000, descuento 10%; si ≥ $2000, descuento 15%. Promedio de descuentos aplicados. Total acumulado sin descuentos y con descuentos. Al final, muestra el monto ahorrado.
**Entrada:** `400`, `800`, `1500`, `200`, `3000`, `500`, `100`, `2500`, `600`, `1200`
**Salida:** `Total sin descuento: $12800 | Total con descuento: $11890 | Ahorro: $910`

---

### Ejercicio 404: Generador de patrón de números con ciclos for anidados
**Enunciado:** Pide un número N de filas. Genera el siguiente patrón:
```
N=3:
1
2 3
4 5 6

N=4:
1
2 3
4 5 6
7 8 9 10
```
Usa for anidados y un contador incremental.
**Entrada:** `4`
**Salida:** (ver arriba)

---

### Ejercicio 405: Sistema de monitoreo de stock con alertas
**Enunciado:** Dado un diccionario de productos con sus cantidades (ej. {"manzanas": 50, "bananas": 12, "naranjas": 100}), pide el nombre de un producto y la cantidad a vender. Si la cantidad disponible es insuficiente, muestra alerta. Si se vende > 80% del stock, marca "Reordenar urgente". Usa excepciones KeyError. Calcula el stock restante y lo muestra.
**Entrada:** `bananas`, `10`
**Salida:** `Venta: 10 bananas | Stock restante: 2 | Alerta: Reordenar urgente (83% vendido)`
**Entrada:** `peras` (inexistente)
**Salida:** `Error: Producto no encontrado en inventario`

---

### Ejercicio 406: Validador de expresiones matemáticas simples
**Enunciado:** Pide un string con formato "NÚMERO OPERADOR NÚMERO" (ej. "10 + 5", "8 / 0"). Valida que se pueda evaluar: primero verifica que la operación sea +, -, *, /, //, %, **. Luego evalúa y muestra resultado o error (ZeroDivisionError, ValueError si no son números). Usa split() y try-except.
**Entrada:** `10 / 0`
**Salida:** `Error: División entre cero`
**Entrada:** `8 + 5`
**Salida:** `Resultado: 13`
**Entrada:** `abc + 5`
**Salida:** `Error: Los operandos deben ser números`

---

### Ejercicio 407: Calculadora de descomposición de cantidad en billetes
**Enunciado:** Pide un monto en pesos (múltiplo de 5). Calcula la descomposición en billetes de $500, $200, $100, $50, $20, $10 y $5. Usa divmod o // y %. Muestra cada tipo de billete con su cantidad.
**Entrada:** `1235`
**Salida:**
```
Billetes de $500: 2 (restan $235)
Billetes de $200: 1 (restan $35)
Billetes de $100: 0 (restan $35)
Billetes de $50: 0 (restan $35)
Billetes de $20: 1 (restan $15)
Billetes de $10: 1 (restan $5)
Billetes de $5: 1
```

---

### Ejercicio 408: Sistema de votación con validación de distrito
**Enunciado:** Tres distritos (A, B, C) con número de electores válidos. Cada distrito tiene candidatos 1, 2, 3. Pide distrito y voto (número candidato). Valida: distrito válido (A, B, C), voto válido (1, 2, 3). Si inválido, muestra error y repite con while. Al final muestra conteo por distrito y ganador general.
**Entrada:** `A`, `1`, `B`, `2`, `C`, `3`, `A`, `2`, `fin`
**Salida:**
```
Distrito A: Candidato 1: 1, Candidato 2: 1
Distrito B: Candidato 2: 1
Distrito C: Candidato 3: 1
Ganador: Candidato 1 (1 voto), Candidato 2 (1 voto), Candidato 3 (1 voto) → Empate
```

---

### Ejercicio 409: Generador de código de producto con checksum
**Enunciado:** Genera un código de producto de 8 dígitos: los 7 primeros son ingresados por el usuario (validar que sean dígitos), el octavo es un dígito verificador calculado con el algoritmo Luhn simplificado: suma de posiciones pares * 3 + suma de posiciones impares * 7, módulo 10. Si el resultado es 0, el verificador es 0. Muestra el código completo.
**Entrada:** `1234567`
**Salida:** `Código generado: 1234567X` (donde X es el checksum calculado)

---

### Ejercicio 410: Simulador de proceso productivo con fallos
**Enunciado:** Una fábrica produce 100 unidades. Cada unidad tiene un 5% de probabilidad de fallo (simulado con minuto actual: si minuto es par, fallo; si es impar, éxito). Muestra: total producidas, total falladas, tasa de éxito en %. Al final, si tasa de éxito < 90%, muestra alerta de mantenimiento.
**Entrada:** (simulación con 100 unidades)
**Salida:** `Total producido: 100 | Exitosos: 52 | Fallados: 48 | Tasa de éxito: 52% | ¡ALERTA: Tasa baja! Se recomienda mantenimiento`

---

## BLOQUE 3 · T9-T10: LISTAS, LISTAS DE LISTAS (MATRICES), FUNCIONES

### Ejercicio 411: Manipulación de lista de compras
**Enunciado:** Crea una lista de compras inicial: ["manzanas", "leche", "pan", "huevos"]. Pide al usuario agregar 3 elementos más (con input), eliminar el primero, imprimir la lista final. Muestra también la cantidad de elementos con len() y el primer y último elemento.
**Entrada:** `arroz`, `frijoles`, `azúcar`
**Salida:** `Lista final: ["leche", "pan", "huevos", "arroz", "frijoles", "azúcar"] | Elementos: 6 | Primero: leche | Último: azúcar`

---

### Ejercicio 412: Ordenamiento de lista sin sort (método burbuja)
**Enunciado:** Dada una lista de números desordenados, ordena de menor a mayor implementando el método de burbuja (for anidados con comparación e intercambio). Muestra lista original y lista ordenada. No uses sort().
**Entrada:** `[5, 2, 8, 1, 9, 3]`
**Salida:** `Lista original: [5, 2, 8, 1, 9, 3] | Lista ordenada: [1, 2, 3, 5, 8, 9]`

---

### Ejercicio 413: Fusión de dos listas ordenadas (interleaving)
**Enunciado:** Dadas dos listas ordenadas (ej. [1, 3, 5] y [2, 4, 6]), crea una nueva lista intercalando sus elementos: [1, 2, 3, 4, 5, 6]. Usa for con range y len, compara y alterna. No uses sort ni sorted.
**Entrada:** `[1, 5, 9]` y `[2, 3, 10]`
**Salida:** `[1, 2, 3, 5, 9, 10]`

---

### Ejercicio 414: Búsqueda de elementos con criterios múltiples
**Enunciado:** Dada una lista de tuplas con (nombre, edad, ciudad): [("Ana", 25, "México"), ("Luis", 30, "España"), ("Ana", 28, "México")]. Pide nombre y ciudad. Encuentra todas las personas que coinciden (ambos criterios). Muestra el número de coincidencias y lista los nombres.
**Entrada:** `Ana`, `México`
**Salida:** `Coincidencias: 2 | Ana (25), Ana (28)`

---

### Ejercicio 415: Calculadora de estadísticas de lista
**Enunciado:** Dada una lista de números, calcula: suma, promedio, valor máximo, valor mínimo, desviación estándar (usa fórmula: raíz de la varianza = promedio de (x-promedio)²). No uses funciones estadísticas integradas. Implementa con for y variables acumuladoras.
**Entrada:** `[10, 12, 23, 23, 16, 23, 21, 16]`
**Salida:** `Suma: 81 | Promedio: 17.38 | Máximo: 23 | Mínimo: 10 | Desviación estándar: 5.32`

---

### Ejercicio 416: Recorrido de lista de listas con recuento
**Enunciado:** Dada una lista de listas con nombres de estudiantes por grupo: [["Ana", "Luis"], ["Maria", "Pedro", "Jose"], ["Juan"]]. Imprime: número de estudiantes por grupo, total de estudiantes, y todos los nombres en una sola línea separados por comas.
**Entrada:** (datos fijos)
**Salida:** `Grupo 0: 2 estudiantes | Grupo 1: 3 estudiantes | Grupo 2: 1 estudiantes | Total: 6 | Nombres: Ana, Luis, Maria, Pedro, Jose, Juan`

---

### Ejercicio 417: Matriz de asistencia de clase
**Enunciado:** Crea una matriz 5x5 donde cada celda es "P" (presente) o "A" (ausente). Pide al usuario ingresar las asistencias (por fila y columna o en bloque). Luego calcula: porcentaje de asistencia por fila (estudiantes), por columna (día), y global. Muestra matriz y estadísticas.
**Entrada:** matriz 5x5 de Ps y As (ejemplo dado)
**Salida:** `Asistencia global: 80% | Por estudiante (fila 0): 80% | Por día (columna 2): 60%`

---

### Ejercicio 418: Transposición de matriz
**Enunciado:** Dada una matriz 3x3, crea su transpuesta (filas → columnas, columnas → filas). Usa listas de listas y ciclos anidados. Muestra la matriz original y la transpuesta en formato sin corchetes.
**Entrada:** `[[1, 2, 3], [4, 5, 6], [7, 8, 9]]`
**Salida:**
```
Original:
1 2 3
4 5 6
7 8 9
Transpuesta:
1 4 7
2 5 8
3 6 9
```

---

### Ejercicio 419: Función que procesa matrices (suma de submatrices)
**Enunciado:** Define una función `suma_submatriz(matriz, fila_inicio, fila_fin, col_inicio, col_fin)` que regresa la suma de una submatriz rectangular. Pruébala con una matriz 4x4. Además, define una función `mostrar_matriz(matriz)` sin return que imprima la matriz sin corchetes ni comas. Usa ambas.
**Entrada:** matriz 4x4 con valores del 1 al 16, submatriz fila 0-1, col 1-2
**Salida:** `Suma de submatriz (filas 0-1, cols 1-2): 32`

---

### Ejercicio 420: Sistema de inventario con matrices (productos x meses)
**Enunciado:** Crea una matriz 3x4: 3 productos, 4 meses. Cada celda es la cantidad vendida. Pide al usuario producir datos de ejemplo o usa datos fijos. Calcula: total vendido por producto (suma de fila), total vendido por mes (suma de columna), producto más vendido, mes con mayor venta. Define funciones modular: `calcular_totaes(matriz)`, `mostrar_matriz(matriz)`.
**Entrada:** datos fijos (ejemplo)
**Salida:** `Total por producto: [120, 180, 95] | Total por mes: [120, 110, 145, 120] | Producto más vendido: Producto 2 (180) | Mes más vendido: Mes 3 (145)`

---

### Ejercicio 421: Función de validación de matriz
**Enunciado:** Define una función `es_matriz_cuadrada(matriz)` que regresa True/False si la matriz es cuadrada (filas = columnas). Define otra función `es_simetrica(matriz)` que regresa True/False si matriz[i][j] == matriz[j][i] para toda i,j. Usa matrices de ejemplo.
**Entrada:** `[[1, 2], [2, 1]]` (simétrica)
**Salida:** `Es cuadrada: True | Es simétrica: True`
**Entrada:** `[[1, 2, 3], [4, 5, 6]]` (no cuadrada)
**Salida:** `Es cuadrada: False | Es simétrica: False`

---

### Ejercicio 422: Función de multiplicación de matrices (sin numpy)
**Enunciado:** Define una función `multiplicar_matrices(A, B)` que regresa la matriz producto C = A*B usando el algoritmo de multiplicación matricial (ciclos for anidados: C[i][j] = sum(A[i][k] * B[k][j])). Valida que las dimensiones sean compatibles. Pruébala con matrices 2x2.
**Entrada:** `A = [[1, 2], [3, 4]]`, `B = [[5, 6], [7, 8]]`
**Salida:** `Resultado: [[19, 22], [43, 50]]`

---

### Ejercicio 423: Matriz de rotación de imágenes (representación simple)
**Enunciado:** Dada una matriz 2x3, rota 90 grados en sentido horario implementando la transformación matemática (elemento [i][j] va a posición [j][filas-1-i]). Muestra matriz original y rotada en formato legible.
**Entrada:** `[[1, 2, 3], [4, 5, 6]]`
**Salida:**
```
Original (2x3):
1 2 3
4 5 6
Rotada 90° (3x2):
4 1
5 2
6 3
```

---

### Ejercicio 424: Sistema de calificaciones de estudiantes con matrices
**Enunciado:** Crea una matriz 4x5: 4 estudiantes, 5 calificaciones cada uno. Calcula: promedio de cada estudiante, calificación más alta de cada uno, estudiante con mejor promedio, y el promedio general de la clase. Guarda en una lista de diccionarios con nombres. Usa funciones: `calcular_promedios(matriz)`, `estudiante_mejor_promedio(matriz)`.
**Entrada:** matriz de 4 estudiantes con 5 calificaciones
**Salida:** `Promedios: [8.2, 9.0, 7.5, 8.8] | Estudiantes: Ana(8.2), Luis(9.0), Maria(7.5), Pedro(8.8) | Mejor: Luis con 9.0 | Promedio general: 8.375`

---

### Ejercicio 425: Función de rotación de elementos en lista
**Enunciado:** Define una función `rotar_lista(lista, n)` que regresa una nueva lista rotada: si n es positivo, rota hacia la derecha n posiciones; si negativo, hacia la izquierda. No uses slicing [::-1], implementa con concatención y for. Pruébala.
**Entrada:** `[1, 2, 3, 4, 5]`, `n = 2`
**Salida:** `[4, 5, 1, 2, 3]`
**Entrada:** `[1, 2, 3, 4, 5]`, `n = -2`
**Salida:** `[3, 4, 5, 1, 2]`

---

## BLOQUE 4 · T11-T12: FUNCIONES (CON Y SIN RETURN) CON PARÁMETROS COMPLEJOS

### Ejercicio 426: Función que retorna stats de una lista de números
**Enunciado:** Define una función `estadisticas_lista(lista)` que regresa un diccionario con: suma, promedio, max, min, cantidad_pares, cantidad_impares. Implementa sin usar funciones estadísticas. Prueba con lista de 10 números.
**Entrada:** `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`
**Salida:** `{'suma': 55, 'promedio': 5.5, 'max': 10, 'min': 1, 'pares': 5, 'impares': 5}`

---

### Ejercicio 427: Función que genera una lista con patrón específico
**Enunciado:** Define una función `generar_secuencia(n)` que regresa una lista con el patrón: 1, -2, 3, -4, 5, -6... hasta n términos. Usa for con range y alternancia de signo. Prueba con n=8.
**Entrada:** `8`
**Salida:** `[1, -2, 3, -4, 5, -6, 7, -8]`

---

### Ejercicio 428: Función que retorna el número palindrómico más cercano
**Enunciado:** Define una función `palindromo_cercano(n)` que regresa el número palindrómico (se lee igual al derecho y al revés) más cercano a n. Implementa con while contando hacia arriba y abajo hasta encontrar. Pruébala.
**Entrada:** `123`
**Salida:** `121 (palindromo más cercano a 123)`
**Entrada:** `100`
**Salida:** `99 (palindromo más cercano a 100)`

---

### Ejercicio 429: Procedimiento que imprime un cubo de asteriscos
**Enunciado:** Define un procedimiento `dibujar_cubo(n)` que NO regresa valor e imprime en consola la representación de un cubo de n x n usando asteriscos y caracteres especiales para las caras. Usa for anidados. Por simplicidad, dibuja solo el frente, la parte superior y el lateral derecho.
**Entrada:** `3`
**Salida:**
```
  +------+
 /      /|
+------+ |
|      | +
|      |/
+------+
```
**Entrada:** `4`
**Salida:** (cubo 4x4 similar)

---

### Ejercicio 430: Función que retorna el MCD (máximo común divisor)
**Enunciado:** Define una función `mcd(a, b)` que regresa el máximo común divisor usando el algoritmo de Euclides (while: mientras b != 0, a, b = b, a % b). Pruébala con varios pares.
**Entrada:** `48`, `18`
**Salida:** `MCD de 48 y 18: 6`
**Entrada:** `100`, `75`
**Salida:** `MCD de 100 y 75: 25`

---

### Ejercicio 431: Función que retorna el MCM (mínimo común múltiplo)
**Enunciado:** Define una función `mcm(a, b)` que regresa el mínimo común múltiplo usando la fórmula: MCM = (a * b) / MCD(a, b). Usa la función del ejercicio 430. Pruébala.
**Entrada:** `12`, `18`
**Salida:** `MCM de 12 y 18: 36`

---

### Ejercicio 432: Procedimiento que muestra una matriz transpuesta
**Enunciado:** Define un procedimiento `mostrar_transpuesta(matriz)` que NO regresa valor e imprime la matriz transpuesta (filas ↔ columnas) sin corchetes ni comas. Usa ciclos anidados. Pruébalo con una matriz 3x3.
**Entrada:** `[[1, 2, 3], [4, 5, 6], [7, 8, 9]]`
**Salida:** `Transpuesta: 1 4 7 | 2 5 8 | 3 6 9`

---

### Ejercicio 433: Función que retorna el número de dígitos de un número
**Enunciado:** Define una función `contar_digitos(n)` que regresa la cantidad de dígitos de un número entero (usa while con // 10). Pruébala con positivos y negativos (el negativo cuenta sin el signo).
**Entrada:** `12345`
**Salida:** `12345 tiene 5 dígitos`
**Entrada:** `-9876`
**Salida:** `-9876 tiene 4 dígitos`

---

### Ejercicio 434: Función que retorna la reversa de un número
**Enunciado:** Define una función `reversar_numero(n)` que regresa el número con los dígitos en orden inverso. Usa while con % 10 y // 10. Pruébala.
**Entrada:** `12345`
**Salida:** `Reversa de 12345: 54321`
**Entrada:** `980`
**Salida:** `Reversa de 980: 89` (sin ceros a la izquierda)

---

### Ejercicio 435: Función que retorna la suma de dígitos
**Enunciado:** Define una función `suma_digitos(n)` que regresa la suma de los dígitos de un número entero. Implementa con while y % 10. Pruébala.
**Entrada:** `4729`
**Salida:** `Suma de dígitos de 4729: 22`

---

### Ejercicio 436: Función que retorna si un número es Armstrong
**Enunciado:** Un número Armstrong (narcisista) es aquel donde la suma de sus dígitos elevados a la cantidad de dígitos es igual al número. Define una función `es_armstrong(n)` que regresa True/False. Usa otras funciones (contar_digitos, potencia con for). Pruébala.
**Entrada:** `153` (1³ + 5³ + 3³ = 1 + 125 + 27 = 153)
**Salida:** `153 es un número Armstrong`
**Entrada:** `123`
**Salida:** `123 no es un número Armstrong`

---

### Ejercicio 437: Función que retorna el factorial con memoización simple
**Enunciado:** Define una función `factorial_memo(n, cache={})` que regresa el factorial usando memoización: si n está en cache, regresa el valor; si no, calcula, guarda en cache y regresa. Implementa con for y acumulador. Pruébala con n=5 y luego con n=5 de nuevo (debe ser más rápido).
**Entrada:** `5`
**Salida:** `Factorial de 5: 120 (calculado)`
**Entrada:** `5` (segunda vez)
**Salida:** `Factorial de 5: 120 (desde caché)`

---

### Ejercicio 438: Función que retorna el n-ésimo número de Fibonacci
**Enunciado:** Define una función `fibonacci(n)` que regresa el n-ésimo número de Fibonacci usando iteración (no recursión). Usa dos variables auxiliares. Pruébala.
**Entrada:** `8`
**Salida:** `Fibonacci(8): 21` (secuencia: 0, 1, 1, 2, 3, 5, 8, 13, 21)
**Entrada:** `10`
**Salida:** `Fibonacci(10): 55`

---

### Ejercicio 439: Función que retorna una lista de números de Fibonacci
**Enunciado:** Define una función `secuencia_fibonacci(n)` que regresa una lista con los primeros n números de Fibonacci. Usa while o for. Pruébala.
**Entrada:** `8`
**Salida:** `[0, 1, 1, 2, 3, 5, 8, 13]`

---

### Ejercicio 440: Función que retorna la potencia con multiplicaciones sucesivas
**Enunciado:** Define una función `potencia(base, exponente)` que regresa base^exponente sin usar **, solo multiplicaciones sucesivas con un for y un acumulador. El exponente puede ser 0 o positivo. Pruébala.
**Entrada:** `3`, `4`
**Salida:** `3^4 = 81`

---

### Ejercicio 441: Función que retorna el máximo de una lista sin max()
**Enunciado:** Define una función `maximo_lista(lista)` que regresa el valor máximo recorriendo la lista con un for. No uses max() ni sort(). Pruébala.
**Entrada:** `[3, 7, 2, 9, 4, 1]`
**Salida:** `Máximo: 9`

---

### Ejercicio 442: Función que retorna el índice del máximo de una lista
**Enunciado:** Define una función `indice_maximo(lista)` que regresa el índice (posición) del primer valor máximo encontrado. Si hay varios, regresa el primero. Usa for con range y len. Pruébala.
**Entrada:** `[3, 7, 9, 2, 9, 4]`
**Salida:** `Índice del máximo: 2 (valor 9)`

---

### Ejercicio 443: Función que retorna una lista de números primos hasta N
**Enunciado:** Define una función `primos_hasta(n)` que regresa una lista con todos los números primos desde 2 hasta n. Usa for con range y verificación de divisibilidad. Pruébala.
**Entrada:** `20`
**Salida:** `[2, 3, 5, 7, 11, 13, 17, 19]`

---

### Ejercicio 444: Función que retorna el factorial de un número (recursivo vs iterativo)
**Enunciado:** Define DOS funciones: `factorial_iterativo(n)` que regresa el factorial con un for y acumulador, Y `factorial_recursivo(n)` que regresa con recursividad (caso base: n==0 o n==1 → 1; caso recursivo: n * factorial_recursivo(n-1)). Prueba ambas y compara resultados.
**Entrada:** `5`
**Salida:** `Iterativo: 120 | Recursivo: 120`

---

### Ejercicio 445: Procedimiento que imprime un rombo de asteriscos
**Enunciado:** Define un procedimiento `dibujar_rombo(n)` que NO regresa valor e imprime un rombo de asteriscos de 2n-1 filas de alto. La fila i tiene 2i-1 asteriscos centrados. Usa for anidados para espacios y asteriscos. Pruébalo.
**Entrada:** `4`
**Salida:**
```
   *
  ***
 *****
*******
 *****
  ***
   *
```

---

### Ejercicio 446: Función que retorna si una palabra es palíndromo
**Enunciado:** Define una función `es_palindromo(cadena)` que regresa True/False. La cadena puede tener espacios y mayúsculas/minúsculas, pero debes ignorarlos (usa lower() y replace(" ", "")). No uses slicing [::-1], implementa con dos índices (inicio, fin) que avanzan hacia el centro. Pruébala.
**Entrada:** `"Anita lava la tina"`
**Salida:** `True`
**Entrada:** `"Python"`
**Salida:** `False`

---

### Ejercicio 447: Función que retorna el MCD de tres números
**Enunciado:** Define una función `mcd_tres(a, b, c)` que regresa el MCD de tres números usando la función del ejercicio 430 (mcd(a,b)) y luego mcd(resultado, c). Pruébala.
**Entrada:** `48`, `18`, `30`
**Salida:** `MCD de 48, 18, 30: 6`

---

### Ejercicio 448: Procedimiento que muestra la tabla de multiplicar de varios números
**Enunciado:** Define un procedimiento `tabla_multiplos(numeros)` que NO regresa valor, recibe una lista de números y para cada uno imprime su tabla de multiplicar del 1 al 10 con un separador entre tablas. Usa for anidados. Pruébalo con [3, 5, 7].
**Entrada:** `[3, 5, 7]`
**Salida:** (tablas de 3, 5 y 7 con separadores)

---

### Ejercicio 449: Función que retorna el n-ésimo número triangular
**Enunciado:** Un número triangular es la suma de los primeros n números naturales (1 + 2 + ... + n). Define una función `triangular(n)` que regresa el n-ésimo número triangular. Implementa con for y acumulador y también con fórmula n*(n+1)/2. Prueba ambas e indica cuál es más eficiente.
**Entrada:** `7`
**Salida:** `Triangular(7) = 28 (fórmula: 7*8/2 = 28)`

---

### Ejercicio 450: Función que retorna cuántos divisores tiene un número
**Enunciado:** Define una función `contar_divisores(n)` que regresa la cantidad de divisores positivos de n (incluyendo 1 y n). Usa for con range(1, n+1) y % para verificar divisibilidad. Pruébala.
**Entrada:** `28`
**Salida:** `28 tiene 6 divisores: 1, 2, 4, 7, 14, 28`

---

## BLOQUE 5 · T13-T14: TUPLAS, DICCIONARIOS, COMBINACIONES

### Ejercicio 451: Diccionario de estudiantes con tuplas de calificaciones
**Enunciado:** Crea un diccionario donde cada clave es un nombre de estudiante y cada valor es una tupla de 3 calificaciones (matemáticas, ciencias, lenguaje). Calcula: promedio de cada estudiante (usando una función), estudiante con mejor promedio, y materia con mejor promedio general (promedio de las calificaciones de cada materia). Usa diccionario, tuplas, funciones y ciclos.
**Entrada:** `{"Ana": (9, 8, 7), "Luis": (10, 9, 8), "Maria": (7, 6, 8)}`
**Salida:** `Promedios: Ana 8.0, Luis 9.0, Maria 7.0 | Mejor promedio: Luis (9.0) | Mejor materia: Matemáticas (promedio 8.67)`

---

### Ejercicio 452: Diccionario de productos con tuplas de precios
**Enunciado:** Crea un diccionario de productos donde cada valor es una tupla (precio_compra, precio_venta, cantidad). Calcula: ganancia por producto (precio_venta - precio_compra) * cantidad, ganancia total, producto con mayor ganancia. Define funciones: `calcular_ganancias(inventario)` que regresa un diccionario con las ganancias.
**Entrada:** `{"Laptop": (8000, 12000, 5), "Mouse": (150, 300, 50), "Teclado": (400, 700, 30)}`
**Salida:** `Ganancias: Laptop $20000, Mouse $7500, Teclado $9000 | Ganancia total: $36500 | Mayor ganancia: Laptop`

---

### Ejercicio 453: Conteo de palabras en texto con diccionario de frecuencias
**Enunciado:** Pide un párrafo largo. Cuenta la frecuencia de cada palabra usando un diccionario (clave = palabra en minúsculas, valor = conteo). Ignora signos de puntuación (, . ! ? : ;). Muestra las palabras ordenadas por frecuencia descendente (usando sorted() con key=lambda). Muestra las 5 palabras más frecuentes.
**Entrada:** `El gato duerme. El perro juega. El gato duerme. El perro corre.`
**Salida:** `Frecuencias: el: 4, gato: 2, duerme: 2, perro: 2, juega: 1, corre: 1 | Top 5: el, gato, duerme, perro, juega`

---

### Ejercicio 454: Sistema de agenda con diccionario de contactos y tuplas de información
**Enunciado:** Crea un diccionario donde cada clave es un nombre y el valor es una tupla (teléfono, correo, edad). Permite: agregar contacto (con input), buscar contacto por nombre (con error KeyError controlado con try-except), mostrar todos los contactos (con ciclo for sobre items()), y actualizar el teléfono de un contacto existente. Define funciones para cada operación.
**Entrada:** (interactivo con agregar, buscar, actualizar)
**Salida:** (mostrará los contactos y los resultados de las operaciones)

---

### Ejercicio 455: Diccionario de ventas por región con tuplas de meses
**Enunciado:** Crea un diccionario donde cada clave es una región y el valor es una tupla de 3 meses (ventas enero, febrero, marzo). Calcula: total por región, región con mayor venta, mes con mayor venta total, promedio mensual por región. Usa funciones y diccionarios.
**Entrada:** `{"Norte": (15000, 12000, 18000), "Sur": (10000, 14000, 11000), "Occidente": (12000, 13000, 15000)}`
**Salida:** `Ventas totales: Norte $45000, Sur $35000, Occidente $40000 | Región más vendida: Norte | Mejor mes: Marzo ($44000) | Promedio mensual Norte: $15000`

---

### Ejercicio 456: Agregación de tuplas en diccionario de listas
**Enunciado:** Dado un diccionario donde las claves son nombres de materias y los valores son listas de tuplas (nombre_estudiante, calificación). Calcula: promedio de cada materia, mejor estudiante de cada materia, materia con mayor promedio general. Usa funciones: `estadisticas_materia(materia, registros)` que regresa diccionario con stats.
**Entrada:** `{"Matemáticas": [("Ana", 9), ("Luis", 10), ("Maria", 7)], "Ciencias": [("Ana", 8), ("Luis", 9), ("Pedro", 6)]}`
**Salida:** `Matemáticas: promedio 8.67, mejor Luis | Ciencias: promedio 7.67, mejor Luis | Mejor materia: Matemáticas (8.67)`

---

### Ejercicio 457: Diccionario de inventario con tuplas inmutables
**Enunciado:** Crea un diccionario de inventario donde cada valor es una tupla (producto, precio, stock_minimo, stock_actual). Implementa: función `verificar_stock(inventario)` que regresa lista de productos con stock < stock_minimo; función `agregar_producto(inventario, nombre, precio, stock)` que agrega un nuevo producto; función `actualizar_stock(inventario, nombre, nueva_cantidad)` que actualiza el stock reemplazando la tupla. Usa try-except para manejar productos inexistentes.
**Entrada:** (agregar productos, verificar, actualizar)
**Salida:** (lista de productos con stock bajo, confirmación de actualizaciones)

---

### Ejercicio 458: Conversor de tupla a diccionario de índices
**Enunciado:** Dada una tupla de palabras, crea un diccionario donde cada clave es la palabra y el valor es su posición (índice) en la tupla. Si una palabra se repite, el valor es una lista de posiciones. Usa for con enumerate. Muestra el diccionario resultante.
**Entrada:** `("manzana", "banana", "manzana", "naranja", "banana")`
**Salida:** `{'manzana': [0, 2], 'banana': [1, 4], 'naranja': [3]}`

---

### Ejercicio 459: Diccionario con tuplas como claves
**Enunciario:** Crea un diccionario donde las claves son tuplas de (ciudad, pais) y los valores son la población. Permite agregar ciudades, buscar por ciudad y país, y mostrar todas las ciudades ordenadas por población descendente (usando sorted con key). No puedes usar tuplas mutables como claves (debes usar tuplas, no listas).
**Entrada:** `{"México": 126, "España": 47}` → `{(México, América): 126, (Madrid, Europa): 47}` 
**Salida:** (diccionario ordenado por población)

---

### Ejercicio 460: Función que retorna estadísticas de tupla de números
**Enunciado:** Define una función `stats_tupla(t)` que regresa un diccionario con: suma, promedio, min, max, cantidad_pares, cantidad_impares, longitud. Implementa usando for sobre la tupla (no convierte a lista). Pruébala con tuplas de diferentes longitudes.
**Entrada:** `(5, 3, 8, 1, 9, 4, 7)`
**Salida:** `{'suma': 37, 'promedio': 5.29, 'min': 1, 'max': 9, 'pares': 2, 'impares': 5, 'longitud': 7}`

---

### Ejercicio 461: Compresión de lista a diccionario con condiciones
**Enunciado:** Dada una lista de números, crea un diccionario donde cada clave es el número y el valor es "par" o "impar" según corresponda. Luego, crea otro diccionario solo con los números pares y su cuadrado. Usa comprensión de diccionario o ciclo for. Muestra ambos diccionarios.
**Entrada:** `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`
**Salida:** `Tipo: {1: 'impar', 2: 'par', ...} | Cuadrado pares: {2: 4, 4: 16, 6: 36, 8: 64, 10: 100}`

---

### Ejercicio 462: Diferencia entre tuplas y listas en funciones
**Enunciado:** Define una función `procesar_secuencia(seq)` que: cuente cuántos elementos son divisibles entre 3, muestre los elementos en orden inverso (usando reversed o slicing si es lista, o convertir a lista si es tupla), y retorne el número de elementos. Llama a la función primero con una lista y luego con una tupla, muestra las diferencias.
**Entrada:** lista `[3, 6, 9, 12, 15]`, tupla `(3, 6, 9, 12, 15)`
**Salida:** (para lista: puede modificar, para tupla: no puede modificar, pero el resultado es igual)

---

### Ejercicio 463: Diccionario de historial de compras con tuplas de fecha
**Enunciado:** Crea un diccionario donde cada clave es un cliente y el valor es una tupla (fecha_compra, monto, producto). Implementa funciones: `agregar_compra(historial, cliente, fecha, monto, producto)`, `total_compras_cliente(historial, cliente)`, `cliente_mayor_gastador(historial)`, `compras_en_rango(historial, fecha_inicio, fecha_fin)`. Usa string de fecha formato "DD/MM/AAAA" (compara como string).
**Entrada:** (varias compras de diferentes clientes)
**Salida:** (total por cliente, mayor gastador, filtros por fecha)

---

### Ejercicio 464: Conversión de lista de tuplas a diccionario
**Enunciado:** Dada una lista de tuplas (nombre, edad, ciudad), crea un diccionario donde la clave es el nombre y el valor es una tupla (edad, ciudad). Si hay nombres duplicados, el último sobrescribe al anterior. Muestra el diccionario resultante y luego imprime los nombres con edad >= 30.
**Entrada:** `[("Ana", 25, "México"), ("Luis", 30, "España"), ("Ana", 35, "EE.UU.")]`
**Salida:** `Diccionario: {'Ana': (35, 'EE.UU.'), 'Luis': (30, 'España')} | Mayores de 30: Ana (35, EE.UU.), Luis (30, España)`

---

### Ejercicio 465: Diccionario de matriz de adyacencia (grafo simple)
**Enunciado:** Crea un diccionario que represente un grafo dirigido donde las claves son nodos (letra) y los valores son tuplas de nodos conectados. Por ejemplo: {"A": ("B", "C"), "B": ("D",), "C": ("D",), "D": ()}. Implementa funciones: `hay_camino(grafo, inicio, fin)` que busca si existe camino (usando BFS con cola simple en lista), `grado_entrada(grafo, nodo)`, `grado_salida(grafo, nodo)`. Usa diccionarios y tuplas.
**Entrada:** grafo definido arriba, inicio "A", fin "D"
**Salida:** `Hay camino de A a D: True | Grado salida A: 2 | Grado entrada D: 2`

---

### Ejercicio 466: Tupla de tuplas como matriz inmutable
**Enunciado:** Dada una tupla de tuplas que representa una matriz 3x3 inmutable: ((1, 2, 3), (4, 5, 6), (7, 8, 9)). Implementa funciones: `suma_fila(matriz, i)` que regresa la suma de la fila i, `suma_columna(matriz, j)` que regresa la suma de la columna j, `diagonal_principal(matriz)` que regresa una tupla con los elementos de la diagonal. Prueba con la matriz dada.
**Entrada:** `((1, 2, 3), (4, 5, 6), (7, 8, 9))`
**Salida:** `Suma fila 0: 6 | Suma columna 1: 15 | Diagonal: (1, 5, 9)`

---

### Ejercicio 467: Diccionario de votaciones por distrito
**Enunciado:** Crea un diccionario donde cada clave es un distrito y el valor es una tupla (votos_candidato1, votos_candidato2, votos_candidato3). Implementa funciones: `total_votos_elegidos(distrito)`, `ganador_por_distrito(distrito)`, `distrito_con_mas_votos_total(distritos)`, `porcentaje_candidato1(distrito)`. Valida que los votos no sean negativos (con try-except). Muestra resultados.
**Entrada:** `{"A": (150, 200, 50), "B": (180, 120, 100), "C": (80, 80, 40)}`
**Salida:** `Distrito A: Ganador Candidato 2 (200 votos, 50%) | Distrito B: Ganador Candidato 1 (180 votos, 45%) | Distrito C: Empate entre 1 y 2 | Distrito con más votos: B (400)`

---

### Ejercicio 468: Tupla de diccionarios para datos anidados
**Enunciado:** Crea una tupla de 3 diccionarios, cada uno representando un estudiante con nombre, edad, y una lista de calificaciones. Implementa funciones: `promedio_estudiante(estudiante)` que regresa el promedio, `estudiante_mayor(estudiantes)` que regresa el estudiante con mayor edad, `agregar_calificacion(estudiantes, nombre, nueva_calificacion)` que regresa una nueva tupla con la calificación agregada (la tupla es inmutable, pero los diccionarios sí se pueden modificar). Prueba.
**Entrada:** (tupla de 3 diccionarios)
**Salida:** (promedios, estudiante mayor, tupla modificada)

---

### Ejercicio 469: Empaquetado y desempaquetado avanzado
**Enunciado:** Dadas tres tuplas: t1 = (1, 2, 3), t2 = (4, 5), t3 = (6, 7, 8, 9). Usa desempaquetado para asignar los primeros 2 elementos de cada tupla a variables (a, b = t1[:2], etc.) y los elementos restantes a una lista. Combina las tres listas restantes en una sola lista. Muestra el resultado.
**Entrada:** (tuplas dadas)
**Salida:** `Primeros elementos: a=1,b=2; c=4,d=5; e=6,f=7 | Restantes combinadas: [3, 5, 8, 9]`

---

### Ejercicio 470: Diccionario de frecuencia de caracteres con tupla de conteo
**Enunciado:** Dado un string, crea un diccionario donde cada clave es un carácter y el valor es una tupla (frecuencia, primera_posicion, última_posicion). Usa for con enumerate para registrar posiciones. Muestra el diccionario y luego las 3 letras más frecuentes con su información.
**Entrada:** `banana`
**Salida:** `{'b': (1, 0, 0), 'a': (3, 1, 5), 'n': (2, 2, 4)} | Top 3: a: 3 veces, n: 2 veces, b: 1 vez`

---

## BLOQUE 6 · T15-T16: EXCEPCIONES + STRINGS, INTEGRACIÓN AVANZADA

### Ejercicio 471: Validador de expresiones matemáticas con excepciones por tipo
**Enunciado:** Pide una expresión matemática simple (ej. "10 + 5", "8 / 0", "abc + 5"). Evalúa con split() y try-except manejando: ValueError (operandos no numéricos), ZeroDivisionError, TypeError (operador desconocido). Muestra el resultado o el error específico. Además, valida que el operador sea uno de +, -, *, /, //, %, **.
**Entrada:** `10 / 0`
**Salida:** `Error: División entre cero`
**Entrada:** `5 % 2`
**Salida:** `5 % 2 = 1`
**Entrada:** `abc + 5`
**Salida:** `Error: Los operandos deben ser números`

---

### Ejercicio 472: Bloque try-except-else-finally completo
**Enunciado:** Implementa un programa que pida dos números y los divida. Usa try-except para ValueError y ZeroDivisionError, un bloque else que muestre "División exitosa" con el resultado, y un bloque finally que siempre imprima "Operación completada". Pide números inválidos, división por cero, y números válidos para probar cada caso.
**Entrada:** `10`, `0`
**Salida:** `Error: No se puede dividir entre cero | Operación completada`
**Entrada:** `10`, `2`
**Salida:** `División exitosa: 5.0 | Operación completada`

---

### Ejercicio 473: Excepción personalizada para rango de edad
**Enunciado:** Define una excepción personalizada `EdadInvalida(Exception)` que toma un mensaje específico. Define una función `validar_edad(edad)` que: si edad < 0 o edad > 120, lanza EdadInvalida con mensaje "La edad debe estar entre 0 y 120 años"; si edad < 18, lanza EdadInvalida con "Debes ser mayor de edad"; si es válida, regresa True. Prueba con diferentes valores.
**Entrada:** `-5`
**Salida:** `Error: La edad debe estar entre 0 y 120 años`
**Entrada:** `15`
**Salida:** `Error: Debes ser mayor de edad`
**Entrada:** `25`
**Salida:** `✓ Edad válida`

---

### Ejercicio 474: Manejo de múltiples excepciones en ciclo de entrada
**Enunciado:** Crea un ciclo que pida 5 números enteros positivos. Para cada uno, usa try-except para capturar ValueError (input no entero) y captura también la excepción general Exception como respaldo. Si el número es negativo, lanza ValueError manualmente con raise y captúralo. Muestra un resumen al final con los números válidos y sus promedios. Almacena los errores en una lista.
**Entrada:** `10`, `abc`, `-5`, `20`, `30`
**Salida:** `Números válidos: [10, 20, 30] | Promedio: 20.0 | Errores: ['Entrada no entera: abc', 'Número negativo: -5']`

---

### Ejercicio 475: Validador de correo electrónico con excepciones
**Enunciado:** Define una excepción `CorreoInvalido(Exception)` con diferentes mensajes según el error: "Falta el símbolo @", "Falta el dominio", "El dominio no es válido (debe tener punto)", "El usuario está vacío". Define una función `validar_correo(correo)` que lanza la excepción correspondiente según la validación fallida. Pide un correo y valida con try-except. Usa string methods: find, split, in.
**Entrada:** `usuarionodominio`
**Salida:** `Error: Falta el símbolo @`
**Entrada:** `usuario@`
**Salida:** `Error: Falta el dominio`
**Entrada:** `usuario@dominio`
**Salida:** `Error: El dominio no es válido (debe tener punto)`
**Entrada:** `usuario@dominio.com`
**Salida:** `✓ Correo válido`

---

### Ejercicio 476: Procesador de texto con excepciones para caracteres especiales
**Enunciado:** Pide un texto y procesa las siguientes operaciones en un bloque try-except: 1) Convierte a mayúsculas, 2) Cuenta palabras con split(), 3) Busca una palabra clave dada (con find(), si no existe muestra -1), 4) Reemplaza una palabra por otra, 5) Elimina caracteres especiales (solo deja letras, números, espacios). Define una excepción `TextoProcesadoVacio` si el texto resultante está vacío. Muestra resultados paso a paso.
**Entrada:** `Hola, Mundo! 123`
**Salida:** (muestra cada etapa del procesamiento)

---

### Ejercicio 477: Excepciones en funciones matemáticas
**Enunciado:** Define funciones matemáticas que lanzan excepciones: `dividir(a, b)` lanza ZeroDivisionError si b=0; `raiz_cuadrada(n)` lanza ValueError si n<0; `logaritmo(n)` lanza ValueError si n<=0. Crea un menú while que pida operación y parámetros, ejecuta la función con try-except para cada caso. Muestra resultados o errores controlados.
**Entrada:** `raiz_cuadrada`, `-4`
**Salida:** `Error: No se puede calcular raíz de número negativo`
**Entrada:** `dividir`, `10`, `0`
**Salida:** `Error: División entre cero`

---

### Ejercicio 478: Sistema de login con bloqueo por intentos fallidos
**Enunciado:** Define usuario y contraseña válidos. Pide al usuario ingresar sus credenciales. Valida: si usuario incorrecto → excepción UsuarioNoEncontrado, si contraseña incorrecta → excepción ContraseñaIncorrecta. Si falla 3 veces, lanza excepción CuentaBloqueada y termina. Muestra número de intento en cada fallo. Usa excepciones personalizadas y try-except.
**Entrada:** `admin`, `123`, `admin`, `admin`, `admin`, `admin2024`
**Salida:** `Intento 1: Error - Contraseña incorrecta | Intento 2: Error - Contraseña incorrecta | Intento 3: ¡Cuenta bloqueada! Demasiados intentos fallidos`

---

### Ejercicio 479: Procesamiento de strings con validaciones y excepciones
**Enunciado:** Pide una frase. Realiza: 1) Verifica que no esté vacía (si está vacía, lanza ValueError con raise), 2) Convierte a mayúsculas, 3) Elimina espacios duplicados (más de un espacio seguidos) usando while y replace, 4) Cuenta palabras, 5) Si la frase tiene más de 50 palabras, lanza excepción FraseDemasiadoLarga. Muestra el resultado final. Usa try-except para manejar las excepciones.
**Entrada:** `   Hola    mundo   Python   `
**Salida:** `Frase procesada: "HOLA MUNDO PYTHON" | Palabras: 3`

---

### Ejercicio 480: Función que retorna y maneja excepciones en una sola función
**Enunciado:** Define una función `procesar_numero(n)` que: si n es negativo, lanza ValueError con "El número debe ser positivo"; si n es 0, lanza ValueError con "El número no puede ser cero"; si n es flotante, lo redondea y continúa; si es entero, lo devuelve. Crea un bloque try-except que llame a la función 5 veces con diferentes valores y capture los errores. Muestra resultados y errores en un diccionario.
**Entrada:** `5`, `-3`, `0`, `3.7`, `10`
**Salida:** `Resultados: {5: 5, -3: Error(Valor negativo), 0: Error(Cero), 3.7: 4, 10: 10}`

---

### Ejercicio 481: Validación de expresiones con excepciones encadenadas
**Enunciado:** Pide una expresión en formato "NÚMERO1 OPERADOR NÚMERO2". Valida: primero separa los partes; si no hay 3 partes, lanza ValueError. Luego valida que número1 y número2 sean numéricos (int o float), si no, lanza ValueError. Luego valida el operador (debe ser +, -, *, /, //, %, **), si no, lanza ValueError. Finalmente, evalúa la operación y maneja ZeroDivisionError. Usa try-except anidados o una sola función con múltiples validaciones con raise.
**Entrada:** `10 + abc`
**Salida:** `Error: El segundo operando no es numérico`
**Entrada:** `10 / 0`
**Salida:** `Error: División entre cero`
**Entrada:** `10 ** 3`
**Salida:** `Resultado: 1000`

---

### Ejercicio 482: Procesador de texto con excepción por palabra prohibida
**Enunciado:** Define una lista de palabras "prohibidas" (ej. ["malo", "feo", "odio"]). Pide un texto. Si el texto contiene alguna palabra prohibida (verifica con if palabra in texto.split()), lanza una excepción PalabraProhibida con el mensaje "Texto contiene palabra prohibida: [palabra]". Si no hay palabras prohibidas, procesa el texto (mayúsculas, conteo de palabras, reemplazo de espacios). Usa try-except.
**Entrada:** `Esto es algo malo`
**Salida:** `Error: Texto contiene palabra prohibida: malo`
**Entrada:** `Esto es algo bueno`
**Salida:** `Texto procesado: "ESTO ES ALGO BUENO" | Palabras: 4`

---

### Ejercicio 483: Función de lectura de datos con manejo robusto de excepciones
**Enunciado:** Define una función `leer_lista_numeros(cantidad)` que pide al usuario una cantidad de números y devuelve una lista de floats válidos. La función usa un ciclo while con try-except para manejar ValueError y sigue pidiendo hasta obtener un número válido. Si el usuario escribe "fin", rompe el ciclo y regresa la lista parcial. Prueba con varios casos. Además, define una función `procesar_lista(lista)` que calcula suma, promedio, máximo y mínimo.
**Entrada:** (ingreso de números con errores intercalados)
**Salida:** (lista procesada con estadísticas)

---

### Ejercicio 484: Sistema de conversión de temperaturas con validaciones
**Enunciado:** Pide una temperatura y la unidad de origen (C, F, K). Convierte a las otras dos unidades. Fórmulas: C→F: F = C*9/5+32; C→K: K = C+273.15; F→C: C = (F-32)*5/9; F→K: K = (F-32)*5/9+273.15; K→C: C = K-273.15; K→F: F = (K-273.15)*9/5+32. Valida: temperatura no puede ser menor a -273.15°C (absoluto cero) → lanza ValueError. Si la unidad no es válida, lanza ValueError con mensaje "Unidad no válida". Usa try-except para cada conversión.
**Entrada:** `32`, `F`
**Salida:** `32°F = 0.0°C = 273.15K`

---

### Ejercicio 485: Validador de contraseña con múltiples excepciones por regla
**Enunciado:** Define una excepción personalizada `ContraseñaInvalida(Exception)` que toma un mensaje específico. Define una función `validar_contraseña(contraseña)` que revisa reglas en orden y lanza la excepción con el primer error encontrado: 1) longitud < 8 → "Debe tener al menos 8 caracteres"; 2) sin mayúscula → "Debe tener al menos una mayúscula"; 3) sin minúscula → "Debe tener al menos una minúscula"; 4) sin dígito → "Debe tener al menos un dígito"; 5) sin carácter especial (!@#$%^&*) → "Debe tener al menos un carácter especial". Si pasa todas, regresa True. Prueba con diferentes contraseñas.
**Entrada:** `abc123`
**Salida:** `Error: Debe tener al menos 8 caracteres`
**Entrada:** `Abcdefg1`
**Salida:** `Error: Debe tener al menos un carácter especial`
**Entrada:** `Abcdefg1!`
**Salida:** `✓ Contraseña válida`

---

### Ejercicio 486: Procesamiento de archivo de texto simulado con excepciones
**Enunciado:** Simula la lectura de un archivo de texto donde cada línea contiene: nombre, edad, ciudad (separados por comas). Si una línea no tiene el formato correcto, lanza ValueError con "Línea mal formateada". Si la edad no es un entero, lanza ValueError con "Edad no es número". Si el nombre está vacío, lanza ValueError con "Nombre vacío". Procesa varias líneas y almacena los datos válidos en un diccionario (clave = nombre, valor = tupla (edad, ciudad)). Muestra el diccionario resultante.
**Entrada:** (varias líneas simuladas)
**Salida:** (diccionario de personas válidas)

---

### Ejercicio 487: Excepción por tipo de dato incorrecto en función
**Enunciado:** Define una función `procesar_datos(datos)` que espera una lista de números. Si recibe algo que no es una lista, lanza TypeError con "Se esperaba una lista". Si la lista contiene elementos que no son números (int o float), lanza TypeError con "La lista debe contener solo números". Si la lista está vacía, lanza ValueError con "La lista no puede estar vacía". Implementa la función y prueba con diferentes casos. Define también una función que procesa una tupla de la misma manera.
**Entrada:** `[1, 2, 3, "a"]`
**Salida:** `Error: La lista debe contener solo números`

---

### Ejercicio 488: Conteo de palabras en párrafos múltiples con excepciones
**Enunciado:** Pide 3 párrafos de texto. Para cada párrafo: cuenta palabras, encuentra la palabra más larga, y verifica si está vacío (si está vacío, lanza excepción ParrafoVacio). Si el párrafo tiene más de 100 palabras, lanza FraseLargaExcesiva. Muestra resultados de los 3 párrafos en un diccionario. Usa try-except para manejar las excepciones de cada párrafo.
**Entrada:** (3 párrafos de diferentes longitudes)
**Salida:** (estadísticas de cada párrafo y manejo de excepciones)

---

### Ejercicio 489: Calculadora con manejo de operadores y excepciones por tipo
**Enunciado:** Implementa una calculadora que pida:tipo de operación (suma, resta, multiplicación, división, potencia, módulo, raíz cuadrada, logaritmo) y los operandos necesarios. Para raíz y logaritmo, un solo operando. Usa try-except para: ValueError (operandos no numéricos), ZeroDivisionError, ValueError (raíz de negativo), ValueError (logaritmo de negativo o cero). Muestra el resultado o el error específico. Implementa como funciones separadas.
**Entrada:** (operaciones variadas)
**Salida:** (resultados y errores controlados)

---

### Ejercicio 490: Sistema de registro de estudiantes con excepciones
**Enunciado:** Crea un sistema que permita registrar estudiantes (nombre, edad, calificación). Crea excepciones: NombreVacio (si nombre está vacío), EdadInvalida (si edad < 0 o > 120 o no es entero), CalificacionInvalida (si calificación < 0 o > 10 o no es número). Define una función `registrar_estudiante(estudiantes, nombre, edad, calificacion)` que agrega a un diccionario si es válido, o lanza la excepción correspondiente. Implementa un menú while para agregar, mostrar y buscar estudiantes. Usa try-except en el menú.
**Entrada:** (registro de estudiantes)
**Salida:** (diccionario de estudiantes registrados con manejo de errores)

---

### Ejercicio 491: Función que retorna resultado o excepción controlada
**Enunciado:** Define una función `dividir_seguro(a, b)` que: si b es 0, retorna la tupla (False, "Error: división entre cero"); si a o b no son números, retorna (False, "Error: operandos no numéricos"); si todo es válido, retorna (True, a/b). Crea un programa que use esta función 5 veces con diferentes casos y muestre los resultados. Implementa una segunda versión que use excepciones y retorne solo el resultado o lance excepción, y compare ambos enfoques.
**Entrada:** (5 divisiones variadas)
**Salida:** (resultados con enfoque de retorno vs excepción)

---

### Ejercicio 492: Procesamiento de string con excepciones por posición
**Enunciado:** Pide un string. Define una función `obtener_caracter(s, posicion)` que: si posicion < 0 o >= len(s), lanza IndexError con "Posición fuera de rango"; si s está vacío, lanza ValueError con "String vacío"; si no, retorna el carácter en esa posición. Define otra función `reemplazar_caracter(s, posicion, nuevo_caracter)` que usa la anterior para validar, luego reemplaza y retorna el nuevo string. Usa try-except para cada caso. Prueba con posiciones inválidas, string vacío, y casos válidos.
**Entrada:** `Hola`, posición `-1`
**Salida:** `Error: Posición fuera de rango`
**Entrada:** `Hola`, posición `5`
**Salida:** `Error: Posición fuera de rango`
**Entrada:** `Hola`, posición `0`, nuevo `M`
**Salida:** `Mola`

---

### Ejercicio 493: Validación de fecha con excepciones
**Enunciado:** Pide día, mes y año. Define una función `validar_fecha(dia, mes, ano)` que: si año < 1900 o año > 2100, lanza ValueError con "Año fuera de rango"; si mes < 1 o mes > 12, lanza ValueError con "Mes inválido"; si día < 1 o día > 31, lanza ValueError con "Día inválido"; además verifica días por mes (febrero con 28 o 29 si año bisiesto, meses de 30 días). Define función auxiliar `es_bisiesto(ano)`. Si la fecha es válida, retorna la fecha formateada como string "DD/MM/AAAA". Prueba con fechas inválidas y bisiestas.
**Entrada:** `29`, `2`, `2024`
**Salida:** `29/02/2024 (año bisiesto) ✓`
**Entrada:** `29`, `2`, `2023`
**Salida:** `Error: Día inválido para el mes`

---

### Ejercicio 494: Función de transformación de texto con validaciones y excepciones
**Enunciado:** Define una función `transformar_texto(texto, operacion)` que recibe un texto y una operación (mayusculas, minusculas, invertir, contar_palabras, eliminar_espacios). Si el texto está vacío, lanza ValueError con "Texto vacío". Si la operación no es válida, lanza ValueError con "Operación no válida". Implementa cada operación dentro de la función con if/elif. Retorna el resultado. Define también una función `reemplazar_texto(texto, viejo, nuevo)` que reemplaza todas las ocurrencias, pero si viejo está vacío, lanza ValueError. Prueba con diferentes textos y operaciones.
**Entrada:** `Hola Mundo`, `mayusculas`
**Salida:** `HOLA MUNDO`
**Entrada:** `Hola Mundo`, `invertir`
**Salida:** `odnuM aloH`
**Entrada:** `""`, `mayusculas`
**Salida:** `Error: Texto vacío`

---

### Ejercicio 495: Sistema de inventario con excepciones por producto inexistente
**Enunciado:** Crea un diccionario de inventario con productos (clave) y cantidades (valor). Define funciones: `vender(inventario, producto, cantidad)` que reduce el stock, pero si el producto no existe lanza KeyError con "Producto no encontrado"; si la cantidad a vender excede el stock, lanza ValueError con "Stock insuficiente"; si la cantidad no es positiva, lanza ValueError con "Cantidad debe ser positiva". Si todo ok, actualiza el stock y retorna el nuevo stock. Define también `agregar(inventario, producto, cantidad)` que agrega o actualiza. Implementa un menú interactivo. Usa try-except.
**Entrada:** (operaciones de venta y agregar)
**Salida:** (inventario actualizado con manejo de errores)

---

### Ejercicio 496: Procesamiento de lista con funciones y excepciones
**Enunciado:** Define funciones que procesan una lista de números y pueden lanzar excepciones: `promedio(lista)` lanza ValueError si lista está vacía; `maximo(lista)` lanza ValueError si lista está vacía; `minimo(lista)` lanza ValueError si lista está vacía; `ordenar(lista)` lanza TypeError si hay elementos de tipos diferentes (no todos int o float). Implementa un menú que permita probar cada función con diferentes listas e indique los errores. Usa try-except para manejar las excepciones.
**Entrada:** (listas de diferentes tipos y longitudes)
**Salida:** (resultados y errores controlados)

---

### Ejercicio 497: Conversor de strings con escape de caracteres
**Enunciado:** Pide un string que puede contener caracteres especiales (saltos de línea \n, tabuladores \t, comillas). Define una función `escape_string(s)` que reemplaza \n por "\\n" (literal), \t por "\\t", y comillas dobles por \\". Define otra función `unescape_string(s)` que hace lo inverso. Implementa con replace(). Si el string de entrada es None o vacío, lanza ValueError. Usa try-except. Prueba con strings que contienen estos caracteres.
**Entrada:** `Hola\nMundo\t2024`
**Salida:** `Hola\\nMundo\\t2024` (versión escape)
**Entrada:** `Hola\\nMundo\\t2024` (versión unescape)
**Salida:** `Hola\nMundo\t2024`

---

### Ejercicio 498: Sistema de evaluación de expresiones con excepciones
**Enunciado:** Pide una expresión matemática como string (ej. "10 + 5 * 2", "(3 + 4) / 0"). Implementa una función `evaluar_expresion(expresion)` que: primero valida que solo contenga caracteres válidos (dígitos, +, -, *, /, //, %, **, (, ), espacios); si hay caracteres inválidos, lanza ValueError con "Caracteres no válidos". Luego intenta evaluar con eval() en un bloque try-except manejando ZeroDivisionError, SyntaxError (excepción de sintaxis), NameError (si hay variables). Retorna el resultado o el error. Implementa validación rigurosa de la expresión antes de evaluar.
**Entrada:** `10 + 5 * 2`
**Salida:** `Resultado: 20`
**Entrada:** `10 / 0`
**Salida:** `Error: División entre cero`
**Entrada:** `10 + `
**Salida:** `Error: Sintaxis inválida`

---

### Ejercicio 499: Función de partición de string con validaciones
**Enunciado:** Define una función `particionar_texto(texto, separador, max_partes)` que divide el texto por el separador y retorna una lista de partes. Si el texto está vacío, lanza ValueError con "Texto vacío". Si el separador está vacío, lanza ValueError con "Separador vacío". Si max_partes es negativo, lanza ValueError con "max_partes debe ser positivo". Si max_partes > 0, usa split(separador, max_partes). Si no hay partes (lista vacía), lanza ValueError con "No se generaron partes". Implementa y prueba con diferentes casos. Usa try-except para cada error.
**Entrada:** `a,b,c,d,e`, `,`, `3`
**Salida:** `['a', 'b', 'c,d,e']`

---

### Ejercicio 500: Sistema de log de errores con excepciones y strings
**Enunciado:** Implementa un sistema de registro de errores donde cada error se guarda en un archivo de texto (simulado con una lista) con formato: TIMESTAMP | TIPO_ERROR | MENSAJE. Define una función `log_error(tipo, mensaje)` que agrega una entrada a la lista de logs. Define excepciones personalizadas para diferentes tipos de errores. Implementa un programa que genere diferentes errores, los capture, y los registre en la lista de logs. Al final, muestra el reporte de logs ordenado por timestamp (usa datetime para generar timestamps). Implementa funciones: `generar_log_error`, `mostrar_logs`, `buscar_logs_por_tipo`.
**Entrada:** (generación de varios errores)
**Salida:** (reporte de logs ordenado con búsqueda por tipo)





## BLOQUE 1 · ESTRUCTURAS ANIDADAS COMPLEJAS + DICIONARIOS (501–525)

### Ejercicio 501: Inventario de tienda con categorías anidadas
**Enunciado:** Se tiene un diccionario anidado que representa el inventario de una tienda, donde cada categoría contiene una lista de productos, y cada producto es un diccionario con `nombre`, `precio`, `cantidad` y `stock_minimo`. Escribe una función `reporte_inventario(inventario)` que:
1. Recorra todas las categorías y productos.
2. Identifique los productos con `cantidad <= stock_minimo` (stock crítico).
3. Calcule el valor total del inventario (suma de `precio * cantidad` de todos los productos).
4. Agrupe los productos críticos por categoría y los muestre en un reporte formateado.
5. Retorne una tupla `(productos_criticos, valor_total)` donde `productos_criticos` es un diccionario `{categoria: [lista de nombres]}`.

**Entrada:**
```python
inventario = {
    "Electrónica": [
        {"nombre": "Mouse", "precio": 50, "cantidad": 3, "stock_minimo": 5},
        {"nombre": "Teclado", "precio": 120, "cantidad": 10, "stock_minimo": 3},
    ],
    "Papelería": [
        {"nombre": "Cuaderno", "precio": 25, "cantidad": 2, "stock_minimo": 10},
        {"nombre": "Bolígrafo", "precio": 8, "cantidad": 50, "stock_minimo": 20},
    ],
}
```
**Salida:**
```
=== REPORTE DE INVENTARIO ===
Categoría: Electrónica
  Mouse — Stock crítico: 3 (mínimo: 5)
  Teclado — Stock OK: 10 (mínimo: 3)
Categoría: Papelería
  Cuaderno — Stock crítico: 2 (mínimo: 10)
  Bolígrafo — Stock OK: 50 (mínimo: 20)

Artículos con stock crítico:
  Electrónica: Mouse
  Papelería: Cuaderno

Valor total del inventario: $2,050
```
`reporte_inventario(inventario)` retorna `({"Electrónica": ["Mouse"], "Papelería": ["Cuaderno"]}, 2050)`

---

### Ejercicio 502: Matriz de adyacencia a lista de adyacencia
**Enunciado:** Dada una matriz de adyacencia (lista de listas de 0s y 1s) que representa un grafo no dirigido, escribe una función `matriz_a_lista(matriz)` que la convierta en una lista de adyacencia (diccionario donde cada clave es un nodo y el valor es una lista de sus vecinos). Luego, escribe una segunda función `grado_vertices(lista_adyacencia)` que retorne una lista de tuplas `(nodo, grado)` ordenada de mayor a menor grado. Si hay empate, ordena por nodo ascendente.

**Entrada:**
```python
matriz = [
    [0, 1, 1, 0],
    [1, 0, 1, 1],
    [1, 1, 0, 0],
    [0, 1, 0, 0],
]
```
**Salida:**
```
Lista de adyacencia: {0: [1, 2], 1: [0, 2, 3], 2: [0, 1], 3: [1]}
Grados ordenados: [(1, 3), (0, 2), (2, 2), (3, 1)]
```

---

### Ejercicio 503: Agrupar alumnos por calificación y rango
**Enunciado:** Dada una lista de diccionarios con `nombre`, `calificacion` (0–100) y `grupo`, escribe una función `agrupar_rendimiento(alumnos)` que:
1. Agrupe a los alumnos en tres categorías: "Excelente" (90–100), "Bueno" (70–89), "Necesita apoyo" (0–69).
2. Dentro de cada categoría, ordene alfabéticamente pornombre`.
3. Retorne un diccionario anidado `{categoria: {grupo: [nombres ordenados]}}`.
4. Además, retorne una segunda función `estadisticas_por_grupo(alumnos)` que calcule, para cada grupo, el promedio, la calificación máxima y mínima, retornando un diccionario `{grupo: {"promedio": x, "max": y, "min": z}}`.

**Entrada:**
```python
alumnos = [
    {"nombre": "Ana", "calificacion": 95, "grupo": "A"},
    {"nombre": "Luis", "calificacion": 82, "grupo": "B"},
    {"nombre": "Carlos", "calificacion": 67, "grupo": "A"},
    {"nombre": "María", "calificacion": 91, "grupo": "A"},
    {"nombre": "Pedro", "calificacion": 78, "grupo": "B"},
    {"nombre": "Sofía", "calificacion": 45, "grupo": "A"},
]
```
**Salida (agrupar_rendimiento):**
```python
{
    "Excelente": {"A": ["Ana", "María"], "B": []},
    "Bueno": {"A": [], "B": ["Luis", "Pedro"]},
    "Necesita apoyo": {"A": ["Carlos", "Sofía"], "B": []},
}
```
**Salida (estadisticas_por_grupo):**
```python
{"A": {"promedio": 74.67, "max": 95, "min": 45}, "B": {"promedio": 80.0, "max": 82, "min": 78}}
```

---

### Ejercicio 504: Tabla de multiplicar transpuesta y formateada
**Enunciado:** Escribe una función `tabla_multiplicar_transpuesta(n, m)` que genere una matriz de tamaño `n x m` donde `matriz[i][j] = (i+1) * (j+1)`. Luego, transpusla (convierta filas en columnas) y retorne ambas matrices formateadas como cadenas. La cadena de la matriz original debe mostrarse con filas separadas por saltos de línea, y la transpuesta con columnas alineadas a la derecha con ancho de 4 caracteres.

**Entrada:** `tabla_multiplicar_transpuesta(4, 5)`
**Salida:**
```
=== MATRIZ ORIGINAL (4x5) ===
1   2   3   4   5
2   4   6   8   10
3   6   9   12  15
4   8   12  16  20

=== MATRIZ TRANSPuesta (5x4) ===
   1    2    3    4
   2    4    6    8
   3    6    9   12
   4    8   12   16
   5   10   15   20
```

---

### Ejercicio 505: Diccionario de frecuencias de palabras con stopwords
**Enunciado:** Escribe una función `frecuencia_palabras_avanzado(texto, stopwords=None)` que:
1. Normalice el texto: minúsculas, elimine signos de puntuación (solo conserva letras, espacios y números).
2. Parta el texto en palabras usando `split()`.
3. Filtre las stopwords (si se proporciona la lista).
4. Construya un diccionario `{palabra: frecuencia}`.
5. Retorne una lista de tuplas `(palabra, frecuencia)` ordenada primero por frecuencia descendente y luego alfabéticamente por palabra para roturas de empate.

**Entrada:**
```python
texto = "La programación es divertida. La programación en Python es aún más divertida. ¡Python es increíble!"
stopwords = ["la", "es", "en", "es", "más"]
```
**Salida:**
```python
[("programacion", 3), ("python", 2), ("divertida", 2), ("increíble", 1), ("aun", 1)]
```

---

### Ejercicio 506: Sistema de calificaciones ponderadas con matriz
**Enunciado:** Se tiene una matriz donde cada fila representa un alumno y las columnas son: `[nombre, calif_examen1, calif_examen2, calif_trabajos, calif_participacion]`. Los pesos son: examen1 30%, examen2 30%, trabajos 25%, participación 15%. Escribe una función `calificaciones_ponderadas(matriz)` que:
1. Calcule la calificación final de cada alumno.
2. Asigne una letra: A (≥90), B (80–89), C (70–79), D (60–69), F (<60).
3. Retorne una lista de tuplas `(nombre, calificacion_final, letra)` ordenada por calificación final descendente.
4. Además, retorne un diccionario con el conteo de letras `{letra: cantidad}`.

**Entrada:**
```python
matriz = [
    ["Ana", 95, 88, 92, 90],
    ["Luis", 72, 68, 75, 80],
    ["María", 85, 90, 88, 92],
    ["Carlos", 55, 60, 58, 65],
]
```
**Salida:**
```python
[
    ("Ana", 91.35, "A"),
    ("María", 88.65, "B"),
    ("Luis", 73.65, "C"),
    ("Carlos", 59.45, "F"),
]
{"A": 1, "B": 1, "C": 1, "F": 1}
```

---

### Ejercicio 507: Árbol de categorías con recorrido en profundidad
**Enunciado:** Se representa un árbol de categorías como un diccionario anidado: `{categoria: {subcategoria: ..., otra_sub: ...}}`. Escribe una función recursiva `profundidad_categoria(arbol, categoria_inicial, profundidad=0)` que imprima cada categoría con su nivel de profundidad con sangría (2 espacios por nivel). Luego, escribe `contar_categorias(arbol)` que retorne el número total de categorías (incluyendo las anidadas) usando recursividad.

**Entrada:**
```python
arbol = {
    "Animales": {
        "Mamíferos": {"Perro": {}, "Gato": {}},
        "Aves": {"Loro": {}, "Águila": {}},
    },
    "Plantas": {"Flores": {"Rosa": {}}, "Árboles": {}},
}
```
**Salida (profundidad_categoria):**
```
Animales (nivel 0)
  Mamíferos (nivel 1)
    Perro (nivel 2)
    Gato (nivel 2)
  Aves (nivel 1)
    Loro (nivel 2)
    Águila (nivel 2)
Plantas (nivel 0)
  Flores (nivel 1)
    Rosa (nivel 2)
  Árboles (nivel 1)
```
`contar_categorias(arbol)` retorna `9`

---

### Ejercicio 508: Deduplicar contactos por email y nombre
**Enunciado:** Dada una lista de diccionarios de contactos con `nombre`, `email` y `telefono`, escritoa función `deduplicar_contactos(contactos)` que:
1. Identifique duplicados por `email` (case-insensitive) — conserve el primero.
2. Identifique duplicados por `nombre` normalizado (minúsculas, sin espacios extra) — conserve el primero.
3. Retorne una tupla `(contactos_limpios, duplicados_eliminados)` donde `duplicados_eliminados` es una lista de los contactos que fueron descartados con su razón (`"email duplicado"` o `"nombre duplicado"`).

**Entrada:**
```python
contactos = [
    {"nombre": "Ana López", "email": "ana@email.com", "telefono": "555-0101"},
    {"nombre": "Juan Pérez", "email": "juan@email.com", "telefono": "555-0102"},
    {"nombre": "ana lópez", "email": "ana.lopez@email.com", "telefono": "555-0103"},
    {"nombre": "Juan Pérez", "email": "juan.perez@email.com", "telefono": "555-0104"},
    {"nombre": "Luis Torres", "email": "juan@email.com", "telefono": "555-0105"},
]
```
**Salida:**
```
Contactos limpios: [
    {"nombre": "Ana López", "email": "ana@email.com", "telefono": "555-0101"},
    {"nombre": "Juan Pérez", "email": "juan@email.com", "telefono": "555-0102"},
]
Duplicados eliminados: [
    ("ana lópez", "nombre duplicado"),
    ("Juan Pérez", "nombre duplicado"),
    ("Luis Torres", "email duplicado"),
]
```

---

### Ejercicio 509: Matrices de rotación de imagen
**Enunciado:** Dada una matriz cuadrada `n x n` que representa píxeles de una imagen (valores 0–255), escribe tres funciones:
1. `rotar_90(matriz)` — rota 90° clockwise (devuelve nueva matriz).
2. `rotar_180(matriz)` — rota 180° (puede usar `rotar_90` dos veces).
3. `rotar_270(matriz)` — rota 270° (equivalente a rotar -90°).
Verifica que las funciones sean correctas comparando con la matriz original transpuesteada y revertida.

**Entrada:**
```python
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
]
```
**Salida (rotar_90):**
```
[[7, 4, 1], [8, 5, 2], [9, 6, 3]]
```
**Salida (rotar_180):**
```
[[9, 8, 7], [6, 5, 4], [3, 2, 1]]
```
**Salida (rotar_270):**
```
[[3, 6, 9], [2, 5, 8], [1, 4, 7]]
```

---

### Ejercicio 510: Expensas mensuales por categoría y recuento
**Enunciado:** Se tiene una lista de diccionarios `gastos = [{"mes": "Enero", "categoria": "Alimentación", "monto": 500}, ...]`. Escribe una función `resumen_gastos(gastos)` que:
1. Agrupe los gastos por mes y categoría, sumando montos.
2. Retorne un diccionario anidado `{mes: {categoria: total}}`.
3. Retorne una lista de las categorías ordenadas por el monto total anual (suma de todos los meses) de mayor a menor, como una lista de tuplas `(categoria, total_anual, mes_mayor_gasto, monto_mayor_mes)`.

**Entrada:**
```python
gastos = [
    {"mes": "Enero", "categoria": "Alimentación", "monto": 500},
    {"mes": "Enero", "categoria": "Transporte", "monto": 150},
    {"mes": "Febrero", "categoria": "Alimentación", "monto": 480},
    {"mes": "Febrero", "categoria": "Entretenimiento", "monto": 200},
    {"mes": "Marzo", "categoria": "Alimentación", "monto": 520},
    {"mes": "Marzo", "categoria": "Transporte", "monto": 180},
    {"mes": "Marzo", "categoria": "Entretenimiento", "monto": 300},
]
```
**Salida:**
```python
{
    "Enero": {"Alimentación": 500, "Transporte": 150},
    "Febrero": {"Alimentación": 480, "Entretenimiento": 200},
    "Marzo": {"Alimentación": 520, "Transporte": 180, "Entretenimiento": 300},
}
[("Alimentación", 1500, "Marzo", 520), ("Entretenimiento", 500, "Marzo", 300), ("Transporte", 330, "Marzo", 180)]
```

---

### Ejercicio 511: Compresión de secuencias con stacks
**Enunciado:** Implementa un algoritmo de compresión de run-length usando una lista como stack. Escribe una función `comprimir_secuencia(secuencia)` que tome una lista de elementos y retorne una lista de tuplas `(elemento, cantidad)` comprimidas. Luego, implementa `descomprimir_secuencia(comprimida)` que reconstruya la secuencia original usando una stack. Valida que `descomprimir(comprimir(x)) == x` para una lista de prueba.

**Entrada:** `secuencia = [1, 1, 1, 2, 2, 3, 1, 1, 4, 4, 4, 4]`
**Salida (comprimir):** `[(1, 3), (2, 2), (3, 1), (1, 2), (4, 4)]`
**Salida (descomprimir):** `[1, 1, 1, 2, 2, 3, 1, 1, 4, 4, 4, 4]`

---

### Ejercicio 512: Sistema de nodes de un árbol de archivos
**Enunciado:** Representa un sistema de archivos como un diccionario anidado donde cada clave es un nombre y el valor es `{"tipo": "archivo"|"directorio", "tamanio": N (si es archivo), "contenido": {...} (si es directorio)}`. Escribe:
1. `calcular_tamanio_directorio(arbol, ruta)` — recursivamente suma el tamaño de todos los archivos dentro del directorio indicado (ruta como lista de strings).
2. `buscar_archivo(arbol, extension, ruta="")` — retorna una lista de rutas completas (como cadenas con "/") de todos los archivos con esa extensión (ej. ".txt").
3. `lista_directorio(arbol, ruta)` — retorna una lista de los nombres inmediatos dentro del directorio.

**Entrada:**
```python
arbol = {
    "documentos": {
        "tipo": "directorio",
        "contenido": {
            "trabajo": {
                "tipo": "directorio",
                "contenido": {
                    "informe.txt": {"tipo": "archivo", "tamanio": 1200},
                    "datos.csv": {"tipo": "archivo", "tamanio": 3400},
                },
            },
            "personal.txt": {"tipo": "archivo", "tamanio": 800},
        },
    },
    "imagenes": {
        "tipo": "directorio",
        "contenido": {
            "foto.jpg": {"tipo": "archivo", "tamanio": 250000},
        },
    },
}
```
**Salida (calcular_tamanio_directorio(arbol, ["documentos"])):** `5400`
**Salida (buscar_archivo(arbol, ".txt")):** `["documentos/trabajo/informe.txt", "documentos/personal.txt"]`
**Salida (lista_directorio(arbol, ["documentos"])):** `["trabajo", "personal.txt"]`

---

### Ejercicio 513: Diferencia entre dos inventarios
**Enunciado:** Dados dos diccionarios de inventario `inventario_anterior` y `inventario_nuevo`, donde cada uno tiene `{producto_id: {"nombre": ..., "precio": ..., "cantidad": ...}}`, escritoa función `comparar_inventarios(anterior, nuevo)` que retorne un diccionario con tres claves:
1. `"agregados"`: lista de productos que están en nuevo pero no en anterior (solo el id).
2. `"eliminados"`: lista de productos en anterior pero no en nuevo.
3. `"modificados"`: lista de tuplas `(id, atributo, valor_antiguo, valor_nuevo)` para cada producto que está en ambos pero cambió precio o cantidad.
4. `"sin_cambios"`: lista de ids sin cambios.

**Entrada:**
```python
anterior = {
    "P001": {"nombre": "Mouse", "precio": 50, "cantidad": 20},
    "P002": {"nombre": "Teclado", "precio": 120, "cantidad": 15},
    "P003": {"nombre": "Monitor", "precio": 300, "cantidad": 8},
}
nuevo = {
    "P001": {"nombre": "Mouse", "precio": 55, "cantidad": 20},
    "P002": {"nombre": "Teclado", "precio": 120, "cantidad": 10},
    "P004": {"nombre": "Webcam", "precio": 80, "cantidad": 12},
}
```
**Salida:**
```python
{
    "agregados": ["P004"],
    "eliminados": ["P003"],
    "modificados": [
        ("P001", "precio", 50, 55),
        ("P002", "cantidad", 15, 10),
    ],
    "sin_cambios": [],
}
```

---

### Ejercicio 514: Tabla de hash simulada conLista de listas
**Enunciado:** Implementa una tabla de hash simple usando una lista de `m` listas (buckets). Escribe una clase `TablaHash`:
1. `__init__(self, m=10)` — crea `self.tabla = [[] for _ in range(m)]` y `self.m = m`.
2. `_hash(self, clave)` — retorna `hash(clave) % self.m`.
3. `insertar(self, clave, valor)` — si la clave ya existe, actualiza; si no, agrega.
4. `buscar(self, clave)` — retorna el valor o `None`.
5. `eliminar(self, clave)` — elimina y retorna True/False.
6. `listar(self)` — retorna lista de tuplas `(clave, valor)` en orden de inserción (recorre buckets en orden).
Valida con un ejemplo donde insertas y recuperas varios elementos.

**Entrada (ejemplo de uso):**
```python
th = TablaHash(m=5)
th.insertar("nombre", "Ana")
th.insertar("edad", 25)
th.insertar("ciudad", "México")
th.insertar("nombre", "Ana López")  # actualizar
print(th.buscar("nombre"))   # "Ana López"
print(th.buscar("edad"))     # 25
print(th.buscar("inexistente"))  # None
print(th.eliminar("edad"))   # True
print(th.buscar("edad"))     # None
print(th.listar())           # [("nombre", "Ana López"), ("ciudad", "México")]
```

---

### Ejercicio 515: Criptografía César con diccionario de sustitución
**Enunciado:** Escribe una función `cifrar_cesar(texto, desplazamiento)` que:
1. Construye un diccionario de sustitución donde cada letra del alfabeto (solo mayúsculas) se mapea a la letra desplazada en `desplazamiento` posiciones (wrapping con módulo 26).
2. Aplica el cifrado solo a letras mayúsculas; el resto de caracteres se conservan.
3. Escribe una función inversa `descifrar_cesar(texto, desplazamiento)`.
4. Valida que `descifrar(cifrar(x, n), n) == x` para un texto de prueba con mayúsculas, minúsculas y símbolos.

**Entrada:** `cifrar_cesar("Hola Mundo! 123", 3)`
**Salida:** `"Krod Pxqgr! 123"`
**Salida descifrar:** `descifrar_cesar("Krod Pxqgr! 123", 3)` → `"Hola Mundo! 123"`

---

### Ejercicio 516: Emparejamiento de donantes y beneficiarios
**Enunciado:** Se tieneuna lista de donantes `[{"id": ..., "nombre": ..., "capacidad": N (litros), "zona": "centro"|"norte"|"sur"}, ...]` y una lista de beneficiarios `[{"id": ..., "nombre": ..., "necesidad": N (litros), "zona": ...}, ...]`. Escribe una función `emparejar_distribucion(donantes, beneficiarios)` que:
1. Primero empareja por zona exacta (donante.capacidad >= beneficiario.necesidad).
2. Para beneficiarios sin pareja en su zona, buscará donantes de otras zonas con capacidad suficiente.
3. Retorna un diccionario `{beneficiario_id: donante_id}` para los exitosamente emparejados, y una lista de beneficiarios sin atención.
4. Cada donante puede atender a múltiples beneficiarios hasta agotar su capacidad (restar necesidad de capacidad cada vez).
5. Prioriza emparejamientos donde el donante exceda el mínimo necesario (capacidad - necesidad sea mínima pero >= 0).

**Entrada:**
```python
donantes = [
    {"id": "D1", "nombre": "Donante Norte", "capacidad": 500, "zona": "norte"},
    {"id": "D2", "nombre": "Donante Centro", "capacidad": 300, "zona": "centro"},
    {"id": "D3", "nombre": "Donante Sur", "capacidad": 200, "zona": "sur"},
]
beneficiarios = [
    {"id": "B1", "nombre": "Comedor Norte", "necesidad": 400, "zona": "norte"},
    {"id": "B2", "nombre": "Comedor Centro 1", "necesidad": 200, "zona": "centro"},
    {"id": "B3", "nombre": "Comedor Centro 2", "necesidad": 150, "zona": "centro"},
    {"id": "B4", "nombre": "Comedor Sur", "necesidad": 180, "zona": "sur"},
    {"id": "B5", "nombre": "Escuela Rural", "necesidad": 250, "zona": "sur"},
]
```
**Salida:**
```python
{
    "B1": "D1",   # D1 queda con 100L
    "B2": "D2",   # D2 queda con 100L
    "B3": "D2",   # D2 queda con -50L → NO (no puede). B3 queda sin
    "B4": "D3",   # D3 queda con 20L
}
```
Beneficiarios sin atención: `["B3", "B5"]` (B3 no tiene donante centro, B5 necesita 250L y D3 solo tiene 200L → falla al intentar zona cruzada si no hay otro)

*(Nota: el algoritmo debe manejar la capacidad residual correctamente — el ejercicio pide implementar esto con detalle)*

---

### Ejercicio 517: Parsear logs de servidor con regex manual
**Enunciado:** Sin usar el módulo `re`, escritoa función `parsear_logs(logs)` que tome una lista de strings de log con formato:
`"[DD/Mon/AAAA:HH:MM:SS -ZZZZ] "METODO RUTA HTTP/1.1" CÓDIGO TAMANO"`
y retorneuna lista de diccionarios con las claves `fecha`, `hora`, `metodo`, `ruta`, `http_version`, `codigo`, `tamano`. Luego, agrupa los logs por código de estado HTTP y retorna un resumen `{codigo: {"cantidad": N, "tamano_total": S, "rutas": [lista de rutas únicas]}}`.

**Entrada:**
```python
logs = [
    '[10/Oct/2023:13:55:36 -0700] "GET /index.html HTTP/1.1" 200 1234',
    '[10/Oct/2023:13:55:37 -0700] "POST /api/login HTTP/1.1" 401 56',
    '[10/Oct/2023:13:55:38 -0700] "GET /index.html HTTP/1.1" 200 1234',
    '[10/Oct/2023:13:55:39 -0700] "GET /favicon.ico HTTP/1.1" 404 0',
]
```
**Salida (lista parseada):**
```python
[
    {"fecha": "10/Oct/2023", "hora": "13:55:36", "metodo": "GET", "ruta": "/index.html", "http_version": "HTTP/1.1", "codigo": 200, "tamano": 1234},
    {"fecha": "10/Oct/2023", "hora": "13:55:37", "metodo": "POST", "ruta": "/api/login", "http_version": "HTTP/1.1", "codigo": 401, "tamano": 56},
    ...
]
```
**Salida (resumen por código):**
```python
{
    200: {"cantidad": 2, "tamano_total": 2468, "rutas": ["/index.html"]},
    401: {"cantidad": 1, "tamano_total": 56, "rutas": ["/api/login"]},
    404: {"cantidad": 1, "tamano_total": 0, "rutas": ["/favicon.ico"]},
}
```

---

### Ejercicio 518: Sistema de votaciones con tuplas y búsqueda binaria
**Enunciado:** Se tieneuna lista de tuplas `(candidato, votos)` desordenada. Escribe una función `procesar_votaciones(votaciones)` que:
1. Ordene por votos descendente (y alfabeticamente por nombre si empata).
2. Calcule el total de votos y el porcentaje de cada candidato.
3. Retorneuna lista de tuplas `(candidato, votos, porcentaje, posicion)` donde `posicion` es basada en 1.
4. Luego, implementauna función `buscar_candidato(lista_ordenada, nombre)` que usa búsqueda binaria sobre la lista ordenada alfabeticamente por nombre (columna 0) para encontrar un candidato — retorna su tupla o `None`.

**Entrada:**
```python
votaciones = [
    ("Carlos", 1200),
    ("Ana", 1800),
    ("Luis", 950),
    ("María", 1800),
    ("Pedro", 1100),
]
```
**Salida (procesar_votaciones):**
```python
[
    ("Ana", 1800, 30.0, 1),
    ("María", 1800, 30.0, 2),  # empate con Ana en votos, pero Ana va primero alfabeticamente
    ("Carlos", 1200, 20.0, 3),
    ("Pedro", 1100, 18.33, 4),
    ("Luis", 950, 15.83, 5),
]
Total: 6050
```
**Salida (buscar_candidato(lista_ordenada_por_nombre, "María")):** `("María", 1800, 30.0, 2)`

---

### Ejercicio 519: Reducción de dimensionalidad con matrices
**Enunciado:** Dadauna matriz `n x m` (lista de listas) que representa datos de `n` muestras con `m` features, escribaa función `normalizar_matriz(matriz)` que:
1. Para cada columna (feature), calcule el mínimo y máximo.
2. Normalice cada valor a `[0, 1]` con la fórmula `(valor - min) / (max - min)` (si max == min, deja 0).
3. Retorne la matriz normalizada (nueva) y también la matriz de mínimos y máximos usados.
Luego, escribaa función `pca_simple(matriz_normalizada, k=2)` que aproxime una reducción de dimensionalidad tomando las `k` columnas con mayor varianza (calcular varianza de cada columna y seleccionar top k).

**Entrada:**
```python
matriz = [
    [10, 100, 5],
    [20, 150, 8],
    [15, 120, 6],
    [25, 200, 10],
]
```
**Salida (normalizar):**
```
[[0.0, 0.0, 0.0],
 [1.0, 1.0, 1.0],
 [0.5, 0.4, 0.333...],
 [1.0, 1.0, 1.0]]
```
*(Los valores exactos dependen del cálculo)*

---

### Ejercicio 520: Árbol binario de búsqueda con tuplas
**Enunciado:** Implementa un árbol binario de búsqueda simple usando tuplas `(clave, valor)` para cada nodo (sin clases, usando diccionarios para representar cada nodo: `{"clave": k, "valor": v, "izq": None, "der": None}`). Escribe:
1. `insertar(arbol, clave, valor)` — retorna el árbol actualizado.
2. `buscar(arbol, clave)` — retorna el valor o `None`.
3. `inorden(arbol)` — retorna una lista de tuplas `(clave, valor)` en orden ascendente.
4. `contar_nodos(arbol)` — retorna la cantidad total de nodos.
El árbol es un diccionario `{"raiz": nodo_o_None}`.

**Entrada:**
```python
arbol = {"raiz": None}
arbol = insertar(arbol, 5, "cinco")
arbol = insertar(arbol, 3, "tres")
arbol = insertar(arbol, 7, "siete")
arbol = insertar(arbol, 2, "dos")
arbol = insertar(arbol, 4, "cuatro")
```
**Salida (inorden):** `[(2, "dos"), (3, "tres"), (4, "cuatro"), (5, "cinco"), (7, "siete")]`
**Salida (buscar 3):** `"tres"`
**Salida (contar_nodos):** `5`

---

### Ejercicio 521: Glossary de términos técnicos con anidamiento
**Enunciado:** Dado un texto largo con términos técnicos definidos entre paréntesis cuadrados `[término: definición]`, escritoa función `extraer_glossary(texto)` que:
1. Extraiga todos los pares `[término: definición]` usando `find()` y `rfind()` para localizar los corchetes (sin regex).
2. Retorne un diccionario `{termino: definicion}`.
3. Escribe `buscar_glossary(glossary, palabra_clave)` que retorna todos los términos cuya definición contiene la `palabra_clave` (case-insensitive).
4. Escribe `exportar_glossary(glossary, archivo)` que escriba el glossary en un archivo de texto con formato: `TÉRMINO: definición` uno por línea.

**Entrada:**
```python
texto = "La [API: Interfaz de Programación de Aplicaciones] permite la comunicación. El [JSON: Notación de Objetos de JavaScript] es un formato de datos. La API REST usa JSON."
```
**Salida (extraer_glossary):**
```python
{"API": "Interfaz de Programación de Aplicaciones", "JSON": "Notación de Objetos de JavaScript"}
```
**Salida (buscar_glossary(glossary, "aplicacion")):** `["API"]`

---

### Ejercicio 522: Sistema de reservas doblemente anidado
**Enunciado:** Una agencia de viajes tiene un sistema de reservas representado como:
`reservas = {cliente_id: {fecha: [(hotel, habitaciones_reservadas, precio_por_noche), ...], ...}, ...}`
Escribe:
1. `calcular_total_por_cliente(reservas, cliente_id)` — suma el total de todas las reservas del cliente (habitaciones * precio * 3 noches asumido).
2. `buscar_disponibilidad(reservas, fecha, hotel)` — retorna cuántas habitaciones están reservadas ese día para ese hotel (si no hay reservas, retorna 0).
3. `nuevas_reservas_por_mes(reservas, mes)` — retorna un diccionario `{cliente_id: total_reservas_ese_mes}`.
4. `reservas_mas_costosas(reservas, top_n=3)` — retornauna lista de las `top_n` reservas más costosas del sistema como tuplas `(cliente_id, fecha, hotel, total)`.

**Entrada:**
```python
reservas = {
    "C001": {
        "2024-01-15": [("Hotel A", 2, 150), ("Hotel B", 1, 200)],
        "2024-02-20": [("Hotel A", 3, 150)],
    },
    "C002": {
        "2024-01-15": [("Hotel C", 2, 100)],
    },
}
```
**Salida (calcular_total_por_cliente(reservas, "C001")):** `2*150*3 + 1*200*3 + 3*150*3 = 900 + 600 + 1350 = 2850`
**Salida (buscar_disponibilidad(reservas, "2024-01-15", "Hotel A")):** `2` (habitaciones reservadas)
**Salida (nuevas_reservas_por_mes(reservas, "01")):** `{"C001": 1, "C002": 1}` (contando fechas que contienen "01")
**Salida (reservas_mas_costosas(reservas, 3)):**
```python
[
    ("C001", "2024-02-20", "Hotel A", 1350),
    ("C001", "2024-01-15", "Hotel A", 900),
    ("C001", "2024-01-15", "Hotel B", 600),
]
```

---

### Ejercicio 523: Compresión de lista de tuplas por clave
**Enunciado:** Dadauna lista de tuplas `(categoria, item, valor)`, escritoa función `comprimir_por_categoria(lista)` que:
1. Agrupe por `categoria` y construya un diccionario `{categoria: {item: valor}}`.
2. Si un `item` aparece múltiples veces para la misma categoría, conserve la última aparición (sobreescribe).
3. Retorne el diccionario comprimido y una lista de tuplas `(categoria, item, valor_anterior, valor_nuevo)` para las sobreescrituras detectadas.
4. Implementa `descomprimir(comprimido)` que reconstruya la lista original de tuplas.

**Entrada:**
```python
lista = [
    ("frutas", "manzana", 5),
    ("frutas", "banana", 3),
    ("verduras", "zanahoria", 2),
    ("frutas", "manzana", 7),  # sobreescribe
    ("verduras", "zanahoria", 4),  # sobreescribe
    ("legumbres", "lentejas", 6),
]
```
**Salida:**
```python
# comprimido
{"frutas": {"manzana": 7, "banana": 3}, "verduras": {"zanahoria": 4}, "legumbres": {"lentejas": 6}}

# sobreescrituras
[("frutas", "manzana", 5, 7), ("verduras", "zanahoria", 2, 4)]
```

---

### Ejercicio 524: Cifrado Vigenère con matriz de sustitución
**Enunciado:** Implementa el cifrado Vigenère: dado un texto en mayúsculas y una palabra clave (también mayúsculas), se construyeuna matriz de 26x26 donde la fila `i` corresponde al desplazamiento `i`. Escribe:
1. `construir_matriz_vigenere()` — retorna la matriz como lista de listas.
2. `cifrar_vigenere(texto, clave)` — para cada letra del texto, usa el desplazamiento de la letra correspondiente de la clave (repetida cíclicamente).
3. `descifrar_vigenere(texto, clave)` — inversa.
4. Valida con un ejemplo.

**Entrada:** `cifrar_vigenere("HOLA", "KEY")` → desplazamientos: K=10, E=4, Y=24, K=10 → resultado
**Salida:** `"ZEMV"` (H+10=Z, O+4=S... verificar y corregir: H(7)+10=17=R, O(14)+4=18=S, L(11)+24=35%26=9=J, A(0)+10=10=K → "RSJK" — este es el cálculo correcto)

---

### Ejercicio 525: Transformación de datos con map/filter/reduce
**Enunciado:** Dadauna lista de diccionarios `empleados = [{"nombre": ..., "edad": ..., "salario": ..., "departamento": ...}, ...]`:
1. Usa `filter()` para obtener empleados con salario > 50000.
2. Usa `map()` para transformar cada empleado a una tupla `(nombre, salario_anual, departamento, edad)` donde `salario_anual = salario * 12`.
3. Usa `reduce()` para calcular el salario total por departamento (agrupando manualmente o con un diccionario acumulador dentro de reduce).
4. Retorneuna tupla `(empleados_filtrados_mapeados, totales_por_depto)`.

**Entrada:**
```python
empleados = [
    {"nombre": "Ana", "edad": 30, "salario": 45000, "departamento": "TI"},
    {"nombre": "Luis", "edad": 35, "salario": 60000, "departamento": "Finanzas"},
    {"nombre": "María", "edad": 28, "salario": 55000, "departamento": "TI"},
    {"nombre": "Carlos", "edad": 42, "salario": 70000, "departamento": "RRHH"},
]
```
**Salida:**
```python
# empleados_filtrados_mapeados
[
    ("Luis", 720000, "Finanzas", 35),
    ("María", 660000, "TI", 28),
    ("Carlos", 840000, "RRHH", 42),
]
# totales_por_depto
{"Finanzas": 720000, "TI": 660000, "RRHH": 840000}
```

---

## BLOQUE 2 · EXCEPCIONES PERSONALIZADAS + VALIDACIONES (526–550)

### Ejercicio 526: Excepción personalizada para rango de edad
**Enunciado:** Define una excepción personalizada `EdadInvalidaException` que herede de `Exception` y acepte un mensaje y la edad proporcionada. Escribe una función `validar_edad(edad)` que:
1. Si `edad` no es un entero, lance `EdadInvalidaException("La edad debe ser un número entero")`.
2. Si `edad < 0`, lance `EdadInvalidaException(f"La edad no puede ser negativa: {edad}")`.
3. Si `edad > 120`, lance `EdadInvalidaException(f"La edad no puede superar 120: {edad}")`.
4. Si la edad es válida, retorne `True` y imprima `Edad válida: {edad}`.
Prueba la función con varios casos y atrapa las excepciones imprimiendo el mensaje personalizado con la edad.

**Entrada:**
```python
pruebas = ["veinte", -5, 150, 25, 0]
```
**Salida:**
```
EdadInvalidaException: La edad debe ser un número entero (recibido: "veinte")
EdadInvalidaException: La edad no puede ser negativa: -5
EdadInvalidaException: La edad no puede superar 120: 150
Edad válida: 25
Edad válida: 0
```

---

### Ejercicio 527: Calculadora con excepciones personalizadas
**Enunciado:** Define excepciones `DivisionPorCeroException`, `OperacionInvalidaException` y `EntradaNoNumericaException`, todas heredando de `Exception` con mensajes personalizados. Escribeuna función `calculadora_segura(operacion, a, b)` que:
1. Si `operacion` no es uno de `["suma", "resta", "multiplicacion", "division"]`, lance `OperacionInvalidaException`.
2. Si `a` o `b` no son números (int o float), lance `EntradaNoNumericaException`.
3. Si `operacion == "division"` y `b == 0`, lance `DivisionPorCeroException`.
4. De lo contrario, realiza la operación y retorna el resultado.
5. Escribeuna función `procesar_operaciones(lista_operaciones)` que recibe una lista de tuplas `(op, a, b)` y retornauna lista de resultados o mensajes de error.

**Entrada:**
```python
operaciones = [
    ("suma", 10, 5),
    ("division", 10, 0),
    ("potencia", 2, 3),  # operación inválida
    ("resta", "diez", 3),  # entrada no numérica
    ("division", 10, 2),
]
```
**Salida:**
```python
[
    15,
    "Error: No se puede dividir por cero.",
    "Error: Operación 'potencia' no válida.",
    "Error: Las entradas deben ser números.",
    5.0,
]
```

---

### Ejercicio 528: Validador de contraseñas con excepciones
**Enunciado:** Define `ContrasenaDebilException` que reciba la contraseña y un mensaje describiendo el fallo. Escribe `validar_contrasena(contraseña)` que verifica:
1. Longitud >= 8 — si no, lanza `ContrasenaDebilException(contraseña, "Mínimo 8 caracteres")`.
2. Contiene al menos una mayúscula — si no, lanza con "Requiere al menos una mayúscula".
3. Contiene al menos una minúscula — si no, lanza con "Requiere al menos una minúscula".
4. Contiene al menos un dígito — si no, lanza con "Requiere al menos un número".
5. Contiene al menos un caracter especial (`!@#$%^&*` etc.) — si no, lanza con "Requiere al menos un caracter especial".
6. Si pasa todas, retorna `True` e imprime "Contraseña válida".
Escribe `probar_contraseñas(lista)` que prueba cada una y retorna una lista de `(contraseña, valida, mensaje_error)`.

**Entrada:**
```python
pruebas = [
    "abc",
    "Abcdefgh",
    "Abcdef1!",
    "ABCD1234!",
    "aB1!abcdef",
]
```
**Salida:**
```
"abc" → Falla: Mínimo 8 caracteres
"Abcdefgh" → Falla: Requiere al menos un número
"Abcdef1!" → Falla: Requiere al menos un caracter especial
"ABCD1234!" → Falla: Requiere al menos una minúscula
"aB1!abcdef" → Válida
```

---

### Ejercicio 529: Sistema de archiving con excepciones de archivo
**Enunciado:** Define excepciones `ArchivoNoExisteException`, `RutaInvalidaException`, `PermisoEscrituraException`. Escribeuna clase `GestorArchivos`:
1. `__init__(self, directorio_base)` — valida que el directorio exista con `os.path.isdir()`, si no lanza `RutaInvalidaException`.
2. `leer(self, ruta_relativa)` — full path = directorio_base + "/" + ruta_relativa; verifica existencia con `os.path.isfile()`, si no lanza `ArchivoNoExisteException`; lee y retorna el contenido.
3. `escribir(self, ruta_relativa, contenido)` — intenta escribir; si hay PermissionError, lanza `PermisoEscrituraException`.
4. `listar(self, ruta_relativa="")` — lista archivos en el directorio indicado, retorna lista de nombres.
5. `eliminar(self, ruta_relativa)` — elimina el archivo, lanza `ArchivoNoExisteException` si no existe.
Crea archivos de prueba en `/tmp/test_gestor/` y valida todas las operaciones.

**Entrada (de prueba):**
```python
import os
os.makedirs("/tmp/test_gestor/subdir", exist_ok=True)
with open("/tmp/test_gestor/archivo1.txt", "w") as f: f.write("Hola")
gestor = GestorArchivos("/tmp/test_gestor")
print(gestor.leer("archivo1.txt"))  # "Hola"
print(gestor.listar())  # ["archivo1.txt", "subdir"]
print(gestor.listar("subdir"))  # []
gestor.escribir("nuevo.txt", "Contenido nuevo")
print(gestor.leer("nuevo.txt"))  # "Contenido nuevo"
```
**Salida esperada:** según los prints anteriores

---

### Ejercicio 530: Excepción para estructura de datos inválida
**Enunciado:** Define `EstructuraInvalidaException` que reciba la estructura recibida y un mensaje. Escribeuna función `procesar_datos(datos)` que espera un diccionario con claves específicas (`"nombre"`, `"edad"`, `"email"`), cada una con tipo específico (`str`, `int`, `str`). Si los datos no cumplen:
1. Si no es un diccionario: lanza con `f"Se esperaba un diccionario, recibido {type(datos).__name__}: {datos}"`.
2. Si falta alguna clave: lanza con `f"Falta la clave: {clave_faltante}"`.
3. Si el tipo no es correcto: lanza con `f"La clave '{clave}' debe ser {tipo_esperado.__name__}, recibido {type(datos[clave]).__name__}: {datos[clave]}"`.
4. Si todo es válido, retorna una versión normalizada: nombre capitalizado, edad como int, email en minúsculas.

**Entrada:**
```python
pruebas = [
    {"nombre": "Ana", "edad": 25, "email": "ANA@EMAIL.COM"},
    ["Ana", 25, "ANA@EMAIL.COM"],
    {"nombre": "Luis", "edad": "veinte", "email": "luis@email.com"},
    {"nombre": "Pedro"},
    {"nombre": "María", "edad": 30, "email": "maría@email.com"},
]
```
**Salida:**
```python
{"nombre": "Ana", "edad": 25, "email": "ana@email.com"}
EstructuraInvalidaException: Se esperaba un diccionario, recibido list: ['Ana', 25, 'ANA@EMAIL.COM']
EstructuraInvalidaException: La clave 'edad' debe ser int, recibido str: veinte
EstructuraInvalidaException: Falta la clave: email
{"nombre": "María", "edad": 30, "email": "maría@email.com"}
```

---

### Ejercicio 531: Multiplicación de matrices con validación
**Enunciado:** Escribeuna función `multiplicar_matrices(A, B)` que:
1. Valida que A y B sean listas de listas (matrices).
2. Valida que las filas de A y B tengan longitudes consistentes (matriz rectangular).
3. Valida que `len(A[0]) == len(B)` (incompatible para multiplicación).
4. Si alguna validación falla, lanza `MatricesInvalidasException` con mensaje descriptivo.
5. Si son válidas, multiplica y retorna la matriz resultante.
Define `MatricesInvalidasException` heredando de `Exception`.

**Entrada:**
```python
A = [[1, 2], [3, 4]]  # 2x2
B = [[5, 6], [7, 8]]  # 2x2
C = [[1, 2, 3]]       # 1x3
D = [[4], [5], [6]]   # 3x1
prueba_invalida = ([[1, 2], [3]], [[1], [2]])  # B no es rectangular
```
**Salida (A * B):** `[[19, 22], [43, 50]]`
**Salida (C * D):** `[[32]]`
**Salida (prueba_invalida):** `MatricesInvalidasException: La matriz B no es rectangular (filas de longitudes diferentes)`

---

### Ejercicio 532: Sistema de matrícula con excepciones de capacidad
**Enunciado:** Define `CursoLlenoException` y `AlumnoNoRegistradoException`. Implementauna clase `SistemaMatricula`:
1. `__init__(self, max_alumnos)` — capacidad máxima.
2. `inscribir(self, nombre, curso)` — si el curso ya tiene `max_alumnos` alumnos, lanza `CursoLlenoException(curso, max_alumnos)`; si el alumno ya está inscrito en ese curso, lanza `AlumnoYaInscritoException`; si no, agrega.
3. `desinscribir(self, nombre, curso)` — si el alumno no está en el curso, lanza `AlumnoNoRegistradoException`; si está, lo elimina.
4. `listar_curso(self, curso)` — retorna lista de nombres inscritos.
5. `total_inscritos(self)` — retorna cantidad total de inscripciones en todos los cursos.
El estado interno es `{curso: [nombres]}`.

**Entrada:**
```python
sistema = SistemaMatricula(max_alumnos=2)
sistema.inscribir("Ana", "Python")
sistema.inscribir("Luis", "Python")
sistema.inscribir("Carlos", "Python")  # lanza CursoLlenoException
sistema.inscribir("Ana", "Python")     # lanza AlumnoYaInscritoException
sistema.desinscribir("Ana", "Python")
sistema.inscribir("Carlos", "Python")  # ahora funciona
print(sistema.listar_curso("Python"))   # ["Luis", "Carlos"]
print(sistema.total_inscritos())        # 2
```

---

### Ejercicio 533: Validación de datos de sensores IoT
**Enunciado:** Define `DatosSensorInvalidosException` que acepte el nombre del sensor, el valor y el motivo. Dados los datos de un sensor como diccionario `{"nombre": ..., "valor": ..., "unidad": ..., "timestamp": ...}`, escritoa función `validar_sensor(datos)` que:
1. Verifica que nombre sea str no vacío.
2. Verifica que valor sea int o float y esté en rango válido (-100 a 1000, dependiendo del sensor — acepta cualquier número para este ejercicio).
3. Verifica que unidad sea uno de `["°C", "°F", "%", "lux", "dB"]`.
4. Verifica que timestamp sea un entero positivo (epoch).
5. Si todo es válido, retorna `True` y imprime un reporte: `"Sensor {nombre}: {valor} {unidad} a las {timestamp}"`.
6. Si no, lanza `DatosSensorInvalidosException`.

**Entrada:**
```python
sensores = [
    {"nombre": "Temperatura", "valor": 25.5, "unidad": "°C", "timestamp": 1699900000},
    {"nombre": "", "valor": 25.5, "unidad": "°C", "timestamp": 1699900000},
    {"nombre": "Humedad", "valor": "n/a", "unidad": "%", "timestamp": 1699900000},
    {"nombre": "Luz", "valor": 500, "unidad": "lux", "timestamp": -1},
    {"nombre": "Sonido", "valor": 45, "unidad": "dB", "timestamp": 1699900000},
]
```
**Salida:**
```
Sensor Temperatura: 25.5 °C a las 1699900000
DatosSensorInvalidosException: Sensor sin nombre (valor recibido: "")
DatosSensorInvalidosException: Valor no numérico para sensor Humedad: n/a
DatosSensorInvalidosException: Timestamp inválido para sensor Luz: -1
Sensor Sonido: 45 dB a las 1699900000
```

---

### Ejercicio 534: Excepciones en operaciones bancarias
**Enunciado:** Define `SaldoInsuficienteException`, `CuentaNoExistenteException`, `MontoInvalidoException`. Implementauna clase `Banco`:
1. `__init__(self)` — `self.cuentas = {}` donde cada cuenta es `{"titular": ..., "saldo": ..., "tipo": "ahorro"|"corriente"}`.
2. `crear_cuenta(self, titular, saldo_inicial, tipo="ahorro")` — crea la cuenta con número automático C001, C002...
3. `depositar(self, numero_cuenta, monto)` — si cuenta no existe, lanza `CuentaNoExistenteException`; si monto <= 0, lanza `MontoInvalidoException`; si todo ok, deposita y retorna nuevo saldo.
4. `retirar(self, numero_cuenta, monto)` — si cuenta no existe, lanza `CuentaNoExistenteException`; si monto <= 0, lanza `MontoInvalidoException`; si saldo < monto, lanza `SaldoInsuficienteException(cuenta, saldo_actual, monto_solicitado)`; sino, retira y retorna saldo restante.
5. `transferir(self, origen, destino, monto)` — combina retirar + depositar con las mismas validaciones.
6. `extracto(self, numero_cuenta)` — retorna una cadena formateada con titular, tipo, saldo y número de cuenta.

**Entrada:**
```python
banco = Banco()
banco.crear_cuenta("Ana", 1000, "ahorro")
banco.crear_cuenta("Luis", 500, "corriente")
print(banco.depositar("C001", 200))   # 1200
print(banco.retirar("C002", 300))     # 200
print(banco.transferir("C001", "C002", 100))  # None (transferencia ok)
print(banco.extracto("C001"))  # Cuenta C001: Ana | Tipo: ahorro | Saldo: $1100.00
```

---

### Ejercicio 535: Validador de formularios web simulado
**Enunciado:** Define `CampoInvalidoException` que reciba el nombre del campo, el valor recibido y el motivo. Escribeuna función `validar_formulario(formulario, esquema)` donde:
1. `formulario` es un diccionario `{campo: valor}`.
2. `esquema` es un diccionario `{campo: {"tipo": str|int|float, "requerido": bool, "validaciones": [funciones]}}`.
3. Para cada campo en el esquema:
   - Si es requerido y falta o es vacío: lanza `CampoInvalidoException(campo, valor, "Campo requerido")`.
   - Si el tipo no coincide: lanza con "Tipo inválido".
   - Ejecuta cada función de validación (que reciben el valor y retornan True/False o lanzan su propia excepción).
4. Si todo pasa, retorna el formulario limpio (valores convertidos al tipo correcto si es necesario).

**Entrada:**
```python
formulario = {
    "nombre": "Ana",
    "edad": 25,
    "email": "ANA@EMAIL.COM",
    "telefono": "",
}
esquema = {
    "nombre": {"tipo": str, "requerido": True, "validaciones": [lambda v: len(v) >= 2]},
    "edad": {"tipo": int, "requerido": True, "validaciones": [lambda v: 0 < v < 120]},
    "email": {"tipo": str, "requerido": True, "validaciones": []},
    "telefono": {"tipo": str, "requerido": False, "validaciones": []},
}
```
**Salida:**
```
{"nombre": "Ana", "edad": 25, "email": "ANA@EMAIL.COM", "telefono": ""}
```
*(El campo telefono está vacío pero no es requerido, así que pasa)*

---

### Ejercicio 536: Juego de adivinanza con excepciones de rango
**Enunciado:** Define `NumeroFueraDeRangoException` (recibe el número intentado y el rango válido) y `IntentosAgotadosException` (recibe la cantidad de intentos permitidos). Implementa el juego de adivinanza:
1. La computadora elige un número secreto entre 1 y 100 (puedes usar `random.randint`).
2. El jugador tiene 7 intentos.
3. Cada intento: si el input no es un entero, pide de nuevo (sin contar como intento); si está fuera de rango [1,100], lanza `NumeroFueraDeRangoException` y no cuenta; si es correcto, felicita y termina; si es incorrecto, dice "más alto" o "más bajo" y cuenta un intento.
4. Si se agotan los 7 intentos, lanza `IntentosAgotadosException` con el número secreto.
5. Escribe el juego en una función `jugar_adivinanza()` que maneje todo con try/except.

**Entrada:** (interactivo — el ejercicio define la lógica)
**Salida:** Depende de la ejecución — imprime pistas y mensajes de excepción según corresponda.

---

### Ejercicio 537: Excepciones para parser de expresiones matemáticas
**Enunciado:** Define `ExpresionInvalidaException` que reciba la expresión y el motivo. Escribeuna función `evaluar_expresion_simple(expresion)` que:
1. Tokeniza la expresión (solo números, +, -, *, /, paréntesis).
2. Valida que la expresión no esté vacía.
3. Valida que no haya caracteres no permitidos.
4. Valida que los paréntesis estén balanceados (contando `(` y `)`).
5. Si falla, lanza `ExpresionInvalidaException`.
6. Si es válida, evalúa con `eval()` (se asume segura por las validaciones) y retorna el resultado.
Escribir `probar_expresiones(lista)` que prueba varias expresiones y atrapa las excepciones mostrando el mensaje.

**Entrada:**
```python
expresiones = [
    "2 + 3 * 4",
    "(1 + 2) * (3 - 1)",
    "2 + + 3",
    "()",
    "2 ^ 3",  # operador no permitido
    "(((2 + 3)",  # paréntesis no balanceados
]
```
**Salida:**
```
"2 + 3 * 4" → 14
"(1 + 2) * (3 - 1)" → 6
"2 + + 3" → ExpresionInvalidaException: Doble operador consecutivo en "2 + + 3"
"()" → ExpresionInvalidaException: Expresión vacía o sin operando en "()"
"2 ^ 3" → ExpresionInvalidaException: Carácter no permitido '^' en "2 ^ 3"
"(((2 + 3)" → ExpresionInvalidaException: Paréntesis no balanceados en "(((2 + 3)"
```

---

### Ejercicio 538: Gestor de configuración con validaciones
**Enunciado:** Define `ConfiguracionInvalidaException` que reciba la clave, el valor y el motivo. Escribeuna clase `GestorConfiguracion` que:
1. `__init__(self, config_file)` — carga un archivo JSON de configuración (si no existe, crea uno vacio `{}`).
2. `obtener(self, clave, default=None)` — retorna el valor o default.
3. `establecer(self, clave, valor, tipo_expected=None)` — si `tipo_expected` está definido, valida el tipo; si no, lanza `ConfiguracionInvalidaException`; guarda y escribe el JSON.
4. `validar_ghost_tipo(self, clave, tipo)` — verifica que el valor existente sea del tipo esperado, sino lanza.
5. `guardar(self)` — escribe el diccionario en el archivo JSON.
6. `respaldar(self)` — copia el archivo actual a `config_file.bak` si existe.

**Entrada:**
```python
gestor = GestorConfiguracion("/tmp/config_test.json")
gestor.establecer("servidor", "localhost")
gestor.establecer("puerto", 8080, str)  # esto falla si tipo_expected es str pero valor es int
gestor.establecer("activo", True)
print(gestor.obtener("servidor"))  # "localhost"
print(gestor.obtener("no_existe", "default_val"))  # "default_val"
gestor.validar_ghost_tipo("puerto", int)  # ok
gestor.validar_ghost_tipo("servidor", int)  # lanza ConfiguracionInvalidaException
```

---

### Ejercicio 539: Validación de argumentos de función con decorador
**Enunciado:** Define `ArgumentoInvalidoException` que reciba el nombre del parámetro, el valor y el motivo. Escribeun decorador `validar_argumentos(**tipos_esperados)` que:
1. Wrapea la función para que, al llamarla, verifique que cada argumento esté en `tipos_esperados` y que su valor no sea `None` (si se especifica `no_none=True` en los kwargs del decorador).
2. Si un argumento falla, lanza `ArgumentoInvalidoException(parametro, valor, motivo)`.
3. Si todo es válido, llama a la función original y retorna su resultado.
Usa el decorador en una función `calcular_area_rectangulo(base, altura)` decorada con `@validar_argumentos(base=(int, float, {"no_none": True}), altura=(int, float, {"no_none": True}))`.

**Entrada:**
```python
@validar_argumentos(base=(int, float, {"no_none": True}), altura=(int, float, {"no_none": True}))
def calcular_area_rectangulo(base, altura):
    return base * altura

print(calcular_area_rectangulo(5, 10))  # 50
print(calcular_area_rectangulo(5, None))  # ArgumentoInvalidoException: altura=None no es válido (no_none=True)
print(calcular_area_rectangulo("5", 10))  # ArgumentoInvalidoException: base="5" no es int ni float
```

---

### Ejercicio 540: Sistema de cola con excepciones de capacidad
**Enunciado:** Define `ColaLlenaException` (recibe la capacidad máxima) y `ColaVaciaException`. Implementauna clase `Cola` con:
1. `__init__(self, capacidad=max)` — `self.items = []`, `self.capacidad = capacidad`.
2. `encolar(self, item)` — si `self.capacidad` es finita y `len(self.items) >= self.capacidad`, lanza `ColaLlenaException`; sino, agrega.
3. `desencolar(self)` — si está vacía, lanza `ColaVaciaException`; sino, retorna y elimina el primer elemento.
4. `ver_frente(self)` — retorna el primer elemento sin eliminarlo, lanza `ColaVaciaException` si vacía.
5. `esta_vacia(self)` — retorna bool.
6. `tamanio(self)` — retorna len.
7. `vaciar(self)` — vacía la cola.
Prueba con una cola de capacidad 3 y verifica las excepciones.

**Entrada:**
```python
q = Cola(capacidad=3)
q.encolar(1)
q.encolar(2)
q.encolar(3)
q.encolar(4)  # ColaLlenaException: La cola alcanzó su capacidad máxima de 3 elementos
print(q.desencolar())  # 1
print(q.ver_frente())   # 2
q.vaciar()
print(q.esta_vacia())  # True
q.desencolar()  # ColaVaciaException
```

---

### Ejercicio 541: Excepciones en API de base de datos simulada
**Enunciado:** Define `DBConnectionException`, `QueryInvalidaException`, `RegistroNoEncontradoException`. Implementauna clase `BaseDeDatosSimulada` que usa un diccionario interno `self.datos = {}` (tablas como claves, cada tabla es una lista de diccionarios — "filas"):
1. `conectar(self)` — simula conexión; si falla conexión (simulado aleatoriamente o fijo), lanza `DBConnectionException`.
2. `insertar(self, tabla, fila)` — agrega la fila a la tabla; si tabla no existe, la crea; retorna True.
3. `buscar(self, tabla, criterio)` — criterio es `{campo: valor}`; retorna la primera fila que coincida o lanza `RegistroNoEncontradoException(tabla, criterio)`.
4. `actualizar(self, tabla, criterio, nuevos_datos)` — busca y actualiza; si no encuentra, lanza `RegistroNoEncontradoException`.
5. `eliminar(self, tabla, criterio)` — busca y elimina; si no encuentra, lanza `RegistroNoEncontradoException`.
6. `listar(self, tabla)` — retorna toda la tabla.

**Entrada:**
```python
db = BaseDeDatosSimulada()
db.conectar()
db.insertar("usuarios", {"id": 1, "nombre": "Ana", "email": "ana@email.com"})
db.insertar("usuarios", {"id": 2, "nombre": "Luis", "email": "luis@email.com"})
print(db.buscar("usuarios", {"id": 1}))  # {"id": 1, "nombre": "Ana", "email": "ana@email.com"}
db.actualizar("usuarios", {"id": 1}, {"nombre": "Ana López"})
print(db.buscar("usuarios", {"id": 1}))  # {"id": 1, "nombre": "Ana López", "email": "ana@email.com"}
db.eliminar("usuarios", {"id": 2})
print(db.listar("usuarios"))  # [{"id": 1, "nombre": "Ana López", "email": "ana@email.com"}]
db.buscar("usuarios", {"id": 99})  # RegistroNoEncontradoException
```

---

### Ejercicio 542: Excepciones en sistema de reserva de videos
**Enunciado:** Define `VideoNoDisponibleException`, `ReservaInvalidaException`, `PerfilNoExisteException`. Implementauna clase `SistemaReservas` que maneja:
1. `__init__(self)` — `self.videos = {}` (`{id: {"titulo": ..., "duracion": ..., "disponible": bool}}`), `self.perfiles = {}` (`{perfil: [ids_reservados]}`).
2. `agregar_video(self, id, titulo, duracion)` — agrega video disponible.
3. `reservar(self, perfil, video_id)` — si perfil no existe, lanza `PerfilNoExisteException`; si video no existe, lanza `VideoNoDisponibleException`; si video no disponible, lanza `VideoNoDisponibleException`; si todo ok, marca no disponible y agrega al perfil.
4. `cancelar_reserva(self, perfil, video_id)` — si no está reservado por ese perfil, lanza `ReservaInvalidaException`; sino, marca disponible de nuevo y elimina de la reserva.
5. `ver_reservas(self, perfil)` — retorna lista de títulos reservados o `[]` si no hay.
6. `listar_disponibles(self)` — retorna lista de títulos disponibles.

**Entrada:**
```python
sys = SistemaReservas()
sys.agregar_video("V1", "Matrix", 136)
sys.agregar_video("V2", "Intelector", 160)
sys.agregar_video("V3", "Gladiador", 155)
sys.reservar("Ana", "V1")   # ok
sys.reservar("Ana", "V2")   # ok
sys.reservar("Luis", "V1")  # VideoNoDisponibleException (ya reservado por Ana)
sys.cancelar_reserva("Ana", "V1")  # ok
sys.reservar("Luis", "V1")  # ahora ok
print(sys.ver_reservas("Ana"))   # ["Intelector"]
print(sys.ver_reservas("Luis"))  # ["Matrix"]
print(sys.listar_disponibles())  # ["Gladiador"]
```

---

### Ejercicio 543: Excepciones en sistema de inventario dinámico
**Enunciado:** Define `ProductoNoExistenteException`, `StockInsuficienteException`, `PrecioInvalidoException`, `CantidadInvalidaException`. Implementauna clase `InventarioDinamico`:
1. `__init__(self)` — `self.productos = {}` (`{id: {"nombre": ..., "precio": ..., "cantidad": ...}}`).
2. `agregar_producto(self, id, nombre, precio, cantidad)` — si precio < 0, lanza `PrecioInvalidoException`; si cantidad < 0, lanza `CantidadInvalidaException`; agrega.
3. `vender(self, id, cantidad)` — si producto no existe, lanza `ProductoNoExistenteException`; si cantidad > stock, lanza `StockInsuficienteException(id, stock_actual, cantidad_solicitada)`; sino, reduce stock y retorna el monto de la venta (precio * cantidad).
4. `reabastecer(self, id, cantidad)` — agrega stock; si producto no existe, lanza `ProductoNoExistenteException`.
5. `obtener_valor_inventario(self)` — retorna suma de `precio * cantidad` de todos los productos.
6. `reporte_stock_bajo(self, umbral=5)` — retorna lista de ids con stock <= umbral.

**Entrada:**
```python
inv = InventarioDinamico()
inv.agregar_producto("P1", "Mouse", 50, 10)
inv.agregar_producto("P2", "Teclado", 120, 5)
print(inv.vender("P1", 3))   # 150
print(inv.vender("P1", 8))   # StockInsuficienteException: P1 tiene 7, se solicitaron 8
inv.reabastecer("P1", 10)
print(inv.obtener_valor_inventario())  # (17*50 + 5*120) = 850 + 600 = 1450
print(inv.reporte_stock_bajo(5))  # ["P2"]
```

---

### Ejercicio 544: Validación de estructura JSON anidada
**Enunciado:** Define `JSONInvalidoException` (recibe la clave/camino donde falló y el motivo), `TipoNoEsperadoException`. Escribeuna función `validar_json_esquema(data, esquema, camino="")` que:
1. Recibe `data` (diccionario o lista) y un `esquema` que define la estructura esperada: `{"tipo": dict|list|str|int|float|bool, "claves": {nombre: esquema_sub}, "items": esquema_elemento (para listas)}`.
2. Si el tipo de `data` no coincide con `esquema["tipo"]`, lanza `TipoNoEsperadoException(camino, tipo_esperado, tipo_recibido)`.
3. Si es dict, recorre cada clave del esquema y valida recursivamente.
4. Si es lista, valida cada elemento con `esquema["items"]`.
5. Si todo es válido, retorna `True`.

**Entrada:**
```python
esquema = {
    "tipo": dict,
    "claves": {
        "nombre": {"tipo": str},
        "edad": {"tipo": int},
        "hobbies": {
            "tipo": list,
            "items": {"tipo": str},
        },
    },
}
data_ok = {"nombre": "Ana", "edad": 25, "hobbies": ["leer", "codear"]}
data_bad_type = {"nombre": "Ana", "edad": "veinte", "hobbies": ["leer"]}
data_bad_hobby = {"nombre": "Ana", "edad": 25, "hobbies": ["leer", 3]}
data_missing = {"nombre": "Ana", "edad": 25}
```
**Salida:**
```
data_ok → True
data_bad_type → TipoNoEsperadoException: "edad" debe ser int, recibido str
data_bad_hobby → TipoNoEsperadoException: "hobbies[1]" debe ser str, recibido int
data_missing → JSONInvalidoException: Falta clave "hobbies" en datos
```

---

### Ejercicio 545: Manejo de errores en operaciones con archivos
**Enunciado:** Define `ArchivoLecturaException`, `ArchivoEscrituraException`, `FormatoInvalidoException`. Escribeuna función `leer_y_procesar_archivo(ruta, validar_linea_func)` que:
1. Intenta abrir el archivo en modo lectura.
2. Si el archivo no existe, lanza `ArchivoLecturaException(ruta, "No existe")`.
3. Si hay PermissionError, lanza `ArchivoLecturaException(ruta, "Sin permisos")`.
4. Lee línea por línea y aplica `validar_linea_func(linea)` a cada línea.
5. Si `validar_linea_func` lanza una excepción, atrapa y registra en una lista de errores, pero continúa.
6. Retorna una tupla `(lineas_validas, errores)` donde `lineas_validas` esuna lista de las líneas que pasaron validación y `errores` esuna lista de tuplas `(numero_linea, linea, error)`.
Escribeuna función `procesar_archivo_dump(ruta, datos, formato="txt")` que:
1. Si formato no es "txt" o "json", lanza `FormatoInvalidoException(formato)`.
2. Escribe los datos en el archivo (txt: cada dato en una línea; json: con json.dump).
3. Si hay PermissionError o IOError, lanza `ArchivoEscrituraException`.

**Entrada:**
```python
# Archivo de prueba: escribir con write_file antes
# contenido: "linea valida\n linea con error\n otra valida\n"
def validar(linea):
    linea = linea.strip()
    if not linea:
        raise ValueError("Línea vacía")
    if "error" in linea:
        raise ValueError("Contiene la palabra 'error'")
    return linea

lineas_validas, errores = leer_y_procesar_archivo("/tmp/test_archivo.txt", validar)
print(lineas_validas)  # ["linea valida", "otra valida"]
print(errores)  # [(2, " linea con error\n", "Contiene la palabra 'error'")]
```

---

### Ejercicio 546: Excepciones en sistema de mensajería
**Enunciado:** Define `MensajeDemasiadoLargoException` (recibe longitud máxima y longitud real), `PerfilBloqueadoException`, `CanalNoExistenteException`. Implementaun sistema de mensajería:
1. `__init__(self, max_mensaje_len=200)` — setea longitud máxima.
2. `crear_canal(self, nombre)` — crea canal si no existe; si ya existe, lanza `CanalExistenteException` (definir también).
3. `enviar_mensaje(self, canal, emisor, texto)` — si canal no existe, lanza `CanalNoExistenteException`; si `len(texto) > self.max_mensaje_len`, lanza `MensajeDemasiadoLargoException`; si emisor está bloqueado, lanza `PerfilBloqueadoException`; sino, agrega el mensaje al canal y retorna `True`.
4. `bloquear_perfil(self, emisor)` — marca perfil como bloqueado.
5. `desbloquear_perfil(self, emisor)` — desbloquea.
6. `obtener_mensajes(self, canal)` — retorna lista de mensajes del canal como `(emisor, texto, timestamp)`.
7. `listar_canales(self)` — retorna lista de nombres de canales.

**Entrada:**
```python
ms = SistemaMensajeria(max_mensaje_len=50)
ms.canal("general")
ms.canal("oficina")
ms.enviar_mensaje("general", "Ana", "Hola a todos")
ms.enviar_mensaje("general", "Luis", "Buenos días") * 10  # MensajeDemasiadoLargoException
ms.bloquear_perfil("Luis")
ms.enviar_mensaje("general", "Luis", "Hola")  # PerfilBloqueadoException
print(ms.obtener_mensajes("general"))  # [("Ana", "Hola a todos", ...)]
```

---

### Ejercicio 547: Excepciones en sistema de reserva de aeronaves
**Enunciado:** Define `AeronaveNoDisponibleException`, `RutaInvalidaException`, `HorarioConflictivoException`. Implementaun sistema de reserva de vuelos:
1. `__init__(self)` — `self.aeronaves = {}` (`{id: {"modelo": ..., "capacidad": ..., "disponible": bool}}`), `self.vuelos = {}` (`{id_vuelo: {"ruta": (origen, destino), "hora_salida": ..., "aeronave_id": ...}}`).
2. `registrar_aeronave(self, id, modelo, capacidad)` — agrega.
3. `crear_vuelo(self, id_vuelo, origen, destino, hora_salida, aeronave_id)` — si aeronave no existe, lanza `AeronaveNoExistenteException`; si aeronave no disponible, lanza `AeronaveNoDisponibleException`; si origen == destino, lanza `RutaInvalidaException`; si hay conflicto de horario (mismo aeronave en otra ruta a esa hora ± 1 hora), lanza `HorarioConflictivoException`; sino, crea el vuelo y marca aeronave no disponible.
4. `cancelar_vuelo(self, id_vuelo)` — elimina y marca aeronave disponible.
5. `buscar_vuelos(self, origen, destino)` — retorna lista de vuelos que coincidan.
6. `ver_disponibilidad(self, aeronave_id)` — retorna si está disponible.

**Entrada:**
```python
sys = SistemaVuelos()
sys.registrar_aeronave("A1", "Boeing 737", 180)
sys.registrar_aeronave("A2", "Airbus A320", 160)
sys.crear_vuelo("V1", "México", "Guadalajara", "08:00", "A1")
sys.crear_vuelo("V2", "México", "Guadalajara", "09:00", "A1")  # HorarioConflictivoException (±1hr)
sys.crear_vuelo("V3", "México", "Monterrey", "10:00", "A2")
print(sys.buscar_vuelos("México", "Guadalajara"))  # [V1]
print(sys.ver_disponibilidad("A1"))  # False (ocupado en V1)
sys.cancelar_vuelo("V1")
print(sys.ver_disponibilidad("A1"))  # True
```

---

### Ejercicio 548: Validaciones en sistema de encuestas
**Enunciado:** Define `RespuestaInvalidaException` (recibe la pregunta, el valor y el motivo), `EncuestaCerradaException` (recibe el id de la encuesta). Implementaun sistema de encuestas:
1. `__init__(self)` — `self.encuestas = {}` (`{id: {"pregunta": ..., "tipo": "abierta"|"multiple"|"_si_no", "opciones": [...], "respuestas": [], "cerrada": bool}}`).
2. `crear_encuesta(self, id, pregunta, tipo, opciones=None)` — crea.
3. `responder(self, id, respondent, respuesta)` — si encuesta no existe, lanza `EncuestaNoExistenteException`; si está cerrada, lanza `EncuestaCerradaException`; si el tipo es "multiple" y la respuesta no está en opciones, lanza `RespuestaInvalidaException`; si el tipo es "_si_no" y la respuesta no es "sí" o "no", lanza; sino, agrega la respuesta.
4. `cerrar_encuesta(self, id)` — marca como cerrada.
5. `resultados(self, id)` — retorna diccionario con conteo de respuestas.
6. `estadisticas(self, id)` — retorna `{"total_respuestas": N, "respuestas_unicas": M, "moda": valor_mas_frecuente}`.

**Entrada:**
```python
enc = SistemaEncuestas()
enc.crear_encuesta("E1", "¿Te gusta Python?", "_si_no")
enc.crear_encuesta("E2", "¿Qué lenguaje prefieres?", "multiple", ["Python", "Java", "C++", "JavaScript"])
enc.responder("E1", "Ana", "sí")
enc.responder("E1", "Luis", "no")
enc.responder("E2", "Ana", "Python")
enc.responder("E2", "Luis", "JavaScript")
enc.responder("E2", "Carlos", "Rust")  # RespuestaInvalidaException
enc.cerrar_encuesta("E1")
enc.responder("E1", "María", "sí")  # EncuestaCerradaException
print(enc.resultados("E1"))  # {"sí": 1, "no": 1}
print(enc.estadisticas("E2"))  # {"total_respuestas": 2, "respuestas_unicas": 2, "moda": "Python" (empate, primero)}

```

---

### Ejercicio 549: Excepciones en sistema de biblioteca
**Enunciado:** Define `LibroNoDisponibleException`, `UsuarioNoRegistradoException`, `PrestamoInvalidoException`, `MultaExcedidaException`. Implementauna clase `Biblioteca`:
1. `__init__(self)` — `self.libros = {}` (`{isbn: {"titulo": ..., "autor": ..., "disponible": bool}}`), `self.usuarios = {}` (`{id: {"nombre": ..., "prestamos": [isbn], "multa": float}}`).
2. `registrar_libro(self, isbn, titulo, autor)` — agrega libro disponible.
3. `registrar_usuario(self, id, nombre)` — agrega usuario con multa 0.
4. `prestar(self, isbn, usuario_id)` — si libro no existe, lanza `LibroNoExistenteException`; si no disponible, lanza `LibroNoDisponibleException`; si usuario no existe, lanza `UsuarioNoRegistradoException`; si el usuario ya tiene 3 préstamos, lanza `PrestamoInvalidoException(usuario_id, "Máximo 3 préstamos simultáneos")`; sino, marca libro no disponible, agrega a préstamos del usuario.
5. `devolver(self, isbn, usuario_id)` — si no está prestado por ese usuario, lanza `PrestamoInvalidaException`; sino, marca disponible y elimina del usuario.
6. `acumular_multa(self, usuario_id, monto)` — suma multa; si supera 500, lanza `MultaExcedidaException(usuario_id, multa_total)`.
7. `pagar_multa(self, usuario_id)` — resetea multa a 0 si tiene saldo.
8. `buscar_libro(self, isbn)` — retorna info del libro o lanza.
9. `listar_prestamos(self, usuario_id)` — retorna lista de títulos prestados.

**Entrada:**
```python
bib = Biblioteca()
bib.registrar_libro("ISBN1", "Cien años de soledad", "Gabriel García Márquez")
bib.registrar_libro("ISBN2", "1984", "George Orwell")
bib.registrar_usuario("U1", "Ana")
bib.registrar_usuario("U2", "Luis")
bib.prestar("ISBN1", "U1")
bib.prestar("ISBN2", "U1")
bib.prestar("ISBN1", "U2")  # LibroNoDisponibleException
bib.devolver("ISBN1", "U1")
bib.prestar("ISBN1", "U2")  # ahora ok
bib.acumular_multa("U1", 200)
bib.acumular_multa("U1", 350)  # MultaExcedidaException: U1 tiene multa total de $550
print(bib.listar_prestamos("U2"))  # ["Cien años de soledad"]
```

---

### Ejercicio 550: Excepciones en sistema de reserva de salas
**Enunciado:** Define `SalaNoDisponibleException`, `IntervaloInvalidoException`, `ReservaSuperpuestaException`. Implementauna clase `SistemaReservasSalas`:
1. `__init__(self)` — `self.salas = {}` (`{id_sala: {"nombre": ..., "capacidad": ..., "reservas": [(hora_inicio, hora_fin, motivo), ...]}}`).
2. `crear_sala(self, id, nombre, capacidad)` — agrega sala.
3. `reservar(self, id_sala, hora_inicio, hora_fin, motivo)` — valida que `hora_inicio < hora_fin` (si no, `IntervaloInvalidoException`); valida que no haya solapamiento con reservas existentes (si hay, `ReservaSuperpuestaException`); si sala no existe, lanza `SalaNoExistenteException`; si sala no disponible en ese intervalo, lanza `SalaNoDisponibleException`; sino, agrega la reserva.
4. `cancelar_reserva(self, id_sala, hora_inicio)` — elimina la reserva con esa hora de inicio.
5. `disponibilidad(self, id_sala, hora_inicio, hora_fin)` — retorna `True` si hay disponibilidad en ese intervalo (sin solapamientos).
6. `calendario(self, id_sala)` — retorna lista de reservas ordenadas por hora de inicio.

**Entrada:**
```python
sys = SistemaReservasSalas()
sys.crear_sala("S1", "Sala de Reuniones A", 10)
sys.reservar("S1", 9, 11, "Reunión de equipo")
sys.reservar("S1", 10, 12, "Presentación")  # ReservaSuperpuestaException (solapama con 9-11)
sys.reservar("S1", 14, 16, "Entrevista")
print(sys.disponibilidad("S1", 12, 14))  # True
print(sys.calendario("S1"))  # [(9, 11, "Reunión de equipo"), (14, 16, "Entrevista")]
sys.cancelar_reserva("S1", 9)
print(sys.calendario("S1"))  # [(14, 16, "Entrevista")]
```

---

## BLOQUE 3 · RECURSIVIDAD AVANZADA (551–575)

### Ejercicio 551: Suma recursiva de dígitos hasta single digit
**Enunciado:** Escribeuna función recursiva `suma_digitos_recursiva(n)` que sume los dígitos de un número entero positivo. Luego, escribe `digital_root(n)` que repite la suma de dígitos hasta obtener un solo dígito (raíz digital), usando recursividad. Valida con ejemplos.

**Entrada:** `digital_root(9875)` → 9+8+7+5=29 → 2+9=11 → 1+1=2
**Salida:** `2`
**Entrada:** `digital_root(12345)` → 1+2+3+4+5=15 → 6
**Salida:** `6`

---

### Ejercicio 552: Torres de Hanoi recursivas con registro
**Enunciado:** Implementa las Torres de Hanoi recursivamente: `hanoi(n, origen, destino, auxiliar)` que imprima cada movimiento. Modificapa la función para que retorne una lista de tuplas `(disco, desde, hacia)` de todos los movimientos realizados. Luego, escribe `contar_movimientos(n)` que retorne la cantidad mínima de movimientos (2^n - 1) y compara con la lista retornada.

**Entrada:** `movimientos = hanoi(3, "A", "C", "B")`
**Salida (lista de movimientos):**
```python
[
    (1, "A", "C"),
    (2, "A", "B"),
    (1, "C", "B"),
    (3, "A", "C"),
    (1, "B", "A"),
    (2, "B", "C"),
    (1, "A", "C"),
]
```
`len(movimientos) == 7 == 2^3 - 1`

---

### Ejercicio 553: Recursividad con memoization para Fibonacci
**Enunciado:** Implementauna función `fibonacci_recursivo(n)` que calcule Fibonacci de forma recursiva simple (sin memo). Luego, implementa `fibonacci_memo(n, memo={})` que usa un diccionario memo para almacenar resultados previos. Compara el rendimiento imprimiendo el número de llamadas para `n=30` en ambos casos (usauna variable global o un contador pasado como parámetro). Finalmente, escribe `fibonacci_secuencia(n)` que retorne una lista con los primeros `n` números de Fibonacci usando memo.

**Entrada:** `fibonacci_secuencia(10)` → `[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]`
**Salida:** la lista y el conteo de llamadas para n=30 (recursivo simple: ~2.6 millones de llamadas; con memo: 30 llamadas)

---

### Ejercicio 554: Recursividad para permutaciones
**Enunciado:** Escribeuna función recursiva `permutaciones(lista)` que retorneuna lista de todas las permutaciones posibles de los elementos de la lista. La estrategia: para cada elemento, genera las permutaciones del resto y prependea el elemento. Retorna una lista de tuplas.

**Entrada:** `permutaciones([1, 2, 3])`
**Salida:**
```python
[(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]
```

---

### Ejercicio 555: Recursividad para subset (subconjuntos)
**Enunciado:** Escribeuna función recursiva `subconjuntos(lista)` que retorneuna lista de todos los subconjuntos posibles (el conjunto potencia). Cada subconjunto esuna tupla. La estrategia: para cada elemento, genera los subconjuntos del resto y une con y sin ese elemento.

**Entrada:** `subconjuntos([1, 2, 3])`
**Salida:**
```python
[(), (1,), (2,), (3,), (1, 2), (1, 3), (2, 3), (1, 2, 3)]
```

---

### Ejercicio 556: Recursividad para árbol de expresión matemática
**Enunciado:** Dada una expresión en notación prefija (operador primero), escritoa función recursiva `evaluar_prefija(tokens)` que evalúa la expresión. Los tokens sonuna lista de strings. Los operadores válidos son `+`, `-`, `*`, `/` y los operandos son números. Si encuentra un operador, recursivamente evalúa sus dos operandos. Si es número, retorna el float.

**Entrada:** `evaluar_prefija(["+", "*", 3, 4, 5])` → + ( * (3,4) , 5 ) = + (12, 5) = 17
**Salida:** `17`
**Entrada:** `evaluar_prefija(["*", "+", 2, 3, 4])` → * (+ (2,3), 4) = * (5, 4) = 20
**Salida:** `20`

---

### Ejercicio 557: Recursividad para búsqueda en espiral de matriz
**Enunciado:** Dadauna matriz cuadrada `n x n`, escritoa función recursiva `espiral_recursiva(matriz, inicio_fila, inicio_columna, fin_fila, fin_columna, resultado)` que recorra la matriz en espiral (arriba→derecha→abajo→izquierda) y agrega los elementos a `resultado`. La función se llama recursivamente con los límites actualizados. Retorne `resultado`.

**Entrada:**
```python
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
]
```
**Salida:** `[1, 2, 3, 6, 9, 8, 7, 4, 5]`

---

### Ejercicio 558: Recursividad para fractales de texto
**Enunciado:** Implementa una función recursiva `fractal_carpet(n)` que dibuje el fractal "carpet" de Sierpinski en texto para nivel `n`. Para `n=0`, es una "██". Para `n=1`, es una matriz 3x3 con el centro vacío. Para `n=2`, esuna matriz 9x9, etc. Retorna la representación como lista de strings (filas). El patrón: cada celda de nivel `n` es una matriz 3x3 de nivel `n-1`, con el centro vacío.

**Entrada:** `fractal_carpet(1)` → lista de 3 filas
**Salida:**
```
["███", "█ █", "███"]
```
**Entrada:** `fractal_carpet(2)` → lista de 9 filas, patrón recursivo

---

### Ejercicio 559: Recursividad para evaluar expresiones booleanas
**Enunciado:** Dada una expresión booleana en notación prefija como lista de tokens (operadores `AND`, `OR`, `NOT`; operandos `True`, `False`), escritoa función recursiva `evaluar_booleano(tokens)` que evalúa la expresión. `NOT` toma un operando; `AND` y `OR` toman dos. Retorna `True` o `False`.

**Entrada:** `evaluar_booleano(["AND", "OR", "True", "False", "True"])` → AND( OR(True, False), True ) = AND(True, True) = True
**Salida:** `True`
**Entrada:** `evaluar_booleano(["NOT", "AND", "True", "False"])` → NOT(AND(True, False)) = NOT(False) = True
**Salida:** `True`

---

### Ejercicio 560: Recursividad para descomposición prima
**Enunciado:** Escribeuna función recursiva `factorizar_primos(n, divisor=2, factores=None)` que retorne una lista de los factores primos de `n`. La estrategia: si `n % divisor == 0`, agrega el divisor y recursa con `n // divisor`; sino, prueba el siguiente divisor (divisor + 1 o divisor + 2 si es par). Optimiza: si `divisor * divisor > n`, n es primo, agrega y termina.

**Entrada:** `factorizar_primos(84)`
**Salida:** `[2, 2, 3, 7]` (84 = 2^2 * 3 * 7)
**Entrada:** `factorizar_primos(17)` → `[17]`
**Salida:** `[17]`

---

### Ejercicio 561: Recursividad para el problema de las N reinas
**Enunciado:** Implementauna solución recursiva al problema de las N reinas: `n_reinas(n)` que retorneuna lista de todas las soluciones posibles, donde cada solución esuna tupla de `n` enteros que representan la posición de la reina en cada fila (columna 0-based). La validación verifica que no hay dos reinas en la misma columna o diagonal.

**Entrada:** `n_reinas(4)`
**Salida:**
```python
[(1, 3, 0, 2), (2, 0, 3, 1)]  # dos soluciones para 4 reinas
```
**Nota:** Este ejercicio es complejo — la implementación puede usar backtracking recursivo.

---

### Ejercicio 562: Recursividad para recorrido de laberinto
**Enunciado:** Dado un laberinto como matriz de 0s (pasillo) y 1s (pared), y una posición inicial `(fila, col)` y posición final `(fila_dest, col_dest)`, escritoa función recursiva `resolver_laberinto(laberinto, fila, col, camino, visitado)` que retorne `True` si hay camino y `camino` es la lista de posiciones recorridas, o `False` si no hay. Usa backtracking: marca como visitado, prueba los 4 direcciones, si no funciona, backtracks.

**Entrada:**
```python
laberinto = [
    [0, 1, 0, 0, 0],
    [0, 1, 0, 1, 0],
    [0, 0, 0, 1, 0],
    [1, 1, 0, 1, 0],
    [0, 0, 0, 0, 0],
]
inicio = (0, 0)
fin = (4, 4)
```
**Salida:** `True` y `camino` como lista de coordenadas que llega de (0,0) a (4,4) sin pasar por paredes.

---

### Ejercicio 563: Recursividad para parsear expresiones con paréntesis anidados
**Enunciado:** Dadauna cadena con una expresión matemática con paréntesis anidados (ej. `"((2+3)*(4-1))"`), escritoa función recursiva `parsear_expresion(cadena, inicio=0)` que retorne un diccionario con la estructura parseada. La función busca el primer paréntesis de apertura, encuentra el de cierre correspondiente (contando balance), y recursivamente parsea el interior.

**Entrada:** `parsear_expresion("((2+3)*(4-1))")`
**Salida (estructura aproximada):**
```python
{
    "tipo": "parentesis",
    "contenido": [
        {"tipo": "parentesis", "contenido": [{"tipo": "numero", "valor": 2}, {"tipo": "operador", "valor": "+"}, {"tipo": "numero", "valor": 3}]},
        {"tipo": "operador", "valor": "*"},
        {"tipo": "parentesis", "contenido": [{"tipo": "numero", "valor": 4}, {"tipo": "operador", "valor": "-"}, {"tipo": "numero", "valor": 1}]},
    ],
}
```

---

### Ejercicio 564: Recursividad para algoritmo de Euclides extendido
**Enunciado:** Implementa el algoritmo de Euclides para calcular el MCD de dos números de forma recursiva: `mcd(a, b)` → si `b == 0` retorna `a`, sino `mcd(b, a % b)`. Luego, implementa `mcd_extendido(a, b)` que retorna una tupla `(mcd, x, y)` tales que `a*x + b*y = mcd` (algoritmo extendido recursivo). Finalmente, escribe `inverso_modular(a, m)` que usa `mcd_extendido` para encontrar el inverso de `a` módulo `m` (si existe), o lanza `InversoModularException` si no existe ( cuando mcd(a,m) != 1).

**Entrada:** `mcd_extendido(48, 18)` → `(6, -1, 3)` porque 48*(-1) + 18*3 = 6
**Entrada:** `inverso_modular(3, 7)` → `5` porque 3*5 = 15 ≡ 1 (mod 7)
**Entrada:** `inverso_modular(2, 4)` → `InversoModularException` porque mcd(2,4)=2 ≠ 1

---

### Ejercicio 565: Recursividad para dividir y conquistar — búsqueda en matriz ordenada
**Enunciado:** Dadauna matriz `n x m` donde cada fila está ordenada y la última columna es el "pivote" para la siguiente fila (matriz totalmente ordenada si se lee fila por fila), escritoa función recursiva `buscar_matriz_ordenada(matriz, valor, inicio_fila, fin_fila, inicio_col, fin_col)` que usa búsqueda binaria divid-y-conquers. Retorna `(fila, columna)` si encuentra, o `(-1, -1)` si no.

**Entrada:**
```python
matriz = [
    [1,  3,  5,  7],
    [10, 11, 16, 20],
    [23, 30, 34, 60],
]
buscar_matriz_ordenada(matriz, 16, 0, 2, 0, 3)  → (1, 3)
buscar_matriz_ordenada(matriz, 15, 0, 2, 0, 3)  → (-1, -1)
```

---

### Ejercicio 566: Recursividad para generar fractales de curvas
**Enunciado:** Implementa la curva de Koch recursivamente: `curva_koch(nivel, longitud)` que retorne una lista de tuplas `(angulo, longitud)` que representan los segmentos de la curva. Para `nivel=0`, es un segmento recto. Para `nivel>0`, se divide en 4 segmentos con ángulos de 60° en el medio. Usa la recursividad para construir la curva.

**Entrada:** `curva_koch(1, 100)` → lista de 4 segmentos
**Salida (aproximada):** `[(0, 100/3), (60, 100/3), (-60, 100/3), (0, 100/3)]` para nivel 1

---

### Ejercicio 567: Recursividad para resolver una expresión postfix (notación postfija)
**Enunciado:** Dadauna lista de tokens en notación postfija (operandos primero, operadores al final), escritoa función recursiva `evaluar_postfija(tokens)` que evalúa usandouna stack implícita en la recursividad. La estrategia recursiva: el último operador es el último token; los operandos son los resultados de evaluar las sub-expresiones. Implementa esto recursivamente sin usar una stack explícita.

**Entrada:** `evaluar_postfija([2, 3, "+", 4, "*"])` → (2+3)*4 = 20
**Salida:** `20`
**Entrada:** `evaluar_postfija([5, 1, 2, "+", "4", "*", "+"])` → 5 + ((1+2)*4) = 5 + 12 = 17
**Salida:** `17`

---

### Ejercicio 568: Recursividad para algoritmo de Dijkstra simplificado en árbol
**Enunciado:** Dado un árbol representado como diccionario `{nodo: [(vecino, peso), ...]}` y un nodo raíz, escritoa función recursiva `distancias_minimas(arbol, nodo_actual, visitado, distancias)` que calcula las distancias mínimas desde la raíz a todos los nodos usando DFS recursivo (el árbol garantiza que no hay ciclos, así que no hace falta el algoritmo completo de Dijkstra). Retorna el diccionario de distancias.

**Entrada:**
```python
arbol = {
    "A": [("B", 5), ("C", 3)],
    "B": [("D", 2), ("E", 4)],
    "C": [("F", 6)],
    "D": [],
    "E": [("F", 1)],
    "F": [],
}
distancias_minimas(arbol, "A", set(), {})
```
**Salida:**
```python
{"A": 0, "B": 5, "C": 3, "D": 7, "E": 9, "F": 9}
```

---

### Ejercicio 569: Recursividad para evaluar expresiones lambda simples
**Enunciado:** Implementa un evaluador de expresiones lambda muy simplificado para entender recursividad aplicada a funciones. Defineuna función `evaluar_expresion_lambda(expr, env)` donde `expr` puede ser:
1. Un número → retorna el número.
2. Una variable (string) → busca en `env` (diccionario de entorno).
3. Una llamada `["funcion", nombre, arg]` → busca la función en `env` y la aplica recursivamente.
4. Una lambda `["lambda", param, cuerpo]` → retorna una función que, al ser llamada, evalúa el cuerpo con el parámetro sustituido.
Usa esto para evaluar `["lambda", "x", ["lambda", "y", ["+", "x", "y"]]]` aplicado a 3 y luego a 5, que debe retornar 8.

**Entrada:**
```python
env = {
    "+": lambda a, b: a + b,
    "*": lambda a, b: a * b,
}
# Evaluar: (lambda x: (lambda y: x + y)) (3) (5)
```
**Salida:** `8`

---

### Ejercicio 570: Recursividad para algoritmo de Kruskal (árbol de expansión mínima simplificado)
**Enunciado:** Implementaun algoritmo de Kruskal simplificado para encontrar el árbol de expansión mínima de un grafo no dirigido con pesos, usando recursividad para verificar ciclos. Dado un grafo como lista de tuplas `(u, v, peso)`, ordena por peso y agrega aristas al árbol si no forman ciclo (usandouna función recursiva `forma_ciclo(arbol_actual, nueva_arista)` que hace DFS para verificar conectividad entre los nodos de la nueva arista). Retorna el árbol de expansión mínima como lista de aristas.

**Entrada:**
```python
aristas = [
    ("A", "B", 1),
    ("B", "C", 2),
    ("A", "C", 3),
    ("C", "D", 4),
    ("B", "D", 5),
]
```
**Salida:** `[("A", "B", 1), ("B", "C", 2), ("C", "D", 4)]` (costo total: 7)

---

### Ejercicio 571: Recursividad para resolver sistemas de ecuaciones lineales (eliminación gaussiana recursiva)
**Enunciado:** Implementa la eliminación gaussiana de forma recursiva para resolver un sistema de ecuaciones lineales representado como matriz aumentada. La función `eliminacion_gaussiana_recursiva(matriz)` hace:
1. Si la matriz es 1x1, retorna la solución.
2. Si no, encuentra el pivote, elimina la primera columna en las filas debajo, y recursa con la submatriz.
3. Retorna la solución como lista.
Simplificado para matrices pequeñas (2x2, 3x3).

**Entrada:**
```python
# Sistema: 2x + y = 5, x + y = 3 → solución: x=2, y=1
matriz = [
    [2, 1, 5],
    [1, 1, 3],
]
```
**Salida:** `[2, 1]` (x=2, y=1)

---

### Ejercicio 572: Recursividad para codificación Run-Length de listas anidadas
**Enunciado:** Dadauna lista que puede contener sublistas anidadas arbitrariamente, escritoa función recursiva `rle_anidado(lista)` que comprima usando run-length: secuencias consecutivas del mismo elemento se comprimen en `(elemento, cantidad)`. Para sublistas, se aplica recursivamente. Retorne la lista comprimida.

**Entrada:** `rle_anidado([1, 1, 1, [2, 2, 3], 1, 1])`
**Salida:** `[(1, 3), [(2, 2), (3, 1)], (1, 2)]`

---

### Ejercicio 573: Recursividad para dibujar un triángulo de Sierpinski con caracteres
**Enunciado:** Implementauna función recursiva `sierpinski_pascal(n)` que dibuje el triángulo de Sierpinski usando el triángulo de Pascal: calcula el triángulo de Pascal hasta la fila `n`, y para cada número, si es impar, dibuja "█", si es par, dibuja " " (espacio). Retorna la lista de filas como strings.

**Entrada:** `sierpinski_pascal(5)`
**Salida (aproximada):**
```
    █
   █ █
  █   █
 █ █ █ █
█████████
```

---

### Ejercicio 574: Recursividad para algoritmo de Huffman (árbol de codificación)
**Enunciado:** Implementa un generador de códigos Huffman básico usando recursividad. Dada una frecuencia de caracteres `{caracter: frecuencia}`, el algoritmo construye un árbol binario mergeando los dos nodos de menor frecuencia recursivamente hasta quedar uno solo. Luego, genera los códigos recorriendo el árbol. Escribe `huffman_codes(frecuencias)` que retorne un diccionario `{caracter: codigo_binario}`.

**Entrada:** `huffman_codes({"a": 5, "b": 9, "c": 12, "d": 13, "e": 16, "f": 45})`
**Salida (ejemplo):**
```python
{"a": "000", "b": "001", "c": "01", "d": "10", "e": "11", "f": "..."}  # los códigos reales dependen de la implementación específica
```

---

### Ejercicio 575: Recursividad para el problema de la mochila (backtracking)
**Enunciado:** Implementa una solución recursiva con backtracking al problema de la mochila 0/1: dada una lista de tuplas `(peso, valor)` y una capacidad máxima `W`, `mochila_recursiva(items, W, indice=0, peso_actual=0, valor_actual=0, mejor=None)` que retorne el máximo valor achievable y la lista de items seleccionados. El backtracking intenta incluir o no cada item.

**Entrada:**
```python
items = [(2, 3), (3, 4), (4, 5), (5, 6)]  # (peso, valor)
capacidad = 8
```
**Salida:** `(valor_maximo, items_seleccionados)` → `(10, [(2, 3), (3, 4), (3... o similar]))`
*Nota: el resultado exacto depende de la selección — valor máximo posible con capacidad 8 es 10 (elegir items de peso 3+5=8, valor 4+6=10, o 2+3+3=8...)*

---

## BLOQUE 4 · ARCHIVOS, ÁMBITO DE VARIABLES Y FUNCIONES AVANZADAS (576–600)

### Ejercicio 576: Lectura y procesamiento de archivo CSV simulado
**Enunciado:** Crea un archivo CSV de prueba con contenido:
```
nombre,edad,ciudad,salario
Ana,25,México,50000
Luis,30,Guadalajara,60000
María,28,México,55000
Carlos,35,Monterrey,70000
Pedro,32,Guadalajara,62000
```
Escribe una función `procesar_csv(archivo)` que:
1. Lea el archivo línea por línea con `open()`.
2. Saltee la primera línea (encabezados).
3. Parse cada línea como `nombre,edad,ciudad,salario`.
4. Agrupe por ciudad y calcule el promedio de salario por ciudad.
5. Retorne un diccionario `{ciudad: {"promedio": salario_promedio, "cantidad": N, "nombres": [lista de nombres]}}`.
6. Además, retorne la ciudad con el mayor salario promedio.

**Entrada:** (el archivo `/tmp/test_data.csv` con el contenido de arriba)
**Salida:**
```python
{
    "México": {"promedio": 52500.0, "cantidad": 2, "nombres": ["Ana", "María"]},
    "Guadalajara": {"promedio": 61000.0, "cantidad": 2, "nombres": ["Luis", "Pedro"]},
    "Monterrey": {"promedio": 70000.0, "cantidad": 1, "nombres": ["Carlos"]},
}
Ciudad con mayor promedio: Monterrey ($70000.00)
```

---

### Ejercicio 577: Escritura de reporte formateado en archivo
**Enunciado:** Dados los datos de un reporte de ventas (lista de diccionarios con `producto`, `cantidad`, `precio_unitario`, `fecha`), escribeuna función `generar_reporte_ventas(ventas, archivo_salida)` que:
1. Calcula el total por producto (suma de `cantidad * precio`).
2. Calcula el total general.
3. Escribe en el archivo de salida un reporte formateado con encabezado, línea de cada venta, y resumen final.
4. Usa `with open()` para manejar el archivo.
5. Formatea los números con `:.2f` para moneda.

**Entrada:**
```python
ventas = [
    {"producto": "Mouse", "cantidad": 10, "precio_unitario": 50, "fecha": "2024-01-15"},
    {"producto": "Teclado", "cantidad": 5, "precio_unitario": 120, "fecha": "2024-01-15"},
    {"producto": "Mouse", "cantidad": 7, "precio_unitario": 55, "fecha": "2024-01-16"},
]
generar_reporte_ventas(ventas, "/tmp/reporte_ventas.txt")
```
**Salida (contenido del archivo):**
```
=== REPORTE DE VENTAS ===
Fecha: 2024-01-15 a 2024-01-16

Producto      Cantidad   Precio Unit.   Total
--------------------------------------------------
Mouse                10        $50.00   $500.00
Teclado               5       $120.00   $600.00
Mouse                 7        $55.00   $385.00
--------------------------------------------------
Total general: $1,485.00

=== RESUMEN POR PRODUCTO ===
Mouse: 17 unidades, $885.00
Teclado: 5 unidades, $600.00
```
*(Nota: el archivo se escribe con `with open(archivo_salida, "w") as f:`)*

---

### Ejercicio 578: Ámbito de variables — funciones anidadas y nonlocal
**Enunciado:** Escribeuna función `contador_avanzado()` que:
1. Define una variable `contador = 0` en su ámbito local.
2. Define una función anidada `incrementar(cantidad=1)` que usa `nonlocal contador` para incrementar el contador.
3. Define una función anidada `decrementar(cantidad=1)` que usa `nonlocal contador` para decrementar (no permite que sea negativo).
4. Define una función anidada `resetear()` que usa `nonlocal contador` para ponerlo a 0.
5. Define una función anidada `obtener()` que retorna el valor actual.
6. Retorna un diccionario con las funciones `{incrementar, decrementar, resetear, obtener}`.

Prueba creando un contador y llamando a las funciones.

**Entrada:**
```python
c = contador_avanzado()
c["incrementar"]()
c["incrementar"](5)
print(c["obtener"]())  # 6
c["decrementar"](3)
print(c["obtener"]())  # 3
c["decrementar"](10)  # No permite negativo, queda en 0
print(c["obtener"]())  # 0
c["resetear"]()
print(c["obtener"]())  # 0
```

---

### Ejercicio 579: Ámbito de variables — funciones como objetos y closures
**Enunciado:** Escribeuna función `crear_multiplicador(factor)` que retorneuna función anidada que multiplica su argumento por `factor`. Demuestra el concepto de closure: la función retornada "recuerda" el valor de `factor` incluso después de que `crear_multiplicador` ha terminado. Luego, escribeuna función `aplicar_transformaciones(valor, transformaciones)` que toma una lista de funciones (cada una es un closure) y aplica todas secuencialmente.

**Entrada:**
```python
doble = crear_multiplicador(2)
triple = crear_multiplicador(3)
print(doble(5))    # 10
print(triple(5))   # 15
print(aplicar_transformaciones(5, [doble, triple]))  # 30 (primero doble → 10, luego triple → 30)
```
**Salida:** `10`, `15`, `30`

---

### Ejercicio 580: Lectura de archivo de configuración INI simulado
**Enunciado:** Crea un archivo de configuración de prueba con formato estilo INI:
```
[database]
host = localhost
port = 5432
user = admin

[server]
host = 0.0.0.0
port = 8080
debug = true
```
Escribeuna función `parsear_ini(archivo)` que:
1. Lea el archivo línea por línea.
2. Identifique las secciones entre `[` y `]`.
3. Identifique los pares `clave = valor` dentro de cada sección.
4. Retorne un diccionario anidado `{seccion: {clave: valor}}`.
5. Los valores deben ser convertidos a int si son numéricos, a bool si son "true"/"false" (case-insensitive), o se mantienen como str.

**Entrada:** (el archivo `/tmp/test_config.ini` con el contenido de arriba)
**Salida:**
```python
{
    "database": {"host": "localhost", "port": 5432, "user": "admin"},
    "server": {"host": "0.0.0.0", "port": 8080, "debug": True},
}
```

---

### Ejercicio 581: Función con *args y **kwargs para logging
**Enunciado:** Escribeuna función `log_ejecucion(*args, **kwargs)` que:
1. Formatee todos los argumentos posicionales (`*args`) como una lista con sus valores.
2. Formatee todos los argumentos nominales (`**kwargs`) como pares clave=valor.
3. Retorne una cadena con el formato: `"Ejecución con args: [lista de args] y kwargs: {diccionario de kwargs}"`.
4. Escribeuna segunda función `ejecutar_con_log(func, *args, **kwargs)` que:
   - Imprime el log antes de ejecutar (usando `log_ejecucion`).
   - Ejecuta la función con los argumentos.
   - Imprime el resultado.
   - Retorna el resultado.

**Entrada:**
```python
def suma(a, b):
    return a + b

ejecutar_con_log(suma, 5, 10, verbose=True, modo="test")
```
**Salida:**
```
Ejecución con args: [5, 10] y kwargs: {'verbose': True, 'modo': 'test'}
Resultado: 15
```

---

### Ejercicio 582: Escritura y lectura de datos serializados (JSON)
**Enunciado:** Define una lista de diccionarios complejos `datos = [{"id": 1, "nombre": "Ana", "tags": ["python", "data"], "perfil": {"edad": 25, "ciudad": "México"}}, ...]`. Escribe:
1. `guardar_json(datos, archivo)` — escribe los datos en un archivo JSON con `json.dump()` y indentación 2.
2. `cargar_json(archivo)` — lee y retorna los datos con `json.load()`.
3. `filtrar_por_tag(datos, tag)` — retorna los elementos que tienen el tag en su lista de tags.
4. `actualizar_perfil(datos, id, nuevo_perfil)` — actualiza el perfil del elemento con ese id y retorna el resultado.
5. Escribe una función `resumen_json(archivo)` que carga el archivo y retorna un resumen: cantidad de elementos, tags únicos, ciudades únicas.

**Entrada:**
```python
datos = [
    {"id": 1, "nombre": "Ana", "tags": ["python", "data"], "perfil": {"edad": 25, "ciudad": "México"}},
    {"id": 2, "nombre": "Luis", "tags": ["java", "backend"], "perfil": {"edad": 30, "ciudad": "Guadalajara"}},
    {"id": 3, "nombre": "María", "tags": ["python", "frontend"], "perfil": {"edad": 28, "ciudad": "México"}},
]
guardar_json(datos, "/tmp/datos.json")
cargados = cargar_json("/tmp/datos.json")
print(filtar_por_tag(cargados, "python"))  # Ana y María
print(actualizar_perfil(cargados, 1, {"edad": 26, "ciudad": "CDMX"}))
print(resumen_json("/tmp/datos.json"))  # cantidad: 3, tags: {'python', 'data', 'java', 'backend', 'frontend'}, ciudades: {'México', 'Guadalajara', 'CDMX'}
```

---

### Ejercicio 583: Función con parámetros por defecto y validaciones
**Enunciado:** Escribeuna función `crear_usuario(nombre, edad, email, rol="usuario", activo=True, permisos=None)` que:
1. `permisos` por defecto es `None`, y si es `None`, se establece como `["leer"]`.
2. Valida que `nombre` sea str no vacío.
3. Valida que `edad` sea int entre 0 y 120.
4. Valida que `email` contenga "@".
5. Valida que `rol` sea uno de `["usuario", "admin", "moderador"]`.
6. Si alguna validación falla, lanza `UsuarioInvalidoException` con el campo y motivo.
7. Retorna un diccionario con los datos del usuario.

Escribe también `procesar_usuarios(listacontables)` que recibe una lista de tuplas `(nombre, edad, email, rol_opcional)` y retorna una lista de resultados (usuarios creados o errores).

**Entrada:**
```python
pruebas = [
    ("Ana", 25, "ana@email.com"),
    ("", 25, "sin_nombre@email.com"),  # error
    ("Luis", -5, "luis@email.com"),     # error
    ("María", 30, "maría.email.com"),   # error (sin @)
    ("Carlos", 45, "carlos@email.com", "admin"),
]
```
**Salida:**
```python
{"nombre": "Ana", "edad": 25, "email": "ana@email.com", "rol": "usuario", "activo": True, "permisos": ["leer"]}
UsuarioInvalidoException: nombre="" no es válido (no vacío)
UsuarioInvalidoException: edad=-5 no es válida (entre 0 y 120)
UsuarioInvalidoException: email="maría.email.com" no contiene "@"
{"nombre": "Carlos", "edad": 45, "email": "carlos@email.com", "rol": "admin", "activo": True, "permisos": ["leer"]}
```

---

### Ejercicio 584: Append y lectura de archivo de log
**Enunciado:** Escribeuna clase `GestorLogs` que:
1. `__init__(self, archivo_log)` — guarda la ruta del archivo.
2. `escribir(self, nivel, mensaje)` — escribe una línea con formato `[TIMESTAMP] [NIVEL] mensaje` usando `datetime.datetime.now().strftime("%Y-%m-%d %H:%M:%S")`. Usa `open(archivo, "a")` para append.
3. `leer_ultimas(self, n=10)` — lee las últimas `n` líneas del archivo y las retorna como lista.
4. `filtrar_por_nivel(self, nivel)` — lee todo el archivo y retorna solo las líneas del nivel especificado.
5. `contar_por_nivel(self)` — retorna un diccionario `{nivel: cantidad}` contando todas las líneas del archivo.
6. `limpiar(self)` — vacía el archivo (open con "w" y escritura de string vacío).

**Entrada:**
```python
logs = GestorLogs("/tmp/test.log")
logs.limpiar()
logs.escribir("INFO", "Aplicación iniciada")
logs.escribir("ERROR", "Error de conexión")
logs.escribir("INFO", "Reconexión exitosa")
logs.escribir("WARNING", "Memoria alta")
logs.escribir("ERROR", "Error de base de datos")
print(logs.leer_ultimas(3))  # últimas 3 líneas
print(logs.filtrar_por_nivel("ERROR"))  # 2 líneas de ERROR
print(logs.contar_por_nivel())  # {"INFO": 2, "ERROR": 2, "WARNING": 1}
```

---

### Ejercicio 585: Función con *args para calcular estadísticas
**Enunciado:** Escribeuna función `calcular_estadisticas(*args, tipo="basic")` que:
1. Si `tipo="basic"`, retorna `(media, mediana, moda, minimo, maximo, rango)` para los números pasados como args.
2. Si `tipo="extended"`, además retorna la desviación estándar y la varianza.
3. Si `tipo="full"`, además retorna los cuartiles (Q1, Q2, Q3).
4. Si no se pasan números, lanza `SinDatosException("No se proporcionaron números")`.
5. Implementa tu propia lógica (sin usar `statistics` module) para media, mediana, moda, etc.

**Entrada:**
```python
print(calcular_estadisticas(1, 2, 3, 4, 5, tipo="basic"))
# (3.0, 3, [1,2,3,4,5] o el que sea más frecuente, 1, 5, 4)
print(calcular_estadisticas(1, 2, 3, 4, 5, 5, 5, tipo="full"))
# más estadísticas con cuartiles
```

---

### Ejercicio 586: Lectura y transformación de archivo JSON
**Enunciado:** Dado un archivo JSON que contiene una lista de objetos con estructura compleja anidada (simula una respuesta de API):
```json
[
    {"id": 1, "usuario": {"nombre": "Ana", "email": "ana@email.com"}, "pedidos": [{"producto": "Laptop", "cantidad": 1, "precio": 10000}, {"producto": "Mouse", "cantidad": 2, "precio": 50}]},
    {"id": 2, "usuario": {"nombre": "Luis", "email": "luis@email.com"}, "pedidos": [{"producto": "Teclado", "cantidad": 1, "precio": 120}]},
    {"id": 3, "usuario": {"nombre": "María", "email": "maría@email.com"}, "pedidos": []}
]
```
Escribeuna función `transformar_datos_json(archivo)` que:
1. Carga el archivo JSON.
2. Transforma cada objeto a una tupla `(id, nombre, email, total_pedidos, total_gastado)`.
3. Retorna una lista de esas tuplas.
4. Además, retorna un diccionario `{nombre: total_gastado}` para los usuarios con pedidos.
5. Escribe una función `exportar_csv_transformado(archivo_json, archivo_csv)` que escribe los datos transformados en un CSV con encabezados.

**Entrada:** (el archivo `/tmp/api_response.json` con el JSON de arriba)
**Salida (transformar_datos_json):**
```python
[
    (1, "Ana", "ana@email.com", 2, 10100),
    (2, "Luis", "luis@email.com", 1, 120),
    (3, "María", "maría@email.com", 0, 0),
]
{"Ana": 10100, "Luis": 120}
```

---

### Ejercicio 587: Función recursiva para procesar una lista de archivos
**Enunciado:** Escribeuna función recursiva `procesar_directorio(ruta, extension=".txt")` que:
1. Recorre el directorio indicado.
2. Si es un archivo con la extensión deseada, lo procesa (lee y cuenta líneas, palabras, caracteres) y agrega al resultado.
3. Si es un subdirectorio, recursa dentro.
4. Retorne un diccionario `{ruta_completa: {"lineas": N, "palabras": N, "caracteres": N}}` para cada archivo procesado.
5. Si la ruta no existe, lanza `RutaInvalidaException(ruta)`.

**Entrada:** (crea una estructura de directorios y archivos de prueba en `/tmp/test_dir/`)
**Salida:** según los archivos encontrados.

---

### Ejercicio 588: Ámbito de variables — global vs local en función recursiva
**Enunciado:** Escribeuna función `fibonacci_con_global(n)` que usauna variable global `llamadas_fib` para contar cuántas veces se llamó a la función recursiva. La función debe:
1. Declarar `global llamadas_fib` y incrementarla cada vez que se entra.
2. Calcular Fibonacci recursivamente.
3. Retornar el Fibonacci y dejar actualizado el contador global.
Creauna segunda versión `fibonacci_sin_global(n, contador_list)` que usauna lista mutable pasada como parámetro para contar (sin global), donde `contador_list[0]` es el contador.

Compara ambas para `n=10`.

**Entrada:**
```python
global llamadas_fib
llamadas_fib = 0
result = fibonacci_con_global(10)
print(result, llamadas_fib)  # 55, número de llamadas

contador = [0]
result2 = fibonacci_sin_global(10, contador)
print(result2, contador[0])  # 55, mismo número de llamadas
```

---

### Ejercicio 589: Función con **kwargs para configurar una conexión
**Enunciado:** Escribeuna función `crear_conexion(**kwargs)` que:
1. Acepta parámetros opcionales: `host` (default "localhost"), `port` (default 5432), `usuario` (default "postgres"), `password` (default ""), `base_datos` (default "mydb"), `ssl` (default False).
2. Valida que `port` sea int entre 1 y 65535.
3. Valida que `ssl` sea bool (si se proporciona).
4. Si hay parámetros desconocidos (no están en la lista de parámetros esperados), imímelos pero no lance error.
5. Retorne un diccionario con la configuración de conexión.
6. Escribeuna función `test_conexion(config)` que simula probar la conexión (si `config["host"] == "localhost"` retorna `True`, si es "invalido" lanza `ConexionFallidaException`).

**Entrada:**
```python
config1 = crear_conexion(host="localhost", port=5432, usuario="admin", ssl=True)
print(config1)  # {"host": "localhost", "port": 5432, "usuario": "admin", "password": "", "base_datos": "mydb", "ssl": True}
print(test_conexion(config1))  # True

config2 = crear_conexion(host="invalido")
print(test_conexion(config2))  # ConexionFallidaException
```

---

### Ejercicio 590: Lectura de archivo con manejo de codificación
**Enunciado:** Crea un archivo de texto con contenido Unicode (acentos, caracteres especiales, emojis) y escribeuna función `leer_archivo_unicode(archivo, encoding="utf-8")` que:
1. Intenta leer con la codificación dada.
2. Si hay `UnicodeDecodeError`, intenta con "latin-1" como fallback.
3. Si ambas fallan, lanza `CodificacionInvalidaException(archivo, encoding_listo)`.
4. Retorna el contenido leído.
5. Escribeuna función `contar_caracteres_especiales(texto)` que cuente cuántos caracteres no ASCII hay en el texto (código > 127) y retorne el conteo y una lista de los caracteres únicos no ASCII.

**Entrada:**
```python
texto = leer_archivo_unicode("/tmp/test_unicode.txt")
print(texto)  # "Hola mundo! 🌍 ¡Esto es una prueba con acentos: áéíóúñ!"
print(contar_caracteres_especiales(texto))  # (conteo, lista de caracteres únicos)
```

---

### Ejercicio 591: Función anidada con closure para contar palabras
**Enunciado:** Escribeuna función `crear_analizador_texto(stopwords)` que:
1. Recibe una lista de stopwords.
2. Define una función anidada `analizar(texto)` que:
   - Normaliza el texto (minúsculas, elimina puntuación).
   - Particiona en palabras.
   - Filtra stopwords.
   - Retorna un diccionario `{palabra: frecuencia}`.
3. Define una función anidada `obtener_stopwords()` que retorna la lista de stopwords.
4. Define una función anidada `actualizar_stopwords(nuevas_stopwords)` que reemplaza la lista.
5. Retorna un diccionario con las funciones `{analizar, obtener_stopwords, actualizar_stopwords}`.

**Entrada:**
```python
analizador = crear_analizador_texto(["el", "la", "los", "las", "de", "en", "un", "una"])
resultado = analizador["analizar"]("El gato duerme en el sofá. La luna brilla.")
print(resultado)  # {"gato": 1, "duerme": 1, "sofá": 1, "luna": 1, "brilla": 1}
print(analizador["obtener_stopwords"]())  # ["el", "la", ...]
analizador["actualizar_stopwords"](["el", "la", "de"])
resultado2 = analizador["analizar"]("El gato duerme de noche")
print(resultado2)  # {"gato": 1, "duerme": 1, "noche": 1}
```

---

### Ejercicio 592: Archivo de acceso concurrente simulado
**Enunciado:** Escribeuna clase `GestorArchivoConcurrente` que simula acceso concurrente a un archivo con un lock simple (usa `threading.Lock` o una bandera manual). La clase debe:
1. `__init__(self, archivo)` — guarda la ruta.
2. `leer_seguro(self)` — adquiere el lock, lee, libera.
3. `escribir_seguro(self, contenido)` — adquiere el lock, escribe, libera.
4. `modificar_seguro(self, transformador_func)` — adquiere el lock, lee, aplica la función transformadora, escribe, libera.
5. El lock se implementa con `threading.Lock` si está disponible, o con una variable de instancia `_lock_adquirido` y `while` loops (spinlock simple).
6. Escribe pruebas que demuestren el uso seguro.

**Entrada:**
```python
gestor = GestorArchivoConcurrente("/tmp/concurrente.txt")
gestor.escribir_seguro("Datos iniciales\n")
gestor.modificar_seguro(lambda lines: [line.upper() for line in lines])
print(gestor.leer_seguro())  # "DATOS INICIALES\n"
```

---

### Ejercicio 593: Función con *args y **kwargs para construir una consulta SQL
**Enunciado:** Escribeuna función `construir_consulta(tabla, *columnas, where=None, order_by=None, limit=None, **otros)` que:
1. Construye una cadena de consulta SQL SELECT básica.
2. Si no se pasan columnas, usa `*`.
3. Si `where` es un diccionario, construye la cláusula WHERE (ej. `{"edad": 25, "ciudad": "México"}` → `WHERE edad = 25 AND ciudad = 'México'`).
4. Si `order_by` es una cadena, agrega `ORDER BY columna`.
5. Si `limit` es un int, agrega `LIMIT n`.
6. Si `otros` tiene claves como `"groupby"`, `"having"`, úsalas (agrega GROUP BY, HAVING si están).
7. Retorne la consulta como cadena.
8. Valida que `tabla` no sea vacío y no contenga caracteres peligrosos (`;` → lanza `ConsultaInvalidaException`).

**Entrada:**
```python
print(construir_consulta("usuarios", "nombre", "edad", where={"ciudad": "México", "activo": True}, order_by="edad", limit=10))
# SELECT nombre, edad FROM usuarios WHERE ciudad = 'México' AND activo = True ORDER BY edad LIMIT 10

print(construir_consulta("productos", where={"precio": 100}, groupby="categoría", having="COUNT(*) > 5"))
# SELECT * FROM productos WHERE precio = 100 GROUP BY categoría HAVING COUNT(*) > 5
```

---

### Ejercicio 594: Archivo de backup con checksum
**Enunciado:** Escribeuna función `crear_backup(archivo_original, archivo_backup)` que:
1. Lee el contenido del archivo original.
2. Calcula un checksum simple (suma de los valores ASCII de todos los caracteres módulo 1000000).
3. Escribe en el archivo de backup: primero el checksum (como string de 6 dígitos con ceros a la izquierda), luego un salto de línea, luego el contenido original.
4. Escribeuna función `verificar_backup(archivo_backup)` que:
   - Lee el archivo de backup.
   - Extrae el checksum y el contenido.
   - Recalcula el checksum del contenido y lo compara.
   - Retorna `True` si coinciden, `False` si no.
5. Escribeuna función `restaurar_backup(archivo_backup, archivo_original)` que extrae el contenido del backup y lo escribe en el archivo original.

**Entrada:**
```python
# Crea archivo de prueba
with open("/tmp/orig.txt", "w") as f: f.write("Hola mundo!")
crear_backup("/tmp/orig.txt", "/tmp/backup.txt")
print(verificar_backup("/tmp/backup.txt"))  # True
restaurar_backup("/tmp/backup.txt", "/tmp/restaurado.txt")
print(open("/tmp/restaurado.txt").read())  # "Hola mundo!"
```

---

### Ejercicio 595: Función con parámetros por defecto mutables (y cómo evitar el pitfall)
**Enunciado:** Escribeuna función `agregar_elemento(elemento, lista=None)` que:
1. Si `lista` es `None`, crea una nueva lista vacía.
2. Agrega el elemento a la lista.
3. Retorna la lista.
Demuestra el problema si se usa `lista=[]` como default (el mismo objeto se comparte entre llamadas).
Luego, escribeuna función `procesar_pedidos(pedidos, almacen=None)` que:
1. `almacen` es un diccionario que agrupa productos por categoría.
2. Si `almacen` es `None`, crea uno nuevo.
3. Cada pedido esuna tupla `(producto, cantidad, categoria)`.
4. Agrega a `almacen[categoria]` una lista de `(producto, cantidad)`.
5. Retorna el diccionario completo.

**Entrada:**
```python
# Demostración del pitfall
print(agregar_elemento(1))  # [1]
print(agregar_elemento(2))  # [2] (no [1, 2] porque usamos None como default)
# Con default mutable (para demostrar el problema)
def agregar_elemento_mal(elemento, lista=[]):
    lista.append(elemento)
    return lista
print(agregar_elemento_mal(1))  # [1]
print(agregar_elemento_mal(2))  # [1, 2] — ¡el mismo objeto!

# Procesar pedidos
pedidos = [("Laptop", 10, "Electrónica"), ("Mouse", 50, "Electrónica"), ("Cuaderno", 100, "Papelería")]
almacen = procesar_pedidos(pedidos)
print(almacen)  # {"Electrónica": [("Laptop", 10), ("Mouse", 50)], "Papelería": [("Cuaderno", 100)]}
```

---

### Ejercicio 596: Lectura de archivo con filtrado y agrupamiento
**Enunciado:** Dado un archivo de texto con datos de estudiantes (formato libre: cada línea contiene `nombre, calificación, grupo`), escribeuna función `procesar_archivo_estudiantes(archivo)` que:
1. Lee el archivo línea por línea.
2. Parsea cada línea como `nombre, calificación, grupo` (con split por coma).
3. Filtra estudiantes con calificación >= 70.
4. Agrupa por grupo.
5. Retorna un diccionario `{grupo: {"aprobados": [nombres], "reprobados": [nombres], "promedio": calificacion_promedio}}`.
6. Escribe los resultados en un archivo de salida `reporte_estudiantes.txt` con formato formateado.

**Entrada:** (el archivo `/tmp/estudiantes.txt` con contenido como:
```
Ana, 95, A
Luis, 67, B
María, 82, A
Carlos, 55, A
Pedro, 78, B
Sofía, 91, A
```
**Salida:**
```python
{
    "A": {"aprobados": ["Ana", "María", "Sofía"], "reprobados": ["Carlos"], "promedio": 80.75},
    "B": {"aprobados": ["Pedro"], "reprobados": ["Luis"], "promedio": 72.5},
}
```
Y el archivo de reporte con el contenido formateado.

---

### Ejercicio 597: Función con lambda y map/filter para transformar datos de archivo
**Enunciado:** Lee un archivo CSV de empleados (similar al ejercicio 576) y usa `map()`, `filter()`, y `lambda` para:
1. Filtrar empleados con salario > 50000 usando `filter()` con lambda.
2. Mapear cada empleado a una tupla `(nombre.upper(), salario * 1.15)` usando `map()` con lambda (aumento del 15%).
3. Ordenar por salario descendente usando `sorted()` con `key=lambda`.
4. Retornar la lista resultante y escribirla en un archivo de salida con formato.

**Entrada:** (el archivo `/tmp/empleados.csv` del ejercicio 576)
**Salida:**
```python
# Empleados con salario > 50000, con aumento del 15%, ordenados por salario descendente
[
    ("CARLOS", 80500.0),
    ("PEDRO", 71300.0),
    ("LUIS", 69000.0),
    ("MARÍA", 63250.0),
]
```
*(Los valores exactos dependen del cálculo con el 15% de aumento)*

---

### Ejercicio 598: Ámbito de variables — función factory con closures
**Enunciado:** Escribeuna función `crear_calculadora(operacion)` que retorne una función que realiza la operación especificada. Las operaciones válidas son `"sumar"`, `"restar"`, `"multiplicar"`, `"dividir"`. La función retornada toma dos argumentos y retorna el resultado. Si la operación no es válida, lanza `OperacionNoSoportadaException`. Demuestra el uso de closures: cada función retornada "recuerda" su operación.

Luego, escribeuna función `aplicar_operaciones(operaciones, valores)` que tomauna lista de funciones (creadas por `crear_calculadora`) y una lista de tuplas `(a, b)`, y aplica cada función a cada tupla, retornandouna matriz de resultados.

**Entrada:**
```python
sumar = crear_calculadora("sumar")
restar = crear_calculadora("restar")
multiplicar = crear_calculadora("multiplicar")
dividir = crear_calculadora("dividir")
print(sumar(5, 3))      # 8
print(restar(5, 3))     # 2
print(multiplicar(5, 3))  # 15
print(dividir(6, 3))    # 2.0

# Aplicar operaciones a múltiples pares
operaciones = [sumar, restar, multiplicar, dividir]
valores = [(10, 5), (20, 4), (8, 2)]
matriz = aplicar_operaciones(operaciones, valores)
print(matriz)
# [[15, 25, 10], [5, 16, 6], [50, 80, 16], [2.0, 5.0, 4.0]]
# (filas: operaciones; columnas: pares de valores)
```

---

### Ejercicio 599: Archivo como base de datos simple — CRUD
**Enunciado:** Implementa un CRUD simple usando un archivo JSON como almacenamiento:
1. `crear(archivo_db, id, datos)` — carga el JSON, agrega el nuevo registro, guarda.
2. `leer(archivo_db, id)` — carga y busca el registro por id, retorna o lanza `RegistroNoEncontradoException`.
3. `actualizar(archivo_db, id, nuevos_datos)` — carga, busca, actualiza, guarda; si no encuentra, lanza.
4. `eliminar(archivo_db, id)` — carga, busca, elimina, guarda; si no encuentra, lanza.
5. `listar(archivo_db)` — carga y retorna todos los registros.
6. `buscar(archivo_db, criterio)` — busca por un campo específico (ej. `{"nombre": "Ana"}`) y retorna lista de coincidencias.
El archivo JSON tiene estructura `{"next_id": N, "registros": {id: datos}}`.

**Entrada:**
```python
archivo = "/tmp/db.json"
crear(archivo, 1, {"nombre": "Ana", "edad": 25})
crear(archivo, 2, {"nombre": "Luis", "edad": 30})
print(leer(archivo, 1))  # {"nombre": "Ana", "edad": 25}
print(listar(archivo))  # {"1": {...}, "2": {...}}
actualizar(archivo, 1, {"nombre": "Ana López", "edad": 26})
print(leer(archivo, 1))  # {"nombre": "Ana López", "edad": 26}
buscar(archivo, {"nombre": "Ana López"})  # [1]
eliminar(archivo, 2)
print(listar(archivo))  # solo Ana
```

---

### Ejercicio 600: Función con *args para mezclar y remezclar datos
**Enunciado:** Escribeuna función `mezclar_datos(*iterables, modo="intercalado")` que:
1. Si `modo="intercalado"`, toma elementos de cada iterable uno por uno (como `zip`), hasta que el más corto se agote.
2. Si `modo="concat"`, concatena todos los iterables en orden.
3. Si `modo="alternado"`, toma un elemento del primero, luego del segundo, etc., y cuando uno se agota, continúa con los restantes.
4. Retorna una lista con el resultado.
5. Si no se pasan iterables, lanza `SinDatosException`.
6. Valida que todos los args sean iterables (si no, lanza `IterablesInvalidosException`).

**Entrada:**
```python
print(mezclar_datos([1, 2, 3], ["a", "b", "c"], ["x", "y", "z"], modo="intercalado"))
# [1, "a", "x", 2, "b", "y", 3, "c", "z"]

print(mezclar_datos([1, 2], ["a", "b", "c"], modo="alternado"))
# [1, "a", 2, "b", "c"]  # el tercer iterable se agota, luego continúa con el segundo

print(mezclar_datos([1, 2, 3], ["a", "b", "c"], modo="concat"))
# [1, 2, 3, "a", "b", "c"]
```

---

## BLOQUE 5 · STRINGS AVANZADOS + FUNCIONES DE ORDEN SUPERIOR (601–625)

### Ejercicio 601: Validación y extracción de emails de texto
**Enunciado:** Dado un texto largo que contiene múltiples direcciones de email mezcladas con otros texto, escritoa función `extraer_emails(texto)` que:
1. Recorra el texto carácter por carácter (sin regex) y extraiga direcciones de email válidas.
2. Un email válido tiene: parte local (letras, números, puntos, guiones, guiones bajos), seguido de `@`, seguido de dominio (letras, números, puntos), seguido de un TLD de al menos 2 letras.
3. Retorne una lista de emails únicos (case-insensitive para deduplicación, pero conservando el caso original de la primera aparición).
4. Ordene por dominio y luego por parte local.

**Entrada:**
```python
texto = """
Contacto: ana@email.com, Luis.perez@empresa.org
Soporte: support@empresa.co.uk, ANA@EMAIL.COM (duplicado)
Invitados: maría+faq@consultora.net, info@blog.gov
Email inválido: @sin_usuario.com, usuario@, usuario@.com
"""
```
**Salida:**
```python
["ana@email.com", "ANA@EMAIL.COM",  # caso original diferente pero dominio igual
 "luis.perez@empresa.org",
 "support@empresa.co.uk",
 "maría+faq@consultora.net",
 "info@blog.gov",
]
```
*(Nota: el email "ANA@EMAIL.COM" es considerado duplicado case-insensitive de "ana@email.com", así que solo se conserva uno — el primero encontrado)*

---

### Ejercicio 602: Análisis de texto con map/filter/reduce — frecuencia de palabras
**Enunciado:** Dado un texto, usaa `map()`, `filter()`, `reduce()` y `lambda` para:
1. Normalice el texto: minúsculas, elimine signos de puntuación (solo conserva letras y espacios).
2. Parta en palabras con `split()`.
3. Filtre palabras vacías (longitud 0) y stopwords proporcionadas.
4. Use `map()` para crear tuplas `(palabra, 1)` para cada palabra.
5. Use `reduce()` para agrupar por palabra y contar frecuencias (acumulando en un diccionario).
6. Retorne el diccionario de frecuencias y una lista ordenada de `(palabra, frecuencia)` por frecuencia descendente.

**Entrada:**
```python
texto = "La programación es divertida. La programación requiere práctica. La práctica hace al maestro."
stopwords = ["la", "es", "al", "de", "el", "la", "un", "una"]
```
**Salida:**
```python
# diccionario
{"programacion": 2, "divertida": 1, "requiere": 1, "practica": 2, "hace": 1, "maestro": 1}
# lista ordenada
[("programacion", 2), ("practica", 2), ("divertida", 1), ("requiere", 1), ("hace", 1), ("maestro", 1)]
```

---

### Ejercicio 603: Cifrado de texto con función de orden superior
**Enunciado:** Escribeuna función `cifrar_texto_per_primo(texto)` que:
1. Para cada carácter del texto, calcula el código ASCII.
2. Si el código es primo, shifta el carácter +1 en el código ASCII.
3. Si el código no es primo, shifta -1.
4. Usa `map()` con una `lambda` que encapsula esta lógica.
5. Retorne el texto cifrado y también el texto descifrado (aplicando la operación inversa).
6. Escribeuna función auxiliar `es_primo(n)` que retorne `True` si n es primo.
7. Valida que `descifrar(cifrar(x)) == x` para un texto de prueba.

**Entrada:** `cifrar_texto_per_primo("Hola")`
**Salida:** (depende de los códigos ASCII: H=72 no primo → G; o=111 no primo → n; l=108 no primo → k; a=97 primo → b) → "Gnkb"
**Descifrar:** "Gnkb" → "Hola"

---

### Ejercicio 604: Comparación de strings con función de orden superior
**Enunciado:** Dadauna lista de strings, escritoa función `analizar_strings(lista, criterio)` donde `criterio` es una función que toma un string y retorna un valor. La función `analizar_strings` debe:
1. Usar `map()` para aplicar el criterio a cada string.
2. Usar `filter()` para filtrar strings que cumplan una condición (ej. longitud > 5).
3. Usar `sorted()` con `key=criterio` para ordenar.
4. Retornar un diccionario con: `{"original": lista, "criterios": list(map(criterio, lista)), "filtrados": list(filter(lambda s: len(s) > 5, lista)), "ordenados": sorted(lista, key=criterio)}`.

**Entrada:**
```python
strings = ["ana", "luis", "maría", "carlos", "pedro", "sofía"]
def criterio_largo(s):
    return len(s)
resultado = analizar_strings(strings, criterio_largo)
print(resultado["criterios"])  # [3, 4, 5, 6, 5, 5]
print(resultado["filtrados"])  # ["maría", "carlos", "sofía"] (largo > 5... wait, "carlos" es 6, "maría" es 5... revisar)
# filtrados por len > 5: ["carlos"] (6), "maría" es 5, "sofía" es 5... solo "carlos"
print(resultado["ordenados"])  # ["ana", "luis", "pedro", "maría", "sofía", "carlos"] (orden por largo creciente)
```

---

### Ejercicio 605: Manipulación avanzada de strings — partision y unión
**Enunciado:** Dadauna cadena con datos separados por varios delimitadores posibles (coma, punto y coma, espacio), escritoa función `parsear_multidelimiters(cadena)` que:
1. Identify qué delimitador se usa (el que aparece más veces).
2. Parta la cadena usando ese delimitador.
3. Filtre elementos vacíos.
4. Retorne una tupla `(delimitador_identificado, elementos)`.
5. Escribeuna función `unificar_datos(elementos, delimitador_nuevo)` que une los elementos con el nuevo delimitador.
6. Escribeuna función `transformar_y_unir(cadena, delimitador_viejo, delimitador_nuevo, transformacion_func)` que parsea, transforma cada elemento con la función dada, y une con el nuevo delimitador.

**Entrada:**
```python
cadena1 = "Ana,Luis,María,Carlos"
cadena2 = "Ana;Luis;María;Carlos"
cadena3 = "Ana Luis María Carlos"
print(parsear_multidelimiters(cadena1))  # (",", ["Ana", "Luis", "María", "Carlos"])
print(parsear_multidelimiters(cadena2))  # (";", ["Ana", "Luis", "María", "Carlos"])
print(parsear_multidelimiters(cadena3))  # (" ", ["Ana", "Luis", "María", "Carlos"])

print(unificar_datos(["Ana", "Luis", "María"], "-"))  # "Ana-Luis-María"
print(transformar_y_unir("Ana,Luis,María", ",", ";", lambda s: s.upper()))  # "ANA;LUIS;MARÍA"
```

---

### Ejercicio 606: Búsqueda de patrones en strings con find/rfind
**Enunciado:** Dadauna cadena larga y un patrón, escritoa función `buscar_patron_avanzado(cadena, patron, caso_sensible=True)` que:
1. Usa `find()` para encontrar la primera aparición del patrón.
2. Usa `rfind()` para encontrar la última.
3. Usa un loop con `find()` desde la posición siguiente para encontrar todas las apariciones.
4. Retorne una lista de posiciones (indices de inicio) de todas las apariciones.
5. Si `caso_sensitive=False`, convierte ambos a minúsculas antes de buscar.
6. Retorne también la cantidad de appariciones y el porcentaje de la cadena que ocupa el patrón (longitud_total_del_patron_encontrado / longitud_de_la_cadena * 100).

**Entrada:**
```python
cadena = "Ana compró un coche. El coche de Ana es rojo. Otro coche más."
print(buscar_patron_avanzado(cadena, "coche"))
# posiciones: [14, 24, 47], cantidad: 3, porcentaje: (5*3)/len(cadena)*100
```

---

### Ejercicio 607: Validación de formato de tarjetas de crédito
**Enunciado:** Escribeuna función `validar_tarjeta(tarjeta)` que:
1. Elimina espacios y guiones de la entrada.
2. Verifica que solo contenga dígitos.
3. Verifica que tenga entre 13 y 16 dígitos.
4. Aplica el algoritmo de Luhn para validar el número.
5. Retorna `True` si es válida, `False` si no.
6. Escribeuna función `formatear_tarjeta(tarjeta)` que formatea el número en grupos de 4 dígitos separados por espacios (ej. `"4111 1111 1111 1111"`).
7. Escribeuna función `extractor_tarjetas(texto)` que busca y extrae números de tarjeta de un texto largo (patrones de 13-16 dígitos consecutivos o con espacios/guiones).

**Entrada:**
```python
print(validar_tarjeta("4111111111111111"))  # True (válida según Luhn)
print(validar_tarjeta("1234567890123456"))  # False (no pasa Luhn)
print(formatear_tarjeta("4111111111111111"))  # "4111 1111 1111 1111"
texto = "Pagar con 4111-1111-1111-1111 o 5500 0000 0000 0004"
print(extractor_tarjetas(texto))  # ["4111111111111111", "5500000000000004"]
```

---

### Ejercicio 608: Reducción de strings con reduce — construcción de histograma
**Enunciado:** Dado un texto, usaa `reduce()` para construir un histograma de caracteres (diccionario `{caracter: frecuencia}`) sin usar un loop explícito. Escribeuna función `histograma_reduce(texto)` que:
1. Convierte el texto a minúsculas.
2. Usa `reduce()` con una lambda que acumula un diccionario: para cada carácter, incrementa su contador.
3. Retorne el diccionario de histograma.
4. Escribeuna función `frecuencia_palabras_reduce(texto)` que hace lo mismo pero a nivel de palabras (usa `split()` y `reduce()`).
5. Escribeuna función `palabras_mas_frecuentes(histograma, n=5)` que retorna las `n` palabras más frecuentes usando `sorted()` con `key=lambda x: x[1], reverse=True`.

**Entrada:**
```python
texto = "aaaa bbb cc ddd e"
hist_caracteres = histograma_reduce(texto)
print(hist_caracteres)  # {"a": 4, " ": 4, "b": 3, "c": 2, "d": 3, "e": 1}

hist_palabras = frecuencia_palabras_reduce(texto)
print(hist_palabras)  # {"aaaa": 1, "bbb": 1, "cc": 1, "ddd": 1, "e": 1}

print(palabras_mas_frecuentes(hist_palabras, 3))  # [("aaaa", 1), ("bbb", 1), ("cc", 1)] (todas empate)
```

---

### Ejercicio 609: Validación y transformación de fechas en strings
**Enunciado:** Escribeuna función `parsear_fecha(fecha_str)` que:
1. Detecta el formato de la fecha (puede ser "DD/MM/AAAA", "MM-DD-AAAA", "AAAA-MM-DD", "DD de Mes de AAAA", etc.).
2. Valida que los componentes sean numéricos donde corresponda y que el mes esté entre 1 y 12, el día válido para el mes (considerando años bisiestos para febrero).
3. Retorna un diccionario `{"dia": D, "mes": M, "ano": A, "formato_detectado": "...", "valida": True/False}`.
4. Escribeuna función `convertir_formato_fecha(fecha_str, formato_destino)` que convierte de un formato a otro (los formatos soportados son los mismos).
5. Escribeuna función `ordenar_fechas(fechas)` que tomauna lista de strings de fechas y las ordena cronológicamente (de menor a mayor), detectando el formato de cada una.

**Entrada:**
```python
print(parsear_fecha("15/03/2024"))  # {"dia": 15, "mes": 3, "ano": 2024, "formato_detectado": "DD/MM/AAAA", "valida": True}
print(parsear_fecha("2024-02-29"))  # {"dia": 29, "mes": 2, "ano": 2024, "valida": True} (2024 es bisiesto)
print(parsear_fecha("2023-02-29"))  # {"dia": 29, "mes": 2, "ano": 2023, "valida": False} (2023 no es bisiesto)
print(convertir_formato_fecha("15/03/2024", "AAAA-MM-DD"))  # "2024-03-15"
print(ordenar_fechas(["2024-01-15", "15/01/2024", "01-15-2024"]))  # todas equivalen al mismo día, orden arbitrario
```

---

### Ejercicio 610: Función de orden superior para transformar palabras
**Enunciado:** Escribeuna función `transformar_palabras(lista_palabras, *funciones)` que:
1. Aplica todas las funciones `*funciones` a cada palabra, en orden secuencial (la salida de una es la entrada de la siguiente).
2. Usa `reduce()` desde `functools` para aplicar las funciones acumulativamente.
3. Retorna una lista de los resultados transformados.
4. Si no se pasan funciones, retorna la lista original.
5. Escribe funciones auxiliares: `a_mayusculas(s)`, `invertir(s)`, `sin_vocales(s)`, ` palindromo(s)` (retorna True/False).

**Entrada:**
```python
palabras = ["hola", "mundo", "python"]
print(transformar_palabras(palabras, a_mayusculas, invertir))  # ["ALOH", "ODNUM", "NOHTYP"]
print(transformar_palabras(palabras, sin_vocales, a_mayusculas))  # ["HL", "MND", "PYTHN"]
# Prueba de palindrome
print(palindromo("radar"))  # True
print(palindromo("python"))  # False
```

---

### Ejercicio 611: Strings como objetos inmutables — operaciones avanzadas
**Enunciado:** Escribeuna función `procesar_string_inmutable(s)` que:
1. Demuestra que las strings son inmutables: intenta modificar un carácter por índice y atrapa el error, mostrando el mensaje.
2. Convierte la string a lista, modifica, y vuelve a string con `join()`.
3. Usa `partition()` para dividir la string en tres partes alrededor de la primera aparición de un separador.
4. Usa `rpartition()` para dividir alrededor de la última aparición.
5. Usa `splitlines()` para dividir en líneas.
6. Usa `expandtabs()` para expandir tabs a espacios.
7. Retorna un diccionario con todos los resultados.

**Entrada:**
```python
resultado = procesar_string_inmutable("Hola\tMundo\nMi amigo,\nque tal?")
print(resultado["lista_modificada"])  # "Hola Mundo\nMi amigo,\nque tal?" (tab reemplazado por espacio)
print(resultado["partition"])  # ("Hola", "\t", "Mundo\nMi amigo,\nque tal?")
print(resultado["rpartition"])  # ("Hola\tMundo\nMi amigo,", "\n", "que tal?")
print(resultado["splitlines"])  # ["Hola\tMundo", "Mi amigo,", "que tal?"]
print(resultado["expandtabs"])  # "Hola    Mundo\nMi amigo,\nque tal?" (tab a 4 espacios)
```

---

### Ejercicio 612: Cifrado de sustitución simple con map
**Enunciado:** Dadaun diccionario de sustitución `sustituciones = {"a": "x", "e": "y", "i": "z", "o": "w", "u": "v"}` (solo vocales), escritoa función `cifrar_sustitucion(texto, diccionario)` que:
1. Usa `map()` con una lambda que, para cada carácter, busca en el diccionario; si está, lo reemplaza; si no, lo conserva.
2. Usa `"".join()` para unir los resultados.
3. Escribeuna función `descifrar_sustitucion(texto, diccionario)` que invierte el diccionario y aplica el mismo proceso.
4. Valida que `descifrar(cifrar(x, d), d) == x` para un texto de prueba.

**Entrada:**
```python
vocales = {"a": "x", "e": "y", "i": "z", "o": "w", "u": "v"}
print(cifrar_sustitucion("hola mundo", vocales))  # "hwlx mwndv"
print(descifrar_sustitucion("hwlx mwndv", vocales))  # "hola mundo"
```

---

### Ejercicio 613: Análisis de texto con reduce — conteo de patrones
**Enunciado:** Dadauna lista de strings, usaa `reduce()` para:
1. Contar cuántos strings contienen cada vocal (a, e, i, o, u) como diccionario `{vocal: cantidad_de_strings_que_la_contienen}`.
2. Encontrar el string más largo y el más corto.
3. Calcular la longitud promedio de los strings.
4. Retornar un diccionario con todos estos resultados.

**Entrada:**
```python
strings = ["ana", "luis", "maría", "carlos", "pedro", "sofía", "juan", "rosa"]
resultado = analisis_reduce(strings)
print(resultado)
# {
#   "vocal_a": 5,  # strings que contienen "a": ana, maría, carlos, pedro (? no), sofía, juan, rosa → ana, maría, carlos, sofía, juan, rosa = 6
#   "vocal_e": 2,  # luis? no, pedro sí, rosa? no → pedro y... más?
#   "vocal_i": 1,  # luis
#   "vocal_o": 2,  # carlos, rosa
#   "vocal_u": 1,  # luis
#   "mas_largo": "carlos" (6 caracteres, empate con "pedro" y "rosa"? carlos=6, pedro=5, rosa=4... "carlos" es el más largo),
#   "mas_corto": "ana" (3),
#   "longitud_promedio": (3+4+5+6+5+5+4+4)/8 = 36/8 = 4.5,
# }
```

---

### Ejercicio 614: Transformación de texto con map/filter/lambda — filtrado de stopwords
**Enunciado:** Dado un texto y una lista de stopwords, usaa `filter()` y `lambda` para:
1. Partir el texto en palabras.
2. Filtrar palabras que están en stopwords (usando `filter()` con lambda que niega la pertenencia).
3. Filtrar palabras que son solo números.
4. Filtrar palabras con longitud < 3.
5. Usar `map()` para capitalizar las palabras restantes (primera letra mayúscula, resto minúsculas).
6. Usar `sorted()` con `key=lambda` para ordenar alfabéticamente.
7. Retornar la lista final y también el texto reconstruido con `join()`.

**Entrada:**
```python
texto = "El rápido desarrollo del software es clave para el éxito del proyecto."
stopwords = ["el", "del", "la", "los", "las", "un", "una", "es", "para", "de", "en"]
resultado = filtro_avanzado(texto, stopwords)
print(resultado["palabras_filtradas"])  # ["Rápido", "Desarrollo", "Software", "Clave", "Éxito", "Proyecto"]
print(resultado["texto_reconstruido"])  # "Rápido Desarrollo Software Clave Éxito Proyecto"
```

---

### Ejercicio 615: Comparación de strings con distancia de Levenshtein recursiva
**Enunciado:** Implementa la distancia de Levenshtein de forma recursiva conmemoización: `levenshtein(s1, s2, i=None, j=None, memo=None)` que calcula el mínimo número de operaciones (inserción, eliminación, sustitución) para transformar `s1` en `s2`. La función recursiva compara los últimos caracteres y recursa. Usa un diccionario memo para evitar cálculos repetidos.

Luego, escribeuna función `buscar_acentos_correctos(lexico, palabra)` que usa `levenshtein` para encontrar la palabra más similar en el lexico (diccionario de palabras válidas) con distancia <= 2.

**Entrada:**
```python
print(levenshtein("casa", "calle"))  # 3 (sustitución c→c, a→a, s→l, inserción l, inserción e → 3 operaciones)
print(levenshtein("hola", "hola"))    # 0
print(levenshtein("python", "typhon"))  # 2 (sustitución p→t, inserción... o similar)

lexico = ["casa", "calle", "casa", "catedral", "casco"]
print(buscar_acentos_correctos(lexico, "csoa"))  # "casa" (distancia 1)
```

---

### Ejercicio 616: Función con *args y **kwargs para formatear tabla
**Enunciado:** Escribeuna función `formatear_tabla(*filas, encabezado=None, alineacion="derecha", ancho_minimo=10)` que:
1. `filas` esuna lista de listas (cada lista esuna fila de datos).
2. Si `encabezado` se proporciona, esuna lista de nombres de columna.
3. Calcula el ancho de cada columna como el máximo entre `ancho_minimo` y la longitud del contenido.
4. Formatea cada celda con `str(celda).rjust(ancho)` si `alineacion="derecha"`, `.ljust(ancho)` si "izquierda", `.center(ancho)` si "centro".
5. Construye la tabla como string con filas separadas por `\n` y columnas separadas por ` | `.
6. Si `encabezado` se proporciona, agrega una línea de encabezado y una línea separadora debajo.
7. Retorna la tabla como string.

**Entrada:**
```python
filas = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
tabla = formatear_tabla(*filas, encabezado=["Col1", "Col2", "Col3"], alineacion="derecha", ancho_minimo=5)
print(tabla)
# """
# |   Col1 |   Col2 |   Col3 |
# |-------|-------|-------|
# |     1 |     2 |     3 |
# |     4 |     5 |     6 |
# |     7 |     8 |     9 |
# """
```

---

### Ejercicio 617: Validación de contraseñas con regex simulado manualmente
**Enunciado:** Sin usar el módulo `re`, escritoa función `validar_contrasena_avanzada(contraseña)` que retorne un diccionario con los resultados de cada validación:
1. `longitud`: `len(contraseña) >= 8`.
2. `mayusculas`: usa un loop para contar mayúsculas (comparar con `isupper()`).
3. `minusculas`: cuenta minúsculas con `islower()`.
4. `digitos`: cuenta dígitos con `isdigit()`.
5. `especiales`: cuenta caracteres que no sean alfanuméricos ni espacios (usar `isalnum()` y negar).
6. `no_espacios`: no contiene espacios.
7. `no_repetidos`: no hay 3 caracteres consecutivos iguales.
8. `retorne {"valida": todas_las_condiciones_cumplidas, "detalles": {cada validación: bool}}`.

**Entrada:**
```python
print(validar_contrasena_avanzada("Abcdef1!"))  # {"valida": False, "detalles": {"longitud": True, "mayusculas": True, "minusculas": True, "digitos": True, "especiales": True, "no_espacios": True, "no_repetidos": True}}
print(validar_contrasena_avanzada("Abcdef1!"))  # falta especial? "!" es especial → True. ¿Por qué no válida? Porque... en este ejemplo sí sería válida. Revisar: longitud 9 >= 8, mayúsculas 1, minúsculas 5, dígitos 1, especiales 1, no espacios True, no repetidos True → valida: True
```

---

### Ejercicio 618: Filtrar y transformar datos de un archivo CSV con funciones de orden superior
**Enunciado:** Dado un archivo CSV con datos de productos `id,nombre,precio,categoria,stock`, escribeuna función `procesar_productos_csv(archivo)` que:
1. Lee el archivo y parsea cada línea.
2. Usa `filter()` para filtrar productos con `stock > 0` (disponibles).
3. Usa `map()` para transformar cada producto a una tupla `(nombre, precio_con_iva, stock)` donde `precio_con_iva = precio * 1.16`.
4. Usa `sorted()` con `key=lambda x: x[1]` para ordenar por precio con IVA descendente.
5. Usa `reduce()` para calcular el valor total del inventario (suma de `precio_con_iva * stock` de los productos disponibles).
6. Retorna una tupla `(productos_ordenados, valor_total_inventario)`.

**Entrada:** (archivo `/tmp/productos.csv` con contenido de ejemplo)
**Salida:**
```python
productos_ordenados = [("Producto A", 1160.0, 10), ("Producto B", 928.0, 5), ...]
valor_total_inventario = suma de (precio_iva * stock) para todos los disponibles
```

---

### Ejercicio 619: Búsqueda de anagramas con tratamiento de strings
**Enunciado:** Escribeuna función `encontrar_anagramas(lista_palabras)` que:
1. Para cada palabra, crea una "firma" ordenando sus caracteres (usando `sorted()` y `"".join()`).
2. Agrupa las palabras por firma usando un diccionario `{firma: [listade_palabras]}`.
3. Retorne una lista de listas, donde cada sublista contiene los anagramas agrupados (solo sublistas con más de 1 palabra).
4. Usa `map()` para crear las firmas y `filter()` para filtrar grupos con al menos 2 palabras.

**Entrada:**
```python
palabras = ["roma", "amor", "mora", "roma", "oro", "roo", "oro", "python", "typhon"]
print(encontrar_anagramas(palabras))
# [["roma", "amor", "mora", "roma"], ["oro", "oro"]]  # "python" y "typhon" no son anagramas (letras diferentes)
```

---

### Ejercicio 620: Manipulación de strings con startswith, endswith, is métodos
**Enunciado:** Dadauna lista de strings que representan nombres de archivo, escritoa función `clasificar_archivos(lista_archivos)` que:
1. Usa `startswith()` para identificar archivos que comienzan con "backup_".
2. Usa `endswith()` para identificar la extensión (`.txt`, `.csv`, `.json`, `.py`, `.md`).
3. Usa `isalpha()`, `isdigit()`, `isalnum()` para verificar si el nombre (sin extensión) contiene solo letras, solo dígitos, o alfanuméricos.
4. Retorne un diccionario `{extension: [listade_archivos]}` y una lista de archivos que son "backup".
5. Retorne también un diccionario `{archivo: {"solo_letras": bool, "solo_digitos": bool, "alfanumerico": bool}}` para cada archivo.

**Entrada:**
```python
archivos = [
    "backup_datos.csv",
    "informe.txt",
    "datos_2024.csv",
    "script.py",
    "README.md",
    "backup_config.json",
    "123_archivo.txt",  # ¿es solo dígitos? no, tiene letras → alfanumérico
    "archivo.txt",
]
resultado = clasificar_archivos(archivos)
print(resultado["extensiones"])
# {".csv": ["backup_datos.csv", "datos_2024.csv"], ".txt": ["informe.txt", "123_archivo.txt", "archivo.txt"], ".py": ["script.py"], ".md": ["README.md"], ".json": ["backup_config.json"]}
print(resultado["backups"])  # ["backup_datos.csv", "backup_config.json"]
```

---

### Ejercicio 621: Función de orden superior para aplicar filtros en cadena
**Enunciado:** Escribeuna función `aplicar_filtros_cadena(lista, *funciones)` que:
1. Aplica cada función de `funciones` a `lista` secuencialmente (la salida de una es la entrada de la siguiente).
2. Cada función debe ser una función que tomauna lista y retornauna lista filtrada o transformada.
3. Usa `reduce()` para aplicarlas en cadena.
4. Si no se pasan funciones, retorna la lista original.
5. Escribe funciones de filtro auxiliares: `filtrar_pares(lista)`, `filtrar_impares(lista)`, `filtrar_positivos(lista)`, `filtrar_negativos(lista)`, `duplicar_elementos(lista)`, `elevar_al_cuadrado(lista)`.

**Entrada:**
```python
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
resultado = aplicar_filtros_cadena(numeros, filtrar_pares, elevar_al_cuadrado, lambda x: x[:3])
print(resultado)  # [4, 16, 36] (pares: 2,4,6,8,10 → al cuadrado: 4,16,36,64,100 → primeros 3: 4,16,36)
```

---

### Ejercicio 622: Cifrado de texto con desplazamiento variable (One-Time Pad simplificado)
**Enunciado:** Escribeuna función `cifrar_otp(texto, clave)` que:
1. Para cada carácter de `texto`, si es letra, aplica un desplazamiento basado en el carácter correspondiente de `clave` (repetida cíclicamente): desplazamiento = `(ord(clave[i % len(clave)]) - ord('A')) % 26`.
2. Conserva el caso (mayúsculas y minúsculas).
3. Caracteres no letras se conservan.
4. Usa `map()` con una función que maneja cada carácter.
5. `descifrar_otp(texto_cifrado, clave)` hace lo inverso (desplazamiento negativo).
6. Valida con un ejemplo.

**Entrada:**
```python
clave = "KEY"
print(cifrar_otp("Hola", clave))  # H desplazado por K=10 → R; o por E=4 → S; l por Y=24 → J; a por K=10 → K → "RSJK"
print(descifrar_otp("RSJK", clave))  # "Hola"
```

---

### Ejercicio 623: Validación de URLs con métodos de string
**Enunciado:** Escribeuna función `validar_url(url)` que:
1. Verifica que `url.startswith("http://")` o `url.startswith("https://")` — si no, retorna `{"valida": False, "error": "Debe comenzar con http:// o https://"}`.
2. Verifica que no contenga espacios (`" " not in url`).
3. Verifica que contenga al menos un `.` después del protocolo.
4. Extrae el dominio: busca el primer `/` después de "://" y toma lo que está entre "://" y ese `/`.
5. Verifica que el dominio contenga al menos un `.` (para TLD).
6. Retorne `{"valida": True/False, " dominio": dominio_extraido, "detalles": dict_con_resultados_de_cada_validación}`.

**Entrada:**
```python
print(validar_url("https://www.google.com/search"))  # {"valida": True, "dominio": "www.google.com", ...}
print(validar_url("ftp://archivo.com"))  # {"valida": False, "error": "Debe comenzar con http:// o https://"}
print(validar_url("https://ejemplo"))  # {"valida": False, "error": "El dominio debe contener un TLD (.com, .org, etc.)"}
```

---

### Ejercicio 624: Análisis de texto con reduce — conteo de palabras por longitud
**Enunciado:** Dado un texto, usaa `reduce()` para:
1. Construir un diccionario `{longitud: cantidad_de_palabras}` que cuenta cuántas palabras hay de cada longitud.
2. Encontrar la longitud más común y la menos común.
3. Calcular el promedio de longitud de las palabras.
4. Retornar un diccionario con todos estos resultados y la lista de palabras ordenadas por longitud.

**Entrada:**
```python
texto = "La programación es divertida y desafiante. Me encanta programar en Python."
resultado = analisis_longitud_reduce(texto)
print(resultado)
# {"longitud_frecuencia": {2: 2, 3: 2, 4: 3, ...}, "longitud_mas_comun": 4, "longitud_menos_comun": 12, "promedio_longitud": 4.2, "palabras_ordenadas_por_longitud": [...]}
```

---

### Ejercicio 625: Transformación final — pipelines de datos con strings, archivos y funciones de orden superior
**Enunciado:** Implementa un pipeline de procesamiento de datos completo:
1. Lee un archivo de texto con datos (formato: cada línea es `nombre, email, edad, ciudad`).
2. Parsea cada línea y crea una lista de diccionarios.
3. Usa `filter()` para filtrar personas con edad >= 18.
4. Usa `map()` para transformar a tuplas `(nombre, email, edad, ciudad)`.
5. Usa `sorted()` con `key=lambda` para ordenar por edad descendente.
6. Usa `reduce()` para agrupar por ciudad y contar personas.
7. Escribe los resultados en un archivo de salida con formato de reporte.
8. Todo el pipeline debe estar en una función `pipeline_datos(archivo_entrada, archivo_salida)` que retorne el resumen final.

**Entrada:** (archivo `/tmp/datos_personales.txt` con contenido de ejemplo)
**Salida:**
```python
# archivo_salida contiene un reporte formateado
# resumen retornado: {"total_personas": N, "mayores_de_edad": M, "por_ciudad": {"México": 2, "Guadalajara": 1, ...}, "personas_mas_joven": (nombre, edad), "persona_mas_adulta": (nombre, edad)}
```

