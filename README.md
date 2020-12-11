# Curso de introducción a la edición (crítica) digital.

#### *Naukowa edycja cyfrowa*  (2020/21)  zob. sylabus w [USOS](https://usosweb.uni.wroc.pl/kontroler.php?_action=katalog2%2Fprzedmioty%2FpokazPrzedmiot&prz_kod=21-FL-H-S2-E2-NEdCy&lang=en)

<img src="https://raw.githubusercontent.com/editio/slides/gh-pages/imagenes/logo_UWr_ang.png" width="40%">

### Contenido del programa:

- Introducción a las humanidades digitales.

- Nociones básicas de edición crítica/documental/académica.

- *Scholarly Digital Editions*: *case studies*.

- Modelo de referencia para la edición digital.

- Los lenguajes de marcado y XML.

- Bases de la codificación con TEI (*Text Encoding Iniciative*).

- TEI-Guidelines.

- Contenido: transcripción con TEI/XML.

- Estructura: schema.

- Información: metadatos y teiHeader.

- Representación: xslt, css, html.

### Bibliografía y presentaciones

- Allés Torrent, S., “[Edición digital y algunas tecnologías aliadas: codificación TEI y transformaciones XSLT](https://academiccommons.columbia.edu/download/fedora_content/download/ac:189048/CONTENT/5.Insula-822-18-21.pdf),” *Insula. Revista de Letras y Ciencias Humanas*, 822, 2015, pp. 18-21.

- Burnard L. et alii (eds.), *[Electronic textual editing](http://www.tei-c.org/About/Archive_new/ETE/Preview/)*, New York, Modern Language Association of America, 2006.

- Burnard L., *[What is the Text Encoding Initiative? How to add intelligent markup to digital resources](http://books.openedition.org/oep/426)*, Marseille, OpenEdition Press (Encyclopédie numérique, n° 3), 2014.

- Driscoll, M.J., Pierazzo, E. (Eds.), *[Digital Scholarly Editing: Theories and Practices](http://www.openbookpublishers.com/product/483)*, Open Book Publishers, 2016.

- Pierazzo E., *Digital Scholarly Editing*, Theories, Models and Methods, Ashgate Publishing, 2015. [available on preprint](https://hal.archives-ouvertes.fr/hal-01182162)

- Losada Palenzuela J.L., [Humanidades digitales. Breve introducción](http://editio.github.io/presentations/dh-intro), 2017.

- Losada Palenzuela J.L., [Markup, XML, TEI. Character, structure, guidelines](http://editio.github.io/slides/xml-tei), 2016.

- Losada Palenzuela J.L., [Introduction to Digital Scholarly Editions. Terminology, examples, evaluation, reference model](http://editio.github.io/slides/editions), 2016.

- Losada Palenzuela, J.L., “[Las fronteras del canon: *distant reading*](http://corpus.hypotheses.org/271)”, *Canon y corpus. Sobre el concepto de clásicos en la literatura*, Hypotheses. Centre for Open Electronic Publishing (Cléo), 29.07.2016.

- Losada Palenzuela, J.L., “[Named Entities. Encoding Names, Persons, Places and Dates](http://editio.github.io/presentations/named-entities.html)”, 2019.

- Losada Palenzuela, J.L. [Marginal annotations in books.
Interpretation, encoding, publication](http://editio.github.io/slides/marginalia-en), 2016.

- Pérez Priego M.A., *La edición de textos*, Madrid, Editorial Síntesis, 1997.

- Sahle P. et alii, [*Criterios para la reseña de ediciones digitales académicas (EDA)*](http://www.i-d-e.de/publikationen/weitereschriften/criterios-version-1-1/), Institut für Dokumentologie und Editorik, version 1.1   

- Spence P., "[Edición académica en la era digital: modelos, difusión y proceso de investigación](http://revistes.uab.cat/anuariolopedevega/article/view/v20-spence/pdf)", *Anuario Lope de Vega*, 20, 2014, pp. 47-83.

- Schreibman S., Siemens R., Unsworth J., [*A Companion to Digital Humanities*](http://www.digitalhumanities.org/companion), Oxford,  Blackwell, 2004.

- Siemens R, Schreibman S. (ed.), *[A Companion to Digital Literary Studies](http://www.digitalhumanities.org/companionDLS)*, Oxford, Blackwell, 2008.

- TEI Consortium. P5: [Guidelines for Electronic Text Encoding and Interchange](http://www.tei-c.org/release/doc/tei-p5-doc/en/html).

Más referencias y páginas con diversos materiales se encuentran enlazadas en las presentaciones correspondientes.

### Materiales

Se irán añadiendo en este repositorio o enlazando los materiales con los que trabajaremos.

· Getting started with oXygen (Burnard L.): [ejercicio práctico](http://tei.it.ox.ac.uk/Talks/2014-07-dhoxss-tei/Exercises/ex-1-oxygen.pdf)

1. [Ejercicio de codificación de un soneto](https://github.com/editio/TEI-Workshop/tree/master/materials/Exercise-01-Lope-Soneto).
2. [Ejercicio de normalización](https://github.com/editio/TEI-Workshop/tree/master/materials/Exercise-02-Lope-Soneto-Normalization).
3. [Ejercicio de codificación de variantes](https://github.com/editio/TEI-Workshop/tree/master/materials/Exercise-03-Lope-Readings).
4. Ejercicio de codificación de nombres y lugares.
5. [Ejercicio de codificación de un soneto acróstico (<i>rendition</i>)](https://github.com/editio/TEI-Workshop/tree/master/materials/Exercise-05-Soneto-Acrostico).
6. Enlace a *[El Discreto](http://nbn-resolving.de/urn:nbn:de:hebis:30-1129898)*, Amsterdam, 1665.  
    - [Ejemplo](http://editio.github.io/manual/p-ej/discreto-estructura.html) del análisis de su estructura

### Programa

Usaremos el editor (de pago) [oXygen XML Editor Version 17.1](https://www.oxygenxml.com/xml_editor/software_archive_editor_eol.html) para codificar los textos.  

En realidad es posible editar XML con cualquier editor de texto plano, como los instalados por defecto en algunos ordenadores: TextEdit (Mac) o Notepad (Windows). Otros editores avanzados como [Notepad++](https://notepad-plus-plus.org) (Windows) o [Sublime](https://www.sublimetext.com) (Mac, Windows, Linux) ayudan en la representación visual, pero carecen de ciertas funciones que facilitan la codificación de XML/TEI. A continuación apunto otros dos editores avanzados de código que pueden (una vez instalados algunos extras) servirnos (a nosotros) como sustitutos gratuitos a oXygen.


#### Atom


[Atom](https://atom.io) (Mac, Windows, Linux). Para tener funciones similares (autocompletado, validación contra un esquema, sugerencias de errores, transformación) se deben tener instalados los siguientes *packages* (pueden instalarse desde la aplicación):

- [linter-autocomplete-jing](https://github.com/aerhard/linter-autocomplete-jing)
- [tei-framework](https://atom.io/packages/tei-framework)
- [linter](https://atom.io/packages/linter)
- [linter-ui-default](https://atom.io/packages/linter-ui-default)
- [atom-xsltransform](https://atom.io/packages/atom-xsltransform) * Necesita descargar saxon

Otros paquetes opcionales

- [atom-beautify](https://atom.io/packages/atom-beautify)
- [atom-wrap-in-tag](https://atom.io/packages/atom-wrap-in-tag)
- [double-tag](https://atom.io/packages/double-tag)

#### Visual Studio Code

[Visual Studio Code](https://code.visualstudio.com) (Mac, Windows, Linux). Para añadir las funciones de validación de esquema, lenguaje de consulta xpath, transformación con xslt se deben instalar las siguientes extensiones (pueden instalarse desde la aplicación):

-[Scholarly XML](https://marketplace.visualstudio.com/items?itemName=raffazizzi.sxml)

-[XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)

-[xslt-transform](https://marketplace.visualstudio.com/items?itemName=SvenAGN.xslt-transform) * Necesita descargar saxon

### Evaluación

Se basará en un [test de competencias generales](https://forms.gle/1mka2ZL5d492CAxe7) y en el proyecto individual de edición (modelo, transcripción y codificación)
