# Postman Collection - User Api

## 📋 Descripción
Batería de pruebas que apuntan contra el sitio de prueba https://reqres.in/.

## 🚀 Configuración Rápida

### 1. Importar en Postman
- Descarga los archivos JSON de este repositorio
- En Postman: Import → Selecciona los archivos:
  - `postman/collections/Users_Api.json`
  - `postman/environments/Demo_env.json`

### 2. Configurar Environment
- Selecciona el environment importado en el dropdown superior derecho
- Verifica que las variables estén configuradas correctamente

### 3. Ejecutar requests
- La collection está organizada en carpetas lógicas
- Comienza con LogIn

## 🔧 Variables de Environment
| Variable | Descripción | Valor Ejemplo |
|----------|-------------|---------------|
| `baseUrl` | URL base de la API | 
| `token` | Token de autenticación |


## 📁 Estructura de la Collection
- **Auth**: Requests de autenticación
- **Users**: Operaciones CRUD de usuarios

## 🧪 Tests Incluidos
Cada request incluye tests para validar:
- Status codes
- Response structure


## 💡 Notas Importantes
Respetando las buenas practicas no se subió el valor de la api-key para la variable api_key
en el enviroment, para conseguirla ingresar a https://reqres.in/signup copiar la calve y agregarlo como valor en el 
campo api_key dentro de las variables de entorno.
