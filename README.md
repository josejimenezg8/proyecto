# Plataforma de Datos para Recetas y Wearables (INF3862)

Proyecto del curso **Plataformas Big Data para Data Science** (Pontificia Universidad Católica de Chile).

* **Estudiante:** José Jiménez G. (Magíster en Estadística UC)
* **Profesor:** Sebastián Hagedorn
* **Ayudante:** Tomás Werth

---

## Caso de Uso
**Sistema de recomendación nutricional y seguimiento post-entrenamiento:**
La plataforma integra el catálogo de recetas de *Food.com* con registros de actividad física de relojes inteligentes (*wearables*) para sugerir preparaciones acordes al desgaste energético diario del usuario (por ejemplo, priorizando proteínas tras sesiones de fuerza o carbohidratos tras ejercicio cardiovascular), filtrando estrictamente según sus restricciones y regímenes alimentarios (vegano, celíaco, alergias, etc.).

---

## Entregables y Estructura del Repositorio

El repositorio está organizado por etapas según las entregas del curso:

* **Entrega 1 (E1) — Diseño de datos (Objetivo, fuentes, OLTP/OLAP y consultas):**
  * [Informe E1 (PDF)](entregas/E1/informe.pdf)
  * [Anexos y Diagramas](entregas/E1/anexos/)
* **Entrega 2 (E2) — Ingesta, transformación y procesamiento:** *(30 de noviembre de 2026)*
* **Entrega 3 (E3) — Datos para ML y arquitectura final:** *(14 de diciembre de 2026)*
* **[Registro de decisiones](decisiones.md):** Bitácora con las decisiones y cambios realizados a lo largo del proyecto.

```text
proyecto/
├── README.md
├── decisiones.md
├── datos/
│   └── README.md         
└── entregas/
    └── E1/
        ├── informe.pdf    # Documento principal + anexos incluidos
