Cartografía y web o por qué tus mapas están MAL
================================================

Diapositivas de nuestra charla en [DrupalVal](http://groups.drupal.org/comunidad-valenciana)
sobre cartgrafía y desarrollo web.

Facilitadores:

- [Pedro-Juan Ferrer](http://twitter.com/vehrka)
- [Jorge Sanz](http://twitter.com/xurxosanz)

## Diapositivas

[Cartografía y web o por qué tus mapas están MAL](http://kcy.me/w5b5)

## Resumen

Cada vez es más habitual que los proyectos web incluyan algún visor de mapas.
Las tecnologías de la información geográfica han entrado de lleno en el mundo
del desarrollo web. Esta charla está enfocada a desarrolladores web que han de
integrar cartografía o servicios de localización en sus proyectos. Como
cartógrafos, trataremos de ofrecer desde nuestro punto de vista lo que
consideramos como conceptos básicos a tener en cuenta a la hora de arrancar un
proyecto de visualización geográfica, os hablaremos de orígenes de datos,
frameworks de web-mapping, servicios de localización y otras herramientas
interesantes.

Nos dedicamos al desarrollo web, nos encanta trabajar con diseñadores y
desarrolladores y nuestro objetivo con esta charla es que conozcáis un poco
más el mundo de la cartografía y la visualización de datos geográficos, hay un
mundo más allá de la API de Google Maps y os lo queremos contar.

## Cómo descargar estas diapositivas

```
git clone https://github.com/geoinquietosvlc/slides-drupalval-cartoweb.git
cd slides-drupalval-cartoweb
git submodules init
git submodules update
```

## Servidor local con autorecarga

Para tener un servidor en local con recarga automática de cambios en las diapositivas
es necesario instalar ``nodejs``, ``npm`` y ejecutar:

```
npm install
```

Y para ejecutar el servidor:


```
grunt server
```