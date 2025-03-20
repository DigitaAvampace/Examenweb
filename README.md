# Examenweb

# Exámenes Integrados - Educación Infantil

Este repositorio contiene una colección de exámenes integrados diseñados para un nivel universitario avanzado en Educación Infantil. Los exámenes combinan tres temas fundamentales:

- **Psicomotricidad:** Evolución histórica, modelos teóricos y métodos de intervención.
- **Educación sensoriomotora y cognitiva:** Planificación, estimulación multisensorial y desarrollo integral.
- **Evaluación de la intervención:** Técnicas, instrumentos y enfoques evaluativos (cualitativos y cuantitativos).

## Estructura del repositorio


- **indice.json:** Archivo índice que lista todos los exámenes con su `id`, `titulo` y `ruta` al archivo JSON.
- **index.html:** Página principal que carga el índice y permite visualizar el contenido de cada examen.
- **examenes/*.json:** Archivos JSON que contienen los exámenes integrados.

## Cómo funciona

1. **Visualización del índice:** Al abrir `index.html`, se carga el archivo `indice.json` y se muestra una lista de exámenes.
2. **Carga de exámenes:** Al hacer clic en un examen, se carga su contenido (archivo JSON) y se muestra formateado en la misma página.
3. **GitHub Pages:** Se recomienda configurar GitHub Pages para que este sitio sea accesible públicamente.

## Instrucciones de despliegue

1. Clona el repositorio:
   ```bash
   git clone https://github.com/DigitaAvampace/Examenweb.git
   cd Examenweb

---git add .
git commit -m "Agregar archivos de exámenes, índice, index.html y README"
git push origin main


### Resumen de pasos

1. **Estructura del repositorio:** Crea la carpeta `/examenes/` con los archivos JSON de los exámenes, junto con `indice.json`, `index.html` y `README.md` en la raíz.
2. **Archivo índice:** Define el listado de exámenes con `id`, `titulo` y `ruta`.
3. **Archivo HTML:** Usa JavaScript para cargar el índice y, al hacer clic, obtener y mostrar el contenido del examen.
4. **Archivo README:** Documenta el proyecto, la estructura y las instrucciones para desplegarlo con GitHub Pages.
5. **Despliegue:** Sube el repositorio a GitHub, configura GitHub Pages y accede a la URL pública.

Con estos pasos y el código proporcionado, tendrás una implementación completa y funcional para mostrar y acceder a los exámenes desde la web usando GitHub Pages.
