Love Arcade Downloads

Repositorio dedicado a la distribución de archivos utilizados por el proyecto.

Los archivos se publican mediante GitHub Releases y pueden ser descargados directamente desde el proyecto principal sin necesidad de navegar manualmente por GitHub.

Purpose

Este repositorio funciona como almacenamiento y distribución de assets independientes del código fuente del proyecto principal.

Puede contener diferentes tipos de archivos, incluyendo:

- APK
- ZIP
- PDF
- Imágenes
- Documentos
- Otros archivos descargables

Repository structure

love-arcade-downloads/
├── README.md
├── CATALOG.md

Los archivos binarios no se almacenan directamente en el repositorio. Se publican como Release Assets.

Asset catalog

Consulta "CATALOG.md" (./CATALOG.md) para ver el listado de archivos disponibles, sus versiones y descripciones.

Naming conventions

Los nombres de los archivos deben ser:

- Descriptivos
- Estables entre versiones cuando sea posible
- Escritos en "kebab-case"
- Sin espacios
- Sin caracteres especiales innecesarios

Ejemplos:

app.apk
resources.zip
user-guide.pdf
project-assets.zip

Evitar:

Mi Archivo Final FINAL 2.zip
app nueva.apk
archivo definitivo!!.zip

Usage

Este repositorio no contiene el código fuente del proyecto principal.

Su función es proporcionar una ubicación centralizada para los archivos que deben estar disponibles para descarga.

---

Source project: "LilithNML/love-arcade"

Distribution repository: "LilithNML/love-arcade-downloads"
