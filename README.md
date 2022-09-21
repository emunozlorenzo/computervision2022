<p align="center"> 
<img src="https://github.com/emunozlorenzo/MasterDataScience/blob/master/img/image2.png">
</p>

# Computer Vision and Machine Learning with Python

## 1. Representanción de una imagen
- Matriz X columnas e Y filas
- Cada valor representa un **píxel**
- **Número de píxeles** se conoce como **resolución**

### 1.1 Imágenes en escala de grises
  - Intensidad mínima: Negro
  - Intensidad máxima blanco
  - Intensidad cuantificada por 2^bits

Ejemplo: para 8 bits, pixel puede tomar intensidades desde 2^0=1 **Negro** a 2^8=256 **Blanco**

Ejemplo: para 1 bit, píxel solo puede tomar 2 valores: 0 y 1. Se conoce como *imagen binaria*

### 1.2 Imágenes en espacio RGB (a color)
  - Cada píxel almacena un color
  - Cada color es representado por una combinación lineal de 3 componentes: _Rojo, Verde y Azul_

Ejemplo: Cubo RGB: Rojo (1,0,0), Verde(0,1,0), Azul(0,0,1)

### 1.3 Espacio de color HSI (Hue, Saturation, Intensity)
  - Hue (Tono): ex: Rojo, verde, azul amarillo
  - Saturation: ex: permite distinguir ente rojo o rosado
  - Intensity: ex: permite distinguir entre rojo oscuro o rojo claro

#### Conversión RGB a HSI
  - [Link](https://www.had2know.org/technology/hsi-rgb-color-converter-equations.html)
