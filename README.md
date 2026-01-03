# 📊 Telecom Churn Analysis: ¿Por qué se van los clientes?

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Descripción del Proyecto

Este proyecto analiza un dataset de **7,043 clientes** de una empresa de telecomunicaciones (Telecom X) para identificar las causas principales de la evasión de clientes (*Churn*).

El objetivo principal es diagnosticar el perfil de riesgo y proponer estrategias basadas en datos para reducir la tasa de abandono actual del **26.5%**.

---

## 🛠️ Tecnologías Utilizadas

* **Python:** Lenguaje principal.
* **Pandas & NumPy:** Limpieza y manipulación de datos.
* **Matplotlib & Seaborn:** Visualización de datos y storytelling.
* **Google Colab:** Entorno de desarrollo.

---

## 🔍 Análisis Exploratorio y Hallazgos (EDA)

A continuación se presentan los descubrimientos más relevantes del análisis:

### 1. Distribución General de la Evasión
La empresa enfrenta un desbalance significativo. De cada 4 clientes que ingresan, 1 termina cancelando el servicio.

<img width="1311" height="583" alt="chum_rate" src="https://github.com/user-attachments/assets/36e23136-4eeb-438b-b532-469722bf6698" />


### 2. El "Triángulo de Riesgo" (Variables Categóricas)
Se identificaron tres factores críticos que disparan la cancelación:
* **Tipo de Contrato:** La fuga es masiva en contratos "Mes a mes".
* **Internet:** Los usuarios de Fibra Óptica son los más insatisfechos.
* **Pago:** El "Cheque Electrónico" genera alta fricción.

 <img width="1583" height="1184" alt="categoria" src="https://github.com/user-attachments/assets/f3e872c9-52cd-419b-8f2b-58ef90ec1848" />


### 3. Comportamiento Financiero y Temporal
El análisis numérico revela que la pérdida de clientes no es por precio bajo, sino por **valor percibido**.
* **Sensibilidad al Precio:** Los clientes que se van pagan en promedio **$74.44** (vs $61.35 de los leales).
* **Momento Crítico:** La mayor cantidad de abandonos ocurre en los **primeros 6 meses**.


<img width="1583" height="1183" alt="numerico" src="https://github.com/user-attachments/assets/e0ecf91a-4d51-4e33-9608-2f3a318a9014" />

---

## 💡 Conclusiones y Recomendaciones

Basado en los datos, se proponen las siguientes estrategias de negocio:

1.  **Migración de Contratos:** Incentivar el cambio de contratos "Mes a mes" a anuales mediante descuentos del 5-10% para asegurar la permanencia.
2.  **Onboarding VIP:** Implementar un programa de seguimiento intensivo durante los primeros 6 meses para los clientes de Fibra Óptica, asegurando que perciban el valor del servicio.
3.  **Automatización de Pagos:** Ofrecer beneficios (ej. gigas extra) a quienes migren de "Cheque Electrónico" a pago automático con tarjeta, reduciendo la fricción de pago mensual.

---

## 📂 Estructura del Repositorio

* `Telecom_Churn_Analisis.ipynb`: Notebook principal con todo el código y análisis.
* `images/`: Gráficos generados para este reporte.

---

### 📬 Contacto

Si tienes dudas sobre este análisis o quieres aportar, ¡contáctame!
* **Tu Nombre**
* [LinkedIn]([TU_LINK_DE_LINKEDIN](https://www.linkedin.com/in/jharvi-nu%C3%B1ez-martinez-98318b289/))
* [Email](jharvimartinez@gmail.com)
