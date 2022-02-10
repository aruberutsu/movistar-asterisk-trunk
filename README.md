asterisk-movistar
#################

Configuración de Asterisk con driver PJSIP para usarlo con un trunk de Movistar FTTH.

# Uso

 * Instalar Asterisk (Debian o Ubuntu lo llevan en su paquetería)
 * Añadir a /etc/asterisk/pjsip.conf el contenido de pjsip.conf de este repositorio, reemplazando "999222345" por vuestro número de teléfono fijo.
 * Añadir a /etc/asterisk/extensions.conf el contenido de extensions.conf de este repositorio.

En una instalación nueva, de forma opcional, añadir también a /etc/asterisk/pjsip.conf el contenido de pjsip.conf.extra, que añadiría tres extensiones locales, y el contenido del contexto [default] de extensions.conf.extra al /etc/asterisk/extensions.conf. Eso dejaría de primeras un sistema ya funcional.

# Nota
Esta configuración lleva funcionando varios años en mi sistema, pero se oferece sin garantía de ningún tipo. Si has de llamar a bomberos y la llamada no sale, no me busques.

# Licencia
[CC0](https://creativecommons.org/publicdomain/zero/1.0/)
