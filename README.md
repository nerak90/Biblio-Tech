📚 Biblio Tech. 

🎯 Descripción del Proyecto

La Biblio Tech  es una aplicación de consola desarrollada en Java que permite a los usuarios explorar, buscar y gestionar una biblioteca personal de libros clásicos de dominio público. La aplicación consume la API REST de Gutendex (Project Gutenberg) para acceder a más de 70,000 obras literarias gratuitas.

 ✨ Características Principales

  🔍 **Búsqueda Inteligente**
- Búsqueda por título con coincidencias parciales
- Filtrado por idiomas (Español, Inglés, Francés, Alemán, Italiano)
- Consulta de libros más populares basada en descargas

  💾 **Gestión de Biblioteca Personal**
- Almacenamiento local en base de datos H2
- Consulta de libros guardados
- Búsqueda por autor en la colección personal
- Estadísticas detalladas de la biblioteca

  🎨 **Interfaz de Usuario Amigable**
- Menú interactivo con 6 opciones principales
- Formato visual atractivo con caracteres Unicode
- Mensajes informativos y manejo de errores
- Navegación intuitiva y fluida

  🛠️ Tecnologías Utilizadas

   **Backend**
- **Java 11+**: Lenguaje de programación principal
- **Maven**: Gestión de dependencias y construcción del proyecto
- **Jackson**: Procesamiento y parseo de JSON
- **Apache HttpClient**: Comunicación HTTP con APIs REST

   **Base de Datos**
- **H2 Database**: Base de datos en memoria para persistencia
- **JDBC**: Conectividad y operaciones de base de datos
- **SQL**: Consultas optimizadas con PreparedStatements

   **Arquitectura**
- **Patrón MVC**: Separación clara de responsabilidades
- **Data Access Object (DAO)**: Abstracción del acceso a datos
- **Service Layer**: Lógica de negocio centralizada
- **Domain Models**: Representación de entidades del negocio

   🌟 Funcionalidades Implementadas

 1. **Búsqueda por Título** 🔍
- Consulta en tiempo real a la API de Gutendex
- Resultados con información completa del libro
- Opción de guardar resultados en biblioteca personal

 2. **Libros Más Populares** 🏆
- Top 10 de libros más descargados
- Ordenamiento por popularidad
- Datos actualizados de la API

 3. **Búsqueda por Idioma** 🌍
- Soporte para múltiples idiomas
- Códigos ISO estándar (es, en, fr, de, it)
- Resultados filtrados y limitados

 4. **Biblioteca Personal** 📖
- Visualización de todos los libros guardados
- Ordenamiento por fecha de guardado
- Información detallada de cada libro

 5. **Búsqueda en Biblioteca** 🔎
- Búsqueda por nombre de autor
- Consultas con coincidencias parciales
- Resultados de la base de datos local

 6. **Panel de Estadísticas** 📊
- Conteo total de libros guardados
- Suma de descargas registradas
- Libro más popular de la colección
- Análisis de datos de la biblioteca


  **Interfaz Visual Atractiva**
```
╔════════════════════════════════════════════════════════════════╗
║                    📚 BIBLIO TECH 📚                    ║
║                                                                ║
║        ¡Bienvenido al mejor catálogo de libros digital!       ║
║           Explora miles de libros de dominio público          ║
╚════════════════════════════════════════════════════════════════╝
```

### **Menú Interactivo**
- Navegación numerada (1-6, 0 para salir)
- Iconos emojis para mejor identificación
- Validación de entradas del usuario
- Mensajes de confirmación y error claros

### **Formato de Resultados**
- Presentación estructurada de información
- Cajas de texto con bordes ASCII
- Información organizada y fácil de leer
- Estadísticas formateadas profesionalmente

## 🔧 Aspectos Técnicos Destacados

### **Manejo de APIs REST**
- Peticiones HTTP GET parametrizadas
- Encoding automático de URLs para caracteres especiales
- Manejo robusto de respuestas y errores de conexión
- Parsing automático de JSON a objetos Java

### **Persistencia de Datos**
- Base de datos H2 embebida auto-configurada
- Transacciones ACID para integridad de datos
- Consultas preparadas para seguridad SQL
- Esquema de base de datos auto-generado

### **Arquitectura Modular**
- Separación clara entre capas (Modelo, Vista, Controlador)
- Bajo acoplamiento entre componentes
- Alta cohesión dentro de cada módulo
- Facilidad para testing y mantenimiento

 📚 Base de Datos de Contenido

 **Project Gutenberg (Gutendex API)**
- **70,000+** libros de dominio público
- Obras clásicas de la literatura mundial
- Múltiples idiomas y formatos
- Datos de popularidad basados en descargas reales

 **Autores Destacados Incluidos**
- William Shakespeare
- Miguel de Cervantes
- Charles Dickens
- Jane Austen
- Arthur Conan Doyle
- Victor Hugo
- Y miles más...

 🎯 Casos de Uso Principales

1. **Estudiante de Literatura**: Busca obras clásicas para investigación académica
2. **Lector Casual**: Descubre libros populares y los guarda para lectura posterior
3. **Bibliotecario**: Gestiona una colección personal de referencias literarias
4. **Investigador**: Analiza estadísticas de popularidad de obras clásicas

 🚀 Instrucciones de Ejecución

 **Requisitos del Sistema**
- Java 11 o superior
- Maven 3.6+
- Conexión a internet (para consultas API)

  **Comando de Ejecución**
```bash
mvn clean compile exec:java -Dexec.mainClass="com.catalogo.CatalogoLibros"
```

  🌟 Valor Agregado

Esta aplicación demuestra competencias en:
- **Desarrollo de software completo** desde la concepción hasta la implementación
- **Integración de sistemas** mediante consumo de APIs externas
- **Gestión de datos** con persistencia local
- **Diseño de interfaces** de usuario intuitivas en consola
- **Aplicación de patrones de diseño** y buenas prácticas de programación
- **Manejo de tecnologías modernas** del ecosistema Java

El proyecto representa una solución completa y funcional que combina aspectos técnicos avanzados con una excelente experiencia de usuario, ideal para demostrar habilidades de desarrollo de software profesional.
