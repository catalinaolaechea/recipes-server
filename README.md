# EXPRESS REST API recipes
>En este proyecto se construyó el backend de una página para crear recetas.

- autenticaciones via [JWT](https://jwt.io/)
- routes via [express](https://expressjs.com/)
- habilitar peticiones desde otros origenes [cors](https://www.npmjs.com/package/cors#usage)
- hashear contraseñas via [bcryptjs](https://www.npmjs.com/package/bcryptjs)
- almacenamiento de variables de entorno via [ENV](https://www.npmjs.com/package/dotenv)
- mealDB para inspiración [api externa](www.themealdb.com/api/json/v1/1/search.php?s=Arrabiata)
  
## ✅ Endpoints disponibles

| Método | Ruta              | Descripción                |
| ------ | ----------------- | -------------------------- |
| GET    | /auth/register    | registrar nuevo usario     |
| GET    | /auth/login       | log in usuario             |
| POST   | /recipes          | Crear una nueva receta     |
| PUT    | /recipes/:id      | Actualizar una receta      |
| DELETE | /recipes/:id      | Eliminar una receta        |
| GET    | /recipes/:id      | Obtener recetas por ID     |
| GET    | /recipes          | Listar todos los productos |
| GET    | /external-recipes | Listar todos los productos |

---

##comandos:
comandos disponibles en `package.json`
```bash
  node --watch server.js #permite que se escuchen los cambios y se vuelva a correr automaticamente el servidor
  node server.js #correr el servidor
```

## Objetivos 📖
* Consumir una API externa, manejo de rutas, hasheo, nodejs
