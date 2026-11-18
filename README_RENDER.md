# Déploiement Render

- Runtime Node.js 22
- Build : `npm install`
- Start : `npm start`
- Health check : `/health`
- Variables obligatoires : `TURSO_DATABASE_URL`, `TURSO_AUTH_TOKEN`, `ADMIN_USER`, `ADMIN_PASSWORD`, `SESSION_SECRET`, `PUBLIC_URL`.

Utiliser une base Turso distincte de l'application course d'orientation. Les tables V1 sont créées automatiquement au premier démarrage.


V1.4 : lors de la création d’un cours, l’enseignant renseigne la durée, le nom de la séance et le circuit. Ces informations sont visibles par l’étudiant après sélection du cours ou lecture du QR code, afin de configurer sa tablette. Les champs sont ajoutés à la table des cours par migration automatique et non destructive.


V1.7 : remplacement du logo Zwift par le logo dédié « Vélo connecté », avec conservation du logo SUAPS côte à côte dans l’en-tête.
