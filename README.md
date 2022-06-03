# Curso Innovacción Virtual, práctica 3, máquinas virtuales.
![Máquinas virtuales de Azure](imgs/avm.png)

##Requisitos
1. Cuenta en Microsoft y acceso a [poooooortaaal.aaazuuuuuuuureeeeeee.cooooooom](portal.azure.com)

-------------

##Introducción
Las máquinas virtuales son un recurso poderoso que nos permite controlar todo el entorno de ejecución dentro de un Sistema Operativo (SO), el cual nos permite trabajar de forma idéntica a como lo hicieramos en las computadoras que tenemos en casa (claro, de acuerdo al SO utilizado). Las máquinas virtuales son un IaaS ya que tenemos adquirido el hardware necesario para su funcionamiento por parte de Azure y el resto lo configuraremos nosotros.

-------------

##Procedimiento
1. Crear máquinas virtuales necesarias

    1.1. El primer paso para crear una máquina virtual será crear una cuenta en Azure y entrar a [aquí](portal.azure.com) para administrar los recursos disponibles para la cuenta.
    1.2. Buscar "Virtual Machines" para acceder a los servicios de máquinas virtuales disponibles.
    ![Máquinas virtuales](imgs/busqvm.png)
    1.3. Seleccionar la opción "Create" para iniciar el proceso de creación de la máquina virtual.
    ![Máquinas virtuales](imgs/mv02.png)
    1.4. Seleccionar la opción que más se ajuste a sus necesidades, para este caso "Azure virtual machine".
    ![Máquinas virtuales](imgs/mv03.png)
    1.5. Comenzar con la configuración de los parámetros básicos de la máquina virtual:

        A. Seleccionar la suscripción Azure adecuada, en este caso "Azure for Students".
        B. Asigne un nombre de grupo de recursos para organizar los mismos.
        C. Asigne nombre a la máquina virtual.
        D. Seleccione la región adecuada para su ubicación geográfica.
        E. Seleccione un S.O.
        F. Elija un tamaño para su máquina virtual (esto determinará el costo).
        G. Asigne un nombre para el usuario.
        H. Asigne la contraseña para el usuario.
        I. Permita sólo los puertos seleccionados.
        J. Sólo permita el puerto RDP.
        K. Marque la casilla de licencia.
        L. Procesa para revisar y crear la máquina virtual.

    ![Máquinas virtuales](imgs/mv04.png)
    ![Máquinas virtuales](imgs/mv05.png)
    1.6. Verifique los datos y costos, si todo está bien, proceda con "Create", esto tomará un tiempo dependiendo de la carga de los servidores de la región seleccionada.
    ![Máquinas virtuales](imgs/mv06.png)
    1.7. Al terminar el proceso, seleccionaremos "Go to resource" para revisar el recurso creado.
    ![Máquinas virtuales](imgs/mv07.png)
    1.8. Esta página nos muestra toda la información disponible sobre nuestra nueva máquina virtual, hay que tener en cuenta que el uso de este equipo cuesta con el simple hecho de estar ejecutándose, por lo que para reducir costos podemos usar las opciones de A:
    - Stop: Detener el recurso, apagar la máquina virtual (y ahorrar porque no estará en ejecución)
    - Start: Iniciar el recurso, encender la máquina virtual (nos cobrarán lo anteriormente indicado por hora)
    ![Máquinas virtuales](imgs/mv08.png)

NOTA: Para esta práctica necesitamos al menos 2 máquinas virtuales, por lo que repetiremos los pasos de la creación tantas veces como sea necesario.