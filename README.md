# 📈 Indexed Funds Analytics / Analítica de Fondos Indexados  

## 🎯 Objective / Objetivo  
**EN:** This project aims to create a web application that displays the **S&P 500 index fund** graph, allowing users to select a future time interval. A **machine learning model** trained on S&P 500 data will estimate the probability of the fund increasing or decreasing.  
**ES:** Este proyecto tiene como objetivo crear una aplicación web que muestre la gráfica del **fondo indexado S&P 500**, permitiendo a los usuarios seleccionar un intervalo de tiempo futuro. Un **modelo de machine learning** entrenado con datos del S&P 500 estimará la probabilidad de que el fondo aumente o disminuya.  

---

## 🗺 **Roadmap / Hoja de Ruta**  
### **EN:**  
1. Develop a **web interface** to visualize the **S&P 500 index fund** over different time intervals.  
2. Implement a **machine learning model** to predict fund trends based on past data.  
3. Integrate a **confidence metric** to indicate how reliable the prediction is.  

### **ES:**  
1. Desarrollar una **interfaz web** para visualizar el **fondo indexado S&P 500** en diferentes intervalos de tiempo.  
2. Implementar un **modelo de machine learning** para predecir las tendencias del fondo basadas en datos históricos.  
3. Integrar una **métrica de confiabilidad** que indique qué tan confiable es la predicción.  

---

## 💡 **Technologies Used / Tecnologías Utilizadas**  
| Technology / Tecnología | Description / Descripción |
|------------------------|--------------------------|
| **HTML, CSS, JS** | Web development for the interface. / Desarrollo web para la interfaz. |
| **Python** | Backend for data processing. / Backend para el procesamiento de datos. |
| **Econometrics** | Statistical analysis for financial predictions. / Análisis estadístico para predicciones financieras. |
| **Machine Learning** | AI model for market trend prediction. / Modelo de IA para la predicción de tendencias del mercado. |

---

## 📊 **S&P 500 Data / Datos del S&P 500**  
**EN:** The project requires a dataset containing historical **S&P 500** values. These data will be used for:  
- Plotting the fund’s performance on the web page.  
- Training the **AI prediction model**.  
- Extracting relevant financial insights.  

**ES:** El proyecto necesita un conjunto de datos con valores históricos del **S&P 500**. Estos datos se utilizarán para:  
- Graficar el rendimiento del fondo en la página web.  
- Entrenar el **modelo de predicción con IA**.  
- Extraer información financiera relevante.  

**Data sources / Fuentes de datos:**  
- **Kaggle** (https://www.kaggle.com/)  
- **Other open financial databases** if needed.  

---

## 🤖 **AI Model Training / Entrenamiento del Modelo de IA**  
**EN:** The **AI model** will be trained using historical **S&P 500** data to predict future trends. The following platforms will be considered:  
**ES:** El **modelo de IA** será entrenado con datos históricos del **S&P 500** para predecir tendencias futuras. Se considerarán las siguientes plataformas:  

| Platform / Plataforma | Description / Descripción |
|----------------------|--------------------------|
| [Microsoft Cloud Learning](https://learning.cloud.microsoft/my-learning/bookmarks) | Cloud-based AI training. / Entrenamiento de IA en la nube. |
| [Hugging Face](https://huggingface.co/models) | Pre-trained ML models. / Modelos de ML preentrenados. |
| [PyTorch Model Zoo](https://pytorch.org/serve/model_zoo.html) | Neural network models. / Modelos de redes neuronales. |
| [TensorFlow Hub](https://www.tensorflow.org/hub) | AI model repository. / Repositorio de modelos de IA. |

**EN:** Additionally, significant events (e.g., **COVID-19, elections, economic crises**) that affect markets will be factored into the model.  
**ES:** Además, se considerarán eventos significativos (e.g., **COVID-19, elecciones, crisis económicas**) que afectan los mercados en el modelo.  

---

## 🎨 **User Interface Design / Diseño de Interfaz**  
| Feature / Función | Description / Descripción |
|------------------|--------------------------|
| **Homepage** | Displays an **S&P 500** graph with adjustable time intervals. / Muestra una gráfica del **S&P 500** con intervalos de tiempo ajustables. |
| **Dropdown Menu** | Future feature: Select other index funds. / Función futura: Seleccionar otros fondos indexados. |
| **Investment Simulation** | Users select an investment amount and time period. / Los usuarios eligen un monto de inversión y un periodo de tiempo. |
| **Analysis Button** | Triggers AI prediction and confidence display. / Activa la predicción de IA y muestra la confiabilidad. |

---

## 📌 **Financial Concepts / Conceptos Financieros**  
**EN:** The project is based on **portfolio theory** and financial modeling concepts such as:  
**ES:** El proyecto se basa en la **teoría de portafolios** y conceptos de modelado financiero como:  

- **Hidden Markov Model** (*Capa oculta de Márkov*): Future data depends exclusively on past data.  
- **Risk Premium** (*Prima de riesgo*): Difference between return on variable-income and fixed-income assets.  
- **Sharpe Ratio** (*Ratio de Sharpe*): Measures return per unit of risk (>1 means investment is worthwhile).  
- **Sortino Ratio** (*Ratio de Sortino*): Evaluates portfolio performance considering downside risk.  
- **Black-Litterman Model**: Uses statistical data from an investment portfolio to estimate returns.  

---

## 📌 **Mathematical Model / Modelo Matemático**  
| Formula / Fórmula | Description / Descripción |
|------------------|--------------------------|
| **Risk Aversion = Black Litterman / Stock Index Deviation** | Measures the reluctance of investors to take risks. / Mide la aversión de los inversionistas al riesgo. |
| **Implicit Equilibrium Excess = Relative Weights * VarCov Matrix * Risk Aversion** | Determines expected portfolio returns. / Determina los retornos esperados del portafolio. |
| **Relative Weights = Invested Value / Total Portfolio Value** | Ratio of each asset’s value in a portfolio. / Relación del valor de cada activo en un portafolio. |

---

## 🚀 **How to Use This Project / Cómo Usar Este Proyecto**  
1. **EN:** Open the web page and select the **S&P 500** time interval.  
   **ES:** Abre la página web y selecciona el intervalo de tiempo del **S&P 500**.  
2. **EN:** Set an **investment amount** and time frame.  
   **ES:** Establece un **monto de inversión** y un período de tiempo.  
3. **EN:** Click **Analyze** to run the AI model and get a confidence score.  
   **ES:** Haz clic en **Analizar** para ejecutar el modelo de IA y obtener un puntaje de confiabilidad.  

---

## 📜 **License / Licencia**  
**EN:** This project is under the MIT License.  
**ES:** Este proyecto está bajo la licencia MIT.  
