# Biblioteca Familiar — beta 9

Organiza los libros de tu familia en Windows y Android: fotografías, catálogo, ubicaciones, préstamos y sincronización privada. Es una versión de prueba, gratuita y sin límite comercial de libros. Todavía no está publicada en Google Play ni Microsoft Store.

## Ya tengo la aplicación: actualizar

- [Actualizar Windows](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.9/Biblioteca-Familiar-Windows-Instalador.exe)
- [Actualizar Android](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.9/Biblioteca-Familiar-Android.apk)
- [QR para descargar Android](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.9/QR-Actualizar-Android.png)
- [Huellas SHA-256](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.9/ACTUALIZACION-SHA256.txt)

1. Sincroniza y cierra la aplicación antes de instalar.
2. Abre el instalador encima de la versión anterior. **No desinstales ni borres los datos.**
3. Abre la aplicación y pulsa «Sincronizar ahora». Actualiza todos los dispositivos familiares antes de editar los nuevos campos.

Se conserva la biblioteca local y la conexión familiar. Si aparece un conflicto, revisa qué dispositivo tiene el dato correcto antes de elegir; no vacíes la biblioteca.

Desde esta beta, la aplicación avisa cuando hay una versión posterior y ofrece «Actualizar» o «Más tarde». También puedes buscar actualizaciones en Ajustes. Las versiones anteriores necesitan instalar esta actualización primero para disponer del nuevo aviso.

## Instalación nueva o para unos amigos

[Descargar el pack completo de Windows y Android](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.9/Biblioteca-Familiar-Pack-Completo.zip)

1. Extrae el ZIP y abre `LEEME_PRIMERO.html`.
2. Instala Windows con `Biblioteca-Familiar-Windows-Instalador.exe`, o Android con `Biblioteca-Familiar-Android.apk`.
3. La primera persona elige «Crear una biblioteca familiar».
4. Sus familiares eligen «Unirme a una biblioteca» e introducen el mismo código de invitación.

Cada familia crea una biblioteca independiente. Comparte los instaladores, **no tu código de invitación**: ese código da acceso a tu biblioteca.

En Android, el QR de descarga abre el enlace a la APK; no es el QR para sincronizar una familia. También puedes enviar la APK por el medio que prefieras. El instalador de Windows sigue sin certificado comercial y puede mostrar SmartScreen: verifica la procedencia y no desactives el antivirus. Si Android indica una firma incompatible, solicita ayuda sin desinstalar ni borrar datos.

## Qué mejora esta versión

- Las portadas descargadas se conservan en el dispositivo. Se evitan peticiones repetidas y se limita la descarga simultánea. La primera carga necesita conexión.
- Al cambiar una portada, los demás dispositivos dejan de reutilizar su imagen antigua al sincronizar.
- Tomo/volumen, edición y presentación (por ejemplo, bolsillo) se pueden editar y buscar. Las ediciones y tomos distintos mantienen fichas separadas.
- Los ejemplares con los mismos datos de edición aparecen agrupados con su número y ubicaciones. Si la información es incompleta se mantienen separados para evitar fusiones incorrectas.
- Se mantienen el árbol de ubicaciones movible, confirmación del destino antes de guardar, préstamos, exportaciones y sincronización bidireccional.

## Fotografías: revisar siempre

Acepta hasta 12 fotos por lote y analiza distintas orientaciones. Las fichas son propuestas que debes revisar antes de guardar; títulos, tomos y ediciones no siempre son legibles.

En las pruebas de esta beta, una foto con 12 libros principales devolvió 12 propuestas. Otra foto de una librería muy compacta devolvió 86 propuestas, **pero omitió libros y tuvo lecturas incompletas**. No se promete reconocimiento total. Para estanterías densas, haz una foto por estante, cercana y de frente. Un número editorial de colección no es necesariamente un número de tomo.

## Sincronización y datos

Los cambios viajan entre Windows y Android. Puedes programar la comprobación en Ajustes o pulsar «Sincronizar ahora». Requiere conexión y que la aplicación pueda ejecutarse; no se garantiza actividad continua con el móvil cerrado por el sistema.

Cada instalación guarda su catálogo en SQLite y las portadas descargadas localmente. Actualizar no exige crear otra biblioteca. Borrar los datos o desinstalar sí puede eliminar la copia local: no lo uses para solucionar conflictos.

Este repositorio contiene únicamente descargas e información pública. No contiene bibliotecas familiares, fotografías de usuarios, códigos de invitación, claves privadas ni código fuente.
