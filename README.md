# Reinforcement Learning aplicado al Blackjack 🎲🃏  

Este proyecto lo realicé hace aproximadamente año y medio como parte de mi aprendizaje en **Reinforcement Learning**. El objetivo fue aplicar diferentes técnicas de RL al entorno clásico de **Blackjack** incluido en [Gym](https://www.gymlibrary.dev/).  

El trabajo se concentra en un único **notebook Jupyter**, donde están implementados los algoritmos, el entrenamiento de los agentes, las gráficas y el análisis de resultados.  

---

## 🎯 Objetivos  
- Implementar y comparar varios algoritmos de **Aprendizaje por Refuerzo** en Blackjack.  
- Analizar el desempeño en términos de **ganancias promedio**, **ratio de victorias/derrotas** y **estabilidad del entrenamiento**.  
- Explorar si modelos más complejos (DQN) mejoran frente a aproximaciones más simples (Q-Learning).  

---

## 🧠 Algoritmos implementados  
- **Q-Learning**: aproximación tabular clásica.  
- **DQN (Double Q-Network)**: integración de RL con redes neuronales.  
- **DQN mejorado**: con representación enriquecida de estados y mayor capacidad en la red.  

---

## 📊 Resultados principales  
- El **DQN simple** superó al Q-Learning en estabilidad y balance entre pérdidas y ganancias.  
- El **DQN mejorado** no logró mejorar los resultados, lo que sugiere que en entornos altamente estocásticos como Blackjack, **un modelo más complejo no siempre es mejor**.  
- Los agentes tienden a **minimizar pérdidas más que maximizar ganancias**, reflejando la naturaleza del juego donde el dealer siempre tiene ventaja.  

---

## ⚙️ Requisitos  
- Python 3.8+  
- Jupyter Notebook  
- Gym  
- NumPy  
- Pandas  
- Matplotlib  
- TensorFlow / Keras  

Instala las dependencias con:  
```bash
pip install -r requirements.txt
