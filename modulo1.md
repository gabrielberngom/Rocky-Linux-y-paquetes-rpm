# Paquetes rpm

RPM es el formato de paquete de Linux Standard, Originalmente desarrollado por y para Red Hat. Es capaz de instalar, actualizar, desinstalar, verificar y solicitar programas.

- Algunos Comandos:

rpm -qa = muestra paquetes instalados.

rpm -qi = muestra la información de un paquete RPM.

rpm -ql = lista ficheros de un paquete RPM instalado.

rpm -qc = lista solo los ficheros de configuración.

rpm --checksig = verifica firma de un paquete RPM.

rpm -ivh "localFile.rpm" = instala un paquete.

rpm -e "localFile.rpm" = desinstala un paquete.
