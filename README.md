#LECTOR DE CSV

# Descripción

Nuestro componente permite visualizar de manera ordenada un archivo CSV, así mismo organizarlo de la forma que más nos facilite. Al leer el CSV, visualizamos las columnas del archivo de manera que podamos seleccionar cuántos datos ver y automáticamente se genera la paginación correspondiente.

## Usos

### Componente de usos académicos o administrativos:
Este componente está diseñado para ser integrado en aplicaciones donde se requiera análisis de archivos. Ejemplos incluyen la vida académica, donde comúnmente se necesitan leer archivos para gestionar bases de datos, o en entornos administrativos, cuando se necesita buscar datos específicos en archivos.

## Características y Especificaciones

- **Lector de CSV**
- **Organizador de CSV**
- **Buscador de datos**

## API del Componente

| Panel           | Uso                                                                                              |
|-----------------|--------------------------------------------------------------------------------------------------|
| `btnCargarCSV`  | Botón para seleccionar un archivo CSV y procesarlo.                                              |
| `TxtNumFilasKeyReleased` | Permite al usuario cambiar el número de filas por página en una tabla al ingresar un número y presionar Enter. |
| `btnAnterior`   | Navegar a la página anterior.                                                                    |
| `btnSiguiente`  | Navegar a la página siguiente.                                                                   |
| `btnPagina`     | Botón de paginación para navegar entre las páginas creadas.                                      |
| `lblSuspensivos`| Contiene puntos suspensivos para separar botones de la paginación.                               |
| `lblPaginaActual` | Indica la página actual, el número total de páginas, y la cantidad de registros del archivo.   |

## Métodos

| Estructura                            | Función                                                                                       |
|---------------------------------------|-----------------------------------------------------------------------------------------------|
| `private void btnCargarCSVActionPerformed()` | Permite seleccionar y abrir archivos CSV para visualizar su contenido.               |
| `private void TxtNumFilasKeyReleased()` | Cambia el número de columnas según la cantidad que se desee ver.                        |
| `private void cargarCSV()`            | Lee el archivo CSV y obtiene los nombres de las columnas y registros.                        |
| `private void actualizarPanelPaginacion()` | Actualiza los datos de visualización como número de páginas y registros.             |
| `private void actualizarTabla()`      | Asegura que la tabla muestra los datos correctos para la página actual.                     |

## Funcionamiento

### Lector de CSV

1. Al ejecutar el programa, el componente abre un botón que permite seleccionar un archivo CSV.
2. Al seleccionar el archivo, se muestra un panel con la información del archivo abierto.
3. En la parte superior derecha, puedes modificar el número de registros mostrados (predeterminado en 5).
4. En la parte inferior, puedes usar la paginación para moverte entre páginas del archivo.

### Uso
1. Añadir el JAR.
   ![Descripción de la imagen](https://github.com/Esme23-78/Componente/raw/main/src/Componente_CSV/Imagenes_Readme/1.png)
2. Añadir el `.jar` del componente a los proyectos donde se desea utilizar.
   ![Descripción de la imagen](https://github.com/Esme23-78/Componente/raw/main/src/Componente_CSV/Imagenes_Readme/2.png)
3. Seguir el flujo de uso del componente para una ejecución fácil y sencilla.
   ![Descripción de la imagen](https://github.com/Esme23-78/Componente/raw/main/src/Componente_CSV/Imagenes_Readme/3.png)
   
   ![Descripción de la imagen](https://github.com/Esme23-78/Componente/raw/main/src/Componente_CSV/Imagenes_Readme/3_1.png)
   
   ![Descripción de la imagen](https://github.com/Esme23-78/Componente/raw/main/src/Componente_CSV/Imagenes_Readme/4.png)
5. La ventana principal muestra:
   ![Descripción de la imagen](https://github.com/Esme23-78/Componente/raw/main/src/Componente_CSV/Imagenes_Readme/5.png)
   - El número de filas predeterminado (5).
   - Opción para cambiar el número de registros mostrados.
   - Paginación y número de página actual, además del total de registros en el CSV.

## Ejecución

[Video de demostración](https://youtu.be/piVn5WejqQk)


## Elaboración
	-Edith Esmeralda Pérez Martínez
 	-Luis Enrrique Pinto Zarate







