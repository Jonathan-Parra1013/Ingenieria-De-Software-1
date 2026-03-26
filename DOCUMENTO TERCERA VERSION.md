# Contenido


Ficha del documento	3
Contenido	4
1 Introducción	5
1.1 Propósito	5
1.2 Alcance	5
1.3 Personal involucrado	5
1.4 Definiciones, acrónimos y abreviaturas	6
1.5 Referencias	6
1.6 Resumen	7
2 Descripción general	8
2.1 Perspectiva del producto	8
2.2 Funcionalidad del producto	8
2.3 Características de los usuarios	8
2.4 Restricciones	9
2.5 Suposiciones y dependencias	9
2.6 Evolución previsible del sistema	9
3 Requisitos específicos	9
3.1 Requisitos comunes de los interfaces	10
3.1.1 Interfaces de usuario	10
3.1.2 Interfaces de hardware	10
3.1.3 Interfaces de software	10
3.1.4 Interfaces de comunicación	10
3.2 Requisitos funcionales	10
3.2.1 Requisito funcional 1	12
3.2.2 Requisito funcional 2	12
3.2.3 Requisito funcional 3	12
3.2.4 Requisito funcional n	12
3.3 Requisitos no funcionales	12
3.3.1 Requisitos de rendimiento	12
3.3.2 Seguridad	12
3.3.3 Fiabilidad	12
3.3.4 Disponibilidad	12
3.3.5 Mantenibilidad	14
3.3.6 Portabilidad	14
3.4 Otros requisitos	14
4 Apéndices	14



# Introducción
El aprendizaje de las matemáticas constituye un pilar fundamental en la educación básica y media; sin embargo, una gran cantidad de estudiantes presenta dificultades en la comprensión de esta área, lo que se refleja en un bajo rendimiento académico, desmotivación y limitadas oportunidades de aprendizaje autónomo. Estas problemáticas evidencian la necesidad de herramientas educativas que se adapten a las necesidades individuales de cada estudiante.
En este contexto, el presente documento describe la especificación de requisitos de software (SRS) para el desarrollo de Dextech Math, una aplicación orientada al aprendizaje y refuerzo de las matemáticas. El objetivo principal del sistema es proporcionar un entorno interactivo, accesible y personalizado que facilite la comprensión de conceptos matemáticos y promueva el aprendizaje autónomo.
El alcance del software abarca estudiantes de educación media y niveles iniciales universitarios, aunque su diseño inclusivo permite su uso por cualquier persona interesada en fortalecer sus habilidades matemáticas. La solución integra tecnologías basadas en modelos de lenguaje extensos (LLM), que permiten adaptar los contenidos y la retroalimentación al nivel y progreso de cada usuario.


# Propósito
El propósito de este software es ofrecer a los usuarios una herramienta integral para el aprendizaje de las matemáticas, permitiéndoles adquirir conocimientos matemáticos de manera efectiva y atractiva. El software se diseñará para adaptarse a las necesidades individuales de los usuarios y fomentar su participación constante a través de diversas funcionalidades interactivas, motivando al usuario a dar seguimiento a su propio proceso de aprendizaje de forma autónoma. De esta manera, se promueve el interés y la constancia sin que la experiencia se perciba como una obligación, sino como una actividad dinámica y estimulante, adecuada tanto para personas que presentan dificultades en matemáticas como para los que ya son buenas en ellas y solo buscan seguir reforzando sus conocimientos en dicha materia mediante retroalimentación (cuestionarios, lecturas, ejercicios,etc) y  recursos interactivos.

# Alcance
El software va dirigido principalmente a estudiantes de educación media y primeros semestres universitarios que buscan fortalecer bases matemáticas críticas (como álgebra avanzada, cálculo y vectores) para evitar la deserción académica, esto permite que quiera, fortalecer, mejorar y complementar su aprendizaje de las matemáticas de acuerdo con los contenidos de sus respectivos niveles académicos. No obstante, su diseño permitirá que cualquier persona interesada en mejorar sus habilidades matemáticas pueda utilizar la plataforma, independientemente de su nivel de conocimiento previo, también se busca que el software sea accesible e inclusivo, permitiendo el ingreso y uso por parte de cualquier persona. También busca alcanzar a cubrir aquellos temas de matemáticas que se deberían ver durante la educación secundaria, pero que en la mayoría de los casos no se alcanzan a desarrollar y explicar completamente por temas de tiempo, permitiendo a los usuarios repasar, reforzar y consolidar estos contenidos de manera autónoma y progresiva.


# Personal involucrado

- Nombre:
Brenda Madeleine Martínez Enriquez
- Rol:
Programadora y diseñadora secundaria
- Categoría profesional:
Estudiante de Ingeniería en Sistemas
- Responsabilidades:
Diseño de interfaz y apoyo en el desarrollo
- Información de contacto:
brendam-martineze@unilibre.edu.co
- Aprobación:
Pendiente




- Nombre:
Jonathan Parra Landinez
- Rol:
Diseñador principal y programador
- Categoría profesional:
Estudiante de Ingeniería en Sistemas
- Responsabilidades:
Diseño y programación del software
- Información de contacto:
jonathan-parral@unilibre.edu.co
- Aprobación:
Pendiente


# Definiciones, acrónimos y abreviaturas

Aprendizaje Autónomo: Capacidad del estudiante para gestionar, regular y evaluar su propio proceso de aprendizaje de manera independiente, utilizando los recursos de la plataforma.
IA (Inteligencia Artificial): Campo de la informática que busca crear sistemas capaces de realizar tareas que requieren inteligencia humana, como el razonamiento o el aprendizaje.
LLM (Large Language Model): Modelo de Lenguaje Extenso. Tecnología de inteligencia artificial (como GPT) entrenada con grandes volúmenes de texto para comprender, generar y explicar contenidos de forma natural y contextual
Gamificación: Uso de mecánicas y elementos de diseño de juegos (logros, medallas, barras de progreso) en entornos no lúdicos para aumentar la motivación y el compromiso del usuario.
UX (User Experience): Experiencia de Usuario. Se refiere a lo que el usuario siente y experimenta al interactuar con la aplicación, buscando que sea intuitiva y satisfactoria.
Interfaz de Usuario (UI): El espacio donde ocurre la interacción entre el usuario y el sistema; incluye el diseño visual, botones, menús y navegación.
Deserción Académica: Abandono de los estudios por parte del estudiante, fenómeno que el software busca mitigar al fortalecer las bases matemáticas en niveles críticos.
API (Application Programming Interface): Interfaz de programación de aplicaciones. Conjunto de reglas y especificaciones que permiten que Dextech Math se comunique con servicios externos, como modelos de IA o bases de datos.


# Referencias

Referencia
Título
Ruta
Fecha
Autor
[Ref.1]
Álgebra
Libro físico
1941
Baldor, A.
[Ref.2]
Cálculo (7ª ed.)
Libro físico
2012
Stewart, J.
[Ref.3]
Cálculo vectorial
Libro físico
1995
Pita Ruiz, C.
[Ref.4]
Principles of Mathematical Analysis
Libro físico
1976
Rudin, W.
[Ref.5]
How to Solve It
Libro físico
1945
Pólya, G.
[Ref.6]
Adding It Up
Libro físico
2001
National Research Council
[Ref.7]
Mindset: The New Psychology of Success
Libro físico
2006
Dweck, C. S.
[Ref.8]
Khan Academy
https://www.khanacademy.org 
2025
Khan Academy
[Ref.9]
GeoGebra
https://www.geogebra.org 
2026
GeoGebra
[Ref.10]
MIT OpenCourseWare
https://ocw.mit.edu 
2026
MIT
[Ref.11]
Brillian
https://www.brilliant.org 
2025
Brilliant.org
[Ref.12]
ICMI
https://www.mathunion.org/icmi 
2025
ICMI







Resumen
El presente documento describe la especificación de requisitos de software (SRS) del proyecto Dextech Math, una aplicación diseñada para apoyar el aprendizaje y refuerzo de las matemáticas en estudiantes. Este proyecto surge a partir de las dificultades que muchos estudiantes presentan en esta área, así como la falta de herramientas que se adapten a su ritmo y forma de aprendizaje. El objetivo principal es definir de manera clara los requerimientos del sistema, proporcionando una base sólida para su desarrollo. La aplicación propone un entorno interactivo y personalizado, en el que el usuario pueda aprender de forma más dinámica, con apoyo de tecnologías actuales como los modelos de lenguaje (LLM), que permiten ofrecer explicaciones y acompañamiento según el nivel del estudiante. Además, el sistema se enfoca en mejorar la experiencia del usuario mediante un diseño intuitivo, accesible y motivador, buscando que el aprendizaje no se perciba como una obligación, sino como un proceso más amigable. En conjunto, este documento sirve como guía para el desarrollo de una solución tecnológica que contribuya a mejorar el rendimiento académico y fomente el aprendizaje autónomo en matemáticas.


Descripción general
Perspectiva del producto
El sistema Dextech Math es un producto de software independiente, diseñado como una aplicación educativa enfocada en el aprendizaje y refuerzo de las matemáticas. No forma parte directa de un sistema mayor, pero puede integrarse en el futuro con plataformas educativas, entornos virtuales de aprendizaje o servicios en la nube. El software se basa en una arquitectura moderna que incluye una interfaz de usuario interactiva, un sistema de gestión de contenidos educativos y la integración de modelos de lenguaje (LLM), los cuales permiten brindar asistencia personalizada en tiempo real. Además, el sistema puede interactuar con servicios externos como bases de datos, APIs de inteligencia artificial y herramientas de análisis de progreso.
En términos generales, el producto funciona como una plataforma autónoma que centraliza recursos educativos, seguimiento del usuario y apoyo inteligente, ofreciendo una experiencia de aprendizaje dinámica y adaptada a las necesidades de cada estudiante.


Funcionalidad del producto
El sistema Dextech Math contará con las siguientes funcionalidades principales:
Gestión de usuarios: Permite el registro e inicio de sesión, así como la creación de un perfil que almacena el progreso y preferencias del usuario.
Diagnóstico inicial: El sistema realiza una evaluación inicial para identificar el nivel de conocimiento del usuario y así adaptar los contenidos a sus necesidades.
Presentación de contenidos: Ofrece temas matemáticos organizados por niveles (básico, intermedio y avanzado), con explicaciones claras y estructuradas.
Ejercicios interactivos: Incluye actividades prácticas como problemas paso a paso, selección múltiple y ejercicios aplicados a situaciones reales.
Evaluaciones adaptativas: Permiten medir el rendimiento del usuario y ajustar automáticamente el nivel de dificultad según sus resultados.
Asistente virtual con IA: Brinda apoyo en tiempo real, resolviendo dudas, explicando procedimientos y guiando al usuario durante su aprendizaje.
Seguimiento del progreso: Muestra estadísticas, resultados y avances del usuario, facilitando la identificación de fortalezas y debilidades.
Recomendaciones personalizadas: Sugiere contenidos y ejercicios según el desempeño del usuario, reforzando los temas donde presenta mayor dificultad.
Interfaz interactiva: Presenta un diseño visual amigable, con elementos dinámicos que facilitan la navegación y mejoran la experiencia del usuario.
Motivación y gamificación: Integra elementos como logros, progreso visual y recompensas para incentivar la constancia en el aprendizaje.
.

Características de los usuarios

Tipo de usuario
Estudiantes de secundaria, primeros semestres de universidad o personas que quieran reforzar sus conocimientos en matemáticas.
Formación
Nivel básico, medio o universitario inicial, con bases en matemáticas pero con algunas dificultades o temas que no quedaron en el colegio claros.
Habilidades
Uso básico de computador o celular, saber navegar en aplicaciones y disposición para aprender por su cuenta.
Actividades
Estudiar, practicar los ejercicios que ofrezca la página, preguntar para resolver dudas, repasar los temas y hacer seguimiento al progreso del usuario en la materia.







Restricciones

Tecnológicas:
Conectividad: El sistema requiere una conexión a internet estable para interactuar con los modelos de lenguaje (LLM) y cargar recursos interactivos externos.
Consumo de API: El uso de modelos de IA estará limitado por las cuotas de tokens o costos asociados a las APIs utilizadas (ej. OpenAI, Anthropic o Gemini).
Metodológicas:
Marco de Trabajo: El desarrollo se regirá bajo el marco de trabajo Scrum, siguiendo sus ceremonias y entregables según la Scrum Guide 2020.
Legales y de Seguridad:
Privacidad: El manejo de datos de los usuarios debe cumplir con la Ley 1581 de 2012 (Protección de Datos Personales en Colombia).

Suposiciones y dependencias
Hardware del Usuario: Se asume que el usuario final dispone de un dispositivo (smartphone, tablet o PC) con capacidad suficiente para ejecutar un navegador web moderno sin degradación crítica del rendimiento.
Base de Conocimientos: Los requisitos se basan en la suposición de que los contenidos curriculares de matemáticas de educación media no sufrirán cambios drásticos por parte de los entes reguladores durante el desarrollo.

Evolución previsible del sistema
Internacionalización: Adaptación de los contenidos y del asistente virtual a múltiples idiomas (inglés, francés, portugués) para expandir el alcance a otros países.
Modo Offline: Desarrollo de una versión que permita descargar módulos de aprendizaje y ejercicios para ser resueltos sin conexión, sincronizando el progreso al detectar red.
Reconocimiento de Escritura: Implementación de una funcionalidad que permita a los usuarios resolver ejercicios a mano alzada en pantallas táctiles, utilizando IA para corregir el procedimiento directamente desde el trazo.
Analítica para Docentes: Creación de un panel de control para que profesores de instituciones educativas puedan seguir el progreso grupal e individual de sus estudiantes en tiempo real.

