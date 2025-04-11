## Protocolo Bustime
### versión 1.1

El protocolo está destinado a transmitir datos sobre las ubicaciones de los vehículos de transporte público.

El protocolo es gratuito y se publica bajo una licencia abierta.


Protocolo: HTTPS (servidor web)

Formato: archivo CSV

Tiempo de actualización: una vez cada 10-15 segundos (recomendado)

Ejemplo: https://your-domain.com/api/bustime.csv

Campos: número único del dispositivo, hora (UTC, formato AAAA-MM-DD HH:MM:SS), longitud, latitud, matrícula (u otro identificador del vehículo), nombre de la ruta, velocidad (km/h), dirección (0-360 grados), accesibilidad para silla de ruedas (1 para accesible, 0 para no accesible)

Ejemplo:

```
12345678,2023-03-11 17:32:42,6.123331,49.815273,LSZ6201,25,24,180,1
12345679,2023-03-11 17:32:42,6.123381,49.815270,LSZ6283,1,12,90,0
```
