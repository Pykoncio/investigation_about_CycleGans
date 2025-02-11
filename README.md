# CycleGAN - Hugo Peralta Muñoz

## Descripción
Este proyecto explora el modelo **CycleGAN**, una técnica de traducción de imágenes a imágenes que permite transformar imágenes de un dominio a otro sin necesidad de contar con datos emparejados. Se analiza la base teórica y se profundiza en la arquitectura del modelo, añadiendo ademas casos de uso reales.

**Materiales:**  
  Todo el análisis se encuentra en el cuaderno:
  - [cycle_gan_theory.ipynb](cycle_gan_theory.ipynb)

## Implementación Práctica
El cuaderno [cycle_gan_example.ipynb](cycle_gan_example.ipynb) contiene una implementación práctica de una *CycleGAN*. Aunque la implementación es muy sencilla, te enseña la base y los pasos a seguir para entender el funcionamiento de esta tecnología.

## Cosas a Mejorar de la implementación Práctica
- Modificar algunas capas de los generadores y/o discriminadores para optimizarlos.

- Ajustar y optimizar los parámetros del modelo para mejorar la calidad de las imágenes generadas.

- Hacer un entrenamiento más denso, con un número mayor de épocas y añadir un guardado y cargado de modelos para hacer el entrenamiento en lotes más pequeños. 


## Bibliografía
- **Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks**. Jun-Yan Zhu, Taesung Park, Phillip Isola, Alexei A. Efros (2017). [Paper oficial](https://arxiv.org/abs/1703.10593)

- Video explicativo sobre CycleGAN: [Youtube Video](https://www.youtube.com/watch?v=D4C1dB9UheQ)

- Web oficial sobre el paper: [Web](https://junyanz.github.io/CycleGAN/)

- Creación de una *CycleGAN*: [Primer ejemplo de creacion](https://hardikbansal.github.io/CycleGANBlog/)

- Creación de otra *CycleGAN*: [Segundo ejemplo de creacion](https://www.geeksforgeeks.org/cycle-generative-adversarial-network-cyclegan-2/)

- Implementación *CycleGAN* (coloreado de imágenes antiguas): [Implementación 1](https://x.com/quasimondo/status/867023499214413830)

- Implementación *CycleGAN* (ciudades antiguas): [Implementacion 2](https://jack-clark.net/2017/06/05/import-ai-issue-45/)

- Implementación *CycleGAN* (Monet a Thomas Kinkade): [Implementacion 3](https://web.eecs.umich.edu/~fouhey//fun/monet/index.html)

- Datasets para *CycleGans*: [Datasets](https://www.kaggle.com/datasets/suyashdamle/cyclegan/data)
