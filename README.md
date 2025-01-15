**Instrucciones de uso del script**

**Paso 1: Instalación**

* Descarga el script y colócalo en una carpeta de tu elección.

**Paso 2: Ejecución**

* Ejecuta el script haciendo doble clic en el archivo .exe.
* El script se ejecutará en segundo plano y comenzará a funcionar automáticamente.

**Paso 3: Uso y Configuración**

**Combinaciones de Teclas:**
* `F5`: Recarga el script.
* `F8`: Activa o desactiva el script (activo por activo_por_defecto = true  en `config.ini`).
* `F12`: Sale de la aplicación.
* `Ctrl + Shift + D`: Muestra o Oculta las áreas de disparo.

**Explicación de Variables en `config.ini`:**
# Manual de Configuración

## Sección: *General*
- *activo_por_defecto*: Define si el aimbot está activado por defecto al iniciar el script.  
  - `1`: Activado  
  - `0`: Desactivado

- *color_em*: Código hexadecimal del color que el aimbot debe detectar en la pantalla para apuntar.  
  - Ejemplo: `0xD82A22` (rojo).

- *col_vn*: Parámetro que ajusta la sensibilidad de la detección del color, generalmente un valor entre 0 y 255.  
  - Ejemplo: `22` (bajo valor).

- *compensar_x*: Ajuste de compensación horizontal en píxeles para el centro del campo de visión (FOV).  
  - Ejemplo: `1` (compensación pequeña).

- *compensar_y*: Ajuste de compensación vertical en píxeles para el centro del campo de visión (FOV).  
  - Ejemplo: `6` (compensación mayor a la horizontal).

- *velocidad_aim_x*: Ajuste para velocidad horizontal del movimiento del aimbot.  
  - Ejemplo: `10` (suavizado bajo).

- *velocidad_aim_y*: Ajuste para velocidad vertical del movimiento del aimbot.  
  - Ejemplo: `10` (suavizado bajo).

## Sección: *Área Escaneada*
- **area_escaneada_x**: Establece el área escaneada en el eje X (horizontal), en porcentaje del ancho total de la pantalla.  
  - Ejemplo: `85` (85% de la pantalla).

- **area_escaneada_y**: Establece el área escaneada en el eje Y (vertical), en porcentaje del alto total de la pantalla.  
  - Ejemplo: `60` (60% de la pantalla).

## Sección: *Mouse*
- *apuntar_con_clic_botton_izquierdo*: Configura si el aimbot debe apuntar al hacer clic con el botón izquierdo del mouse.  
  - `1`: Activado  
  - `0`: Desactivado

- *apuntar_con_clic_botton_derecho*: Configura si el aimbot debe apuntar al hacer clic con el botón derecho del mouse.  
  - `1`: Activado  
  - `0`: Desactivado

## Sección: **Área Antishake Ignorar**
- *activar_antishake*: Activa o desactiva la funcionalidad para evitar tambaleos (Antiskake).  
  - `1`: Activado  
  - `0`: Desactivado

- *antishake_x*: Define el área de ignorancia del movimiento "shake" en el eje X (horizontal).  
  - Ejemplo: `1` (área pequeña).

- *antishake_y*: Define el área de ignorancia del movimiento "shake" en el eje Y (vertical).  
  - Ejemplo: `2` (área pequeña).

## Sección: *Opciones Experimentales*
- *optimizar_pantalla*: Activa o desactiva la optimización de la pantalla para mejorar el rendimiento.  
  - `1`: Activado  
  - `0`: Desactivado

## Sección: *TriggerBot*
- *activar_triggerbot*: Activa o desactiva la función de disparo automático (TriggerBot).  
  - `1`: Activado  
  - `0`: Desactivado

- *tamano_area_triggerbot*: Define el tamaño del área de activación del TriggerBot en píxeles.  
  - Ejemplo: `5` (área pequeña).

- *tiempo_antes_de_disparo*: Configura el tiempo de espera (en milisegundos) antes de disparar después de detectar el color.  
  - Ejemplo: `180` ms (espera corta).

**Paso 5: Desinstalación**

* Para desinstalar el script, simplemente cierra el proceso de AutoHotkey y elimina los archivos del script.

**Consejos y advertencias**

* Asegúrate de leer y seguir las instrucciones de uso cuidadosamente para evitar problemas.
* No uses el script en juegos que no permitan el uso de scripts o bots.
* El script no es responsable de cualquier daño o pérdida causada por su uso.


