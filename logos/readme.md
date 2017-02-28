Readme v1.01

Logos variados que se pueden vincular con los canales de listas IPTV agregándoles el atributo:

tvg-logo="http://example.com/path/to/logo/logo.png"

Ejemplo:
#EXTINF:-1 type="stream" tvg-logo="https://raw.githubusercontent.com/chwlibre/iptv/master/logos/Boomerang.png", Boomerang
http://premium.exabytetv.info/HLSST/10477/10477-TPWQB-1011000101100111010011011110110-ExabyteTV.m3u8

Los logos pueden estar en formato PNG (con o sin transparencias) y JPG.

El objetivo de esta carpeta es reducir el número de peticiones a diferentes servidores externos 
y que inicialmente apunten solo a GitHub, mientras los logos se guardan en el cache del sistema.
