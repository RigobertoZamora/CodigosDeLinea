# Digital Line Coding Simulator

> **Simulador interactivo de Codificación de Línea para telecomunicaciones.**
> Visualiza formas de onda digitales y protocolos de transmisión en tiempo real.

![Status](https://img.shields.io/badge/Status-Completed-success)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20JS%20%7C%20CSS3-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📋 Descripción (About)

Esta herramienta web permite a estudiantes e ingenieros visualizar cómo se comportan las señales digitales bajo diferentes esquemas de codificación. Transforma cadenas binarias en diagramas de tiempo (formas de onda) precisos directamente en el navegador, facilitando el estudio de la capa física del modelo OSI sin necesidad de osciloscopios o hardware dedicado.

🔗 **[Ver Demo en Vivo](https://rigobertozamora.github.io/Digitales/)**

---

## 🚀 Protocolos Soportados

El simulador incluye soporte completo para los siguientes esquemas de codificación de línea:

* **NRZ (Non-Return-to-Zero):** Variantes NRZ-L y NRZ-I.
* **RZ (Return-to-Zero):** Codificación polar estándar.
* **Manchester:** Estándar (IEEE 802.3) y Diferencial.
* **Bipolar / AMI:** Inversión de Marca Alternada.
* **Alta Densidad:** HDB3 (High Density Bipolar 3).
* **B8ZS:** Bipolar con sustitución de 8 ceros.

## 🛠️ Tecnologías

Este proyecto fue construido utilizando tecnologías web estándar, asegurando compatibilidad total sin instalaciones complejas:

* **Core:** JavaScript (ES6+) para la lógica de señalización.
* **Visualización:** Canvas API / HTML5.
* **Interfaz:** CSS3 Responsivo.

## 📸 Capturas de Pantalla

> *RZ.html*

![Vista General del Simulador](./img/demo-screenshot.png)

## 📦 Instalación y Uso Local

No se requiere backend ni servidores. Para ejecutarlo localmente:

1.  Clona el repositorio:
    ```bash
    git clone [https://github.com/RigobertoZamora/CodigosDeLinea.git](https://github.com/RigobertoZamora/CodigosDeLinea.git)
    ```
2.  Navega a la carpeta del proyecto.
3.  Abre el archivo `index.html` (o cualquiera de los archivos `.html` específicos) en tu navegador favorito.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---
*Desarrollado con ❤️ por Rigoberto Zamora para la comunidad de ingeniería.*
