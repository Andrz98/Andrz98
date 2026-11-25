# Andrés Guerrero

Software Developer. GIS, sistemas aeronáuticos y arquitectura limpia.

Frontend geoespacial con React, TypeScript y OpenLayers. Backend en Python. Reglas de dominio fuera de la interfaz.

[LinkedIn](https://www.linkedin.com/in/andresguerrero-fullstack/) · [Correo](mailto:andresdgr2898@gmail.com)

&nbsp;

## Trabajo actual

### Alchemy

GIS para planos de obra de telecomunicaciones. Convierte información geoespacial en hojas cartográficas listas para el trabajo técnico.

- Gestión de capas y áreas
- Creación y manipulación de viewports
- Control de escalas
- Distribución del terreno entre hojas

`React` `TypeScript` `OpenLayers`

&nbsp;

### Flight Log System

Registro de vuelo digital para una operación aérea, integrado con AIMS como fuente de información operacional.

El backend en Python es la frontera autoritativa: la comunicación con AIMS, las validaciones y los cálculos críticos no dependen del navegador. Las reglas operacionales se modelan en el dominio, separadas de la interfaz.

Está desarrollado con TDD y diseño por contratos, y documentado para su traslado a un equipo de IT: decisiones técnicas, contratos, responsabilidades del backend y criterios de evolución.

`React` `TypeScript` `Python` `API REST`

Repositorio privado, por tratarse de un sistema de dominio operacional.

&nbsp;

## Proyectos públicos

### [TuttoFatto](https://github.com/Andrz98/ToDoBot)

Bot de Telegram para tareas y recordatorios. Notificaciones programadas con `cron`, persistencia en MongoDB y acceso restringido a usuarios autorizados.

Código organizado por responsabilidad, con pruebas en Vitest y linting con ESLint y Prettier. Más de 480 commits. En funcionamiento: [@tuttofatto_bot](https://t.me/tuttofatto_bot).

`Node.js` `Telegraf` `MongoDB` `Vitest`

&nbsp;

### [Atoms para MQL5](https://github.com/Andrz98/MQL5-InvestBrothers)

Librería modular para Expert Advisors. Cada componente es una clase independiente, sin lógica de estrategia, con interfaz mínima separada de su implementación.

| Módulo | Responsabilidad |
|---|---|
| `Flow` | Detectar la apertura de una nueva vela |
| `Indicators` | Gestionar una media móvil |
| `Risk` | Calcular lotes según riesgo, stop loss y saldo |
| `Trade` | Simplificar órdenes de compra y venta |

`MQL5`

&nbsp;

## Stack

**Frontend** · TypeScript, JavaScript, React, Vite, Tailwind CSS, OpenLayers

**Backend** · Python, FastAPI, Node.js, API REST

**Datos** · Python, Microsoft Fabric, MongoDB

**Calidad** · Vitest, Testing Library, ESLint, TDD

**Herramientas** · Git, GitHub, GitHub Projects

&nbsp;

## Método

Parto del dominio y de sus reglas antes de elegir herramientas. Mantengo límites claros entre frontend, backend y datos, y contratos explícitos entre ellos. Las pruebas protegen el comportamiento que el producto debe conservar. El código debe poder leerse, discutirse y mejorarse sin reconstruir el sistema entero.

Planifico con [GitHub Projects](https://github.com/users/Andrz98/projects/5/views/1) en Kanban: objetivos divididos en issues y subissues, con etiquetas automatizadas y criterios de aceptación ligados a cada entrega.

&nbsp;

---

Si quieres conversar sobre GIS, arquitectura de software, sistemas aeronáuticos o automatización, escríbeme por [LinkedIn](https://www.linkedin.com/in/andresguerrero-fullstack/) o por [correo](mailto:andresdgr2898@gmail.com).
