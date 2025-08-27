# Desarrollo de Software Seguro

## 1. Instalación de Kali Linux en VirtualBox

1. Descargar VirtualBox desde [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads) y seguir el instalador correspondiente al sistema operativo host.

2. Descargar la ISO de Kali Linux desde [https://www.kali.org/get-kali/#kali-virtual-machines](https://www.kali.org/get-kali/#kali-virtual-machines) (opción VirtualBox).

3. Crear una nueva máquina virtual en VirtualBox y nombrarla según preferencia.

4. Seleccionar la **Imagen ISO de Kali Linux** en la sección *"ISO image"*.

5. Especificar los recursos de la máquina virtual:
   - **Memoria RAM:** mantener el valor predeterminado o ajustar según disponibilidad.
   - **Número de CPUs:** mantener valor predeterminado.
   - **Tamaño del disco duro:** mantener valor predeterminado o ajustar según necesidad.

6. Finalizar la configuración e iniciar la máquina virtual.

7. Seguir los pasos del instalador de Kali Linux para completar la instalación.

      7.1. Iniciar Instalación
      - Ejecutar el instalador de Kali Linux con la opción **Graphical Install**.
      
      7.2. Seleccionar Idioma
      - Elegir **Español**.
      
      7.3. Seleccionar Ubicación
      - Elegir tu ubicación geográfica.
      
      7.4. Configuración de Teclado
      - Seleccionar **Latinoamericano**.
      
      7.5. Configuración de Usuario
      - Nombre completo: `Agustin Schlechter`
      - Nombre de usuario: `agustin` (ejemplo)
      - Ingresar contraseña segura
      
      7.6. Configuración de Red
      - Dirección IP: `0.2.15` (ejemplo, según tu red)
      - Configurar según necesidad de la red local
      
      7.7. Particionado del Disco
      - Método: **Utilizar todo el disco (Guiado)**
      - Elegir la opción recomendada
      - Cuando se pregunte si deseas formatear el disco: **Sí**
      - Continuar con todas las configuraciones predeterminadas
      
      7.8. Finalizar Instalación
      - Una vez completada, el sistema se reiniciará
      - En la pantalla de inicio, seleccionar: **Kali GNU/Linux**
      - Ingresar **nombre de usuario** y **contraseña** creados previamente

## 2. Instalación de un Proxy de Interpretación (ZAP)

   1. Abrir la Terminal en Linux
   
   2. Dentro de la terminal ingresar:
   ```bash
sudo apt update && sudo apt upgrade -y
sudo apt install zaproxy -y

   3. Revisar si se instalo con el comando:
zaproxy --version
