<h1>Capítulo V: Product Implementation, Validation & Deployment</h1>
<h3>5.1. Software Configuration Management</h3>
A continuación, se presentará un repositorio central y organizado que servirá como guía para el desarrollo enfocado y consistente de nuestra solución.
<h3>5.1.1. Software Development Environment Configuration</h3>
En esta sección se incluye los links de las aplicaciones, productos de software realizadas durante el ciclo del proyecto en los programas que se utilizaron. 
Para ello se clasificará en las siguientes secciones:
<br><br>
<strong>Requirements Management</strong><br>
Es el proceso de garantizar que una organización documente verifique y satisfaga las necesidades, expectativas de sus clientes con las partes interesadas internas o externas.<br><br>
<ul>
<li><strong>Pivotal Tracker</strong>: Esta herramienta se define como una plataforma en la que se realiza la gestión de user stories, agrupándoles en epics y clasificando su presencia en el programa, por puntaje. Se usó porque permite que cada miembro del equipo comparte la misma vista en tiempo real de lo que está sucediendo con cada proyecto, ya sea aportando con diferentes secciones o corrigiendo el flujo del proyecto. https://www.pivotaltracker.com/n/projects/2603049
</li>
</ul>

<strong>Product UX/UI Design</strong>

<ul>
<li><strong>Uxpressia:</strong> es una herramienta en línea para el mapeo de la trayectoria del cliente que crea mapas de impacto y personas. Sus herramientas nos permitieron establecer las bases del modelado de User Persona, Empathy Map y Journey Map.<br>
https://uxpressia.com/

</li>
<li><strong>Figma:</strong> es una pizarra digital colaborativa en línea, que puede ser usada para la investigación, la ideación, la creación de lluvias de ideas, mapas mentales y una variedad de otras actividades colaborativas.<br>https://www.figma.com/design/ 
</li>
<li><strong>Structurizr:</strong> es una herramienta de diseño que soporta el modelo C4, para visualizar la arquitectura de software de nuestra solución. <br>https://structurizr.com/  
</li>
<li><strong>Lucid Chart:</strong> es una herramienta de diagramación basada en la web, que permite a los usuarios colaborar y trabajar juntos en tiempo real, creando diseños UML, mapas mentales, prototipos de software y muchos otros tipos de diagrama. <br>https://lucid.app/documents#/dashboard 
</li>
<li><strong>MIRO:</strong> es una pizarra digital colaborativa en línea, que puede ser usada para la investigación, la ideación, la creación de lluvias de ideas, mapas mentales y una variedad de otras actividades colaborativas. <br>https://miro.com/app/dashboard/ 
</li>
</ul>
<br>
<strong>Software Development</strong><br>
Es una estructura aplicada al desarrollo de un producto de software. Se utiliza para el establecimiento de un proceso para el desarrollo de software, cada uno de los cuales describe un enfoque diferente para diferentes actividades que tienen lugar durante el proceso.<br>
<ul>

<li><strong>Github:</strong> Es un repositorio comunitario cuya función es almacenar los avances de un proyecto elaborado por un grupo de personas. <br>
https://github.com/TechOps-upc
</li>

<li>
<strong>Web Storm:</strong> Es un entorno de JetBrains, empresa desarrolladora de Software, orientado en el desarrollo web en JavaScript. Este nos ofrece facilidad en probar nuestro entorno web en navegadores como Google. Para el proyecto se implementará la ayuda de los lenguajes HTML, CSS , JavaScript y TypeScript.<br>
https://www.jetbrains.com/webstorm/promo/?source=google&medium=cpc&campaign=9641686239&term=webstorm&gclid=CjwKCAjwv-GUBhAzEiwASUMm4ncU-aP3HPxUWVYTPMthApgSMowOvvfEAoJMFvwf1O_gQdv0HtWOrhoCdacQAvD_BwE
</li>

<li>
<strong>Visual Studio Code:</strong> Es un editor potente que brinda extensiones que nos permiten personalizar y agregar funcionalidades para que la función del desarrollador sea más eficiente. Asimismo, se empleará para poder construir el backend de nuestro web Applications.<br>
https://code.visualstudio.com/ 
</li>

<li>
<strong>HTML:</strong> Es un lenguaje que sirve como desarrollador de plataformas web que trabaja con hipertextos, que enlace a otros documentos. Este lenguaje ofrece herramientas para el diseño del sitio web. Asimismo, la disponibilidad de trabajar HTML junto con CSS y JavaScript. Este lenguaje será utilizado en el presente proyecto para implementar la documentación de la página web. <br>https://www.jetbrains.com/help/webstorm/editing-html-files.html 
</li>

<li>
<strong>CSS:</strong> Es un lenguaje de diseño para el entorno web. Permite elaborar el interfaz de usuario diseñada anteriormente, agregando colores, tamaños entre otros elementos. Además, se puede diseñar un estilo en CSS y compartirlo en el web elaborado en HTML. Este lenguaje se utilizará para la implementación del diseño de nuestra plataforma web.<br>
https://www.jetbrains.com/help/webstorm/style-sheets.html#ws_css_completion 
</li>
</ul>
<strong>Software Deployment</strong>
<ul>
<li>
<strong>Github pages:</strong>Servicio de Github que nos permitió alojar nuestra lading page y nos permitirá alojar nuestro web applications.<br>
https://pages.github.com/<br> 
https://github.com/ 
</li>
</ul>

<h3><a id="source-code-management">5.1.2. Source Code Management</a></h3>
A continuación, se presenta la gestión de código fuente o como es conocido por sus siglas en ingles SCM (Source Code Management). Su función principal es realizar un seguimiento de las modificaciones que el equipo realizara a lo largo del desarrollo de sus proyectos en los repositorios de código fuente. Se empleará como un sistema de control de versiones que permite dar seguimiento a los cambios que cada integrante o desarrollador realice en el proyecto. Asimismo, cabe resaltar que para el sistema de control de versiones emplearemos GitHub.
<ul>
<li>
<strong>URL de la Organización:</strong> https://github.com/TechOps-upc
</li>
<li><strong>URL del Repositorio del Landing Page:</strong>https://diegoacuna1612.github.io/diegoAcuna1612land.github.io/public/index.html</li>
</ul>
<strong>GitFlow</strong>
El enfoque de desarrollo de ramas en Git que ha ganado una gran importancia en los últimos años es un método alternativo que muchos desarrolladores consideran esencial. Este flujo de trabajo de control de versiones, que se basa en el uso de ramas, fue introducido y promovido por Vincent Driessen. Su propósito principal es facilitar la gestión y organización de las diferentes versiones de un código, permitiendo la creación ordenada de nuevas características (features) y correcciones urgentes (hotfixes).
<br><br>
<p align ="center">
   <img src="./static/source-code-management-images/gitflow-image.png" >
</p>
Como se mencionó anteriormente, GitFlow trabaja con branches o ramas. A continuación, se muestran las ramas que se emplearan en el flujo de trabajo de nuestro proyecto.<br><br>

<strong>Main Branches</strong>

<ul>
<li><strong>main:</strong> es la rama principal, a partir de ella se recorrerán todas las ramas y contendrá la última versión y las anteriores creadas por los desarrolladores. Almacenara el historial de publicación oficial.
</li>
<li><strong>develop:</strong> Esta rama puede ser creada a partir de la master Branch, contara con todos los Features estables. Esto significa que a través de esta rama el equipo podrá integrar las funciones.</li>
</ul>
 
<strong>Support Branches</strong><br>
A diferencia de las ramas principales, estas branches tienen un tiempo de vida limitado, ya que se eliminar al realizar el merge con sus ramas primarias.<br>
<ul>
<li>
   <strong>Feature:</strong>
      <ul>
      <li>Se ramifica de: develop</li>
      <li>Debe fusionarse de nuevo en: develop</li>
      </ul>
   Se emplean para desarrollar las nuevas funciones que se integraran en una versión siguiente. Cabe resaltar, que esta rama existe mientras este en proceso de desarrollo. Sin embargo, cuando el desarrollador culmine con esa función, se fusionará nuevamente a develop. 
</li>
<br><br>
<p align ="center">
   <img src="./static/source-code-management-images//giflow-feature-image.png" >
</p>
<li>
   <strong>Release:</strong>
      <ul>
      <li>Se ramifica de: develop</li>
      <li>Debe fusionarse de nuevo en: develop / master</li>
      </ul>
      Son aquellas que admiten la preparación de una nueva versión de producción. A través de esta rama, se permite corregir errores menores que surgieron en la etapa de desarrollo y preparar metadatos para su lanzamiento. Esto último genera que la develop Branch se autoriza para recibir nuevas funciones para la próxima versión, pues se generara cuando se acerque una fecha de publicación determinada. 
</li>
<br>
<p align ="center">
   <img src="./static/source-code-management-images/gitflow-release.png" >
</p>
</ul>

<strong>Principales motivos para usar Gitflow</strong>
<br><br>
Este flujo de trabajo es ideal para el equipo, puesto que nuestro proyecto se basa en publicaciones en un determinado sprint.
<br><br>
Esta centralizado como subversión (SVN) y descentralizado, que permite que el equipo trabaje individualmente. Pues no todos tienen el mismo horario. Sin embargo, todos deben mantener las actualizaciones en el repositorio central en GitHub.

<h3>5.1.3. Source Code Style Guide & Conventions</h3>
En esta sección, se presentarán las directrices, estándares, estilos y principios que se aplicarán a cada uno de los lenguajes utilizados en el desarrollo de nuestra aplicación, Nourishify. La adopción de este conjunto de normas es fundamental, ya que tienen como objetivo mantener la calidad estructural del software, mejorar la legibilidad del código fuente y simplificar el proceso de mantenimiento del código.
<br><br>
Dado que en este proyecto se utilizarán HTML, CSS, JavaScript para la codificación de la plataforma web y Gherkin para el proceso de prueba del programa, a continuación, se enumerarán y explicarán las reglas y recomendaciones generales que se seguirán al trabajar con estos lenguajes:
<br><br>
<div class=WordSection1>

<p class=MsoListParagraphCxSpFirst style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><b><span>Nomenclatura
General<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>A los nombres de las variables, objetos, elementos y
funciones que se utilicen, se les designarán términos en inglés que estén
relacionados y puedan describir a lo que están representando. No se usarán
mayúsculas porque de acuerdo con W3Schools (s.f.), la mezcla de estas con las
letras minúsculas luce mal y, además, el uso exclusivo de minúsculas otorga
mayor legibilidad al código.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Ejemplo de nomenclatura estándar según Google (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto'><span
class=GramE><span class=tagcolor><span style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;mso-ansi-language:ES-PE'>.</span></span><span
class=SpellE><span class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown;mso-ansi-language:ES-PE'>gallery</span></span></span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'> </span></span><span class=tagcolor><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;mso-ansi-language:
ES-PE'>{}<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto'><span
class=GramE><span class=tagcolor><span style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;mso-ansi-language:ES-PE'>.</span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'>video</span></span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'> </span></span><span class=tagcolor><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;mso-ansi-language:
ES-PE'>{}<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto'><span
class=tagcolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:mediumblue;mso-ansi-language:ES-PE'>.</span></span><span class=SpellE><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'>login</span></span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'> </span></span><span class=tagcolor><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;mso-ansi-language:
ES-PE'>{}<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><b><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><b><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Sangría<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>En el momento de utilizar HTML, CSS y/o JavaScript se
aplicará un espaciado antes de cada línea que se encuentre dentro de un bloque.
Este espacio debe ser de dos y según W3Schools (s.f.) no se debe hacer uso de
la tecla “Tabulación”.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Ejemplo de nomenclatura estándar de la sangría en HTML
según W3Schools (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span class=tagcolor><span style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>table</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&lt;</span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>tr</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;&nbsp;&nbsp;</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=SpellE><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>th</span></span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>Name</span><span class=tagcolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&lt;</span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>/<span class=SpellE>th</span></span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;&nbsp;&nbsp;</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=SpellE><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>th</span></span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>Description</span><span class=tagcolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&lt;</span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>/<span class=SpellE>th</span></span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'><span style='mso-spacerun:yes'>  </span></span></span><span
class=tagcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;
color:mediumblue;mso-ansi-language:ES'>&lt;</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'>/<span class=SpellE>tr</span></span></span><span
class=tagcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;
color:mediumblue;mso-ansi-language:ES'>&gt;</span></span><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;mso-ansi-language:
ES'><br>
</span><span class=tagcolor><span lang=ES style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;mso-ansi-language:ES'>&lt;</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'>/table</span></span><span
class=tagcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;
color:mediumblue;mso-ansi-language:ES'>&gt;<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=tagcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;
color:mediumblue;mso-ansi-language:ES'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Ejemplo de nomenclatura estándar de la sangría en CSS
según W3Schools (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span class=tagcolor><span style='mso-bidi-font-size:14.0pt;
line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=SpellE><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'>html</span></span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'> </span></span><span class=tagcolor><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;mso-ansi-language:
ES-PE'>{</span></span><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:black;mso-ansi-language:ES-PE'><br>
<span style='background:white'>&nbsp;&nbsp;<span class=SpellE>background</span></span></span><span
class=tagcolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:mediumblue;mso-ansi-language:ES-PE'>: </span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'>#fff;</span></span><span style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;mso-ansi-language:ES-PE'><br>
<span style='background:white'>&nbsp;&nbsp;color</span></span><span
class=tagcolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:mediumblue;mso-ansi-language:ES-PE'>: </span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:brown;mso-ansi-language:ES-PE'>#404;</span></span><span style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;mso-ansi-language:ES-PE'><br>
</span><span class=tagcolor><span style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue;mso-ansi-language:ES-PE'>}<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagcolor><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;mso-ansi-language:
ES-PE'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Ejemplo de nomenclatura estándar de la sangría en
JavaScript según W3Schools (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagcolor><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;mso-ansi-language:
ES-PE'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=jskeywordcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;
background:white'>function</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>&nbsp;<span class=SpellE>toCelsius</span>(<span
class=SpellE>fahrenheit</span>) {</span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;</span></span><span
class=jskeywordcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;background:white'>return</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>&nbsp;(</span><span class=jsnumbercolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:red;background:white'>5</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>&nbsp;/&nbsp;</span><span class=jsnumbercolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:red;
background:white'>9</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>) * (<span class=SpellE>fahrenheit</span>
-&nbsp;</span><span class=jsnumbercolor><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:red;background:white'>32</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>);</span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:black'><br>
<span style='background:white'>}</span></span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:0cm;mso-add-space:auto'><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span >Seguidamente, explicaremos las reglas específicas que
se necesitan en cada lenguaje para entender el código de nuestro programa, <span
class=SpellE>Nourishify</span>.<span style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpFirst style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><b><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>HTML<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Llamado así por las siglas del nombre en inglés <span
class=SpellE>HyperText</span> <span class=SpellE>Markup</span> <span
class=SpellE>Language</span>. HTML es un lenguaje de marcado que define la
estructura de una página web. Además, cuenta con funciones capaces de
determinar el comportamiento de distintas partes del contenido de la página,
tales como el cambiar el tamaño del texto, aplicar cursiva, entre otros. Nosotros
emplearemos HTML5, y las características y pautas a seguir para hacer uso de
este lenguaje son las siguientes:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Declare Document Type</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>El
tipo de documento debe declararse en la primera línea de código. De acuerdo con
Google (s.f.) HTML5 es de preferencia la mejor sintaxis para todo documento
HTML, para declararla sólo es necesario copiar lo siguiente:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue;background:white'>&lt;</span></span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;background:white'>!DOCTYPE</span><span
class=attributecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:red;background:white'>&nbsp;html</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue;background:white'>&gt;</span></span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'> </span><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Blank Lines </span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Cada
vez que, luego de un bloque, lista o tabla de gran longitud se inicie uno
nuevo, se debe saltar la siguiente línea y dejarla en blanco para brindar mayor
legibilidad y amenidad, así manifiesta W3Schools (s.f.).<span
style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=SpellE><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%'>Ejemplo</span></span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%'>:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagcolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&lt;</span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>body</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>h1</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>Famous Cities</span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>/h1</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>h2</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>Tokyo</span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>/h2</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>p</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>Tokyo is the capital of
Japan, the center of the Greater Tokyo Area, and the most populous metropolitan
area in the <span class=GramE>world.<span class=tagcolor><span
style='color:mediumblue'>&lt;</span></span></span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>/p</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>h2</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>London</span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>/h2</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>p</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>London is the capital
city of England. It is the most populous city in the United <span class=GramE>Kingdom.<span
class=tagcolor><span style='color:mediumblue'>&lt;</span></span></span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>/p</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>h2</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>Paris</span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>/h2</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>p</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>Paris is the capital of
France. The Paris area is one of the largest population centers in <span
class=GramE>Europe.<span class=tagcolor><span style='color:mediumblue'>&lt;</span></span></span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>/p</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>/body</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:mediumblue'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Quote Attribute Values</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Para
los valores de los atributos se utilizan comillas dobles alrededor. De acuerdo
con W3Schools (s.f.) Aunque esta característica no sea obligatoria, le da más
legibilidad al código y es muy frecuente entre los desarrolladores.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;
margin-left:34.9pt;line-height:normal;background:white'><span style='mso-bidi-font-size:
14.0pt;mso-ansi-language:ES-PE'>Ejemplo:<br>
</span><span lang=ES style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:"Times New Roman";color:mediumblue;
mso-ansi-language:ES;mso-fareast-language:ES'>&lt;</span><span lang=ES
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:"Times New Roman";
mso-bidi-font-family:"Times New Roman";color:brown;mso-ansi-language:ES;
mso-fareast-language:ES'>table</span><span lang=ES style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
color:red;mso-ansi-language:ES;mso-fareast-language:ES'>&nbsp;<span
class=SpellE>class</span></span><span lang=ES style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
color:mediumblue;mso-ansi-language:ES;mso-fareast-language:ES'>=&quot;<span
class=SpellE>striped</span>&quot;&gt;<o:p></o:p></span></p>

<span lang=ES style='font-size:14.0pt;line-height:115%;font-family:"Zizou Slab Light";
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
color:mediumblue;mso-ansi-language:ES;mso-fareast-language:ES;mso-bidi-language:
AR-SA'><br clear=all style='mso-special-character:line-break;page-break-before:
always'>
</span>

<p class=MsoNormal><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
color:mediumblue;mso-ansi-language:ES;mso-fareast-language:ES'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpFirst style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Multimedia Fallback</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Asegurar
un acceso alterno a los objetos multimedia por si este fallara al cargar. De la
misma forma, según la W3Schools (s.f.), es recomendable añadir las dimensiones
del elemento porque así los navegadores guardan el espacio que utilizará antes
de comenzar a cargarlo.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=SpellE><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%'>Ejemplo</span></span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%'>:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue;background:white'>&lt;</span></span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;background:white'>img</span><span
class=attributecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:red;background:white'>&nbsp;src</span></span><span
class=attributevaluecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;background:white'>=&quot;html5.gif&quot;</span></span><span
class=attributecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:red;background:white'>&nbsp;alt</span></span><span
class=attributevaluecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;background:white'>=&quot;HTML5&quot;</span></span><span
class=attributecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:red;background:white'>&nbsp;style</span></span><span
class=attributevaluecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;background:white'>=&quot;width:128<span
class=GramE>px;height</span>:128px&quot;</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;
background:white'>&gt;<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Never Skip the &lt;tittle&gt; Element</span></b><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>El
elemento &lt;<span class=SpellE>tittle</span>&gt; permite que las páginas
aparezcan en la lista de resultados al momento de buscar en un navegador web.
Asimismo, esta es la que da el nombre de la página si se la añade a favoritos.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=SpellE><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%'>Ejemplo</span></span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%'>:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>title</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>HTML Style Guide and
Coding Conventions</span><span class=tagcolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&lt;</span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>/title</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>HTML Line-Wrapping</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>El
hecho de que en un documento HTML no haya un límite de palabras por línea, no
quiere decir que sea recomendable generar líneas muy extensas de código. Al
contrario, esto dificulta la lectura del código. Para pasar a la siguiente
línea es necesario utilizar al menos cuatro espacios para diferenciar de
elementos hijos.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo
según Google (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>button</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'> </span><span class=attributecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:red'>mat-icon-button
color</span></span><span class=attributevaluecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;background:
white'>=&quot;</span></span><span class=attributevaluecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>primary&quot;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'> </span><span class=attributecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:red'>class</span></span><span
class=attributevaluecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>=&quot;menu-button&quot;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'><span style='mso-spacerun:yes'>    </span></span><span
class=attributecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:red'>(click)</span></span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;background:white'>=</span><span
class=attributevaluecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'> &quot;<span class=SpellE><span class=GramE>openMenu</span></span><span
class=GramE>(</span>)&quot;</span></span><span class=attributevaluecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'><span style='mso-spacerun:yes'>  </span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>mat-icon</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>&gt;menu</span><span class=attributevaluecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&lt;/</span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>mat-icon</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'>&gt;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='text-align:justify'><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&lt;/</span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>button</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>&gt;<o:p></o:p></span></span></p>

<span lang=EN-US style='font-size:14.0pt;line-height:115%;font-family:"Zizou Slab Light";
mso-fareast-font-family:"Times New Roman";mso-fareast-theme-font:minor-fareast;
mso-bidi-font-family:"Times New Roman";mso-bidi-theme-font:minor-bidi;
color:black;background:white;mso-ansi-language:EN-US;mso-fareast-language:EN-US;
mso-bidi-language:AR-SA'><br clear=all style='mso-special-character:line-break;
page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:black;background:white'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpFirst style='text-align:justify'><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;background:white'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><b><span>CSS<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Llamado así por las siglas del nombre en inglés <span
class=SpellE>Cascading</span> Style <span class=SpellE>Sheets</span>. CSS es un
lenguaje de marcado que se centra en definir y mejorar la presentación de un
documento que se basa en HTML. Las pautas que a seguir al momento de usar CSS
son las siguientes:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-36.0pt'><span
class=tagcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;
color:mediumblue;mso-ansi-language:ES'><span style='mso-spacerun:yes'>  </span></span></span><span
class=tagcolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Shorthand Properties</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Hay
que utilizar abreviación de propiedades, declarar los campos de los elementos
en la menor cantidad de líneas posibles. De acuerdo con Google (s.f.), esto
aumenta la eficacia del código y lo hace más entendible. De la misma manera,
debemos evitar el colocar las unidades luego del valor cero.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=SpellE><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%'>Ejemplo</span></span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%'>:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagnamecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>border-top</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: 0;<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagnamecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>font</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: 100</span></span><span class=tagcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext'>%/</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>1.6</span></span><span class=tagcolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext'> <span
class=SpellE>palatino</span>, <span class=SpellE>georgia</span>, serif;</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'> <o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagnamecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>padding</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: 0 1em 2em;</span></span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Declaration Stops</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Hay
que colocar un punto y coma luego de cada declaración al igual que gran parte
de lenguajes de programación. Según Google (s.f.). esta característica ayuda a
que haya más consistencia en el código<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=SpellE><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%'>Ejemplo</span></span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%'>:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast><span class=tagnamecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>html </span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>{</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;background</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: </span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>#fff;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;color</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: </span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>#404;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>}<o:p></o:p></span></span></p>

<span class=tagcolor><span lang=EN-US style='font-size:14.0pt;line-height:115%;
font-family:"Zizou Slab Light";mso-fareast-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-bidi-font-family:"Times New Roman";
mso-bidi-theme-font:minor-bidi;color:mediumblue;mso-ansi-language:EN-US;
mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br clear=all
style='mso-special-character:line-break;page-break-before:always'>
</span></span>

<p class=MsoNormal><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:mediumblue'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpFirst><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Property Name Stops</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Debe
existir un espacio entre los dos puntos que están luego del nombre de una
propiedad y el valor ingresado. Siempre solo un espacio luego de los dos
puntos, mas no antes.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo
estándar según Google (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagnamecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>html </span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>{</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;background</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: </span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>#fff;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;color</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: </span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>#404;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>}<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagcolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Declaration Block Separation</span></b><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>El
uso de un separador de un espacio es necesario luego del nombre de un elemento
seleccionado y la llave que inicia un bloque. Además, esta llave tiene que
estar en la misma línea.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo
estándar según Google (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=tagnamecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>html </span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>{</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;background</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: </span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>#fff;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;color</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: </span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>#404;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>}<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>CSS Quotation Marks</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>No
se deben emplear las comillas dobles (“”), solo están permitidas las simples
(‘’) para el uso exclusivo de selectores de atributos y valores de propiedades.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo
estándar según Google (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast><span class=tagnamecolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>html </span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>{</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;font-family</span></span><span
class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue'>: </span></span><span class=tagnamecolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown'>‘open
sans’</span></span><span class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:windowtext'>, arial, sans-serif</span></span><span
class=tagnamecolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown'>;</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
</span><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue'>}<o:p></o:p></span></span></p>

<span class=tagcolor><span lang=EN-US style='font-size:14.0pt;line-height:115%;
font-family:"Zizou Slab Light";mso-fareast-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-bidi-font-family:"Times New Roman";
mso-bidi-theme-font:minor-bidi;color:mediumblue;mso-ansi-language:EN-US;
mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br clear=all
style='mso-special-character:line-break;page-break-before:always'>
</span></span>

<p class=MsoNormal><span class=tagcolor><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:mediumblue'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpFirst><span class=tagcolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue'><o:p>&nbsp;</o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><b><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>JavaScript<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Es un lenguaje de programación que otorga la
posibilidad de indicar exactamente las acciones que debe ejecutar el navegador,
indicando el orden de las tareas y el número de veces que se realizarán. Las
indicaciones para usar JavaScript en nuestro proyecto son las siguientes:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Spaces around operators</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Se
debe colocar un espacio alrededor de cada operador matemático que se introduzca
en el código. Esto también aplica a las comas.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo
estándar según W3Schools (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=SpellE><span
class=jskeywordcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue;background:white;mso-ansi-language:ES'>let</span></span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white;mso-ansi-language:ES'>&nbsp;x = y + z;</span><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;mso-ansi-language:
ES'><br>
</span><span class=SpellE><span class=jskeywordcolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;background:
white;mso-ansi-language:ES'>const</span></span></span><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;background:white;
mso-ansi-language:ES'>&nbsp;<span class=SpellE>myArray</span> = [</span><span
class=jsstringcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;background:white;mso-ansi-language:ES'>&quot;Volvo&quot;</span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white;mso-ansi-language:ES'>,&nbsp;</span><span class=jsstringcolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
background:white;mso-ansi-language:ES'>&quot;Saab&quot;</span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white;mso-ansi-language:ES'>,&nbsp;</span><span class=jsstringcolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
background:white;mso-ansi-language:ES'>&quot;Fiat&quot;</span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white;mso-ansi-language:ES'>];<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white;mso-ansi-language:ES'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Simple Statement’s End</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Una
indicación simple debe terminar en un punto y coma, esto se cumple también en
muchos otros lenguajes de programación.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo
estándar según W3Schools (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=SpellE><span
class=jskeywordcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:mediumblue;background:white;mso-ansi-language:ES'>let</span></span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white;mso-ansi-language:ES'>&nbsp;x = y + z;</span><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;mso-ansi-language:
ES'><br>
</span><span class=SpellE><span class=jskeywordcolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;background:
white;mso-ansi-language:ES'>const</span></span></span><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;background:white;
mso-ansi-language:ES'>&nbsp;<span class=SpellE>myArray</span> = [</span><span
class=jsstringcolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;background:white;mso-ansi-language:ES'>&quot;Volvo&quot;</span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white;mso-ansi-language:ES'>,&nbsp;</span><span class=jsstringcolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
background:white;mso-ansi-language:ES'>&quot;Saab&quot;</span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white;mso-ansi-language:ES'>,&nbsp;</span><span class=jsstringcolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
background:white;mso-ansi-language:ES'>&quot;Fiat&quot;</span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white;mso-ansi-language:ES'>];<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Beginning and End of a Function</span></b><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Un
bloque de función debe contar con una llave al final de la primera línea, para
que el cierre de esta se encuentre sola en la última. Una función termina en
llave y no en punto y coma. Lo mismo aplica para condicionales o bucles.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo
estándar según W3Schhol (<span class=SpellE>s.f</span>):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast><span class=jskeywordcolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;background:
white'>function</span></span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:black;background:white'>&nbsp;<span class=SpellE>toCelsius</span>(<span
class=SpellE>fahrenheit</span>) {</span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;</span></span><span
class=jskeywordcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:mediumblue;background:white'>return</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>&nbsp;(</span><span class=jsnumbercolor><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:red;background:white'>5</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>&nbsp;/&nbsp;</span><span class=jsnumbercolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:red;
background:white'>9</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>) * (<span class=SpellE>fahrenheit</span>
-&nbsp;</span><span class=jsnumbercolor><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:red;background:white'>32</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>);</span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:black'><br>
<span style='background:white'>}<o:p></o:p></span></span></p>

<span lang=EN-US style='font-size:14.0pt;line-height:115%;font-family:"Zizou Slab Light";
mso-fareast-font-family:"Times New Roman";mso-fareast-theme-font:minor-fareast;
mso-bidi-font-family:"Times New Roman";mso-bidi-theme-font:minor-bidi;
color:black;background:white;mso-ansi-language:EN-US;mso-fareast-language:EN-US;
mso-bidi-language:AR-SA'><br clear=all style='mso-special-character:line-break;
page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:black;background:white'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpFirst><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Object Rules</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Para
la construcción de un objeto, al igual que en una función, se comienza con una
llave al final de la primera línea, pero, esta vez, la llave de cierre debe
estar acompañada de un punto y coma. Para las propiedades, se colocan dos
puntos y un espacio para indicar su valor, el cual debe estar entre comillas
dobles si este es un <span class=SpellE><i>string</i></span>.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo
estándar según W3School (s.f.):<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span class=jskeywordcolor><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:mediumblue;
background:white'>const</span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%;color:black;background:white'>&nbsp;person = {</span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp; <span class=SpellE>firstName</span>:&nbsp;</span></span><span
class=jsstringcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown;background:white'>&quot;John&quot;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>,</span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:black'><br>
<span style='background:white'>&nbsp;&nbsp;<span class=SpellE>lastName</span>:&nbsp;</span></span><span
class=jsstringcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown;background:white'>&quot;Doe&quot;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;
background:white'>,</span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:black'><br>
<span style='background:white'>&nbsp; age:&nbsp;</span></span><span
class=jsnumbercolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:red;background:white'>50</span></span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;color:black;background:white'>,</span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>&nbsp; <span class=SpellE>eyeColor</span>:&nbsp;</span></span><span
class=jsstringcolor><span lang=EN-US style='mso-bidi-font-size:14.0pt;
line-height:115%;color:brown;background:white'>&quot;blue&quot;</span></span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%;color:black'><br>
<span style='background:white'>};<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span class=SpellE><b><span style='mso-bidi-font-size:14.0pt;
line-height:115%;mso-ansi-language:ES-PE'>Gherkin</span></b></span><b><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Es un Lenguaje Específico de Dominio (DSL por sus
siglas en inglés) que tiene como objetivo la resolución de un problema en
específico. Para ello, se generan casos para la validación de la característica
en distintos escenarios. <span class=SpellE>Gherkin</span> cuenta con múltiples
elementos, de los cuales, los más famosos y, además, más utilizados son</span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:#333333;
letter-spacing:-.15pt;background:white;mso-ansi-language:ES'>&nbsp;</span><span
class=SpellE><i><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>Feature</span></i></span><i><span style='mso-bidi-font-size:
14.0pt;line-height:115%;mso-ansi-language:ES-PE'>,&nbsp;<span class=SpellE>Scenario</span>,&nbsp;<span
class=SpellE>Example</span>,&nbsp;<span class=SpellE>Scenario</span>, <span
class=SpellE>Given</span>, <span class=SpellE>When</span> </span></i><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>y<i>
<span class=SpellE>Then</span>. </i>Las indicaciones para tomar en cuenta en el
uso de <span class=SpellE>Gherkin</span> en nuestro código son las siguientes.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><i><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></i></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Discernible Given-When-Then Blocks</span></b><span
lang=EN-US style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Aplicar
sangría para los elementos que indiquen pasos a seguir del escenario. En el
caso de <i>And</i>, aplicar dos veces. De acuerdo con </span><span
class=SpellE><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:windowtext;mso-ansi-language:ES-PE'>Keiblinger</span></span><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;mso-ansi-language:
ES-PE'> (2021),</span><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'> Esto ayuda a detectar rápidamente las partes que
forman un escenario.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>    </span></span></span><span class=SpellE><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:ES'>Scenario</span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:ES'>:</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'> </span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'>Ingreso los requisitos con claridad</span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:windowtext;mso-ansi-language:ES-PE'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:
ES'>Given</span></span></span><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'> </span></span><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:windowtext;mso-ansi-language:ES'>que en el
formulario de ingreso de oferta laboral</span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:
ES'>When</span></span></span><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'> </span></span><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:windowtext;mso-ansi-language:ES'>escribo
claramente los requisitos<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:91.6pt;mso-add-space:
auto;text-align:justify;text-indent:-49.6pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#0070C0;mso-ansi-language:ES'>Then</span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#0070C0;mso-ansi-language:ES'> </span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:windowtext;mso-ansi-language:ES'>se mostrará el mensaje <o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:127.05pt;mso-add-space:
auto;text-align:justify;text-indent:-49.65pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#0070C0;mso-ansi-language:ES'>And</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'> </span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'>mi oferta solo aparecerá a quienes cumplan con estos</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'><span style='mso-spacerun:yes'>     
</span><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:127.05pt;mso-add-space:
auto;text-align:justify;text-indent:-49.65pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:#0070C0;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span>And </span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:windowtext;mso-ansi-language:ES'>se habilita la opción<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:127.05pt;mso-add-space:
auto;text-align:justify;text-indent:-49.65pt'><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Step with Tables</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Según
</span><span class=SpellE><span style='mso-bidi-font-size:14.0pt;line-height:
115%;color:windowtext;mso-ansi-language:ES-PE'>Keiblinger</span></span><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>
(2021), para las partes del escenario que necesiten la introducción de valores,
hay que agregar una tabla o crear un propio formulario que recree esa parte del
escenario. Antes de esta representación se deben colocar dos puntos. <o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:91.6pt;mso-add-space:
auto;text-align:justify;text-indent:-49.6pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#0070C0;mso-ansi-language:ES'>Then</span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#0070C0;mso-ansi-language:ES'> </span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:windowtext;mso-ansi-language:ES'>se mostrará el mensaje:</span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:windowtext;mso-ansi-language:ES-PE'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:119.95pt;mso-add-space:
auto;text-align:justify;text-indent:-7.1pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'>| mensaje<span
style='mso-spacerun:yes'>                                         
</span>|<span style='mso-spacerun:yes'>                        </span><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:119.95pt;mso-add-space:
auto;text-align:justify;text-indent:-7.1pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'>| Se completaron los requisitos adecuadamente<span
style='mso-spacerun:yes'>      </span>| <o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:119.95pt;mso-add-space:
auto;text-align:justify;text-indent:-7.1pt'><span style='mso-bidi-font-size:
14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Reducing Noise</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Con
el fin de reducir la acumulación de demasiadas líneas de código en un
escenario, se deben colocar valores por defecto dentro de los pasos para los
campos que no sean muy relevantes para este. Los valores “estándar” que
coloquemos, deben ir entre comillas simples. De acuerdo con </span><span
class=SpellE><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:windowtext;mso-ansi-language:ES-PE'>Keiblinger</span></span><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;mso-ansi-language:
ES-PE'> (2021), esta acción reduce considerablemente el tamaño del código.</span><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:
ES'>When</span></span></span><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'> </span></span><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:windowtext;mso-ansi-language:ES'>escribo
claramente los requisitos </span></span><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:gray;mso-themecolor:
background1;mso-themeshade:128;mso-ansi-language:ES'>‘dominio en C’</span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:windowtext;mso-ansi-language:ES-PE'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:119.95pt;mso-add-space:
auto;text-align:justify;text-indent:-7.1pt'><span style='mso-bidi-font-size:
14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt;
mso-list:l8 level1 lfo6'><![if !supportLists]><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span lang=EN-US style='mso-bidi-font-size:
14.0pt;line-height:115%'>Scenarios Separator</span></b><span lang=EN-US
style='mso-bidi-font-size:14.0pt;line-height:115%'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>Para
la separación de dos escenarios, se debe insertar un salto de línea y, según </span><span
class=SpellE><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:windowtext;mso-ansi-language:ES-PE'>Keiblinger</span></span><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;mso-ansi-language:
ES-PE'> (2021),</span><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'> de ser posible, hay que agregar una línea de
comentario para facilitar la visualización de estos. De esta forma se halla
rápidamente el inicio y fin de un escenario.<o:p></o:p></span></p>

<span style='font-size:14.0pt;line-height:115%;font-family:"Zizou Slab Light";
mso-fareast-font-family:"Times New Roman";mso-fareast-theme-font:minor-fareast;
mso-bidi-font-family:"Times New Roman";mso-bidi-theme-font:minor-bidi;
color:black;mso-themecolor:text1;mso-ansi-language:ES-PE;mso-fareast-language:
EN-US;mso-bidi-language:AR-SA'><br clear=all style='mso-special-character:line-break;
page-break-before:always'>
</span>

<p class=MsoNormal><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpFirst style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'>Ejemplo:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES'><span
style='mso-spacerun:yes'>          </span></span><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:#70AD47;mso-themecolor:
accent6;mso-ansi-language:ES'>#-----------------------------------------------------------------------------------</span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:
ES'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>    </span></span></span><span class=SpellE><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:ES'>Scenario</span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:ES'>:</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'> </span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'>Ingreso los requisitos con claridad</span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:windowtext;mso-ansi-language:ES-PE'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:
ES'>Given</span></span></span><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'> </span></span><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:windowtext;mso-ansi-language:ES'>que en el
formulario de ingreso de oferta laboral</span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:
ES'>When</span></span></span><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'> </span></span><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:windowtext;mso-ansi-language:ES'>escribo
claramente los requisitos<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:91.6pt;mso-add-space:
auto;text-align:justify;text-indent:-49.6pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#0070C0;mso-ansi-language:ES'>Then</span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#0070C0;mso-ansi-language:ES'> </span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:windowtext;mso-ansi-language:ES'>se mostrará el mensaje <o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:127.05pt;mso-add-space:
auto;text-align:justify;text-indent:-49.65pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#0070C0;mso-ansi-language:ES'>And</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'> </span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'>mi oferta solo aparecerá a quienes cumplan con estos</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'><span style='mso-spacerun:yes'>     
</span><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:127.05pt;mso-add-space:
auto;text-align:justify;text-indent:-49.65pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:#0070C0;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span>And </span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:windowtext;mso-ansi-language:ES'>se habilita la opción</span></span><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;mso-ansi-language:
ES'><span style='mso-spacerun:yes'> </span><span lang=ES><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:#70AD47;mso-themecolor:
accent6;mso-ansi-language:ES'><span style='mso-spacerun:yes'>         
</span>#-----------------------------------------------------------------------------------</span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:
ES'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>    </span></span></span><span class=SpellE><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:ES'>Scenario</span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:ES'>:</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'> </span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'>Ingreso los requisitos con claridad</span></span><span
class=tagnamecolor><span style='mso-bidi-font-size:14.0pt;line-height:115%;
color:windowtext;mso-ansi-language:ES-PE'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:
ES'>Given</span></span></span><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'> </span></span><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:windowtext;mso-ansi-language:ES'>que en el formulario
de ingreso de oferta laboral</span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:42.0pt;mso-add-space:
auto;text-align:justify'><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#4472C4;mso-themecolor:accent1;mso-ansi-language:
ES'>When</span></span></span><span class=tagnamecolor><span lang=ES
style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;mso-ansi-language:
ES'> </span></span><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:windowtext;mso-ansi-language:ES'>escribo
claramente los requisitos<o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:91.6pt;mso-add-space:
auto;text-align:justify;text-indent:-49.6pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=SpellE><span class=tagnamecolor><span lang=ES style='mso-bidi-font-size:
14.0pt;line-height:115%;color:#0070C0;mso-ansi-language:ES'>Then</span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#0070C0;mso-ansi-language:ES'> </span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:windowtext;mso-ansi-language:ES'>se mostrará el mensaje <o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:127.05pt;mso-add-space:
auto;text-align:justify;text-indent:-49.65pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:brown;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span></span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:#0070C0;mso-ansi-language:ES'>And</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'> </span></span><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'>mi oferta solo aparecerá a quienes cumplan con estos</span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:brown;mso-ansi-language:ES'><span style='mso-spacerun:yes'>     
</span><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:127.05pt;mso-add-space:
auto;text-align:justify;text-indent:-49.65pt'><span class=tagnamecolor><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:#0070C0;
mso-ansi-language:ES'><span style='mso-spacerun:yes'>        </span>And </span></span><span
class=tagnamecolor><span lang=ES style='mso-bidi-font-size:14.0pt;line-height:
115%;color:windowtext;mso-ansi-language:ES'>se habilita la opción</span></span><span
lang=ES style='mso-bidi-font-size:14.0pt;line-height:115%;color:windowtext;
mso-ansi-language:ES'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span class=SpellE><b><span style='mso-bidi-font-size:14.0pt;
line-height:115%;mso-ansi-language:ES-PE'>TypeScript</span></b></span><b><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>El
equipo usara los siguientes estilos para determinadas categorías:<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=SpellE><b><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>UpperCamelCase</span></b></span><b><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>: </span></b><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>clase/interfaz/tipo/<span
class=SpellE>enum</span>/decorador/parámetros de tipo<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><span
class=SpellE><b><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>lowerCamelCase</span></b></span><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>: variable
/ parámetro / función / método / propiedad / alias de módulo <o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify'><b><span
style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:ES-PE'>CONSTANT_CASE:
</span></b><span style='mso-bidi-font-size:14.0pt;line-height:115%;mso-ansi-language:
ES-PE'>valores constantes globales, incluidos los valores de enumeración<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'>*Nunca se utilizan identificadores privados.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:0cm;mso-add-space:auto;
text-align:justify'><span style='mso-bidi-font-size:14.0pt;line-height:115%;
mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level3 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>§<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><u><span
style='color:windowtext;mso-ansi-language:ES-PE'>Variables y Funciones<o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Mala Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:red;mso-ansi-language:ES-PE'>let</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE>RandomName</span>:
</span><span class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>string</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> = ‘Juan’;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>function</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>RandomFunction</span></span><span class=GramE>(</span>) {}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Buena Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:red;mso-ansi-language:ES-PE'>let</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE>randomName</span>:
</span><span class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>string</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> = ‘Juan’;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>function</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>randomFunction</span></span><span class=GramE>(</span>) {}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level3 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>§<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><u><span
style='color:windowtext;mso-ansi-language:ES-PE'>Clases<o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Mala Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>class</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>view</span></span><span class=GramE>{</span>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Buena Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>class</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=GramE>View{</span>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><u><span style='color:windowtext;mso-ansi-language:
ES-PE'>Propiedades y métodos de la clase<o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Mala Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>class</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=GramE>test{</span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span style='color:windowtext;
mso-ansi-language:ES-PE'>Name</span></span><span style='color:windowtext;
mso-ansi-language:ES-PE'>: </span><span class=SpellE><span style='color:#0070C0;
mso-ansi-language:ES-PE'>string</span></span><span style='color:#0070C0;
mso-ansi-language:ES-PE'>;</span><span style='color:windowtext;mso-ansi-language:
ES-PE'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span class=GramE><span
style='color:windowtext;mso-ansi-language:ES-PE'>GetFullName</span></span></span><span
class=GramE><span style='color:windowtext;mso-ansi-language:ES-PE'>(</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'>){}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Buena Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>class</span></span><span
style='color:#0070C0;mso-ansi-language:ES-PE'> </span><span class=GramE><span
style='color:windowtext;mso-ansi-language:ES-PE'>test{</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span style='color:windowtext;
mso-ansi-language:ES-PE'>name</span></span><span style='color:windowtext;
mso-ansi-language:ES-PE'>: </span><span class=SpellE><span style='color:#0070C0;
mso-ansi-language:ES-PE'>string</span></span><span style='color:#0070C0;
mso-ansi-language:ES-PE'>;</span><span style='color:windowtext;mso-ansi-language:
ES-PE'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span class=GramE><span
style='color:windowtext;mso-ansi-language:ES-PE'>getFullName</span></span></span><span
class=GramE><span style='color:windowtext;mso-ansi-language:ES-PE'>(</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'>){}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level3 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>§<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><u><span
style='color:windowtext;mso-ansi-language:ES-PE'>Interfaces <o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>No
emplear el prefijo I para nombrar interfaces<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Mala Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
style='color:#0070C0;mso-ansi-language:ES-PE'>interface</span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>IPerson</span></span><span class=GramE>{</span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span class=GramE><span
style='color:windowtext;mso-ansi-language:ES-PE'>Name:string</span></span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'>;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Buena Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
style='color:#0070C0;mso-ansi-language:ES-PE'>interface</span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>Person</span></span><span class=GramE>{</span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span class=GramE><span
style='color:windowtext;mso-ansi-language:ES-PE'>name:string</span></span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'>;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level3 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>§<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><span
class=SpellE><u><span style='color:windowtext;mso-ansi-language:ES-PE'>Enums</span></u></span><u><span
style='color:windowtext;mso-ansi-language:ES-PE'> <o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>No
emplear el prefijo I para nombrar interfaces<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Mala Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>enum</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>clientType</span></span><span class=GramE>{</span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span style='color:windowtext;
mso-ansi-language:ES-PE'>person</span></span><span style='color:windowtext;
mso-ansi-language:ES-PE'> = “p”;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span style='color:windowtext;
mso-ansi-language:ES-PE'>business</span></span><span style='color:windowtext;
mso-ansi-language:ES-PE'> = “b”;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Buena Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>enum</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>ClientType</span></span><span class=GramE>{</span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span style='color:windowtext;
mso-ansi-language:ES-PE'>Person</span></span><span style='color:windowtext;
mso-ansi-language:ES-PE'> = “P”;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>Age
= “A”;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level3 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>§<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><span
class=SpellE><u><span style='color:windowtext;mso-ansi-language:ES-PE'>Visibility</span></u></span><u><span
style='color:windowtext;mso-ansi-language:ES-PE'> <o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>Restringir
la visibilidad de propiedades, métodos y tipos ayudaran a mantener el código
desacoplado.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Mala Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>enum</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>clientType</span></span><span class=GramE>{</span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span style='color:windowtext;
mso-ansi-language:ES-PE'>person</span></span><span style='color:windowtext;
mso-ansi-language:ES-PE'> = “p”;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span style='color:windowtext;
mso-ansi-language:ES-PE'>business</span></span><span style='color:windowtext;
mso-ansi-language:ES-PE'> = “b”;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Buena Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>enum</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> <span class=SpellE><span
class=GramE>ClientType</span></span><span class=GramE>{</span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><span style='color:windowtext;
mso-ansi-language:ES-PE'>Person</span></span><span style='color:windowtext;
mso-ansi-language:ES-PE'> = “P”;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>Age
= “A”;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level3 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>§<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><span
class=SpellE><u><span style='color:windowtext;mso-ansi-language:ES-PE'>Getters</span></u></span><u><span
style='color:windowtext;mso-ansi-language:ES-PE'> and <span class=SpellE>Setters</span><o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>Se
pueden utilizar los <span class=SpellE>getters</span> y <span class=SpellE>setters</span>
para los miembros de la clase. También son útiles como medio para restringir la
visibilidad de los detalles de implementación internos, aplicando la
Programación Orientada a Objetos;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span style='color:windowtext;mso-ansi-language:
ES-PE'>Nomenclatura:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
class=SpellE><span style='color:#0070C0;mso-ansi-language:ES-PE'>Class</span></span><span
style='color:#0070C0;mso-ansi-language:ES-PE'> </span><span class=SpellE><span
style='color:windowtext;mso-ansi-language:ES-PE'>Foo</span></span><span
style='color:windowtext;mso-ansi-language:ES-PE'> {<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span class=GramE><span lang=EN-US style='color:windowtext'>constructor(</span></span><span
lang=EN-US style='color:windowtext'>private <span class=SpellE>readonly</span> <span
class=SpellE>someService:SomeService</span>) {}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'>get <span
class=SpellE><span class=GramE>someMember</span></span><span class=GramE>(</span>):</span><span
lang=EN-US style='color:#0070C0'>string</span><span lang=EN-US
style='color:windowtext'>{<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'>return <span
class=SpellE><span class=GramE>this.someService.someVariable</span></span>;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'>set <span
class=SpellE>someMember</span>(<span class=SpellE><span class=GramE>newValue:<span
style='color:#0070C0'>string</span></span></span>){<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'><span
style='mso-spacerun:yes'>  </span><span class=SpellE><span class=GramE>this.someService.someVariable</span></span>
= <span class=SpellE>newValue</span>;<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'>}<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level3 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>§<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><u><span
style='color:windowtext;mso-ansi-language:ES-PE'>Variables<o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>Uso
de <span class=SpellE>const</span> o <span class=SpellE>let</span> para
declarar variables. Utilice <span class=SpellE>const</span> de forma
predeterminada, a menos que sea necesario reasignar una variable.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><span style='color:windowtext;mso-ansi-language:ES-PE'>No
usar <span class=SpellE>var</span> para declarar variables. <o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><b><span lang=EN-US
style='color:windowtext'>Nomenclatura</span></b></span><b><span lang=EN-US
style='color:windowtext'>:<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
lang=EN-US style='font-family:Wingdings;mso-fareast-font-family:Wingdings;
mso-bidi-font-family:Wingdings;color:windowtext'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
lang=EN-US style='color:#0070C0'>const</span><span lang=EN-US style='color:
windowtext'> foo = <span class=SpellE><span class=GramE>otherValue</span></span><span
class=GramE>;<span style='mso-spacerun:yes'>  </span>/</span>/ Use if
&quot;foo&quot; never changes.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level5 lfo5'><![if !supportLists]><span
lang=EN-US style='font-family:Wingdings;mso-fareast-font-family:Wingdings;
mso-bidi-font-family:Wingdings;color:windowtext'><span style='mso-list:Ignore'>Ø<span
style='font:7.0pt "Times New Roman"'> </span></span></span><![endif]><span
lang=EN-US style='color:#0070C0'>let</span><span lang=EN-US style='color:windowtext'>
bar = <span class=SpellE><span class=GramE>someValue</span></span><span
class=GramE>;<span style='mso-spacerun:yes'>   </span></span><span
style='mso-spacerun:yes'>  </span>// Use if &quot;bar&quot; is ever assigned into
later on.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:144.0pt;mso-add-space:
auto;text-align:justify'><span lang=EN-US style='color:windowtext'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify;text-indent:-18.0pt;mso-list:l5 level3 lfo5'><![if !supportLists]><span
style='font-family:Wingdings;mso-fareast-font-family:Wingdings;mso-bidi-font-family:
Wingdings;color:windowtext;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>§<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><span
class=SpellE><u><span style='color:windowtext;mso-ansi-language:ES-PE'>Imports</span></u></span><u><span
style='color:windowtext;mso-ansi-language:ES-PE'><span
style='mso-spacerun:yes'>                  </span>Nomenclatura <o:p></o:p></span></u></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span lang=EN-US style='color:windowtext'>Module</span></b><span
lang=EN-US style='color:windowtext'>:<span style='mso-tab-count:1'>      </span><span
style='mso-spacerun:yes'>        </span>import * as foo from '...';<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><span class=SpellE><b><span lang=EN-US
style='color:windowtext'>Destructuring</span></b></span><span lang=EN-US
style='color:windowtext'>: <span style='mso-spacerun:yes'> </span>import {<span
class=SpellE>SomeThing</span>} from '...';<span style='mso-tab-count:1'>    </span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:72.0pt;mso-add-space:
auto;text-align:justify'><b><span lang=EN-US style='color:windowtext'>Default</span></b><span
lang=EN-US style='color:windowtext'>:<span style='mso-tab-count:1'>      </span><span
style='mso-spacerun:yes'>        </span>import <span class=SpellE>SomeThing</span>
from '...';<span style='mso-tab-count:1'>       </span><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:72.0pt;mso-add-space:auto;
text-align:justify'><b><span lang=EN-US style='color:windowtext'>Side-effect:</span></b><span
lang=EN-US style='color:windowtext'><span style='mso-tab-count:1'> </span><span
style='mso-spacerun:yes'>        </span>import '...';<span style='mso-tab-count:
1'>     </span>Only to import libraries for their side-effects on load (such as
custom elements)<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='color:windowtext'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:54.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Vue.js <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:70.8pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Vue.js es un <span class=SpellE>framework</span>
de JavaScript ampliamente utilizado para crear aplicaciones web interactivas y
dinámicas. Aquí están las pautas y características que se seguirán al trabajar
con Vue.js:<o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:90.0pt;mso-add-space:auto;
text-align:justify;text-indent:-18.0pt;mso-list:l11 level1 lfo12'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='mso-ansi-language:ES-PE'>Nombres de Componentes:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Se utilizará un formato estándar para nombrar
los componentes en el proyecto.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Los nombres de los componentes seguirán la
convención de <span class=SpellE>camelCase</span>.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Los nombres de los componentes se escribirán en
singular.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Un ejemplo estándar sería: &quot;<span
class=SpellE>informationComponent.vue</span>&quot;.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Para las referencias en el código, se utilizará
la estructura &quot;kebab-case&quot;.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Ejemplo de referencia: &quot;<span
class=SpellE>information-component</span>&quot;.<o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:90.0pt;mso-add-space:auto;
text-align:justify;text-indent:-18.0pt;mso-list:l11 level1 lfo12'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='mso-ansi-language:ES-PE'>Nombres de Servicios:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Los nombres de los servicios seguirán un
formato estándar.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Se añadirá el sufijo &quot;<span class=SpellE>Service</span>&quot;
al nombre.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Cada palabra en el nombre del servicio comenzará
con mayúscula.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Ejemplos: &quot;<span class=SpellE>dataService</span>&quot;,
&quot;<span class=SpellE>paymentService</span>&quot;.<o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:90.0pt;mso-add-space:auto;
text-align:justify;text-indent:-18.0pt;mso-list:l11 level1 lfo12'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='mso-ansi-language:ES-PE'>Nombres de Archivos de Pruebas Unitarias:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Los nombres de los archivos de pruebas
unitarias seguirán un formato similar al de los componentes, pero con la adición
de <span class=GramE>&quot;.<span class=SpellE>spec</span></span>&quot; antes
de &quot;.<span class=SpellE>vue</span>&quot;.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Ejemplo: &quot;<span class=SpellE>information-component.spec.vue</span>&quot;.<o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:90.0pt;mso-add-space:auto;
text-align:justify;text-indent:-18.0pt;mso-list:l11 level1 lfo12'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='mso-ansi-language:ES-PE'>Declaración de Funciones:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Se seguirán las siguientes pautas al declarar
funciones:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Siempre especificar la visibilidad de la función
(pública, protegida o privada).<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Si hay múltiples operadores, especificar el
orden utilizando corchetes.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Evitar usar &quot;<span class=SpellE>this</span>.&quot;
cuando no sea necesario.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Ejemplo de declaración de función correcta:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
class=SpellE><span style='mso-ansi-language:ES-PE'>javascriptCopy</span></span><span
style='mso-ansi-language:ES-PE'> <span class=SpellE>code</span><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
class=SpellE><span style='mso-ansi-language:ES-PE'>public</span></span><span
style='mso-ansi-language:ES-PE'> <span class=SpellE><span class=GramE>setGroupNames</span></span><span
class=GramE>(</span><span class=SpellE>group</span>, <span class=SpellE>name</span>)
{ // Código de la función } <o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:90.0pt;mso-add-space:auto;
text-align:justify;text-indent:-18.0pt;mso-list:l11 level1 lfo12'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='mso-ansi-language:ES-PE'>División de Líneas:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Al dividir una expresión en múltiples líneas,
se seguirán las siguientes pautas:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Hacer un salto de línea después de una coma.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Dividir antes de un operador.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Alinear la nueva línea con el comienzo de la
expresión en la línea anterior.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Si las reglas anteriores resultan en un código
confuso o demasiado ajustado al margen derecho, se agregará una sangría de 8
espacios en su lugar.<o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:90.0pt;mso-add-space:auto;
text-align:justify;text-indent:-18.0pt;mso-list:l11 level1 lfo12'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;mso-ansi-language:ES-PE'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='mso-ansi-language:ES-PE'>Contadores de Bucles:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Las variables locales en bucles seguirán la
convención de nombres estándar, como i, j, k, l, en todos los casos.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'>Estas pautas y características se aplicarán al
desarrollar aplicaciones Vue.js para mantener un código limpio, legible y
coherente.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:90.0pt;text-align:justify'><span
style='mso-ansi-language:ES-PE'><o:p>&nbsp;</o:p></span></p>

</div>

<h3>5.1.4. Software Deployment Configuration</h3>
Como ya se ha mencionado, la gestión de nuestro código fuente se realizará a través de GitHub. Asimismo, se utilizará GitHub Pages para la publicación y despliegue de la página. Cada sección del Landing Page que se ha creado deberá aparecer en el siguiente vínculo:<br>https://diegoacuna1612.github.io/diegoAcuna1612land.github.io/public/index.html
<br><br>
Para el desarrollo del Landing Page de Nourishify se han utilizado las siguientes herramientas: 
   <ul>
      <li>
         <strong>Html:</strong> Es el lenguaje de marcado que estructuro nuestro Landing Page.<br>Evidencia: Archivos HTML, el principal es index.html donde todos los integrantes juntaron el contenido realizado en su rama individual. 
      </li>
      <br>
         <p align ="center">
         <img src="../images/software-deployment-configuration-images/softdevconfig-html-evidence.png" >
         </p>
      <li>
         <strong>Css:</strong> Es aquel que nos ayudó con el diseño gráfico para que el Landing Page sea agradable e interactúale<br>Evidencia: Se presenta el file styles.css, donde el grupo implemento el diseño de toda la estructura realizada con html. 
      </li><br>
         <p align ="center">
            <img src="../images/software-deployment-configuration-images/softdevconfig-css-evidence.png" >
         </p>
      <li>
         <strong>JS:</strong> Nos ayudó a desarrollar la lógica necesaria para el Landing Page.<br>Evidencia: Se muestra el documento main.js.
      </li><br>
         <p align ="center">
            <img src="../images/software-deployment-configuration-images/softdevconfig-js-evidence.png" >
         </p>
   </ul>
El despliegue del Landing Page de Nourishify no pudo ser posible sin utilizar las siguientes tecnologías:

   <ul>
      <li><strong>Git:</strong> Sistema de control de versiones que está pensado en la eficiencia y compatibilidad de versiones. El cual nos ayudó a trabajar en equipo durante el desarrollo del Landing Page. 
      </li><br>
         <p align ="center">
            <img src="../images/software-deployment-configuration-images/git.png" width="100" height="100" >
         </p>
      <li>
         <strong>Github:</strong> Plataforma de desarrollo colaborativo
      </li><br>
       <p align ="center">
            <img src="../images/software-deployment-configuration-images/github.png" width="100" height="100" >
         </p>
      <li>
         <strong>Git Flow:</strong>Nos permitió controlar el avance de cada uno de nuestros integrantes con respecto al desarrollo del Landing Page
      </li> 
      <li>
         <strong>Git Hub Pages</strong>Servicio de Github que nos permitió alojar nuestra Landing page.
      </li> <br>
         <p align ="center">
            <img src="../images/software-deployment-configuration-images/githubpages.jpg" width="200" height="100" >
         </p>
   </ul>
   <br>
   Asimismo, se han realizado los siguientes pasos: 
   <ul>
      <li><strong>Dirigirse al repositorio de la página</strong>: Dado que se ha empleado Github, debemos ir al repositorio creado en este sitio web para publicar el Landing Page que ha desarrollado el equipo. Desde aquí, se podrá iniciar la configuración del vínculo de la página dirigiéndonos al apartado de Settings.</li><br>
        <p align ="center">
            <img src="../images/software-deployment-configuration-images/pasos-settings.png">
         </p>
      <li><strong>Ir a la opción de páginas:</strong> Una vez presentes la configuración del repositorio, debemos dirigirnos a la sección de Pages. Esto se debe a que ahí se encuentran todas las opciones de configuración de publicación de la página en un link o vínculo.</li><br>
        <p align ="center">
            <img src="../images/software-deployment-configuration-images/pasos-pages.png">
         </p>
      <li><strong>Elección de rama y carpeta de guardado: </strong>Dentro de pages, se debe seleccionar la rama o branch que se va a publicar en el vínculo. De la misma manera, se tiene que elegir la carpeta donde se localizará esta publicación a realizar. Finalmente podremos acceder a nuestra página con el link que aparece en la parte superior de este apartado de configuración</li><br>
        <p align ="center">
            <img src="../images/software-deployment-configuration-images/pasos-rama.png">
         </p>
   </ul>
   Siguiendo los pasos, obtenemos el siguiente enlace:<br>
   https://diegoacuna1612.github.io/diegoAcuna1612land.github.io/public/index.html
   <br>
   <strong>Evidencia de Deployment</strong><br><br>
        <p align ="center">
            <img src="../images/software-deployment-configuration-images/evidencia-deployment.png">
         </p>
   Se puede visualizar el link en la barra de búsqueda y que está en modo público desde un computador x. 
   <br><br>
   Se muestran las acciones realizadas en el github para el lanzamiento del Landing Page.<br><br>
        <p align ="center">
            <img src="../images/software-deployment-configuration-images/evidencia-deployment2.png">
         </p>

<div display="flex" align="right" >
   </br></br>
   &lt;
   <a href="../chapter-4/8-database-design.md">Previous</a>
   &boxh;
   <a href="./sprint-1/1-sprint-planing-1.md">Next</a>
   &gt;
   </br></br>
</div>
