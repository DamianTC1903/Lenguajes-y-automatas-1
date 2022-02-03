<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Lenguajes y automatas 1</h3>
  <p align="center">
    Analizador lexico | simulador de un compilador basado en el lenguaje java!
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenido</summary>
  <ol>
    <li>
      <a href="#about-the-project">Sobre el proyecto</a>
      <ul>
        <li><a href="#built-with">Construido con</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre el Proyecto

[![Product Name Screen Shot][product-screenshot]](https://example.com)

El analizador léxico primera fase de un compilador.

Consistente en un programa que recibe como entrada el código fuente de otro programa (secuencia de caracteres) y produce una salida compuesta de tokens (componentes léxicos) o símbolos. Estos tokens sirven para una posterior etapa del proceso de traducción, siendo la entrada para el analizador sintáctico (en inglés parser).

El principal objetivo del analizador lexico es leer el flujo de caracteres de entrada y transformarlo en una secuencia de componentes
lexicos que utilizara el analizador sintactico.

Se han desarrollado herramientas para construir analizadores léxicos a partir de
expresiones regulares. Un ejemplo de este tipo es LEX escrito por Mike Lex y Eric
Schmidt, que en su versión libre se denominó Flex (Fast Lex) o java.util.regex un paquete para trabajar con expresiones regulares en java el cual fue usado para este proyecto


El paquete incluye las siguientes clases:
* PatternClase - Define un patrón (para ser usado en una búsqueda)
* MatcherClase: se utiliza para buscar el patrón.
* PatternSyntaxExceptionClase: indica un error de sintaxis en un patrón de expresión regular


<p align="right">(<a href="#top">back to top</a>)</p>



### Construido con

* [javaSE](https://www.oracle.com/java/technologies/java-se-glance.html)
* [java.util.regex.Pattern](https://docs.oracle.com/javase/7/docs/api/java/util/regex/Pattern.html)
* [regex101](https://regex101.com/) 

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Empezando

Descargue el ultimo paquete de los lanzamientos

### Prerequisitos

Plataforma de desarrollo java eclipse (preferiblemente pero puede usar otro IDE) y JDK 8 o superior.

1. Descargue [eclipse](https://www.eclipse.org/downloads/)
2. Descargue [Java SE 8](https://www.oracle.com/mx/java/technologies/javase/javase8-archive-downloads.html)  o [Java SE+](https://www.oracle.com/java/technologies/java-se-glance.html)


  ```sh
  _______________
  ```

### Instalacion

Descomprima el archivo en su carpeta preferida

Importe un proyecto en Eclipse:
1. Pulse Archivo > Importar.
2. En la página Seleccionar del recuadro de diálogo Importar, seleccione Proyectos al Espacio de trabajo en el recuadro de lista Seleccionar un origen de importación y pulse Siguiente.
3. En la página Importar proyectos del recuadro de diálogo Importar, verifique si la opción Seleccionar directorio raíz está seleccionada y, a continuación , pulse el botón Examinar de esta opción.
4. En el recuadro de diálogo Examinar para buscar carpeta, vaya a la ubicación de almacenamiento.
5. Seleccione la carpeta (aqui el nombre puede variar) en el recuadro de lista Proyectos del recuadro de diálogo Importar proyectos.
Pulse Finalizar.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Uso

.....

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## Licencia

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Agradecimientos

......

* [Choose an Open Source License](https://choosealicense.com)


<p align="right">(<a href="#top">back to top</a>)</p>





[product-screenshot]: screenshots/main.png

