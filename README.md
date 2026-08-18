# Documentos legales de Ataphro Dev

Este repositorio existe por una razón muy concreta: **Google Play exige que la política de
privacidad esté en una URL pública y accesible sin registro**, y las tiendas comprueban que siga
estándolo.

Publicado con GitHub Pages en <https://ataphrodev.github.io/legal/>.

| Documento | URL |
|---|---|
| Política de privacidad de TactikosHub | <https://ataphrodev.github.io/legal/privacidad.html> |

## Por qué está aquí y no dentro del repositorio de la app

Por dos motivos, y los dos importan:

1. **Publicar la página obliga a que el repositorio sea público.** El de TactikosHub contiene el
   código fuente del producto, y hacerlo público es una decisión de negocio distinta que no hay
   que verse forzado a tomar por un trámite de la tienda.
2. **Una sola copia.** Con el mismo documento en dos repositorios, el día que se corrige uno el
   otro se queda mintiendo. La URL que ve un usuario apunta aquí, así que aquí vive el original.

## Cómo se cambia

Se edita el HTML, se cambia la fecha de «Última actualización» del encabezado y se sube. GitHub
Pages republica solo en un par de minutos.

**El historial de este repositorio es el registro de versiones de la política.** Es lo que permite
demostrar qué decía en una fecha concreta, y por eso los cambios van en commits separados y con un
mensaje que diga qué cambió de fondo.

## Qué obliga a revisar la política

- Que la app empiece a hacer una conexión de red que antes no hacía.
- Que se añada cualquier SDK de terceros (analítica, publicidad, informes de errores).
- Que se habiliten pagos dentro de la aplicación.
- Que se pida un permiso nuevo del sistema: cámara, galería, ubicación, contactos.
- Que se empiece a guardar una categoría de dato que hoy no se guarda.
