# Predicción de Capacidades Hospitalarias con Variables Meteorológicas y Ambientales en Medellín : Monografía presentada para optar al título de Especialista en Analítica y Ciencia de Datos



Este reporsitorio se puede evidenciar el desarrollo de la monografía y se tendrá en cuenta lo siguiente:
- Resumen
- Requisitos previos
- Instalación del desarrollo
- Tomar data carpeta drive
- Usar Requirements.txt
- Contactos

## Resumen

Colombia es un país que presenta un alto porcentaje de mortalidad por enfermedades respiratorias debido a sus zonas de concentración de contaminantes. Estas cifras pueden darse en ocasiones donde las condiciones climáticas y ambientales son dañinas para la salud. Dadas estas cifras alarmantes, es necesario tener en cuenta la cantidad de pacientes que pueden ingresar a los hospitales en ocasiones donde existan afectaciones en las condiciones ambientales, por ello, con el fin de alertar a los establecimientos de salud acerca de la cantidad de pacientes con diagnósticos asociados a enfermedades respiratorias que ingresarán en ciertos sectores o comunas de Medellín, presentamos un modelo alimentado por variables climáticas e ingresos en hospitales, con datos proporcionados por el Sistema de Alerta Temprana de Medellín y el Valle de Aburrá (SIATA) y el Sistema de Información de Prestaciones de Salud (RIPS) en los años de 2020 a 2024. La creación del modelo predictivo es a base de la metodología CRISP-DM, lo que permite realizar el proceso ETL en los datos para ajustar el modelo de XGBoost a un R2 de 0.97. De esta forma, podemos estimar la cantidad de asistencias proyectadas en entidades hospitalarias cercanas a los puntos de toma de información.

## Requisitos previos
Para poder usar el desarrollo de manera loca deberán tener instalado previamente lo que sería lo siguiente: 
- Crear un ambiente virtual en conda o a su elección, para ello despues de instalar conda para crear el ambiente  deben abril el anaconda prompt y seguir estos pasos:

```
conda create -n nombreambiente python=3.12
 ```
para activar el ambiente

```
conda activate nombreambiente
 ```

Una vez que ya este activado el ambiente deje el anaconda prompt a un lado por un momento y sigue el manual.

Como se debio dar cuenta el desarrollo se realizo con la versión de python 3.12

Revise que tenga GIT instalado en su computador

## Instalación del desarrollo

1) Clonar Repositorio:
    - Para clonar debes usar el comando
    ```
    git clone https://github.com/kennethLeonel/Proyecto-Grado-Prediccion-Atenciones-Medicas.git
    ```

    - desde el visual studio en la terminal escriben el comand change directory de la siguiente forma 
    ```
    cd Proyecto-Grado-Prediccion-Atenciones-Medicas
    ```
Verá que nada más encuentra la carpeta
## Tomar data carpeta drive
Para el modelo fue necesario usar los datos del SIATA y de RIPS Medellín, estos datos se alojaron porque son pesados en el drive 
```
https://drive.google.com/drive/folders/1ZryWHzcMUuBdWhhOzTDO0UOtxtN1HUsW?usp=drive_link
```
una vez se dirija podra observar que existe dentro de la carpeta data 3 subcarpetas que son analytics, stage, esto es de gran importancia conocer ya que es nuestro ciclo de los datos

- raw(datos crudos que fueron tomadas por las entidades)
- stage(datos ya limpios y preprocesados)
- analytics(datos finales y se deja el modelo en la subcarpeta models)

Porfavor descargue completamente la carpeta data. Una vez descargado use herramientas para descomprimir el archivo zip y esa carpeta data dejala en el directorio Proyecto-Grado-Prediccion-Atenciones-Medicas

## Usar Requirements.txt

En el mismo directorio podra detallar el archivo Requierements.txt este contiene las librerias usadas en el desarrollo

para instalar las dependencias use el siguiente comando desde el anaconda prompt donde ya esta activado el ambiente virtual anteriormente.

```
pip install -r requirements.txt
```

## Correr Desarrollo

Una vez ya hecho los pasos anteriores puede observar en el archivo con Nombre ProyectoGrado.ipynb y ejecutarlo con el ambiente virtual y listo.


## Contactos

| Nombre | Apellido | Correo               | Cédula   | Universidad     | Rol |
|--------|----------|----------------------|----------|-----------------|-----|
| Juan Jose  | Naranjo Velasquez    | jjose.naranjo@udea.edu.co      | No informa | Universidad de Antioquia   | Estudiante |
| Kenneth David    | Leonel Triana    | kenneth.leonel@udea.edu.co        | 1192817456 | Universidad de Antioquia   | Estudiante |
| Alejandro    |     | @udea.edu.co        | No informa | Universidad de Antioquia   | Asesor |
