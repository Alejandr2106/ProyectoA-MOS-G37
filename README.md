# Proyecto 2-A MOS — G27

Cada caso accede a su respectiva carpeta de datos para cargar los archivos CSV necesarios para la ejecución del modelo, y al finalizar genera automáticamente un archivo de verificación dentro de la carpeta **verificaciones**.

Los integrantes del grupo son:  
**Juan Esteban Lopez Torres — 202020285**  
**Bastien Quentin Clement Thirion — 202525085**  
**Matthieu Maxime Viranin — 202525086**  
**Alejandro Gonzalez Salazar — 201921465**

Los tres casos se ejecutan de manera independiente. Cada uno lee sus datos desde una carpeta dedicada ubicada en el repositorio. El Caso 1 lee los archivos desde `datos_caso1/`, el Caso 2 desde `datos_caso2/` y el Caso 3 desde `datos_caso3/`. En cada carpeta deben existir los archivos CSV correspondientes al escenario.

Cada caso procesa la información, construye el modelo de ruteo, ejecuta los algoritmos de optimización y reconstruye las rutas encontradas para cada vehículo. Luego genera un archivo CSV de verificación 

Todos los archivos de verificación se almacenan en la carpeta: verificaciones/


Para ejecutar cualquiera de los casos no es necesario modificar el código: basta con clonar el repositorio, ubicar los archivos CSV en la carpeta correspondiente (`datos_caso1/`, `datos_caso2/`, `datos_caso3/`) y ejecutar el script del caso correspondiente. Mientras la estructura de carpetas y nombres de los archivos se mantengan, la ejecución será correcta y se generarán los resultados en la carpeta de verificaciones. Si el caso incluye visualización geográfica, los mapas `.html` producidos pueden abrirse en cualquier navegador para revisar visualmente las rutas generadas.

Nota: El notebook se encuentra ejecutado dentro del repositorio, sin embargo, se recomienda clonarlo y correrlo localmente o en google colab, ya que dentro de github no se pueden apreciar bien los mapas de cada uno de los caso.



