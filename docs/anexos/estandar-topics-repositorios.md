# Anexo técnico: Estándar transversal de topics para repositorios académicos

## Alcance

Este estándar es de aplicación transversal para todos los repositorios académicos de las líneas de Software, Ciencia de Datos e Inteligencia Artificial, Infraestructura Tecnológica y Gestión de Tecnologías de Información.

Los estándares técnicos o académicos particulares de cada línea se documentarán en anexos específicos y deberán mantener compatibilidad con este estándar transversal.

## Estándar de topics

Todos los repositorios académicos deben configurar los siguientes **topics**:

```text
campus-<lima|juliaca|tarapoto>
semestre-<2026-1|2026-2>
linea-<software|cdia|infraestructura|gestion>

# Tipo de proyecto (elegir solo uno)
tipo-ps          # Proyecto Sello
tipo-pi          # Proyecto Integrador
tipo-epe         # Evaluación de Perfil de Egreso

# Cursos (usar únicamente los nombres oficiales)
# Agregar solo los cursos que participan en el proyecto.
<curso1>
<curso2>
...

seccion-<gu|g1|g2|g3|g4>
grupo-<numero>-<nombre-proyecto>
```

### Ejemplo 1: Proyecto Sello (Big Data)

```text
campus-juliaca
semestre-2026-1
linea-cdia
tipo-ps
bigdata
seccion-gu
grupo-1-clima-agricultura
```

### Ejemplo 2: Proyecto Integrador (REQ + BD1 + LP1)

```text
campus-juliaca
semestre-2026-1
linea-software
tipo-pi
req
bd1
lp1
seccion-g2
grupo-1-codebuilders
```

### Ejemplo 3: Proyecto Integrador (ADS + BD2 + LP2)

```text
campus-juliaca
semestre-2026-1
linea-software
tipo-pi
ads
bd2
lp2
seccion-g1
grupo-2-bomerp
```

### Ejemplo 4: Evaluación de Perfil de Egreso (EPE)

```text
campus-juliaca
semestre-2026-2
linea-software
tipo-epe
seccion-g1
grupo-1-evaluacion-final
```

Los nombres de los cursos deben corresponder al catálogo oficial definido por la Escuela para mantener consistencia en las búsquedas y clasificación de los repositorios.

## Catálogo oficial de topics para cursos

### Línea Software

| Curso                                              | Topic  |
| -------------------------------------------------- | ------ |
| Fundamentos de Programación (FP)                   | `fp`   |
| Programación Orientada a Objetos (POO)             | `poo`  |
| Ingeniería de Requerimientos (REQ)                 | `req`  |
| Administración de Base de Datos I (BD1)            | `bd1`  |
| Lenguaje de Programación I (LP1)                   | `lp1`  |
| Análisis y Diseño de Sistemas de Información (ADS) | `ads`  |
| Administración de Base de Datos II (BD2)           | `bd2`  |
| Lenguaje de Programación II (LP2)                  | `lp2`  |
| Desarrollo de Aplicaciones Distribuidas (DIST)     | `dist` |
| Desarrollo de Aplicaciones Móviles (MOV)           | `mov`  |
| Ingeniería de Software I (IS1)                     | `is1`  |
| Ingeniería de Software II (IS2)                    | `is2`  |
| Pruebas y Despliegue de Software (PDS)             | `pds`  |

### Línea CDIA

| Curso                         | Topic          |
| ----------------------------- | -------------- |
| Big Data                      | `bigdata`      |
| Minería de Datos              | `mineriadatos` |
| Inteligencia de Negocios (BI) | `bi`           |
| Inteligencia Artificial (IA)  | `ia`           |
| Machine Learning (ML)         | `ml`           |
| Internet de las Cosas (IoT)   | `iot`          |

Utilizar únicamente los topics definidos en este catálogo. No crear variantes, traducciones ni abreviaturas diferentes.
