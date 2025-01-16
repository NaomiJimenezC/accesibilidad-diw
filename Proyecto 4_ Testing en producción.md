# Proyecto 4: **Testing en producción**

Naomi Jiménez Cerpa

[**Evaluación inicial de estándares y navegación	3**](#evaluación-inicial-de-estándares-y-navegación)

[Reflexión sobre los estándares y navegación intuitiva	3](#reflexión-sobre-los-estándares-y-navegación-intuitiva)

[**Pruebas de Usabilidad	3**](#pruebas-de-usabilidad)

[WebPageTest	3](#webpagetest)

[PageSpeed Insights	3](#pagespeed-insights)

[Lighthouse	3](#lighthouse)

[Ghost Inspector	3](#ghost-inspector)

# Evaluación inicial de estándares y navegación {#evaluación-inicial-de-estándares-y-navegación}

Proyecto escogido: [mymelodyrate.netlify.app](https://mymelodyrate.netlify.app)  
HTML: HTML 5  
Javascript: En concreto JavaScript ES7  
CSS: CSS3

## Reflexión sobre los estándares y navegación intuitiva {#reflexión-sobre-los-estándares-y-navegación-intuitiva}

Considero que los estándares son una cosa esencial en el desarrollo web debido a que nos deja claro qué tecnologías debemos usar y cómo debemos usarlas. Si no esto no existiese ,seguramente viviríamos en un caos en el que cada empresa y/o persona haciendo lo que quisieran como quisieran y no habría mucha compatibilidad entre herramientas. Hay gente que llegaría a considerar que los estándares limitan las formas de trabajar, pero esa limitación, en cuanto al desarrollo web, es de lo mejor que ha podido pasarnos.

Respecto a la navegación intuitiva, lo considero una parte importante a la hora de hacer un diseño de una aplicación web. El que el usuario se sepa guiar y se pueda guiar sin necesidad de mucho trabajo mental y/o físico es algo fundamental para poder retener el número de de usuarios potenciales en nuestra página, sobretodo hoy en día que vivimos en una sociedad con una necesidad preocupante de estímulos y cosas al instantes y sencillas. Es saber cómo guiar al usuario a ir donde tú quieres que vaya sin directrices verbales.

# Pruebas de Usabilidad {#pruebas-de-usabilidad}

## WebPageTest {#webpagetest}

### Home  
#### Chrome  
![alt text](image.png)
![alt text](image-2.png)
![alt text](image-3.png)

#### Firefox
![alt text](image-4.png)
![alt text](image-5.png)

evaluación de Navegación   
Listado ¿?  
Producto ¿?

## PageSpeed Insights {#pagespeed-insights}

3. [**PageSpeed Insights**](https://pagespeed.web.dev/):

   * Analiza al menos **3 páginas clave**: home, listado y producto.  
   * Identifica los **elementos de mejora** y explica las recomendaciones.

**Home**

Cuando hablamos de los resultados de los tests de escritorio: De media tiene un 90 de puntuación en todos los apartados (menos en SEO, que tiene un 82). Respecto al rendimiento, prácticamente todo radica en una mejor optimización de las imágenes en la página mediando el uso de imágenes con formato como WebP o precargando la imagen de renderizado o también poner una altura y anchura explícita a las imágenes.

En cuanto la accesibilidad solo comentan dos cosas, el contraste de los colores de las imágenes con el fondo de la página, aunque eso era intencionado para resaltar el color del texto. También comenta que el select debe usar un label para ayudar a las personas que usan lectores de pantallas.

Todo bien respecto al apartado de prácticas recomendadas

En cuanto SEO, dice que no tengo metadatos en la página y que el archivo robots.txt está mal entero.

**Listado**

Con respecto al listado, a nivel de rendimiento y prácticas recomendables está perfecto, pues esos apartados están puntuados con un 100, pero la accesibilidad y el SEO tienen una media de 85 puntos y quiero profundizar en esos resultados.

La accesibilidad, comenta los resultados, que se pueden mejorar el contraste de colores y hacer los elementos con un mayor tamaño para la zona táctil, pues los elementos de la página son tan pequeños que no hay espacio entre ellos para un correcto uso de ello.


**Producto**

Todo bien menos el apartado de buenas prácticas y el SEO, que es debido al iframe de Spotify, pues debido a ello salen cookies de terceros, lo cual me advierte que eso es un problema de seguridad y que tal vez debería buscar otra solución para quitar ese iframe.

Con respecto al SEO añadimos otra posible mejora es poner enlaces rastreables.

## Lighthouse {#lighthouse}

![alt text](image-6.png)

4. **Optimización con Lighthouse**:

   * Evalúa el rendimiento del sitio web utilizando **Lighthouse** en Chrome DevTools. Mide y analiza los siguientes parámetros:  
     * **Largest Contentful Paint (LCP):** tiempo que tarda en renderizarse el elemento más grande visible.  
     * **Interaction to Next Paint (INP):** latencia en la interacción con elementos interactivos.  
     * **Cumulative Layout Shift (CLS):** estabilidad visual del contenido durante la carga.  
     * **First Contentful Paint (FCP):** tiempo hasta que se muestra el primer elemento visual.  
     * **First Input Delay (FID):** tiempo de respuesta a la primera interacción del usuario.  
     * **Time to First Byte (TTFB):** tiempo hasta recibir el primer byte del servidor.  
   * Documenta los resultados obtenidos y realiza recomendaciones específicas para optimizar cada parámetro medido. 

## Ghost Inspector {#ghost-inspector}



 
5. **Evaluación con Ghost Inspector**

   * Realiza un testeo automatizado con **Ghost Inspector** para comprobar la navegación general y los procesos críticos del sitio web.  
   * Adjunta el **video generado** y analiza los resultados. Por ejemplo, presta atención a posibles fallos como botones inactivos, enlaces rotos o tiempos de carga excesivos.  
   * Una guía visual sencilla podría consistir en comparar la salida del testeo con el comportamiento esperado (por ejemplo, verificar si los pasos automatizados coinciden con el flujo de navegación diseñado).

