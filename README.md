<img src="Imagenes/004.JPG" width="500">
# datalogger
Código y diseño de caja de datalogger para medir cambios de luz. EL código para crear y almacenar en archivos es tomado de el código creado por Bentley Born, aunque lo adaptamos para este logger, puede encontrar el [código original en este link](/https://github.com/bborncr/Datalogger_STATE_SDConfig)

* Para el datalogger se utiliza el controlador [Adafruit Feather Adalogger](https://www.adafruit.com/product/2796).
* Se utiliza el sensor [SI1145](https://www.adafruit.com/products/1777) de Adafruit. 
* Detalles de conexión los puden [encotrar acá](https://learn.adafruit.com/adafruit-si1145-breakout-board-uv-ir-visible-sensor).
* Se utiliza una [batería Lipo](https://www.adafruit.com/products/1317)
* el repositorio Light_Sensor_SI1145 contiene código para leer por puerto serial, la información del sensor. Con este código se pueden ver los datos para efectos de calibración.
* En Datalogger_STATE_SDConfig está el código para datalogging.  En archivo CONFIG.TXT se cambia para indicar fecha e intervalos de grabación de datos en la tarjeta SD
* El repositorio Caja, contiene los archivos de diseño para armar las caja.


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Este obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">licencia de Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional</a>.
