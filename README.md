# 📷 Cámara Georeferenciada - Programa Agropecuario Peine

Esta aplicación web fue desarrollada como una herramienta de apoyo para el levantamiento de información territorial y monitoreo en terreno del **Programa Agropecuario de Peine**. 

Su función principal es capturar fotografías utilizando la cámara del dispositivo móvil y estampar automáticamente los datos de geolocalización, fecha, hora y logotipos institucionales en la imagen final, facilitando el registro y la trazabilidad de las actividades agrícolas y ganaderas en la zona.

## 🌟 Características Principales

* **Georeferencia en UTM:** Obtiene las coordenadas GPS del dispositivo y las convierte automáticamente al formato UTM (Zona, Este, Norte) mediante la librería matemática `proj4js`.
* **Dos Botones de Captura:** La interfaz incluye dos opciones de disparo para adaptarse a la necesidad del terreno:
  * **Captura Normal (Fotograma de video):** Toma una foto rápida basada en la resolución de lo que se visualiza en la pantalla del navegador.
  * **Captura HD (Fotográfica):** Utiliza la API avanzada del dispositivo para solicitar al sensor de la cámara que tome una fotografía real en su máxima definición, ideal para cuando se necesita leer detalles o abarcar un paisaje amplio.
* **Marca de Agua Inteligente:** Genera un recuadro semitransparente en la esquina inferior derecha de la fotografía con todos los datos espaciales y logotipos. El recuadro es dinámico y escala proporcionalmente según la resolución de la cámara.
* **100% Web y Responsivo:** No requiere descargar ni instalar aplicaciones (APK). Funciona directamente en navegadores móviles estándar (Chrome, Safari, etc.).

## ⚙️️ Requisitos de Funcionamiento (Permisos)

Para que esta herramienta funcione adecuadamente, es **estrictamente necesario** que el usuario otorgue al navegador web de su teléfono (Chrome, Safari, etc.) los siguientes permisos cuando el sistema los solicite:

1. **Cámara:** Para acceder al lente del dispositivo y capturar la imagen.
2. **Ubicación (GPS):** Para obtener las coordenadas geográficas exactas en tiempo real.
3. **Almacenamiento:** Para permitir la descarga y guardado automático de la fotografía generada en la galería o archivos del teléfono.

*⚠️ Si se deniega alguno de estos permisos, la aplicación no podrá acceder al hardware del teléfono y no funcionará correctamente.*

## 🔒 Privacidad y Protección de Datos

Esta aplicación ha sido diseñada respetando al máximo la privacidad del usuario:
* **Procesamiento Local:** La aplicación funciona en su totalidad dentro de tu propio navegador.
* **Cero Almacenamiento:** **No aloja, no recopila ni envía datos personales**, fotografías, coordenadas de ubicación (GPS/UTM) ni registros sobre el uso de la herramienta a ningún servidor externo. 
* Toda fotografía tomada con esta aplicación se procesa en la memoria RAM del teléfono y se descarga directa y exclusivamente en el almacenamiento interno de tu dispositivo.

## 🚀 Alojamiento y Herramientas

Para garantizar su accesibilidad y el correcto funcionamiento de los sensores del teléfono (los cuales exigen protocolos de seguridad estrictos), esta aplicación se aloja utilizando **GitHub Pages**. 

Esta es una plataforma de **uso gratuito** proporcionada por GitHub que permite desplegar páginas web estáticas con certificados de seguridad (HTTPS) sin costo alguno de servidores ni mantención.

## 📄 Licencia y Uso

Este es un proyecto de **código abierto (Open Source)** y de **libre uso**. 

Cualquier persona, equipo técnico o comunidad puede acceder al código fuente, utilizarlo, modificarlo o adaptarlo de forma totalmente gratuita según sus propias necesidades de levantamiento de datos territoriales.

---
*Aplicación Web se encuentra en desarrollo para mejorar el registro de atenciones del programa en el territorio de Peine.*
