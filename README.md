# Control de Diabetes

App web para **llevar el día a día de una persona con diabetes**: ver el plan de insulina, consultar qué se puede comer, seguir menús semanales y registrar los controles de glucemia.

🔗 **Demo en vivo:** https://controldiabetes1.netlify.app/

## Qué hace

La app tiene cuatro pestañas:

1. **Controles de glucemia e insulina**
   - El plan de insulina basal y de corrección, con las dosis por comida.
   - Tabla de ajuste: cuántas unidades sumar según el valor de glucosa.
   - Guía de **hipoglucemia** (glucosa < 70): síntomas y qué hacer en el momento.
2. **Dieta**
   - Bebidas de consumo libre, alimentos prohibidos y porciones permitidas para desayuno/merienda y almuerzo/cena.
3. **Menús variados**
   - Menús por día de la semana (desayuno, almuerzo, merienda y cena) que siguen las pautas de la dieta.
4. **Registro diario**
   - Cargás el valor de glucosa de cada comida y notas del día.
   - Tabla histórica con colores según el rango del valor, filtro por fechas, edición y borrado.
   - Estadísticas: promedio general y cantidad de registros.
   - **Exportación a CSV** para llevarle los datos al médico.

También muestra un versículo del día al abrir la app.

## Tecnología

- Un solo `index.html` con HTML, CSS y JavaScript vanilla.
- Los registros se guardan en `localStorage` (no salen del dispositivo).
- Deploy en Netlify.

## Correrlo localmente

Abrí `index.html` en el navegador.

> ⚠️ Las dosis y la dieta que trae cargadas son las de un plan médico concreto. No son una recomendación: cada persona tiene que usar las que le indique su médico.

---

Proyecto de **Sebastián Soba**.
