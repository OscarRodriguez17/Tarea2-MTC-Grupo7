# Tarea 2 — Métodos y Técnicas de Construcción (MTC)

**Proyecto:** Bodegas BSL Quilicura — Calle Meulén N°331 (ex 451), Lote F, Quilicura, RM.
**Grupo 7** — Oscar Rodríguez · Nicolás Letelier
**Entrega:** viernes 13 de noviembre de 2026, 23:59 hrs.

---

## Descripción de la tarea

Desarrollar una **programación**, **valorización** y **preparación de dos estados de pago** (15 % y 35 %) para la
construcción de un edificio de bodegas industriales. Total: **180 puntos**.

## Estructura del repositorio

```
.
├── README.md
├── Enunciado - Tarea 2.docx                 # Enunciado oficial
├── Antecedentes/                            # Itemizado y especificaciones técnicas
│   ├── 1 Itemizado y partidas Tarea 2.xlsx  # Itemizado (41 partidas) + cantidades por grupo
│   ├── 3.1 BSL_EETT - RF - VBR.pdf          # EETT de arquitectura
│   └── 3.2 EETT-PAV-ALL.pdf                 # EETT de pavimentación y aguas lluvias
├── Planos/                                  # Planos del proyecto
│   ├── 2.1 Planta General.pdf
│   ├── 2.2 Elevaciones.pdf
│   ├── 2.3 Cortes.pdf
│   └── 2.4 Detalle Fundaciones.pdf
└── Trabajo/                                 # Entregables y plan de trabajo
    ├── PLAN.md                              # Plan de trabajo y checklist
    ├── 01_Itemizado_Grupo7.xlsx             # Itemizado con cantidades del grupo 7
    └── 09_Precios_Referenciales.md          # Precios unitarios referenciales (investigación)
```

## Entregables

### A. Programación en MS Project (60 pts)
- [ ] Orden de precedencia lógico y constructivo (10)
- [ ] Duración total + duración fundamentada de cada partida (10)
- [ ] Relaciones de precedencia con desfases, explicadas en informe (10)
- [ ] Sangría (WBS por grupos de actividades) (5)
- [ ] Ruta crítica (10)
- [ ] Seguimiento del avance al 5 %, 15 %, 25 %, 50 % y 75 % (15)

### B. Valorización (60 pts)
- [ ] 41 partidas valorizadas a **enero 2026**, con fuente demostrable (20)
- [ ] Precios unitarios detallados de las 4 partidas asignadas al grupo 7 (15)
- [ ] Gastos generales (18 ítems) + utilidades, fundamentados (10)
- [ ] Estados de pago al 15 % y 35 % con reajuste por IPC (base enero 2026) (15)

### C. Informe (60 pts)
- [ ] Introducción (5)
- [ ] Criterios de duración de actividades (5)
- [ ] Criterios de relación de precedencia (10)
- [ ] Criterios de valorización, gastos generales y utilidades (10)
- [ ] Estados de pago (10)
- [ ] Conclusiones (20)

## Datos asignados al Grupo 7

**Cantidades:** columna "7" de la hoja *Cantidades de Obras* del itemizado.

**Partidas con precio unitario detallado (abierto):**

| Ítem | Partida | Unidad | Cantidad G7 |
|---|---|---|---|
| 1.14 | Hormigón G-25 radier (malla acma C-92) | m³ | 2.403 |
| 1.19 | Hormigón G-25 Pedestales Galpones y Oficinas | m³ | 82 |
| 1.26 | Remoción de Soleras | m | 45 |
| 2.14 | Cierre perimetral Bulldog | ml | 364 |

## Cómo trabajar (Git)

```bash
# Clonar
git clone https://github.com/OscarRodriguez17/Tarea2-MTC-Grupo7.git

# Antes de empezar a trabajar: traer cambios del compañero
git pull

# Guardar avances
git add .
git commit -m "Descripción del avance"
git push
```

**Regla de oro:** hagan `git pull` antes de trabajar y `git push` al terminar, para no pisarse.
Si trabajan en paralelo, avisen qué archivo toca cada uno.
