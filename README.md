# Pulse Analytics — Dashboard

> Dashboard analítico SaaS construido desde cero en HTML, CSS y JavaScript puro.  
> [Ver Demo en vivo →](https://gastongarcia1295.github.io/Dashboard-Analitico/)

---

## ¿Qué es Pulse Analytics?

Pulse es un dashboard de gestión y analítica pensado para negocios reales. Permite registrar ventas, clientes, productos y sesiones web, y visualizar toda esa información en gráficos dinámicos que se actualizan según los datos que vos cargás.

No hay datos pre-establecidos. Empezás desde cero y construís tu propio panel.

---

## Funcionalidades

### 📊 Dashboard General
- KPIs en tiempo real: ingresos, órdenes, clientes y ticket promedio
- Comparación automática contra el período anterior (deltas ▲ ▼)
- Gráfico de ingresos y órdenes por mes
- Distribución de ventas por canal
- Estados de órdenes (completadas / pendientes / canceladas)
- Historial de últimas transacciones
- Contador de usuarios en vivo (simulado)
- Heatmap de actividad anual

### 📈 Analíticas
- Sesiones totales, tiempo promedio y tasa de rebote
- Gráfico de sesiones por día
- Distribución por dispositivo (Mobile / Desktop / Tablet)
- Páginas más visitadas con barras de progreso

### 🛒 Ventas
- KPIs del período: ingresos, órdenes, ticket promedio y % completadas
- Gráfico de ingresos por semana
- Historial completo de ventas filtrable por período

### 👥 Clientes
- Total de clientes, clientes con órdenes y LTV promedio
- Ranking de clientes por valor de vida (LTV)
- Cálculo automático de LTV cruzando ventas registradas

### 📦 Productos
- Inventario con stock, precio y estado
- Métricas: productos activos, stock crítico y valor total del inventario

### 📋 Reportes
- Exportación de ventas, clientes, productos y resumen general en `.txt`

### ⚙️ Configuración
- Personalización de nombre, email, empresa y moneda (ARS / USD / EUR)
- Vista de conteo por colección de datos
- Opción para borrar todos los datos

---

## Filtros de período

Los botones **7D · 30D · 90D · 1A** filtran todos los datos del dashboard según el rango seleccionado. Los KPIs, gráficos y tablas se recalculan automáticamente en base a los registros reales.

---

## Persistencia de datos

Todos los datos se guardan en `localStorage` del navegador. Si cerrás y volvés a abrir el archivo, los datos siguen disponibles.

---

## Stack

```
HTML5 · CSS3 · JavaScript ES6+ · Chart.js 4.4
Google Fonts: Plus Jakarta Sans · IBM Plex Mono
```

## Estructura del proyecto

```
Dashboard-Analitico/
├── pulse.html      ← Aplicación completa en un solo archivo
└── README.md
```

---

## Cómo correr localmente

```bash
git clone https://github.com/GastonGarcia1295/Dashboard-Analitico.git
cd Dashboard-Analitico
# Abrí pulse.html en tu navegador
```

## Autor

**Gastón García** — Desarrollador Web  
[gastongarcia1295@gmail.com](mailto:gastongarcia1295@gmail.com)

---

*Desarrollado por Gastón García*
