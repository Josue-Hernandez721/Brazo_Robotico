# Mejora Estructural y Simulación de Brazo Robótico

**Materia:** Laboratorio de Robótica
**Docente:** Dominguez Chavez Jose Alfonso
**Autor:** Josue Guadalupe Hernandez Perez
**Autor:** Rendon Hernandez Christopher


## Descripción General
Este repositorio documenta el proceso de rediseño, optimización física y simulación de un brazo robótico previamente existente. El objetivo principal del proyecto es la mejora mecánica del sistema para aumentar su estabilidad, optimizar la gestión del cableado y preparar nuevos componentes para manufactura aditiva, culminando en la validación cinemática en un entorno virtual.

## Fases de Desarrollo

### Fase 1: Levantamiento de Dimensiones y Modelado Base
El proyecto inició con un proceso de ingeniería inversa, realizando la toma de medidas detallada y el análisis geométrico del brazo robótico físico existente. A partir de estos datos, se desarrolló un modelo 3D de alta precisión utilizando **SolidWorks**, estableciendo el gemelo digital base para las futuras modificaciones.

![Brazo_Parte_1_boceto](https://github.com/user-attachments/assets/5a584000-f372-4e7d-88b9-211e919eb58c)

### Fase 2: Diseño de Efector Final y Optimización Mecánica
La segunda etapa se centró en el rediseño del efector final. Se modelaron nuevas pinzas funcionales, aplicando criterios de diseño orientado a la impresión 3D para asegurar su correcta fabricación y ensamble.

![Brazo_Robotico_SolidWorks](https://github.com/user-attachments/assets/a6626ce0-bc0b-4204-b21d-1b70253e914b)


**Justificación de Diseño (Nota sobre componentes):** Para esta iteración del proyecto no se requirió una nueva selección de componentes electrónicos ni actuadores. El esfuerzo de ingeniería se enfocó estrictamente en la **mejora física del robot**. Las decisiones de diseño se tomaron para:
* Mitigar movimientos parásitos, holguras y perturbaciones durante la operación.
* Integrar un sistema de enrutamiento y acomodo para el cableado, previniendo tensiones mecánicas o enredos que pudieran limitar los grados de libertad del brazo.

### Fase 3: Integración y Simulación en Entorno Virtual
Una vez validado el modelo CAD, se realizó la transición del ensamblaje de **SolidWorks** al software de simulación **CoppeliaSim**. En esta plataforma se configuraron las propiedades físicas y las articulaciones del modelo para iniciar el diseño de la simulación de movimiento, permitiendo evaluar el comportamiento cinemático de las nuevas piezas antes de su fabricación.

![Brazo_Robotico_Coppelia_Sim](https://github.com/user-attachments/assets/f3551337-04e5-4e65-9e79-b6b8ad30999a)


## Estructura del Repositorio
* 📁 `/CAD`: Archivos de partes y ensamblajes desarrollados en SolidWorks, y archivos exportados para impresión 3D.
* 📁 `/Simulacion`: Escena de simulación configurada para CoppeliaSim.
* 📁 `/Evidencias`: Capturas de pantalla del modelado, detalles de las nuevas pinzas y renders del entorno de simulación.
