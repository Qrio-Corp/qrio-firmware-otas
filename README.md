# Rama `pruebas-v2` — binarios de prueba de qrio-firmware-v2

**Esta rama es temporal y no tiene relación con `main`** (es una rama huérfana:
historial propio, sin ancestro común). No afecta a ninguna OTA de producción.

`f.bin` es una imagen de prueba de `qrio-firmware-v2`. Se sirve por
`raw.githubusercontent.com` para probar el camino de OTA por 4G contra la
placa de test `0017`.

El nombre es corto a propósito: cada carácter de la URL cuenta contra el
tamaño del mensaje MQTT que la transporta.

Se puede borrar entera sin consecuencias:

    git push origin --delete pruebas-v2
