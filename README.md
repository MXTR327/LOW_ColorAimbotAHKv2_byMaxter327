**Instrucciones de uso del script**

**Paso 1: Instalación**
* Descarga el script y colócalo en una carpeta de tu elección.
* Asegúrate de tener instalado AutoHotkey v2.0 o superior.
* Mantén los archivos incluidos (`ValidationTOKEN/validacionToken.ahk`, `Gui.ahk`, etc.) en la estructura de carpetas original.

**Paso 2: Ejecución**
* Ejecuta el script haciendo doble clic en el archivo .exe.
* El script creará automáticamente un archivo `config_[RESOLUCIÓN]_[VERSIÓN].ini` adaptado a tu pantalla.

**Paso 3: Uso y Configuración**

**Combinaciones de Teclas:**
* `Fin`: Muestra/Oculta el panel de configuración gráfica.
* `F5`: Recarga el script.
* `F8`: Activa/Desactiva el script (estado inicial en `script_activo_por_defecto`).
* `F12`: Cierra la aplicación.
* `Ctrl + Shift + D`: Muestra/Oculta las áreas de disparo y ajustes.

**Explicación de Variables en `config.ini`:**

### Sección: *Teclas*
- *mostrar_ocultar_panel*: Tecla para mostrar/ocultar el panel (Ej: `End`).
- *mostrar_ocultar_areas*: Tecla para mostrar/ocultar areas (Ej: `+^d`).
- *reiniciar*: Tecla para reiniciar el script (Ej: `F5`).
- *pausar*: Tecla para pausar el script (Ej: `F8`).
- *salir*: Tecla para cerrar el script (Ej: `F12`).

### Sección: *Mouse*
- *aimbot_click_izquierdo*: Activa el aimbot al hacer clic izquierdo (`true`/`false`).
- *aimbot_click_derecho*: Activa el aimbot al hacer clic derecho (`true`/`false`).

### Sección: *General*
- *script_activo_por_defecto*: Estado inicial del script (`true`/`false`).
- *velocidad_aim_x*: **Velocidad horizontal del aimbot (1-250).**  
  Ej: `60` = 60% de velocidad.
- *velocidad_aim_Y*: **Velocidad vertical del aimbot (1-250).**  
  Ej: `50` = 50% de velocidad.

### Sección: *Color*
- *utilizar_color_personalizado*: Usar color hexadecimal personalizado (`true`/`false`).
- *color_personalizado*: Color HEX para detección (Ej: `0x000000` para rojo).
- *sensibilidad_color*: Tolerancia de color (0-50). Valores bajos = mayor precisión.

### Sección: *Offsets*
- *head_offset_x*: Compensación horizontal del punto de mira (0-15).
- *head_offset_y*: Compensación vertical del punto de mira (0-50).

### Sección: *Área_Aimbot*
- *area_escaneada_x*: Ancho del área de escaneo (1-500).
- *area_escaneada_y*: Alto del área de escaneo (1-500).

### Sección: *Area_Antishake*
- *activar_antishake*: Activar filtro de vibración (`true`/`false`).
- *antishake_x*: Área horizontal ignorada al detectar movimiento (1-30)).
- *antishake_y*: Área vertical ignorada al detectar movimiento (1-30).

### Sección: *TriggerBot*
- *activar_triggerbot*: Disparo automático al detectar color (`true`/`false`).
- *tamano_area_triggerbot*: Tamaño del área de activación (1-50).
- *tiempo_antes_de_disparo*: Retardo antes de disparar (milisegundos).

### Sección: *Experimentos*
- *desactivar_escalado_dpi*: Mejora rendimiento en pantallas HD (`true`/`false`).
- *limite_acumulacion_recoil*: Máximo retroceso acumulable (0-100).
- *intensidad_control_retroceso*: Fuerza de compensación de retroceso (0-10).
- *compensacion_retroceso*: Porcentaje de compensación vertical (0-100).
- *anti_deteccion_aimbot*: Añade variabilidad aleatoria al movimiento evitando deteccion de anticheats (`true`/`false`).
- *humanizacion*: Limita la velocidad máxima del aimbot para parecer humano (`true`/`false`).
- *intentos_busqueda*: Número de intentos de detección por ciclo (1-15).

**Paso 4: Desinstalación**
* Cierra el script con `F12`.
* Elimina todos los archivos relacionados, incluido el `.ini` generado.

**Notas Importantes:**
- El archivo de configuración se genera automáticamente con tu resolución y versión.
- ¡Usa `Delete o Supr` para acceder rápidamente al panel!
- La sección *Experimentos* contiene funciones en desarrollo - úsalas con precaución.
