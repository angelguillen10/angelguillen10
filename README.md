<div align="center">

# Angel Guillen

**Backend & AI Engineer Sr**

Node.js · TypeScript · NestJS · PostgreSQL · AWS

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/angelguillen10/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:angelguillen4@gmail.com)
[![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white)](https://stackoverflow.com/users/13367726)

</div>

---

## Sobre mí

Ingeniero backend con más de 7 años construyendo sistemas en producción, enfocado hoy en **agentes de IA** e **infraestructura de pagos**.

La mayor parte de mi trabajo reciente vive en repositorios privados: plataformas SaaS multi-tenant, agentes de IA que venden por WhatsApp atendiendo conversaciones reales todos los días, y un hub de pagos que integra cuatro proveedores en tres países. Construyo sistemas que corren solos y me quedo a operarlos.

**Disponible para posiciones de backend e ingeniería de IA, en remoto.**

<div align="center">

[![Contribuciones](https://github-readme-stats.vercel.app/api?username=angelguillen10&show_icons=true&count_private=true&include_all_commits=true&hide=stars,issues&theme=dark&hide_border=true&bg_color=0d1117&title_color=d4823a&icon_color=d4823a&text_color=8f8f8c)](https://github.com/angelguillen10)
[![Racha](https://github-readme-streak-stats.herokuapp.com/?user=angelguillen10&theme=dark&hide_border=true&background=0d1117&ring=d4823a&fire=d4823a&currStreakLabel=d4823a&sideLabels=8f8f8c&dates=5e5e5b)](https://github.com/angelguillen10)

</div>

> El gráfico de contribuciones refleja trabajo mayormente en repositorios privados: unos 290 días activos en el último año sobre proyectos en producción.

---

## Qué construyo

**Agentes de IA para WhatsApp**
Asistentes de venta y atención sobre la API oficial de WhatsApp Business. Responden con el catálogo y los precios reales del negocio, arman el pedido con dirección validada, derivan a una persona cuando la conversación lo necesita, y corren 24/7 en producción. NestJS con Gemini y Claude, sobre PostgreSQL.

**Infraestructura de pagos**
Un hub central que abstrae Mercado Pago, dLocal, Cryptomus y Stripe detrás de una sola API. Webhooks idempotentes, verificación de firma, conciliación, y una única superficie de integración para todos los productos del stack.

**Automatización publicitaria a escala**
Gestión de campañas contra las APIs de Meta Marketing y TikTok Ads: conversiones del servidor con deduplicación, monitoreo de costo por venta, y reglas que reasignan presupuesto y pausan creativos con evidencia estadística suficiente, no por un mal día.

**Plataformas de comercio**
Ecommerce multi-país con pago contra entrega, integración con transportadoras, ciclo de vida del pedido y atribución que sobrevive el camino entre el clic en un anuncio y el paquete entregado.

---

## Cómo trabajo

**Arquitectura hexagonal.** La lógica de dominio es independiente de frameworks y de la entrada y salida. Los adaptadores se reemplazan, el núcleo se testea sin base de datos.

**Explícito antes que implícito.** Tipado de punta a punta. Si algo puede fallar, devuelve un resultado que tengo que manejar.

**Operable desde el diseño.** Logs estructurados, trace IDs entre servicios, auditoría, y alertas que disparan solo donde una persona tiene que decidir algo.

**Infraestructura por código.** Cada entorno reproducible desde un repositorio. Ningún servidor configurado a mano.

---

## Stack

**Backend** · Node.js · NestJS · TypeScript · Express · REST · Webhooks

**Frontend** · Next.js · React · Tailwind CSS

**Datos** · PostgreSQL · Redis · MongoDB · DynamoDB

**Infraestructura** · Docker · AWS · GitHub Actions · nginx

**IA** · Gemini · Claude · SDK de Anthropic · prompt caching · salida estructurada

---

## Experiencia

**Fintech** — detección de fraude, procesos de KYC y procesamiento de pagos en microservicios de alto tráfico.

**Ecommerce** — sistemas de pedidos, inventario y fulfillment en varios países y monedas.

**Producto** — plataformas SaaS llevadas de cero a producción, incluida la operación que las mantiene andando.

---

<details>
<summary><strong>English version</strong></summary>

<br/>

## About

Backend engineer with 7+ years building production systems, currently focused on **AI agents** and **payment infrastructure**.

Most of my recent work lives in private repositories: multi-tenant SaaS platforms, WhatsApp AI sales agents handling real customer conversations at scale, and a payment hub integrating four providers across three countries. I build systems that run unattended and I stay to operate them.

**Open to backend and AI engineering roles — remote.**

## What I build

**AI agents for WhatsApp** — sales and support assistants on the official WhatsApp Business API. They answer from a real product catalog, assemble orders with validated addresses, hand off to humans when needed, and run 24/7 in production.

**Payment infrastructure** — a central hub abstracting Mercado Pago, dLocal, Cryptomus and Stripe behind one API. Idempotent webhooks, signature verification and reconciliation.

**Ad automation at scale** — campaign management against the Meta Marketing and TikTok Ads APIs: server-side conversion tracking with deduplication, cost-per-acquisition monitoring, and budget rules driven by statistical evidence.

**Commerce platforms** — multi-country e-commerce with cash-on-delivery flows, carrier integrations and attribution that survives the gap between an ad click and a delivered package.

## Engineering

**Hexagonal architecture** — domain logic independent of frameworks and I/O. Adapters are replaceable, the core is testable without a database.

**Explicit over implicit** — typed boundaries end to end. If it can fail, it returns a result I have to handle.

**Operable by design** — structured logs, trace IDs across services, audit trails, and alerts that fire on conditions a human should act on.

**Infrastructure as code** — every environment reproducible from a repository.

</details>
