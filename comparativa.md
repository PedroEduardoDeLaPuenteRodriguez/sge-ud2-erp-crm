# Usuario git

PedroEduardoDeLaPuenteRodriguez

# Empresa

10-Organización de eventos "Momentos Corporate"

# Palabra del dia

Compañero

# Software libre, código abierto y software propietario

No todo el software funciona de la misma manera. Una diferencia importante es **qué podemos hacer con el programa** y **qué derechos nos da su licencia**.

## 1. Software libre (FSF)

La **Free Software Foundation (FSF)** considera que un programa es libre cuando respeta las libertades de sus usuarios.

En general, podemos:

* Usar el programa para cualquier propósito.
* Ver cómo funciona.
* Modificarlo.
* Compartir copias.
* Compartir nuestras modificaciones.

Por ejemplo, si un programa tiene una licencia libre, podemos estudiarlo y adaptarlo a nuestras necesidades.

> **Software libre = libertad para usar, estudiar, modificar y compartir.**

---

## 2. Código abierto (Open Source / OSI)

El **código abierto** es un concepto promovido por la **Open Source Initiative (OSI)**.

La idea es que el código fuente esté disponible y que la licencia permita cosas como:

* Ver el código.
* Modificarlo.
* Compartirlo.
* Crear versiones modificadas.

En la práctica, **software libre y código abierto son muy parecidos** y muchas veces se refieren al mismo software.

La diferencia principal está en el enfoque:

* **FSF:** pone el foco en las libertades del usuario.
* **OSI:** pone el foco en las condiciones que debe cumplir una licencia para considerarse de código abierto.

---

## 3. Software propietario

El software propietario es aquel en el que el creador o la empresa mantiene el control sobre el programa.

Normalmente:

* No podemos ver el código fuente.
* No podemos modificarlo libremente.
* No podemos copiarlo o distribuirlo libremente.
* Tenemos que aceptar las condiciones de la licencia.

Ejemplos habituales son muchos programas comerciales como Microsoft Office, Adobe Photoshop o algunos videojuegos.

> **Software propietario = el creador decide qué podemos hacer con el programa.**

---

## 4. ¿Software libre significa que es gratis?

**No.**

"Libre" significa **libertad**, no necesariamente "gratis".

Por ejemplo, una empresa podría cobrar 20 € por una copia de un programa libre. Si la licencia lo permite, el comprador podría tener derecho a:

* Estudiar el código.
* Modificarlo.
* Compartirlo.
* Crear una versión modificada.

Por otro lado, un programa puede ser **gratis pero no libre**.

Por ejemplo:

> Un programa puede costar 0 € y aun así no permitirnos ver su código, modificarlo o compartirlo.

Por eso es importante distinguir:

| Concepto        | Significado                                                |
| --------------- | ---------------------------------------------------------- |
| **Gratis**      | No tienes que pagar para obtenerlo.                        |
| **Libre**       | Tienes determinadas libertades sobre el software.          |
| **Propietario** | El propietario limita lo que puedes hacer con el software. |

---

## 5. Community vs Enterprise

Muchos programas tienen diferentes ediciones, por ejemplo:

* **Community**
* **Enterprise**

No son tipos de licencia universales. Cada empresa puede definirlas de una manera diferente.

### Community

Normalmente está pensada para:

* Usuarios individuales.
* Estudiantes.
* Desarrolladores.
* Proyectos pequeños.
* Personas que quieren probar o utilizar el programa.

Puede ser gratuita y tener las funciones principales del programa.

El soporte suele ser principalmente mediante:

* Documentación.
* Foros.
* Comunidad.

### Enterprise

Normalmente está pensada para empresas y organizaciones grandes.

Puede incluir funciones adicionales como:

* Seguridad avanzada.
* Administración de usuarios.
* Integración con otros sistemas.
* Herramientas para grandes equipos.
* Soporte técnico profesional.
* Actualizaciones o servicios adicionales.
* Acuerdos de nivel de servicio (SLA).

Normalmente tiene algún tipo de coste comercial.

# Fe de erratas

## 1. Licencia de ERPNext

En el PDF aparece:

> "Versión de código abierto bajo licencia LGPLv3"

Este dato es **incorrecto**. ERPNext utiliza la licencia **GNU GPLv3**, no LGPLv3.

### Corrección

```text
ERPNext
- Licencia: GNU GPLv3
- Servidor: Python
- Base de datos: MariaDB
- Código disponible públicamente
```

**Fuente:** [Frappe - License and Trademark](https://docs.frappe.io/legal/others/license-and-trademark)

---

## 2. Versión de ERPNext

El PDF indica:

> "Versión actual: 15"

Este dato puede considerarse **desactualizado**, ya que las versiones del software cambian con el tiempo. Además, indicar "versión actual" sin especificar una fecha puede hacer que el documento quede obsoleto.

### Corrección

En lugar de indicar una versión como si fuera permanente, sería mejor escribir:

```text
- Versión: consultar la versión estable actual en la documentación oficial de ERPNext.
```

De esta manera, el documento no queda desactualizado cuando aparece una nueva versión.

**Fuente:** [ERPNext - Documentación oficial](https://docs.frappe.io/erpnext)

---

## 3. Licencia de Odoo Enterprise

El PDF indica:

> "Versión comunitaria (LGPLv3)"
> "Versión empresarial comercial"

La información es demasiado general. Odoo Community utiliza **LGPLv3**, pero Odoo Enterprise utiliza una licencia diferente denominada **Odoo Enterprise Edition License v1.0**.

### Corrección

```text
Odoo
- Community: código abierto bajo licencia LGPLv3.
- Enterprise: utiliza la Odoo Enterprise Edition License v1.0
  y requiere una suscripción válida.
```

La edición Enterprise también puede incluir funciones, soporte, actualizaciones y servicios adicionales dependiendo del plan contratado.

**Fuente:** [Odoo - Licencias](https://www.odoo.com/documentation/17.0/legal/licenses.html)

## Conclusión

Los principales errores o datos desactualizados encontrados son:

1. **ERPNext no utiliza LGPLv3**, sino **GNU GPLv3**.
2. La afirmación **"Versión actual: 15"** de ERPNext puede quedar desactualizada y debería indicarse con una fecha o sustituirse por una referencia a la versión actual.
3. **Odoo Enterprise no utiliza simplemente una "licencia comercial" genérica**; utiliza la **Odoo Enterprise Edition License v1.0**.

