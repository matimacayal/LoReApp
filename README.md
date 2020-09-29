Aplicación desarrollada para celulares con sistema operativo Android y funciona en
conjunto con nodo LoRa. Sus funciones principales son tres.
1. Hacer de interfaz de control y monitor del nodo, permitiendo: (1) configurar perfil de
maestro o esclavo, (2) iniciar o detener la transmisión, (3) ajustar la potencia y los
parámetros LoRa de la comunicación y (4) mediante un monitor mostrar los paquetes
enviados o recibidos por el nodo.
2. Hacer un seguimiento de la localización de los dispositivos a lo largo de la prueba de
cobertura, asignando a cada paquete enviado o recibido una posición geográfica según
latitud y longitud. Esto permitirá posteriormente visualizar el perfil de cobertura del
terreno en un mapa.
3. Almacenar los datos de la prueba en la memoria del celular en formato excel para luego
ser exportado o enviado por alguna aplicación.

El almacenamiento de los datos de prueba se hace en archivos excel formato .xls. Estos
se generan de manera automática y una vez terminada la prueba solo es necesario enviarlos
del celular al computador para su análisis. Los datos almacenados son lo siguientes:

– Rol (maestro o esclavo)
– Número de paquete
– Paquete
– LoRa PA_BOOST
(true or false)

– LoRa Power
– LoRa Mode
– Hora
– Fecha
– Latitud

– Longitud
– Altura
– Lugar

– RSSI (Sólo nodo maes-
tro)
