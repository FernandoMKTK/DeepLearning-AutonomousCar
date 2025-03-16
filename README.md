# DeepLearning-AutonomousCar

**DeepLearning-AutonomousCar** es un modelo basado en **Deep Learning** desarrollado en **PyTorch**, diseñado para la conducción autónoma en una pista simulada o en hardware real. Este modelo utiliza una **Red Neuronal Convolucional (CNN)** para predecir comandos de dirección a partir de imágenes capturadas en tiempo real.

---

## ✨ Características
- 🧠 **Red Neuronal Convolucional (CNN)** para el procesamiento de imágenes.
- 🎮 **Control de conducción** basado en predicciones de la CNN.
- 📊 **Entrenamiento con PyTorch** utilizando un conjunto de datos capturado desde la perspectiva del automóvil.
- 🚀 **Inferencia en tiempo real** para la toma de decisiones autónoma.
- 🔧 **Implementación en hardware real o simulación**.

---

## 🛠 Instalación y Configuración

### 1️⃣ **Clonar el Repositorio**
```bash
git clone [https://github.com/tu_usuario/AutonomousCar-PyTorch.git](https://github.com/FernandoMKTK/DeepLearning-AutonomousCar)![image](https://github.com/user-attachments/assets/207d771e-76a7-409e-ae49-b5842d290aba)

```

### 2️⃣ **Instalar Dependencias**
Asegúrate de tener **Python 3.8+** y ejecuta:
```bash
pip install -r requirements.txt
```

### 3️⃣ **Entrenar el Modelo**
Si deseas entrenar el modelo desde cero, ejecuta:
```bash
python train.py
```
Asegúrate de contar con un dataset de imágenes y etiquetas de control.

### 4️⃣ **Prueba del Modelo**
Para probar el modelo en la pista o simulación:
```bash
python test.py
```

---

## 📜 Tecnologías Utilizadas
- **Python 3.6+**
- **PyTorch**
- **OpenCV**
- **NumPy**
- **Matplotlib**
- **TQDM**

---

## 🎯 Resultados y Rendimiento
El modelo ha sido probado en una pista y ha demostrado capacidad de conducción autónoma en entornos simulados. Algunos ejemplos de inferencia:

📸 **Ejemplo de Entrada**  
Imagen capturada por la cámara del automóvil
🠗  
🔀 **Salida del Modelo**  
Ángulo de giro del volante: 45° (derecha) 90° (defrente) 135° (izquierda)

---


## 📜 Licencia
Este proyecto está bajo la licencia **MIT**, por lo que puedes usarlo y modificarlo libremente.

---

## 📧 Contacto
Si tienes preguntas o deseas colaborar, puedes contactarme en:  
📩 **a20196303@pucp.edu.pe**  
📌 **GitHub:** https://github.com/FernandoMKTK


---

🚀 ¡Gracias por visitar este proyecto! Si te gustó, dale ⭐ en GitHub.
