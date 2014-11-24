# Multicóptero
###Qués es un multicóptero y como funciona

Un multicóptero es un vehículo aéreo mecánicamente sencillo cuto movimiento es controlado acelerando o frenando multiples unidades de motor más hélice generando un empuje hacia abajo.

A multicopter is a mechanically simple aerial vehicle whose motion is controlled by speeding or slowing multiple downward thrusting motor/propeller units.

**Los multicóptero son aerodinémicametne inestables** y requieren un equipo de control a bordo (conocido como controlador de vuelo) para un vuelo más estable. Como resultado, si el sistema no esta conectado o funcioando el sistema no vuela. El controlador de vuelo combina información de la placa como giróscopos, acelerómetros (los mismo que existen en los teléfonos móviles) para mantener una estimación precisa de su orientación y posición.

El quadricóptero es el multicóptero más sensillo, donde cada motor gira en dirección contraria a los dos motores que tiene a su lado ( es decir, motoroes e esquinas opuestas del bastidor giran en la misma dirección).

Un quadricóptero puede controlar el *roll* y el *pitch* acelerando dos motores de un lado y reduciendo la velocidad de los otros dos. Por ejemplo,si un quadricóptero quiere modificar el roll hacia la izquierda deberá acelerar los motores de la derecha y frenar los dos de la derecha. De forma similar si quieres girar hacia delante acelera los dos motores traseros y ralentiza los delanteros.

Los giros sobre su eje (conocidos com *yaw*) hacia la izquierda o hacia la derecha se producen por la aceleración de dos motores que están en diagonal y ralentiza los otros dos.

El movimiento horizontal se lleva a cabo mediante la aceleración/desaceleración temporal de alguno de los motores para que el vehículo se incline en la dirección deseada y aumenta la velocidad de todos losmotores para que le vehículo se desplace hacia delante.

La altitud se controla acelerando o desacelerando todos los motores al mismo tiempo.


###¿Qué es diferente entre un multicóptero y un UAV/Drone?

**Un multicóptero puede ser un UAV o Drone cuando es capaz de realizar vuelos autónomos**. Normalmente esto significa tomar la información de los acelerómetros y giróscopos y los cambina con los daos del barómetro y GPS por lo que el controlador entiendo no solo de orientación, sino también de posición.