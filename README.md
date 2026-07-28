# SCZ1 Escobar - Info Interna

Portal web interno del centro de logistica **SCZ1 (Escobar)**. Replica en formato web el file interno "SCZ1 Escobar - INFO INTERNA", organizado en solapas.

## Como funciona

Es un sitio estatico (HTML + JS, sin dependencias). El archivo `index.html` levanta cada solapa leyendo un JSON de la carpeta `/data`. Para actualizar o eliminar datos, se edita el JSON correspondiente.

## Solapas incluidas

- **Plan de Trabajo 2026** - `data/plan-trabajo.json`
- **Proyectos SCZ1** - `data/proyectos.json`
- **Mensual Operativa** (auditorias + acceso Moki) - `data/mensual-operativa.json`
- **Solucion de problemas** - `data/solucion-problemas.json`
- **On Way** - `data/on-way.json`
- **Estacion Errada** - `data/estacion-errada.json`
- **Avisos de Riesgo** - `data/avisos-riesgo.json`

## Uso local

Al usar `fetch()` sobre los JSON, conviene servir la carpeta con un servidor local (por ejemplo `python -m http.server`) o publicarlo con GitHub Pages en lugar de abrir el archivo directamente.

## Seguridad

Por tratarse de un repositorio **publico**, las credenciales de acceso (usuario y contrasena de Moki) **no** se publican aqui. Solo se incluyen el link del portal, la empresa y el instructivo. La gestion de credenciales es interna.
