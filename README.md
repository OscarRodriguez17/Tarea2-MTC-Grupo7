# Tarea 2 — Métodos y Técnicas de Construcción (MTC)

**Proyecto:** Bodegas BSL Quilicura — Calle Meulén N°331 (ex 451), Lote F, Quilicura, RM.  
**Grupo 7** — Oscar Rodríguez · Nicolás Letelier  
**Entrega:** viernes 13 de noviembre de 2026, 23:59 hrs.  
**Puntaje Total:** 180 puntos (60 Programación + 60 Valorización + 60 Informe).  

---

## Descripción de la tarea

Desarrollar una **programación integral en MS Project**, **valorización a enero 2026** y **preparación de dos estados de pago** (15 % y 35 % con reajuste IPC oficial INE) para la construcción de un edificio de bodegas industriales. Total: **180 puntos**.

## Estructura del repositorio y entregables

```
.
├── README.md                                # Este archivo
├── Enunciado - Tarea 2.docx                 # Enunciado oficial
├── Antecedentes/                            # Itemizado y especificaciones técnicas
│   ├── 1 Itemizado y partidas Tarea 2.xlsx  # Itemizado (41 partidas) + cantidades por grupo
│   ├── 3.1 BSL_EETT - RF - VBR.pdf          # EETT de arquitectura
│   └── 3.2 EETT-PAV-ALL.pdf                 # EETT de pavimentación y aguas lluvias
├── Planos/                                  # Planos oficiales del proyecto
│   ├── 2.1 Planta General.pdf
│   ├── 2.2 Elevaciones.pdf
│   ├── 2.3 Cortes.pdf
│   └── 2.4 Detalle Fundaciones.pdf
└── Trabajo/                                 # Entregables completados
    ├── PLAN.md                              # Plan de trabajo, checklist y parámetros
    ├── 01_Itemizado_Grupo7.xlsx             # Itemizado oficial cantidades Grupo 7
    ├── 02_Duraciones_Grupo7.xlsx            # Rendimientos, cuadrillas y duraciones fundamentadas
    ├── 03_Programacion_Grupo7.mpp           # Archivo nativo Microsoft Project 16.0
    ├── 03_Programacion_Grupo7.xml           # Archivo estándar XML MS Project
    ├── 04_Analisis_PU_Grupo7.xlsx           # Los 4 APU abiertos detallados del Grupo 7
    ├── 05_Valorizacion_Presupuesto_Grupo7.xlsx # Presupuesto 41 partidas + 18 ítems GG + Utilidad
    ├── 06_Estados_de_Pago_Grupo7.xlsx       # EP N°1 (15%) y EP N°2 (35%) con reajuste IPC
    ├── 07_Informe_Tarea2_MTC_Grupo7.docx    # Informe técnico universitario en Word
    ├── 07_Informe_Tarea2_MTC_Grupo7.pdf     # Informe final exportado en PDF (20 páginas)
    ├── 08_Seguimiento_Avance_Grupo7.xlsx    # Seguimiento al 5%, 15%, 25%, 35%, 50%, 75% y Curva S
    └── 09_Precios_Referenciales.md          # Investigación de precios a Enero 2026 y fuentes
```

---

## Estado de Cumplimiento de la Pauta Oficial (180 puntos)

### A. Programación en MS Project (60 pts) — ✔ COMPLETADO
- [x] **Orden de precedencia lógico y constructivo (10 pts):** Secuencia técnica estricta de galpones industriales (tierras $\rightarrow$ fundaciones $\rightarrow$ pedestales $\rightarrow$ acero $\rightarrow$ cubierta $\rightarrow$ radier protegido $\rightarrow$ terminaciones).
- [x] **Duración total + duración fundamentada de cada partida (10 pts):** 193 días hábiles calculados matemáticamente ($D_i = \lceil Q_i / n R_i \rceil$) con cuadrillas ONDAC/CYPE en `02_Duraciones_Grupo7.xlsx`.
- [x] **Relaciones de precedencia con desfases explicadas (10 pts):** Justificación técnica de relaciones $CC+d$ y $FC+d$ (fraguados, curados, sectores) detallada en el informe.
- [x] **Sangría y WBS / EDT jerárquico (5 pts):** Estructura desglosada en capítulos, subgrupos e hitos en `03_Programacion_Grupo7.mpp`.
- [x] **Ruta crítica (10 pts):** Calculada y visible en MS Project (Holgura Total = 0), con radier interior 1.14 como partida crítica y estructura metálica como subcrítica.
- [x] **Seguimiento del avance al 5 %, 15 %, 25 %, 50 % y 75 % (15 pts):** Línea base fijada y matriz de cortes en `08_Seguimiento_Avance_Grupo7.xlsx`.

### B. Valorización y Estados de Pago (60 pts) — ✔ COMPLETADO
- [x] **41 partidas valorizadas a enero 2026 con fuente demostrable (20 pts):** Costo Directo Total de $4.633.771.240 CLP en `05_Valorizacion_Presupuesto_Grupo7.xlsx`.
- [x] **Precios unitarios detallados de las 4 partidas del Grupo 7 (15 pts):** APU abiertos para 1.14 (Radier G-25), 1.19 (Pedestales G-25), 1.26 (Remoción Soleras) y 2.14 (Cierre Bulldog) en `04_Analisis_PU_Grupo7.xlsx`.
- [x] **Gastos generales (18 ítems) + Utilidades fundamentadas (10 pts):** Análisis de los 18 ítems exigidos ($707.600.000, 15,27%) y Utilidad ($417.039.411, 9,00%), totalizando un presupuesto con IVA de $6.852.508.675 CLP.
- [x] **Estados de pago al 15 % y 35 % con reajuste IPC (15 pts):** EP1 al 30-Abr-2026 (15,03% avance) y EP2 al 16-Jun-2026 (35,35% avance) con serie IPC oficial INE base Enero 2026 en `06_Estados_de_Pago_Grupo7.xlsx`.

### C. Informe Técnico Final (60 pts) — ✔ COMPLETADO
- [x] **1. Introducción (5 pts):** Antecedentes, ubicación en Quilicura, características y volúmenes de obra Grupo 7.
- [x] **2. Criterios de duración de actividades (5 pts):** Fórmulas, cuadrillas, maquinaria y tabla de rendimientos.
- [x] **3. Criterios de relación de precedencia (10 pts):** Justificación de secuencias, tabla analítica de desfases y análisis de ruta crítica.
- [x] **4. Criterios de valorización, GG y utilidades (10 pts):** Costeo directo, APU abiertos, memoria de los 18 ítems de GG y tasa de utilidad.
- [x] **5. Estados de pago (10 pts):** Liquidaciones, aplicación del polinomio de reajuste IPC, retenciones y liquidez.
- [x] **6. Conclusiones (20 pts):** Vulnerabilidad de la ruta crítica, riesgos climáticos invernales en Quilicura, sensibilidad inflacionaria y recomendaciones LPS/LOD.
- Documento disponible en Word (`07_Informe_Tarea2_MTC_Grupo7.docx`) y PDF (`07_Informe_Tarea2_MTC_Grupo7.pdf`, 20 páginas).

---

## Datos asignados al Grupo 7

**Cantidades:** columna "7" de la hoja *Cantidades de Obras* del itemizado.

**Partidas con precio unitario detallado (abierto):**

| Ítem | Partida | Unidad | Cantidad G7 | PU Costo Directo | PU Venta (sin IVA) | Monto Total G7 (sin IVA) |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|
| **1.14** | **Hormigón G-25 radier (malla acma C-92)** | m³ | 2.403 | $170.306 | $211.639 | $508.568.517 |
| **1.19** | **Hormigón G-25 Pedestales Galpones y Oficinas** | m³ | 82 | $223.965 | $278.322 | $22.822.404 |
| **1.26** | **Remoción de Soleras** | m | 45 | $5.658 | $7.031 | $316.395 |
| **2.14** | **Cierre perimetral Bulldog** | ml | 364 | $43.868 | $54.515 | $19.843.460 |

---

## Flujo de Trabajo en Git

```bash
# Antes de empezar a trabajar:
git pull

# Guardar avances completados:
git add .
git commit -m "Entrega completa Tarea 2 MTC: Programacion MS Project, Presupuesto, Estados de Pago e Informe"
git push
```
