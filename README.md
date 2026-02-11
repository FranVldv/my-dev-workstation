# My Development Workstation & Hardware Architecture

Este repositorio documenta las especificaciones técnicas de mi estación de trabajo, diseñada para soportar flujos de trabajo intensivos en **Desarrollo Full Stack (NestJS/TypeScript)** y **entrenamiento/ejecución de modelos de IA locales**.

## 🛠️ Build Specifications
He ensamblado y optimizado este equipo personalmente, logrando un equilibrio entre potencia de procesamiento multihilo, capacidad de memoria masiva y una gestión térmica eficiente.

### Componentes Principales:
* **Procesador (CPU):** **AMD Ryzen 7 5700G** (8 núcleos / 16 hilos). 
    * *Justificación:* Ideal para paralelizar tareas, correr múltiples microservicios y contenedores de Docker simultáneamente sin degradación de performance.
* **Memoria RAM:** **48GB DDR4**.
    * *Justificación:* Capacidad extendida para entornos de desarrollo complejos que requieren múltiples instancias de VS Code, navegadores con cientos de pestañas y bases de datos locales pesadas.
* **Gráficos (GPU):** **Sapphire AMD Radeon RX 6700 XT (12GB VRAM)**.
    * *Justificación:* Los 12GB de memoria de video permiten cargar y testear modelos de lenguaje (LLMs) y Stable Diffusion de forma local para prototipado rápido.
* **Almacenamiento (Arquitectura de 3 niveles):**
    1.  **NVMe M.2 (1TB):** Unidad principal para el SO y proyectos activos (máxima velocidad de lectura/escritura).
    2.  **SSD SATA (1TB):** Almacenamiento de alta velocidad para librerías y dependencias (node_modules, docker images).
    3.  **HDD (512GB):** Backup local y archivos estáticos.
* **Refrigeración:** Sistema de refrigeración por aire + flujo de aire optimizado con **6 ventiladores** y sistema de control unificado.
    * *Justificación:* Estabilidad térmica garantizada bajo cargas de trabajo del 100% (compilación masiva o renderizado).

## 🖥️ Hardware Skills Demostrados
- **Montaje Integral:** Ensamblaje de hardware de alta gama y gestión de cableado.
- **Optimización Térmica:** Configuración de curvas de ventilación y presión de aire positiva en el gabinete.
- **Mantenimiento:** Diagnóstico de hardware, actualización de BIOS y mantenimiento preventivo periódico.

## 💡 Filosofía Técnica
Entender la arquitectura del hardware (como la latencia de un NVMe o la gestión de hilos de un Ryzen 7) me permite escribir código más eficiente, optimizando el uso de recursos y mejorando la calidad final del software desarrollado.