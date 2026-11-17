# can-labeling-coding-system

**Context:** Proyecto grupal de ingeniería para el curso de "Sistemas Electrohidráulicos y Electroneumáticos (MT242)". Incorpora los fundamentos de la programación, configuración y cableado de PLCs en sistemas electroneumáticos.
**Date:** 2026  
**Tools:** SolidWorks, MATLAB, FluidSIM, TíaPortal.
**Status:** Completo.

## Summary
El informe detalla el diseño, modelamiento y construcción de una maqueta electroneumática automatizada para el etiquetado y codificación de latas de comida, usando envases tipo Pringles como estándar. Aborda los cuellos de botella de los procesos manuales mediante el dimensionamiento de actuadores neumáticos y el diseño de una lógica de control secuencial. El objetivo principal es validar empíricamente la viabilidad técnica y la integridad del producto, sirviendo como prueba de concepto escalable para una futura implementación a escala industrial.

## Objective
- Diseñar, modelar lógicamente y construir una maqueta física y funcional de un sistema electroneumático automatizado para la alimentación, etiquetado envolvente y codificación de latas de comida selladas, sirviendo como una prueba de concepto rigurosa para validar su viabilidad técnica en una futura implementación a escala industrial.

## What I did
- Diseñar los parámetros y límites de operación mecánicos de los componentes neumáticos con base en las especificaciones de actuación y normativa UNE.
- Simular los modos de operación de la maqueta de la planta de etiquetado y codificaciones de latas de comida mediante programación PLC en FluidSIM y TiaPortal.
- Validar el funcionamiento electroneumático desde la PLC, pasando por el cableado eléctrico y neumático, y hasta el compresor.

## Results / Evidence
- Key result or metric:
Ejecución esperada de la lógica electroneumática.
- Photos/videos: [![Mira la demo del proyecto](<img width="1920" height="1080" alt="Captura de pantalla (295)" src="https://github.com/user-attachments/assets/f9b9e1c2-1e60-418d-a5d1-0348e56f67d3" />)](https://www.youtube.com/playlist?list=PLFLzO6kCow5g)
- Report: [Descargar el informe completo en PDF](docs/Sistema_Automatizado_Electroneumático_Latas.pdf)

## Limitations and next steps
Al tratarse de una maqueta de laboratorio, el diseño está sujeto a las siguientes restricciones:

* **Materiales y Tolerancias:** El uso de materiales de fabricación rápida (acrílico, madera, PLA/PETG) presenta mayor fricción y desgaste asimétrico en comparación con componentes industriales, lo que puede afectar la repetitividad milimétrica.
* **Restricciones Neumáticas:** El funcionamiento está limitado a la capacidad de caudal del compresor del laboratorio. Además, las posibles variaciones de humedad y presión del aire, junto con el ruido electromagnético, pueden generar fluctuaciones en los sensores.
* **Presupuesto (Control Todo/Nada):** Por limitaciones económicas, se utilizan válvulas y cilindros estándar (todo/nada). Queda excluido el uso de servoneumática o válvulas proporcionales que permitirían un control continuo de fuerza y posición.
* **Alcance del Proceso:** Diseñado exclusivamente para el post-procesamiento de un único formato de envase (lata Pringles de 37g), sin sistemas de ajuste rápido (*changeover*) y sin integración de visión artificial o IoT en esta fase.

El sistema actual sirve como prueba de concepto (PoC) para validar la viabilidad técnica de las siguientes mejoras a escala industrial:

* **Escalabilidad Industrial:** Migración de los materiales de prototipado a componentes de grado industrial (guías lineales, aceros endurecidos) para garantizar la precisión y robustez en entornos de manufactura reales.
* **Control Avanzado:** Implementación de válvulas proporcionales o tecnología servoneumática para lograr un control preciso y continuo de la fuerza de sujeción y la velocidad.
* **Integración de Tecnologías 4.0:** Adición de sistemas de visión artificial para el control de calidad del etiquetado en tiempo real, y protocolos de comunicación IoT industrial para el monitoreo remoto.
* **Flexibilidad de Producción:** Diseño de herramientas flexibles y mecanismos de ajuste rápido que permitan procesar botellas o latas de diferentes volúmenes (sistema *changeover*).
* **Optimización de Throughput:** Recalibración de los tiempos de ciclo y estrangulamientos para alcanzar cuotas de producción industriales (latas por minuto), superando el enfoque actual de movimiento seguro y observable.

## Authors / credits
- Lorenzo A. Mendoza Cordova
- Piero S. Vidaurre Salinas, David A. Nava Laburiano
