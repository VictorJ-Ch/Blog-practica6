---
layout: base.njk
title: VICTORJ-CH の BLOG
---

# {{ title }}


Este es un blog hecho como práctica 6, para la materia de leguajes interpretativos, hecho por Víctor Javier Chavarría Martínez, plantilla dada por  John Mircha.

[Acerca de mi]({{ '/acerca' | url }})

## Podes leer acerca de:

### Animes

{% for anime in collections.anime %}

- [{{anime.data.title}}]({{ anime.url | url }})

{% endfor %}

### Videojuegos

{% for videogames in collections.videogames %}

- [{{videogames.data.title}}]({{ videogames.url | url }})

{% endfor %}

### Animales

{% for animales in collections.animales %}

- [{{animales.data.title}}]({{ animales.url | url }})

{% endfor %}