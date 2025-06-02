# funcion-mostrar-mensaje

¿Cómo funciona la función? (explicación paso a paso)

La función se llama mostrarMensaje y se activa cuando el usuario hace clic en el botón "ENVIAR" del formulario de adopciones.

Esto es lo que hace paso a paso:
1. Se ejecuta automáticamente al enviar el formulario.
2. Muestra un mensaje (alerta) con el texto: “¡Gracias por tu solicitud! En breve un michi se pondrá en contacto con vos 🐾”
3. Luego del mensaje, la función devuelve true, lo que permite que el formulario se envíe normalmente.

Es decir, el formulario se comporta igual que siempre, pero antes aparece un mensajito simpático para que el usuario sepa que su solicitud fue hecha.

¿Por qué es útil o necesaria para su proyecto? (justificación)

Esta función es útil porque:
1. Mejora la experiencia del usuario, mostrando un agradecimiento al instante.
2. Genera una conexión emocional con la temática del sitio (gatitos).
3. Es una forma muy simple y efectiva de dar respuesta.

En un sitio como el nuestro, donde se busca que la gente adopte gatitos y se sienta bien recibida, este detalle aporta calidez y confianza.

¿Cómo la pensamos y cómo la implementamos? (proceso, ideas, pruebas)

Primero, pensé en qué podía hacer con JavaScript que fuera simple, útil y que se notara.
Como tenía formularios, se me ocurrió agregar un mensaje de agradecimiento al enviarlos.

Me decidi por usar alert() porque:
1. Es algo que ya aprendimos.
2. Es fácil de implementar.
3. Llama la atención del usuario.

Probé con varias formas de hacerlo, pero al principio usába return false; y eso impedía que el formulario se enviara.
Después entendí que sí usaba return true; al final de la función, el mensaje aparecía y el formulario igual se enviaba.

