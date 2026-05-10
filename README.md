# 🏪 Tobacco Shop — Business Performance Analysis 2024 → 2025

> **Interactive business dashboard** analyzing revenue, margin, seasonality and product family segmentation for a tobacco shop with ancillary activities (CBD, vape, lottery, press, services)

---

## 📊 Live Dashboard

| Language | Link |
|---|---|
| 🇬🇧 English | [View dashboard](./dashboard_business_2025_en.html) |
| 🇪🇸 Español | [Ver dashboard](./dashboard_business_2025_es.html) |
| 🇫🇷 Français | [Voir le dashboard](./dashboard_business_2025_fr.html) |

---

## 🎯 Project Overview

This project is a complete business analysis of a real French tobacco shop, comparing fiscal years **2024 and 2025** across **41 product families** and **7 business segments**. It was built as part of a data analytics portfolio to demonstrate end-to-end analytical skills — from raw data to actionable business insights.

**Business context:** The shop operates in a regulated environment (tobacco, lottery, services) with ancillary growth segments (vape, CBD). The challenge is to identify which product families drive profitability, where margin is eroding despite revenue growth, and how to reduce concentration risk

---

## 🔍 Methodology

### 1. Data Collection
Raw sales data extracted from the point-of-sale system, organized by product family and month for both 2024 and 2025

### 2. Data Processing
- Aggregation by product family (41 families) and segment (7 segments: TOBACCO, LOTTERY, SERVICE, PRESS, OTHERS, VAPE, CBD)
- Calculation of revenue, gross margin, margin rate, YoY evolution, and cumulative monthly figures
- Segmentation logic applied to classify each family by growth profile and margin behavior

### 3. Analysis Framework
Five analytical dimensions were explored:

| Dimension | Description |
|---|---|
| **Overview** | Cumulative revenue & margin growth 2024 vs 2025 |
| **Segmentation** | Macro view by business segment |
| **Family classification** | 41 families ranked by growth and margin profile |
| **Revenue × Margin matrix** | Bubble chart positioning each family by CA and margin rate |
| **Seasonality** | Monthly revenue patterns and peak identification |

### 4. Visualization
Built with **Chart.js 4.4.1** — pure HTML/CSS/JS, no framework, no backend. Fully portable and runs in any browser

---

## 📈 Key Findings

### Revenue & Margin
- **+24.0% revenue growth** in 2025 vs 2024 (€1.31M vs €1.06M)
- **+20.1% gross margin growth** (€118.5k vs €98.7k)
- **Margin rate slightly down** at 9.04% vs 9.33% — revenue grew faster than margin

### Concentration Risk
- **5 families out of 41 generate 80.6% of total revenue**
- Top 3 alone (cigarettes, scratch cards, loto) = 69.5% of revenue
- High dependency on regulated products = structural risk

### Growth Drivers
The top 5 families by revenue growth account for **84.3% of total growth**:

| Family | Revenue growth | Margin rate |
|---|---|---|
| 110 Cigarettes | +22.0% | 8.35% |
| Loto | +33.3% | 5.20% |
| Scratch cards | +16.1% | 5.19% |
| Card payments | +72.4% | 1.57% |
| Roll-your-own | +25.8% | 8.35% |

### Margin Pressure Alerts
Several high-growth families show significant margin erosion:

| Family | Revenue growth | Margin shift |
|---|---|---|
| CBD flowers & resins | +126.4% | −12.77 pt |
| Nicotine pouches | +90.2% | −7.72 pt |
| E-cigarettes refills | +78.7% | −6.60 pt |

### Seasonality
- **July** is the strongest month at 11.60% of annual revenue (+29% vs monthly average)
- **Summer peak** (July-August) + **year-end** (December) are the 3 main activity peaks
- **November** is the weakest month in 2025

---

## 💡 Strategic Recommendations

**1. Reduce concentration risk**
Develop complementary high-margin product lines (e-liquid, stationery, gifts) to reduce dependency on tobacco and lottery

**2. Protect margin on fast-growing families**
Flowers and resins CBD and e-cigarette refills are experiencing rapid growth, but margins are shrinking: a new pricing strategy, renegotiation with suppliers or the entry of new suppliers are necessary

**3. Leverage seasonality**
Stock high-margin products (magnets, greeting cards, gifts) ahead of summer and December peaks

**4. Monitoring of high-margin families in decline**
The e-cigarette market (-29.1%) is in structural decline, but with some growth in refills (+78,73%)

---

## 🛠️ Technical Stack

- **Data source:** Point-of-sale export (real retail data, anonymized)
- **Processing:** Google Sheets (aggregation, KPI calculation, segmentation)
- **Visualization:** Chart.js 4.4.1 (bar, line, bubble, doughnut charts)
- **Languages:** HTML5, CSS3, vanilla JavaScript
- **Available in:** 🇬🇧 English · 🇪🇸 Spanish · 🇫🇷 French

---

## 📁 Repository Structure

```
📦 tobacco-shop-business-analysis
 ┣ 📄 README.md 
 ┣ 📊 dashboard_business_2025_en.html   # English version
 ┣ 📊 dashboard_business_2025_es.html   # Spanish version
 ┗ 📊 dashboard_business_2025_fr.html   # French version
```

---

## 👤 About

Built by **Guillaume** as part of a data analytics portfolio project.
Transitioning into data analytics with a background in management and operations.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](www.linkedin.com/in/guillaume-sanchez-124839337)

---

---

# 🏪 Análisis de Rendimiento de Negocio 2024 → 2025

> **Dashboard interactivo** que analiza el CA, el margen, la estacionalidad y la segmentación de familias de productos de un estanco con actividades complementarias (CBD, vape, lotería, prensa, servicios).

---

## 🎯 Descripción del proyecto

Este proyecto es un análisis completo de un estanco francés real, comparando los ejercicios **2024 y 2025** en **41 familias de productos** y **7 segmentos de negocio**. Fue desarrollado como parte de un portfolio de análisis de datos para demostrar competencias analíticas de principio a fin — desde los datos brutos hasta los insights de negocio.

---

## 🔍 Metodología

### 1. Recopilación de datos
Datos de ventas extraídos del sistema de punto de venta, organizados por familia de productos y mes para 2024 y 2025.

### 2. Procesamiento
- Agregación por familia de productos (41 familias) y segmento (7 segmentos)
- Cálculo de CA, margen bruto, tasa de margen, evolución interanual y cifras mensuales acumuladas
- Lógica de segmentación aplicada para clasificar cada familia según su perfil de crecimiento y comportamiento del margen

### 3. Dimensiones de análisis

| Dimensión | Descripción |
|---|---|
| **Vista general** | Crecimiento acumulado de CA y margen 2024 vs 2025 |
| **Segmentación** | Vista macro por segmento de negocio |
| **Clasificación por familia** | 41 familias clasificadas por crecimiento y perfil de margen |
| **Matriz CA × Margen** | Posicionamiento de cada familia por CA y tasa de margen |
| **Estacionalidad** | Patrones mensuales e identificación de picos de actividad |

---

## 📈 Hallazgos principales

- **+24,0% de crecimiento del CA** en 2025 vs 2024 (1,31M€ vs 1,06M€)
- **+20,1% de crecimiento del margen bruto** (118,5k€ vs 98,7k€)
- **Tasa de margen ligeramente a la baja** al 9,04% vs 9,33%
- **5 familias de 41 generan el 80,6% del CA total** — riesgo de concentración elevado
- **Julio** es el mes más fuerte con el 11,60% del CA anual
- Familias con fuerte crecimiento pero presión de margen: CBD flores y resinas (+126,4%, −12,77 pt), Recarga cigarillos elec (+78,7%, −6,60 pt)

---

## 🛠️ Stack técnico

- **Fuente de datos:** Exportación del punto de venta (datos reales anonimizados)
- **Procesamiento:** Google Sheets
- **Visualización:** Chart.js 4.4.1
- **Lenguajes:** HTML5, CSS3, JavaScript
- **Disponible en:** 🇬🇧 Inglés · 🇪🇸 Español · 🇫🇷 Francés

---
