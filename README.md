# PEC3: Visionando el futuro con las gafas de Manovich 

### Recurso de aprendizaje de Cultura Digital 


Autor: Óscar Rafael Fernández Sánchez


Fecha: 12/05/2025

## Índice
- [Planteamiento](#planteamiento)
- [Caso 1: Xbox Cloud Gaming](#caso-1-xbox-cloud-gaming)
- [Caso 2: Midjourney en Discord](#caso-2-midjourney-en-discord)
- [Conclusión](#conclusión)
- [Referencias y Bibliografía](#referencias-y-bibliografía)


## Planteamiento
En El lenguaje de los nuevos medios y en Software toma el mando, Manovich describe cómo el software redefine nuestros medios. Hoy en día, esa hibridación ha dado lugar a ecosistemas digitales completamente nuevos que merecen un análisis independiente. Este ensayo explora dos casos contemporáneos de hibridación no abordados por Manovich: he elegido Xbox Cloud Gaming por su innovadora fusión entre streaming y gaming, y Midjourney en Discord por integrar IA generativa en una plataforma social que entrelaza comunicación y creación artística colaborativa. Ambos ejemplos reflejan cómo la nube y la inteligencia artificial están transformando nuestras prácticas culturales digitales.


## Re-descubriendo la hibridacion: Caso 1
![project-xcloud-microsoft](https://github.com/user-attachments/assets/4bf47907-99fd-47df-b3bd-6d085703eca7)

## Caso 1: Xbox Cloud Gaming

### Descripción
Xbox Cloud Gaming es un servicio de suscripción (parte de Xbox Game Pass Ultimate) que permite jugar a títulos de última generación directamente en la nube, sin necesidad de descargar ni instalar nada en el dispositivo local. Funciona sobre cualquier pantalla con conexión a Internet —smartphones, tablets, PCs, televisores o incluso otras consolas—, pues el juego se renderiza en centros de datos de Microsoft y se transmite al instante como un flujo de vídeo interactivo.

Project xCloud se presentó por primera vez el 8 de octubre de 2018 en el blog de Microsoft, marcando el inicio de un ambicioso proyecto para llevar la experiencia Xbox a cualquier dispositivo mediante streaming.
. Durante 2019 se lanzó la primera vista previa pública, permitiendo a los usuarios probar títulos como Gears 5 y Halo 5 en móviles Android mediante la app de Xbox Game Streaming GeekWire.
. El 15 de septiembre de 2020, Microsoft integró oficialmente el servicio en Xbox Game Pass Ultimate, ampliando la disponibilidad a PC y consolas sin coste adicional para los suscriptores. En 2021 y 2022 se actualizaron los servidores a hardware basado en Xbox Series X y se añadió soporte web, alcanzando millones de usuarios en decenas de países.

### Elementos de hibridación
- **Automatización y transcoding**: el software del juego (motores gráficos Unity/Unreal) corre automáticamente en servidores remotos y, en tiempo real, se codifica (transcoding) en vídeo optimizado para cada ancho de banda.  
- **Modularidad**: la arquitectura basada en microservicios desacopla la lógica de juego, el almacenamiento de partidas y las funciones de matchmaking, permitiendo actualizaciones continuas sin interrumpir la experiencia del usuario.  
- **Variabilidad**: configuración automática de la calidad gráfica y la latencia según el dispositivo y la velocidad de red del usuario, generando múltiples “versiones” del mismo juego adaptadas a cada contexto.  
- **Software como servicio cultural**: se abandona el modelo de venta de licencias individuales para convertirse en un servicio por suscripción, con colas de prioridad, análisis de uso y repositorios de datos de telemetría que alimentan mejoras constantes.

### Análisis (bajo las “gafas de Manovich”)
1. **Representación numérica y transcoding**: Xbox Cloud Gaming codifica el mundo 3D de los juegos en datos de vídeo comprimido, ejemplificando la conversión permanente de medios analógicos (la imagen en pantalla) a forma digital manipulable.  
2. **Automatización**: el proceso de renderizado, compresión y distribución se orquesta sin intervención humana, liberando al jugador de cualquier consideración técnica más allá de conectarse a Internet.  
3. **Variabilidad**: el mismo título puede verse y jugarse con distintos niveles de detalle gráfico o resoluciones según el dispositivo, introduciendo “versiones” variables de un mismo medio.  
4. **Modularidad y actualización continua**: al funcionar en la nube, cada parche o DLC se despliega de forma instantánea para toda la comunidad, sin necesidad de instalaciones locales ni gestión de dependencias, lo que facilita la evolución permanente del medio.  
5. **Nuevo lenguaje mediático**: al convertir el videojuego en servicio de streaming, se configura un espacio de interacción colectivo donde fluyen datos de telemetría, métricas sociales (logros, retransmisiones) y experiencias compartidas en directo, generando un lenguaje híbrido entre videojuego, vídeo bajo demanda y red social.

En conjunto, Xbox Cloud Gaming ejemplifica la hibridación de medios al convertir el producto de software en un servicio cultural dinámico, anclado en infraestructuras de la nube y gobernado por principios algorítmicos de automatización, transcoding y variabilidad.  

## Re-descubriendo la hibridacion: Caso 2

![MIDJOURNEY](https://github.com/user-attachments/assets/7b30b65f-668e-4fae-9426-48eb31ca94c1)


## Caso 2: Midjourney en Discord

### Descripción
Midjourney debutó en beta abierta el 12 de julio de 2022 como un bot de Discord que convierte descripciones de texto en obras de arte mediante un avanzado modelo de difusión latente. En cuestión de meses superó el millón de imágenes generadas y vio crecer su comunidad de forma exponencial. A finales de 2022 lanzó la versión 4, con mejoras sustanciales en calidad y coherencia, y en 2023 presentó Midjourney V6, optimizando aún más la interpretación de los prompts y el nivel de detalle visual. Como bot de IA, Midjourney funciona únicamente dentro de Discord: al escribir  /imagine <tu prompt>: El sistema devuelve un grid de cuatro imágenes en segundos. Los botones “U” (upscale) y “V” (variations), junto con parámetros de calidad (`--q`), relación de aspecto (`--ar`) y estilo (`--stylize`), permiten refinar y personalizar los resultados sin salir de la ventana de chat.


### Elementos de hibridación
- **Metamedia**: fusiona creación pictórica y fotográfica con algoritmos de IA, simulando medios previos y produciendo un nuevo espacio creativo texto–imagen.  
- **Automatización**: todo el pipeline (interpretación del prompt, generación y renderizado) se ejecuta sin intervención manual.  
- **Variabilidad**: controles de parámetro (`--stylize`, `--ar`, `--v`) y comandos de “reroll” generan infinitas versiones de un mismo concepto.  
- **Modularidad**: cada prompt, cada imagen y cada interacción (votos, comentarios) actúa como módulo reutilizable en nuevos contextos.  
- **Software como servicio**: funciona por suscripción en la nube, con distintos planes que gestionan acceso a GPU en “Fast” y “Relax” Mode, así como modo privado.  
- **Interfaz social**: la integración en Discord convierte la creación en un ritual comunitario, donde la conversación y el crowdsourcing alimentan un repositorio vivo de conocimientos.

### Análisis (bajo las “gafas de Manovich”)
1. **Representación numérica**: el texto se convierte en vectores que el modelo traduce a matrices de píxeles, ejemplificando la digitalización de medios.  
2. **Transcoding**: transforma un lenguaje natural en imágenes digitales, ilustrando la conversión y mezcla de códigos mediáticos.  
3. **Automatización y variabilidad**: la generación instantánea de múltiples variaciones refleja estos dos principios fundamentales de Manovich.  
4. **Modularidad colaborativa**: la estructura de canales, prompts e interacciones sociales configura un ecosistema modular de creación distribuida.  
5. **Metamedia expandida**: Discord funciona como lienzo digital extensible, combinando texto, imagen y código de IA para gestar un nuevo medio.  
6. **Nuevo lenguaje mediático**: la dinámica de co-creación y remix comunitario redefine la práctica artística tradicional y actualiza la noción de medio planteada por Manovich.

## Conclusión
- Gracias a la exploración de Xbox Cloud Gaming y Midjourney en Discord “con las gafas de Manovich” he descubierto hasta qué punto ha cambiado nuestra manera de crear y vivir la cultura digital: ambos casos fusionan mundos que parecían distantes —el juego de alto rendimiento y el arte generativo— para ofrecer experiencias tan intuitivas como asombrosas. Xbox Cloud Gaming derriba las barreras del hardware, regalándonos la sensación de un salón de videojuegos global al que asomarnos desde cualquier pantalla, de la misma forma que Netflix transformó el consumo audiovisual y sacudió la todopoderosa industria del cine. Por su parte, Midjourney convierte cada prompt en una chispa colectiva que crece con la curiosidad de la comunidad, llevando la colaboración creativa en tiempo real al siguiente nivel. Estas plataformas no son meras herramientas, sino ecosistemas vivos donde técnica e imaginación se entrelazan, recordándonos que la verdadera hibridación no reside solo en la tecnología, sino en cómo nos invita a repensar el acceso y explotación a los medios y a cómo se tranforma y se modldea la cultura en nuestras sociedades.
 


### Referencias y Bibliografía

1. Manovich, Lev. (2013). **El Software toma el mando**. Barcelona: Editorial UOC.
2. Microsoft. “Xbox Cloud Gaming.” https://www.xbox.com/es-ES/xbox-game-pass/cloud-gaming
3. Microsoft Docs. “Game Streaming over Azure.” [https://docs.microsoft.com/…](https://learn.microsoft.com/en-us/gaming/gdk/docs/services/fundamentals/live-xbl-overview)
4. Microsft Docs. "Historia de Xcloud" https://blogs.microsoft.com/blog/2018/10/08/project-xcloud-gaming-with-you-at-the-center
5. Midjourney. “Discord Command List.” https://docs.midjourney.com/hc/en-us/articles/32894521590669-Discord-Command-List
6. Midjourney. "Tutorial para Discord" https://docs.midjourney.com/hc/en-us/articles/32631709682573-Discord-Quick-Start
7. Viso.ai. (2024) "Noticias acerca de generación de arte con IA "https://viso.ai/deep-learning/midjourney-stable-diffusion/
8. Medium. (2023) "Noticias acerca midjourney" https://medium.com/%40oluigbopeter/how-midjourney-became-a-billion-dollar-ai-art-startup-in-less-than-a-year-416663997f77

## Uso de IA

Para la generación de ideas y búsqueda de documentación especifica se empleo el uso de modelo GPT-4 de OpenAI.

