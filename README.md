# Conclusiones & Discoveries 

Trabajo Práctico Final - Fundamentos de Analisis de Datos en Python - Primer Cuatrimestre 2025 - Vázquez Nadal

## Conclusiones 1
**Factores más correlacionados con el precio por noche:**
El precio está fuertemente determinado por las características físicas del alojamiento, especialmente la capacidad (personas, camas, dormitorios) y el tipo de propiedad. Sin embargo, el puntaje de reviews no tiene un impacto tan claro en el precio como se podría esperar.

Quienes tienen alojamientos más pequeños pueden competir diferenciándose con calidad, diseño o experiencias únicas, ya que las reviews positivas no están siendo capitalizadas en los precios como podrían. También pueden beneficiarse de un pricing más inteligente en temporadas altas o fines de semana.

## Conclusiones 2
Existen barrios que ofrecen experiencias muy bien valoradas por los huéspedes a un precio significativamente más bajo que zonas más populares y caras. Algunas zonas poco turísticas pueden ofrecer una mejor relación calidad-precio.
La Marina de Port, Sant Martí de Provençals y El Congrés i els Indians ofrecen la mejor combinación de precios bajos y puntajes altos. En cambio, barrios como Diagonal Mar o la Vila Olímpica son caros pero no necesariamente mejor puntuados.

Los viajeros con presupuesto limitado pueden enfocarse en estos barrios alternativos sin resignar calidad. Por otro lado, los hosts en zonas caras deberían trabajar en mejorar la percepción de valor: ofrecer amenities distintivos o estrategias de diferenciación para justificar el precio.

## Conclusiones 3
Ser superhost está fuertemente asociado con mejores ingresos, más reviews y mejor reputación. Claramente marca una diferencia en performance.

Los hosts con entre 6 y 10 propiedades obtienen el mejor rendimiento. En cambio, los que manejan más de 10 tienden a tener menor reputación y menos ingresos por alojamiento (posiblemente por perder el toque personalizado y con ello la calidad de servicio).

Si sos un host individual o pequeño, enfocarte en alcanzar y mantener el estatus de superhost debería ser prioridad. Si sos un host con muchas propiedades, invertir en estandarización, automatización o gestión profesional puede ayudarte a recuperar calidad y reputación.

## Conclusiones Bonus
Este modelo predictivo se centró en estimar los ingresos anuales de un alojamiento en Airbnb Barcelona, lo cual representa una métrica muy relevante para los hosts desde el punto de vista del negocio.

Usando un modelo de Random Forest Regressor y variables como la capacidad del alojamiento, el precio, la disponibilidad, el puntaje promedio y el tipo de propiedad, se logró:

Un error absoluto medio (MAE) de €9.424, lo cual es razonable en un rango de ingresos anuales que puede variar ampliamente.

Un R² de 0.44, lo que indica que el modelo explica el 44% de la variación en los ingresos. 

Este modelo es una herramienta sólida para estimar el rendimiento económico de una propiedad y tomar decisiones más informadas sobre precios, disponibilidad y calidad del servicio.

