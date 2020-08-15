# De compras por la red

En <a href="https://decomprasporlared.com">DeComprasPorLaRed</a> se desarrollan tres áreas totalmente independientes y todas ellas con el objetivo común de orientar y/o asesorar a las personas en sus compras por Internet.

- <strong>Cestín</strong>.  Nuestro asesor inteligente de productos de Internet publicando diariamente sus <a href="https://decomprasporlared.com/categorias">recomendaciones</a> sobre más de 60 categorías diferentes de productos.
- <strong>Expertos</strong>. Noticias y reviews de colaboradores con conocimientos sobre diferentes categorías de productos. 
- <strong>Foros</strong>. Para compartir opiniones e impresiones sobre productos o servicios.

<strong>Arquitectura básica de Cestín</strong>
Cestín es un proceso automático desarrollado íntegramente en Python e instalado en una Raspberry Pi 3 que realiza diariamente sin descanso las siguientes tareas:

1. <strong>Obtención de datos</strong>.  Cestín obtiene y almacena información de productos disponibles en las diferentes tiendas de Internet.  Entre la información más relevante que obtiene se encuentra el nombre del producto, categoría, precio, valoración global de los usuarios y los comentarios individuales realizados sobre los mismos…
2. <strong>Análisis y recomendación</strong>. Dentro de cada categoría de productos, Cestín puntúa de forma independiente cada uno de los productos para seleccionar los <strong><a href="https://decomprasporlared.com/categorias">4 productos</a></strong> de mayor calidad contrastada.
3. <strong>Publicación</strong>. Los 4 productos recomendados son publicados por Cestín en la web <a href="https://decomprasporlared.com">DeComprasPorLaRed</a> junto a mucha otra información relacionada como la evolución de precios, análisis de sentimiento de comentarios, etc para ayudar a los usuarios a tomar una decisión inteligente.

Las principales librerías Python utilizadas por Cestín son las siguientes:

- <strong>Scrapy</strong> para la obtención de datos de las diferentes tiendas de Internet.
- <strong>Pandas</strong>, Numpy para el análisis númerico que permite realizar las recomendaciones de productos.
- <strong>TensorFlow</strong>, Keras para el análisis de sentimiento de los comentarios asociados a cada uno de los productos recomendados.

Por último, <a href="https://decomprasporlared.com">DeComprasPorLaRed</a>  es una web basada en el famoso y versátil gestor de contenido WordPress.
