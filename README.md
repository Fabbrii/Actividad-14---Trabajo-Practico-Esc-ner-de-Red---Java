# Escáner de Red – TP Redes E.T. 36 5TO 1ra

# Descripción

Aplicación en Java con interfaz gráfica para escanear un rango de direcciones IP, detectar dispositivos activos y mostrar información como:

  - Dirección IP
  - Nombre del host (si está disponible)
  - Estado de conexión
  - Tiempo de respuesta

Incluye opciones para filtrar, ordenar y guardar los resultados en un archivo CSV.

# Requisitos
  - Java 8 o superior instalado
  - Sistema operativo Windows o Linux con comandos ping y nslookup disponibles

# Instalación

1. Clonar el repositorio.
   
   git clone https://github.com/usuario/repositorio.git
   cd repositorio

2. Compilar el programa.
   
   javac EscanerRed.java

3. Ejecutar.

   java EscanerRed

# Uso 

1. Ingresar IP de inicio y fin del rango a escanear.
2. Configurar tiempo de espera (timeout) en milisegundos.
3. Presionar Comenzar escaneo.
4. Filtrar o ordenar los resultados desde la tabla.
5. Guardar los resultados en formato .csv si es necesario.

# Autor
Fabrizio Bruno - 5to 1era - Materia: Redes - 2025
