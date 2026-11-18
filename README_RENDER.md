# Déploiement Render

- Runtime Node.js 22
- Build : `npm install`
- Start : `npm start`
- Health check : `/health`
- Variables obligatoires : `TURSO_DATABASE_URL`, `TURSO_AUTH_TOKEN`, `ADMIN_USER`, `ADMIN_PASSWORD`, `SESSION_SECRET`, `PUBLIC_URL`.

Utiliser une base Turso distincte de l'application course d'orientation. Les tables V1 sont créées automatiquement au premier démarrage.
