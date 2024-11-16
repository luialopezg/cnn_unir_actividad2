# **Clasificación de Imágenes con Redes Neuronales Convolucionales (CNN) usando CIFAR-10**

Este proyecto explora el uso de **Redes Neuronales Convolucionales (CNN)** para la clasificación de imágenes utilizando el famoso conjunto de datos **CIFAR-10**. El objetivo principal es aprender y practicar diferentes arquitecturas y técnicas avanzadas, como *data augmentation* y *transfer learning*, para obtener el mejor rendimiento en la tarea de clasificación.

## **Descripción del Proyecto**

El conjunto de datos **CIFAR-10** contiene 60,000 imágenes divididas en 10 clases (avión, coche, ave, gato, ciervo, perro, rana, caballo, barco y camión). Este proyecto implementa múltiples arquitecturas de CNN para aprender y clasificar estas imágenes, comparando su rendimiento en función de diferentes configuraciones.

El proyecto está organizado en cuatro fases principales:
1. **Arquitectura básica**: Una CNN simple para entender los fundamentos.
2. **Profundización de la red**: Introducción de *batch normalization* y más filtros para capturar patrones complejos.
3. **Data Augmentation**: Aumentar la robustez del modelo simulando variaciones en los datos.
4. **Transfer Learning**: Uso de **MobileNetV2**, un modelo preentrenado en **ImageNet**, para mejorar significativamente el rendimiento.

## **Resultados Principales**

| Modelo                   | Precisión Global | Observaciones Clave                                      |
|--------------------------|------------------|---------------------------------------------------------|
| CNN básica               | 70%             | Buen comienzo, pero limitado en clases complejas.       |
| CNN con capas profundas  | 73%             | Mejor captura de patrones complejos.                    |
| CNN con data augmentation | 71.4%           | Sin mejoras significativas, pero útil para robustez.    |
| MobileNetV2 (Transfer Learning) | 86%       | Resultados sobresalientes con un modelo preentrenado.   |

### **Reflexión**
Cada etapa del proyecto enseñó algo valioso sobre la práctica con CNN:
- La importancia de los fundamentos y las arquitecturas progresivamente complejas.
- Las limitaciones y ventajas de técnicas como el *data augmentation*.
- El poder del *transfer learning* al aprovechar redes preentrenadas.

## **Estructura del Proyecto**

```plaintext
├── notebooks/
│   ├── basic_cnn.ipynb          # Implementación del modelo básico
│   ├── deeper_cnn.ipynb         # Arquitectura más profunda con batch normalization
│   ├── data_augmentation.ipynb  # Experimentos con data augmentation
│   ├── transfer_learning.ipynb  # Transfer learning con MobileNetV2
├── data/
│   ├── cifar10/                 # Conjunto de datos CIFAR-10 (descargado automáticamente)
├── requirements.txt             # Dependencias del proyecto
├── README.md                    # Este archivo

Requisitos

Antes de comenzar, asegúrate de instalar las dependencias necesarias:
pip install -r requirements.txt

Las dependencias incluyen:

    tensorflow
    keras
    matplotlib
    numpy
    jupyter

Si trabajas con Transfer Learning, asegúrate de tener instalado tensorflow_hub:
pip install tensorflow-hub

pip install tensorflow-hub

## Ejecución del Proyecto

1.    Clona el repositorio:
git clone https://github.com/tu_usuario/tu_repositorio.git


2.    Navega al directorio del proyecto:

cd tu_repositorio

3.    Abre los notebooks en Jupyter:

    jupyter notebook

4.    Explora los notebooks en la carpeta notebooks para ver cada fase del proyecto.

Aprendizajes Clave

    CNN básica: Entender las capas convolucionales y de pooling.
    Batch normalization: Cómo estabilizar y acelerar el entrenamiento.
    Data augmentation: La importancia de aumentar la diversidad de datos.
    Transfer learning: Usar modelos preentrenados para lograr resultados avanzados rápidamente.

Contribuciones

Si deseas contribuir, abre un issue o realiza un pull request con tus sugerencias. ¡Tu colaboración es bienvenida!
Licencia

Este proyecto está bajo la licencia MIT. Puedes utilizarlo libremente con fines educativos y de investigación.

¡Gracias por explorar este proyecto! Aprender con redes neuronales es un viaje desafiante pero increíblemente gratificante. 🚀


### **Cómo Usar**

1. Copia este texto y guárdalo como `README.md` en el directorio raíz de tu repositorio.
2. Personaliza los enlaces y nombres según sea necesario (por ejemplo, reemplaza `tu_usuario` y `tu_repositorio` con los tuyos).
3. Súbelo a tu repositorio en GitHub, y estará listo para que todos lo vean.

¡Espero que lo encuentres útil! 
