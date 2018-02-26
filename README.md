Después de los últimos días de indignación de Internet / reacción exagerada a la revelación de que el iPhone tiene un caché para su servicio de ubicación, decidí echar un vistazo a lo que mis dispositivos Android almacenan en caché para la misma función.

Este es un volcado rápido que lancé para analizar los archivos del proveedor de ubicación de Android.

Los archivos se denominan cache.cell y cache.wifi y se encuentran en /data/data/com.google.android.location/files en el dispositivo Android.

Necesitará acceso raíz al dispositivo para leer este directorio.

Uso:
parse.py <archivo de caché>
