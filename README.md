
> [!IMPORTANT]  
> 2024: este curso está ya integrado en https://github.com/Juanvvc/crypto Este repositorio no seguirá actualizándose.


# Criptografía y autenticación

Este curso es una continuación del curso "Introducción a la criptografía", aunque no asume que los alumnos han realizado el otro curso primero. Puedes encontrar las transparencias del primer curso en 
[juanvvc.github.io/crypto/slides](https://juanvvc.github.io/crypto/slides/index.html),

Las transparencias de este curso están en
[juanvvc.github.io/crypto2/slides](https://juanvvc.github.io/crypto2/slides/index.html),
pero puedes acceder directamente a cada capítulo seleccionando los enlaces en
el apartado "Contenido".

## Contenido

- [Introducción](https://juanvvc.github.io/crypto2/index.html)
- [Conceptos básicos](https://juanvvc.github.io/crypto2/01-conceptos.html)
    - [Anexo: glosario](https://juanvvc.github.io/crypto2/A1-glosario.html)
- [Sistemas de cifrado](https://juanvvc.github.io/crypto2/02-cifrado.html)
- [Hashes y firma electrónica](https://juanvvc.github.io/crypto2/03-hashes.html)
- [TLS y Public Key Infrastructure](https://juanvvc.github.io/crypto2/04-pki.html)
    - [Anexo: TLS en detalle](https://juanvvc.github.io/crypto2/A1-glosario.html)
- [Sistemas de autenticación](https://juanvvc.github.io/crypto2/05-autenticacion.html)
- [Business Email Compromise](https://juanvvc.github.io/crypto2/06-bec.html)
- [Comunicaciones anónimas](https://juanvvc.github.io/crypto2/07-anonimato.html)

Puedes crear la versión PDF de las transparencias "imprimiendo a PDF" en Google Chrome.

## Descarga local

Aunque lo más recomendable es acceder a la versión en línea para ver siempre la
versión actualizada, si quieres puedes descargarte las transparencias para
visualizarlas fuera de línea. Simplemente aprieta el botón `Download ZIP` de
arriba.

O si tienes cuenta en GitHub puedes simplemente un `fork` (botón de arriba a la
derecha), aunque no las voy a borrar a medio plazo, con lo que si simplemente
marcas con una estrella tendrás un recordatorio en tu cuenta de donde residen
para cuando las necesites.

O también, puedes clonar el proyecto en tu disco duro local (necesitas un
cliente `git`):

```bash
$ git clone git@github.com:juanvvc/crypto.git
```

De esta manera tienes una copia local que siempre puedes mantener al día con:

```bash
$ git pull
```            

Puedes crear las transparencias con:

```bash
# Si no tienes marp instalado, ejecuta esto solo una vez
npm install @marp-team/marp-cli

# Para crear las transparencias en el directorio build
make

# Alternativamente, para crear PDFs en el directorio build
make pdfs
```

# Notas de presentación

Puedes acceder a las notas de presentación, que probablemente contengan
información interesante y extendida, pulsando la tecla `P`

# Licencia

Esta obra esta sujeta a una licencia de [Attribution-ShareAlike 4.0
International (CC BY-SA 4.0) ](https://creativecommons.org/licenses/by-sa/4.0/)

[![Licencia de Creative
Commons](https://licensebuttons.net/l/by-sa/3.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

Copyright © 2020-2023 [Juan Vera del Campo](https://github.com/juanvvc)

