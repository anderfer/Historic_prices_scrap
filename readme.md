![Black Friday](https://e00-elmundo.uecdn.es/assets/multimedia/imagenes/2022/11/23/16691602310947.png)


*Proyecto en progreso

## OBJETIVO
El objetivo principal de este proyecto es tratar de aportar informacion real sobre los precios durante el Black Friday, poder comprobar o desmentir las ofertas ofrecidas por diferentes webs

## INICIO DE PROYECTO
Al iniciar este proyecto muy próximo a la fecha del black friday, la unica posibilidad era recoger datos historicos, estos datos historicos de precios no son da fácil acceso.

Se necesita la instalación de una extension de crhome que proporciona histogramas sobre precios. Al acceder a un producto concreto se despliega la extension sobre la web, pero la información no queda registrada en la web de la tienda.

## PRIMEROS PASOS
- Acceder a la web mediante driver
- Encontrar los enlaces a los productos de la pagina de ofertas del Black Friday
- Acceder al producto y programar los clicks necesarios para llegar a la extension
- Mediante movimiento de ratón recorrer el histograma completo
- Sacar un pantallazo de cada movimiento del ratón, que representan un dia cada uno.
- Procesar el texto en la imagen.
- Limpiar el dato de fecha del dato y precio del día.
- Guardar cada producto en un csv distinto.
- Asignar un product ID a cada recolección.
- Importar las tablas a SQL

## RECURSOS UTILIZADOS

Se utiliza Selenium para controlar un navegador web.

Se utiliza la biblioteca Pillow (PIL) para procesar las imágenes capturadas, como recortar, redimensionar y manipular la información visual.

Se emplea la biblioteca pytesseract para realizar reconocimiento óptico de caracteres (OCR) en imágenes, extrayendo texto de las capturas de pantalla.

Se utiliza PyAutoGUI para realizar acciones automatizadas en el sistema operativo, como guardar imágenes o interactuar con archivos y ventanas.




