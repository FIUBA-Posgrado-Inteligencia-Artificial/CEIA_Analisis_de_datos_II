## Materiales de bimestres anteriores

Los materiales de cada bimestre en el que se dictó la materia están archivados en una etiqueta (tag) específica de Git y disponibles a través de una versión (release) en GitHub.
Si cursaste en un bimestre anterior (por ejemplo, 4to bimestre del 2026), podés acceder a los materiales completos de tu curso utilizando las siguientes opciones: 


#### Opción 1: Descargar los Materiales desde la página de releases 
Podés descargar los materiales directamente desde la interfaz de GitHub sin necesidad de usar Git.

**Pasos**:
1. Visitá la página de [*Releases*](https://github.com/FIUBA-Posgrado-Inteligencia-Artificial/CEIA_Analisis_de_datos_II/releases) del repositorio.
2. En la sección de la versión correspondiente (por ejemplo, "4B2026"), encontrarás:
   - Un enlace para descargar el código fuente como archivo ZIP o TAR.GZ (etiquetado como "Source code (zip)" o "Source code (tar.gz)").
3. Hacé click en el link de descarga (ZIP o TAR.GZ) o en el archivo adjunto y descomprimilo en tu computadora.

**Notas**:
- Esta opción es la más sencilla si no estás familiarizado con Git.
- El archivo ZIP/TAR.GZ contiene todos los documentos del repositorio tal como estaban al final de tu cohorte.


#### Opción 2: clonar el repositorio usando Git 
También se puede clonar el repositorio directamente y acceder a los materiales de tu cohorte utilizando la etiqueta (tag) correspondiente.

**Prerrequisitos**:
- Tener Git instalado en tu computadora.
- Un entorno de Python configurado para ejecutar los cuadernos Jupyter (consultá el ReadMe de este repo si necesitás instrucciones para configurar el ambiente).

**Pasos**:
1. Abrir una terminal.
2. Clonar el repositorio:

```bash
   git clone https://github.com/FIUBA-Posgrado-Inteligencia-Artificial/CEIA_Analisis_de_datos_II.git
```

Navegar al directorio del repositorio:

```bash
cd CEIA_Analisis_de_datos_II
```

Seleccioná el repo de tu cohorte, con el tag correspondiente. Debe tener la forma `bX-YYYY`, donde `X` es el bimestre y `YYYY` es el año:

```bash
git checkout bX-YYYY
```

Por ejemplo, los alumnos que cursaron durante el cuarto bimestre de 2026, deberían usar la etiqueta "b4-2026":

```bash
git checkout b4-2026
```

Notas:

* En el ejemplo, el tag te lleva al estado exacto del repositorio al final de tu cohorte.


* Estarás en un estado de "HEAD separado" al usar "git checkout {tag}". Esto es normal y te permite ver los archivos sin modificarlos. 


3. Explorar Archivos en la Interfaz de GitHub

Si solo necesitás ver o descargar archivos individuales, podés explorar el repositorio en GitHub.

Pasos:

1. Visitá el repositorio:
https://github.com/FIUBA-Posgrado-Inteligencia-Artificial/CEIA_Analisis_de_datos_II.git

2. En el desplegable de las branches (donde dice "main" por defecto), seleccioná la pestaña "Tags".

3. Elegí la etiqueta de tu cohorte (por ejemplo, b4-2026).

4. Navegá por los archivos (por ejemplo, notebooks/, datasets/) y descárgalos individualmente haciendo click-->"Download" o copiando el contenido desde la vista "Raw".

Nota: Esta opción es útil para acceder a archivos específicos, pero descargar el ZIP desde la página de Releases es más práctico para obtener todo el contenido.

Ante cualquier inconveniente, no dudes en contactarte con las docentes:

* [✉️](macroldan@fi.uba.edu.ar) María Carina Roldán 
* [✉️](arigarmendia@gmail.com) Ariadna Garmendia

