# Prueba Técnica [Carengo México](http://carengo.mx)
## Descripción
Crea una aplicación web que simula un *feed* de productos, cada elemento tiene la siguiente información:

![alt text](https://drive.google.com/uc?export=view&id=1e_1FsvnnrfDnMoeiJfQeklH6BKACkhlJ "Product example")
* Título
* Imagen
* Descripción
* Precio

La información es obtenida de un *webservice* que puede despachar no más de 20 productos en un solo *request*. El formato del http *request* y de la respuesta es parte de tu solución, es decir, eres libre de diseñarlos como creas más conveniente.

![alt text](https://drive.google.com/uc?export=view&id=14GfOZx6wM1JLOyc4jE-9uI3YH0hHIPQ2 "Scroll Down Example")

El número total de productos en el back-end es de 96. Para mostrarlos correctamente implementa un *infinite scroll*, cada que llegas al final de la página, si hay más productos por mostrar tienes que hacer otra petición http para obtener los siguientes 20, y así sucesivamente hasta que llegues al límite de 96.

## Restricciones técnicas.
- Back-end:
  - Node.js v9.2.0
- Front-end
  - Responsive design, debe funcionar correctamente para móbiles con resolución 360x640 y para browsers con resolución de al menos 1280x800.
  - Usa media queries para el cambio de resolución, no uses Bootstrap o similares.
  - Sólamente usa React, Angular o VanillaJS, no uses JQuery. Puedes usar módulos npm.

## ¿Qué necesitas enviar?
- URL de repositorio público que contiene:
  - README.md
   - Explicación breve de tu solución.
   - Pasos a seguir para ejecutar tu solución en una laptop nueva.
  - src Directorio con el código fuente de tu solución.

## Consejos:
- No pierdas tiempo utilizando una BD, nos interesa más ver como administras los componentes de tu solución y ver la calidad de tu código Javascript.
- Si tienes más experiencia trabajando en backend o frontend pon mayor esfuerzo en esa área, no es necesario que seas experto en ambos.
