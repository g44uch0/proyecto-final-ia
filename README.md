# CelticPig AI: Monitoreo inteligente para la preservación del cerdo celta

Final project for the Building AI course

## Summary

Building AI course project. CelticPig AI es una solución basada en visión por computadora y aprendizaje automático para monitorear la salud y comportamiento del cerdo celta, una raza porcina autóctona en peligro de extinción. Apoya a pequeños productores en zonas rurales.

## Background

El cerdo celta, originario del noroeste de España, es una raza porcina valorada por su carne, pero en riesgo de desaparición debido a su baja rentabilidad y dificultades para ser criada con medios modernos. Esto afecta directamente a pequeños ganaderos rurales y a la biodiversidad ganadera.

Las dificultades que intenta resolver este proyecto incluyen:
* La detección tardía de enfermedades en cerdos.
* El escaso control del ciclo reproductivo en explotaciones extensivas.
* La falta de herramientas digitales para el manejo de razas autóctonas.

Mi motivación personal surge del interés en el desarrollo sostenible del medio rural y en la aplicación de tecnologías avanzadas a la protección de razas en peligro.

## How is it used?

El sistema se instala en granjas rurales. Usa cámaras de bajo coste (como las de Raspberry Pi) y sensores que capturan datos visuales y ambientales. Una red neuronal analiza en tiempo real:
* comportamiento anómalo (falta de movimiento, aislamiento),
* signos visibles de enfermedad (letargo, heridas),
* patrones reproductivos (monta, celo).

Los usuarios (ganaderos, veterinarios, técnicos) reciben alertas y recomendaciones a través de una app móvil o interfaz web.

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f7/Cerdo_Celta_de_Galicia_2.jpg" width="400">

El sistema está pensado para operar incluso con conectividad limitada, almacenando datos localmente y enviándolos cuando haya red disponible.

## Data sources and AI methods

Se recogen los siguientes datos:
* Imágenes y video de los animales en el corral.
* Sensores de temperatura corporal, ambiente y peso.

Fuentes de datos:
* Propias, mediante colaboración con granjas piloto.
* Repositorios abiertos de imágenes ganaderas para entrenamiento inicial.

Técnicas de IA utilizadas:
* Visión por computadora con modelos como YOLOv8 para detección de cerdos y signos visibles.
* Clasificación con redes neuronales convolucionales (CNN) para analizar patrones de comportamiento.

Código de ejemplo:

