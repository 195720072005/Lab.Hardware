## Definición y Justificación del Sistema Operativo
&nbsp; Para la propuesta final del sistema informático, se ha seleccionado **Windows 11 Pro de 64 bits**.

### Justificación Técnica:
* **Compatibilidad Nativa de Ecosistema**: Todos los programas asignados cuentan con soporte oficial completo y nativo para Windows.
* **Limitaciones críticas en otras plataformas**: Proteus Design Suite es una aplicación diseñada casi exclusivamente para entornos Windows. No cuentan con soporte nativo para computadoras Apple Mac con procesadores ARM (Apple Silicon M1/M2/M3), lo cual obligaría a utilizar complejas capas de virtualización que degradarían el rendimiento gráfico y de simulación de circuitos.
* **Optimización Gráfica**: Autodesk Fusion aprovecha de manera óptima las librerías DirectX de Microsoft presentes en Windows. Esto permite exprimir al máximo la potencia de las placas de video dedicadas profesionales al realizar render 3D o simulaciones de esfuerzos mecánicos.
* **Seguridad y Redes**: La edición **Pro** de Windows 11 añade capas críticas para un escenario profesional de ingeniería, tales como cifrado de datos mediante BitLocker, soporte mejorado para almacenamiento masivo en red y asignación eficiente de núcleos híbridos de las CPUs modernas (Intel Core de última generación o AMD Ryzen).


## Selección y Justificación de Hardware

### Diseño Integral del Sistema Informático
* **Procesador (CPU)**: AMD Ryzen 5 7600 (6 núcleos / 12 hilos, hasta 5.1 GHz) con cooler Wraith Stealth integrado.
* *Justificación*: Cumple con la frecuencia mayor a 3.0 GHz recomendada por Fusion. Sus 6 núcleos nativos permiten realizar cálculos de simulación de circuitos en Proteus sin congelar el sistema, y otorgan la agilidad necesaria al compilar código o ejecutar entornos virtuales en Visual Studio Code.
* **Placa Madre (Motherboard)**: ASUS Prime B650M-A II (Socket AM5).
* *Justificación*: Ofrece el zócalo AM5 requerido por el procesador y pistas PCIe 4.0/5.0 nativas para máxima velocidad de transferencia de datos. Soporta memoria RAM DDR5 y cuenta con disipación pasiva en sus VRM, garantizando estabilidad en jornadas largas de trabajo de ingeniería.
* **Memoria RAM**: Kingston Fury Beast 32 GB DDR5 (2 x 16 GB, 5600 MHz).
* *Justificación*: Se instalan **32 GB** distribuidos en dos módulos para activar el *Dual Channel*, duplicando el ancho de banda del sistema. Supera el requisito de 16 GB de Fusion y Proteus, permitiendo renderizar piezas mecánicas complejas y ejecutar planos de circuitos en paralelo con fluidez masiva.
* **Tarjeta Gráfica (GPU)**: NVIDIA GeForce RTX 4060 8GB GDDR6 (Gigabyte Eagle OC).
* *Justificación*: Proporciona los **8 GB de VRAM** recomendados por Autodesk. Los núcleos CUDA de NVIDIA aceleran de manera crítica el procesamiento tridimensional en programas de CAD y garantizan total compatibilidad con las librerías Direct3D de Proteus.
* **Almacenamiento (SSD)**: SSD M.2 NVMe WD Black SN770 1TB PCIe Gen4.
* *Justificación*: Cumple con la estricta exigencia de almacenamiento rápido tipo SSD. Ofrece velocidades de lectura de hasta 5150 MB/s, lo que reduce a segundos la apertura de planos pesados, la carga de bases de datos de componentes en Proteus y las dependencias de VS Code.
* **Fuente de Alimentación**: Corsair CX650 M (650W, Certificación 80 Plus Bronze).
* *Justificación*: Otorga la potencia requerida para abastecer la CPU y la GPU RTX 4060 bajo máxima carga de procesamiento de manera segura. La certificación garantiza eficiencia energética y protecciones eléctricas activas (OVP, UVP, SCP).
* **Gabinete**: Cougar MX110.
* *Justificación*: Buena ventilación y flujo de aire para conservar la vida útil de las piezas.
* **Monitor**: LG 24" 24MK430H Full HD IPS.
* *Justificación*: Panel IPS que asegura una fidelidad de color precisa y ángulos de visión óptimos para verificar planos técnicos.
