# TRABAJO INTEGRADOR FINAL: LABORATORIO DE HARDWARE
## RELEVAMIENTO DE REQUISITOS. ESTACIÓN DE TRABAJO PARA INGENIERÍA 

### Introducción al escenario técnico 
Una estación de trabajo de ingeniería requiere un rendimiento balanceado.
Mientras que programas como Visual Studio y Adobe Acrobat consumen principalmente hilos de procesamiento de CPU y memoria RAM para tareas lógicas de texto, el software de diseño como Autodesk Fusion y la suite de simulación Proteus Desing Suite exigen un uso intesivo de procesamiento gáfico (GPU) y cálculo matemático en paralelo. Por lo tanto, el relevamiento se enfoca estrictamente en **requisitos recomenddos** para garantizar fluidez profesional, ignorando los mínimos.

### Tabla Comparativa de Requisitos Recomendados
| Software | Sistema Operativo Compatible | CPU Recomendada | Memoria RAM | Almacenamiento Requerido | Tarjeta Gráfica (GPU) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Autodesk Fusion** | Windows 11 / Windows 10 (64-bit) | 64-bit, 4 o más núcleos físicos (3.0 GHz o superior) | **16 GB** mínimo (Se sugieren **32 GB** para ensambles industriales) | 15 GB o más (Obligatorio en unidades SSD) | Dedicada certificada compatible con DirectX 11 (**8 GB o más de VRAM**) |
| **Proteus Desing Suite** | Windows 11 / Windows 10 (64-bit nativo) | Procesador de alto rendimiento x64 (Intel Core i5/i7 o AMD Ryzen 5/7 de 4+ núcleos) | **16 GB** o superior | 2 GB a 10 GB (Se beneficia de SSD por alta tasa de datos en simulaciones) | Dedicada (NVIDIA o AMD) compatible con OpenGL v2.0 o superior y Direct3D |
| **Adobe Acrobat Reader** | Windows 11 / Windows 10 (64-bit) | Procesador Intel o Amd a 1.5 GHz o más rápido | **4 GB** (Suficiente para PDFs técnicos complejos) | 1 GB de espacio libre disponible | Integrada básica (No requiere GPU dedicada) |
| **Visual Studio Code** | Windows 11 / Windows 10 (64-bit), macOS, Linux | Procesador multinúcleo a 1.8 GHz o superior | **8 GB a 16 GB** (Recomendado para usar extensiones pesadas de IA y depuradores) | 2 GB a 5 GB (Contando el entorno básico, extensiones y compiladores) | Integrada (Utiliza aceleración por hardware básica para renderizar fuentes) |