# 🏥 Corre_Plan

**Corre_Plan** es una herramienta digital diseñada para ayudar a médicos internos a organizar y visualizar las tareas pendientes de cada paciente en hospitalización, distribuidos por camas. Permite gestionar tareas, editar, borrar, marcar avances con checkboxes, y navegar entre la vista general (panel acumulado) o por cama individual. 💡

---

## 🧩 Funcionalidades implementadas (hasta v.alfa_0.2.8)

### 📌 Panel Acumulado (vista general):
- Ver todas las tareas de todas las camas.
- Añadir nuevas tareas seleccionando número de checkboxes (1–3).
- Editar texto de la tarea (✏️).
- Marcar checkboxes para señalar progreso.
- Eliminar tareas individuales con confirmación (🗑️).
- Eliminar **todas** las tareas de todas las camas con doble confirmación.
- Orden visual hegemónico: **Texto → Checkboxes → Editar → Borrar**.

### 🛏️ Ventana por cama específica:
- Ver tareas solo de una cama específica.
- Añadir tareas desde esa misma ventana (totalmente sincronizado).
- Editar texto de la tarea (con sincronización a panel acumulado).
- Marcar checkboxes interactivos sin necesidad de recargar.
- Borrar tareas individuales (con confirmación).
- Botón para eliminar **todas las tareas de esa cama específica** con doble confirmación.
- Orden visual igual al panel acumulado.

### 💾 Gestión de almacenamiento:
- Todas las tareas y sus estados (checks, estilo) se guardan en `localStorage`.
- Optimización progresiva en estructura y limpieza del almacenamiento para mantener eficiencia y evitar duplicados.

---

## 🧱 Estructura del proyecto

```
Corre_Plan/
├── index.html         # Archivo principal HTML (sin backend)
├── README.md          # Este documento
├── styles.css         # (pendiente para versión futura)
└── script.js          # Lógica JS completa (incluye todas las funcionalidades)
```

---

## 🔢 Historial de versiones

### v.alfa_0.1.X — Estructura inicial
- ✔️ Añadir tareas por cama.
- ✔️ Checkboxes simples.
- ✔️ Primer guardado básico en localStorage.

### v.alfa_0.2.0 — Tareas visibles en panel acumulado.
- ✔️ Se muestran todas las tareas agrupadas por cama.

### v.alfa_0.2.1 — Checks sincronizados.
- ✔️ Se refleja visualmente si las tareas están completas.

### v.alfa_0.2.2 — Interacción total y persistencia.
- ✔️ Checks y estilos se mantienen incluso tras recargar la página.

### v.alfa_0.2.3 — Editar y borrar desde cualquier vista.
- ✔️ Botón de editar y botón de borrar desde vistas por cama.
- ✔️ Sincronización total al editar texto.

### v.alfa_0.2.4 — Confirmaciones de borrado.
- ✔️ Mensaje de confirmación antes de borrar tareas individuales.

### v.alfa_0.2.5 — Mejora estética en orden de tareas.
- ✔️ Hegemonía visual: Texto → Checkboxes → Editar → Borrar.
- ✔️ Justificación adecuada para mantener orden.

### v.alfa_0.2.6 — Botón de borrar todas las tareas (general).
- ✔️ Botón rojo visible solo en panel acumulado.
- ✔️ Doble confirmación antes de borrar TODAS las tareas.

### v.alfa_0.2.7 — Botón de borrar tareas de una sola cama.
- ✔️ Aparece solo en la vista de cama específica.
- ✔️ Misma posición y estilo que el botón general.
- ✔️ Doble confirmación.

### v.alfa_0.2.8 — Orden visual y edición desde cualquier vista.
- ✔️ Posibilidad de editar desde la vista de camas (sin recargar).
- ✔️ Reorganización visual uniforme de todos los elementos de una tarea.

---

## 🚧 Próximas versiones

### 🔜 v.alfa_0.2.9 – Optimización de localStorage
- Reestructurar almacenamiento para evitar redundancias y hacerlo más eficiente.

### 🔮 v.alfa_0.3.0 – Modo configuración
- Ventana de ajustes visuales (tema, orden por defecto, etc).

### 🕰️ v.alfa_0.4.X – Alertas por tiempo o fecha
- Recordatorios en base a tareas críticas o vencimientos.

### 📆 v.alfa_0.5.X – Navegación entre días
- Guardar tareas por fecha.
- Revisar qué se hizo ayer o qué queda pendiente para mañana.

---

## 🧪 Uso local

1. Clona el repositorio:

```bash
git clone https://github.com/javi-lama/Corre_Plan.git
```

2. Abre `index.html` en tu navegador (no se requiere backend).
3. ¡Empieza a gestionar tus tareas hospitalarias como un pro! 💼🧠

---

## 🧠 Autor

Desarrollado con cariño por **Javier Lama**, médico interno, entusiasta de la productividad médica, programación y eficiencia hospitalaria. 💙

---

## 📬 Contacto y sugerencias

¿Tienes ideas, bugs o sugerencias? ¡Puedes abrir un issue o contribuir con un pull request!

---

## ⭐ Licencia

MIT License. Libre para modificar y distribuir con créditos.
