# 📊 Dashboard Logística (Prog. & Plan.) - Power BI

Este repositorio contiene un ejemplo real de implementación de un dashboard de Power BI conectado a SQL Server, orientado al análisis de indicadores y herramientas enfocadas a la Programación y Planeación de la Demanda en entornos industriales.

El repositorio actual contiene código, fórmulas e información que aplican a 3 tableros:
1. Logística (Prog. & Plan.)
2. Ventas & Logística
3. Distribución & Logística

La diferencia entre estos tableros es únicamente la información desplegada correspondientes a las áreas que tienen acceso al tablero, pues el modelo semántico es el mismo para los 3 dashboards.

El tablero "Logística (Prog. & Plan.)" es el global que contiene toda la información, mientras que los otros dos son para áreas respectivas.

---

## 📌 Objetivo

Clarificar y establecer las directrices para el uso adecuado del tablero de PowerBI “Logística (Prog. & Plan.)” con el fin de garantizar una visualización clara, oportuna y confiable de los datos para contribuir a una toma de decisiones basada en información precisa y actualizada que contribuya a la mejora continua de los procesos logísticos.

---

## 🛠️ Tecnologías Utilizadas

- Power BI Desktop (DirectQuery)
- SQL Server (Consultas a vistas y tablas en producción)
- DAX (Medidas complejas para disponibilidad, eficiencia, forecast, etc.)
- GitHub (para control de versiones y documentación técnica)

---

## 📁 Estructura del Repositorio

```plaintext
PowerBI-OEE-Coflex/
├── pbix/                                   → Archivo PBIX del tablero
├── docs/
│   ├── README.md                           → Descripción general del repositorio
│   ├── Medidas.md                          → Medidas DAX documentadas
│   ├── Columnas_Calculadas.md              → DAX documentadas
│   ├── Tablas_Catalogo.md                   → DAX documentadas
│   ├── Instructivo Dashboard OEE.docx      → Guía de uso del dashboard
│   └── Modelo_Tablero.md                   → Qué mide y cómo funciona
├── sql/ 
│   └── consulta_fuente_OEE.sql             → Consulta SQL base
├── img/
│   ├── preview_dashboard.png               → Captura del dashboard
│   └── modelo_datos.png                    → Relación entre tablas
└── LICENSE                                 → MIT (u otra que se defina)
```

---

## 📷 Preview del Dashboard

![Preview](COFLEX/Logística/preview_dashboard.png)

---

## 📎 Cómo utilizarlo

1. Clona este repositorio.
2. Abre el archivo `pbix/Logística_(Prog._&_Plan.).pbix` con Power BI Desktop.
3. Conecta tu fuente de datos o consulta en SQL Server y Excel.
4. Revisa la documentación en `/docs` para entender cada fórmula y estructura.

---

## 📄 Licencia

MIT – Libre uso con atribución.

