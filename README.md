# COIL_Sistemas_Espaciales

Repositorio para el desarrollo y diseño del proyecto CubeSat. Este repositorio incluye código, esquemáticos, modelos 3D y otros archivos relacionados con el diseño y funcionamiento de los sistemas del proyecto.

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

### Directorios principales

- **Códigos/Funcional**: Contiene el código fuente para el funcionamiento de los diferentes módulos y sensores utilizados en el proyecto, como BMP_280, GPS_NEO, GY_271, entre otros.

- **Diseño**: Incluye los archivos relacionados con el diseño físico y electrónico del sistema.
  - **3D**: Modelos tridimensionales de los componentes y ensamblajes del sistema.
  - **Esquemáticos**: Diagramas de circuitos electrónicos necesarios para el ensamblaje del sistema.
  - **Hiles**: Archivos de soporte y librerías.
  - **brd**: Archivos de diseño de PCB (circuito impreso) para la fabricación.

## Descripción de los Componentes

A continuación se listan los componentes principales integrados en el proyecto:

- **BMP_280**: Sensor de presión y temperatura.
- **GPS_NEO**: Módulo de GPS para geolocalización.
- **GY_271**: Sensor de campo magnético (brújula digital).
- **GY_271-MTQ**: Modificación del GY_271 para la integración con los magnetotorques.
- **MAGNETORQUERS**: Magnetotorques para el control de actitud mediante el uso de campos magnéticos.
- **MPU_6050**: Acelerómetro y giroscopio para la detección de movimiento y orientación.
- **SD_CARD**: Módulo de almacenamiento mediante tarjeta SD.

## Instalación y Uso

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu_usuario/COIL_Sistemas_Espaciales.git
   ```
2. Accede al directorio principal del proyecto:
   ```bash
   cd COIL_Sistemas_Espaciales
   ```
3. Abre la carpeta `Códigos/Funcional` para acceder al código fuente o la carpeta `Diseño` para los diseños físicos y electrónicos.

## Contribución

Si deseas contribuir al proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama para tu función o corrección de errores (`git checkout -b feature/nueva-funcion`).
3. Realiza tus cambios y haz commit de ellos (`git commit -am 'Agrega nueva función'`).
4. Sube tus cambios al repositorio (`git push origin feature/nueva-funcion`).
5. Abre un pull request en GitHub.

