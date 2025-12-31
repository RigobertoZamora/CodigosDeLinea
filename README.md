# Digital Line Coding Simulator

> **Simulador interactivo de Codificación de Línea para telecomunicaciones.**
> Visualiza formas de onda digitales y protocolos de transmisión en tiempo real.

![Status](https://img.shields.io/badge/Status-Completed-success)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20JS%20%7C%20CSS3-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📋 Descripción (About)

Esta herramienta web permite a estudiantes e ingenieros visualizar cómo se comportan las señales digitales bajo diferentes esquemas de codificación. Transforma cadenas binarias en diagramas de tiempo (formas de onda) precisos directamente en el navegador, facilitando el estudio de la capa física del modelo OSI sin necesidad de osciloscopios o hardware dedicado.

🔗 **[Ver Demo en Vivo](https://github.com/RigobertoZamora/CodigosDeLinea)**

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
<img width="1913" height="969" alt="Captura de pantalla 2025-12-30 181922" src="https://github.com/user-attachments/assets/77112acf-47e6-49ad-9c78-73c5896c6f1b" />

> *RZ.html*
<img width="1919" height="971" alt="Captura de pantalla 2025-12-30 182122" src="https://github.com/user-attachments/assets/6fd3aa4c-4095-4318-abb0-b47b86525ef3" />

> *Unipolar.html*
<img width="1919" height="970" alt="Captura de pantalla 2025-12-30 182155" src="https://github.com/user-attachments/assets/0d76db2a-20aa-43e3-b214-92c1eab28560" />

> *AMI.html*
<img width="1919" height="974" alt="Captura de pantalla 2025-12-30 182213" src="https://github.com/user-attachments/assets/f2215f86-fdf2-4df6-9900-499297440502" />

> *NRZ-I.html*
<img width="1919" height="968" alt="Captura de pantalla 2025-12-30 182251" src="https://github.com/user-attachments/assets/ff4338a5-1663-4d80-9d5d-ac068a6f25d3" />

> *ManchesterDif.html*
<img width="1919" height="971" alt="Captura de pantalla 2025-12-30 182236" src="https://github.com/user-attachments/assets/35526ffe-d277-4df7-8a9e-88707b442e62" />
<img width="1917" height="981" alt="Captura de pantalla 2025-12-30 182304" src="https://github.com/user-attachments/assets/d63243cc-122d-4d4e-8b02-b080d674ad88" />

> *index.html*

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
*Desarrollado con ❤️ para la comunidad de ingeniería por Rigoberto Zamora y su equipo: Rodolfo Vega, Moisés Urbina y Elías Melendez.*
