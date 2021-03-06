![portada](https://github.com/EmilioOcelotl/cc4-di-2022-2/blob/main/img/of13.png)

# Código Creativo | Cuarto Semestre | 2022-2

**Objetivo:** aplicar conocimientos de programación para diseñar y construir modelos 3D de objetos y espacios en entornos digitales, para su representación, análisis y posible fabricación.

## Sesiones

- [x] Sesión 01 - Repaso | [Código](https://gist.github.com/EmilioOcelotl/e7038c57bf39c7140986d4a4f92bbc9c) | [Video](https://drive.google.com/file/d/1LQItFi6RfXEiQy5_Q9t-4IJAtrSkBmnP/view?usp=sharing)
  - Processing (lenguaje, IDE, motor)
  - Sistema de coordenadas
  - for() sencillo y matrices

- [x] Sesión 02 - 3d y geometrías | [Código](https://gist.github.com/EmilioOcelotl/8c340401323b3ff66f0fb83630095517)
  - [Coordenadas](https://processing.org/tutorials/p3d) (x, y, z)
  - [Geometrías](https://processing.org/examples/primitives3d.html) ( cubo, esfera )
  - for() indentados
  - [transformaciones](https://processing.org/tutorials/transform2d) y push/pop
  - [Cámara](https://processing.org/tutorials/p3d/#camera)	     
  - PeasyCam ( https://mrfeinberg.com/peasycam/ ) 

- [x] Sesión 03 - 2d y 3d | [Código](https://gist.github.com/EmilioOcelotl/ddd755137e64bc76879c26167187d0ff) | [Video](https://drive.google.com/file/d/1CKR6lCja1fHV3hppGZxrwifRpWHLoaOh/view?usp=sharing) 
  - 3d en una pantalla 2d y 2d en un espacio 3d > impresión
  - Lectura de imágenes e iteraciones
  - Luces sencillas
  - Magnitudes y parámetros en 3d 

- [x] Sesión 04 - Posiciones y composición concreta / sintética | [Código](https://gist.github.com/EmilioOcelotl/a2d285f75b7cffb8db3c880de118adb3) | [Video](https://drive.google.com/file/d/14FH2ZwEoDBxqzaUaTD2apg7gmVve6U6l/view?usp=sharing)
  - Imágenes y profundidad - Revisión y entrega en Brightspace
  - Guardar posiciones en un arreglo 

- [x] Sesión 05 - noise() y PVector | Código | [Video](https://drive.google.com/file/d/1OpmG4ZyXse1bbjIy5A9d_XlpHomoL-HB/view?usp=sharing)
  - Composición sintética
    - [modos de color](https://processing.org/reference/colorMode_.html)  
    - función noise en profundidad y color
  - [PVector](https://processing.org/reference/PVector.html) para guardar posiciones
  - Guardar y reconstruir con archivos de texto plano 

- [x] Sesión 06 - Mallas y triángulos | [Código](https://gist.github.com/EmilioOcelotl/660b89a794a59b521df9e80582d6c601) | [Video](https://drive.google.com/file/d/1OeZXXRPP3TrWFSecctIJRyaLr1sWtRql/view?usp=sharing) 
  - 3d y programas gráficos
  - [Triangle mesh](https://en.wikipedia.org/wiki/Triangle_mesh)
  - beginShape y el caso [triangle strip](https://processing.org/reference/beginShape_.html)
  - vertices como posiciones e interecciones como caras 
  - Distintas formas de abordar un mesh: el caso de [three.js](https://threejs.org/manual/#en/fundamentals) 

- [x] Sesión 07 - Mesh y audioreactividad | [Código](https://gist.github.com/EmilioOcelotl/f4bd04fb76ebb0446d0a082c63235d91) | [Video](https://drive.google.com/file/d/1FdHyT0AmjITfPoLq0b_hcl4Nln_arJ8T/view?usp=sharing)
  - Repaso del mesh que construimos la sesión pasada
  - Algunas ideas sobre [sonido](https://processing.org/tutorials/sound), la computadora y Processing 
  - Análisis de audio y la música como información
  - [Amplitud](https://processing.org/reference/libraries/sound/Amplitude.html), [forma de onda](https://processing.org/reference/libraries/sound/Waveform.html) y [fft](https://processing.org/reference/libraries/sound/FFT.html)
  - Bins > posición en z 

- [x] Sesión 08 - Esfera, coordenadas esféricas y coordenadas polares | [Código](https://gist.github.com/EmilioOcelotl/0f0984f27bd0242a36e56759732bd3ce) | [Video](https://drive.google.com/file/d/1d4nlFMTGr1vgnt-EgWh3hP-GZlynO8a3/view?usp=sharing)
  - [Coordenadas geográficas](https://es.wikipedia.org/wiki/Coordenadas_geogr%C3%A1ficas) y la localización de un punto a partir de dos coordenadas ( la tercera, es altitud ) 
  - [Coordenadas esféricas](https://es.wikipedia.org/wiki/Coordenadas_polares#Coordenadas_esf%C3%A9ricas) y conversión a coordenadas cartesianas
  - Pasos
    - PeasyCam
    - Usamos ángulos: longitud (-180, 180 ) y latitud (-90, 90) y anidamiento de for() para localizar puntos
    - Iteraciones con resoluciones determinadas y luego mapeo a valores de long lat
    - Convertir (r, lat, long ) a  (x, y, z)
      - Theta > lat
      - Phi > lon

- [x] Sesión 09 | [Video](https://drive.google.com/file/d/1rivLuFqiTSQuWWVREKgA2EEKcyYVKQdk/view?usp=sharing) | [Código](https://gist.github.com/EmilioOcelotl/fc54ce415e4fbf77128314f0dbefb478)

   - Modulación: esfera + noise + información de audio
   - texturas 

- [x] Sesión 10 | [Video](https://drive.google.com/file/d/1AQQXlGl4Q1zObFSWOreJs9VmpBRA-QPQ/view?usp=sharing) 

  - Entrega de ejercicio final con audio e imagen como textura.
  - Muestra de ejemplos
  - ¿Tiempo de pasar a otra plataforma?
    - Three.js, la web y el formato glTF > [ejemplos]()
    - Texturas con [Hydra](https://hydra.ojack.xyz/)
  - Para la entrega final: [OBJExport](https://n-e-r-v-o-u-s.com/tools/obj/)

- [x] Sesión 11
  - Repaso del último código revisado ( plano )
  - Ajustes para el siguiente ejercicio ( quitar o comentar audio ) 
  - Figuras a partir de superficies. Ejemplo: [Steinbach Screw](https://mathworld.wolfram.com/SteinbachScrew.html)
    - Importante: mover lon y lat dentro de fors anidados
  - Librería [Nervoussystem](https://n-e-r-v-o-u-s.com/tools/obj/) para capturar obj
  - Condicionales para capturar
  - Optativo: agregar noise 

- [x] Sesión 12 | [Código](https://gist.github.com/EmilioOcelotl/3af155903c25a17f7da4cda546fd0603) | [Video](https://drive.google.com/file/d/1kgzNkEZAs2qoCaZuwaYzL70N3vK7H8km/view?usp=sharing)
  - Inquietudes 
  - Otras formas (de más sencillas a más complejas): [Torus](https://mathworld.wolfram.com/Torus.html), [Elliptic Torus](https://mathworld.wolfram.com/EllipticTorus.html), [Elliptic Paraboloid](https://mathworld.wolfram.com/EllipticParaboloid.html), [Sine Surface](https://mathworld.wolfram.com/SineSurface.html), [Corkscrew surface](https://mathworld.wolfram.com/CorkscrewSurface.html), [Helicoid](https://mathworld.wolfram.com/Helicoid.html), [Catalan Surface](https://mathworld.wolfram.com/CatalansSurface.html), [Astroidal Ellipsoid](https://mathworld.wolfram.com/AstroidalEllipsoid.html)  
  - [Control](https://www.sojamo.de/libraries/controlP5/) (instalar librería)
    - Sliders y botones 

- [x] Sesión 13 | [Código](https://gist.github.com/EmilioOcelotl/0e35305eee915d3e390abb2a4e26d135) | [Video](https://drive.google.com/file/d/1O7vEPwAVS86njLL2uXXZxfotQzioGdwd/view?usp=sharing)
  - P5 Control 

- [x] Sesión 14 | Controles y transformaciones

- [ ] Sesión 15 | [Código](https://gist.github.com/EmilioOcelotl/9f4a2a71fbef4f72b9abfc80ce880cbd) | [Video](https://drive.google.com/file/d/1DX-XDG1xjt3LN5Zb6K4qF8haR913zI69/view?usp=sharing)

## Pendientes

- Análisis de imagen y estimaciones de profundidad 
- ¿ Cambio de plataforma ? Objetivo final: generar un objeto que pueda imprimirse y exhibirse

## Metas de aprendizaje

- Conocer a nivel intermedio las posibilidades de Java 3D mediante Processing
- Realizar proyectos de diseño de espacios y/o objetos paramétricos para su producción, con posibilidades de personalización a través de interfaces interactivas.

## Evaluación

- Entregas con ejercicios sencillos
- Proyecto final

## Referencias 

- Bohnacker, H., Groß, B., & Laub, J. (2009). Generative design: visualize, program and create with processing. New York: Princeton Architectural Press.
- Cormen, T. H. (2013). Algorithms unlocked. Cambridge, Massachusetts: The MIT Press.
- Cormen, T., & Balkcom, D. (2018, Diciembre). Khan Academy. Retrieved from Computer science algorithms: https://www.khanacademy.org/computing/computer-science/algorithms
- Cramer, F. (2008) Language. In Fuller, Matthew, Ed., Software Studies, a Lexicon. Massachusetts: MIT Press. 
- Crews, T., & Murphy, C. (2008). A guide to working with visual logic.
- Johnsonbaugh, R. (1999). Matemáticas discretas, 4a ed. México: Prentice Hall.
- Liers, F. (n.d.). Basic Introduction into Algorithms and Data. Germany: University of Cologne.
- Petzold, C. (2000). The hidden language of computer hardware and software. Redmond, Washington: Microsoft Press.
- Reas, C., & Fry, B. (2014). Processing: a programming handbook for visual designers and artists. Massachusetts: MIT Press.
- Reas, C., McWilliams, C., & LUST. (2010). Form + Code: in design, art and architecture. New York:Princeton Architectural Press.
- Runberg, D. (2015). The Sparkfun Guide To Processing. San Francisco: No Starch Press. 
- Van Cleave, M., & Community, L. (2016). Introduction to logic and critical thinking. Independent.
