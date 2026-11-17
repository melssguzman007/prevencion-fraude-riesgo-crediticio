# Análisis de Prevención de Fraude y Riesgo Crediticio

Proyecto práctico de análisis de datos orientado a la **detección temprana de fraude en solicitudes de crédito y monitoreo transaccional**, utilizando Python (Pandas, NumPy, Matplotlib y Seaborn).

## Objetivo del proyecto
Simular el flujo de evaluación preventiva de un analista de fraude en una entidad financiera o fintech, aplicando reglas de negocio automatizadas para mitigar pérdidas operativas sin afectar la experiencia de los usuarios legítimos.

## Funcionalidades y reglas implementadas
* **Análisis de biometrías de identidad y documentación:** Detección de scores biométricos bajos (`< 70%`) y validación de documentos apócrifos o adulterados.
* **Detección de patrones inusuales:** Identificación de alta velocidad de intentos en ventanas cortas de tiempo, múltiples dispositivos asociados a un mismo DNI y solicitudes de montos extremos en horarios atípicos.
* **Motor de alertas y bloqueos preventivos:** Clasificación automática de las solicitudes según su nivel de riesgo en tres estados:
  * `Aprobado Automático` (sin alertas).
  * `Revisión Manual (KYC)` (1 alerta detectada).
  * `Bloqueo Preventivo` (2 o más alertas críticas).
* **Cuantificación de impacto:** Cálculo del monto total protegido gracias a las reglas de bloqueo y visualización gráfica de la distribución de casos.

## Tecnologías utilizadas
* **Lenguaje:** Python 3
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn
* **Entorno:** Google Colaboratory / Jupyter Notebook

## Cómo visualizar el proyecto
Podés abrir el archivo `prevencion_fraude_riesgo_crediticio.ipynb` directamente desde este repositorio o ejecutarlo en Google Colab haciendo clic en el botón **Open in Colab** ubicado en la parte superior del notebook.
