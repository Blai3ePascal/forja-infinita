# Verificación de la edición 1.2.0-beta.3

Pascal & Sara · 20 de octubre de 2026

## Resultados

- 207/207 soluciones del recorrido actual ejecutadas en el navegador, con todos sus casos y comprobaciones.
- 145/145 plantillas de completar, programar u ordenar rechazadas en al menos un caso hasta corregirlas.
- 18 cuadernos; 414 celdas de código de trabajo y solución cotejadas con el catálogo.
- Pruebas de economía: compras, precios crecientes, producción fraccionaria, límite de ocho horas, recompensas únicas, guardados antiguos y entradas inválidas.
- Tutorial, teclado, monedas, compra y producción, mapa en ambos sentidos, historial, borradores, ayudas en ventanas y opciones persistentes.
- Análisis automatizado de accesibilidad en nueve vistas: sin incidencias detectadas. Comprobación de móvil a 200 %, controles grandes y movimiento reducido.

Las 207 actividades de los cuadernos de soluciones se ejecutaron en CPython 3.12/Pyodide, incluidas las celdas SQL. También se rechazaron nueve soluciones incorrectas específicas.

## Correcciones de comprobación

Se reforzaron cinco casos de reparación que antes coincidían accidentalmente: máximo negativo, último elemento, avance de búsqueda binaria, acumulación entre llamadas y nota negativa. Dos gráficos comprueban categorías y alturas, además de la imagen y el total.

## Contenido y alcance

La ruta usa nuestros materiales, agrupados en los temas de la asignatura. Las ampliaciones de alcance no confirmado quedan reservadas al profesorado. Consulta [Cobertura](COBERTURA.md).

La revisión documental usa fuentes secundarias de los paquetes; no dispone de los PDF originales del campus para certificar la equivalencia exacta con una guía oficial vigente.

## Límites de las pruebas

Se usó Microsoft Edge/Chromium en Windows. No se ejecutó directamente la interfaz de Colab. Los cuadernos de trabajo incluyen errores o huecos deliberados.

Una batería de casos no demuestra corrección para todas las entradas ni garantiza aprendizaje completo. Las explicaciones, modelos, diseño e interpretación requieren revisión con el profesorado. Las comprobaciones gráficas no califican la calidad de la interpretación.

Los informes de versiones anteriores se conservan como historial y no describen los recuentos de esta edición. La distribución pública contiene el código propio ofuscado; la copia de mantenimiento es legible. Las sumas SHA-256 permiten cotejar la publicación.
