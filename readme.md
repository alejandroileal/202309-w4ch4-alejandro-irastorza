# Week 4 - Challenge 3

## Teléfono React

Aquí tienes la maquetación HTML/CSS de una aplicación, tendrás que programarla en React.

- Se debe poder escribir un número de teléfono clicando en los botones numéricos. La tecla borrar puede borrar el último dígito o borrar el número completo, como prefieras.
- Sólo se verá o el botón Llamar o el botón Colgar, nunca los dos a la vez.
- No se puede introducir un número de más de 9 cifras.
- El botón Llamar sólo se puede pulsar si el número tiene 9 cifras. Cuando tenga 9 cifras el botón debe tener la clase "active".
- El mensaje superior "Llamando..." sólo aparece cuando se pulsa el botón "Llamar" y mientras dure la llamada. Usa la clase "off" para controlar su visibilidad (el elemento HTML correspondiente debe seguir estando, aunque no se vea).
- Al pulsar el botón "Llamar", éste debe desaparecer del DOM y debe aparecer en su lugar el botón "Colgar". El teclado tiene que quedar deshabilitado.
- Al pulsar el botón "Colgar", éste debe desaparecer y debe aparecer en su lugar el botón "Llamar". El teclado tiene que habilitarse. Además, se debe borrar el número de teléfono.
- Si no ocurre nada tras cinco segundos de llamada, ésta se debe colgar automáticamente.

Separa todo en los siguientes componentes:

- Info
- Display
- Actions
  - Action
- Keyboard
  - Key

Entrega también un listado de responsabilidades en el README

- ¿Qué renderiza?
- ¿Qúe interacciones del usuario tiene?
- ¿Qué información recibe y desde donde?

## listado de responsabilidades

#### ¿Qué renderiza?

**Info:** Renderiza la leyenda 'Calling'.
**Display:** Renderiza los números que se van marcando.
**Actions:** Renderiza el div que encasilla las acciones.
**Action:** Renderiza los botones 'Call' y 'Hang'.
**Keyboard:** Renderiza la lista.
**Key:** Renderiza los botones que corresponden al teclado.

#### ¿Qúe interacciones del usuario tiene?

**Info:** Se ejecuta cuando el usuario presiona el botón 'Call'.
**Display:** Cuando el usuario da click.
**Actions:** Cuando se carga la página.
**Action:** Cuando el usuario da click.
**Keyboard:** Cuando se carga la página.
**Key:** Cuando el usuario da click.

#### - ¿Qué información recibe y desde donde?

**Info:** El array de números marcados desde el contexto.
**Display:** Recibe los números de teléfono desde el contexto.
**Actions:** Recibe los componentes de la lista desde el componente action.
**Action:** Recibe los números de teléfono y la variable boolean para determinar el display desde el contexto.
**Keyboard:** Recibe los botones desde el componente key.
**Key:** Recibe los números de teléfono desde el contexto.
