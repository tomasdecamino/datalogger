<img src="Imagenes/004.jpg" width="100">
# datalogger
Código y diseño de caja de datalogger para medir cambios de luz. EL código para crear y almacenar en archivos es tomado de el código creado por Bentley Born, aunque lo adaptamos para este logger, puede encontrar el [código original en este link](/https://github.com/bborncr/Datalogger_STATE_SDConfig)

* el repositorio Light_Sensor_SI1145 contiene código para leer por puerto serial, la información del sensor. Con este código se pueden ver los datos para efectos de calibración.
* En Datalogger_STATE_SDConfig está el código para datalogging.  En archivo CONFIG.TXT se cambia para indicar fecha e intervalos de grabación de datos en la tarjeta SD
* El repositorio Caja, contiene los archivos de diseño para armar las caja.
