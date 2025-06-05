# 🌾 Generación y Análisis de Datos Agrícolas Sintéticos con GAN

Este proyecto utiliza una red generativa adversarial (GAN) para crear datos sintéticos del sector agrícola. El objetivo es simular datos realistas que puedan ser usados para análisis exploratorio, entrenamiento de modelos de predicción o pruebas de sistemas sin necesidad de datos reales.

## 🚀 Objetivos del Proyecto

- Generar variables agrícolas sintéticas como:
  - Hectáreas sembradas
  - Temperatura media
  - Precipitación
  - Humedad del suelo
  - Fertilizante utilizado
  - Producción en kilogramos

- Evaluar la coherencia estadística de los datos generados
- Analizar correlaciones y patrones entre variables
- Visualizar relaciones mediante gráficos de dispersión y mapas de calor

---

## 📊 Variables generadas

| Variable          | Descripción                                       |
|-------------------|--------------------------------------------------|
| `hectareas`        | Tamaño del terreno sembrado en hectáreas         |
| `temperatura`      | Temperatura media durante la temporada (°C)      |
| `precipitacion`    | Lluvia acumulada (mm)                            |
| `humedad_suelo`    | Porcentaje de humedad del suelo (%)              |
| `fertilizante_kg`  | Fertilizante aplicado (kg por hectárea)         |
| `produccion_kg`    | Producción obtenida (kg)                         |

---

## 📈 Análisis de Resultados

- **Distribuciones naturales**: Las variables generadas muestran distribuciones razonables (normales, sesgadas o bimodales), lo que indica buen aprendizaje de la GAN.
- **Relaciones coherentes**: La producción guarda relaciones positivas con variables como fertilizante, hectáreas y humedad del suelo.
- **Correlaciones fuertes**: Matriz de correlación muestra valores esperados (ej: `producción` vs `hectáreas` ≈ 0.95).
- **Dispersión realista**: Los diagramas de dispersión revelan patrones no triviales, lo cual valida la complejidad aprendida por la GAN.

---

## 🧠 Tecnología utilizada

- Python 3.10+
- TensorFlow / PyTorch (según implementación GAN)
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (para validaciones estadísticas)

---

## 🏗️ Cómo usar el proyecto

1. **Clona el repositorio:**

```bash
git clone https://github.com/reyandres015/Red-Gan-Datos-Sintenticos.git
cd Red-Gan-Gatos-Sinteticos
```

2. **Ambiente Virtual**
```bash
virtualenv .venv
source .venv/bin/activate
```

3. **Instalar requerimientos**
```bash
pip install -r requirements.txt
```

4. **Abrir notebook** ```UI.ipynb``` 
