## Protocolo Bustime
### versão 1.1
O protocolo destina-se à transmissão de dados sobre as localizações dos veículos de transporte público.

O protocolo é gratuito e publicado sob uma licença aberta.


Protocolo: HTTPS (servidor web)

Formato: ficheiro CSV

Tempo de atualização: uma vez a cada 10-15 segundos (recomendado)

Exemplo: https://your-domain.com/api/bustime.csv

Campos: número único do dispositivo, hora (UTC, formato AAAA-MM-DD HH:MM:SS), longitude, latitude, matrícula (ou outro identificador do veículo), nome da rota, velocidade (km/h), direção (0-360 graus), acessibilidade para cadeira de rodas (1 para acessível, 0 para não acessível)

Exemplo:
```
12345678,2023-03-11 17:32:42,6.123331,49.815273,LSZ6201,25,24,180,1
12345679,2023-03-11 17:32:42,6.123381,49.815270,LSZ6283,1,12,90,0
```
