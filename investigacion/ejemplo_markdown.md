# Guía de ejemplo en Markdown

> Este es un archivo de **ejemplo** que demuestra *encabezados*, **listas**, **tablas**, **enlaces** e **imágenes** en Markdown.

---

## 1. Encabezados

# Título H1
## Título H2
### Título H3
#### Título H4
##### Título H5
###### Título H6

---

## 2. Listas

### 2.1 Lista sin orden
- Elemento A
- Elemento B
  - Sub-elemento B.1
  - Sub-elemento B.2
- Elemento C

### 2.2 Lista numerada
1. Paso uno
2. Paso dos
3. Paso tres
   1. Sub-paso 3.1
   2. Sub-paso 3.2

### 2.3 Lista de tareas (checklist)
- [x] Definir el objetivo
- [x] Crear el archivo
- [ ] Revisar y publicar

---

## 3. Enlaces

### 3.1 Enlace en línea
Visita el **sitio de UNEMI**: <https://www.unemi.edu.ec>

### 3.2 Enlace con texto
Consulta la [documentación de Markdown](https://www.markdownguide.org/) para más detalles.

### 3.3 Enlaces con referencias
Puedes leer sobre [Git](ref-git) y [GitHub](ref-github).  
[ref-git]: https://git-scm.com/ "Sitio oficial de Git"
[ref-github]: https://github.com/ "Repositorio de GitHub"

---

## 4. Imágenes

### 4.1 Imagen remota (URL pública)
![Banner de ejemplo](https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg)

### 4.2 Imagen local (ruta relativa)
> Si subes una imagen a `./images/diagrama.png`, se mostrará así:
![Diagrama del sistema](images_md/diagrama.png "Diagrama del sistema (ruta relativa)")

---

## 5. Tablas

### 5.1 Tabla simple
| Nombre         | Rol                 | Curso                     |
|----------------|---------------------|---------------------------|
| Ana Pineda     | Estudiante          | Estructura de Datos       |
| Luis Andrade   | Estudiante          | Introducción a I. Software|
| M. Rodríguez   | Docente             | Gestión de TI             |

### 5.2 Tabla con alineación
| Alineación Izq | Centrada         | Derecha     |
|:---------------|:----------------:|------------:|
| texto          | medio            |      123.45 |
| más texto      | centrado         |       67.89 |
| final          | aquí             |        0.25 |

> **Nota:** En muchas plataformas, las tablas se renderizan automáticamente. Si necesitas exportar a PDF/Word, revisa el soporte del conversor.

---

## 6. Código y resaltado (extra)
Bloque de código en línea: `print("Hola Markdown")`

Bloque de código con lenguaje:
```python
def saludo(nombre: str) -> str:
    return f"Hola, {nombre}!"
print(saludo("UNEMI"))
```

---

## 7. Citas y separación (extra)
> _“La simplicidad es la máxima sofisticación.”_ — Leonardo da Vinci

---

## 8. Pie de página (extra)
Este documento es un **ejemplo** para cursos de *Ingeniería de Software*. Puedes adaptarlo a tus clases, guías o repositorios.

