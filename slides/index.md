---
marp: true
title: Criptografía - Índice
paginate: true
footer: '[Inicio](index.html)'
headingDivider: 2
theme: marp-viu
---

<style>
    /* You can add custom style here. VSCode supports this.
    Other editor might need these custom code in
    the YAML header: section: | */
</style>

# Criptografía y autenticación
<!-- _class: first-slide -->

**Presentación**

Juan Vera del Campo - <juan.vera@professor.universidadviu.com>


## Temario
<!-- _class: cool-list smaller-font -->

1. [Conceptos básicos](01-conceptos.html)
    - Anexo: [Glosario](A1-glosario.html)
1. [Sistemas de cifrado](02-cifrado.html)
1. [Funciones de hash y Firma digital](03-hashes.html)
1. [TLS y Public Key Infrastructure](04-pki.html)
    - Anexo: [TLS en detalle](A2-protocolos.html)
1. [Sistemas de autenticación](05-autenticacion.html)
1. *Temas extras*
    - [Business Email Compromise](06-bec.html)
    - [Anonimato](07-anonimato.html)

# Presentación
<!-- _class: lead -->

## Sobre mí

![bg left:45%](images/juanvi.jpg)

Dr. Juan Vera (Juanvi)

<juan.vera@professor.universidadviu.com>

Intereses:

- DFIR: Análisis forense e *Incident Response*
- Miembro del Cyber Incident Response Team de [Valeo](https://es.wikipedia.org/wiki/Valeo)
- Cualquier cosa que vuele

## Intrucciones de uso de las transparencias
<!-- _class: smaller-font -->

Versión más actualizada:

- Acceso directo HTML: <http://juanvvc.github.io/crypto2>
    - Puedes pulsar `p` para ver las notas de presentación
    - Con "Inicio" (en pie de cada transparencia) puedes venir a esta presentación, con el índice global de contenidos
    - Puedes "Imprimir a PDF" usando Chrome para tener las transparencias en PDF
- Código Markdown: <https://github.com/juanvvc/crypto2>

Durante el estudio personal es muy recomendable seguir los enlaces que aparecen en las transparencias para completar el tema.

[![Licencia de Creative Commons](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/) Esta obra esta sujeta a una licencia de [Atribución 4.0 Internacional de Creative Commons](http://creativecommons.org/licenses/by/4.0/)

## Instrucciones de uso de las actividades
<!-- _class: with-warning smaller-font -->

Los ejercicios son notebook de Google Colab:

1. Después de los temas 2, 3 y 5 se incluirá el enlace a Google Colab en la zona de Actividades de la asignatura
1. Comandos básicos:
    - INTRO: edita línea actual
    - SHIFT+INTRO: ejecuta línea actual
1. Las actividades deben resolverse individualmente
1. Aunque haya código, no es necesario saber programar: son preguntas de texto libre

**Presenta las actividades como PDF: imprimir a PDF**

<!-- Las actividades refuerzan el contenido de las clases e incluyen información adicional -->

## Evaluación
<!-- _class: smaller-font -->

- Puntuación. Dos partes:
    - 50% examen
    - 50% actividades
- Son tres actividades en total, se recomienda realizarlas después de los temas 2, 3 y 5
    - No es  necesario superar las actividades individuales, solo que **la media de todos las actividades sea superior a 5**
    - Las actividades no presentados se puntúan como 0
    - Se pueden presentar las actividades hasta el día del examen correspondiente
- Es necesario superar con nota media de 5 **cada parte por separado**
- En segunda convocatoria, se mantiene la nota de aquella parte que fue superada en primera convocatoria

## Conocimientos recomendables

- Álgebra básica, probabilidad
- Conocimientos básicos de programación. Los ejemplos se presentarán en Python, pero no se pedirá programar nada. Será suficiente con poder entenderlos.
- Conocimientos básicos de redes: cómo funciona Internet.

## Bibliografía
<!-- _class: smaller-font -->

- Del profesor: <https://juanvvc.github.io/crypto2/>
- "[*A Graduate Course in Applied Cryptography*](http://toc.cryptobook.us/)".  Dan Boneh   and   Victor Shoup. Con vídeos en:
    - <https://crypto.stanford.edu/~dabo/courses/OnlineCrypto/>
    - https://www.coursera.org/learn/crypto
    - https://www.coursera.org/learn/crypto2
    - https://www.coursera.org/learn/cryptography
- "[*The Joy of Cryptography*](https://joyofcryptography.com/)" de Mike Rosulek, 2021
- "[*A Course in Cryptography*](https://www.cs.cornell.edu/courses/cs4830/2010fa/lecnotes.pdf)" Rafael Pass & Abhi Shelat. Más ligero que el anterior.
- "[*Handbook of Applied Cryptography*](http://cacr.uwaterloo.ca/hac/)" Alfred J. Menezes. Un clásico para conceptos fundamentales.
- "A Course in Cryptography" Heiko Knospe.
- "Criptografía Ofensiva. Atacando y defendiendo organizaciones". Dr. Alfonso Muñoz.

---
<!-- _class: center -->

Continúa en: [Principios básicos](01-conceptos.html)

# ¡Gracias!
<!-- _class: last-slide -->
