<div align="center">
<td>


![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)


</td>
</tr>
<tr>
<td><b>DevOps</b></td>
<td>


![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)


</td>
</tr>
<tr>
<td><b>AI</b></td>
<td>


![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OCR](https://img.shields.io/badge/OCR-333333?style=flat-square)


</td>
</tr>
</table>


---


### 🚀 Live Projects

<table>
<tr>
<td width="50%">

**[hienchina.com](https://hienchina.com)**

B2B wholesale platform — processing real orders and payments daily in production.

- Decoupled monolith into NestJS API + Next.js frontend — zero deployment failures since migration
- 9 backend modules: orders, inventory, dealer debt, returns, notifications
- Custom JWT auth, atomic transactions, role-based access (Admin/Dealer)
- Automated CI/CD via GitHub Actions to production VPS

| | |
|:--|:--|
| **Frontend** | `Next.js` `Zustand` |
| **Backend** | `NestJS` `Prisma` |
| **Database** | `PostgreSQL` |
| **Deploy** | `Docker Compose` `Nginx` `GitHub Actions` |

</td>
<td width="50%">

**[conhonannhonbinhdinh.vn](https://conhonannhonbinhdinh.vn)**

Real-time multiplayer platform — peak 500+ concurrent connections, live payments via PayOS.

- Atomic transactions + row-level locking to prevent overselling under concurrency
- Idempotent webhook handlers + 15-min auto-expiry CRON for unpaid orders
- Sub-100ms response times via Redis caching layer
- 7-tab admin dashboard: real-time analytics, moderation, regional config

| | |
|:--|:--|
| **Frontend** | `React` `Vite` |
| **Backend** | `Node.js` `Express` `WebSocket` `SSE` |
| **Database** | `PostgreSQL` `Redis` |
| **Deploy** | `Docker Compose` |

</td>
</tr>
</table>

