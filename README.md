# notification-service

Microservice de notifications de retard d'emprunt (Node.js, Express).
Fait partie du projet Gestion Bibliothèque : voir le dépôt `gitops-config` pour l'architecture globale.

## Endpoints

- `GET /health` : état du service
- `POST /notifications` : création d'une notification (à venir)
- `GET /notifications` : historique des notifications (à venir)

## Lancement local

```bash
npm install
npm start
```

## Variables d'environnement

- `PORT` : port d'écoute (défaut 3002)
