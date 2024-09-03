# Proyecto Vórtice-01

## Objetivo
Crear un satélite de bajo coste, llamado Vortex-01, que proporcione una red Wi-Fi gratuita a través de una conexión satelital. El satélite estará equipado con sensores, sistemas de energía y un sistema de seguridad remoto.

## Especificaciones del satélite

- **Nombre:** Vórtice-01
- **Función:** Proporcionar Internet gratis vía satélite

### Componentes principales

- **Raspberry Pi 4B:** Ordenador central para procesamiento y control de datos.

### Sensores

- **Sensor de Presión Atmosférica:** **BMP180** - Sensor accesible para medir presión y altitud.
- **Sensor de aceleración (IMU):** **MPU-6050** - Combina acelerómetro y giroscopio, ideal para monitorear el movimiento y la orientación.
- **Sensor de Radiación:** **RADFET** - Opcional, para monitorear la exposición a la radiación de una manera económica.

### Antenas

- **Antena Dipolo de Banda Ancha:** Antena dipolo casera para comunicación RF de bajo costo.
- **Antena Yagi:** Antena Yagi DIY para mejorar la dirección y ganancia de la comunicación, construida con materiales asequibles.

### Sistemas de energía

- **Paneles Solares:** **Paneles Policristalinos** - Económicos y suficientes para generar energía en proyectos de espacios reducidos.
- **Controlador de carga solar:** **Controlador PWM** - Solución asequible para la gestión básica de carga de paneles solares.
- **Batería:** Baterías de coche o **baterías 18650 reacondicionadas** - Alternativa económica para el almacenamiento de energía, utilizando baterías reutilizadas de portátiles viejos.

### Control térmico

- **Mantas Térmicas:** **Mantas Mylar** - Solución económica de aislamiento térmico, utilizando materiales ligeros y reflectantes.

### Sistema de propulsión

- **Propulsores de gas frío:** Propulsores de bricolaje que utilizan botellas de CO2 de paintball, válvulas de liberación, para maniobras seguras y económicas.

### Sistemas de navegación y control

- **GPS:** **Módulo GPS NEO-6M** - Módulo GPS asequible adecuado para navegación básica y seguimiento de posición.

## Sistema de seguridad

- **Función:** Desactiva el sistema de combustible y activa un paracaídas gigante en caso de fallo o peligro.
- **Mecanismo:** Se activa de forma remota para garantizar la seguridad en caso de una falla crítica.

##Software

- **Desarrollo:** Uso de Ubuntu, Python, C, Assembly y Java
- **Comunicación:** A través de señales de RF

### Características

- Código para la gestión de sensores.
- Código para comunicación y transmisión de datos.
- Código para el sistema de seguridad.

## Diseño de satélites

- **Estructura:**
 - **Formato:** Compacto y ligero, fabricado en acero y aluminio.
 - **Paneles Solares:** Para generación de energía
 - **Batería:** Batería de automóvil o baterías 18650 para almacenamiento de energía

## Lanzamiento

- **Preparación:** Montaje en el lugar de lanzamiento
- **Combustible:** Se agregará gasolina en el sitio de lanzamiento.
- **Procedimientos de Seguridad:** Distancia de seguridad y activación remota del sistema de seguridad

### Planificación del lanzamiento

- **Fase de montaje:** Ensamble el satélite y agregue combustible en el sitio de lanzamiento.
- **Activación remota:** Sistema de seguridad activado remotamente para cortar el combustible y abrir el paracaídas en caso de emergencia.

## Repositorios

- **Modelo 3D:** [GitHub - Modelo Vortex-01](https://github.com/Vortex-01/Model)
- **Código fuente:** [GitHub - Código fuente de Vortex-01](https://github.com/Vortex-01/Source-Code)

## Objetivo de reconocimiento

- **Objetivo:** Utilizar el proyecto Vortex-01 como escaparate para demostrar habilidades técnicas e innovadoras, con el objetivo de atraer la atención de instituciones como el MIT.
