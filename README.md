# SIM_908
modulo gsm/gps /gprs

Este es una placa arduino GPS/GPRS/GSM de DFRobot,con un motor GSM/GPRS de banda cuádruple funciona en frecuencias EGSM 900MHz/DCS 1800MHz y GSM 850MHz/ PCS 1900MHz. También es compatible con la tecnología GPS para navegación por satélite. Es posible enviar mensajes y utilizar la red GSM.
Se controla mediante comandos AT (GSM 07.07, 07.05 y comandos AT mejorados SIMCOM). El diseño de esta placa permite manejar la función GSM y GPS directamente con la computadora. Incluye un SMD de alta ganancia Antena para GPS y GSM. Utiliza un chip SIM908 integrado de SIMCom. Con una interfaz estándar de la industria y una función GPS, la combinación de ambas tecnologías permite rastrear sin problemas los bienes, vehículos y personas en cualquier lugar y en cualquier momento con cobertura de señal.

El archivo sim908 permite encender el modulo mediante comandos AT, encender el gps y obtener sus datos. Para que este funcione el codigo debe ser cargado a la placa arduino y los interruptores del modulo se deben encontrar en el siguiente orden:

S1 = PROG
S2 = ARDUINO
S3 = MIDDLE

luego de cargar el codigo mover le interruptor S1 a COMM.
Para mas información consultar en: https://wiki.dfrobot.com/GPS_GPRS_GSM_Module_V3.0__SKU_TEL0051_
