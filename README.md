Script en bash para revisar el hardware de nuestro equipo

Nos proporciona la siguiente informacion: 
  Marca y modelo de la CPU
  Memoria Ram total insertada
  Memoria Ram maxima insertable
  Marca y modelo de GPU
  Marca y modelo de Placa Base
  Numero de discoduros insertados

Como usarlo

1. Actualizamos los paquetes del sistema
   
       apt-get -y update && apt-get -y upgrade

2. Clonamos el repositorio
   
       git clone https://github.com/Bilalbel04/hardware.git

3. Entramos en el directorio hardware
   
       cd hardware

4. Descomprimimos el archivo
   
       unzip hardware.git

5. Proporcionamos permisos de ejecucion
   
       chmod 755 hardware.sh
  
6. Ejecutamos el script
   
       ./hardware.sh

