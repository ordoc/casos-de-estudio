# Casos de estudio

Cinco aplicaciones web que he construido en el año 2026. **El código fuente es privado**: este repositorio documenta qué hace cada una, cómo está armada y qué decisiones se tomaron, con cifras verificables de sus repositorios.

> Las construí con apoyo de asistentes de IA: yo defino los requisitos, reviso, pruebo y decido; la IA acelera la escritura. Por eso dejo a la vista las pruebas automáticas y las decisiones, que son lo que se puede comprobar.

| Proyecto | Qué es | Stack principal | Pruebas automáticas | Estado |
|---|---|---|---|---|
| [Cosechas](proyectos/cosechas/) | Finanzas familiares con contexto colombiano | React, TypeScript, Firebase | Más de 1.100 | Beta cerrada por invitación |
| [Ordoc English](proyectos/ordoc-english/) | Aprendizaje de inglés adaptado a la vida real, con IA | Next.js, Firebase, Gemini | Más de 350 | En uso por un hogar pequeño |
| [Aprendiendo con ORDOC](proyectos/ordocedtech/) | Ruta gratuita en español para el examen PL-300 de Power BI | Next.js, Supabase, MDX | Más de 250 | En construcción |
| [FamilyGym](proyectos/familygym/) | Bienestar y movimiento en familia, con gamificación | React, Firebase | Cerca de 500 | En uso por un grupo de familias pequeño |
| [AcademyX](proyectos/academyx/) | Organización escolar familiar con gamificación y asistente de IA | React, Firebase | Sin cifra | En uso por un hogar pequeño |

*Cifras a 12 de noviembre de 2026. Las pruebas se cuentan como casos de prueba escritos en cada repositorio, de forma aproximada. En AcademyX las pruebas usan otro estilo y no se pudieron contar.*

## Medición dentro de cada aplicación

Todas las aplicaciones miden su propio uso. Quien las usa ve su avance en un panel, y en varias el administrador ve cómo se usa el producto, siempre con cifras agregadas.

| Proyecto | Panel para quien la usa | Panel para el administrador |
|---|---|---|
| Cosechas | Análisis de gastos, ingresos, ahorro y patrimonio, y del comportamiento de gasto | Panel de uso: cuántos registros entran, de qué origen y en qué semana, sin leer descripciones, montos ni cuentas |
| Ordoc English | Panel diario, progreso, analítica personal e informe semanal | Métricas de enganche: activos a 7 y 30 días, retención, sesiones, contenido repetido y qué se practica |
| Aprendiendo con ORDOC | Panel de estudio: racha, minutos por semana, precisión por dominio, temas débiles y ritmo frente al plan | Aprobación de contenido e invitaciones; las estadísticas agregadas, con consentimiento, están en preparación |
| FamilyGym | Vitalidad: rachas, check-ins, plan semanal y rango de análisis | Panel de telemetría con eventos que separa la actividad humana de la técnica del sistema |
| AcademyX | Rendimiento por materia, rueda de metas y repaso semanal | Gasto de IA por día, con límites por hijo, por familia y global |

Medir tiene un costo en privacidad, así que cada panel agrega: cuenta eventos y no lee el contenido personal.

## Cómo trabajo

- **Pruebas y control de calidad desde el inicio:** pruebas unitarias, de reglas de seguridad de la base de datos y de navegador, con integración continua donde aplica.
- **Decisiones documentadas:** cada proyecto lleva sus decisiones y límites por escrito, no solo el código.
- **Datos personales:** las apps de uso familiar son privadas y sus datos reales no aparecen aquí. Las capturas son de páginas públicas o de las propias aplicaciones, con los nombres sustituidos y los datos reemplazados por valores ilustrativos.

## Contacto

[Portafolio](https://portfolio-c649d.web.app/) · [LinkedIn](https://www.linkedin.com/in/ordoc/)
