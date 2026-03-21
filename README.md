# GreenTech Solutions: Refactorización Sostenible 


## 1. Código Original 
En el código encontramos los siguientes problemas de sostenibilidad:
* **Framework innecesario** Se cargaba el framework Bootstrap entero y la librería jQuery 
* **Desperdicio de recursos:** Uso de JavaScript para tareas que el HTML puede hacer solo (como el año del footer).
* **Consumo de datos:** Uso de fuentes externas (Google Fonts) y formatos de imagen pesados que aumentan la huella de carbono.

## 2. Refactorización 
He utilizado HTML5 y CSS, aplicando las siguientes medidas de ecodiseño:

**Imágenes** en Formato WebP y `loading="lazy"` ---> Menos transferencia de datos y ahorro de ancho de banda. 
**Tipografía y Fuentes del Sistema** (`system-ui`) ---> Se eliminan las peticiones a servidores externos (Google Fonts). |
**Código**  Eliminación de JavaScript ---> Menor uso de CPU y ahorro de batería en dispositivos móviles. 
**Eliminacion de frameworks**  CSS sin frameworks ---> Web ultra ligera que funciona en dispositivos antiguos. 

## 3. Conclusion
La nueva versión de la web no solo carga más rápido, sino que es éticamente responsable. Al reducir el peso de la página, disminuimos la energía necesaria en los servidores y en los routers. 

Además, al no exigir un procesador potente para renderizar la web, permitimos que usuarios con dispositivos de gama baja o antiguos puedan navegar perfectamente, extendiendo la vida útil de su hardware y reduciendo la generación de residuos electrónicos (**e-waste**).


## 4. Referencias bibliográficas

[1] A. Project, "Sustainable Web Design", 2023. [En línea]. Disponible en: https://sustainablewebdesign.org

[2] W3C, "Web Sustainability Guidelines (WSG) 1.0", 2024. [En línea]. Disponible en: https://w3c.github.io/sustyweb/

[3] Modern Font Stacks, "The Case for System Fonts: Performance and Sustainability," en System Font Stacks Guide,  
    2024.Disponible en: https://modernfontstacks.com/