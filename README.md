<div align="center">

# Hola, soy Juan Perdomo 👋
### Desarrollador Backend • Sistemas Embebidos • Infraestructura IT

📍 **Barquisimeto, Venezuela** | 🎓 **TSU en Informática (IUJO — 99/100)** | 🐧 **Linux Enthusiast**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-perdomo-44a196416)
[![Email](https://img.shields.io/badge/Email-Contactar-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jperdomo@proton.me)
[![GitHub](https://img.shields.io/badge/GitHub-jaberus19-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jaberus19)

</div>

---

### 👨‍💻 Sobre mí

Ingeniero de software enfocado en construir **sistemas backend de alto rendimiento**, **firmware de bajo nivel** e **infraestructura tecnológica resiliente**. Disfruto resolver problemas complejos desde el registro del microcontrolador hasta la arquitectura distribuida en el servidor.

- ⚡ **Backend & Concurrencia:** Desarrollo de microservicios asíncronos en **Rust (Actix Web)** y APIs empresariales escalables en **TypeScript / Node.js (NestJS, Express)**.
- 🔌 **Sistemas Embebidos:** Programación *bare-metal* (`no_std`) sobre arquitecturas **ARM Cortex-M** y **STM32**, optimizando memoria y latencia sin sobrecarga de sistema operativo.
- 🛡️ **Infraestructura & Operaciones IT:** Experiencia práctica en administración de redes LAN, auditoría de hardware, automatización con scripts y despliegue de soluciones ITSM (**GLPI**) en entornos institucionales.

---

### 🛠️ Stack Tecnológico

| Área | Tecnologías y Herramientas |
| :--- | :--- |
| **Lenguajes** | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![C/C++](https://img.shields.io/badge/C%2FC++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Backend & APIs** | ![Actix Web](https://img.shields.io/badge/Actix_Web-000000?style=flat-square&logo=rust&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) ![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white) ![Tokio](https://img.shields.io/badge/Tokio_Async-000000?style=flat-square&logo=rust&logoColor=white) |
| **Bases de Datos & Caché** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **Embebidos & Hardware** | ![ARM Cortex-M](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=flat-square&logo=arm&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![OpenOCD](https://img.shields.io/badge/OpenOCD_%2F_GDB-2E3440?style=flat-square&logo=gnu&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) |
| **Sistemas & DevOps** | ![Linux](https://img.shields.io/badge/Manjaro_Linux-35BF5C?style=flat-square&logo=manjaro&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black) |

---

### 🚀 Proyectos Destacados

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/jaberus19/api-actix-web">api-actix-web</a></h4>
      <p>Microservicio asíncrono en <b>Rust</b> para despacho de notificaciones en tiempo real sobre <b>WebSockets</b> en operaciones de autolavado.</p>
      <ul>
        <li>Concurrencia segura con <code>Arc&lt;Mutex&gt;</code> y broadcast segmentado por roles.</li>
        <li>Worker desacoplado en <b>Tokio</b> con polling a <b>PostgreSQL</b> (SQLx) y deduplicación de estados.</li>
      </ul>
      <sub><code>Rust</code> • <code>Actix Web</code> • <code>WebSockets</code> • <code>PostgreSQL</code></sub>
    </td>
    <td width="50%" valign="top">
      <h4>🔌 <a href="https://github.com/jaberus19/rust_embedded_code">rust_embedded_code</a></h4>
      <p>Firmware <i>bare-metal</i> (<code>#![no_std]</code>) en <b>Rust</b> para microcontroladores <b>ARM Cortex-M0+ (STM32L0x1)</b> sin sistema operativo.</p>
      <ul>
        <li>Configuración directa de relojes internos (RCC HSI16) y registros GPIO.</li>
        <li>Optimización binaria con LTO ajustada a 32 KB Flash y 8 KB RAM.</li>
      </ul>
      <sub><code>Rust Embedded</code> • <code>ARM Cortex-M</code> • <code>STM32</code> • <code>OpenOCD</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🏢 <a href="https://github.com/RitoTorri/AquaGlossPro-Backend">AquaGlossPro-Backend</a></h4>
      <p>Backend empresarial modular para gestión operativa y administrativa con persistencia relacional y caché de alta velocidad.</p>
      <ul>
        <li>Arquitectura desacoplada en <b>NestJS 11</b> con <b>TypeORM</b> y <b>PostgreSQL</b>.</li>
        <li>Aceleración de endpoints críticos con <b>Redis</b>, validación DTO y exportación PDF/Excel.</li>
      </ul>
      <sub><code>TypeScript</code> • <code>NestJS</code> • <code>Redis</code> • <code>PostgreSQL</code></sub>
    </td>
    <td width="50%" valign="top">
      <h4>🚛 <a href="https://github.com/RitoTorri/API-Trans-Services">API-Trans-Services</a></h4>
      <p>API REST para control de flota de transporte, liquidación de nóminas y cálculo de retenciones impositivas.</p>
      <ul>
        <li>Modelado relacional en 3FN con <b>Prisma ORM</b> y precisión decimal financiera.</li>
        <li>Seguridad RBAC con <b>JWT</b>, <i>rate-limiting</i> y generación automática de comprobantes PDF.</li>
      </ul>
      <sub><code>Node.js</code> • <code>Express</code> • <code>Prisma</code> • <code>PostgreSQL</code></sub>
    </td>
  </tr>
</table>

---

### 🛡️ Experiencia en Infraestructura & Operaciones IT

**Soporte Técnico e Infraestructura de TI — Gobernación del Estado Lara (OTIC)**
- 🔍 **Auditoría y Diagnóstico:** Automatización de reportes de salud de almacenamiento (métricas S.M.A.R.T.) mediante scripts en **Windows PowerShell**.
- 🌐 **Redes y Servicios:** Administración y verificación de servicios internos en red LAN (HTTP/IIS, FTP) y seguridad de endpoints.
- 📋 **Gestión ITSM:** Evaluación técnica y propuesta de arquitectura para despliegue *On-Premise* de **GLPI** orientado a inventario y mesas de ayuda.

---

<div align="center">

### 📊 Actividad y Métricas en GitHub

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=jaberus19&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jaberus19&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" />

</div>
