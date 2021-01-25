# Apunts_UF1_1

**Ingeniería de software:** Disciplina que estudia los principios y metodologías para el desarrollo y mantenimiento de sistemas software.

**Desarrollo de software**
+ **Análisis:** Se determina y define claramente las necesidades del cliente y se especifica los requisitos que debe cumplir el software a desarrollar.
+ **Diseño:** Se descompone y organiza el sistema en elementos componentes que pueden ser desarrollados por separado. También se especifica la interrelación y funcionalidad de los elementos componentes.
+ **Codificación:** Se escribe el código fuente de cada componente.
+ **Pruebas:** El principal objetivo de las pruebas debe ser conseguir que el programa funcione incorrectamente y que se descubran defectos.
+ **Mantenimiento:** Durante la explotación del sistema software es necesario realizar cambios ocasionales.
**Tipos de mantenimiento:**
    + Correctivo: se corrigen defectos.
    + Perfectivo: se mejora la funcionalidad.
    + Evolutivo: se añade funcionalidades nuevas.
    + Adaptativo: se adapta a nuevos entornos.

**Modelos de desarrollo de software**
+ **Modelos clásicos (predictivos)**
    + **Modelo en cascada:** Modelo de mayor antigüedad, identifica las fases principales del desarrollo software. Las fases han de realizarse en el orden indicado y el resultado de una fase es la entrada de la siguiente fase. Es un modelo bastante rígido que se adapta mal al cambio continuo de especificaciones.
    + **Modelo en V:** Modelo muy parecido al modelo en cascada, tiene una visión jerarquizada con distintos niveles, los niveles superiores indican mayor abstracción y los niveles inferiores indican mayor nivel de detalle. El resultado de una fase es la entrada de la siguiente fase.
+ **Modelo de construcción de prototipos:** Se crea un prototipo durante la fase de análisis y es probado por el usuario/cliente para refinar los requisitos del software a desarrollar y se repite el paso anterior las veces necesarias.
    + **Prototipos rápidos:** El prototipo puede estar desarrollado usando otro lenguaje o herramientas. Finalmente el prototipo se desecha.
    + **Prototipos evolutivos:** El prototipo está diseñado en el mismo lenguaje y herramientas del proyecto. El prototipo se usa como base para desarrollar el proyecto.
+ **Modelos evolutivos o incrementales**
    + **Modelo en espiral (iterativos):** En la actividad de ingeniería corresponde a las fases de los modelos clásicos: análisis, diseño, codificación, etc. En la actividad de ingeniería se da gran importancia a la reutilización de código.
    + **Metodologías ágiles (adaptativos):** Son métodos de ingeniería del software basados en el desarrollo iterativo e incremental. Los requisitos y soluciones evolucionan con el tiempo según la necesidad del proyecto. El trabajo es realizado mediante la colaboración de equipos auto-organizados y multidisciplinarios, inmersos en un proceso compartido de toma de decisiones a corto plazo. Las metodologías más conocidas son:
        + **Kanban:** Controla por demanda la fabricación de los productos necesarios en la cantidad y tiempo necesarios. Enfocado a entregar el máximo valor para los clientes, utilizando los recursos justos.
        + **Scrum:** Iteraciones (sprint) regulares cada 2, 3 o 4 semanas. Al principio de cada iteración se establecen sus objetivos priorizados (sprint backlog). Al finalizar cada iteración se obtiene una entrega parcial utilizable por el cliente. Existen reuniones diarias para tratar la marcha del sprint.
        + **XP (eXtreme Programming):** Diseño sencillo, pequeñas mejoras continuas, pruebas y refactorización, integración continua, programación por parejas, el cliente se integra en el equipo de desarrollo, propiedad del código compartida, estándares de codificación y de 40 horas semanales.

**Obtención de código ejecutable**
+ **Compilar:** Es transforma el código fuente de un programa a su equivalente en otro lenguaje de programación de más bajo nivel
+ **Interpretar:** es ejecutar directamente las instrucciones escritas en un lenguaje de programación dado.

**Java:** Lenguajes compilado e interpretado. El código fuente Java se compila y se obtiene un código binario intermedio denominado bytecode. Puede considerarse código objeto pero destinado a la máquina virtual de Java en lugar de código objeto nativo.
Después este bytecode se interpreta para ejecutarlo.

**Tipos de lenguaje**
+ **Declarativos:** Indicamos el resultado a obtener sin especificar los pasos.
+ **Imperativos:** indicamos los pasos a seguir para obtener un resultado.

**Tipos de lenguajes según nivel de abstracción**
+ **Bajo nivel:** Ensamblador.
+ **Medio nivel:** C.
+ **Alto nivel:** C++, Java.

**Evolución de los lenguajes**
+ Código binario.
+ Ensamblador.
+ Lenguajes estructurados.
+ Lenguajes orientados a objetos.

**Criterios para selección de lenguaje de programación**
+ Campo de aplicación
+ Experiencia previa
+ Herramientas de desarrollo
+ Documentación disponible
+ Base de usuarios
+ Reusabilidad
+ Portabilidad
+ Imposición del cliente
