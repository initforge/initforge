<div align="center">
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
| **Deploy** | `Docker Compose` `GitHub Actions` |


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
| **Deploy** | `Docker Compose` `GitHub Actions` |


</td>
</tr>
</table>


