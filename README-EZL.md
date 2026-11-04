# Calculadora de sistema solar autónomo

Página web que calcula cuántos paneles solares, baterías y qué inversor necesita una vivienda que no está conectada a la red eléctrica.

## Qué hace

- Calcula el consumo diario de energía a partir de los equipos de la vivienda.
- Indica el número de paneles solares necesarios.
- Indica la capacidad de las baterías.
- Sugiere la potencia del inversor.

Los resultados se actualizan automáticamente al cambiar cualquier dato.

## Cómo usarla

1. Agrega tus equipos con su potencia en watts, las horas de uso al día y la cantidad.
2. Indica las horas de sol de tu zona, el voltaje del sistema, los días sin sol que debe soportar y los watts de cada panel.
3. Lee los resultados en la sección "Lo que necesitas".

Para usarla en tu computadora, descarga el archivo `index.html` y ábrelo con cualquier navegador. No necesita instalación ni conexión a internet.

## Supuestos del cálculo

- Eficiencia de baterías e inversor: 85 %.
- Pérdidas del sistema: 25 %.
- Descarga máxima de las baterías: 50 %.
- El inversor se calcula con todos los equipos encendidos a la vez, más un 25 % de margen.

Los resultados son referenciales y deben validarse con datos reales de radiación solar y con las fichas técnicas de los equipos.

## Archivos

- `index.html`: la calculadora completa (HTML, estilos y cálculo en un solo archivo).
- `README.md`: esta descripción.

## Autor

Eduardo Zumaeta Labajos
Ingeniería de la Energía, Universidad Nacional Toribio Rodríguez de Mendoza de Amazonas (UNTRM)

## Licencia

MIT
