# GUÍA BÁSICA DE MARKDOWN

## INDEX

[**1. ¿Qué es Markdown?**](#1-qué-es-markdown)  
[**2. ¿Qué es un archivo README?**](#2-qué-es-un-archivo-readme)  
[**3. Atajos más comunes**](#3-atajos-más-comunes)  
&emsp; [**TÍTULOS** (Headers)](#títulos-headers)  
&emsp; [**ITÁLICA (CURSIVA) y NEGRITA**](#itálica-cursiva-y-negrita)  
&emsp; [**CITAS RESALTADAS O DESTACADAS**](#citas-resaltadas-o-destacadas)  
&emsp; [**LISTAS**](#-34-listas)  
&emsp; [**CASILLAS DE VERIFICACIÓN** (checkbox)](#casillas-de-verificación-checkbox)  
&emsp; [**SALTO DE LÍNEA**](#salto-de-línea)   
&emsp; [**LÍNEA DE SEPARADOR**](#línea-de-separador)    

# 1. ¿Qué es Markdown?

Markdown **no es un lenguaje de programación**, sino un **lenguaje de marcado ligero**, lo que significa que se utiliza para dar formato y estructura a un texto plano de manera sencilla, utilizando símbolos y caracteres especiales. 

No ejecuta instrucciones ni realiza cálculos; simplemente describe cómo debe presentarse el texto visualmente. 

Es muy popular porque es fácil de aprender y usar, y se puede convertir fácilmente a otros formatos como HTML para su visualización en la web. 

Markdown posee un conjunto de **atajos para darle formato a tus textos**. En lugar de usar botones o menús, usas símbolos comunes como # para títulos, * para negrita o 
- para listas.
Por ejemplo, si a la palabra "ciberseguridad" le agragamos ** antes y despúes de la palabra, queda así: "**ciberseguridad**"

Es como escribir un mensaje de texto pero con superpoderes para que se vea estético y bien organizado.

# **2. ¿Qué es un archivo README?**

**Un archivo README en GitHub es la tarjeta de presentación de tu proyecto**. Es un documento esencial que proporciona una visión general, instrucciones de instalación y uso, y otra información clave para ayudar a los usuarios y colaboradores a entender y aprovechar tu proyecto. 

**Piensa en él como un manual de instrucciones y una invitación a participar en tus proyectos.** 

# **3. Atajos más comunes**

**NOTA:** Si queremos que el símbolo o caracter se muestre sin que sea visualizado como Markdown (sin que se aplique el estilo), podemos escapar al atajo anteponiendo \ , por ejemplo, \\# (aquí tuve que aplicar doble \\\ para que no aplique el estilo)

## **TÍTULOS** (Headers)

Para escribir Títulos (Headers) se antepone de 1 a 6 almohadillas (hash) # dependiendo de la jerarquía que tenga el texto que queremos estilizar.</br>
El elemento de mayor jerarquía será el que tengan menos # 

\# Título de nivel 1 
# Título de nivel 1 

\## Subtítulo de nivel 2 
## Subtítulo de nivel 2 

\### Título de nivel 3 
### Título de nivel 3

\#### Título de nievel 4
#### Título de nievel 4

\##### Título de nivel 5
##### Título de nivel 5 

## **ITÁLICA (CURSIVA) y NEGRITA**

**Itálicas:** Asterisco * o un guion bajo _ antes y después de lo que queremos estilizar.</br>
**Negritas:** Doble asterisco ** o doble guión bajo __ antes y después de lo que queremos estilizar.

## **CITAS RESALTADAS O DESTACADAS**

Anteponer \> al inicio de la cita

>**"The quieter you become the more you are able to hear" - Kali Linux**

## **LISTAS**

Puedes hacer una lista de elementos usando \* o los numerales seguidos de . , es decir, \1. \2. etc.

**Ejemplo1:**

### **Los 4 principales sistemas operativos usados para hacer pentesting son:**

* **Kali Linux:** Es el sistema operativo más conocido y utilizado para pentesting. Basado en Debian, viene con una amplia gama de herramientas de seguridad preinstaladas y se actualiza regularmente. Su interfaz es amigable y personalizable, lo que lo hace adecuado tanto para principiantes como para profesionales.

* **Parrot Security OS:** También basado en Debian, Parrot OS se enfoca en la privacidad y el anonimato, además de ofrecer herramientas para pentesting. Es una buena opción si te preocupa la seguridad de tus propias actividades mientras realizas pruebas de penetración.

* **BlackArch Linux:** Basado en Arch Linux, BlackArch es conocido por su enorme colección de herramientas de seguridad, que supera las 2000. Es una opción ideal para usuarios avanzados que necesitan una amplia variedad de herramientas a su disposición.

* **BackBox Linux:** Basado en Ubuntu, BackBox Linux ofrece un entorno de pentesting completo y fácil de usar. Su enfoque en la simplicidad y la estabilidad lo convierte en una buena opción para aquellos que buscan una experiencia de pentesting sin complicaciones.

**Ejemplo2:**

### **Algunas de las principales revistas de hacking son:**

**1. Phrack Magazine:** Una de las publicaciones más antiguas y respetadas en la comunidad hacker, conocida por sus artículos técnicos profundos y su enfoque en la exploración y el aprendizaje. **LINK:** http://www.phrack.org/

**2. 2600: The Hacker Quarterly:** Una revista impresa trimestral que cubre una amplia gama de temas relacionados con la tecnología, el hacking y la cultura hacker.
Hakin9: Una revista que ofrece tutoriales, artículos técnicos y noticias sobre seguridad informática y hacking ético. **LINK:** https://www.2600.com/

**3. PenTest Magazine:** Una revista enfocada en pruebas de penetración y hacking ético, con artículos técnicos y entrevistas a expertos en seguridad. **LINK:** https://pentestmag.com/

## **CASILLAS DE VERIFICACIÓN** (checkbox)

Podemos hacer listas con **casillas de verificación** (checkbox) como las típicas listas **to-do** para marcar cosas que debemos hacer.</br>
Para la casilla se usa la siguiente sintaxis:</br>
\- [ ] Casilla no marcada</br>
\- [x] Casilla marcada</br>

## Lista de Chequeo para Respuesta a Incidentes de Malware (Blue Team)
- [x] **1. Identificación y Aislamiento:**

- [x]  **Confirmar la alerta:** Verificar la legitimidad de la alerta de posible intrusión de malware.
- [x]  **Aislar el sistema afectado:** Desconectar el sistema de la red para prevenir la propagación del malware.
- [x] **Identificar el tipo de malware:** Utilizar herramientas de análisis para determinar el tipo y comportamiento del malware.
- [x]  **Evaluar el alcance del impacto:** Determinar qué sistemas y datos pueden haber sido afectados.

**2. Contención y Erradicación:**

- [ ] **Detener el proceso malicioso:** Terminar los procesos asociados al malware.
- [ ] **Eliminar el malware:** Utilizar herramientas de eliminación de malware para limpiar el sistema.
- [ ] **Aplicar parches y actualizaciones:** Asegurarse de que el sistema esté actualizado para prevenir futuras infecciones.
- [ ] **Restablecer contraseñas:** Cambiar las contraseñas de cuentas potencialmente comprometidas.

**3. Recuperación y Análisis:**

- [ ] **Restaurar datos desde backups:** Recuperar datos limpios desde copias de seguridad.
- [ ] **Monitorear el sistema:** Vigilar el sistema en busca de actividad sospechosa después de la limpieza.
- [ ] **Analizar el incidente:** Realizar un análisis forense para entender cómo ocurrió la infección y prevenir futuros ataques.
- [ ] **Documentar el incidente:** Registrar todos los detalles del incidente para futuras referencias y mejoras en la seguridad.

**4. Comunicación y Mejora Continua:**

- [ ] **Informar a las partes interesadas:** Comunicar el incidente a los equipos relevantes y a la gerencia.
- [ ] **Actualizar políticas y procedimientos:** Revisar y mejorar las políticas de seguridad y los procedimientos de respuesta a incidentes.
- [ ] **Capacitar al personal:** Educar a los usuarios sobre cómo identificar y evitar amenazas de malware.
- [ ] **Realizar pruebas de penetración:** Evaluar regularmente la seguridad de la red para identificar vulnerabilidades.

**Consideraciones Adicionales:**

- [ ] **Mantener herramientas actualizadas:** Asegurarse de que las herramientas de seguridad y antivirus estén al día.
- [ ] **Utilizar múltiples capas de seguridad:** Implementar firewalls, sistemas de detección de intrusos y otras medidas de seguridad para proteger la red.
- [ ] **Tener un plan de respuesta a incidentes:** Preparar un plan detallado para responder a incidentes de seguridad de manera efectiva.

**Recuerda:** La respuesta a incidentes de malware requiere una acción rápida y coordinada. Sigue esta lista de chequeo para minimizar el impacto y recuperarte de la intrusión de manera efectiva. 

## **SALTO DE LÍNEA** 

Establecer un salto de línea, es decir, después del final de una línea de texto empezar una nueva más abajo.

**Opción 1:** Simplemente añade dos espacios al final de la línea donde quieres que ocurra el salto.  
**Opción 2:** Usar la etiqueta HTML \</br> al final de la línea (ej. salto de línea\</br>) para insertar un salto de línea.

## **LÍNEA DE SEPARADOR** 

Podemos usar una línea para separar un párrafo o una sección de otra, usando 3 guiones seguidos (\---) entre un párrafo y otro.

**Uso:** 
Párrafo 1  
\---  
Párrafo 2  

**Ejemplo:**

### Reseñas de libros: Adéntrate en el mundo del hacking ético

**1. "Ethical Hacking"** de **Pablo González Pérez** (Editorial 0xword): En el presente libro puedes encontrar procedimientos, procesos, vectores de ataque, técnicas de hacking, teoría y práctica de este arte.
El libro propone un enfoque distinto a lo común, en el cual se guiará al lector por un conjunto de pruebas a realizar en auditorías técnicas. La auditoría perimetral y auditoría interna son el foco común en este tipo de procesos. Además, se añaden pruebas modernas no tan comunes en los procesos de hacking ético. Los famosos APT, las pruebas de DDoS o las simulaciones de fugas de información desde dentro de la organización son algunos de los ejemplos que podrás encontrar en el libro.

---

**2. "The Hacker Playbook: Practical Guide To Penetration Testing"** de **Peter Kim**: Al igual que un atleta profesional no se presenta sin un plan de juego sólido, los hackers éticos, profesionales de TI e investigadores de seguridad tampoco deberían estar desprevenidos. **The Hacker Playbook** les proporciona sus propios planes de juego. Escrito por un experimentado profesional de seguridad y CEO de Secure Planet, LLC, esta guía paso a paso sobre el "juego" del hacking de penetración incluye ejemplos prácticos y consejos útiles de los mejores expertos del campo. A través de una serie de "jugadas" al estilo del fútbol americano, esta guía directa aborda muchos de los obstáculos que las personas pueden enfrentar al realizar pruebas de penetración, incluidos los ataques a diferentes tipos de redes, pivotar a través de controles de seguridad y evadir software antivirus.

## **Agregar una Imagen**

Usa la siguiente secuencia: \![Titulo de la imagen]\(url_de_la_imagen)

Esto se vería así:
#### Richard Stallman: Padre del Software Libre  
![Richard Stallman](https://www.muylinux.com/wp-content/uploads/2013/06/rms.jpg)


## **Tabulación o Espacios antes de una línea**

Si queremos anteponer una tabulación o espacios antes de una línea usamos:

* nbsp para agregar un solo espacio.
* ensp para agregar 2 espacios.
* emsp para agregar 4 espacios.

Puedes utilizar espacios indivisibles (nbsp) 4 veces para insertar una tabulación.
Añade & al principio y ; al final la sintaxis de espacio sugerida anteriormente.

**Uso:** \&emsp; 

**Ejemplo:**

**"El hacking ético es una forma de arte y de pensamiento crítico. Aprende a ver más allá de lo evidente y encontrarás las soluciones.** - **Kevin Mitnick**
</br>
&emsp; **"La humildad es esencial en el mundo de la seguridad. Nunca te creas invencible, siempre hay algo nuevo por aprender".** - **Kevin Mitnick**  

¡Gracias al colaborador Muhammad Tariq por este dato!

## **Cambiar el color del texto**

Podemos usar la siguiente línea de atajos quitando las comillas del inicio y final: "$\color{green}{\text{AQUÍ VA TU TEXTO}}$"

**Y esto se ve así:** $\color{green}{\text{AQUÍ VA TU TEXTO}}$

**Colores:**
* green $\color{green}{\text{green}}$  
* blue $\color{blue}{\text{azul}}$  
* red $\color{red}{\text{rojo}}$  
* black $\color{black}{\text{negro}}$  
* pink $\color{pink}{\text{rosa}}$  
* orange $\color{orange}{\text{naranjo}}$  

Prueba otros colores...

🙃 ## **Sí, también puedes usar Emojis**

Para usar emojis simplemente escribes : y luego la inicial o código completo del smiley.  
Puedes encontrar un listado muy completo de emojis para Markdown aquí: https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

# Para experimentar...

**Automizar escritura de documentos técnicos con Markdown:** jsdoc-to-markdown es una herramienta de línea de comandos y una biblioteca de Node.js que te permite generar automáticamente documentación en formato Markdown a partir de los comentarios JSDoc en tu código JavaScript.  es una herramienta de Node.js, lo que significa que se puede instalar y utilizar tanto en Windows como en Linux, siempre y cuando tengas Node.js y npm (Node Package Manager) instalados en tu sistema.

El proceso de instalación es el mismo en ambos sistemas operativos:  
* Instalar Node.js y npm: Si aún no los tienes, descárgalos e instálalos desde el sitio web oficial de Node.js: https://nodejs.org/
* Instalar jsdoc-to-markdown: Una vez que tengas Node.js y npm, abre tu terminal o línea de comandos y ejecuta el siguiente comando: npm install -g jsdoc-to-markdown 

