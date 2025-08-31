# Plan de Gestión de Configuración de Software

**Materia:** Ingeniería y Calidad de Software  
**Repositorio:**
**Versión:** 1.0  
**Fecha:** 27/08/2025

---

## 1. Propósito

Este documento define las convenciones de nombres, la estructura de carpetas y las reglas de gestión de configuración para todos los items del curso. Su objetivo es estandarizar cómo se organizan, nombran y versionan documentos, ejercicios, parciales y trabajos prácticos.

---

## 2. Alcance

Incluye:

- Documentos de planificación, clases, parciales, trabajos prácticos y bibliografía.
- Artefactos entregables (diagramas, código, resoluciones, etc.).
- Archivos de soporte necesarios para evaluaciones.

---

## 3. Estructura del Repositorio

```plaintext

ISW_2025_4K3_G7
  /Planificacion
  /Parciales
    /Parcial_<N>
      /Ejercicios
      /Elementos de clase
        /Clase_<N>_<FECHA>
      /Parciales Viejos
      /Resúmenes
  /TrabajosPracticos
    /Practico_<N>
      /Artefactos
  /Bibliografia

```

## 4. Reglas de Nombrado y Ruta

| Tipo de Ítem           | Regla de Nombrado                   | Ruta                                                                          |
| ---------------------- | ----------------------------------- | ----------------------------------------------------------------------------- |
| **Template Parcial**   | `P<N>_TEMPLATE_<Nombre>.pdf`        | `ISW_2025_4K3_G7/Parciales/Parcial_<N>/`                                      |
| **Ejercicio Resuelto** | `P<N>_EJ<N>_<Nombre>.<ext>`         | `ISW_2025_4K3_G7/Parciales/Parcial_<N>/Ejercicios/`                           |
| **Presentación Clase** | `P<N>_C<N>_PRES_<Titulo>.ppt`       | `ISW_2025_4K3_G7/Parciales/Parcial_<N>/Elementos de clase/Clase_<N>_<FECHA>/` |
| **Nota de Clase**      | `P<N>_C<N>_NOTA_<Titulo>.<formato>` | `ISW_2025_4K3_G7/Parciales/Parcial_<N>/Elementos de clase/Clase_<N>_<FECHA>/` |
| **Parcial Viejo**      | `P<N>_<Año>_<Tema>.pdf`             | `ISW_2025_4K3_G7/Parciales/Parcial_<N>/Parciales Viejos/`                     |
| **Resumen Parcial**    | `P<N>_RES<N>_<Autor>.pdf`           | `ISW_2025_4K3_G7/Parciales/Parcial_<N>/Resúmenes/`                            |
| **Enunciado TP**       | `TP<N>_ENUNCIADO_<Titulo>.pdf`      | `ISW_2025_4K3_G7/TrabajosPracticos/Practico_<N>/`                             |
| **Artefacto TP**       | `TP<N>_ART<N>_<Nombre>.<ext>`       | `ISW_2025_4K3_G7/TrabajosPracticos/Practico_<N>/Artefactos/`                  |
| **Resolución TP**      | `TP<N>_RESOLUCION_ITEM<N>.<ext>`    | `ISW_2025_4K3_G7/TrabajosPracticos/Practico_<N>/`                             |
| **Item Bibliografía**  | `BIB<N>_<Nombre>.<formato>`         | `ISW_2025_4K3_G7/Bibliografia/`                                               |

## 5. Glosario

- <code>P</code>: Parcial
- <code>TP</code>: Trabajo Practico
- <code>BIB</code>: Bibliografia
- <code>N</code>: Numero de Parcial/TP/Item/etc
- <code>EJ</code>: Ejercicio
- <code>C</code>: Clase
- <code>RES</code>: Resumen
- <code>ART</code>: Articulo
- <code>PRES</code>: Presentacion
