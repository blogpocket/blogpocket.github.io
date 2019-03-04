---
layout: post
title: Mary tenía un blog
image: /images/cover-promocion-blogpocket-6.png
author: Antonio C.
categories: ideas
published: false 
---

... Y lo perdió gracias al malware.

![cover-promocion-blogpocket-6.png]({{site.baseurl}}/images/cover-promocion-blogpocket-6.png)

Mary es la desdichada protagonista del post de Sucuri, [A Little Tale About Website Cross-Contamination](https://blog.sucuri.net/2012/03/a-little-tale-about-website-cross-contamination.html).

Y es que Mary tenía todo su blog protegido con todo lo que se recomienda en Blogpocket; por ejemplo en el post [Las 10 medidas de seguridad imprescindibles en WordPress](https://www.blogpocket.com/2016/07/24/las-10-medidas-de-seguridad-imprescindibles-en-wordpress/).

Ella usaba WordPress y siempre lo mantenía actualizado. También tenía sus plugins y themes actualizados, usaba contraseñas seguras, accedía al panel de administración a través de SSL y tomaba muy en serio todas las recomendaciones de seguridad. Incluso tenía instalado el [plugin WordFence](https://www.blogpocket.com/2016/08/14/configurar-wordfence/) y su blog estaba conectado a [CloudFlare](https://www.blogpocket.com/2016/07/31/velocidad-seguridad-blog-cloudflare/).

Pero cometió un «pequeño» error: creó un blog de pruebas con un dominio adicional y se despreocupó. No siguió las directrices de seguridad que tenía aplicadas a su blog principal.

Pasó el tiempo, uno de los plugins tenía una vulnerabilidad y eso fue aprovechado por los hackers para entrar atacando el blog de pruebas y realizando una contaminación cruzada hacia su blog de producción.

Estas semanas atrás hemos aprendido muchas cosas. Y una de ellas es que no es conveniente tener nada más que el dominio principal en tu cuenta de hosting compartido; es decir, un blog.

Si quieres hacer pruebas, hazlo en [plataformas como Pilvia](https://twitter.com/i/moments/1000784735205982208).

En servidores compartidos (lo más económico en hosting) es peligroso tener más de un blog en tu cuenta. Si se contamina uno, se contaminarán todos. 


