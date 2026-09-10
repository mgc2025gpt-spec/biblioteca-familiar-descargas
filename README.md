# Biblioteca Familiar

Aplicación privada para organizar los libros de una familia desde Windows y
Android. Cada familia crea su propia biblioteca independiente y puede unir sus
dispositivos mediante un código o un QR.

## Descarga sencilla

- [Pack completo para Windows y Android 0.9.0 beta 2](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.2/Biblioteca-Familiar-Pack-Completo.zip)
- [Instalador para Windows 11](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.2/Biblioteca-Familiar-Windows-Instalador.exe)
- [Aplicación para Android](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.2/Biblioteca-Familiar-Android.apk)
- [Código QR para instalar en Android](https://github.com/mgc2025gpt-spec/biblioteca-familiar-descargas/releases/download/v0.9.0-beta.2/QR-Instalar-Android.png)

La opción recomendada es descargar el **pack completo**, abrir el ZIP y leer
`LEEME_PRIMERO.html`. La aplicación permite fotografiar varios libros, revisar
las fichas detectadas, buscar, organizar ubicaciones y exportar listas a Excel o
Word.

La versión 0.9.0 beta 2 busca también una carátula de mejor calidad y datos adicionales
en Open Library cuando la coincidencia del libro es fiable. Antes de guardar se
pueden comparar la portada fotografiada y la de Internet; el recorte original se
conserva siempre como alternativa. Comprueba automáticamente la foto en cuatro
orientaciones, detecta libros de lado o boca abajo y endereza cada recorte. También
permite registrar préstamos por ejemplar, persona y fecha, devoluciones y exportar
esos datos. Acepta hasta 12 fotografías por lote y las procesa en tandas para
evitar que el reconocimiento se bloquee con estanterías grandes. Si hay una
sesión móvil o de Windows caducada, la aplicación intenta renovarla sin volver a
asociar silenciosamente un dispositivo que haya sido revocado.

Esta beta añade una base SQLite independiente en cada instalación, sincronización
con control de cambios concurrentes, caché local de portadas, aviso si falla el
guardado y mejor tratamiento de lotes en los que una fotografía falla. Se ha
verificado el instalador y arranque de Windows y la instalación, firma y arranque
de Android 15 en un dispositivo limpio automatizado. También recupera
automáticamente respuestas de reconocimiento mal formadas y permite empezar una
biblioteca nueva y vacía desde Ajustes.

## Sincronización familiar

En el primer dispositivo, abre **Ajustes > Sincronización familiar > Crear
biblioteca familiar**. En los demás dispositivos usa **Unirse a una biblioteca**
y escribe el mismo código o escanea el QR. No compartas ese código fuera de la
familia.

La sincronización es bidireccional: los libros, ubicaciones, ajustes, portadas y
préstamos que se cambien en Android se envían a Windows, y al revés. En **Ajustes**
puedes elegir cada cuánto comprobar cambios (1, 5, 15, 30 o 60 minutos) y usar
**Sincronizar ahora** cuando quieras. El intervalo se guarda en la biblioteca;
al volver a abrir la aplicación se pone al día automáticamente. La sincronización
necesita conexión a Internet en ese momento, pero la biblioteca sigue disponible
sin conexión y los cambios pendientes se reintentan después.

Al instalar 0.9.0 beta 2 sobre una versión anterior firmada se conserva la
biblioteca local. No desinstales la aplicación ni borres sus datos.

Si quieres empezar desde cero, no es necesario reinstalar. Abre **Ajustes >
Empezar una biblioteca nueva y vacía**, confirma y crea la nueva familia primero
en Windows. Después une Android con el código o QR mostrado por Windows.

## Actualización desde Android 0.4.2

Antes de cambiar desde Android 0.4.2: sincroniza y anota el código familiar. Esa
versión antigua puede requerir una desinstalación única; después instala la beta y
vuelve a unirte con el código. Desde 0.7.x, la actualización es directa y conserva
la biblioteca.

Este repositorio contiene únicamente archivos instalables públicos. No contiene
bibliotecas familiares, fotografías, contraseñas, claves privadas ni el código
fuente del programa.
