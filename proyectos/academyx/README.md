# AcademyX

Aplicación de **organización escolar familiar con gamificación**, instalable en el celular (PWA). Reúne tareas, rutinas y notas de los hijos, con puntos de experiencia, una mascota que se cuida, un modo pensado para niños y un asistente de IA.

**Estado:** uso privado en familia. · **Sitio:** [academyx-c0135.web.app](https://academyx-c0135.web.app/) (acceso con cuenta)

## Qué ofrece

- **Vista del día y de la semana,** con revisión semanal y recordatorios.
- **Gamificación:** puntos de experiencia, niveles, cuadro de honor, y una mascota con cuidados y vestuario.
- **Modo niño** y temporizador de enfoque.
- **Importación de notas** y gestión de rutinas y asignaciones entre miembros de la familia.
- **Asistente de IA** y recordatorios desde funciones en la nube.

## Stack

React · Vite · JavaScript y TypeScript · Firebase (Authentication, Firestore, Cloud Functions, Hosting) · PWA · GitHub Actions

## En cifras

| | |
|---|---|
| Commits | 61 (19 de agosto al 13 de octubre de 2026) |
| Archivos de prueba | 14: unitarias, de navegador y de reglas de seguridad |
| Despliegue | Automático desde GitHub Actions |

## Calidad

Tras una auditoría interna, el proyecto lleva una **bitácora de remediación** con lo hecho y lo pendiente. Un ejemplo de decisión: los puntos de experiencia se otorgan de forma **atómica e idempotente** con transacciones, para que completar una tarea dos veces no sume dos veces.

El código es privado.
