# Mantenimiento Preventivo
<p><code>Fundamentos de Mantenimiento</code></p>

<p>Creado por <code>Jsotelo</code> para fortalecer los fundamentos de la <code>reparacion de los equipos de computo</code> en los cursos de mantenimiento y reparacion </p>

# Practica de laboratorio 01 - Caracterización

## Objetivos 

### Objetivo General

Proporcionar el conocimiento y generar las habilidades necesarias para realizar mantenimientos preventivos de equipos informaticos.

### Objetivos Específicos:
- Conocer los fundamentos necesarios para dar un diagnostico preciso para el Mantenimiento Preventivo.

---
## 1. [Configurar el entorno de trabajo](#) ✔
1. Instalar [VSCode][1_1]
2. Instalar [Git][1_2]
3. Crear una cuenta en [github][1_3]
4. Crear un [repositorio nuevo][1_4] en Github llamado <code>Lab-Mantenimiento</code>
5. Instalar la [extension de github][1_5] para VScode
6. Agregar <code>Usuario</code> y <code>Correo</code>
7. Cerrar carpeta y clonar el repositorio remoto desde VScode.
8. Crear una carpeta en el repositorio  llamada <code>Mant-01</code>.


[1_1]:https://code.visualstudio.com/download
[1_2]:https://git-scm.com/download/win
[1_3]:https://github.com/
[1_4]:https://github.com/new
[1_5]:https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github


## 2. [Preguntas reflexivas de ambientación](#) ✔

<ol type="a">
<li>¿Cuáles son los principales riesgos o problemas que pueden surgir si no se realiza mantenimiento preventivo en los portátiles?</li>R//si no se realiza mantenimiento preventivo en los portatiles reduciria la vida util del equipo o tambien podria tener algunos errores como por ejemplo problemas en la memoria, posible perdida de informacion, bloqueos, virus.
<li>¿Qué componentes de un portátil son más susceptibles a fallas y requieren un mantenimiento preventivo más frecuente?</li>R// los componentes mas suceptibles a fallas son:  la pantalla, teclado, disco duro, memoria ram. 
<li>¿Qué herramientas y recursos se necesitan para llevar a cabo un mantenimiento preventivo efectivo en los portátiles?</li>se necesita utilizar un buen antivirus, actualizar el software, una limpieza.
<li>¿Cuáles son las mejores prácticas para mantener limpios los componentes internos y externos de un portátil como parte del mantenimiento preventivo?</li>r// para mantener los componentes internos y externos limpios se necesita: limpiar el disco duro, vaciar papelera desfragmentar el disco duro, disinstalar programas, corroborar actualizaciones, cargar bateria lo necesario,evitar situaciones que puedan poner en riesgo al PC.
<li>¿Qué estrategias podemos emplear para optimizar el rendimiento del portátil como parte del mantenimiento preventivo, además de simplemente corregir problemas existentes?</li>R// Actualizar sistema operativo, actualizar drivers, actualizar software util, elimina software innecesario, antivirus actualizado y configurado.
</ol>

## 3. [Caracterización del Pc ](#) ✔
|Parámetro||Valor|
|--|:--:|--:|
|Número Discos Físicos|-->|3|(1)
|Tamaño de Discos|-->|40 GB|(117 GB)
|Horas de uso|-->|8523|(3:9:52)
|Memoria fisica disponible|-->|7000 MB|  ( 981 MB )
|Memoria virtual tamaño maximo|-->|7000 MB| ( 6.732 MB) 
|Memoria virtual disponible|-->|7000 MB| (1.538 MB) 
|Memoria virtual en uso|-->|7000 MB|(5.194 MB)
|Procesador |-->|Liteon Technology Corporation |( Intel64 Family 6 Model 55 Stepping 8 GenuineIntel ~2159 Mhz)
|Fabricante del procesador|-->|3C-A0-67| Intel
|Modelo del Computador|-->|3C-A0-67-E8-D8-77| (Aspire E5-411)

>Nota: Para obtener los parámetros del sistema, usaremos los comandos [tecla de Windows + R][10], [cmd][8], [systeminfo][9].


## 4. [Caracteristcias de sistema](#) ✔
|Parámetro||Valor|
|--|:--:|--:|
|Sistema Operativo|-->|linux,windows|(windows 10 home single lenguaje)
|Arquitectura de sistema|-->|cuantos bits|(64 bits)
|version de producto|-->|profesional home|(home single lenguaje)
|Version del sistema|-->|22.04H|(18363.592)
|Grupo de trabajo|-->|wordgrouo|WORKGROUP
|Nombre del equipo|-->|nombre del equipo|(desktop-V6MH80O)

>Nota: Para obtener los parámetros de la red, usaremos el comando [tecla de Windows + R][10], [cmd][8], [systeminfo][9] o usando las propiedades del equipo dando click derecho.

## 5. [Diagnostico Diferencial](#) ✔
|Parámetro|Diagnostico|
|--|--:|
|Diagnostico del sistema| como|(esta muy lento)
|Diagnostico para discos| recom|(dejar un poco de espacio libre en la unidad solida (ssd))
|Diagnostico de memorias| recom|(cerrar aplicaciones que no se utiliza, reiniciar dispositivoregularmente)
|Diagnostico fisico| reco|(el sistema no estaba actualizado totalmente)

>Nota: Para obtener los parámetros dedemos, usar los sistemas recomendados.


[1]:https://www.speedtest.net/es
[2]:https://fast.com/es/#
[3]:http://speedtest.claro.net.co/
[4]:https://www.nperf.com/es/
[5]:https://www.cual-es-mi-ip.net/
[6]:https://ipinfo.io/

[9_1]:https://asrank.caida.org/

[8]:https://man7.org/linux/man-pages/man8/ifconfig.8.html
[9]:https://learn.microsoft.com/es-es/windows-server/administration/windows-commands/getmac
[10]:https://learn.microsoft.com/es-es/windows-server/administration/windows-commands/ipconfig
[11]:https://learn.microsoft.com/es-es/windows-server/administration/windows-commands/arp
[12]:https://learn.microsoft.com/es-es/windows-server/administration/windows-commands/ping
[13]:https://learn.microsoft.com/es-es/windows-server/administration/windows-commands/tracert

---
## Evaluación y rúbrica
- Fecha máximo entrega: 08 de Marzo de 2024
- Hora de entrega: 11:59pm	
- Nota máxima: 5.0 
- Número de actividades: 5
- Valor de cada actividad: 0.5
- Ponderación: 20%