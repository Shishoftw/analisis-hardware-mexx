Análisis de Performance y Rentabilidad Trimestral: Sector Hardware 🖥️📈

📌 Descripción del Proyecto
Este proyecto presenta un análisis integral de las ventas y la rentabilidad de una empresa líder en hardware (Mexx) durante un trimestre crítico. El objetivo principal fue consolidar datos fragmentados y diagnosticar las causas de la caída en el volumen de ventas de categorías estrella, integrando variables macroeconómicas y dinámicas de la cadena de suministro (Comex).

🎯 El Desafío de Negocio
A inicios de 2026, el sector de hardware enfrentó una tormenta perfecta:

Rally de la IA 🤖: El auge de la Inteligencia Artificial disparó la demanda de servidores, elevando los costos globales de componentes NAND (SSDs) y DRAM (Memorias RAM).

Estrategias de Fabricantes: El lanzamiento de nuevas APUs y el incremento en el costo de la VRAM reconfiguraron la competitividad de las PCs armadas.

Price Lag (Desfase de Precios) ⏳: Mientras los costos de reposición subían, competidores con sobrestock antiguo mantuvieron precios bajos, afectando la rotación de nuestro inventario nuevo.

🛠️ Stack Tecnológico
Lenguaje: Python 🐍

Librerías: Pandas (ETL y manipulación de datos), Matplotlib (Visualización de tendencias).

Entorno: Google Colab / Jupyter Notebooks.

⚙️ Proceso Técnico (ETL y Limpieza)
Para garantizar la integridad de los datos, se desarrolló un pipeline de procesamiento:

Consolidación de Datos: Unión de múltiples reportes mensuales .xls en un DataFrame maestro de +3,700 registros.

Sanitización: Corrección de errores de formato en columnas y manejo de tipos de datos financieros (float64).

Anonimización Protegida: Se aplicó un factor de escala a los montos de facturación y ganancia para proteger la confidencialidad de la empresa sin alterar las tendencias porcentuales.

📊 Hallazgos Estratégicos
Anomalía en SKU Gamer (5527): Se detectó una caída del 48.9% en la facturación de febrero.

Correlación de Margen: A pesar de la caída en ventas, se optó por una estrategia de Preservación de Valor, manteniendo márgenes estables en lugar de vender a pérdida frente a competidores con stock desfasado.

Impacto de la Oferta: La saturación de catálogos con APUs de AMD desplazó temporalmente la demanda de configuraciones con GPUs dedicadas de entrada.

<img width="736" height="649" alt="Captura de pantalla 2026-03-10 17420421" src="https://github.com/user-attachments/assets/7dd927b2-28d8-484b-b24f-c9ef1009ffc7" />


💡 Recomendaciones
Sourcing Anticipativo: Monitorear el mercado de semiconductores para anticipar compras de stock antes de picos de demanda por IA.

Reajuste de Mix: Pivotar hacia configuraciones que optimicen el uso de componentes con precios más estables.
