# php.ini
 la ejecución de páginas PHP no inicia o no carga en Termux

SOLUCION;

Estoy seguro de que muchos usuarios van a tener ese error.
Tenia el mismo error en el moto g8 power. configurar los módulos de Apache instale MariaDB y php en su versión 8

De ahi todo parece normal hasta que habro el navegador en localhost: 8080 y la pagina se mantiene en blanco y no carga

Este error se debe a que apt install php no instala el archivo de configuracion php.ini por lo tanto ay que crearlo y configurarlo

nano /data/data/com.termux/files/urs/lib/php.ini
