<p align="center">
  <img src="assets/logo_terra.png" alt="Terra Ecosystem Logo" width="220" />
</p>

<h1 align="center">TERRA ECOSYSTEM</h1>

<p align="center">
  <strong>Infraestructura Efímera, Serverless Nativa y Ecosistema de Computación a Coste Económico $0</strong>
</p>

<p align="center">
  <a href="#-visión-y-filosofía">Visión</a> •
  <a href="#-el-motor-subyacente-github-engine">GitHub Engine</a> •
  <a href="#-las-aplicaciones-del-ecosistema">Apps del Ecosistema</a> •
  <a href="#-hiven-el-agente-cognitivo">Hiven AI</a> •
  <a href="#-hoja-de-ruta">Roadmap</a> •
  <a href="LICENSE">Licencia MIT</a>
</p>

---

## 🌍 Visión y Filosofía

**Terra** no es solo un conjunto de herramientas; es un paradigma de arquitectura y una filosofía de ingeniería de software. Nace como respuesta a los altos costes y la complejidad operativa de la nube moderna.

Su regla inquebrantable es: **Coste económico de infraestructura cero ($0) y mantenimiento nulo**, garantizando siempre una experiencia de usuario fluida, gratuita y libre de dependencias cautivas de terceros.

En Terra, la infraestructura no se alquila ni se mantiene encendida 24/7; **se invoca, se consume y se autodestruye en cuestión de segundos (El Laboratorio Fantasma).**

---

## ⚙️ El Motor Subyacente (GitHub Engine)

Terra transforma de forma legítima y creativa las primitivas gratuitas de la plataforma de GitHub en un motor de computación en la nube:

* **Computación (Compute):** Sustituida por **GitHub Actions**. Ejecuta lógica de negocio, contenedores efímeros y agentes de IA que mueren tras completar su tarea.
* **Almacenamiento y Estado (Storage):** Sustituida por la **Git Database API** y **GitHub Releases**. Los datos y estados se inyectan como JSONs o binarios inmutables sin clonar repositorios completos.
* **Colas y Tareas (Message Brokers):** Sustituidas por **GitHub Issues** y **`repository_dispatch`** para orquestación asíncrona de eventos.
* **Red de Distribución (CDN / Edge):** Sustituida por **GitHub Pages** para servir interfaces, dashboards y escudos perimetrales a escala global.

---

## 🐝 Hiven: El Agente Cognitivo Autónomo

<p align="center">
  <img src="assets/logo_hiven_v2.png" alt="Hiven Agent Logo" width="140" />
</p>

<p align="center">
  <strong>Hiven</strong> es la "Mente Enjambre" y el primer titán activo del ecosistema Terra.
</p>

Es un agente de ingeniería de software autónomo multi-agente (*Swarm*) de código abierto que actúa como un desarrollador Senior 24/7. Lee requerimientos en lenguaje natural, diseña la arquitectura, escribe código, ejecuta pruebas en sandboxes aislados y realiza despliegues/PRs autónomas sin requerir un servidor dedicado.

👉 **Explora el repositorio oficial de Hiven:** [Hiven Public Repository](https://github.com/amglogicalis/hiven-repo-public)

---

## 🗄️ Rolla: Motor de Almacenamiento de Objetos

<p align="center">
  <img src="assets/logo_rolla.png" alt="Rolla Storage Logo" width="140" />
</p>

<p align="center">
  <strong>Rolla</strong> es el almacén de objetos inmutable e ilimitado a coste $0 del ecosistema.
</p>

Permite almacenar e intercambiar archivos de cualquier tamaño mediante **Rolla-Balls** (*Balls*) sobre GitHub Releases, con soporte transparente para fragmentación (*chunking*) de archivos >2GB y distribución perimetral global. Incluye SDK para Node.js/TypeScript, CLI interactiva y consola web nativa.

👉 **Explora el repositorio oficial de Rolla:** [Rolla Public Repository](https://github.com/amglogicalis/rolla-repo-public)

---

## 🌐 Webbl: Motor de Hosting & CDN Global

<p align="center">
  <img src="assets/logo_webbl.png" alt="Webbl Hosting Logo" width="140" onerror="this.src='https://raw.githubusercontent.com/amglogicalis/webbl-repo-public/main/logo_webbl.png'" />
</p>

<p align="center">
  <strong>Webbl</strong> es la infraestructura de alojamiento estático, SPAs y Serverless Morphs del ecosistema Terra a coste $0.
</p>

Permite desplegar proyectos web (Vite, React, Astro, Next.js estático) en **Cocoons** sobre GitHub Pages, ejecutar funciones Serverless (**Async, Build y Hatch Morphs**) y utilizar inteligencia de compilación (**Chrysalis**). Incluye consola web interactiva 24/7 y CLI.

👉 **Explora el repositorio oficial de Webbl:** [Webbl Public Repository](https://github.com/amglogicalis/webbl-repo-public)

---

## 🏛️ Las Aplicaciones del Ecosistema Terra

El ecosistema está compuesto por **21 aplicaciones modulares** («Titanes») que pueden operar de forma aislada o en perfecta sinergia:

| App | Dominio | Estado | Descripción |
| :--- | :--- | :---: | :--- |
| 🐝 **Hiven** | *AI & Logic* | 🟢 **Completado** | Agente cognitivo autónomo y sintetizador de lógica multi-enjambre. |
| 🗄️ **Rolla** | *Object Storage* | 🟢 **Completado** | Motor de almacenamiento de objetos inmutable e ilimitado sobre Rolla-Balls. |
| 🌐 **Webbl** | *Hosting & CDN* | 🟢 **Completado** | Alojamiento frontend estático instantáneo con distribución perimetral (Cocoons, Morphs & Chrysalis). |
| 🏛️ **Combase** | *Base de Datos Efímera* | 🟡 **En Progreso** | Motor transaccional y base de datos estructurada efímera de coste $0. |
| 🔐 **Lumina** | *IAM & Identity* | ⚪ *Planificado* | Proveedor de identidad stateless, Magic Links y emisión de tokens JWT. |
| 🛡️ **Synchlor** | *Gestión de Secretos* | ⚪ *Planificado* | Camuflaje de credenciales y gestión de secretos efímeros. |
| ⏰ **Syncada** | *Orquestación & Crons* | ⚪ *Planificado* | Reloj maestro asíncrono, colas de mensajes y dispatcher de eventos. |
| 🐜 **Formica** | *Event Mesh & Purgado* | ⚪ *Planificado* | Bus de eventos (Pheromones), K/V store (Chambers), telemetría (Foragers) y purgado universal efímero (Legionarys). |
| 🦗 **Grillout** | *Colas & Mensajería* | ⚪ *Planificado* | Motor de colas asíncronas, mensajería y notificaciones efímeras. |
| ⚡ **Pheri** | *Real-Time Streaming* | ⚪ *Planificado* | Tuberías de eventos y streaming de alta frecuencia de coste cero. |
| 🎭 **Ballom** | *DNS & Routing* | ⚪ *Planificado* | Capa de enmascaramiento DNS, routing inteligente y proxy perimetral. |
| 🐝 **MockHive** | *Compute & Serverless* | ⚪ *Planificado* | Entornos efímeros (Hives), funciones serverless (PollenPods) y grafos (Waggles). |
| 🦟 **Maskito** | *Testing & Data* | ⚪ *Planificado* | Motor de pruebas de estrés masivo y siembra sintética de datos. |
| 🕷️ **Termes** | *Scraping & APIs* | ⚪ *Planificado* | Digestor de datos no estructurados, headless browser y generador de APIs sintéticas. |
| 🦎 **Lepisma** | *Salud de Dependencias* | ⚪ *Planificado* | Motor de salud estructural, mapeo de dependencias y anti-decadencia. |
| 🛡️ **Waisp** | *Red Teaming* | ⚪ *Planificado* | Orquestador de seguridad ofensiva y pentesting dinámico (DAST) automatizado. |
| 🦗 **Chiton** | *Gobernanza & FinOps* | ⚪ *Planificado* | Blindaje preventivo de PRs, escaneo de secretos y auditoría multicloud. |
| 🦋 **Decrefly** | *Control Financiero* | ⚪ *Planificado* | Motor de equilibrio activo, techo financiero y arquitectura de suma cero. |
| 📊 **Libella** | *Observabilidad & Telemetría* | ⚪ *Planificado* | Panóptico universal de telemetría, métricas y control de costes efímero. |
| 🧠 **Mantx** | *AutoML & LLMOps* | ⚪ *Planificado* | Arena de batalla de modelos ML/SLM e inferencia predictiva efímera. |
| 🎛️ **Terra Console & Hub** | *Orquestación & Comunidad* | ⚪ *Planificado* | Centro de mando unificado y ecosistema público (Forest, Library, Colony). |

---

## 🚀 Hoja de Ruta de Desarrollo

El criterio de ordenación es sencillo: **no se implementa una herramienta hasta que exista algo que justifique su existencia**. Una herramienta de observabilidad (`Libella`) no tiene sentido antes de que haya apps que observar. Un motor de purgado (`Formica Legionarys`) no tiene sentido antes de que exista infraestructura que purgar.

1. **🧱 Fase 1 — Fundamentos:** `Webbl` ➡️ `Combase` *(almacenamiento, hosting y base de datos)*
2. **🔒 Fase 2 — Identidad & Seguridad:** `Lumina` ➡️ `Synchlor` *(auth y gestión de secretos)*
3. **🔗 Fase 3 — Comunicación & Orquestación:** `Syncada` ➡️ `Formica` ➡️ `Grillout` ➡️ `Pheri` *(sistema nervioso del enjambre)*
4. **🌐 Fase 4 — Red & Compute:** `Ballom` ➡️ `MockHive` *(routing y cómputo efímero)*
5. **🧪 Fase 5 — Testing & Calidad:** `Maskito` ➡️ `Termes` ➡️ `Lepisma` ➡️ `Waisp` *(validación de lo existente)*
6. **🧹 Fase 6 — Gobernanza & Control:** `Chiton` ➡️ `Formica Legionarys` ➡️ `Decrefly` ➡️ `Libella` *(solo útil cuando hay infra activa)*
7. **🧠 Fase 7 — Inteligencia Artificial:** `Mantx` *(capa avanzada sobre infra consolidada)*
8. **🎛️ Fase 8 — Plataforma:** `Terra Console & Hub` *(centro de mando y comunidad)*

---

<p align="center">
  <sub>Desarrollado bajo la filosofía Terra • Infraestructura Efímera de Coste $0</sub>
</p>
