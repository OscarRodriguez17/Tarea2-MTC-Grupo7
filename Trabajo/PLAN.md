# Tarea 2 — Métodos y Técnicas de Construcción
## Plan de trabajo — GRUPO 7

**Proyecto:** Bodegas BSL Quilicura — Calle Meulén N°331 (ex 451), Lote F, Quilicura.
**Integrantes:** Oscar Rodríguez · Nicolás Letelier (Grupo 7)
**Repositorio:** https://github.com/OscarRodriguez17/Tarea2-MTC-Grupo7
**Entrega:** viernes 13 de noviembre de 2026, 23:59 hrs.
**Puntaje total:** 180 puntos.
**Inicio de obras (según enunciado):** marzo de 2026.

---

## 1. Alcance y entregables

| # | Entregable | Formato | Pts |
|---|---|---|---|
| A | Programación de obra | MS Project (.mpp) | 60 |
| B | Valorización + estados de pago | Excel | 60 |
| C | Informe | Word/PDF | 60 |

### A. Programación (60 pts)
- [ ] Orden de precedencia lógico y constructivo — 10
- [ ] Duración total + duración de cada partida, fundamentada — 10
- [ ] Relaciones de precedencia (con desfases), explicadas — 10
- [ ] Sangría / WBS por grupos de actividades — 5
- [ ] Ruta crítica — 10
- [ ] Seguimiento al 5 %, 15 %, 25 %, 50 % y 75 % — 15

### B. Valorización (60 pts)
- [ ] 41 partidas valorizadas a **enero 2026** con fuente demostrable — 20
- [ ] **PU detallados (abiertos)** de las 4 partidas del grupo 7 — 15
- [ ] Gastos generales (18 ítems) + utilidades, fundamentados — 10
- [ ] **Estados de pago al 15 % y 35 %** con reajuste IPC (base enero 2026) — 15

### C. Informe (60 pts)
- [ ] Introducción — 5
- [ ] Criterios de duración de actividades (con origen de las duraciones) — 5
- [ ] Criterios de relación de precedencia (con/sin desfase) — 10
- [ ] Criterios de valorización, GG y utilidades — 10
- [ ] Estados de pago — 10
- [ ] Conclusiones — 20

---

## 2. Datos asignados al Grupo 7

**Cantidades:** columna "7" de la hoja *Cantidades de Obras* (ver `01_Itemizado_Grupo7.xlsx`).

**Partidas con PU detallado (abiertas):**

| Ítem | Partida | Unidad | Cantidad G7 |
|---|---|---|---|
| 1.14 | Hormigón G-25 radier (malla acma C-92) | m³ | 2.403 |
| 1.19 | Hormigón G-25 Pedestales Galpones y Oficinas | m³ | 82 |
| 1.26 | Remoción de Soleras | m | 45 |
| 2.14 | Cierre perimetral Bulldog | ml | 364 |

---

## 3. Estructura de archivos

```
Tarea 2 MTC/
├── Enunciado - Tarea 2.docx
├── Antecedentes - Tarea 2.zip
├── Planos - Tarea 2.zip
├── extraido/                     (referencias desempaquetadas)
└── Trabajo/
    ├── PLAN.md                   (este archivo)
    ├── 01_Itemizado_Grupo7.xlsx  (itemizado + cantidades + marca PU)
    ├── 02_Duraciones.xlsx        (rendimientos y duraciones por partida)
    ├── 03_Programacion.mpp       (MS Project)
    ├── 04_Analisis_PU.xlsx       (análisis de precios unitarios)
    ├── 05_Valorizacion.xlsx      (valorización + GG + utilidades)
    ├── 06_Estados_de_Pago.xlsx   (EP 15 % y 35 % + IPC)
    ├── 07_Informe.docx / .pdf    (informe final)
    └── 08_Seguimiento.xlsx       (avance 5/15/25/50/75 %)
```

---

## 4. Fases y orden de ejecución

### Fase 0 — Preparación ✔ (en curso)
- [x] Extraer antecedentes (planos, EETT, itemizado)
- [x] Identificar grupo 7: cantidades + 4 partidas de PU detallado
- [x] Crear `01_Itemizado_Grupo7.xlsx`
- [ ] Confirmar calendario/feriados y fecha de inicio (marzo 2026)

### Fase 1 — Duraciones (insumo de A y B)
Para cada una de las 41 partidas definir: cuadrilla, equipo, rendimiento y duración.
Fuentes de rendimiento: EETT del proyecto, fichas de rendimiento de mercado (CYPE, MOP,
manuales de constructores) y bases de datos de precios. Registrar la fuente de cada uno.

### Fase 2 — Programación MS Project
1. Cargar 41 partidas + actividades administrativas (instalación de faenas, trazado,
   terminaciones, aseo, recepción).
2. WBS (sangría): por capítulos y subgrupos.
3. Predecesoras y desfases (fin-comienzo, comienzo-comienzo, etc. — explicar las no FC).
4. Calendario, ruta crítica, duración total.
5. Línea base + seguimiento a 5/15/25/50/75 % (fechas de corte).
6. Exportar `.mpp` y vistas para el informe.

### Fase 3 — Precios unitarios detallados (grupo 7)
Desglose de: materiales, mano de obra, equipos, subcontratos + pérdidas + GG + utilidad, a
precios **enero 2026**. Partidas 1.14, 1.19, 1.26 y 2.14.

### Fase 4 — Valorización
Valorizar las 41 partidas (cantidad G7 × PU). Calcular % de gastos generales a partir de los
18 ítems exigidos y % de utilidad justificado. Presupuesto total de la obra.

### Fase 5 — Estados de pago 15 % y 35 %
Avance físico acumulado → partidas ejecutadas → monto. Reajuste: monto × (IPC mes cierre /
IPC enero 2026). Base: IPC enero 2026. Obras inician marzo 2026, EP al mes de cierre del avance
(habitualmente el mes siguiente).

### Fase 6 — Informe
Redactar las 6 secciones con tablas y capturas de Project. Exportar a PDF.

---

## 5. Pendientes / decisiones
- [x] Integrantes del grupo (Oscar Rodríguez · Nicolás Letelier) — informar por CANVAS
- [x] Repositorio GitHub creado y colaborador invitado
- [x] Fecha de inicio de obras fijada: **marzo de 2026** (según enunciado)
- [ ] Fuente de precios unitarios — investigación en curso (`09_Precios_Referenciales.md`)
- [ ] Valores oficiales de IPC (base enero 2026 y mes de cierre) — verificar en INE
- [ ] Calendario y feriados de 2026 para MS Project
