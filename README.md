# QUIZ-FLEX
Es un analizador léxico en Flex que valida números complejos de la forma:
a + bi
donde a y b son números reales (incluyendo notación científica) y la unidad imaginaria puede ser i, I, j o J. Se permiten espacios opcionales y el coeficiente de la parte imaginaria puede omitirse (por ejemplo, a+i).

El programa procesa un archivo de texto línea por línea e imprime en pantalla ACEPTA o NO ACEPTA según cada expresión evaluada.

Contenido del archivo .zip

complejo.l → Código fuente en Flex del analizador.

entrada.txt → Archivo de prueba con expresiones a validar.
