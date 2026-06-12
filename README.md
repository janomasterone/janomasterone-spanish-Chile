# janomasterone-spanish-Chile

Escritura en manúscrita para el idioma español.
El diseño corresponde al enseñado en la Escuela Proyecto de Futuro, Paillaco, Región de los Ríos, Chile, América del Sur, Planeta Tierra, Sistema Solar, Vía Láctea, Pequeño Cúmulo de Galaxias, Supercúmulo de Laniakea, Universo... Promoción año 2005 del calendario gregoriano.

## Origen
El archivo con la terminación .ttf ha sido editado usando la aplicación FontForge en su versión Flatpak (puede revisar en https://flathub.org/es/apps/org.fontforge.FontForge para más detalles de la aplicación), se ha utilizado como plantilla un archivo .ttf obtenido en la carpeta de configuración de Fuentes Tipográficas de la Distribución Garuda Mokka, después de instalar diversos paquetes de acceso libre con estilo de escritura cursiva, con nombre "PlaywriteCL[wght].ttf" cuya metadata deriva a https://github.com/TypeTogether/Playwrite que cuenta con licencia "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org". 

## Modificaciones
Proyecto autodidacta,debido a la falta de conocimiento respecto a los script y reglas de búsqueda en las tablas GSUB / GPOS, se han eliminado todas las reglas GSUB / GPOS, se han agregado nuevos anclajes, ligaduras y sustituciones. Los cambios están enfocados en las 27 letras del alfabeto español, las letras minúsculas han sido rediseñados en su totalidad y algunas mayúsculas. Proyecto aún en desarrollo, se estarán añadiendo modificaciones que permitan una conexión fluida en las ligaduras para que simule un estilo manuscrito formal.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ed2f7854-e2e7-4321-8483-700bfc8e8ed7" />

## Instalación 
Requiere intervención manual en los directorios del sistema.
En distribuciones base Arch, Debian, Fedora, openSUSE, el archivo .ttf se debe mover/copiar al directorio "/usr/local/share/fonts/" (puede quedar solo el archivo .ttf o puede crear una subcarpeta para manter el orden simétrico de los directorios, en ambos será reconocido por el sistema) y luego actualizar la caché de fuentes desde terminal con el comando "sudo fc-cache -f -v", eso permitirá aplicar a todo el sistema y que pueda ser reconocido por las aplicaciones, después, dependiendo de su necesidad, puede aplicar el diseño de fuentes desde la configuración del sistema o directamente desde las aplicaciones que permiten escoger tipos de fuentes . Debido a la amplia cantidad de distribuciones Linux y entornos de escritorio, se recomienda confirmar buscando en la documentación oficial de su distribución para verificar el directorio correspondiente y los pasos a seguir para cambiar el estilo de letra en el sistema, desde el entorno de escritorio KDE Plasma: Preferencias del sistema > Texto y tipo de letras > Tipos de letra. 
Para instalar solo a nivel usuario, el proceso es idéntico, debe mover el archivo .ttf al directorio /.local/share/fonts/ y luego actualizar la caché de fuentes desde terminal con el comando "fc-cache -f -v", aquí no es necesario ingresar como root (los directorios que comienzan con un punto son carpetas que están ocultas, para hacerlas visibles debe presionar las teclas "ctrl+h")

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/c5d3164d-eea3-4a3a-9591-91b632087b6d" />

## Prueba
Se está testeando en las distribuciones Garuda Mokka, Linux Mint Cinnamon, Nobara Official, openSUSE Tumbleweed y la aplicación LibreOffice Write. 

## Objetivo
Proyecto con fin educativo o por mera fruición si os agrada el arte de la caligrafía en su expresión más elemental.
Aplicación práctica para el estudio y aprendizaje del idioma español manuscrito.

<img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/15d47043-4cb8-4bfb-8fca-354c8c2724e4" />




Thanks ;)




                                                           janomasterone                                                                
