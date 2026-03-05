# ReqRes API - Colección Postman

Colección Postman para testear la API de ReqRes.in con 26 tests automatizados.

## Endpoints cubiertos

| Método | Endpoint | Descripción | Status esperado |
|---|---|---|---|
| GET | /api/users | Lista de usuarios | 200 |
| GET | /api/users/2 | Usuario específico | 200 |
| GET | /api/users/999 | Usuario inexistente | 404 |
| POST | /api/users | Crear usuario | 201 |
| PUT | /api/users/2 | Actualizar usuario | 200 |
| DELETE | /api/users/2 | Eliminar usuario | 204 |
| POST | /api/login | Login válido | 200 |
| POST | /api/login | Login inválido | 400 |

## Resultados

- ✅ 26 tests pasando
- ❌ 0 tests fallando

## Cómo usar

1. Importa `ReqRes_API.postman_collection.json` en Postman
2. Importa `ReqRes_Dev.postman_environment.json` en Postman
3. Activa el environment **ReqRes Dev**
4. Agrega tu API key en la variable `api_key`
5. Corre la colección con **Collection Runner**
