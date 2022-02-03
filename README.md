<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



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
Importe un proyecto de Eclipse para la guía de aprendizaje de UCM.

Para importar:

En Eclipse:
1. Pulse Archivo > Importar.
2. En la página Seleccionar del recuadro de diálogo Importar, seleccione Proyectos al Espacio de trabajo en el recuadro de lista Seleccionar un origen de importación y pulse Siguiente.
3. En la página Importar proyectos del recuadro de diálogo Importar, verifique si la opción Seleccionar directorio raíz está seleccionada y, a continuación , pulse el botón Examinar de esta opción.
4. En el recuadro de diálogo Examinar para buscar carpeta, vaya a la ubicación de almacenamiento.
5. Seleccione la carpeta (aqui el nombre puede variar) en el recuadro de lista Proyectos del recuadro de diálogo Importar proyectos.
Pulse Finalizar.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Uso

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: screenshots/main.png

