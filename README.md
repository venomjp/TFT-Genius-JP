# TFT Firmware Artillery Genius

Modificación del firmware de la pantalla TFT de mi Artillery Genius basada en el trabajo de <a rel="bigtreetech" href= "https://github.com/bigtreetech/BIGTREETECH-TouchScreenFirmware/tree/master"> BIGTREETECH</a>.

He incorporado mi logo al iniciar la pantalla:

<img alt="miLogo" style="border-width:0" src="Tarjeta SD\MKS\bmp\logo.bmp" width="400" align="center"/>

# Modificaciones
1. **config.ini** - Etiquetas de los g-code en castellano
2. **language-es.ini** - He traducido muchas expresiones, acortándolas para que se vean bien en pantalla.
3. **logo.bmp** - He creado mi propio logo.

# Cómo instalar el firmware
***Estas son las modificaciones que he hecho yo para mi impresora "Artillery Genius", si quieres puede usarlas bajo tu responsabilidad.***

**1.** Formatea una tarjeta microSD de 8Gb a FAT32

**2.** Copia los archivos de la carpeta "Tarjeta SD" a la raíz de la microSD (mantén la estructura).

**3.** Con la impresora 3D apagada inserta la tarjeta microSD

**4.** Enciende la impresora 3D y empezará la actualización del firmware de la pantalla TFT. Espera a que acabe, es posible que la primera vez tengas que calibrar la pantalla tocando en algunos puntos.

**5.** Para que cargue bien el idioma español tienes que apagar la impresora 3D y volver a encenderla. Esta vez sólo cargará el idioma.

**6.** Puedes sacar la microSD y cambiar el idioma: *Menu-->Screen-->Language*

<span style="color:violet">*Con esta actualización puedes desactivar la pantalla para cargar un nuevo firmware Marlin en la placa sin necesidad de abrir la impresora (no pierdes el precinto de garantía) ni desenchufar nada.*</span>

# Licencia
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Licencia Creative Commons" style="border-width:0" src="by-sa.png" width="200" align = "center"/></a>

<br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">TFT-Artillery Genius</span> modificado por <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Juan Pedro Perianes Rodríguez</span> se distribuye bajo una <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional</a>.
