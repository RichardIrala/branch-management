# Gestión de branchs

### Pull request

**Pull request normal** => El titulo refiere a lo que se ha hecho en ese branch
**Pull request de un trabajo no terminado.** Vamos a utilizar la terminología WIP => In progress => [WIP] + nombre de la rama y/o descripción de lo que se está haciendo.

```
Ejemplo:

[WIP] hotfix/login-screen
[WIP] feature/news
[WIP] styles/home-screen
[WIP] hotfix/edit-profile-viewmodel
```

### Creación de branchs:

Lo más habitual son estos términos: 
* feature
* hotfix

**_FEATURE:_**

Implica que vamos a desarrollar algo por ejemplo una vista nueva

Ejemplo:

feature/login-screen <= implica que vamos a desarrollar la vista de login por ejemplo.

**_HOTFIX_**

Esta terminología refiere a que vamos a solucionar un bug o algún problema en el código

Ejemplo:

hotfix/login-screen <= implica que vamos a corregir algún error o problema en la vista login

### Otras terminologías que estaría bueno implementar son:
* viewmodel
* test
* styles

**_VIEWMODEL:_**

Si solamente trabajamos en el viewmodel y/o la mayor parte del trabajo a realizar es en el viewmodel de algún componente del FrontEnd entonces utilizamos por ejemplo:

- viewmodel/create-item
- viewmodel/login

Pero... si hubiera un error en un viewmodel cambiamos el termino igualmente a:

- hotfix/create-item-viewmodel
- hotfix/login-viewmodel

**_TEST:_**

* test/login-viewmodel
* test/create-item-viewmodel

**_STYLES:_**

Este está más enfocado en el cambio de estilos. La mayor parte del trabajo en este branch sería enfocado en ello.

* styles/dashboard-screen
* styles/profile-screen
