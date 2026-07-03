# janomasterone-spanish-Chile

Tipografía en manúscrita para el idioma español en formato TTF (TrueType Font).
El diseño corresponde al enseñado en la Escuela Proyecto de Futuro, Paillaco, Región de los Ríos, Chile, América del Sur, Planeta Tierra, Sistema Solar, Vía Láctea, Pequeño Cúmulo de Galaxias, Supercúmulo de Laniakea, Universo... Promoción año 2005 del calendario gregoriano.

## Origen
El archivo con la terminación .ttf ha sido editado usando la aplicación FontForge en su versión Flatpak (puede revisar en https://flathub.org/es/apps/org.fontforge.FontForge para más detalles de la aplicación), se ha utilizado como plantilla un archivo .ttf obtenido en la carpeta de configuración de Fuentes Tipográficas de la distro Garuda Mokka, después de instalar diversos paquetes de acceso libre con estilo de escritura cursiva, con nombre "PlaywriteCL[wght].ttf", cuya metadata deriva a https://github.com/TypeTogether/Playwrite que cuenta con licencia "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org". 

## Modificaciones
Proyecto autodidacta,debido a la falta de conocimiento respecto a los script, manuales en otro idioma con lenguaje muy técnico que se distorsiona al usar las herramientas de traducción, se han eliminado todas las reglas GSUB / GPOS originales, para comprender el funcionamiento se han agregado nuevas reglas GSUB/GPOS para anclajes, ligaduras y sustituciones. Los cambios están enfocados en las 27 letras del alfabeto español, las letras minúsculas han sido rediseñados en su totalidad y algunas mayúsculas. Proyecto aún en desarrollo, se estarán añadiendo modificaciones que permitan una conexión fluida en las ligaduras para que simule un estilo manuscrito formal.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ed2f7854-e2e7-4321-8483-700bfc8e8ed7" />

## Instalación 
Requiere intervención manual en los directorios del sistema con permiso de superusuario.
En distribuciones base Arch, Debian, Fedora, openSUSE, el archivo .ttf se debe mover o copiar en el directorio "/usr/share/fonts/" (puede quedar solo el archivo .ttf o se puede crear una subcarpeta para manter el orden simétrico de los directorios, en ambos será reconocido por el sistema), luego actualizar la caché de fuentes desde terminal con el comando "sudo fc-cache -fv", eso permitirá que pueda ser reconocido por todo el sistema, después, dependiendo de su necesidad, puede aplicar el diseño de fuente desde la configuración del sistema o directamente desde las aplicaciones que permitan escoger tipos de fuentes. 
Para instalar solo a nivel usuario, el proceso es idéntico, debe mover el archivo .ttf al directorio ~/.local/share/fonts/ y luego actualizar la caché de fuentes desde terminal con el comando "fc-cache -fv", (los directorios que comienzan con un punto son carpetas que están ocultas, para hacerlas visibles debe presionar las teclas "ctrl+h")
Debido a la diferencia de permisos entre distribuciones, recomendaré copiar desde termminal usando "cp", para ello simplemente sigue el siguiente comando:
sudo cp [origen] [destino]      . Se respeta el espacio y las direcciones se escriben sin los corchetes, en "origen" es la dirección del archivo .ttf descargado y en "destino" es la dirección del sistema que se encarga de las tipografías. Si crea la carpeta y mueve dentro de esta el archivo .ttf, para copiar la carpeta y su contenido el comando es:
sudo cp -r [origen] [destino]           . El comando "cp" creará una copia exacta del archivo sin eliminar el original. Si prefiere mover el archivo .ttf o carpeta con él (una vez copiado el archivo, se elimina automáticamente en la dirección de origen), usar el comando "mv":
sudo mv [origen] [destino]

Desde el entorno de escritorio KDE Plasma: Preferencias del sistema > Texto y tipo de letras > Tipos de letra. 
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/c5d3164d-eea3-4a3a-9591-91b632087b6d" />

Desde el entorno de escritorio Cinnamon: Configuración del sistema > Apariencia > Selección de tipografías.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/c8778f4c-f2b2-4336-8e9b-a094b629888d" />

Desde el entorno de escritorio XFCE: Configuración > Apariencia > Letras.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ca2de028-0ec1-41d9-8b0e-74e372c22f36" />

(Debido a la amplia cantidad de distribuciones Linux y entornos de escritorio, se recomienda confirmar buscando en la documentación oficial de su distribución para verificar el directorio correspondiente y los pasos a seguir para cambiar el estilo de letra en el sistema)

## Prueba
Se ha testeado en las distribuciones Garuda Mokka, Linux Mint Cinnamon, Nobara Official, openSUSE Tumbleweed, Linux Kodachi, Tuxedo OS y la aplicación de ofimática LibreOffice Write. 

## Objetivo
Proyecto con fin educativo o por mera fruición si os agrada el arte de la caligrafía en su expresión más elemental.
Aplicación práctica para el estudio y aprendizaje del idioma español manuscrito.

<img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/15d47043-4cb8-4bfb-8fca-354c8c2724e4" />




Thanks ;)




                                                           janomasterone                                                                
