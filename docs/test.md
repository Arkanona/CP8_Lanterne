## 4 Vérifier l'API déployée

Après avoir effectué le test de `http://localhost:3000/api/health` j'ai obtenu :
```
{
  "status": "ok",
  "environment": "development",
  "version": "1.0.0"
}

```
La méthode HTTP est `GET` le statut attendu est `ok` et celui obtenu est `ok` donc c'est bon.