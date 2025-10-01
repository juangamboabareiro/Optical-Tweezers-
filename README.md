# Optical Tweezers Analysis


##Contenidos

- [Descripcion del proyecto](#descripcion)
- [Origen de los datos](#datos)
- [Software Utilizado](#software)
- [Limpieza y Procesamiento de los datos](#)
- []


##Descripcion

En este proyecto se utiliza un kit de pinzas opticas para caracterizar las propiedades de un fluido compuesto por diferentes concentraciones de glicerina, agua MQ y particulas de latex. En este proyecto, se consideraron porcentajes de glicerina de 10%, 15%, 20% y 25%. El trabajo realizado se baso en el manual del kit de pinzas opticas portable EDU - OT3 de Thorlabs (Manual)[https://www.thorlabs.com/drawings/138f32cd3f789f7a-2564705D-C17A-1CEC-5663FA6C21D0F82D/EDU-OT3-EnglishManual.pdf].


##Datos

Los datos utilizados provienen de mediciones experimentales sobre cada muestra. Se utilizo el software Tracker para obtener la trayectoria de un promedio de 10 particulas de latex por muestra. Para cada muestra se presentan 4 archivos de datos:

- Browniano: Se dan las trayectorias de particulas bajo movimiento browniano
- Radios_Browniano: Se dan los radios de las particulas sometidas al movimiento browniano
- Radio_Potencia: Se da la trayectoria de una particula atrapada por el laser a distintas potencias de intensidad del laser
- Velocidad_Escape: Se da la trayectoria de una particula atrapada por el laser y desplazada al punto de soltarse del mismo


##Software

- Tracker
- Pandas
- Numpy
- Matplotlib
- Scipy


##Limpieza y procesamiento de los datos

Se procesaron los datos de manera de completar valores faltantes y corregir la notacion cientifica del software Tracker

