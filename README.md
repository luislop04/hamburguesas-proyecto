# Sistema de Inventario para Negocio de Hamburguesas

## 📌 Descripción
Este proyecto tiene como objetivo automatizar y mejorar el control de inventario de un pequeño negocio de hamburguesas. A través de una aplicación desarrollada en Java, se busca simplificar la gestión de productos, ventas, y reposición de insumos.

## ❗ Problema identificado
El emprendimiento presentaba dificultades en el control de insumos, lo que provocaba desabasto o exceso de productos. No había registros claros de entradas, salidas ni alertas de stock mínimo.

## ✅ Solución propuesta
Se desarrolló un sistema en Java con interfaz básica, control de productos e integración con pruebas automatizadas (JUnit), gestionado mediante GitHub y Trello. Se usa integración continua (CI) con GitHub Actions.

## 🧱 Arquitectura
- Aplicación Java
- Repositorio en GitHub
- Flujo de desarrollo con ramas (`develop`, `master`, `feature/*`)
- CI/CD: GitHub Actions
- Trello para gestión de tareas y etapas (Beta / GA)

## 📚 Tabla de Contenidos
- [Descripción](#-descripción)
- [Problema identificado](#-problema-identificado)
- [Solución propuesta](#-solución-propuesta)
- [Arquitectura](#-arquitectura)
- [Requerimientos](#-requerimientos)
- [Instalación](#-instalación)
- [Configuración](#-configuración)
- [Uso](#-uso)
- [Contribución](#-contribución)
- [Roadmap](#-roadmap)
- [Producto](#-producto)

## ⚙️ Requerimientos
- Java: 17 o superior
- IDE recomendada: NetBeans, IntelliJ o VS Code
- Librerías: JUnit (para pruebas)
- CI/CD: GitHub Actions
- Servidor web opcional: Heroku o local (Tomcat si se usa WAR)
- Archivos: JAR ejecutable

## 🛠️ Instalación

### Ambiente de desarrollo:
1. Instala Java 17 o superior
2. Descarga NetBeans o IntelliJ IDEA
3. Clona el repositorio con:
```bash
git clone https://github.com/luislop04/hamburguesas-proyecto.git
```
4. Abre el proyecto en tu IDE

### Pruebas manuales:
1. Abre el paquete `test`
2. Ejecuta las clases de prueba

### Producción:
- Ejecuta con: `java -jar hamburguesas.jar`
- O súbelo a Heroku como repo de GitHub

## ⚙️ Configuración

- `src/`: Código fuente
- `test/`: Pruebas con JUnit
- `.github/workflows/`: GitHub Actions
- `README.md`: Documentación

No se requieren archivos externos de configuración.

## 👤 Uso

### Usuario final:
- Abrir la app
- Agregar o consultar productos
- Generar alertas de stock

### Administrador:
- Subir nuevas versiones
- Verificar pruebas en Actions
- Gestionar ramas y PRs

## 🤝 Contribución

1. Clona el repo:
```bash
git clone https://github.com/luislop04/hamburguesas-proyecto.git
```
2. Crea una rama:
```bash
git checkout -b feature-x
```
3. Haz cambios y súbelos
4. Abre un Pull Request a `develop`
5. Espera el merge

## 🛣️ Roadmap
- Agregar base de datos (SQLite o MySQL)
- Mejorar interfaz gráfica
- Subida a Heroku completa
- Validaciones más robustas

## 📦 Producto
- Repositorio: https://github.com/luislop04/hamburguesas-proyecto
- Video demo: [pendiente]
- Archivo JAR/WAR subido al repo
- Pruebas en GitHub Actions validadas
