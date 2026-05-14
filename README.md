# Libro Digital de Programación Orientada a Objetos - UPeU

Este repositorio publica el curso de Programación Orientada a Objetos como libro digital en Markdown. El material está organizado por unidades, con sesiones alineadas al desarrollo incremental de un sistema de escritorio en Java usando IntelliJ IDEA.

## Qué encontrará el estudiante

- El sílabo actualizado del curso.
- Tres unidades organizadas por productos parciales.
- Dieciséis sesiones teórico-prácticas en formato de lectura y guía de trabajo.
- Un taller complementario para reforzar el modelado orientado a objetos.

## Enfoque del curso

El curso está centrado en construir un sistema de ventas con enfoque orientado a objetos. El recorrido formativo parte del modelado del dominio, continúa con persistencia y GUI, y culmina con un proyecto integrador.

La herramienta base de trabajo es IntelliJ IDEA. El libro no depende de cuadernos Jupyter ni de ejecución embebida en el sitio.

## Ruta de aprendizaje

| Unidad | Sesiones | Producto esperado |
|---|---:|---|
| Fundamentos de POO | 1-6 | Aplicación funcional en memoria con clases, relaciones y colecciones. |
| GUI y base de datos | 7-12 | Aplicación de escritorio con JavaFX, DAO, JDBC y SQLite. |
| Proyecto integrador | 13-16 | Sistema completo documentado, probado y sustentado. |

## Ejecución local

### Con Docker

```powershell
docker compose up
```

Luego abra:

```text
http://127.0.0.1:8002/
```

### Con Python local

```powershell
python -m pip install mkdocs mkdocs-material pymdown-extensions
mkdocs serve
```

## Generación del sitio

```powershell
docker compose run --rm mkdocs mkdocs build
```

o bien:

```powershell
mkdocs build
```

## Estructura del libro

- Inicio y presentación del curso.
- Sílabo de POO.
- Unidad 1: fundamentos de modelado y programación orientada a objetos.
- Unidad 2: arquitectura, persistencia y GUI en Java.
- Unidad 3: proyecto integrador, documentación y evaluación final.
- Taller complementario.