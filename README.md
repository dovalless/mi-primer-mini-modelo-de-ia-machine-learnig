# 🧠 Mini ChatGPT con Redes Neuronales (Google Colab)

Este proyecto es un **chatbot educativo** construido con **Machine Learning y Redes Neuronales**, cuyo objetivo es **entender cómo funciona un modelo de lenguaje desde dentro**, incluyendo la **visualización de activaciones neuronales**.

⚠️ **No es un LLM como ChatGPT**, sino un **modelo neuronal pequeño**, ideal para aprendizaje, experimentación y fundamentos de IA.

---

## 🚀 Características principales

- ✅ Red neuronal real (TensorFlow / Keras)
- ✅ Entrenamiento con Machine Learning
- ✅ Procesamiento de lenguaje natural (Bag of Words)
- ✅ Clasificación por intenciones
- ✅ Chat interactivo en consola
- ✅ Visualización de activaciones neuronales
- ✅ Heatmaps explicativos por capa
- ✅ Interpretabilidad del modelo (qué palabras activan la red)

---

## 🧠 ¿Qué tipo de IA es?

| Tipo | ¿Incluido? |
|----|----|
| Machine Learning | ✅ |
| Redes neuronales | ✅ |
| NLP clásico | ✅ |
| Reglas IF/ELSE | ❌ |
| LLM (ChatGPT, GPT-4, etc.) | ❌ |
| Comprensión semántica profunda | ❌ |

Este proyecto **NO utiliza respuestas programadas**.  
Las respuestas son generadas a partir de **probabilidades aprendidas durante el entrenamiento**.

---

## 📦 Tecnologías usadas

- Python 3.12
- TensorFlow / Keras
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 ¿Cómo funciona internamente?

1. El texto del usuario se convierte en números (Bag of Words)
2. Los datos entran a una red neuronal multicapa
3. Las neuronas se activan según el input
4. El modelo predice una **intención**
5. Se devuelve una respuesta asociada
6. Se muestran gráficamente las activaciones neuronales

---

## 🧪 Ejemplo de uso

```text
Tú: hola
🤖: Hola 👋 ¿en qué puedo ayudarte?

🧠 Palabras activas en el input:
 • 'hola' → activó la red
