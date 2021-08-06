# Proyecto Crtndrdrs (Cartones de Hidalgo)

Aplicación para la gestion de las operaciones de venta de cajas de carton corrugado a negocios minoristas llamada "Cartones de hidalgo". La aplicación se compone de los siguientes modulos.

- Visualización de indicadores de costos, ventas, y producción. Mediante kernels, los datos en formato JSON son obtenidos, procesados y analizados. [_'Analisis de operaciones con Python'_](https://github.com/JAOscoy/Prototype_DataAnalyst-cartonesHidalgo.git).

- Usando la misma base de datos, usamos el framework ExpressJS para configurar una API siguiendo las recomendaciones de la arquitectura REST para transferencia de información. [_'Backend con Express'_](https://github.com/JAOscoy/Crtndrdrs_backend-Express.git).

- Con ayuda del framework de React, creamos la vista para el usuario [_'Frontend con React'_](https://github.com/JAOscoy/webCrtndrdrsTS.git).

# Descripción del problema

![Diagrama_cartonadoradores.png](/Diagrama_cartonadoradores.png)

### Limitaciones

- Cada prospecto requiere un ciclo de iteraciones con muestras fisicas y cambios en el diseño antes de realizar una cotización final.
- Una vez aceptada la cotización, algunas veces se requiere investigación de historial de credito ya que algunas veces se arregla con el maquilador una opción de financiamiento con el cliente.

# Product Backlog

![Historias_usuario.jpg](/Historias_usuario.jpg)

# Arquitectura

Diseño actual:

![Technologies_architecture.jpg](/Technologies_architecture.jpg)

### Ventajas:

- Protocolo HTTPS incluido.
- La mayor parte de los datos pueden cambiarse sobre un solo archivo (Interfaces TS).
- Ultimas versiones de paqueterias para evitar obsolecencia.
- Facil integración y arranque de futuros componentes.
- Pay-as-you-go por los servicios AWS y escalabilidad.

Primer boceto:

![Architecture.png](/Architecture.png)

#### Nice to have:

- Dashboard resultados.
- Adquisicón de datos remoto (clientes nuevos, registro de ordenes, creación de productos).
- Venta en linea.

# Estado actual

![current_state.jpg](/current_state.jpg)

#### V 2.0

- Full web-mobile responsive
- Compra final del dominio.
- Inclusión de más fotos de diseños flexibles y manejo desde la nube (AWS S3 Bucket).










