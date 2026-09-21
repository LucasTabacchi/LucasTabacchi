<h1 align="center">Hola, soy Lucas Tabacchi</h1>
<h3 align="center">Systems Analyst</h3>

<p align="center">
  <img src="assets/hero-systems-analyst.png" width="100%" alt="Lucas Tabacchi — Systems Analyst" />
</p>

<p align="center">
  Me gusta transformar ideas en productos funcionales: desde la interfaz y la experiencia de usuario, hasta el backend, las integraciones y el despliegue.
</p>

<p align="center">
  <a href="https://github.com/LucasTabacchi"><img src="https://img.shields.io/badge/GitHub-Perfil-181717?style=flat-square&logo=github" /></a>
  <a href="https://www.linkedin.com/in/lucas-tabacchi-ab74551a5/"><img src="https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=flat-square&logo=linkedin" /></a>
</p>

## Sobre mí

Soy **Systems Analyst** y me enfoco en transformar ideas en productos digitales funcionales, cuidando todo el recorrido: experiencia de usuario, backend, integraciones y despliegue.

Me interesa construir soluciones end-to-end con especial atención a la **arquitectura**, la **automatización** y una base técnica mantenible.

- ⚙️ **Backend e infraestructura:** APIs, bases de datos, Docker, integraciones y automatizaciones.
- 📱 **Web & Mobile:** Desarrollo aplicaciones web end-to-end con **Next.js, React y TypeScript**, integrando interfaces, backend, autenticación, pagos, CMS, emails y bases de datos. En mobile, construyo aplicaciones multiplataforma con **React Native (Expo)**, navegación tipada, autenticación, mapas, telemetría en tiempo real y soporte offline, integradas con **Supabase, Node.js y arquitecturas orientadas a eventos**.
- 🧩 **En exploración constante:** arquitectura de software, sistemas distribuidos, developer experience y prácticas que mejoran la mantenibilidad y escalabilidad de los productos.

---

## Proyectos que muestran mi perfil

<table>
  <tbody>
    <tr>
      <td width="50%" valign="top">
        <p><a href="https://github.com/LucasTabacchi/autodocker"><strong>🤖 AutoDocker</strong></a></p>
        <p><strong>Dockerización asistida para convertir repositorios en entornos ejecutables y editables.</strong></p>
        <ul>
          <li>Analiza proyectos ZIP o Git y detecta stacks Node, Python, PHP, Java, Go y Ruby, incluso monorepos.</li>
          <li>Genera <code>Dockerfile</code>, <code>.dockerignore</code>, <code>docker-compose</code>, documentación y bootstrap de CI que se pueden editar.</li>
          <li>Valida builds, permite previsualizar resultados y abrir pull requests desde el flujo de trabajo.</li>
        </ul>
        <p><code>Python</code> · <code>Django</code> · <code>DRF</code> · <code>Celery</code> · <code>Redis</code> · <code>PostgreSQL</code> · <code>Docker</code> · <code>GitHub Actions</code></p>
      </td>
      <td width="50%" valign="top">
        <p><a href="https://github.com/LucasTabacchi/project-flow"><strong>📋 ProjectFlow</strong></a></p>
        <p><strong>Gestión colaborativa de proyectos con visibilidad sobre el trabajo, sus dependencias y resultados.</strong></p>
        <ul>
          <li>Organiza equipos con tableros, listas y tarjetas drag-and-drop, fechas límite, bloqueos y actividad.</li>
          <li>Incluye automatizaciones, dependencias, campos personalizados, recurrencias y reportes de tiempo.</li>
          <li>Centraliza invitaciones y notificaciones por email, además de exportaciones CSV y PDF.</li>
        </ul>
        <p><code>Next.js</code> · <code>React</code> · <code>TypeScript</code> · <code>Prisma</code> · <code>PostgreSQL</code> · <code>Tailwind CSS</code> · <code>Zustand</code> · <code>Redis</code></p>
      </td>
    </tr>
    <tr>
      <td width="50%" valign="top">
        <p><a href="https://github.com/LucasTabacchi/frontend-ecommerce-amargo-y-dulce"><strong>🍫 Amargo y Dulce</strong></a></p>
        <p><strong>E-commerce de chocolates diseñado para cubrir el recorrido completo de compra.</strong></p>
        <ul>
          <li>Ofrece catálogo, carrito, checkout, perfil, direcciones, pedidos, promociones, cupones y facturas.</li>
          <li>Integra Mercado Pago y procesa actualizaciones de estado de pedidos mediante webhooks.</li>
          <li>Consume Strapi mediante REST y GraphQL, y utiliza Brevo para emails transaccionales.</li>
        </ul>
        <p><code>Next.js</code> · <code>React</code> · <code>TypeScript</code> · <code>Strapi</code> · <code>GraphQL</code> · <code>Mercado Pago</code> · <code>Tailwind CSS</code> · <code>Zustand</code></p>
      </td>
      <td width="50%" valign="top">
        <p><a href="https://github.com/LucasTabacchi/banking-events-kafka-nextjs"><strong>📨 banking-events-kafka-nextjs</strong></a></p>
        <p><strong>Exploración de flujos basados en eventos con servicios Node, Kafka y una interfaz web.</strong></p>
        <ul>
          <li>Levanta Kafka y Kafka UI mediante Docker Compose para trabajar con brokers y topics configurables por entorno.</li>
          <li>Separa las responsabilidades en servicios <code>api</code>, <code>orchestrator</code> y <code>gateway</code> construidos con Node.js.</li>
          <li>Conecta una aplicación Next.js mediante URLs públicas de API y WebSockets.</li>
        </ul>
        <p><code>Apache Kafka</code> · <code>Docker Compose</code> · <code>Node.js</code> · <code>Next.js</code> · <code>WebSockets</code></p>
      </td>
    </tr>
    <tr>
      <td width="50%" valign="top">
        <p><a href="https://github.com/LucasTabacchi/BDD_NSQL_2026/tree/main/airports-api"><strong>✈️ Airports API</strong></a></p>
        <p><strong>API y visor web para explorar 8.108 aeropuertos mediante búsquedas por cercanía y popularidad.</strong></p>
        <ul>
          <li>Consulta datos de aeropuertos en MongoDB y realiza búsquedas de proximidad con Redis GEO y <code>GEOSEARCH</code>.</li>
          <li>Ordena resultados por popularidad con Redis ZSET y una caché con TTL de un día.</li>
          <li>Combina un backend Node/Express con un visor HTML basado en Leaflet y MarkerCluster, orquestado con Docker Compose.</li>
        </ul>
        <p><code>Node.js</code> · <code>Express</code> · <code>MongoDB</code> · <code>Redis GEO</code> · <code>Leaflet</code> · <code>Docker</code></p>
      </td>
      <td width="50%" valign="top">
        <p><a href="https://github.com/LucasTabacchi/Desarrollo-y-Arquitectura-en-aplicaciones-m-viles---2026/tree/main/tp_3/ibank"><strong>🏦 iBank</strong></a></p>
        <p><strong>Flujo de autenticación móvil bancario con validaciones y recuperación de acceso segura.</strong></p>
        <ul>
          <li>Implementa login con protección contra enumeración de cuentas y registro con reglas de contraseña en tiempo real y confirmación por email.</li>
          <li>Gestiona restablecimiento de contraseña mediante enlaces profundos y sesiones persistentes con AsyncStorage.</li>
          <li>Usa formularios tipados con React Hook Form y Zod, y navegación tipada con Expo Router.</li>
        </ul>
        <p><code>React Native</code> · <code>Expo</code> · <code>TypeScript</code> · <code>Supabase Auth</code> · <code>Zod</code> · <code>Expo Router</code></p>
      </td>
    </tr>
    <tr>
      <td width="50%" valign="top">
        <p><a href="https://github.com/LucasTabacchi/IS2_TPFI"><strong>🧩 IS2_TPFI</strong></a></p>
        <p><strong>Servidor TCP en Python para aplicar patrones de diseño sobre un caso funcional y testeable.</strong></p>
        <ul>
          <li>Implementa un servidor con los patrones Proxy, Singleton y Observer, junto con clientes de suscripción.</li>
          <li>Expone operaciones <code>get</code>, <code>set</code> y <code>list</code> con persistencia intercambiable entre mock JSON y AWS DynamoDB.</li>
          <li>Define framing JSON de 4 bytes y cobertura automatizada con pytest.</li>
        </ul>
        <p><code>Python</code> · <code>TCP Sockets</code> · <code>Design Patterns</code> · <code>AWS DynamoDB</code> · <code>pytest</code> · <code>JSON</code></p>
      </td>
      <td width="50%" valign="top">
        <p><a href="https://github.com/LucasTabacchi/Desarrollo-y-Arquitectura-en-aplicaciones-m-viles---2026/tree/main/tp_5"><strong>📶 Network QoS Monitor</strong></a></p>
        <p><strong>Monitor móvil de calidad de red en tiempo real y mapa personal de cobertura.</strong></p>
        <ul>
          <li>Mide RTT y jitter mediante sondas TCP, junto con throughput de subida y bajada.</li>
          <li>Guarda sesiones y muestras con GPS en SQLite, con exportación de datos en CSV y JSON.</li>
          <li>Integra métricas de señal, RAT y operador con Kotlin TelephonyManager, un backend de benchmark Fastify y pruebas móviles y de integración.</li>
        </ul>
        <p><code>React Native</code> · <code>TypeScript</code> · <code>Kotlin</code> · <code>SQLite</code> · <code>Fastify</code> · <code>Docker</code></p>
      </td>
    </tr>
  </tbody>
</table>

---

## Tecnologías con las que más trabajo

### Lenguajes & Web

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,python,html,css,react,nextjs,nodejs,express" alt="TypeScript, JavaScript, Python, HTML5, CSS3, React, Next.js, Node.js y Express" />
</p>

### Backend & APIs

<p align="center">
  <img src="https://skillicons.dev/icons?i=fastapi,django,strapi" alt="FastAPI, Django y Strapi" />
  <img src="https://img.shields.io/badge/Fastify-202020?style=flat-square&logo=fastify&logoColor=white" alt="Fastify" />
  <img src="https://img.shields.io/badge/Django_REST_Framework-092E20?style=flat-square&logo=django&logoColor=white" alt="Django REST Framework" />
  <img src="https://img.shields.io/badge/REST-005571?style=flat-square" alt="REST" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL" />
</p>

### Mobile

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/Expo_Router-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo Router" />
</p>

### Datos & Cloud

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,sqlite,supabase,prisma,aws" alt="PostgreSQL, MongoDB, Redis, SQLite, Supabase, Prisma y AWS" />
  <img src="https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white" alt="AWS S3" />
</p>

### Infraestructura & Eventos

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kafka,rabbitmq,githubactions" alt="Docker, Apache Kafka, RabbitMQ y GitHub Actions" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Compose" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" alt="Celery" />
</p>

### Calidad, UI & DX

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,tailwind,vite,jest,vitest,pytest,eslint,prettier" alt="Git, Tailwind CSS, Vite, Jest, Vitest, pytest, ESLint y Prettier" />
  <img src="https://img.shields.io/badge/Husky-000000?style=flat-square&logo=husky&logoColor=white" alt="Husky" />
  <img src="https://img.shields.io/badge/lint--staged-4B32C3?style=flat-square" alt="lint-staged" />
  <img src="https://img.shields.io/badge/Commitlint-000000?style=flat-square&logo=commitlint&logoColor=white" alt="Commitlint" />
  <img src="https://img.shields.io/badge/Swagger%20%2F%20OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black" alt="Swagger y OpenAPI" />
  <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square" alt="Zustand" />
  <img src="https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" alt="React Query" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square" alt="Zod" />
  <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white" alt="React Hook Form" />
  <img src="https://img.shields.io/badge/Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white" alt="Radix UI" />
  <img src="https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white" alt="Leaflet" />
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white" alt="Cloudinary" />
</p>

### Datos e IA

<p align="center">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
</p>

---

## En lo que estoy enfocado ahora

- construir productos más sólidos end-to-end
- mejorar arquitectura y mantenibilidad
- seguir creciendo entre producto, backend e infraestructura

---

## Métricas de GitHub & Actividad

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=LucasTabacchi&amp;theme=github_dark" alt="Métricas de GitHub de Lucas Tabacchi" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=LucasTabacchi&amp;theme=github_dark" alt="Gráfico de contribuciones de Lucas Tabacchi durante el último año" />
</p>