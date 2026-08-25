# CENEVAL Economía Trainer

Entrenador personal en HTML para preparación intensiva del **EGEL Plus Economía (CENEVAL)**.

## Objetivo

Practicar reactivos de Economía en formato de examen, medir aciertos y velocidad, detectar debilidades y exportar cada intento a JSON para analizarlo posteriormente con ChatGPT.

## Áreas

- Microeconomía
- Macroeconomía
- Proyectos de inversión

## Funciones de la V1

- Modos de 20, 50 y banco completo.
- Preguntas y opciones aleatorias.
- Cronómetro total y tiempo acumulado por reactivo.
- Navegador de preguntas.
- Marcación de confianza: Seguro / Dudoso / Adiviné.
- Resultados por área y tema.
- Exportación de resultados a JSON.
- Historial local de intentos con `localStorage`.
- Modo Revancha para repetir errores del intento anterior.
- Funciona completamente en el navegador, sin servidor ni dependencias externas.

## Uso

1. Descarga `index.html`.
2. Ábrelo con cualquier navegador moderno.
3. Selecciona el modo de examen.
4. Responde y pulsa **Terminar examen**.
5. Descarga el JSON generado.
6. Sube ese JSON a ChatGPT y pide un análisis de fortalezas, debilidades, velocidad y plan de repaso.

## Formato del JSON

Cada resultado contiene fecha, modo, duración, puntuación global, puntuación por área/tema, respuesta elegida, respuesta correcta, confianza, tiempo por reactivo, preguntas no contestadas e IDs de errores para el modo Revancha.

> Herramienta de estudio independiente. No es un producto oficial ni está afiliado con CENEVAL.
