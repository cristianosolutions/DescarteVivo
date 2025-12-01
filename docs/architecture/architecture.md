                  ┌──────────────────────────────┐
                  │           Usuários            │
                  │  Web / Mobile / Desktop       │
                  └──────────────┬───────────────┘
                                 │ HTTP / HTTPS
                                 ▼
                     🌐 Frontend (React.js)
                     Interface e lógica de UI
                                 │ Axios
                                 ▼
                    🚀 API REST Backend (Node.js / Express)
             Controllers ─ Services ─ Middleware ─ JWT Auth
                                 │
                                 ▼
                         🗄 PostgreSQL (Railway Cloud)
                           schema.sql / Migrations
                                 │
                                 ▼
                      Deploy Vercel + Railway CD CI
