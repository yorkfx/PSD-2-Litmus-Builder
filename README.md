## Build System Photoshop to HTML - Litmus Builder

Estas configuraciones sirven para convertir un PSD de Photoshop a un Newsletter Resposivo que pase todas las pruebas de [Litmus Builder](https://litmus.com)

###Ajustes de Newsletter.irs
Esta Configuración sirve para exportar de PSD a HTML. 
Incluye el nombre de los archivos, carpeta donde se guardan los assets y el formato del HTML.

#### Ajustes de salida Newsltter.iros
Esta configuracion sive para exportar los assets al formato del archivo y el peso maximo de los assets. 

### Default.sublime-commands & reg_replace_rules.sublime-settings
Esta configuración requiere [RegReplace](https://github.com/facelessuser/RegReplace) una extensión de Sublime Text 3 que ayudara a darle formato al HTML devuelto por Photoshop, dandole formato a las tablas y sea compatible con las mayoría los clientes de email.

### tabla-responsive.sublime-snippet
Este es un snippet de Sublime Text, para usarlo posicionate antes de _<head>_ y escribe _tablacss_ y _tab_ se agregara unas lineas de CSS que volveran el newsletter responsivo.
- Tab1 = ID de la tabla 
- Tab2 = Ancho de la tabala
- Tab3 = Alto de la tabla

