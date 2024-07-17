# mlab-glowy10-fwdump
Dump del Firmware de la tablet Microlab Glowy 10 (8990)

![image](https://github.com/user-attachments/assets/aaef216d-3ab6-4422-8ced-8922966b1926)

# Hardware:
SoC: Unisoc SC9863a


RAM: 2 GB (no estoy seguro que variante)


Bateria: 6000 mAh


Memoria interna: 32 GB eMMC 5.1


CPU: ARM Cortex-A55 a 1,60 GHz con 8 Nucleos


Arquitectura: arm32-binder64 (El sistema operativo es de 32 bits pero el soc es compatible con 64)


GPU: PowerVR Rogue GE8322


Board: sp9863a_1h10_32b


Resolución: 800 x 1280 (vertical), 1280 x 800 (horizontal)



# Software:
Versión de Android: Android 10 Go (con cosas de unisoc)


Nivel de parche de seguridad de Android: 5 de noviembre de 2020 (muy desactualizado)


Actualización del sistema de Google Play: 2020-03-01 (muy desactualizado)


Banda base: FM_BASE_18B_W20.24.2_P4|sc9863A_modem|04-26-2021 16:15:11


Marlin2_18A_W20.18.3|sharkl3_cm4|04-29-2020 02:47:56


Kernel: 4.14.133, compilado el 8 de junio de 2021 a las 17:25:07 PM


Número de compilación: MLAB_GLOWY10_user_W20.19.4_P1_20210608

# Como desbloquear el bootloader:
pues no lo he logrado aún 😢
Ademas, los archivos del firmware no estan en .pac asi que es practicamente imposible flashear la rom stock sin tenerlo desbloqueado, ya que por ahora solo se puede flashear por FastbootD.

La tablet en si tiene fastboot y fastbootD, pero no se puede desbloquear el bootloader con ninguno de los dos, quizás la marca uso una llave privada distinta así para prevenir desbloquear el bootloader.

# Fallos
Cuando la tablet esta en modo reposo durante mucho tiempo, el WiFi y el Bluetooth dejan de funcionar.

La tablet tiene el software ADUPS Fota, que es un spyware, un gran error por la marca.

Y pues por ahora solo eso.
