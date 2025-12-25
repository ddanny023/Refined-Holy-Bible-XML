# Refined-Holy-Bible-XML

## English Overview
This repository provides refined XML versions of the Bible in multiple languages.  
It builds upon the [Holy-Bible-XML-Format](https://github.com/Beblia/Holy-Bible-XML-Format/tree/master) project, adding explicit book names to the `<book>` tag for better readability and usability.

### 🔄 Improvements over the original repository
**Original format:**
```xml
<book number="1">
```

**Refined format:**
```xml
<book number="1" name="Genesis">
```
Each book now includes a `name` attribute with the localized title according to the language/version.

### 🌍 Features
- **200+ languages** supported (aligned with the original project).
- **1000+ Bible versions** available.
- Enhanced XML structure for easier parsing and integration.
- Ideal for apps, research, and multilingual projects.

### 📂 Repository Structure
- `/xml/` → Contains refined XML files per language/version.
- Each file follows the schema with `<book number="X" name="LocalizedName">`.

### 🚀 Usage
You can use these XML files in:
- Bible apps and study tools.
- Linguistic and translation research.
- Data parsing and text analysis projects.

### 🤝 Contribution
Contributions are welcome!
- Add new languages or versions.
- Improve book name mappings.
- Report inconsistencies.

### 📜 License
This repository follows the same licensing approach as the original project.  
Please check individual files for specific copyright notices.

---

## 🇪🇸 Descripción en Español
Este repositorio ofrece versiones refinadas de la Biblia en XML en múltiples idiomas.  
Se basa en el proyecto [Holy-Bible-XML-Format](https://github.com/Beblia/Holy-Bible-XML-Format/tree/master), añadiendo nombres explícitos de los libros en la etiqueta `<book>` para mayor claridad y facilidad de uso.

### 🔄 Mejoras respecto al repositorio original
**Formato original:**
```xml
<book number="1">
```

**Formato refinado:**
```xml
<book number="1" name="Génesis">
```
Cada libro ahora incluye un atributo `name` con el título localizado según el idioma/versión.

### 🌍 Características
- Más de **200 idiomas** soportados (en línea con el proyecto original).
- Más de **1000 versiones** de la Biblia disponibles.
- Estructura XML mejorada para facilitar el análisis y la integración.
- Ideal para aplicaciones, investigación y proyectos multilingües.

### 📂 Estructura del repositorio
- `/xml/` → Contiene los archivos XML refinados por idioma/versión.
- Cada archivo sigue el esquema `<book number="X" name="NombreLocalizado">`.

### 🚀 Uso
Puedes usar estos archivos XML en:
- Aplicaciones y herramientas de estudio bíblico.
- Investigación lingüística y de traducción.
- Proyectos de análisis de datos y texto.

### 🤝 Contribución
¡Las contribuciones son bienvenidas!
- Añadir nuevos idiomas o versiones.
- Mejorar los mapeos de nombres de libros.
- Reportar inconsistencias.

### 📜 Licencia
Este repositorio sigue el mismo esquema de licencias que el proyecto original.  
Por favor revisa los archivos individuales para notas específicas de copyright.
