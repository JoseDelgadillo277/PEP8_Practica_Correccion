Durante el análisis con Pylint, se detectaron errores de estilo relacionados con la falta de documentación del módulo (C0114) y la clase (C0115), los cuales fueron corregidos agregando docstrings descriptivas. Además, se ajustó el formato para cumplir con PEP 8, asegurando una indentación consistente, espaciado adecuado entre funciones y eliminando líneas en blanco innecesarias, mejorando así la legibilidad y funcionalidad del código sin alterar su propósito original.
Nombres de Variables Descriptivos : Aunque no fue señalado por Pylint, se identificó que los nombres de variables como a y b podrían ser más descriptivos para mejorar la claridad del código. Se sugirió renombrarlas a num1 y num2 en los métodos calcular_mcd y calcular_mcm, para reflejar mejor su propósito como números de entrada.
Manejo de Excepciones Mejorado : Si bien el código ya incluye manejo de errores con try-except, se observó que podría ser útil agregar un mensaje más específico en caso de entradas inválidas (por ejemplo, indicando qué tipo de dato es aceptado). Esto mejora la experiencia del usuario al proporcionar retroalimentación más clara durante la ejecución.

Integrantes: 
1. Lozano Porta Henry Rolando
   2. Jhon Sidani Espinoza Mendoza
   3. Delgadillo Pantoja José Samuel
