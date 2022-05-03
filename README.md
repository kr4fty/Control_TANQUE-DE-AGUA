# Control de carga para TANQUE DE AGUA
 La función del circuito es la de encendido/apagar el motor el cual llena el
 tanque de agua. Sería reemplazo directo a los conocidos flotadores mecánicos.

## Objetivo
 El objetivo es la realización de un circuito que controle al motor, logrando
 el llenado del tanque con la menor cantidad de encendidas. De esta forma se
 intenta ahorrar energía, ya que al encender el motor este consume unas 6 veces
 la corriente nominal de trabajo.
 También se intentara diseñar el circuito con la menor cantidad de componentes y
 de esta forma lograr que sea mas económico en comparación a los flotadores.
 Y por ultimo, el objetivo final seria lograr ser el reemplazo directo, UNO a
 UNO entre los dos dispositivos (electrónico - mecánico), no agregando mas
 cables ni fuentes adicionales a los ya existentes.

## Ventajas
 * Mas económico en comparación al flotador mecánico
 * Menor consumo de energía, ya que solo se activara cuando llegue al nivel
   seteado
 * ...

## Desventajas
 * Fuente de continua, se debería agregar esta fuente para alimentar el control
 * Dependiendo los sensores utilizados, se debería hasta agujerear al taque

## Futuras Modificaciones por mi (Kr4fty)
 * Utilizar una fuente capacitiva que me convierta los 220Vac a los 12Vdc
 * Modificar/corregir el circuito, ya que por ejemplo si seteamos que el nivel
   mínimo de agua a un 25% y este sensor falla, es decir queda ABIERTO, el
   motor seguiría funcionando indefinidamente. Lo mismo sucede con el sensor de
   75%
 * Optimizar el circuito para tratar de utilizar la menor cantidad de componen_
   tes electrónicos

## Autor original
 [ELECTROALL](https://github.com/ELECTROALL)
