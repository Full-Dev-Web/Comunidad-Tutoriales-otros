# Contribuyendo con "Aprendiendo-Javascript"

Para nosotros tú contribución es muy importante, y en pro de mantener un orden en nuestros repos hemos creado este archivo `contributing.md`, para que puedas enviar todos tus aportes. 
Aquí están los lineamientos para poder contribuir.


## Sobre el "branch" o "rama" a utilizar.

En los proyectos de "Aprendiendo-Javascript", tenemos 3 branches, o ramas por defecto: 

- `master`.
- `develop`.
- `gh_pages`.

Te recomendamos nombrar los branches o ramas de tus colaboraciones para "Aprendiendo-Javascript" con el prefijo: `js` seguido por la convención de tú preferencia. A nosotros nos agrada esta:

`<prefijo js>-<palabra "issue">-<numero de issue>-`.

Quedaría algo como esto: `js-issue-14-encuesta`. Pero también es válido algo como esto: `js-issue-20`.

El branch `master` es tratado como "producción", `gh_page` sera la rama de despliegue usando GitHub Pages y `develop` como el de "ci", o "qa", por lo consiguiente, se deben crear branches o ramas individuales, a partír de `develop` para cualquier aporte, luego en el `pull request` se debe especificar que el nuevo cambio será unirá a `develop`.

##### **_IMPORTANTE_**
¡NUNCA! debemos hacer merge a `master` ya que estaríamos haciendo cambios a "PRODUCCION". 

## Formato de Commits
Tenemos una estructura a seguir, para facilitar la validación de tus contribuciones y mantener un buen flujo de trabajo. Los mensajes de commits _deberían_ ser de la siguiente manera: 

````

<Tipo>(<Ámbito>): <Mensaje Corto>
<LINEA EN BLANCO>
<Mensaje Explicativo>

````

 
El Encabezado:  `tipo(ámbito): <Mensaje Corto>` **es obligatorio**, el resto es opcional. Las acciones disponibles, puedes encontarlas en [Acciones](#acciones), un poco más abajo.

Cualquier línea en un mensaje de commit no de ser mayor de 100 caracteres!. Esto permite la fácil lectura de los mensajes tant oen Github como en varias herramientas de git.

#### Ejemplos:
_Commit Corto:_

`(Agrega): Clase Utils para lectura de atributos.`


_*Commit Largo:*_

```
(Agrega): Clase Utils para lectura de atributos.

La clase utils,esta divida en varios métodos para diferentes usos.
Para validar se usan los siguientes métodos.
ValidaPhone.
ValidaIp
ValidaNavegador
ValidaNovias
```


## Pull Requests
Por favor asegurate que tú `pull request` cumpla los siguientes lineamientos:

- Crea un `pull request` individual por cada aporte.
- Sigue las indicaciones dadas en la plantilla de `pulls requests`.
- Usa `title-casing` (AP style).
- Presta mucha atención a tu ortografía.
- Nuevos aportes o mejoras a lo que ya existe, siempre es bienvenido.


## Tipos Acciones
Las acciones son los indicativos primordiales de los cambios que realizamos en un determinado archivo. Con éstas lo que intentamos es saber con una simple lectura que tipo de modificació fué hecha.
Actualmente tenemos estás acciones disponibles: 

- **Agrega**: Usalo para notificar una nueva funcionalidad, o algún comportamiento que antes no estaba.
- **Elimina**: Cuando eliminas alguna funcionalidad, tratamiento o porción de codigo, sin afectar un comportamiento.
- **Modifica**: Al cambiar sustancialmente un comportamiento, funcionalidad o  tratamiento. 
- **Actualiza**: Exclusivamente para documentos informativos, o dependencias utilizadas.
- **Correccion**: Si existe un bug, y es solventado, esta acción es la ideal para avisarlo. 
- **Refactor**: Cuando se hace un cambio de logica, comportamiento o funcionalidad de manera sustancial. 



## Ámbito
El ámbito es el lugar de la aplicación donde se realiza el cambio.

## Mensaje
El mensaje debe contener una descripción clara y concisa del cambio realizado.

- Use tiempo presente imperativo, agrega, no agregado ni agregó.
- No capitalizar la primera letra.
- No coloque punto (.) al final


_Si quieres proponer un nuevo tipo de "Accion", puedes abrir un `issue`, para ello en este [enlace](https://github.com/ngVenezuela/wengy-ven/issues)_

**_¡Importante!: Las contribuciones que no cumpla con las recomendaciones acá expuestas no será aceptadas._**

_Agradecimientos: Comunidad [ngVenezuela](https://github.com/ngVenezuela) por permitirnos usar su [CONTRIBUTING.md](https://github.com/ngVenezuela/wengy-ven/blob/develop/.github/CONTRIBUTING.md) como base para el nuestro. ¡Mil gracias! 😎_