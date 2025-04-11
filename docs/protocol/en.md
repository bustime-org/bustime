## Bustime protocol
### version 1.1

The protocol is intended for transmitting data about the public transport vehicle locations.

The protocol is free and published under an open license.


Protocol: HTTPS (web-server)

Format: CSV file

Update time: once in 10-15 seconds (recommended)

Example: https://your-domain.com/api/bustime.csv

Fields: unique device number, time (UTC, format YYYY-MM-DD HH:MM:SS), longitude, latitude, license plate (or other vehicle identifier), name of the route, speed (km/h), heading (0-360 degrees), wheelchair accessibility (1 for accessible, 0 for not)


Example:
```
12345678,2023-03-11 17:32:42,6.123331,49.815273,LSZ6201,25,24,180,1
12345679,2023-03-11 17:32:42,6.123381,49.815270,LSZ6283,1,12,90,0
```
