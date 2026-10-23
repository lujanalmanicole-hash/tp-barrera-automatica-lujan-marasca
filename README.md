# tp de lujan nicole y marasca renata y scascitelli valentina 
# Requerimientos funcionales
# RF1: Medir la distancia con el sensor ultrasónico.
# RF2: Mostrar la distancia en el monitor serie.
# RF3: Detectar objetos a menos de 20 cm.
# RF4: Mover el servo a 90° o 0° según la distancia.
# RF5: Repetir las mediciones cada 500 ms.
# Requerimientos no funcionales
# RNF1: Responder rápidamente a los cambios de distancia.
# RNF2: Medir la distancia en centímetros.
# RNF3: Ser compatible con Arduino.
# RNF4: Tener un código fácil de entender y modificar.
# RNF5: Funcionar continuamente mientras esté encendido.
# Historias de usuario
# HU1: Como usuario, quiero medir la distancia de un objeto.
# HU2: Como usuario, quiero ver la distancia en el monitor serie.
# HU3: Como usuario, quiero detectar objetos cercanos.
# HU4: Como usuario, quiero que el servo se mueva automáticamente.
# HU5: Como usuario, quiero que el sistema mida continuamente.
# | Componente                 | Conexión en Arduino                       |
# | -------------------------- | -----------------------------------|
# | Sensor de distancia (TRIG) | Pin digital 9                             |
# | Sensor de distancia (ECHO) | Pin digital 10                            |
# | Sensor de distancia (VCC)  | 5V                                        |
# | Sensor de distancia (GND)  | GND                                       |
# | Servomotor (señal)         | Pin digital 6                             |
# | Servomotor (+)             | 5V                                        |
# | Servomotor (−)             | GND                                       |
# | Protoboard                 | Distribuye las conexiones de alimentación |
# | Computadora                | Se conecta al Arduino mediante USB        |
